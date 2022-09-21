## Fontbakery report

Fontbakery version: 0.8.10

<details><summary><b>[9] NotoSansInscriptionalParthian-Regular.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Check that texts shape as per expectation (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Shaping Checks>.html#com.google.fonts/check/shaping/regression">com.google.fonts/check/shaping/regression</a>)</summary><div>


* 🔥 **FAIL** qa/shaping_tests/inscriptional-parthian.json: Expected and actual shaping not matching
<div class="shaping">


<style type="text/css">
    @font-face {font-family: "TestFont"; src: url(../../fonts/NotoSansInscriptionalParthian/googlefonts/ttf/NotoSansInscriptionalParthian-Regular.ttf);}
    .tf { font-family: "TestFont"; }
    .shaping pre { font-size: 1.2rem; }
    .shaping li {
        font-size: 1.2rem;
        border-top: 1px solid #ddd;
        padding: 12px;
        margin-top: 12px;
    }
    .shaping-svg {
        height: 100px;
        margin: 10px;
        transform: matrix(1, 0, 0, -1, 0, 0);
    }
</style>

<h4>qa/shaping_tests/inscriptional-parthian.json: Expected and actual shaping not matching</h4>


</div>
<div class="shaping">

<li>Shaping did not match: <span class="tf">𐭍𐭆𐭇</span> (Issue #1)</li>


<pre>Expected: u10B47=2+832|u10B46=1+328|u10B4D.alt01=0+299</pre>



<pre>Got     : u10B47=2+832|u10B46=1@381,0+709|u10B4D.alt01=0+299</pre>



<pre>                               ^ +
</pre>


Got: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 1840 2370" transform="matrix(1 0 0 -1 0 0)">
<path d="M10.0,-10.0L10.0,64.0Q48.0,64.0 86.5,84.0Q125.0,104.0 159.0,136.0Q193.0,168.0 218.0,204.0Q261.0,267.0 284.5,352.5Q308.0,438.0 308.0,536.0L396.0,536.0Q397.0,459.0 411.0,382.0Q425.0,305.0 453.5,239.5Q482.0,174.0 528.0,131.0Q558.0,103.0 590.5,88.5Q623.0,74.0 659.0,74.0L659.0,536.0L747.0,536.0L747.0,0.0L660.0,0.0Q541.0,0.0 458.0,83.0Q415.0,126.0 389.0,181.0Q363.0,236.0 352.0,304.0Q325.0,195.0 239.0,104.0Q209.0,72.0 170.5,46.0Q132.0,20.0 91.0,5.0Q50.0,-10.0 10.0,-10.0Z"  transform="translate(0, 801)"/>
<path d="M106.0,-10.0Q88.0,-10.0 62.0,-6.5Q36.0,-3.0 19.0,2.0L19.0,76.0Q46.0,64.0 92.0,64.0Q123.0,64.0 140.5,82.5Q158.0,101.0 158.0,131.0Q158.0,165.0 145.0,197.5Q132.0,230.0 119.0,261.0Q106.0,292.0 106.0,320.0Q106.0,426.0 224.0,546.0L290.0,491.0Q247.0,451.0 220.5,412.0Q194.0,373.0 194.0,322.0Q194.0,296.0 207.0,268.0Q220.0,240.0 233.0,207.0Q246.0,174.0 246.0,132.0Q246.0,68.0 208.5,29.0Q171.0,-10.0 106.0,-10.0Z"  transform="translate(1213, 801)"/>
<path d="M-657.0,-166.0L-657.0,-92.0L126.0,-92.0L126.0,536.0L214.0,536.0L214.0,-166.0L-657.0,-166.0Z"  transform="translate(1541, 801)"/>
</svg>
 Expected: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 1459 2370" transform="matrix(1 0 0 -1 0 0)">
<path d="M10.0,-10.0L10.0,64.0Q48.0,64.0 86.5,84.0Q125.0,104.0 159.0,136.0Q193.0,168.0 218.0,204.0Q261.0,267.0 284.5,352.5Q308.0,438.0 308.0,536.0L396.0,536.0Q397.0,459.0 411.0,382.0Q425.0,305.0 453.5,239.5Q482.0,174.0 528.0,131.0Q558.0,103.0 590.5,88.5Q623.0,74.0 659.0,74.0L659.0,536.0L747.0,536.0L747.0,0.0L660.0,0.0Q541.0,0.0 458.0,83.0Q415.0,126.0 389.0,181.0Q363.0,236.0 352.0,304.0Q325.0,195.0 239.0,104.0Q209.0,72.0 170.5,46.0Q132.0,20.0 91.0,5.0Q50.0,-10.0 10.0,-10.0Z"  transform="translate(0, 801)"/>
<path d="M106.0,-10.0Q88.0,-10.0 62.0,-6.5Q36.0,-3.0 19.0,2.0L19.0,76.0Q46.0,64.0 92.0,64.0Q123.0,64.0 140.5,82.5Q158.0,101.0 158.0,131.0Q158.0,165.0 145.0,197.5Q132.0,230.0 119.0,261.0Q106.0,292.0 106.0,320.0Q106.0,426.0 224.0,546.0L290.0,491.0Q247.0,451.0 220.5,412.0Q194.0,373.0 194.0,322.0Q194.0,296.0 207.0,268.0Q220.0,240.0 233.0,207.0Q246.0,174.0 246.0,132.0Q246.0,68.0 208.5,29.0Q171.0,-10.0 106.0,-10.0Z"  transform="translate(832, 801)"/>
<path d="M-657.0,-166.0L-657.0,-92.0L126.0,-92.0L126.0,536.0L214.0,536.0L214.0,-166.0L-657.0,-166.0Z"  transform="translate(1160, 801)"/>
</svg>


</div>
<div class="shaping">

<li>Shaping did not match: <span class="tf">𐭍𐭂𐭅𐭑𐭂𐭅𐭍𐭍𐭂</span> (Issue #2)</li>


<pre>Expected: u10B42=8+605|u10B4D10B4D=6+521|u10B4210B45=4+951|u10B51.alt01=3+596|u10B4210B45=1+951|u10B4D.alt01=0+299</pre>



<pre>Got     : u10B42=8@112,0+717|u10B4D10B4D=6+521|u10B4210B45=4+951|u10B51.alt01=3+596|u10B4210B45=1@112,0+1063|u10B4D.alt01=0+299</pre>



<pre>                  ^^ ^                                                                     ^^^
</pre>


Got: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 4147 2370" transform="matrix(1 0 0 -1 0 0)">
<path d="M15.0,-10.0L15.0,64.0Q183.0,64.0 300.0,154.0Q416.0,245.0 458.0,401.0Q349.0,301.0 201.0,301.0Q133.0,301.0 84.5,322.0Q36.0,343.0 0.0,396.0L61.0,446.0Q87.0,406.0 121.5,391.0Q156.0,376.0 201.0,376.0Q383.0,376.0 486.0,536.0L563.0,536.0Q556.0,375.0 486.0,248.0Q417.0,122.0 300.0,56.0Q183.0,-10.0 31.0,-10.0L15.0,-10.0Z"  transform="translate(112, 801)"/>
<path d="M-505.0,-301.0L-505.0,-227.0L348.0,-227.0L348.0,536.0L436.0,536.0L436.0,-301.0L-505.0,-301.0ZM-505.0,-166.0L-505.0,-92.0L107.0,-92.0L107.0,536.0L195.0,536.0L195.0,-166.0L-505.0,-166.0Z"  transform="translate(717, 801)"/>
<path d="M391.0,-10.0Q227.0,-10.0 133.0,61.5Q39.0,133.0 39.0,274.0Q39.0,325.0 63.0,366.5Q87.0,408.0 128.5,433.0Q170.0,458.0 220.0,458.0Q282.0,458.0 321.5,432.5Q361.0,407.0 380.0,366.5Q399.0,326.0 399.0,279.0Q399.0,231.0 383.5,191.5Q368.0,152.0 344.5,122.0Q321.0,92.0 296.0,72.0Q317.0,68.0 340.5,66.0Q364.0,64.0 391.0,64.0Q504.0,64.0 586.5,107.5Q669.0,151.0 723.0,227.5Q777.0,304.0 804.0,401.0Q695.0,301.0 547.0,301.0Q500.0,301.0 464.0,310.0L491.0,382.0Q517.0,376.0 547.0,376.0Q729.0,376.0 832.0,536.0L909.0,536.0Q903.0,428.0 870.5,329.5Q838.0,231.0 776.0,154.5Q714.0,78.0 618.5,34.0Q523.0,-10.0 391.0,-10.0ZM208.0,106.0Q254.0,136.0 281.5,180.5Q309.0,225.0 309.0,280.0Q309.0,330.0 285.0,357.0Q261.0,384.0 222.0,384.0Q182.0,384.0 156.0,352.5Q130.0,321.0 130.0,273.0Q130.0,218.0 149.0,176.0Q168.0,134.0 208.0,106.0Z"  transform="translate(1238, 801)"/>
<path d="M-581.0,-240.0L-581.0,-166.0L-125.0,-166.0Q-47.0,-166.0 -2.0,-126.0Q43.0,-86.0 61.0,4.0L166.0,536.0L256.0,536.0L301.0,409.0Q316.0,367.0 330.0,342.0Q344.0,317.0 364.5,306.0Q385.0,295.0 419.0,295.0Q407.0,328.0 407.0,396.0L407.0,536.0L495.0,536.0L495.0,395.0Q495.0,358.0 499.5,329.5Q504.0,301.0 515.5,275.0Q527.0,249.0 547.0,217.0L422.0,217.0Q362.0,217.0 324.5,232.5Q287.0,248.0 263.0,284.5Q239.0,321.0 221.0,382.0L148.0,0.0Q132.0,-86.0 99.0,-139.0Q66.0,-192.0 11.5,-216.0Q-43.0,-240.0 -125.0,-240.0L-581.0,-240.0Z"  transform="translate(2189, 801)"/>
<path d="M391.0,-10.0Q227.0,-10.0 133.0,61.5Q39.0,133.0 39.0,274.0Q39.0,325.0 63.0,366.5Q87.0,408.0 128.5,433.0Q170.0,458.0 220.0,458.0Q282.0,458.0 321.5,432.5Q361.0,407.0 380.0,366.5Q399.0,326.0 399.0,279.0Q399.0,231.0 383.5,191.5Q368.0,152.0 344.5,122.0Q321.0,92.0 296.0,72.0Q317.0,68.0 340.5,66.0Q364.0,64.0 391.0,64.0Q504.0,64.0 586.5,107.5Q669.0,151.0 723.0,227.5Q777.0,304.0 804.0,401.0Q695.0,301.0 547.0,301.0Q500.0,301.0 464.0,310.0L491.0,382.0Q517.0,376.0 547.0,376.0Q729.0,376.0 832.0,536.0L909.0,536.0Q903.0,428.0 870.5,329.5Q838.0,231.0 776.0,154.5Q714.0,78.0 618.5,34.0Q523.0,-10.0 391.0,-10.0ZM208.0,106.0Q254.0,136.0 281.5,180.5Q309.0,225.0 309.0,280.0Q309.0,330.0 285.0,357.0Q261.0,384.0 222.0,384.0Q182.0,384.0 156.0,352.5Q130.0,321.0 130.0,273.0Q130.0,218.0 149.0,176.0Q168.0,134.0 208.0,106.0Z"  transform="translate(2897, 801)"/>
<path d="M-657.0,-166.0L-657.0,-92.0L126.0,-92.0L126.0,536.0L214.0,536.0L214.0,-166.0L-657.0,-166.0Z"  transform="translate(3848, 801)"/>
</svg>
 Expected: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 3923 2370" transform="matrix(1 0 0 -1 0 0)">
<path d="M15.0,-10.0L15.0,64.0Q183.0,64.0 300.0,154.0Q416.0,245.0 458.0,401.0Q349.0,301.0 201.0,301.0Q133.0,301.0 84.5,322.0Q36.0,343.0 0.0,396.0L61.0,446.0Q87.0,406.0 121.5,391.0Q156.0,376.0 201.0,376.0Q383.0,376.0 486.0,536.0L563.0,536.0Q556.0,375.0 486.0,248.0Q417.0,122.0 300.0,56.0Q183.0,-10.0 31.0,-10.0L15.0,-10.0Z"  transform="translate(0, 801)"/>
<path d="M-505.0,-301.0L-505.0,-227.0L348.0,-227.0L348.0,536.0L436.0,536.0L436.0,-301.0L-505.0,-301.0ZM-505.0,-166.0L-505.0,-92.0L107.0,-92.0L107.0,536.0L195.0,536.0L195.0,-166.0L-505.0,-166.0Z"  transform="translate(605, 801)"/>
<path d="M391.0,-10.0Q227.0,-10.0 133.0,61.5Q39.0,133.0 39.0,274.0Q39.0,325.0 63.0,366.5Q87.0,408.0 128.5,433.0Q170.0,458.0 220.0,458.0Q282.0,458.0 321.5,432.5Q361.0,407.0 380.0,366.5Q399.0,326.0 399.0,279.0Q399.0,231.0 383.5,191.5Q368.0,152.0 344.5,122.0Q321.0,92.0 296.0,72.0Q317.0,68.0 340.5,66.0Q364.0,64.0 391.0,64.0Q504.0,64.0 586.5,107.5Q669.0,151.0 723.0,227.5Q777.0,304.0 804.0,401.0Q695.0,301.0 547.0,301.0Q500.0,301.0 464.0,310.0L491.0,382.0Q517.0,376.0 547.0,376.0Q729.0,376.0 832.0,536.0L909.0,536.0Q903.0,428.0 870.5,329.5Q838.0,231.0 776.0,154.5Q714.0,78.0 618.5,34.0Q523.0,-10.0 391.0,-10.0ZM208.0,106.0Q254.0,136.0 281.5,180.5Q309.0,225.0 309.0,280.0Q309.0,330.0 285.0,357.0Q261.0,384.0 222.0,384.0Q182.0,384.0 156.0,352.5Q130.0,321.0 130.0,273.0Q130.0,218.0 149.0,176.0Q168.0,134.0 208.0,106.0Z"  transform="translate(1126, 801)"/>
<path d="M-581.0,-240.0L-581.0,-166.0L-125.0,-166.0Q-47.0,-166.0 -2.0,-126.0Q43.0,-86.0 61.0,4.0L166.0,536.0L256.0,536.0L301.0,409.0Q316.0,367.0 330.0,342.0Q344.0,317.0 364.5,306.0Q385.0,295.0 419.0,295.0Q407.0,328.0 407.0,396.0L407.0,536.0L495.0,536.0L495.0,395.0Q495.0,358.0 499.5,329.5Q504.0,301.0 515.5,275.0Q527.0,249.0 547.0,217.0L422.0,217.0Q362.0,217.0 324.5,232.5Q287.0,248.0 263.0,284.5Q239.0,321.0 221.0,382.0L148.0,0.0Q132.0,-86.0 99.0,-139.0Q66.0,-192.0 11.5,-216.0Q-43.0,-240.0 -125.0,-240.0L-581.0,-240.0Z"  transform="translate(2077, 801)"/>
<path d="M391.0,-10.0Q227.0,-10.0 133.0,61.5Q39.0,133.0 39.0,274.0Q39.0,325.0 63.0,366.5Q87.0,408.0 128.5,433.0Q170.0,458.0 220.0,458.0Q282.0,458.0 321.5,432.5Q361.0,407.0 380.0,366.5Q399.0,326.0 399.0,279.0Q399.0,231.0 383.5,191.5Q368.0,152.0 344.5,122.0Q321.0,92.0 296.0,72.0Q317.0,68.0 340.5,66.0Q364.0,64.0 391.0,64.0Q504.0,64.0 586.5,107.5Q669.0,151.0 723.0,227.5Q777.0,304.0 804.0,401.0Q695.0,301.0 547.0,301.0Q500.0,301.0 464.0,310.0L491.0,382.0Q517.0,376.0 547.0,376.0Q729.0,376.0 832.0,536.0L909.0,536.0Q903.0,428.0 870.5,329.5Q838.0,231.0 776.0,154.5Q714.0,78.0 618.5,34.0Q523.0,-10.0 391.0,-10.0ZM208.0,106.0Q254.0,136.0 281.5,180.5Q309.0,225.0 309.0,280.0Q309.0,330.0 285.0,357.0Q261.0,384.0 222.0,384.0Q182.0,384.0 156.0,352.5Q130.0,321.0 130.0,273.0Q130.0,218.0 149.0,176.0Q168.0,134.0 208.0,106.0Z"  transform="translate(2673, 801)"/>
<path d="M-657.0,-166.0L-657.0,-92.0L126.0,-92.0L126.0,536.0L214.0,536.0L214.0,-166.0L-657.0,-166.0Z"  transform="translate(3624, 801)"/>
</svg>


</div> [code: shaping-regression]
</div></details><details><summary>⚠ <b>WARN:</b> Are there caret positions declared for every ligature? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/ligature_carets">com.google.fonts/check/ligature_carets</a>)</summary><div>


* ⚠ **WARN** This font lacks caret position values for ligature glyphs on its GDEF table. [code: lacks-caret-pos]
</div></details><details><summary>⚠ <b>WARN:</b> Is there kerning info for non-ligated sequences? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/kerning_for_non_ligated_sequences">com.google.fonts/check/kerning_for_non_ligated_sequences</a>)</summary><div>


* ⚠ **WARN** GPOS table lacks kerning info for the following non-ligated sequences:

	- u10B42 + u10B45

	- u10B47 + u10B45

	- u10B49 + u10B45

	- u10B4D + u10B43

	- u10B43 + u10B45

	- u10B4F + u10B4B

	- u10B53 + u10B45 

	- And u10B55 + u10B45 [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Noto Sans Inscriptional Parthian' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/googlefonts/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- uni00A0.1
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2 

	- And Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure dotted circle glyph is present and can attach marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/dotted_circle">com.google.fonts/check/dotted_circle</a>)</summary><div>


* ⚠ **WARN** No dotted circle glyph present [code: missing-dotted-circle]
</div></details><details><summary>⚠ <b>WARN:</b> Are any segments inordinately short? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_short_segments">com.google.fonts/check/outline_short_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have segments which seem very short:

	* two (U+0032) contains a short segment L<<159.0,84.0>--<159.0,80.0>>

	* at (U+0040) contains a short segment B<<613.0,293.0>-<612.0,275.0>-<612.0,267.5>>

	* at (U+0040) contains a short segment B<<612.0,267.5>-<612.0,260.0>-<612.0,257.0>>

	* M (U+004D) contains a short segment L<<177.0,626.0>--<173.0,626.0>>

	* M (U+004D) contains a short segment L<<450.0,129.0>--<454.0,129.0>>

	* N (U+004E) contains a short segment L<<176.0,593.0>--<172.0,593.0>>

	* N (U+004E) contains a short segment L<<582.0,123.0>--<586.0,123.0>>

	* Q (U+0051) contains a short segment B<<416.0,-9.0>-<410.0,-9.0>-<403.5,-9.5>>

	* Q (U+0051) contains a short segment B<<403.5,-9.5>-<397.0,-10.0>-<391.0,-10.0>>

	* W (U+0057) contains a short segment B<<468.0,577.5>-<463.0,600.0>-<461.0,609.0>> 

	* And 62 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-short-segments]
</div></details><br></div></details>
### Summary

| 💔 ERROR | 🔥 FAIL | ⚠ WARN | 💤 SKIP | ℹ INFO | 🍞 PASS | 🔎 DEBUG |
|:-----:|:----:|:----:|:----:|:----:|:----:|:----:|
| 0 | 1 | 8 | 108 | 8 | 102 | 0 |
| 0% | 0% | 4% | 48% | 4% | 45% | 0% |

**Note:** The following loglevels were omitted in this report:
* **SKIP**
* **INFO**
* **PASS**
* **DEBUG**
