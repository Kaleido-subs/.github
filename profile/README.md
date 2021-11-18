<!-- TO-DO: Figure out why <styl> tags don't work -->
<img src="img/misc/hr.png" style="width: auto;">
<p style="text-align: center; margin: 10px;">
    <img src="img/banners/banner.jpg" style="border-radius: 15px"></img>
</p>
<img src="img/misc/hr.png" style="width: auto;">

<h3 align="center">Connect with us!</h3>
<p align="center">
<a href="https://discord.gg/dk7aadV" target="_blank"><img style="display: inline-block; width: 40px; height: auto; margin: 3px;" src="img/icons/discord.png" alt="" /></a>  
<a href="https://kaleido.kageru.moe/" target="_blank"><img style="display: inline-block; width: 40px; height: auto; margin: 3px;" src="img/icons/chrome.png" alt=""/></a>  
<a href="https://twitter.com/kaleidosubs" target="_blank"><img style="display: inline-block; width: 40px; height: auto; margin: 3px;" src="img/icons/twitter.png" alt="" /></a>
</p>

<p align="center">
<img style="display: inline-block; margin: 10px;" src="https://komarev.com/ghpvc/?username=Kaleido-subs&color=fd76aa&label=Views"><img>
</div>
</p>

<img src="img/misc/hr.png" style="width: auto;">

Kaleido is a fansub group aimed at high-quality translation and localisation, alongside high video and typesetting
quality, no matter how long it may take.

Kaleido operates primarily through a freelancer-style system. We have our core members, but also employ other fansubbers
all over to collaborate with us on projects. This opens the doors to both veteren and green fansubbers to try their
hands at projects and create some fansubs.

<img src="img/misc/hr.png" style="width: auto;">

We're also very open to collaborations and open-source fansubbing projects! All our finalised releases will be publicly
available in this organisation, and you are free to create your own copies to build upon them as you'd like. Full
credit is not required, but we would appreciate it!

As these repositories are public, you can leave Issues and Pull Requests to let us know about any problems in our subtitles or send in your own fixes!

Want to work with Kaleido? We can try to work something out! Contact us through <a href=https://discord.gg/dk7aadV target="_blank">Discord</a>,
and if there is staff interest, we can continue talks and see what sprouts out of it!

<img src="img/misc/hr.png" style="width: auto;">

<p align="center">
    <img src="https://raw.githubusercontent.com/Kaleido-subs/.github/30687bc48758ec1468d7794723d6dc41c9aa8c86/github-metrics.svg">
</p>

<!--START_SECTION:activity-->

<!-- TODO: Make deschtimes progress visible here somehow or another? Shinon? -->

<img src="img/misc/hr.png" style="width: auto;">

<h2 align="center"> Frequently Asked Questions</h2>

<details><summary>When will X be done?</summary>
<ul>
    <li>
    We're done when we're done, simple as that really. If you want specific details on what the hold-up may be, please check our <a href="https://kaleido.kageru.moe/" target="_blank">main website</a> for the Deschtimes feed, or feel free to ask in our <a href="https://discord.gg/dk7aadV" target="_blank">Discord server</a> (and if you have the relevant expertise, please do not hesitate to help out!).
    </li>
</ul>
</details>

<details><summary>How do I build your subtitles?</summary>
<ul>
    <li>
    We use a tool called <a href=https://github.com/Myaamori/SubKt target="_blank">SubKt</a> to build all our subtitle scripts. You can build the subtitles by running `./gradlew merge.01` (or other episodes). For muxing, you must make sure the name of the encode you'd like to mux with matches the "premux" property of the project (check `sub.properties`), and then run `./gradlew mux.01`. For further questions, please check out the official <a href="https://github.com/Myaamori/SubKt/tree/master/docs" target="_blank">SubKt documentation</a>.
    </li>
</ul>
</details>

<details><summary>Can I translate your translation into another language?</summary>
<ul>
    <li>
    By all means, please do! Credit would be much appreciated if you make use of our subtitles. You may also want to make sure to update the `sub.properties` before you start building your subtitles.
    </li>
</ul>
</details>

<details><summary>Will you translate X or Y for me?</summary>
<ul>
    <li>
    We do not currently accept specific subbing requests. If you're interested in doing it as a project, we may consider doing it if there's staff interest and you already have some staff of your own.
    </li>
</ul>
</details>
