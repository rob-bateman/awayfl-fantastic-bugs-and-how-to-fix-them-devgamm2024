<script>
  import 'reveal.js/dist/reveal.css';

    import jQuery                 from 'jquery';
    import Reveal            from 'reveal.js';
    import { onMount, tick } from 'svelte';
    import Presentation      from './Presentation.svelte';

    export let app;
    export let reveal;

    onMount(async () => {
        await tick();
        const deck = new Reveal(reveal);
        deck.initialize({
            transition: 'fade',
            controls: false,
            progress: true,
        });

        deck.on('slidechanged', function(event) {
            // var gifAttr = event.currentSlide.getAttribute('data-gif');
            // if (gifAttr && gifAttr === 'repeat') {
            //     var img = event.currentSlide.querySelector('img');
            //     var gif = img.getAttribute('src');

            //     img.setAttribute('src', gif + '?t=' + (new Date().getTime()));

            //     event.currentSlide.getAttribute('data-background-image');
            // }
            var waterAttr = event.currentSlide.getAttribute('data-watermark');

            if (waterAttr) {
                jQuery('.left-watermark').each(function (i, e) {
                    e.style="filter: opacity(1);";
                });
                jQuery('.right-watermark').each(function (i, e) {
                    e.style="filter: opacity(1);";
                });
            } else {
                jQuery('.left-watermark').each(function (i, e) {
                    e.style="filter: opacity(0);";
                });
                jQuery('.right-watermark').each(function (i, e) {
                    e.style="filter: opacity(0);";
                });
            }
        });
      });

//     Reveal.addEventListener( 'ready', function( event ) {
//     var banners = '<div id="banners"><header \/><footer \/><\/div>';
//     $('section').each(function (index, slide ) {
//         if ($(slide).children('section').length == 0) {
//           var bannerText = $(slide).closest('[data-banner]').data('banner');
//           if (bannerText) { 
//             var background = $(slide.slideBackgroundElement);
//             background.append(banners);
//             background.find('header,footer').text(bannerText);
//           }
//         }
//     });
//   });
</script>

<svelte:head>
    <title>{app.name}</title>
</svelte:head>

<div class="reveal">
    <div class="slides">
        <Presentation/>
    </div>
</div>

<div class="left-watermark">
    <img src="assets/TheAwayFoundation_RGB_WhiteText.png" alt="The Away Foundation">
</div>

<div class="right-watermark">
    <img src="assets/awayfl-logo_large_trans_white.png" alt="The Away Foundation">
</div>