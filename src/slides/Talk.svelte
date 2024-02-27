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
<section data-watermark="true" data-background="assets/talk_background.png" data-autoslide="500">
    <p style="margin: 0px;">&nbsp;</p>
    <div class="r-stack">
        <img src="assets/when-your-program-runs-without-any-bugs.gif" class="fragment fade-in" data-autoslide="0" alt="When Your Program Runs Without Any Bugs" width="800" height="800">
        
    </div>
    <div class="r-stretch"></div>
</section>

<section data-watermark="true" data-background="assets/talk_background.png" data-autoslide="500" data-auto-animate>
    <div class="r-hstack">
        <img src="assets/awayfl-logo_large_black.png" class="fragment fade-in" alt="AwayFL" width="300" height="300">
    </div>
</section>

<section data-watermark="true" data-background="assets/talk_background.png" data-autoslide="1000" data-auto-animate>
    <div class="r-hstack">
        <img src="assets/awayfl-logo_large_black.png" alt="AwayFL" width="300" height="300">
        <div class="r-vstack">
            <div>
                <p style="padding: 0px 20px 0px 20px; text-align: left;"  class="fragment fade-in" data-autoslide="100">🚀 Open Source</p>
                <p style="padding: 0px 20px 0px 20px; text-align: left;"  class="fragment fade-in" data-autoslide="100">❤️ Apache 2 license</p>
                <p style="padding: 0px 20px 0px 20px; text-align: left;"  class="fragment fade-in" data-autoslide="0">♻️ Active Community</p>
            </div>

            <div class="r-stretch">
        </div>
        <div class="r-stretch">
    </div>
</section>

<section data-watermark="true" data-background="assets/talk_background.png">
    <p style="margin: 0px;">http://awayfl.org</p>
    <div class="r-stack">
        <img src="assets/awayfl_org.png" alt="awayfl.org" width="800" height="1000">
    </div>
    <div class="r-stretch">
    </div>
</section>

<section data-watermark="true" data-background="assets/talk_background.png" data-autoslide="500">
    
    <div class="r-vstack fragment fade-in" data-autoslide="0">
        <h2>Better Questions</h2>
        <img src="assets/deep-thought-h2g2.jpeg" alt="Deep Thought" width="800" height="1000">
    </div>
    <div class="r-stretch">
    </div>
</section>

<section data-watermark="true" data-background="assets/talk_background.png">
    <h2>Playback Bug</h2>
    <div class="r-stack">
        <iframe data-src="http://localhost:80/escaping_the_prison.html" width="750" height="519"></iframe>
    </div>
    <div class="r-stretch">
    </div>
</section>


<!--////////////////////////// REVERSE ENGINEERING //////////////////////////-->
<section data-background="assets/minecraft_computer.jpg" data-background-opacity="0.5">
    <h2>Reverse Engineering</h2>
</section>

<section data-watermark="true" data-background="assets/talk_background.png">
    <div class="r-stack">
        <img src="assets/timeline_impossible_quiz.png" alt="Timeline Impossible Quiz" width="900" height="1000">
    </div>
    <div class="r-stretch">
    </div>
</section>


<section data-watermark="true" data-background="assets/talk_background.png">
    <h2>Timeline Flow</h2>
    <div class="r-hstack gridstyle">
        <div class="r-vstack" style="border-width: 1; border-style: solid; border-color: #e5e7eb;">
            <p class="fragment paragraph-style" data-fragment-index="1">┐</p>
            <p class="fragment paragraph-style" data-fragment-index="2">advanceFrame()</p>
            <p class="fragment paragraph-style" data-fragment-index="3">advanceFrame()</p>
            <p class="fragment paragraph-style" data-fragment-index="4">advanceFrame()</p>
            <p class="fragment paragraph-style" data-fragment-index="5">└</p>
        </div>
        <div class="r-vstack">
            <p class="fragment paragraph-style" data-fragment-index="10">┌</p>
            <p class="fragment paragraph-style" data-fragment-index="9">constructors()</p>
            <p class="fragment paragraph-style" data-fragment-index="8">constructors()</p>
            <p class="fragment paragraph-style" data-fragment-index="7">constructors()</p>
            <p class="fragment paragraph-style" data-fragment-index="6">┘</p>
        </div>
        <div class="r-vstack">
            <p class="fragment paragraph-style" data-fragment-index="11">┐</p>
            <p class="fragment paragraph-style" data-fragment-index="12">executeScript()</p>
            <p class="fragment paragraph-style" data-fragment-index="13">executeScript()</p>
            <p class="fragment paragraph-style" data-fragment-index="14">executeScript()</p>
            <p class="fragment paragraph-style" data-fragment-index="15">└</p>
        </div>
    </div>
</section>

<section data-watermark="true" data-background="assets/talk_background.png">
    <h2>Fancy Pants Adventure</h2>
    <div class="r-stack">
        <iframe data-src="assets/demos/assets/FPAWorld1_sdk/index.html" width="720" height="480"></iframe>
    </div>
    <div class="r-stretch">
    </div>
</section>

<section data-background="assets/gandalf-lofi.gif">
    <h2 class="fragment fade-in" style="padding: 30px;">Money</h2>
    <ul class="bulletstyle">
        <li style="list-style-type: '&#128077';" class="fragment fade-in">Do it for the love</li>
        <li style="list-style-type: '&#128078';"class="fragment fade-in">You are not a charity</li>
        <li style="list-style-type: '&#128073';"class="fragment fade-in">Community follows success</li>
    </ul>
    <audio src="assets/gandalf-lofi.m4a" data-autoplay></audio>
    <div class="r-stretch">
    </div>
</section>

<!--////////////////////////// LANGUAGES //////////////////////////-->
<section data-background="assets/matrix_code.jpg" data-background-opacity="0.5">
    <h2>Languages</h2>
</section>

<section data-watermark="true" data-background="assets/talk_background.png">
    <div class="r-stack" style="margin: 0px 0px 20px 0px;">
        <img src="assets/gandalf_vs_balrog_sd.jpg" alt="Gandalf vs Balrog" width="900" height="1000">
        <div class="r-vstack">
            <h1 style="margin: 0px 0px 80px 0px;color: #000;font-size: 340px !important;">as3</h1>
            <h2 style="margin: 0px 0px 0px 0px;font-size: 30px !important;">as2</h2>
        </div>
    </div>
    <h3 class="fragment">Interpreted vs Compiled</h3>
</section>

<section data-watermark="true" data-background="assets/talk_background.png" data-auto-animate>
    <div>
        <table width="100%">
            <thead>
                <tr>
                    <th><h3>interpreted</h3></th>
                    <th><h3 class="fragment" data-fragment-index="7">jit</h3></th>
                    <th><h3>compiled</h3></th>
                </tr>
            </thead>
            <tbody>
                <tr>
                    <td class="fragment" data-fragment-index="1">Python</td>
                    <td class="fragment" data-fragment-index="8">Java</td>
                    <td class="fragment" data-fragment-index="4">C / C++</td>
                </tr>
                <tr>
                    <td class="fragment" data-fragment-index="2">Lua</td>
                    <td class="fragment" data-fragment-index="9">C#</td>
                    <td class="fragment" data-fragment-index="5">Rust</td>
                </tr>
                <tr>
                    <td class="fragment" data-fragment-index="3">AS2</td>
                    <td class="fragment" data-fragment-index="10">AS3</td>
                    <td class="fragment" data-fragment-index="6">Zig</td>
                </tr>
            </tbody>
        </table>
        <p style="margin:20px 0px 0px 80px;text-shadow: #FC0 1px 0 10px !important;" class="fragment" data-fragment-index="11">Javascript</p>
    </div>
</section>

<section data-watermark="true" data-background="assets/talk_background.png">
    <div style="margin:0px 180px 0px 180px;">
        <p style="text-align: justify;">"Javascript should not be the last programming language. Think of the children!"</p>
        <p style="text-align: right;">- Douglas Crockford</p>
    </div>
</section>

<section data-watermark="true" data-background="assets/talk_background.png">
    <div class="r-stack">
            <img src="assets/pngwing.com.png" alt="Swiss Army Knife" width="700" height="1000">
        <div>
            <h2 style="margin:180px 0px 0px 0px;">eval()</h2>
        </div>
    </div>
</section>

<section data-watermark="true" data-background="assets/talk_background.png">
    <h2>awayfl jit</h2>
    <p class="fragment" style="margin:0px 0px 0px 0px;" data-autoslide="50">SWF</p>
    <p class="fragment" style="margin:0px 0px 0px 0px;" data-autoslide="50">↓</p>
    <p class="fragment" style="margin:0px 0px 0px 0px;" data-autoslide="50">Actionscript Byte Code</p>
    <p class="fragment" style="margin:0px 0px 0px 0px;" data-autoslide="50">↓</p>
    <p class="fragment" style="margin:0px 0px 0px 0px;" data-autoslide="50">Javascript</p>
    <p class="fragment" style="margin:0px 0px 0px 0px;" data-autoslide="50">↓</p>
    <p class="fragment" style="margin:0px 0px 0px 0px;" data-autoslide="50">JIT</p>
    <p class="fragment" style="margin:0px 0px 0px 0px;" data-autoslide="50">↓</p>
    <p class="fragment" style="margin:0px 0px 0px 0px;">x86 / ARM</p>
    <div class="r-stretch">
        
    </div>
</section>

<section data-watermark="true" data-background="assets/talk_background.png">
    <h2>Bad Ice Cream</h2>
    <div class="r-stack">
        <iframe data-src="assets/demos/assets/bad-ice-cream/index.html" width="550" height="550"></iframe>
    </div>
    <div class="r-stretch">
    </div>
</section>

<!--////////////////////////// BUGS //////////////////////////-->
<!--//
<section data-background="assets/Bugs-life6.webp" data-background-opacity="0.5">
    <h2>Bugs</h2>
</section>
//-->
<section data-background="assets/gandalf-lofi.gif">
    <h2 class="fragment fade-in" style="padding: 30px;">Bugs</h2>
    <ul class="bulletstyle">
        <li style="list-style-type: '&#128077';" class="fragment fade-in">Minimise your test loop</li>
        <li style="list-style-type: '&#128077';"class="fragment fade-in">Fix, don't patch!</li>
        <li style="list-style-type: '&#128073';"class="fragment fade-in">Unit tests help refactoring</li>
    </ul>
    <audio src="assets/gandalf-lofi.m4a" data-autoplay></audio>
    <div class="r-stretch">
    </div>
</section>
<!--//
<section data-watermark="true" data-background="assets/talk_background.png">
    <h2>Poki</h2>
    <div class="r-stack">
        <iframe data-src="assets/demos/assets/papa_freezeria_sdk/index.html" width="700" height="525"></iframe>
    </div>
    <div class="r-stretch">
    </div>
</section>
//-->
<section data-watermark="true" data-background="assets/talk_background.png">
    <h2>Coolmath Games</h2>
    <div class="r-stack">
        <iframe data-src="assets/demos/jacksmith_sdk.html" width="700" height="525"></iframe>
    </div>
    <div class="r-stretch">
    </div>
</section>