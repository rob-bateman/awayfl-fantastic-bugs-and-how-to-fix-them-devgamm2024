<!--
<script>
 import Notes from '../lib/Notes.svelte';
 import Youtube from '../lib/Youtube.svelte';

</script>

<section data-background="assets/talk_background.png">
    <h2>Getting Started</h2>
    <ul>
        <li class="fragment fade-up">Configure your Presentation in <code>config.js</code></li>
        <li class="fragment fade-up">Create your Slides in <code>src/slides</code></li>
        <li class="fragment fade-up">Add your Slides in <code>Presentation.svelte</code></li>
    </ul>
		<div class="grid place-items-center">
				<Youtube url="https://www.youtube.com/watch?v=xcDUpe1NfCQ"/>
		</div>
		<Notes>This is an example of slide notes</Notes>
</section>
//-->
<!--////////////////////////// INTRODUCTION //////////////////////////-->
<section data-watermark="true" data-background="assets/talk_background.png" data-autoslide="500">
    <p style="margin: 0px;">&nbsp;</p>
    <div class="r-stack">
        <img src="assets/when-your-program-runs-without-any-bugs.gif" class="fragment fade-in" data-autoslide="0" alt="When Your Program Runs Without Any Bugs" width="800" height="800">
        
    </div>
    <div class="r-stretch"></div>
</section>

<section data-watermark="true" data-background="assets/talk_background.png" data-auto-animate>
    <h2>Flash&nbsp;&nbsp;Emulator</h2>
    <p style="margin: 0px;">&nbsp;</p>
    <div class="r-hstack">
        <img src="assets/awayfl-logo_large_black.png" alt="AwayFL" width="300" height="300">
    </div>
    <div class="r-stretch"></div>
</section>

<section data-watermark="true" data-background="assets/talk_background.png" data-autoslide="1000" data-auto-animate>
    <h2>Flash&nbsp;&nbsp;Emulator</h2>
    <p style="margin: 0px;">&nbsp;</p>
    <div class="r-hstack">
        <img src="assets/awayfl-logo_large_black.png" alt="AwayFL" width="300" height="300">
        <div class="r-vstack">
            <div>
                <p style="padding: 0px 20px 0px 20px; text-align: left;" class="fragment fade-in" data-autoslide="100">🚀 Open Source</p>
                <p style="padding: 0px 20px 0px 20px; text-align: left;" class="fragment fade-in" data-autoslide="100">❤️ Apache 2 license</p>
                <p style="padding: 0px 20px 0px 20px; text-align: left;" class="fragment fade-in" data-autoslide="0">♻️ Active Community</p>
            </div>
        </div>
    </div>
    <div class="r-stretch"></div>
</section>

<section data-watermark="true" data-background="assets/talk_background.png">
    <p style="margin: 0px;">http://awayfl.org</p>
    <div class="r-stack">
        <img src="assets/awayfl_org.png" alt="awayfl.org" width="800" height="1000">
    </div>
    <div class="r-stretch">
    </div>
</section>

<section data-watermark="true" data-background="assets/talk_background.png">
    <div class="r-stack">
        <iframe data-src="http://localhost/CM2wonderputt-NoSiteLock.html" width="750" height="650"></iframe>
    </div>
    <div class="r-stretch">
    </div>
</section>

<!--

<section data-watermark="true" data-background="assets/talk_background.png">
    <h2>Poki - Flipline Games</h2>
    <div class="r-stack">
        <iframe data-src="http://localhost/papa_freezeria_sdk.html" width="700" height="525"></iframe>
    </div>
    <div class="r-stretch">
    </div>
</section>
-->

<section data-background="assets/Bugs-life6.webp" data-background-opacity="0.5">
    <h2>Bugs</h2>
</section>

<section data-watermark="true" data-background="assets/talk_background.png">
    <h2 style="padding: 10px; margin: 0px;">Bug Types</h2>
    <ul class="bulletstyle">
        <li style="list-style-type: '&#129419';">Syntax</li>
        <li style="list-style-type: '&#128027';">Implementation</li>
        <li style="list-style-type: '&#129439';">Data Flow</li>
        <li style="list-style-type: '&#129440';">Deployment</li>
        <li style="list-style-type: '&#128009';">Memory</li>
        <li style="list-style-type: '&#128025';" class="fragment fade-in">Mandelbug</li>
        <li style="list-style-type: '&#128165';" class="fragment fade-in">Heisenbug</li>
    </ul>
    <div class="r-stretch">
    </div>
</section>

<!--////////////////////////// EXAMPLES //////////////////////////-->
<section data-watermark="true" data-background="assets/talk_background.png">
    <h2 style="padding: 10px; margin: 0px;">Stack Trace</h2>
    <div class="r-stack">
        <img src="assets/10.png" alt="Stack trace" width="800" height="800">
    </div>
    <div class="r-stretch">
    </div>
</section>

<section data-watermark="true" data-background="assets/talk_background.png">
    <h2 style="padding: 10px; margin: 0px;">Testing</h2>
    <div class="r-stack">
        <img src="assets/StressTesting-Thanos.jpeg" alt="Tests" width="700" height="700">
    </div>
    <div class="r-stretch"></div>
</section>

<section data-watermark="true" data-background="assets/talk_background.png">
    <h2 style="padding: 10px; margin: 0px;">Escaping the Prison</h2>
    <div class="r-stack">
        <iframe data-src="http://localhost/escaping_the_prison.html" width="750" height="519"></iframe>
    </div>
    <div class="r-stretch">
    </div>
</section>

<section data-watermark="true" data-background="assets/talk_background.png">
    <p style="margin: 0px;">&nbsp;</p>
    <div class="r-stack">
        <img src="assets/timeline_impossible_quiz.png" alt="Timeline Impossible Quiz" width="900" height="1000">
    </div>
    <div class="r-stretch">
    </div>
</section>

<section data-watermark="true" data-background="assets/talk_background.png">
    <h2 style="padding: 10px; margin: 0px;">Escaping the Prison</h2>
    <div class="r-stack">
        <iframe data-src="http://localhost/escaping_the_prison.html" width="750" height="519"></iframe>
    </div>
    <div class="r-stretch">
    </div>
</section>

<section data-background="assets/BBCp.gif" data-background-opacity="0.5">
    <h2>Reduce Your Test Loop</h2>
</section>

<section data-watermark="true" data-background="assets/talk_background.png">
    <h2>Isolated Tests</h2>
    <div class="r-vstack">
        <div class="r-hstack">
            <iframe data-src="http://localhost/animationTest.html" width="350" height="250" style="padding: 10px;"></iframe>
            <iframe data-src="http://localhost/BitmapDataMCDraw.html" width="350" height="250" style="padding: 10px;"></iframe>
        </div>
        <div class="r-hstack">
            <iframe data-src="http://localhost/cauldronMask.html" width="350" height="250" style="padding: 10px;"></iframe>
            <iframe data-src="http://localhost/disposeTest.html" width="350" height="250" style="padding: 10px;"></iframe>
        </div>
    </div>
    <div class="r-stretch">
    </div>
</section>

<section data-watermark="true" data-background="assets/talk_background.png">
    <h2>Bloons</h2>
    <div class="r-stack">
        <iframe data-src="http://localhost/assets/bloonstd_dec_v3/index.html" width="700" height="525"></iframe>
    </div>
    <div class="r-stretch">
    </div>
</section>

<section data-watermark="true" data-background="assets/talk_background.png">
    <h2>Bloons</h2>
    <div class="r-stack">
        <iframe data-src="http://localhost/AS2Sound_Test.html" width="700" height="525"></iframe>
    </div>
    <div class="r-stretch">
    </div>
</section>

<section data-watermark="true" data-background="assets/talk_background.png">
    
    <div class="r-vstack">
        <h2 style="padding: 10px; margin: 0px;">Better Questions</h2>
            <img src="assets/deep-thought-h2g2.jpeg" alt="Deep Thought" width="800" height="400">
            <p style="font-size: 30px; font-style: italic; width: 600px; margin: 0px">"Once you know what the question actually is, you'll know what the answer means"</p>
    </div>
    <div class="r-stretch">
    </div>
</section>

<!--
<section data-background="assets/wonderputt_start_crop.png" data-background-opacity="0.5">
    <h2>Optimisation</h2>
</section>


<section data-watermark="true" data-background="assets/talk_background.png">
    <h2 style="margin: 0px;">Wonderputt</h2>
    <div class="r-stack">
        <iframe data-src="http://localhost/CM2wonderputt-NoSiteLock.html" width="750" height="650"></iframe>
    </div>
    <div class="r-stretch">
    </div>
</section>

<section data-watermark="true" data-background="assets/talk_background.png" data-auto-animate>
    <h2>Rendering</h2>
    <div class="r-vstack">
            <p class="fragment fade-in">MouseEvent / KeyBoardEvent</p>
            <p class="fragment fade-in" data-autoslide="50">↓</p>
            <p class="fragment fade-in" data-autoslide="0">event.updateAfterEvent()</p>
            <p class="fragment fade-in" data-autoslide="50">↓</p>
            <p class="fragment fade-in" data-autoslide="0">render()</p>
    </div>
    <div class="r-stretch">
    </div>
</section>

<section data-watermark="true" data-background="assets/talk_background.png" data-auto-animate>
    <h2>Rendering</h2>
    <div class="r-vstack">
            <p>MouseEvent / KeyBoardEvent</p>
            <p>↓</p>
            <p>event.updateAfterEvent()</p>
            <p data-autoslide="50">↓</p>
            <p>renderFlag = true</p>
    </div>
    <div class="r-stretch">
    </div>
</section>-->
<!--////////////////////////// BUGS //////////////////////////-->
<!--//
<section data-background="assets/Bugs-life6.webp" data-background-opacity="0.5">
    <h2>Bugs</h2>
</section>
//-->
<!--//
<section data-watermark="true" data-background="assets/talk_background.png">
    <h2>Poki</h2>
    <div class="r-stack">
        <iframe data-src="http://localhost/assets/papa_freezeria_sdk/index.html" width="700" height="525"></iframe>
    </div>
    <div class="r-stretch">
    </div>
</section>
//-->

<section data-watermark="true" data-background="assets/talk_background.png">
    <h2 style="padding: 10px; margin: 0px;">Final Thoughts</h2>
    <ul class="bulletstyle">
        <li style="list-style-type: '&#128077';" class="fragment fade-in">Use strong types</li>
        <li style="list-style-type: '&#128076';" class="fragment fade-in">Have (some) automated tests</li>
        <li style="list-style-type: '&#129305';" class="fragment fade-in">Reduce your test loop</li>
        <li style="list-style-type: '&#129304';" class="fragment fade-in">Ask better questions</li>
        <li style="list-style-type: '&#9996';" class="fragment fade-in">Don't get too hung up</li>
        <li style="list-style-type: '&#129302';" class="fragment fade-in">Let the AI do it</li>
    </ul>
    <div class="r-stretch">
    </div>
</section>

<section data-watermark="true" data-background="assets/talk_background.png">
    <h2>Solving > Patching</h2>
</section>