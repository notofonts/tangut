## FontBakery report

fontbakery version: 0.12.10



## Experimental checks

These won't break the CI job for now, but will become effective after some time if nobody raises any concern.


<details><summary>[1] NotoSerifTangut-Regular.ttf</summary>
<div>
<details>
    <summary>🔥 <b>FAIL</b> Checking that the typoAscender exceeds the yMax of the /Agrave. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.metrics.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>OS/2.sTypoAscender value should be greater than 931, but got 856 instead</p>
 [code: typoAscender]



</div>
</details>
</div>
</details>




## All other checks



<details><summary>[13] NotoSerifTangut-Regular.ttf</summary>
<div>
<details>
    <summary>🔥 <b>FAIL</b> Checking OS/2 usWinAscent & usWinDescent. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.metrics.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>OS/2.usWinAscent value should be equal or greater than 979, but got 856 instead</p>
 [code: ascent]



* 🔥 **FAIL** <p>OS/2.usWinDescent value should be equal or greater than 240, but got 150 instead</p>
 [code: descent]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Check for presence of an ARTICLE.en_us.html file <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.description.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>This is a Noto font but it lacks an ARTICLE.en_us.html file.</p>
 [code: missing-article]



* 🔥 **FAIL** <p>This is a Noto font but it lacks a DESCRIPTION.en_us.html file.</p>
 [code: missing-description]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check if each glyph has the recommended amount of contours. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.</p>
<p>The following glyphs do not have the recommended number of contours:</p>
<pre><code>- Glyph name: aogonek	Contours detected: 3	Expected: 2

- Glyph name: Uogonek	Contours detected: 2	Expected: 1

- Glyph name: uogonek	Contours detected: 2	Expected: 1

- Glyph name: Uogonek	Contours detected: 2	Expected: 1

- Glyph name: aogonek	Contours detected: 3	Expected: 2

- Glyph name: uogonek	Contours detected: 2	Expected: 1
</code></pre>
 [code: contour-count]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check math signs have the same width. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The most common width is 559 among a set of 6 math glyphs.
The following math glyphs have a different width, though:</p>
<p>Width = 310:
minus</p>
 [code: width-outliers]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check font contains no unreachable glyphs <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.glyphset.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs could not be reached by codepoint or substitution rules:</p>
<pre><code>- glyph1

- glyph2
</code></pre>
 [code: unreachable-glyphs]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Validate size, and resolution of article images, and ensure article page has minimum length and includes visual assets. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.article.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>Family metadata at fonts/NotoSerifTangut/googlefonts/ttf does not have an article.</p>
 [code: lacks-article]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check for codepoints not covered by METADATA subsets. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.subsets.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The following codepoints supported by the font are not covered by
any subsets defined in the font's metadata file, and will never
be served. You can solve this by either manually adding additional
subset declarations to METADATA.pb, or by editing the glyphset
definitions.</p>
<ul>
<li>U+02C7 CARON: try adding one of: yi, tifinagh, canadian-aboriginal</li>
<li>U+02C9 MODIFIER LETTER MACRON: not included in any glyphset definition</li>
<li>U+02D8 BREVE: try adding one of: yi, canadian-aboriginal</li>
<li>U+02D9 DOT ABOVE: try adding one of: yi, canadian-aboriginal</li>
<li>U+02DB OGONEK: try adding one of: yi, canadian-aboriginal</li>
<li>U+02DD DOUBLE ACUTE ACCENT: not included in any glyphset definition</li>
<li>U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: coptic, math, tifinagh, cherokee</li>
<li>U+0306 COMBINING BREVE: try adding one of: old-permic, tifinagh</li>
<li>U+0307 COMBINING DOT ABOVE: try adding one of: math, syriac, tifinagh, canadian-aboriginal, old-permic, tai-le, malayalam, coptic</li>
<li>U+030A COMBINING RING ABOVE: try adding syriac</li>
<li>U+030B COMBINING DOUBLE ACUTE ACCENT: try adding one of: osage, cherokee</li>
<li>U+030C COMBINING CARON: try adding one of: tai-le, cherokee</li>
<li>U+0326 COMBINING COMMA BELOW: not included in any glyphset definition</li>
<li>U+0327 COMBINING CEDILLA: not included in any glyphset definition</li>
<li>U+0328 COMBINING OGONEK: not included in any glyphset definition</li>
<li>U+1F6D3 STUPA: try adding symbols</li>
<li>U+1F6D4 PAGODA: try adding symbols</li>
</ul>
<p>Or you can add the above codepoints to one of the subsets supported by the font: <code>latin</code>, <code>latin-ext</code>, <code>tangut</code></p>
 [code: unreachable-subsetting]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Ensure dotted circle glyph is present and can attach marks. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/shaping.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>No dotted circle glyph present</p>
 [code: missing-dotted-circle]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/shaping.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The dot of soft dotted characters used in orthographies <em>must</em> disappear in the following strings: į̀ į́ į̂ į̃ į̄ į̌</p>
<p>The dot of soft dotted characters <em>should</em> disappear in other cases, for example: į̆ į̇ į̈ į̊ į̋ į̦̀ į̦́ į̦̂ į̦̃ į̦̄ į̦̆ į̦̇ į̦̈ į̦̊ į̦̋ į̦̌ į̧̀ į̧́ į̧̂ į̧̃</p>
<p>Your font fully covers the following languages that require the soft-dotted feature: Dutch (Latn, 31,709,104 speakers), Lithuanian (Latn, 2,357,094 speakers).</p>
<p>Your font does <em>not</em> cover the following languages that require the soft-dotted feature: Mundani (Latn, 34,000 speakers), South Central Banda (Latn, 244,000 speakers), Ekpeye (Latn, 226,000 speakers), Bafut (Latn, 158,146 speakers), Fur (Latn, 1,230,163 speakers), Ngbaka (Latn, 1,020,000 speakers), Kom (Latn, 360,685 speakers), Lugbara (Latn, 2,200,000 speakers), Mfumte (Latn, 79,000 speakers), Cicipu (Latn, 44,000 speakers), Ma’di (Latn, 584,000 speakers), Sar (Latn, 500,000 speakers), Zapotec (Latn, 490,000 speakers), Bete-Bendi (Latn, 100,000 speakers), Southern Kisi (Latn, 360,000 speakers), Ejagham (Latn, 120,000 speakers), Avokaya (Latn, 100,000 speakers), Ijo, Southeast (Latn, 2,471,000 speakers), Yala (Latn, 200,000 speakers), Mango (Latn, 77,000 speakers), Basaa (Latn, 332,940 speakers), Ukrainian (Cyrl, 29,273,587 speakers), Igbo (Latn, 27,823,640 speakers), Dii (Latn, 71,000 speakers), Ebira (Latn, 2,200,000 speakers), Belarusian (Cyrl, 10,064,517 speakers), Aghem (Latn, 38,843 speakers), Navajo (Latn, 166,319 speakers), Nzakara (Latn, 50,000 speakers), Kpelle, Guinea (Latn, 622,000 speakers), Vute (Latn, 21,000 speakers), Makaa (Latn, 221,000 speakers), Nateni (Latn, 100,000 speakers), Koonzime (Latn, 40,000 speakers), Dan (Latn, 1,099,244 speakers), Gulay (Latn, 250,478 speakers).</p>
 [code: soft-dotted]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Do outlines contain any jaggy segments? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/outline.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs have jaggy segments:</p>
<pre><code>* u17013 (U+17013): L&lt;&lt;508.0,544.0&gt;--&lt;247.0,478.0&gt;&gt;/L&lt;&lt;247.0,478.0&gt;--&lt;542.0,478.0&gt;&gt; = 14.191096549023982

* u170B3 (U+170B3): L&lt;&lt;322.0,103.0&gt;--&lt;597.0,165.0&gt;&gt;/L&lt;&lt;597.0,165.0&gt;--&lt;332.0,165.0&gt;&gt; = 12.705169690097586

* u170B3 (U+170B3): L&lt;&lt;742.0,161.0&gt;--&lt;421.0,81.0&gt;&gt;/L&lt;&lt;421.0,81.0&gt;--&lt;700.0,81.0&gt;&gt; = 13.994237771997035

* u170F1 (U+170F1): L&lt;&lt;276.0,-26.0&gt;--&lt;276.0,381.0&gt;&gt;/B&lt;&lt;276.0,381.0&gt;-&lt;242.0,207.0&gt;-&lt;236.0,158.0&gt;&gt; = 11.056412980248197

* u170F2 (U+170F2): L&lt;&lt;273.0,-34.0&gt;--&lt;273.0,384.0&gt;&gt;/B&lt;&lt;273.0,384.0&gt;-&lt;241.0,240.0&gt;-&lt;227.0,157.0&gt;&gt; = 12.528807709151492

* u170F5 (U+170F5): L&lt;&lt;313.0,-75.0&gt;--&lt;313.0,447.0&gt;&gt;/B&lt;&lt;313.0,447.0&gt;-&lt;257.0,223.0&gt;-&lt;245.0,159.0&gt;&gt; = 14.036243467926484

* u17114 (U+17114): B&lt;&lt;273.0,168.0&gt;-&lt;211.0,98.0&gt;-&lt;134.0,57.0&gt;&gt;/L&lt;&lt;134.0,57.0&gt;--&lt;136.0,58.0&gt;&gt; = 1.4688007143857

* u17171 (U+17171): B&lt;&lt;545.0,120.0&gt;-&lt;488.0,70.0&gt;-&lt;418.0,41.0&gt;&gt;/L&lt;&lt;418.0,41.0&gt;--&lt;429.0,45.0&gt;&gt; = 2.52042197786743

* u1717D (U+1717D): B&lt;&lt;549.0,183.0&gt;-&lt;484.0,100.0&gt;-&lt;410.0,51.0&gt;&gt;/L&lt;&lt;410.0,51.0&gt;--&lt;415.0,53.0&gt;&gt; = 11.709609311488988

* u171AC (U+171AC): L&lt;&lt;650.0,-77.0&gt;--&lt;650.0,203.0&gt;&gt;/B&lt;&lt;650.0,203.0&gt;-&lt;634.0,139.0&gt;-&lt;628.0,112.0&gt;&gt; = 14.036243467926484

* u171E9 (U+171E9): L&lt;&lt;186.0,355.0&gt;--&lt;649.0,450.0&gt;&gt;/L&lt;&lt;649.0,450.0&gt;--&lt;170.0,450.0&gt;&gt; = 11.595220304772592

* u171E9 (U+171E9): L&lt;&lt;824.0,446.0&gt;--&lt;307.0,334.0&gt;&gt;/L&lt;&lt;307.0,334.0&gt;--&lt;691.0,334.0&gt;&gt; = 12.223358425843676

* u17213 (U+17213): L&lt;&lt;491.0,352.0&gt;--&lt;779.0,420.0&gt;&gt;/L&lt;&lt;779.0,420.0&gt;--&lt;500.0,420.0&gt;&gt; = 13.284866484902187

* u17213 (U+17213): L&lt;&lt;846.0,400.0&gt;--&lt;537.0,331.0&gt;&gt;/L&lt;&lt;537.0,331.0&gt;--&lt;861.0,331.0&gt;&gt; = 12.587693381648801

* u17274 (U+17274): B&lt;&lt;868.0,-17.0&gt;-&lt;871.0,-19.0&gt;-&lt;874.0,-19.0&gt;&gt;/B&lt;&lt;874.0,-19.0&gt;-&lt;868.0,-20.0&gt;-&lt;874.0,-20.0&gt;&gt; = 9.462322208025613

* u17302 (U+17302): L&lt;&lt;427.0,0.0&gt;--&lt;427.0,208.0&gt;&gt;/B&lt;&lt;427.0,208.0&gt;-&lt;401.0,90.0&gt;-&lt;394.0,47.0&gt;&gt; = 12.425942865427485

* u17373 (U+17373): B&lt;&lt;847.0,-17.0&gt;-&lt;850.0,-18.0&gt;-&lt;852.0,-18.0&gt;&gt;/L&lt;&lt;852.0,-18.0&gt;--&lt;848.0,-19.0&gt;&gt; = 14.036243467926484

* u17373 (U+17373): L&lt;&lt;852.0,-18.0&gt;--&lt;848.0,-19.0&gt;&gt;/B&lt;&lt;848.0,-19.0&gt;-&lt;857.0,-19.0&gt;-&lt;865.0,-15.0&gt;&gt; = 14.036243467926484

* u17388 (U+17388): L&lt;&lt;274.0,-75.0&gt;--&lt;274.0,281.0&gt;&gt;/B&lt;&lt;274.0,281.0&gt;-&lt;243.0,140.0&gt;-&lt;238.0,111.0&gt;&gt; = 12.399666426309755

* u1738B (U+1738B): L&lt;&lt;254.0,-71.0&gt;--&lt;254.0,292.0&gt;&gt;/B&lt;&lt;254.0,292.0&gt;-&lt;228.0,177.0&gt;-&lt;221.0,135.0&gt;&gt; = 12.739646792482095

* u1738F (U+1738F): L&lt;&lt;269.0,-75.0&gt;--&lt;269.0,324.0&gt;&gt;/B&lt;&lt;269.0,324.0&gt;-&lt;232.0,159.0&gt;-&lt;225.0,119.0&gt;&gt; = 12.63906244063008

* u17390 (U+17390): L&lt;&lt;267.0,-75.0&gt;--&lt;267.0,305.0&gt;&gt;/B&lt;&lt;267.0,305.0&gt;-&lt;238.0,183.0&gt;-&lt;226.0,113.0&gt;&gt; = 13.371331969891925

* u17397 (U+17397): L&lt;&lt;225.0,0.0&gt;--&lt;225.0,271.0&gt;&gt;/B&lt;&lt;225.0,271.0&gt;-&lt;204.0,179.0&gt;-&lt;198.0,140.0&gt;&gt; = 12.858090172998171

* u17401 (U+17401): L&lt;&lt;281.0,165.0&gt;--&lt;280.0,167.0&gt;&gt;/B&lt;&lt;280.0,167.0&gt;-&lt;300.0,115.0&gt;-&lt;300.0,79.0&gt;&gt; = 5.52754015165606

* u17402 (U+17402): L&lt;&lt;281.0,165.0&gt;--&lt;280.0,167.0&gt;&gt;/B&lt;&lt;280.0,167.0&gt;-&lt;300.0,115.0&gt;-&lt;300.0,79.0&gt;&gt; = 5.52754015165606

* u1740D (U+1740D): L&lt;&lt;167.0,269.0&gt;--&lt;649.0,376.0&gt;&gt;/L&lt;&lt;649.0,376.0&gt;--&lt;202.0,376.0&gt;&gt; = 12.516220763063778

* u1740D (U+1740D): L&lt;&lt;774.0,356.0&gt;--&lt;284.0,248.0&gt;&gt;/L&lt;&lt;284.0,248.0&gt;--&lt;761.0,248.0&gt;&gt; = 12.42972301845446

* u17439 (U+17439): L&lt;&lt;513.0,68.0&gt;--&lt;522.0,73.0&gt;&gt;/B&lt;&lt;522.0,73.0&gt;-&lt;454.0,50.0&gt;-&lt;361.0,32.0&gt;&gt; = 10.36725259386594

* u17449 (U+17449): B&lt;&lt;535.0,156.0&gt;-&lt;471.0,85.0&gt;-&lt;406.0,49.0&gt;&gt;/L&lt;&lt;406.0,49.0&gt;--&lt;412.0,51.0&gt;&gt; = 10.544758875006739

* u1754D (U+1754D): B&lt;&lt;836.0,-20.0&gt;-&lt;839.0,-18.0&gt;-&lt;838.0,-19.0&gt;&gt;/B&lt;&lt;838.0,-19.0&gt;-&lt;849.0,-12.0&gt;-&lt;855.0,2.0&gt;&gt; = 12.528807709151522

* u17565 (U+17565): L&lt;&lt;630.0,153.0&gt;--&lt;635.0,157.0&gt;&gt;/B&lt;&lt;635.0,157.0&gt;-&lt;597.0,134.0&gt;-&lt;547.0,113.0&gt;&gt; = 7.4748335953516625

* u175CE (U+175CE): L&lt;&lt;451.0,577.0&gt;--&lt;237.0,531.0&gt;&gt;/L&lt;&lt;237.0,531.0&gt;--&lt;451.0,531.0&gt;&gt; = 12.131321066632482

* u175CE (U+175CE): L&lt;&lt;516.0,637.0&gt;--&lt;704.0,677.0&gt;&gt;/L&lt;&lt;704.0,677.0&gt;--&lt;516.0,677.0&gt;&gt; = 12.01147838636543

* u175CF (U+175CF): L&lt;&lt;451.0,583.0&gt;--&lt;237.0,541.0&gt;&gt;/L&lt;&lt;237.0,541.0&gt;--&lt;451.0,541.0&gt;&gt; = 11.103833436636071

* u175CF (U+175CF): L&lt;&lt;516.0,640.0&gt;--&lt;704.0,677.0&gt;&gt;/L&lt;&lt;704.0,677.0&gt;--&lt;516.0,677.0&gt;&gt; = 11.133999210646985

* u175D0 (U+175D0): L&lt;&lt;451.0,566.0&gt;--&lt;237.0,516.0&gt;&gt;/L&lt;&lt;237.0,516.0&gt;--&lt;451.0,516.0&gt;&gt; = 13.1509486809447

* u175D0 (U+175D0): L&lt;&lt;516.0,630.0&gt;--&lt;704.0,674.0&gt;&gt;/L&lt;&lt;704.0,674.0&gt;--&lt;516.0,674.0&gt;&gt; = 13.172553423326871

* u175D1 (U+175D1): L&lt;&lt;451.0,591.0&gt;--&lt;237.0,552.0&gt;&gt;/L&lt;&lt;237.0,552.0&gt;--&lt;451.0,552.0&gt;&gt; = 10.328405587303893

* u175D1 (U+175D1): L&lt;&lt;516.0,644.0&gt;--&lt;704.0,678.0&gt;&gt;/L&lt;&lt;704.0,678.0&gt;--&lt;516.0,678.0&gt;&gt; = 10.251198750817418

* u175D2 (U+175D2): L&lt;&lt;451.0,611.0&gt;--&lt;237.0,581.0&gt;&gt;/L&lt;&lt;237.0,581.0&gt;--&lt;451.0,581.0&gt;&gt; = 7.980113745168495

* u175D2 (U+175D2): L&lt;&lt;516.0,657.0&gt;--&lt;704.0,684.0&gt;&gt;/L&lt;&lt;704.0,684.0&gt;--&lt;516.0,684.0&gt;&gt; = 8.172764877554496

* u1762A (U+1762A): L&lt;&lt;532.0,335.0&gt;--&lt;371.0,305.0&gt;&gt;/L&lt;&lt;371.0,305.0&gt;--&lt;532.0,305.0&gt;&gt; = 10.55518143294881

* u1762A (U+1762A): L&lt;&lt;597.0,380.0&gt;--&lt;718.0,403.0&gt;&gt;/L&lt;&lt;718.0,403.0&gt;--&lt;597.0,403.0&gt;&gt; = 10.762537223142443

* u1769E (U+1769E): L&lt;&lt;452.0,402.0&gt;--&lt;272.0,361.0&gt;&gt;/L&lt;&lt;272.0,361.0&gt;--&lt;452.0,365.0&gt;&gt; = 11.558749022473359

* u1769E (U+1769E): L&lt;&lt;517.0,462.0&gt;--&lt;649.0,492.0&gt;&gt;/L&lt;&lt;649.0,492.0&gt;--&lt;517.0,489.0&gt;&gt; = 11.502313392707837

* u176F7 (U+176F7): B&lt;&lt;706.0,297.0&gt;-&lt;637.0,279.0&gt;-&lt;541.0,268.0&gt;&gt;/L&lt;&lt;541.0,268.0&gt;--&lt;598.0,262.0&gt;&gt; = 12.545639606291529

* u1777E (U+1777E): B&lt;&lt;447.0,75.0&gt;-&lt;477.0,88.0&gt;-&lt;484.0,91.0&gt;&gt;/B&lt;&lt;484.0,91.0&gt;-&lt;476.0,89.0&gt;-&lt;472.0,89.0&gt;&gt; = 9.162347045721706

* u177C2 (U+177C2): B&lt;&lt;76.0,204.0&gt;-&lt;138.0,250.0&gt;-&lt;192.0,327.0&gt;&gt;/B&lt;&lt;192.0,327.0&gt;-&lt;179.0,314.0&gt;-&lt;148.0,309.0&gt;&gt; = 9.95807059846092

* u177DA (U+177DA): B&lt;&lt;838.0,626.0&gt;-&lt;754.0,536.0&gt;-&lt;559.0,499.0&gt;&gt;/L&lt;&lt;559.0,499.0&gt;--&lt;722.0,499.0&gt;&gt; = 10.743787070980858

* u17980 (U+17980): L&lt;&lt;522.0,-75.0&gt;--&lt;522.0,401.0&gt;&gt;/B&lt;&lt;522.0,401.0&gt;-&lt;483.0,234.0&gt;-&lt;474.0,176.0&gt;&gt; = 13.144867617550734

* u179DC (U+179DC): B&lt;&lt;646.0,454.0&gt;-&lt;736.0,384.0&gt;-&lt;741.0,330.0&gt;&gt;/L&lt;&lt;741.0,330.0&gt;--&lt;741.0,593.0&gt;&gt; = 5.290081205371211

* u179DC (U+179DC): L&lt;&lt;741.0,-3.0&gt;--&lt;741.0,313.0&gt;&gt;/B&lt;&lt;741.0,313.0&gt;-&lt;738.0,275.0&gt;-&lt;709.0,269.0&gt;&gt; = 4.513988458001203

* u179DE (U+179DE): L&lt;&lt;504.0,-75.0&gt;--&lt;504.0,330.0&gt;&gt;/B&lt;&lt;504.0,330.0&gt;-&lt;475.0,207.0&gt;-&lt;466.0,151.0&gt;&gt; = 13.266480846583704

* u179DF (U+179DF): L&lt;&lt;533.0,18.0&gt;--&lt;533.0,416.0&gt;&gt;/B&lt;&lt;533.0,416.0&gt;-&lt;489.0,223.0&gt;-&lt;479.0,152.0&gt;&gt; = 12.842754043944451

* u17A81 (U+17A81): L&lt;&lt;597.0,-6.0&gt;--&lt;589.0,7.0&gt;&gt;/B&lt;&lt;589.0,7.0&gt;-&lt;595.0,-11.0&gt;-&lt;611.0,-15.0&gt;&gt; = 13.172553423326871

* u17AEC (U+17AEC): B&lt;&lt;257.0,147.0&gt;-&lt;270.0,125.0&gt;-&lt;284.0,100.0&gt;&gt;/L&lt;&lt;284.0,100.0&gt;--&lt;283.0,102.0&gt;&gt; = 2.683775159468774

* u17B1C (U+17B1C): L&lt;&lt;640.0,219.0&gt;--&lt;644.0,221.0&gt;&gt;/B&lt;&lt;644.0,221.0&gt;-&lt;613.0,206.0&gt;-&lt;568.0,189.0&gt;&gt; = 0.7440592028875314

* u17B1E (U+17B1E): B&lt;&lt;320.0,609.0&gt;-&lt;336.0,582.0&gt;-&lt;341.0,560.0&gt;&gt;/L&lt;&lt;341.0,560.0&gt;--&lt;341.0,824.0&gt;&gt; = 12.80426606528674

* u17B45 (U+17B45): B&lt;&lt;923.0,480.0&gt;-&lt;781.0,499.0&gt;-&lt;656.0,566.0&gt;&gt;/L&lt;&lt;656.0,566.0&gt;--&lt;685.0,541.0&gt;&gt; = 12.572296827147996

* u17BB6 (U+17BB6): B&lt;&lt;843.0,110.0&gt;-&lt;751.0,31.0&gt;-&lt;524.0,-14.0&gt;&gt;/B&lt;&lt;524.0,-14.0&gt;-&lt;783.0,-14.0&gt;-&lt;823.0,-10.0&gt;&gt; = 11.212821076311865

* u17BC7 (U+17BC7): B&lt;&lt;789.0,93.0&gt;-&lt;792.0,91.0&gt;-&lt;795.0,91.0&gt;&gt;/L&lt;&lt;795.0,91.0&gt;--&lt;791.0,90.0&gt;&gt; = 14.036243467926484

* u17BC7 (U+17BC7): L&lt;&lt;795.0,91.0&gt;--&lt;791.0,90.0&gt;&gt;/B&lt;&lt;791.0,90.0&gt;-&lt;806.0,90.0&gt;-&lt;813.0,93.0&gt;&gt; = 14.036243467926484

* u17BCA (U+17BCA): B&lt;&lt;777.0,84.0&gt;-&lt;780.0,82.0&gt;-&lt;783.0,82.0&gt;&gt;/B&lt;&lt;783.0,82.0&gt;-&lt;778.0,81.0&gt;-&lt;784.0,81.0&gt;&gt; = 11.309932474020195

* u17BCF (U+17BCF): B&lt;&lt;641.0,31.0&gt;-&lt;546.0,-3.0&gt;-&lt;448.0,-14.0&gt;&gt;/B&lt;&lt;448.0,-14.0&gt;-&lt;700.0,-14.0&gt;-&lt;748.0,-13.0&gt;&gt; = 6.4043527263841025

* u17BCF (U+17BCF): B&lt;&lt;688.0,566.0&gt;-&lt;607.0,532.0&gt;-&lt;518.0,510.0&gt;&gt;/L&lt;&lt;518.0,510.0&gt;--&lt;705.0,510.0&gt;&gt; = 13.884667685258169

* u17C5B (U+17C5B): B&lt;&lt;888.0,219.0&gt;-&lt;821.0,234.0&gt;-&lt;757.0,257.0&gt;&gt;/L&lt;&lt;757.0,257.0&gt;--&lt;855.0,200.0&gt;&gt; = 10.416511980430695

* u17C7C (U+17C7C): L&lt;&lt;280.0,621.0&gt;--&lt;212.0,607.0&gt;&gt;/L&lt;&lt;212.0,607.0&gt;--&lt;280.0,607.0&gt;&gt; = 11.633633998940427

* u17C7C (U+17C7C): L&lt;&lt;633.0,734.0&gt;--&lt;727.0,753.0&gt;&gt;/L&lt;&lt;727.0,753.0&gt;--&lt;135.0,753.0&gt;&gt; = 11.427101593945128

* u17C86 (U+17C86): L&lt;&lt;293.0,511.0&gt;--&lt;289.0,511.0&gt;&gt;/L&lt;&lt;289.0,511.0&gt;--&lt;339.0,506.0&gt;&gt; = 5.710593137499633

* u17CA8 (U+17CA8): L&lt;&lt;679.0,535.0&gt;--&lt;710.0,571.0&gt;&gt;/B&lt;&lt;710.0,571.0&gt;-&lt;703.0,565.0&gt;-&lt;680.0,559.0&gt;&gt; = 8.66659865528633

* u17CA9 (U+17CA9): L&lt;&lt;279.0,671.0&gt;--&lt;688.0,752.0&gt;&gt;/L&lt;&lt;688.0,752.0&gt;--&lt;136.0,752.0&gt;&gt; = 11.202132451619969

* u17CB6 (U+17CB6): L&lt;&lt;279.0,671.0&gt;--&lt;688.0,752.0&gt;&gt;/L&lt;&lt;688.0,752.0&gt;--&lt;136.0,752.0&gt;&gt; = 11.202132451619969

* u17CBF (U+17CBF): L&lt;&lt;334.0,529.0&gt;--&lt;264.0,512.0&gt;&gt;/L&lt;&lt;264.0,512.0&gt;--&lt;334.0,512.0&gt;&gt; = 13.65041913475701

* u17CBF (U+17CBF): L&lt;&lt;639.0,658.0&gt;--&lt;688.0,670.0&gt;&gt;/L&lt;&lt;688.0,670.0&gt;--&lt;639.0,670.0&gt;&gt; = 13.760785111791225

* u17CC0 (U+17CC0): L&lt;&lt;334.0,530.0&gt;--&lt;238.0,512.0&gt;&gt;/L&lt;&lt;238.0,512.0&gt;--&lt;334.0,512.0&gt;&gt; = 10.61965527615514

* u17CC0 (U+17CC0): L&lt;&lt;635.0,630.0&gt;--&lt;709.0,644.0&gt;&gt;/L&lt;&lt;709.0,644.0&gt;--&lt;635.0,644.0&gt;&gt; = 10.713123022791033

* u17CC1 (U+17CC1): L&lt;&lt;334.0,582.0&gt;--&lt;241.0,565.0&gt;&gt;/L&lt;&lt;241.0,565.0&gt;--&lt;334.0,565.0&gt;&gt; = 10.359052488083714

* u17CC1 (U+17CC1): L&lt;&lt;640.0,683.0&gt;--&lt;706.0,695.0&gt;&gt;/L&lt;&lt;706.0,695.0&gt;--&lt;640.0,695.0&gt;&gt; = 10.304846468766044

* u17CC2 (U+17CC2): L&lt;&lt;327.0,537.0&gt;--&lt;255.0,523.0&gt;&gt;/L&lt;&lt;255.0,523.0&gt;--&lt;327.0,523.0&gt;&gt; = 11.003540851749507

* u17CC2 (U+17CC2): L&lt;&lt;642.0,644.0&gt;--&lt;696.0,655.0&gt;&gt;/L&lt;&lt;696.0,655.0&gt;--&lt;642.0,655.0&gt;&gt; = 11.513831184487014

* u17D2B (U+17D2B): B&lt;&lt;294.0,499.0&gt;-&lt;283.0,481.0&gt;-&lt;238.0,459.0&gt;&gt;/B&lt;&lt;238.0,459.0&gt;-&lt;373.0,492.0&gt;-&lt;507.0,549.0&gt;&gt; = 12.31722700486836

* u17D2C (U+17D2C): B&lt;&lt;225.0,454.0&gt;-&lt;221.0,452.0&gt;-&lt;218.0,451.0&gt;&gt;/B&lt;&lt;218.0,451.0&gt;-&lt;366.0,484.0&gt;-&lt;510.0,547.0&gt;&gt; = 5.865157015243321

* u17D2C (U+17D2C): B&lt;&lt;54.0,423.0&gt;-&lt;111.0,430.0&gt;-&lt;180.0,443.0&gt;&gt;/L&lt;&lt;180.0,443.0&gt;--&lt;179.0,443.0&gt;&gt; = 10.66978280449666

* u17D2D (U+17D2D): B&lt;&lt;292.0,507.0&gt;-&lt;282.0,491.0&gt;-&lt;251.0,475.0&gt;&gt;/B&lt;&lt;251.0,475.0&gt;-&lt;369.0,506.0&gt;-&lt;489.0,558.0&gt;&gt; = 12.579912493839538

* u17D2E (U+17D2E): B&lt;&lt;292.0,507.0&gt;-&lt;282.0,491.0&gt;-&lt;251.0,475.0&gt;&gt;/B&lt;&lt;251.0,475.0&gt;-&lt;369.0,506.0&gt;-&lt;489.0,558.0&gt;&gt; = 12.579912493839538

* u17D4B (U+17D4B): B&lt;&lt;886.0,196.0&gt;-&lt;829.0,208.0&gt;-&lt;787.0,221.0&gt;&gt;/L&lt;&lt;787.0,221.0&gt;--&lt;872.0,172.0&gt;&gt; = 12.763642876351874

* u17D52 (U+17D52): B&lt;&lt;886.0,196.0&gt;-&lt;829.0,208.0&gt;-&lt;787.0,221.0&gt;&gt;/L&lt;&lt;787.0,221.0&gt;--&lt;872.0,172.0&gt;&gt; = 12.763642876351874

* u17D80 (U+17D80): L&lt;&lt;516.0,283.0&gt;--&lt;525.0,290.0&gt;&gt;/B&lt;&lt;525.0,290.0&gt;-&lt;488.0,270.0&gt;-&lt;457.0,255.0&gt;&gt; = 9.481964229715157

* u17D84 (U+17D84): B&lt;&lt;360.0,-74.0&gt;-&lt;357.0,-74.0&gt;-&lt;358.0,-74.0&gt;&gt;/B&lt;&lt;358.0,-74.0&gt;-&lt;342.0,-75.0&gt;-&lt;325.0,-66.0&gt;&gt; = 3.576334374997269

* u17D85 (U+17D85): B&lt;&lt;360.0,-74.0&gt;-&lt;357.0,-74.0&gt;-&lt;358.0,-74.0&gt;&gt;/B&lt;&lt;358.0,-74.0&gt;-&lt;342.0,-75.0&gt;-&lt;325.0,-66.0&gt;&gt; = 3.576334374997269

* u17D8A (U+17D8A): B&lt;&lt;360.0,-74.0&gt;-&lt;357.0,-74.0&gt;-&lt;358.0,-74.0&gt;&gt;/B&lt;&lt;358.0,-74.0&gt;-&lt;342.0,-75.0&gt;-&lt;325.0,-66.0&gt;&gt; = 3.576334374997269

* u17DAA (U+17DAA): B&lt;&lt;333.0,179.0&gt;-&lt;307.0,170.0&gt;-&lt;277.0,167.0&gt;&gt;/L&lt;&lt;277.0,167.0&gt;--&lt;339.0,160.0&gt;&gt; = 12.15219323683465

* u17DD2 (U+17DD2): B&lt;&lt;822.0,-19.0&gt;-&lt;825.0,-20.0&gt;-&lt;827.0,-20.0&gt;&gt;/B&lt;&lt;827.0,-20.0&gt;-&lt;820.0,-21.0&gt;-&lt;827.0,-21.0&gt;&gt; = 8.13010235415596

* u17EF1 (U+17EF1): B&lt;&lt;699.0,379.0&gt;-&lt;732.0,352.0&gt;-&lt;738.0,325.0&gt;&gt;/L&lt;&lt;738.0,325.0&gt;--&lt;738.0,551.0&gt;&gt; = 12.528807709151492

* u17F7D (U+17F7D): B&lt;&lt;900.0,379.0&gt;-&lt;761.0,393.0&gt;-&lt;630.0,422.0&gt;&gt;/L&lt;&lt;630.0,422.0&gt;--&lt;697.0,398.0&gt;&gt; = 7.225489458024169

* u17F81 (U+17F81): B&lt;&lt;477.0,507.0&gt;-&lt;393.0,476.0&gt;-&lt;309.0,456.0&gt;&gt;/L&lt;&lt;309.0,456.0&gt;--&lt;543.0,456.0&gt;&gt; = 13.392497753751098

* u17FA9 (U+17FA9): L&lt;&lt;372.0,240.0&gt;--&lt;374.0,242.0&gt;&gt;/B&lt;&lt;374.0,242.0&gt;-&lt;365.0,234.0&gt;-&lt;352.0,234.0&gt;&gt; = 3.3664606634298315

* u17FF4 (U+17FF4): B&lt;&lt;849.0,-18.0&gt;-&lt;852.0,-19.0&gt;-&lt;854.0,-19.0&gt;&gt;/L&lt;&lt;854.0,-19.0&gt;--&lt;850.0,-20.0&gt;&gt; = 14.036243467926484

* u1801C (U+1801C): B&lt;&lt;737.0,541.0&gt;-&lt;636.0,498.0&gt;-&lt;531.0,477.0&gt;&gt;/L&lt;&lt;531.0,477.0&gt;--&lt;735.0,477.0&gt;&gt; = 11.309932474020195

* u18035 (U+18035): B&lt;&lt;322.0,-75.0&gt;-&lt;319.0,-75.0&gt;-&lt;320.0,-75.0&gt;&gt;/B&lt;&lt;320.0,-75.0&gt;-&lt;305.0,-76.0&gt;-&lt;288.0,-67.0&gt;&gt; = 3.8140748342903783

* u1806B (U+1806B): B&lt;&lt;488.0,250.0&gt;-&lt;489.0,245.0&gt;-&lt;489.0,243.0&gt;&gt;/B&lt;&lt;489.0,243.0&gt;-&lt;494.0,265.0&gt;-&lt;560.0,612.0&gt;&gt; = 12.80426606528674

* u1806C (U+1806C): B&lt;&lt;504.0,248.0&gt;-&lt;505.0,245.0&gt;-&lt;505.0,243.0&gt;&gt;/B&lt;&lt;505.0,243.0&gt;-&lt;506.0,247.0&gt;-&lt;559.0,549.0&gt;&gt; = 14.036243467926484

* u1813A (U+1813A): B&lt;&lt;353.0,-74.0&gt;-&lt;350.0,-74.0&gt;-&lt;351.0,-74.0&gt;&gt;/B&lt;&lt;351.0,-74.0&gt;-&lt;335.0,-75.0&gt;-&lt;318.0,-66.0&gt;&gt; = 3.576334374997269

* u1813B (U+1813B): B&lt;&lt;346.0,-74.0&gt;-&lt;343.0,-74.0&gt;-&lt;344.0,-74.0&gt;&gt;/B&lt;&lt;344.0,-74.0&gt;-&lt;328.0,-75.0&gt;-&lt;311.0,-66.0&gt;&gt; = 3.576334374997269

* u1813D (U+1813D): B&lt;&lt;360.0,-74.0&gt;-&lt;357.0,-74.0&gt;-&lt;358.0,-74.0&gt;&gt;/B&lt;&lt;358.0,-74.0&gt;-&lt;342.0,-75.0&gt;-&lt;325.0,-66.0&gt;&gt; = 3.576334374997269

* u1813E (U+1813E): B&lt;&lt;360.0,-74.0&gt;-&lt;357.0,-74.0&gt;-&lt;358.0,-74.0&gt;&gt;/B&lt;&lt;358.0,-74.0&gt;-&lt;342.0,-75.0&gt;-&lt;325.0,-66.0&gt;&gt; = 3.576334374997269

* u1813F (U+1813F): B&lt;&lt;360.0,-74.0&gt;-&lt;357.0,-74.0&gt;-&lt;358.0,-74.0&gt;&gt;/B&lt;&lt;358.0,-74.0&gt;-&lt;342.0,-75.0&gt;-&lt;325.0,-66.0&gt;&gt; = 3.576334374997269

* u18149 (U+18149): B&lt;&lt;360.0,-74.0&gt;-&lt;357.0,-74.0&gt;-&lt;358.0,-74.0&gt;&gt;/B&lt;&lt;358.0,-74.0&gt;-&lt;342.0,-75.0&gt;-&lt;325.0,-66.0&gt;&gt; = 3.576334374997269

* u1814C (U+1814C): B&lt;&lt;360.0,-74.0&gt;-&lt;357.0,-74.0&gt;-&lt;358.0,-74.0&gt;&gt;/B&lt;&lt;358.0,-74.0&gt;-&lt;342.0,-75.0&gt;-&lt;325.0,-66.0&gt;&gt; = 3.576334374997269

* u1814D (U+1814D): B&lt;&lt;360.0,-74.0&gt;-&lt;357.0,-74.0&gt;-&lt;358.0,-74.0&gt;&gt;/B&lt;&lt;358.0,-74.0&gt;-&lt;342.0,-75.0&gt;-&lt;325.0,-66.0&gt;&gt; = 3.576334374997269

* u1814E (U+1814E): B&lt;&lt;360.0,-74.0&gt;-&lt;357.0,-74.0&gt;-&lt;358.0,-74.0&gt;&gt;/B&lt;&lt;358.0,-74.0&gt;-&lt;342.0,-75.0&gt;-&lt;325.0,-66.0&gt;&gt; = 3.576334374997269

* u18162 (U+18162): B&lt;&lt;333.0,-73.0&gt;-&lt;330.0,-73.0&gt;-&lt;331.0,-73.0&gt;&gt;/B&lt;&lt;331.0,-73.0&gt;-&lt;313.0,-74.0&gt;-&lt;298.0,-65.0&gt;&gt; = 3.1798301198641643

* u18173 (U+18173): L&lt;&lt;699.0,-74.0&gt;--&lt;699.0,115.0&gt;&gt;/B&lt;&lt;699.0,115.0&gt;-&lt;690.0,79.0&gt;-&lt;688.0,68.0&gt;&gt; = 14.036243467926484

* u181E3 (U+181E3): B&lt;&lt;408.0,122.0&gt;-&lt;425.0,102.0&gt;-&lt;448.0,72.0&gt;&gt;/L&lt;&lt;448.0,72.0&gt;--&lt;447.0,74.0&gt;&gt; = 10.911128384283376

* u1828A (U+1828A): L&lt;&lt;339.0,307.0&gt;--&lt;396.0,262.0&gt;&gt;/L&lt;&lt;396.0,262.0&gt;--&lt;393.0,265.0&gt;&gt; = 6.709836807756896

* u182ED (U+182ED): B&lt;&lt;824.0,12.0&gt;-&lt;827.0,-17.0&gt;-&lt;837.0,-19.0&gt;&gt;/B&lt;&lt;837.0,-19.0&gt;-&lt;836.0,-19.0&gt;-&lt;836.0,-19.0&gt;&gt; = 11.309932474020195

* u182F8 (U+182F8): B&lt;&lt;487.0,393.0&gt;-&lt;439.0,329.0&gt;-&lt;376.0,273.0&gt;&gt;/L&lt;&lt;376.0,273.0&gt;--&lt;380.0,276.0&gt;&gt; = 4.763641690726066

* u1835B (U+1835B): L&lt;&lt;490.0,-75.0&gt;--&lt;490.0,234.0&gt;&gt;/B&lt;&lt;490.0,234.0&gt;-&lt;471.0,149.0&gt;-&lt;467.0,116.0&gt;&gt; = 12.600159826080658

* u18392 (U+18392): B&lt;&lt;746.0,655.0&gt;-&lt;633.0,615.0&gt;-&lt;498.0,581.0&gt;&gt;/L&lt;&lt;498.0,581.0&gt;--&lt;659.0,581.0&gt;&gt; = 14.136061798147056

* u18447 (U+18447): L&lt;&lt;488.0,-82.0&gt;--&lt;488.0,250.0&gt;&gt;/B&lt;&lt;488.0,250.0&gt;-&lt;457.0,121.0&gt;-&lt;453.0,90.0&gt;&gt; = 13.512530635785994

* u184A1 (U+184A1): L&lt;&lt;423.0,693.0&gt;--&lt;643.0,746.0&gt;&gt;/L&lt;&lt;643.0,746.0&gt;--&lt;133.0,746.0&gt;&gt; = 13.544973367945516

* u184A2 (U+184A2): L&lt;&lt;423.0,693.0&gt;--&lt;643.0,746.0&gt;&gt;/L&lt;&lt;643.0,746.0&gt;--&lt;133.0,746.0&gt;&gt; = 13.544973367945516

* u184DE (U+184DE): B&lt;&lt;823.0,-18.0&gt;-&lt;826.0,-19.0&gt;-&lt;828.0,-19.0&gt;&gt;/L&lt;&lt;828.0,-19.0&gt;--&lt;824.0,-20.0&gt;&gt; = 14.036243467926484

* u185A5 (U+185A5): L&lt;&lt;253.0,562.0&gt;--&lt;717.0,647.0&gt;&gt;/L&lt;&lt;717.0,647.0&gt;--&lt;141.0,647.0&gt;&gt; = 10.380893154598164

* u185A6 (U+185A6): L&lt;&lt;253.0,562.0&gt;--&lt;717.0,647.0&gt;&gt;/L&lt;&lt;717.0,647.0&gt;--&lt;141.0,647.0&gt;&gt; = 10.380893154598164

* u185A8 (U+185A8): L&lt;&lt;253.0,561.0&gt;--&lt;717.0,646.0&gt;&gt;/L&lt;&lt;717.0,646.0&gt;--&lt;141.0,646.0&gt;&gt; = 10.380893154598164

* u185AB (U+185AB): L&lt;&lt;253.0,568.0&gt;--&lt;717.0,647.0&gt;&gt;/L&lt;&lt;717.0,647.0&gt;--&lt;141.0,647.0&gt;&gt; = 9.662446366297745

* u185AD (U+185AD): L&lt;&lt;253.0,585.0&gt;--&lt;717.0,655.0&gt;&gt;/L&lt;&lt;717.0,655.0&gt;--&lt;141.0,655.0&gt;&gt; = 8.579065518012115

* u185BB (U+185BB): L&lt;&lt;537.0,356.0&gt;--&lt;727.0,401.0&gt;&gt;/L&lt;&lt;727.0,401.0&gt;--&lt;524.0,401.0&gt;&gt; = 13.324531261890783

* u185C0 (U+185C0): L&lt;&lt;253.0,589.0&gt;--&lt;717.0,656.0&gt;&gt;/L&lt;&lt;717.0,656.0&gt;--&lt;141.0,656.0&gt;&gt; = 8.216521262247507

* u185CE (U+185CE): B&lt;&lt;640.0,321.0&gt;-&lt;642.0,303.0&gt;-&lt;632.0,292.0&gt;&gt;/B&lt;&lt;632.0,292.0&gt;-&lt;635.0,294.0&gt;-&lt;642.0,297.0&gt;&gt; = 14.036243467926457

* u185CF (U+185CF): L&lt;&lt;381.0,167.0&gt;--&lt;403.0,196.0&gt;&gt;/B&lt;&lt;403.0,196.0&gt;-&lt;391.0,185.0&gt;-&lt;381.0,185.0&gt;&gt; = 10.304846468766009

* u18676 (U+18676): L&lt;&lt;226.0,-75.0&gt;--&lt;226.0,214.0&gt;&gt;/B&lt;&lt;226.0,214.0&gt;-&lt;207.0,133.0&gt;-&lt;196.0,73.0&gt;&gt; = 13.201087175705565

* u18678 (U+18678): L&lt;&lt;227.0,-75.0&gt;--&lt;227.0,218.0&gt;&gt;/B&lt;&lt;227.0,218.0&gt;-&lt;203.0,110.0&gt;-&lt;196.0,73.0&gt;&gt; = 12.528807709151492

* u18678 (U+18678): L&lt;&lt;694.0,-75.0&gt;--&lt;694.0,210.0&gt;&gt;/B&lt;&lt;694.0,210.0&gt;-&lt;674.0,111.0&gt;-&lt;668.0,73.0&gt;&gt; = 11.421186274999258

* u1869F (U+1869F): B&lt;&lt;840.0,-17.0&gt;-&lt;843.0,-19.0&gt;-&lt;846.0,-19.0&gt;&gt;/B&lt;&lt;846.0,-19.0&gt;-&lt;842.0,-20.0&gt;-&lt;847.0,-20.0&gt;&gt; = 14.036243467926484

* u18707 (U+18707): L&lt;&lt;217.0,233.0&gt;--&lt;621.0,332.0&gt;&gt;/L&lt;&lt;621.0,332.0&gt;--&lt;230.0,332.0&gt;&gt; = 13.76897646412483

* u187E0 (U+187E0): L&lt;&lt;630.0,153.0&gt;--&lt;635.0,157.0&gt;&gt;/B&lt;&lt;635.0,157.0&gt;-&lt;597.0,134.0&gt;-&lt;547.0,113.0&gt;&gt; = 7.4748335953516625

* u187ED (U+187ED): B&lt;&lt;743.0,-37.0&gt;-&lt;743.0,-40.0&gt;-&lt;743.0,-39.0&gt;&gt;/B&lt;&lt;743.0,-39.0&gt;-&lt;739.0,-71.0&gt;-&lt;714.0,-74.0&gt;&gt; = 7.125016348901757

* u188B5 (U+188B5): L&lt;&lt;385.0,62.0&gt;--&lt;390.0,65.0&gt;&gt;/B&lt;&lt;390.0,65.0&gt;-&lt;331.0,40.0&gt;-&lt;264.0,21.0&gt;&gt; = 7.9999834722189425

* u18943 (U+18943): L&lt;&lt;280.0,621.0&gt;--&lt;212.0,607.0&gt;&gt;/L&lt;&lt;212.0,607.0&gt;--&lt;280.0,607.0&gt;&gt; = 11.633633998940427

* u18943 (U+18943): L&lt;&lt;633.0,734.0&gt;--&lt;727.0,753.0&gt;&gt;/L&lt;&lt;727.0,753.0&gt;--&lt;135.0,753.0&gt;&gt; = 11.427101593945128

* u189CC (U+189CC): B&lt;&lt;665.0,725.0&gt;-&lt;578.0,583.0&gt;-&lt;385.0,483.0&gt;&gt;/L&lt;&lt;385.0,483.0&gt;--&lt;410.0,495.0&gt;&gt; = 1.7492361457273844

* u189F1 (U+189F1): B&lt;&lt;525.0,175.0&gt;-&lt;477.0,126.0&gt;-&lt;425.0,88.0&gt;&gt;/L&lt;&lt;425.0,88.0&gt;--&lt;436.0,96.0&gt;&gt; = 0.13081205470331186

* u18AED (U+18AED): B&lt;&lt;593.0,567.0&gt;-&lt;476.0,518.0&gt;-&lt;353.0,497.0&gt;&gt;/L&lt;&lt;353.0,497.0&gt;--&lt;562.0,497.0&gt;&gt; = 9.68878656036679
</code></pre>
 [code: found-jaggy-segments]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Do outlines contain any semi-vertical or semi-horizontal lines? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/outline.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs have semi-vertical/semi-horizontal lines:</p>
<pre><code>* u17000 (U+17000): L&lt;&lt;871.0,218.0&gt;--&lt;872.0,-2.0&gt;&gt;

* u17004 (U+17004): L&lt;&lt;581.0,-1.0&gt;--&lt;578.0,682.0&gt;&gt;

* u17004 (U+17004): L&lt;&lt;645.0,642.0&gt;--&lt;647.0,291.0&gt;&gt;

* u17004 (U+17004): L&lt;&lt;647.0,269.0&gt;--&lt;648.0,14.0&gt;&gt;

* u17005 (U+17005): L&lt;&lt;891.0,218.0&gt;--&lt;892.0,-2.0&gt;&gt;

* u17006 (U+17006): L&lt;&lt;871.0,202.0&gt;--&lt;872.0,-2.0&gt;&gt;

* u17007 (U+17007): L&lt;&lt;899.0,169.0&gt;--&lt;900.0,-1.0&gt;&gt;

* u17008 (U+17008): L&lt;&lt;860.0,206.0&gt;--&lt;861.0,-2.0&gt;&gt;

* u17009 (U+17009): L&lt;&lt;871.0,202.0&gt;--&lt;872.0,-2.0&gt;&gt;

* u1700B (U+1700B): L&lt;&lt;886.0,223.0&gt;--&lt;887.0,-2.0&gt;&gt;

* u1700D (U+1700D): L&lt;&lt;892.0,218.0&gt;--&lt;893.0,-2.0&gt;&gt;

* u1700F (U+1700F): L&lt;&lt;880.0,177.0&gt;--&lt;881.0,-2.0&gt;&gt;

* u17010 (U+17010): L&lt;&lt;912.0,174.0&gt;--&lt;913.0,-4.0&gt;&gt;

* u17011 (U+17011): L&lt;&lt;856.0,218.0&gt;--&lt;857.0,-2.0&gt;&gt;

* u17012 (U+17012): L&lt;&lt;870.0,218.0&gt;--&lt;871.0,-2.0&gt;&gt;

* u17014 (U+17014): L&lt;&lt;902.0,208.0&gt;--&lt;903.0,5.0&gt;&gt;

* u17016 (U+17016): L&lt;&lt;831.0,218.0&gt;--&lt;832.0,-2.0&gt;&gt;

* u17018 (U+17018): L&lt;&lt;866.0,204.0&gt;--&lt;867.0,-2.0&gt;&gt;

* u17019 (U+17019): L&lt;&lt;885.0,218.0&gt;--&lt;886.0,-2.0&gt;&gt;

* u1701A (U+1701A): L&lt;&lt;879.0,153.0&gt;--&lt;880.0,-2.0&gt;&gt;

* u1701D (U+1701D): L&lt;&lt;900.0,207.0&gt;--&lt;901.0,5.0&gt;&gt;

* u17020 (U+17020): L&lt;&lt;898.0,218.0&gt;--&lt;899.0,-2.0&gt;&gt;

* u17021 (U+17021): L&lt;&lt;885.0,222.0&gt;--&lt;886.0,-2.0&gt;&gt;

* u17022 (U+17022): L&lt;&lt;917.0,294.0&gt;--&lt;918.0,119.0&gt;&gt;

* u17025 (U+17025): L&lt;&lt;885.0,218.0&gt;--&lt;886.0,-2.0&gt;&gt;

* u17027 (U+17027): L&lt;&lt;885.0,218.0&gt;--&lt;886.0,-2.0&gt;&gt;

* u17028 (U+17028): L&lt;&lt;862.0,203.0&gt;--&lt;863.0,-2.0&gt;&gt;

* u17029 (U+17029): L&lt;&lt;700.0,120.0&gt;--&lt;701.0,-5.0&gt;&gt;

* u17029 (U+17029): L&lt;&lt;910.0,183.0&gt;--&lt;911.0,-3.0&gt;&gt;

* u1702A (U+1702A): L&lt;&lt;885.0,218.0&gt;--&lt;886.0,-2.0&gt;&gt;

* u1702B (U+1702B): L&lt;&lt;896.0,176.0&gt;--&lt;897.0,-3.0&gt;&gt;

* u1702E (U+1702E): L&lt;&lt;889.0,218.0&gt;--&lt;890.0,-2.0&gt;&gt;

* u1702F (U+1702F): L&lt;&lt;907.0,129.0&gt;--&lt;908.0,-2.0&gt;&gt;

* u1703F (U+1703F): L&lt;&lt;909.0,150.0&gt;--&lt;910.0,9.0&gt;&gt;

* u17042 (U+17042): L&lt;&lt;904.0,153.0&gt;--&lt;905.0,-1.0&gt;&gt;

* u17044 (U+17044): L&lt;&lt;910.0,206.0&gt;--&lt;911.0,4.0&gt;&gt;

* u17048 (U+17048): L&lt;&lt;881.0,202.0&gt;--&lt;882.0,-2.0&gt;&gt;

* u1704C (U+1704C): L&lt;&lt;902.0,223.0&gt;--&lt;903.0,-2.0&gt;&gt;

* u1704D (U+1704D): L&lt;&lt;884.0,218.0&gt;--&lt;885.0,-2.0&gt;&gt;

* u17053 (U+17053): L&lt;&lt;882.0,223.0&gt;--&lt;883.0,-2.0&gt;&gt;

* u17056 (U+17056): L&lt;&lt;653.0,-3.0&gt;--&lt;811.0,-2.0&gt;&gt;

* u17056 (U+17056): L&lt;&lt;764.0,-74.0&gt;--&lt;624.0,-75.0&gt;&gt;

* u17057 (U+17057): L&lt;&lt;881.0,222.0&gt;--&lt;882.0,-3.0&gt;&gt;

* u1705B (U+1705B): L&lt;&lt;875.0,188.0&gt;--&lt;876.0,-2.0&gt;&gt;

* u1705C (U+1705C): L&lt;&lt;890.0,218.0&gt;--&lt;891.0,-2.0&gt;&gt;

* u1705D (U+1705D): L&lt;&lt;894.0,188.0&gt;--&lt;895.0,-2.0&gt;&gt;

* u17061 (U+17061): L&lt;&lt;923.0,156.0&gt;--&lt;924.0,-1.0&gt;&gt;

* u17067 (U+17067): L&lt;&lt;878.0,218.0&gt;--&lt;879.0,-2.0&gt;&gt;

* u1706E (U+1706E): L&lt;&lt;906.0,181.0&gt;--&lt;907.0,2.0&gt;&gt;

* u17073 (U+17073): L&lt;&lt;837.0,135.0&gt;--&lt;838.0,-2.0&gt;&gt;

* u17077 (U+17077): L&lt;&lt;874.0,201.0&gt;--&lt;875.0,-2.0&gt;&gt;

* u17078 (U+17078): L&lt;&lt;906.0,155.0&gt;--&lt;907.0,-2.0&gt;&gt;

* u1707A (U+1707A): L&lt;&lt;778.0,171.0&gt;--&lt;779.0,-2.0&gt;&gt;

* u1707B (U+1707B): L&lt;&lt;910.0,189.0&gt;--&lt;911.0,-2.0&gt;&gt;

* u1707F (U+1707F): L&lt;&lt;687.0,-3.0&gt;--&lt;862.0,-2.0&gt;&gt;

* u1707F (U+1707F): L&lt;&lt;815.0,-74.0&gt;--&lt;658.0,-75.0&gt;&gt;

* u17083 (U+17083): L&lt;&lt;910.0,223.0&gt;--&lt;911.0,6.0&gt;&gt;

* u17084 (U+17084): L&lt;&lt;888.0,188.0&gt;--&lt;889.0,-2.0&gt;&gt;

* u17087 (U+17087): L&lt;&lt;878.0,188.0&gt;--&lt;879.0,-2.0&gt;&gt;

* u17088 (U+17088): L&lt;&lt;898.0,221.0&gt;--&lt;899.0,-4.0&gt;&gt;

* u1708A (U+1708A): L&lt;&lt;919.0,138.0&gt;--&lt;920.0,-3.0&gt;&gt;

* u17092 (U+17092): L&lt;&lt;921.0,175.0&gt;--&lt;922.0,2.0&gt;&gt;

* u1709A (U+1709A): L&lt;&lt;882.0,188.0&gt;--&lt;883.0,-2.0&gt;&gt;

* u1709B (U+1709B): L&lt;&lt;852.0,162.0&gt;--&lt;853.0,-2.0&gt;&gt;

* u1709C (U+1709C): L&lt;&lt;230.0,-27.0&gt;--&lt;229.0,433.0&gt;&gt;

* u1709C (U+1709C): L&lt;&lt;910.0,192.0&gt;--&lt;911.0,4.0&gt;&gt;

* u1709D (U+1709D): L&lt;&lt;893.0,218.0&gt;--&lt;894.0,-2.0&gt;&gt;

* u170A1 (U+170A1): L&lt;&lt;927.0,166.0&gt;--&lt;928.0,1.0&gt;&gt;

* u170A3 (U+170A3): L&lt;&lt;908.0,189.0&gt;--&lt;909.0,-2.0&gt;&gt;

* u170A9 (U+170A9): L&lt;&lt;908.0,189.0&gt;--&lt;909.0,-2.0&gt;&gt;

* u170AD (U+170AD): L&lt;&lt;897.0,155.0&gt;--&lt;898.0,-2.0&gt;&gt;

* u170AE (U+170AE): L&lt;&lt;930.0,138.0&gt;--&lt;931.0,-3.0&gt;&gt;

* u170B1 (U+170B1): L&lt;&lt;914.0,189.0&gt;--&lt;915.0,-2.0&gt;&gt;

* u170B2 (U+170B2): L&lt;&lt;923.0,167.0&gt;--&lt;924.0,2.0&gt;&gt;

* u170B5 (U+170B5): L&lt;&lt;891.0,218.0&gt;--&lt;892.0,-2.0&gt;&gt;

* u170B7 (U+170B7): L&lt;&lt;913.0,164.0&gt;--&lt;914.0,1.0&gt;&gt;

* u170BC (U+170BC): L&lt;&lt;925.0,145.0&gt;--&lt;926.0,-1.0&gt;&gt;

* u170BD (U+170BD): L&lt;&lt;940.0,146.0&gt;--&lt;941.0,0.0&gt;&gt;

* u170BE (U+170BE): L&lt;&lt;907.0,222.0&gt;--&lt;908.0,-3.0&gt;&gt;

* u170C0 (U+170C0): L&lt;&lt;909.0,181.0&gt;--&lt;910.0,-3.0&gt;&gt;

* u170C3 (U+170C3): L&lt;&lt;903.0,196.0&gt;--&lt;904.0,-3.0&gt;&gt;

* u170C5 (U+170C5): L&lt;&lt;913.0,129.0&gt;--&lt;914.0,-1.0&gt;&gt;

* u170C7 (U+170C7): L&lt;&lt;948.0,148.0&gt;--&lt;949.0,0.0&gt;&gt;

* u170C8 (U+170C8): L&lt;&lt;878.0,218.0&gt;--&lt;879.0,-2.0&gt;&gt;

* u170C9 (U+170C9): L&lt;&lt;839.0,139.0&gt;--&lt;840.0,-4.0&gt;&gt;

* u170D2 (U+170D2): L&lt;&lt;908.0,218.0&gt;--&lt;909.0,-2.0&gt;&gt;

* u170DA (U+170DA): L&lt;&lt;868.0,218.0&gt;--&lt;869.0,-2.0&gt;&gt;

* u170DE (U+170DE): L&lt;&lt;885.0,148.0&gt;--&lt;886.0,0.0&gt;&gt;

* u170DF (U+170DF): L&lt;&lt;925.0,148.0&gt;--&lt;926.0,0.0&gt;&gt;

* u170E1 (U+170E1): L&lt;&lt;893.0,187.0&gt;--&lt;894.0,-3.0&gt;&gt;

* u170E7 (U+170E7): L&lt;&lt;870.0,141.0&gt;--&lt;871.0,-4.0&gt;&gt;

* u170E9 (U+170E9): L&lt;&lt;906.0,236.0&gt;--&lt;907.0,6.0&gt;&gt;

* u170EB (U+170EB): L&lt;&lt;901.0,241.0&gt;--&lt;902.0,-1.0&gt;&gt;

* u170ED (U+170ED): L&lt;&lt;879.0,218.0&gt;--&lt;880.0,-2.0&gt;&gt;

* u170EF (U+170EF): L&lt;&lt;868.0,134.0&gt;--&lt;869.0,-4.0&gt;&gt;

* u170F0 (U+170F0): L&lt;&lt;900.0,183.0&gt;--&lt;901.0,-3.0&gt;&gt;

* u170F1 (U+170F1): L&lt;&lt;911.0,138.0&gt;--&lt;912.0,-3.0&gt;&gt;

* u170F2 (U+170F2): L&lt;&lt;895.0,218.0&gt;--&lt;896.0,-2.0&gt;&gt;

* u170F4 (U+170F4): L&lt;&lt;911.0,116.0&gt;--&lt;912.0,-5.0&gt;&gt;

* u170FA (U+170FA): L&lt;&lt;928.0,222.0&gt;--&lt;929.0,5.0&gt;&gt;

* u170FB (U+170FB): L&lt;&lt;901.0,152.0&gt;--&lt;902.0,0.0&gt;&gt;

* u17101 (U+17101): L&lt;&lt;843.0,218.0&gt;--&lt;844.0,-2.0&gt;&gt;

* u17104 (U+17104): L&lt;&lt;587.0,-10.0&gt;--&lt;750.0,-9.0&gt;&gt;

* u17104 (U+17104): L&lt;&lt;706.0,-74.0&gt;--&lt;558.0,-75.0&gt;&gt;

* u17107 (U+17107): L&lt;&lt;836.0,135.0&gt;--&lt;837.0,-2.0&gt;&gt;

* u17108 (U+17108): L&lt;&lt;905.0,136.0&gt;--&lt;906.0,-1.0&gt;&gt;

* u1710A (U+1710A): L&lt;&lt;817.0,129.0&gt;--&lt;818.0,-1.0&gt;&gt;

* u1710F (U+1710F): L&lt;&lt;914.0,136.0&gt;--&lt;915.0,-1.0&gt;&gt;

* u17110 (U+17110): L&lt;&lt;899.0,218.0&gt;--&lt;900.0,-2.0&gt;&gt;

* u17112 (U+17112): L&lt;&lt;914.0,136.0&gt;--&lt;915.0,-1.0&gt;&gt;

* u17114 (U+17114): L&lt;&lt;875.0,166.0&gt;--&lt;876.0,-3.0&gt;&gt;

* u17119 (U+17119): L&lt;&lt;936.0,169.0&gt;--&lt;937.0,2.0&gt;&gt;

* u1711B (U+1711B): L&lt;&lt;882.0,166.0&gt;--&lt;883.0,-3.0&gt;&gt;

* u1711C (U+1711C): L&lt;&lt;926.0,136.0&gt;--&lt;927.0,-1.0&gt;&gt;

* u1711D (U+1711D): L&lt;&lt;908.0,180.0&gt;--&lt;909.0,3.0&gt;&gt;

* u17120 (U+17120): L&lt;&lt;888.0,218.0&gt;--&lt;889.0,-2.0&gt;&gt;

* u17126 (U+17126): L&lt;&lt;895.0,222.0&gt;--&lt;896.0,-3.0&gt;&gt;

* u1712F (U+1712F): L&lt;&lt;894.0,218.0&gt;--&lt;895.0,-2.0&gt;&gt;

* u17137 (U+17137): L&lt;&lt;813.0,181.0&gt;--&lt;814.0,-3.0&gt;&gt;

* u1713B (U+1713B): L&lt;&lt;894.0,218.0&gt;--&lt;895.0,-2.0&gt;&gt;

* u1713C (U+1713C): L&lt;&lt;903.0,146.0&gt;--&lt;904.0,-2.0&gt;&gt;

* u17142 (U+17142): L&lt;&lt;902.0,218.0&gt;--&lt;903.0,-2.0&gt;&gt;

* u17143 (U+17143): L&lt;&lt;894.0,218.0&gt;--&lt;895.0,-2.0&gt;&gt;

* u17144 (U+17144): L&lt;&lt;894.0,218.0&gt;--&lt;895.0,-2.0&gt;&gt;

* u17148 (U+17148): L&lt;&lt;917.0,126.0&gt;--&lt;918.0,-2.0&gt;&gt;

* u17149 (U+17149): L&lt;&lt;887.0,218.0&gt;--&lt;888.0,-2.0&gt;&gt;

* u1714B (U+1714B): L&lt;&lt;887.0,218.0&gt;--&lt;888.0,-2.0&gt;&gt;

* u1714D (U+1714D): L&lt;&lt;894.0,218.0&gt;--&lt;895.0,-2.0&gt;&gt;

* u1714F (U+1714F): L&lt;&lt;891.0,171.0&gt;--&lt;892.0,-3.0&gt;&gt;

* u17150 (U+17150): L&lt;&lt;904.0,149.0&gt;--&lt;905.0,-2.0&gt;&gt;

* u17151 (U+17151): L&lt;&lt;883.0,171.0&gt;--&lt;884.0,-3.0&gt;&gt;

* u17153 (U+17153): L&lt;&lt;897.0,222.0&gt;--&lt;898.0,-3.0&gt;&gt;

* u17158 (U+17158): L&lt;&lt;887.0,218.0&gt;--&lt;888.0,-2.0&gt;&gt;

* u1715B (U+1715B): L&lt;&lt;891.0,218.0&gt;--&lt;892.0,-2.0&gt;&gt;

* u1715D (U+1715D): L&lt;&lt;910.0,222.0&gt;--&lt;911.0,-3.0&gt;&gt;

* u17160 (U+17160): L&lt;&lt;887.0,218.0&gt;--&lt;888.0,-2.0&gt;&gt;

* u17165 (U+17165): L&lt;&lt;887.0,218.0&gt;--&lt;888.0,-2.0&gt;&gt;

* u17166 (U+17166): L&lt;&lt;896.0,218.0&gt;--&lt;897.0,-2.0&gt;&gt;

* u17167 (U+17167): L&lt;&lt;887.0,218.0&gt;--&lt;888.0,-2.0&gt;&gt;

* u17170 (U+17170): L&lt;&lt;935.0,190.0&gt;--&lt;936.0,3.0&gt;&gt;

* u17171 (U+17171): L&lt;&lt;899.0,156.0&gt;--&lt;900.0,-4.0&gt;&gt;

* u17172 (U+17172): L&lt;&lt;900.0,196.0&gt;--&lt;901.0,-3.0&gt;&gt;

* u1717B (U+1717B): L&lt;&lt;920.0,135.0&gt;--&lt;921.0,-1.0&gt;&gt;

* u1717E (U+1717E): L&lt;&lt;910.0,222.0&gt;--&lt;911.0,-3.0&gt;&gt;

* u17180 (U+17180): L&lt;&lt;897.0,218.0&gt;--&lt;898.0,-2.0&gt;&gt;

* u17182 (U+17182): L&lt;&lt;867.0,134.0&gt;--&lt;868.0,-4.0&gt;&gt;

* u17185 (U+17185): L&lt;&lt;893.0,144.0&gt;--&lt;894.0,-6.0&gt;&gt;

* u17187 (U+17187): L&lt;&lt;885.0,134.0&gt;--&lt;886.0,-4.0&gt;&gt;

* u17188 (U+17188): L&lt;&lt;946.0,186.0&gt;--&lt;947.0,3.0&gt;&gt;

* u17189 (U+17189): L&lt;&lt;942.0,135.0&gt;--&lt;943.0,-1.0&gt;&gt;

* u1718A (U+1718A): L&lt;&lt;900.0,197.0&gt;--&lt;901.0,-3.0&gt;&gt;

* u1718B (U+1718B): L&lt;&lt;871.0,134.0&gt;--&lt;872.0,-4.0&gt;&gt;

* u1718E (U+1718E): L&lt;&lt;906.0,135.0&gt;--&lt;907.0,-1.0&gt;&gt;

* u17192 (U+17192): L&lt;&lt;924.0,135.0&gt;--&lt;925.0,-1.0&gt;&gt;

* u17193 (U+17193): L&lt;&lt;900.0,144.0&gt;--&lt;901.0,-6.0&gt;&gt;

* u17198 (U+17198): L&lt;&lt;932.0,135.0&gt;--&lt;933.0,-1.0&gt;&gt;

* u17199 (U+17199): L&lt;&lt;921.0,196.0&gt;--&lt;922.0,-3.0&gt;&gt;

* u1719F (U+1719F): L&lt;&lt;907.0,218.0&gt;--&lt;908.0,-2.0&gt;&gt;

* u171A4 (U+171A4): L&lt;&lt;905.0,144.0&gt;--&lt;906.0,-6.0&gt;&gt;

* u171A5 (U+171A5): L&lt;&lt;915.0,153.0&gt;--&lt;916.0,-4.0&gt;&gt;

* u171A7 (U+171A7): L&lt;&lt;907.0,197.0&gt;--&lt;908.0,-3.0&gt;&gt;

* u171A9 (U+171A9): L&lt;&lt;934.0,114.0&gt;--&lt;935.0,-2.0&gt;&gt;

* u171AC (U+171AC): L&lt;&lt;937.0,218.0&gt;--&lt;938.0,-2.0&gt;&gt;

* u171AD (U+171AD): L&lt;&lt;935.0,125.0&gt;--&lt;936.0,-2.0&gt;&gt;

* u171AE (U+171AE): L&lt;&lt;928.0,125.0&gt;--&lt;929.0,-2.0&gt;&gt;

* u171B2 (U+171B2): L&lt;&lt;907.0,218.0&gt;--&lt;908.0,-2.0&gt;&gt;

* u171B3 (U+171B3): L&lt;&lt;924.0,135.0&gt;--&lt;925.0,-1.0&gt;&gt;

* u171B5 (U+171B5): L&lt;&lt;938.0,147.0&gt;--&lt;939.0,0.0&gt;&gt;

* u171BB (U+171BB): L&lt;&lt;896.0,197.0&gt;--&lt;897.0,-3.0&gt;&gt;

* u171BF (U+171BF): L&lt;&lt;900.0,120.0&gt;--&lt;901.0,-5.0&gt;&gt;

* u171C4 (U+171C4): L&lt;&lt;911.0,218.0&gt;--&lt;912.0,-2.0&gt;&gt;

* u171C5 (U+171C5): L&lt;&lt;925.0,222.0&gt;--&lt;926.0,5.0&gt;&gt;

* u171C6 (U+171C6): L&lt;&lt;928.0,121.0&gt;--&lt;929.0,-2.0&gt;&gt;

* u171C8 (U+171C8): L&lt;&lt;908.0,218.0&gt;--&lt;909.0,-2.0&gt;&gt;

* u171CC (U+171CC): L&lt;&lt;909.0,125.0&gt;--&lt;910.0,-2.0&gt;&gt;

* u171CE (U+171CE): L&lt;&lt;907.0,141.0&gt;--&lt;908.0,-1.0&gt;&gt;

* u171D0 (U+171D0): L&lt;&lt;597.0,-9.0&gt;--&lt;760.0,-8.0&gt;&gt;

* u171D0 (U+171D0): L&lt;&lt;715.0,-74.0&gt;--&lt;568.0,-75.0&gt;&gt;

* u171D7 (U+171D7): L&lt;&lt;898.0,218.0&gt;--&lt;899.0,-2.0&gt;&gt;

* u171D9 (U+171D9): L&lt;&lt;891.0,218.0&gt;--&lt;892.0,-2.0&gt;&gt;

* u171E1 (U+171E1): L&lt;&lt;847.0,218.0&gt;--&lt;848.0,-2.0&gt;&gt;

* u171E2 (U+171E2): L&lt;&lt;923.0,146.0&gt;--&lt;924.0,0.0&gt;&gt;

* u171E4 (U+171E4): L&lt;&lt;625.0,-9.0&gt;--&lt;797.0,-8.0&gt;&gt;

* u171E4 (U+171E4): L&lt;&lt;752.0,-74.0&gt;--&lt;596.0,-75.0&gt;&gt;

* u171E5 (U+171E5): L&lt;&lt;855.0,218.0&gt;--&lt;856.0,-2.0&gt;&gt;

* u171E7 (U+171E7): L&lt;&lt;828.0,134.0&gt;--&lt;829.0,-4.0&gt;&gt;

* u171E8 (U+171E8): L&lt;&lt;894.0,125.0&gt;--&lt;895.0,-2.0&gt;&gt;

* u171EC (U+171EC): L&lt;&lt;894.0,125.0&gt;--&lt;895.0,-2.0&gt;&gt;

* u171EF (U+171EF): L&lt;&lt;890.0,218.0&gt;--&lt;891.0,-2.0&gt;&gt;

* u171F0 (U+171F0): L&lt;&lt;890.0,218.0&gt;--&lt;891.0,-2.0&gt;&gt;

* u171F1 (U+171F1): L&lt;&lt;890.0,218.0&gt;--&lt;891.0,-2.0&gt;&gt;

* u171F2 (U+171F2): L&lt;&lt;932.0,125.0&gt;--&lt;933.0,-2.0&gt;&gt;

* u171F4 (U+171F4): L&lt;&lt;906.0,125.0&gt;--&lt;907.0,-2.0&gt;&gt;

* u171F5 (U+171F5): L&lt;&lt;577.0,-9.0&gt;--&lt;692.0,-8.0&gt;&gt;

* u171F7 (U+171F7): L&lt;&lt;590.0,-6.0&gt;--&lt;751.0,-5.0&gt;&gt;

* u171F7 (U+171F7): L&lt;&lt;705.0,-74.0&gt;--&lt;561.0,-75.0&gt;&gt;

* u171F9 (U+171F9): L&lt;&lt;824.0,178.0&gt;--&lt;825.0,-3.0&gt;&gt;

* u171FF (U+171FF): L&lt;&lt;829.0,134.0&gt;--&lt;830.0,-4.0&gt;&gt;

* u17207 (U+17207): L&lt;&lt;850.0,178.0&gt;--&lt;851.0,-3.0&gt;&gt;

* u17208 (U+17208): L&lt;&lt;892.0,178.0&gt;--&lt;893.0,-3.0&gt;&gt;

* u1720B (U+1720B): L&lt;&lt;889.0,178.0&gt;--&lt;890.0,-3.0&gt;&gt;

* u1720D (U+1720D): L&lt;&lt;877.0,167.0&gt;--&lt;878.0,-3.0&gt;&gt;

* u1720F (U+1720F): L&lt;&lt;914.0,125.0&gt;--&lt;915.0,-2.0&gt;&gt;

* u17210 (U+17210): L&lt;&lt;867.0,178.0&gt;--&lt;868.0,-3.0&gt;&gt;

* u17214 (U+17214): L&lt;&lt;873.0,166.0&gt;--&lt;874.0,-4.0&gt;&gt;

* u17216 (U+17216): L&lt;&lt;864.0,178.0&gt;--&lt;865.0,-3.0&gt;&gt;

* u17218 (U+17218): L&lt;&lt;876.0,167.0&gt;--&lt;877.0,-3.0&gt;&gt;

* u1721C (U+1721C): L&lt;&lt;818.0,178.0&gt;--&lt;819.0,-3.0&gt;&gt;

* u1721D (U+1721D): L&lt;&lt;887.0,178.0&gt;--&lt;888.0,-3.0&gt;&gt;

* u1721E (U+1721E): L&lt;&lt;906.0,125.0&gt;--&lt;907.0,-2.0&gt;&gt;

* u17220 (U+17220): L&lt;&lt;889.0,178.0&gt;--&lt;890.0,-3.0&gt;&gt;

* u17222 (U+17222): L&lt;&lt;928.0,125.0&gt;--&lt;929.0,-2.0&gt;&gt;

* u17224 (U+17224): L&lt;&lt;600.0,-3.0&gt;--&lt;801.0,-2.0&gt;&gt;

* u17224 (U+17224): L&lt;&lt;755.0,-74.0&gt;--&lt;571.0,-75.0&gt;&gt;

* u17227 (U+17227): L&lt;&lt;873.0,166.0&gt;--&lt;874.0,-4.0&gt;&gt;

* u1722D (U+1722D): L&lt;&lt;935.0,222.0&gt;--&lt;936.0,5.0&gt;&gt;

* u1722F (U+1722F): L&lt;&lt;917.0,128.0&gt;--&lt;918.0,-1.0&gt;&gt;

* u17231 (U+17231): L&lt;&lt;892.0,218.0&gt;--&lt;893.0,-2.0&gt;&gt;

* u17232 (U+17232): L&lt;&lt;903.0,218.0&gt;--&lt;904.0,-2.0&gt;&gt;

* u17235 (U+17235): L&lt;&lt;891.0,218.0&gt;--&lt;892.0,-2.0&gt;&gt;

* u17236 (U+17236): L&lt;&lt;905.0,216.0&gt;--&lt;906.0,-4.0&gt;&gt;

* u1723B (U+1723B): L&lt;&lt;852.0,219.0&gt;--&lt;853.0,-1.0&gt;&gt;

* u1724C (U+1724C): L&lt;&lt;870.0,181.0&gt;--&lt;871.0,2.0&gt;&gt;

* u1725C (U+1725C): L&lt;&lt;895.0,218.0&gt;--&lt;896.0,-2.0&gt;&gt;

* u17263 (U+17263): L&lt;&lt;904.0,218.0&gt;--&lt;905.0,-2.0&gt;&gt;

* u17266 (U+17266): L&lt;&lt;906.0,218.0&gt;--&lt;907.0,-2.0&gt;&gt;

* u1726C (U+1726C): L&lt;&lt;905.0,222.0&gt;--&lt;906.0,5.0&gt;&gt;

* u1726F (U+1726F): L&lt;&lt;899.0,135.0&gt;--&lt;900.0,-1.0&gt;&gt;

* u17271 (U+17271): L&lt;&lt;930.0,157.0&gt;--&lt;931.0,1.0&gt;&gt;

* u17272 (U+17272): L&lt;&lt;894.0,139.0&gt;--&lt;895.0,-4.0&gt;&gt;

* u17274 (U+17274): L&lt;&lt;958.0,125.0&gt;--&lt;959.0,-2.0&gt;&gt;

* u17275 (U+17275): L&lt;&lt;880.0,197.0&gt;--&lt;881.0,-3.0&gt;&gt;

* u1727A (U+1727A): L&lt;&lt;842.0,218.0&gt;--&lt;843.0,-2.0&gt;&gt;

* u1727E (U+1727E): L&lt;&lt;859.0,219.0&gt;--&lt;860.0,-1.0&gt;&gt;

* u17280 (U+17280): L&lt;&lt;914.0,169.0&gt;--&lt;915.0,-3.0&gt;&gt;

* u17285 (U+17285): L&lt;&lt;926.0,218.0&gt;--&lt;927.0,-2.0&gt;&gt;

* u17288 (U+17288): L&lt;&lt;922.0,218.0&gt;--&lt;923.0,-2.0&gt;&gt;

* u1728D (U+1728D): L&lt;&lt;841.0,180.0&gt;--&lt;842.0,-2.0&gt;&gt;

* u1728E (U+1728E): L&lt;&lt;922.0,166.0&gt;--&lt;923.0,1.0&gt;&gt;

* u1729F (U+1729F): L&lt;&lt;907.0,218.0&gt;--&lt;908.0,-2.0&gt;&gt;

* u172A2 (U+172A2): L&lt;&lt;907.0,218.0&gt;--&lt;908.0,-2.0&gt;&gt;

* u172A6 (U+172A6): L&lt;&lt;874.0,218.0&gt;--&lt;875.0,-2.0&gt;&gt;

* u172A7 (U+172A7): L&lt;&lt;879.0,218.0&gt;--&lt;880.0,-2.0&gt;&gt;

* u172AD (U+172AD): L&lt;&lt;830.0,134.0&gt;--&lt;831.0,-4.0&gt;&gt;

* u172AF (U+172AF): L&lt;&lt;874.0,218.0&gt;--&lt;875.0,-2.0&gt;&gt;

* u172B3 (U+172B3): L&lt;&lt;907.0,218.0&gt;--&lt;908.0,-2.0&gt;&gt;

* u172B4 (U+172B4): L&lt;&lt;907.0,218.0&gt;--&lt;908.0,-2.0&gt;&gt;

* u172B8 (U+172B8): L&lt;&lt;890.0,218.0&gt;--&lt;891.0,-2.0&gt;&gt;

* u172B9 (U+172B9): L&lt;&lt;907.0,218.0&gt;--&lt;908.0,-2.0&gt;&gt;

* u172BD (U+172BD): L&lt;&lt;913.0,192.0&gt;--&lt;914.0,3.0&gt;&gt;

* u172BE (U+172BE): L&lt;&lt;886.0,175.0&gt;--&lt;887.0,-3.0&gt;&gt;

* u172BF (U+172BF): L&lt;&lt;904.0,135.0&gt;--&lt;905.0,-1.0&gt;&gt;

* u172C1 (U+172C1): L&lt;&lt;917.0,219.0&gt;--&lt;918.0,-1.0&gt;&gt;

* u172C6 (U+172C6): L&lt;&lt;907.0,222.0&gt;--&lt;908.0,-3.0&gt;&gt;

* u172C9 (U+172C9): L&lt;&lt;882.0,218.0&gt;--&lt;883.0,-2.0&gt;&gt;

* u172CB (U+172CB): L&lt;&lt;874.0,218.0&gt;--&lt;875.0,-2.0&gt;&gt;

* u172D0 (U+172D0): L&lt;&lt;909.0,218.0&gt;--&lt;910.0,-2.0&gt;&gt;

* u172D1 (U+172D1): L&lt;&lt;905.0,218.0&gt;--&lt;906.0,-2.0&gt;&gt;

* u172D3 (U+172D3): L&lt;&lt;909.0,222.0&gt;--&lt;910.0,5.0&gt;&gt;

* u172D5 (U+172D5): L&lt;&lt;917.0,219.0&gt;--&lt;918.0,-1.0&gt;&gt;

* u172D6 (U+172D6): L&lt;&lt;913.0,578.0&gt;--&lt;914.0,413.0&gt;&gt;

* u172D9 (U+172D9): L&lt;&lt;935.0,171.0&gt;--&lt;936.0,1.0&gt;&gt;

* u172E0 (U+172E0): L&lt;&lt;874.0,218.0&gt;--&lt;875.0,-2.0&gt;&gt;

* u172E1 (U+172E1): L&lt;&lt;900.0,219.0&gt;--&lt;901.0,-1.0&gt;&gt;

* u172E2 (U+172E2): L&lt;&lt;911.0,133.0&gt;--&lt;912.0,-4.0&gt;&gt;

* u172E4 (U+172E4): L&lt;&lt;461.0,612.0&gt;--&lt;649.0,611.0&gt;&gt;

* u172E4 (U+172E4): L&lt;&lt;722.0,582.0&gt;--&lt;470.0,583.0&gt;&gt;

* u172E9 (U+172E9): L&lt;&lt;877.0,218.0&gt;--&lt;878.0,-2.0&gt;&gt;

* u172EA (U+172EA): L&lt;&lt;900.0,218.0&gt;--&lt;901.0,-2.0&gt;&gt;

* u172EF (U+172EF): L&lt;&lt;904.0,127.0&gt;--&lt;905.0,-4.0&gt;&gt;

* u172F1 (U+172F1): L&lt;&lt;886.0,197.0&gt;--&lt;887.0,-3.0&gt;&gt;

* u172F8 (U+172F8): L&lt;&lt;884.0,197.0&gt;--&lt;885.0,-3.0&gt;&gt;

* u172F9 (U+172F9): L&lt;&lt;907.0,125.0&gt;--&lt;908.0,-2.0&gt;&gt;

* u172FB (U+172FB): L&lt;&lt;909.0,522.0&gt;--&lt;910.0,357.0&gt;&gt;

* u17301 (U+17301): L&lt;&lt;925.0,125.0&gt;--&lt;926.0,-2.0&gt;&gt;

* u17302 (U+17302): L&lt;&lt;918.0,135.0&gt;--&lt;919.0,-1.0&gt;&gt;

* u17303 (U+17303): L&lt;&lt;900.0,218.0&gt;--&lt;901.0,-2.0&gt;&gt;

* u17308 (U+17308): L&lt;&lt;909.0,218.0&gt;--&lt;910.0,-2.0&gt;&gt;

* u1730A (U+1730A): L&lt;&lt;924.0,222.0&gt;--&lt;925.0,5.0&gt;&gt;

* u1730C (U+1730C): L&lt;&lt;900.0,218.0&gt;--&lt;901.0,-2.0&gt;&gt;

* u17313 (U+17313): L&lt;&lt;909.0,218.0&gt;--&lt;910.0,-2.0&gt;&gt;

* u17315 (U+17315): L&lt;&lt;920.0,125.0&gt;--&lt;921.0,-2.0&gt;&gt;

* u17316 (U+17316): L&lt;&lt;920.0,125.0&gt;--&lt;921.0,-2.0&gt;&gt;

* u17318 (U+17318): L&lt;&lt;928.0,135.0&gt;--&lt;929.0,-1.0&gt;&gt;

* u1731F (U+1731F): L&lt;&lt;901.0,197.0&gt;--&lt;902.0,-3.0&gt;&gt;

* u17321 (U+17321): L&lt;&lt;879.0,218.0&gt;--&lt;880.0,-2.0&gt;&gt;

* u17326 (U+17326): L&lt;&lt;906.0,218.0&gt;--&lt;907.0,-2.0&gt;&gt;

* u17327 (U+17327): L&lt;&lt;890.0,218.0&gt;--&lt;891.0,-2.0&gt;&gt;

* u1732B (U+1732B): L&lt;&lt;842.0,116.0&gt;--&lt;843.0,-5.0&gt;&gt;

* u1733D (U+1733D): L&lt;&lt;913.0,210.0&gt;--&lt;914.0,-10.0&gt;&gt;

* u17340 (U+17340): L&lt;&lt;913.0,210.0&gt;--&lt;914.0,-10.0&gt;&gt;

* u17341 (U+17341): L&lt;&lt;900.0,218.0&gt;--&lt;901.0,-2.0&gt;&gt;

* u17343 (U+17343): L&lt;&lt;912.0,218.0&gt;--&lt;913.0,-2.0&gt;&gt;

* u17344 (U+17344): L&lt;&lt;916.0,218.0&gt;--&lt;917.0,-2.0&gt;&gt;

* u17345 (U+17345): L&lt;&lt;893.0,175.0&gt;--&lt;894.0,-3.0&gt;&gt;

* u17348 (U+17348): L&lt;&lt;909.0,192.0&gt;--&lt;910.0,-14.0&gt;&gt;

* u1734A (U+1734A): L&lt;&lt;902.0,218.0&gt;--&lt;903.0,-2.0&gt;&gt;

* u1734B (U+1734B): L&lt;&lt;910.0,218.0&gt;--&lt;911.0,-2.0&gt;&gt;

* u1734C (U+1734C): L&lt;&lt;892.0,162.0&gt;--&lt;893.0,-2.0&gt;&gt;

* u1734D (U+1734D): L&lt;&lt;917.0,218.0&gt;--&lt;918.0,-2.0&gt;&gt;

* u17353 (U+17353): L&lt;&lt;909.0,218.0&gt;--&lt;910.0,-2.0&gt;&gt;

* u17356 (U+17356): L&lt;&lt;873.0,175.0&gt;--&lt;874.0,-3.0&gt;&gt;

* u1735A (U+1735A): L&lt;&lt;916.0,180.0&gt;--&lt;917.0,-15.0&gt;&gt;

* u17360 (U+17360): L&lt;&lt;896.0,126.0&gt;--&lt;897.0,-4.0&gt;&gt;

* u17364 (U+17364): L&lt;&lt;918.0,184.0&gt;--&lt;919.0,-2.0&gt;&gt;

* u17365 (U+17365): L&lt;&lt;864.0,130.0&gt;--&lt;865.0,-4.0&gt;&gt;

* u1736B (U+1736B): L&lt;&lt;910.0,125.0&gt;--&lt;911.0,-2.0&gt;&gt;

* u1736C (U+1736C): L&lt;&lt;913.0,210.0&gt;--&lt;914.0,-10.0&gt;&gt;

* u17372 (U+17372): L&lt;&lt;916.0,126.0&gt;--&lt;917.0,-1.0&gt;&gt;

* u17373 (U+17373): L&lt;&lt;931.0,167.0&gt;--&lt;932.0,2.0&gt;&gt;

* u17377 (U+17377): L&lt;&lt;909.0,218.0&gt;--&lt;910.0,-2.0&gt;&gt;

* u17378 (U+17378): L&lt;&lt;913.0,218.0&gt;--&lt;914.0,-2.0&gt;&gt;

* u1737A (U+1737A): L&lt;&lt;913.0,218.0&gt;--&lt;914.0,-2.0&gt;&gt;

* u1737C (U+1737C): L&lt;&lt;913.0,218.0&gt;--&lt;914.0,-2.0&gt;&gt;

* u1737E (U+1737E): L&lt;&lt;897.0,218.0&gt;--&lt;898.0,-2.0&gt;&gt;

* u17382 (U+17382): L&lt;&lt;907.0,167.0&gt;--&lt;908.0,2.0&gt;&gt;

* u17388 (U+17388): L&lt;&lt;912.0,219.0&gt;--&lt;913.0,-1.0&gt;&gt;

* u1738C (U+1738C): L&lt;&lt;922.0,134.0&gt;--&lt;923.0,0.0&gt;&gt;

* u1738F (U+1738F): L&lt;&lt;907.0,182.0&gt;--&lt;908.0,-3.0&gt;&gt;

* u17391 (U+17391): L&lt;&lt;899.0,175.0&gt;--&lt;900.0,-3.0&gt;&gt;

* u17392 (U+17392): L&lt;&lt;902.0,218.0&gt;--&lt;903.0,-2.0&gt;&gt;

* u17393 (U+17393): L&lt;&lt;912.0,219.0&gt;--&lt;913.0,-1.0&gt;&gt;

* u17398 (U+17398): L&lt;&lt;897.0,218.0&gt;--&lt;898.0,-2.0&gt;&gt;

* u173A1 (U+173A1): L&lt;&lt;911.0,219.0&gt;--&lt;912.0,-1.0&gt;&gt;

* u173AB (U+173AB): L&lt;&lt;896.0,218.0&gt;--&lt;897.0,-2.0&gt;&gt;

* u173AD (U+173AD): L&lt;&lt;900.0,218.0&gt;--&lt;901.0,-2.0&gt;&gt;

* u173AE (U+173AE): L&lt;&lt;834.0,134.0&gt;--&lt;835.0,-4.0&gt;&gt;

* u173B0 (U+173B0): L&lt;&lt;914.0,167.0&gt;--&lt;915.0,2.0&gt;&gt;

* u173B2 (U+173B2): L&lt;&lt;883.0,136.0&gt;--&lt;884.0,-4.0&gt;&gt;

* u173B4 (U+173B4): L&lt;&lt;785.0,218.0&gt;--&lt;786.0,-2.0&gt;&gt;

* u173B5 (U+173B5): L&lt;&lt;888.0,125.0&gt;--&lt;889.0,-2.0&gt;&gt;

* u173B6 (U+173B6): L&lt;&lt;889.0,188.0&gt;--&lt;890.0,3.0&gt;&gt;

* u173B8 (U+173B8): L&lt;&lt;845.0,185.0&gt;--&lt;846.0,-1.0&gt;&gt;

* u173B9 (U+173B9): L&lt;&lt;881.0,171.0&gt;--&lt;882.0,-3.0&gt;&gt;

* u173BB (U+173BB): L&lt;&lt;906.0,189.0&gt;--&lt;907.0,4.0&gt;&gt;

* u173BF (U+173BF): L&lt;&lt;900.0,164.0&gt;--&lt;901.0,1.0&gt;&gt;

* u173C0 (U+173C0): L&lt;&lt;889.0,218.0&gt;--&lt;890.0,-2.0&gt;&gt;

* u173C1 (U+173C1): L&lt;&lt;869.0,175.0&gt;--&lt;870.0,-3.0&gt;&gt;

* u173C2 (U+173C2): L&lt;&lt;934.0,135.0&gt;--&lt;935.0,-1.0&gt;&gt;

* u173C3 (U+173C3): L&lt;&lt;886.0,218.0&gt;--&lt;887.0,-2.0&gt;&gt;

* u173C4 (U+173C4): L&lt;&lt;893.0,130.0&gt;--&lt;894.0,-4.0&gt;&gt;

* u173C7 (U+173C7): L&lt;&lt;902.0,218.0&gt;--&lt;903.0,-2.0&gt;&gt;

* u173D2 (U+173D2): L&lt;&lt;906.0,218.0&gt;--&lt;907.0,-2.0&gt;&gt;

* u173D5 (U+173D5): L&lt;&lt;906.0,218.0&gt;--&lt;907.0,-2.0&gt;&gt;

* u173D6 (U+173D6): L&lt;&lt;902.0,218.0&gt;--&lt;903.0,-2.0&gt;&gt;

* u173D7 (U+173D7): L&lt;&lt;881.0,222.0&gt;--&lt;882.0,-3.0&gt;&gt;

* u173DB (U+173DB): L&lt;&lt;902.0,218.0&gt;--&lt;903.0,-2.0&gt;&gt;

* u173DC (U+173DC): L&lt;&lt;902.0,135.0&gt;--&lt;903.0,-1.0&gt;&gt;

* u173DE (U+173DE): L&lt;&lt;897.0,222.0&gt;--&lt;898.0,-3.0&gt;&gt;

* u173DF (U+173DF): L&lt;&lt;888.0,197.0&gt;--&lt;889.0,-3.0&gt;&gt;

* u173E4 (U+173E4): L&lt;&lt;884.0,218.0&gt;--&lt;885.0,-2.0&gt;&gt;

* u173EA (U+173EA): L&lt;&lt;940.0,148.0&gt;--&lt;941.0,0.0&gt;&gt;

* u173F0 (U+173F0): L&lt;&lt;917.0,135.0&gt;--&lt;918.0,-1.0&gt;&gt;

* u173F6 (U+173F6): L&lt;&lt;901.0,218.0&gt;--&lt;902.0,-2.0&gt;&gt;

* u173FC (U+173FC): L&lt;&lt;916.0,135.0&gt;--&lt;917.0,-1.0&gt;&gt;

* u17407 (U+17407): L&lt;&lt;885.0,273.0&gt;--&lt;886.0,117.0&gt;&gt;

* u17411 (U+17411): L&lt;&lt;837.0,153.0&gt;--&lt;838.0,-3.0&gt;&gt;

* u17412 (U+17412): L&lt;&lt;859.0,153.0&gt;--&lt;860.0,-3.0&gt;&gt;

* u17416 (U+17416): L&lt;&lt;855.0,153.0&gt;--&lt;856.0,-3.0&gt;&gt;

* u17417 (U+17417): L&lt;&lt;869.0,153.0&gt;--&lt;870.0,-3.0&gt;&gt;

* u17419 (U+17419): L&lt;&lt;870.0,153.0&gt;--&lt;871.0,-3.0&gt;&gt;

* u1741F (U+1741F): L&lt;&lt;862.0,153.0&gt;--&lt;863.0,-3.0&gt;&gt;

* u17422 (U+17422): L&lt;&lt;932.0,145.0&gt;--&lt;933.0,0.0&gt;&gt;

* u17424 (U+17424): L&lt;&lt;915.0,171.0&gt;--&lt;916.0,1.0&gt;&gt;

* u17427 (U+17427): L&lt;&lt;915.0,171.0&gt;--&lt;916.0,1.0&gt;&gt;

* u1742F (U+1742F): L&lt;&lt;868.0,166.0&gt;--&lt;869.0,-3.0&gt;&gt;

* u17431 (U+17431): L&lt;&lt;812.0,156.0&gt;--&lt;813.0,-2.0&gt;&gt;

* u17433 (U+17433): L&lt;&lt;816.0,165.0&gt;--&lt;817.0,-2.0&gt;&gt;

* u17434 (U+17434): L&lt;&lt;866.0,169.0&gt;--&lt;867.0,-2.0&gt;&gt;

* u17436 (U+17436): L&lt;&lt;849.0,166.0&gt;--&lt;850.0,-3.0&gt;&gt;

* u17443 (U+17443): L&lt;&lt;844.0,218.0&gt;--&lt;845.0,-2.0&gt;&gt;

* u17444 (U+17444): L&lt;&lt;152.0,459.0&gt;--&lt;548.0,460.0&gt;&gt;

* u17444 (U+17444): L&lt;&lt;251.0,301.0&gt;--&lt;758.0,303.0&gt;&gt;

* u17444 (U+17444): L&lt;&lt;522.0,430.0&gt;--&lt;161.0,429.0&gt;&gt;

* u17444 (U+17444): L&lt;&lt;799.0,273.0&gt;--&lt;175.0,271.0&gt;&gt;

* u17445 (U+17445): L&lt;&lt;842.0,218.0&gt;--&lt;843.0,-2.0&gt;&gt;

* u17449 (U+17449): L&lt;&lt;858.0,166.0&gt;--&lt;859.0,-3.0&gt;&gt;

* u1744B (U+1744B): L&lt;&lt;884.0,137.0&gt;--&lt;885.0,-1.0&gt;&gt;

* u1744C (U+1744C): L&lt;&lt;823.0,157.0&gt;--&lt;824.0,-4.0&gt;&gt;

* u17450 (U+17450): L&lt;&lt;145.0,530.0&gt;--&lt;587.0,531.0&gt;&gt;

* u17450 (U+17450): L&lt;&lt;234.0,339.0&gt;--&lt;468.0,340.0&gt;&gt;

* u17450 (U+17450): L&lt;&lt;468.0,310.0&gt;--&lt;169.0,309.0&gt;&gt;

* u17450 (U+17450): L&lt;&lt;533.0,340.0&gt;--&lt;788.0,341.0&gt;&gt;

* u17450 (U+17450): L&lt;&lt;571.0,501.0&gt;--&lt;154.0,500.0&gt;&gt;

* u17450 (U+17450): L&lt;&lt;830.0,311.0&gt;--&lt;533.0,310.0&gt;&gt;

* u17453 (U+17453): L&lt;&lt;859.0,218.0&gt;--&lt;860.0,-2.0&gt;&gt;

* u1745C (U+1745C): L&lt;&lt;856.0,218.0&gt;--&lt;857.0,-2.0&gt;&gt;

* u1745D (U+1745D): L&lt;&lt;883.0,217.0&gt;--&lt;884.0,-3.0&gt;&gt;

* u1745E (U+1745E): L&lt;&lt;824.0,155.0&gt;--&lt;825.0,-2.0&gt;&gt;

* u17464 (U+17464): L&lt;&lt;599.0,-6.0&gt;--&lt;763.0,-5.0&gt;&gt;

* u17464 (U+17464): L&lt;&lt;717.0,-74.0&gt;--&lt;570.0,-75.0&gt;&gt;

* u17465 (U+17465): L&lt;&lt;827.0,157.0&gt;--&lt;828.0,-2.0&gt;&gt;

* u17469 (U+17469): L&lt;&lt;909.0,111.0&gt;--&lt;910.0,-4.0&gt;&gt;

* u1746B (U+1746B): L&lt;&lt;862.0,160.0&gt;--&lt;863.0,-3.0&gt;&gt;

* u1746E (U+1746E): L&lt;&lt;856.0,218.0&gt;--&lt;857.0,-2.0&gt;&gt;

* u17471 (U+17471): L&lt;&lt;880.0,140.0&gt;--&lt;881.0,-5.0&gt;&gt;

* u17477 (U+17477): L&lt;&lt;825.0,123.0&gt;--&lt;826.0,-4.0&gt;&gt;

* u17479 (U+17479): L&lt;&lt;842.0,156.0&gt;--&lt;843.0,-7.0&gt;&gt;

* u1747B (U+1747B): L&lt;&lt;856.0,159.0&gt;--&lt;857.0,-2.0&gt;&gt;

* u1747C (U+1747C): L&lt;&lt;867.0,159.0&gt;--&lt;868.0,-2.0&gt;&gt;

* u1747E (U+1747E): L&lt;&lt;867.0,159.0&gt;--&lt;868.0,-2.0&gt;&gt;

* u17484 (U+17484): L&lt;&lt;577.0,-3.0&gt;--&lt;696.0,-2.0&gt;&gt;

* u17485 (U+17485): L&lt;&lt;817.0,134.0&gt;--&lt;818.0,-4.0&gt;&gt;

* u17488 (U+17488): L&lt;&lt;827.0,157.0&gt;--&lt;828.0,-2.0&gt;&gt;

* u17492 (U+17492): L&lt;&lt;873.0,158.0&gt;--&lt;874.0,-2.0&gt;&gt;

* u17495 (U+17495): L&lt;&lt;893.0,154.0&gt;--&lt;894.0,-4.0&gt;&gt;

* u17497 (U+17497): L&lt;&lt;819.0,127.0&gt;--&lt;820.0,-4.0&gt;&gt;

* u1749E (U+1749E): L&lt;&lt;879.0,217.0&gt;--&lt;880.0,-3.0&gt;&gt;

* u174A0 (U+174A0): L&lt;&lt;871.0,157.0&gt;--&lt;872.0,-4.0&gt;&gt;

* u174A2 (U+174A2): L&lt;&lt;876.0,120.0&gt;--&lt;877.0,-3.0&gt;&gt;

* u174A8 (U+174A8): L&lt;&lt;885.0,154.0&gt;--&lt;886.0,-4.0&gt;&gt;

* u174AB (U+174AB): L&lt;&lt;842.0,155.0&gt;--&lt;843.0,-4.0&gt;&gt;

* u174AC (U+174AC): L&lt;&lt;877.0,154.0&gt;--&lt;878.0,-4.0&gt;&gt;

* u174AD (U+174AD): L&lt;&lt;843.0,157.0&gt;--&lt;844.0,-4.0&gt;&gt;

* u174B3 (U+174B3): L&lt;&lt;880.0,157.0&gt;--&lt;881.0,-2.0&gt;&gt;

* u174B7 (U+174B7): L&lt;&lt;856.0,218.0&gt;--&lt;857.0,-2.0&gt;&gt;

* u174C3 (U+174C3): L&lt;&lt;873.0,168.0&gt;--&lt;874.0,-3.0&gt;&gt;

* u174C8 (U+174C8): L&lt;&lt;823.0,123.0&gt;--&lt;824.0,-4.0&gt;&gt;

* u174C9 (U+174C9): L&lt;&lt;837.0,123.0&gt;--&lt;838.0,-4.0&gt;&gt;

* u174CC (U+174CC): L&lt;&lt;822.0,157.0&gt;--&lt;823.0,-4.0&gt;&gt;

* u174D0 (U+174D0): L&lt;&lt;856.0,218.0&gt;--&lt;857.0,-2.0&gt;&gt;

* u174D6 (U+174D6): L&lt;&lt;860.0,124.0&gt;--&lt;861.0,-3.0&gt;&gt;

* u174D7 (U+174D7): L&lt;&lt;872.0,154.0&gt;--&lt;873.0,-4.0&gt;&gt;

* u174DA (U+174DA): L&lt;&lt;867.0,218.0&gt;--&lt;868.0,-2.0&gt;&gt;

* u174DB (U+174DB): L&lt;&lt;895.0,157.0&gt;--&lt;896.0,1.0&gt;&gt;

* u174DD (U+174DD): L&lt;&lt;885.0,136.0&gt;--&lt;886.0,-1.0&gt;&gt;

* u174E2 (U+174E2): L&lt;&lt;862.0,218.0&gt;--&lt;863.0,-2.0&gt;&gt;

* u174F0 (U+174F0): L&lt;&lt;854.0,135.0&gt;--&lt;855.0,-4.0&gt;&gt;

* u174F7 (U+174F7): L&lt;&lt;871.0,141.0&gt;--&lt;872.0,-3.0&gt;&gt;

* u174F8 (U+174F8): L&lt;&lt;854.0,153.0&gt;--&lt;855.0,-4.0&gt;&gt;

* u174F9 (U+174F9): L&lt;&lt;861.0,145.0&gt;--&lt;862.0,-3.0&gt;&gt;

* u174FB (U+174FB): L&lt;&lt;876.0,131.0&gt;--&lt;877.0,-5.0&gt;&gt;

* u174FD (U+174FD): L&lt;&lt;822.0,123.0&gt;--&lt;823.0,-4.0&gt;&gt;

* u174FF (U+174FF): L&lt;&lt;831.0,122.0&gt;--&lt;832.0,-5.0&gt;&gt;

* u17500 (U+17500): L&lt;&lt;861.0,145.0&gt;--&lt;862.0,-3.0&gt;&gt;

* u17502 (U+17502): L&lt;&lt;892.0,136.0&gt;--&lt;893.0,-1.0&gt;&gt;

* u17505 (U+17505): L&lt;&lt;881.0,147.0&gt;--&lt;882.0,0.0&gt;&gt;

* u17507 (U+17507): L&lt;&lt;815.0,123.0&gt;--&lt;816.0,-4.0&gt;&gt;

* u17514 (U+17514): L&lt;&lt;873.0,154.0&gt;--&lt;874.0,-4.0&gt;&gt;

* u17516 (U+17516): L&lt;&lt;858.0,158.0&gt;--&lt;859.0,-5.0&gt;&gt;

* u1751D (U+1751D): L&lt;&lt;868.0,158.0&gt;--&lt;869.0,-5.0&gt;&gt;

* u1751E (U+1751E): L&lt;&lt;888.0,158.0&gt;--&lt;889.0,-4.0&gt;&gt;

* u1751F (U+1751F): L&lt;&lt;867.0,158.0&gt;--&lt;868.0,-5.0&gt;&gt;

* u17520 (U+17520): L&lt;&lt;831.0,123.0&gt;--&lt;832.0,-4.0&gt;&gt;

* u17522 (U+17522): L&lt;&lt;869.0,154.0&gt;--&lt;870.0,-4.0&gt;&gt;

* u17524 (U+17524): L&lt;&lt;874.0,158.0&gt;--&lt;875.0,-5.0&gt;&gt;

* u17525 (U+17525): L&lt;&lt;858.0,158.0&gt;--&lt;859.0,-5.0&gt;&gt;

* u1752A (U+1752A): L&lt;&lt;894.0,147.0&gt;--&lt;895.0,0.0&gt;&gt;

* u1752B (U+1752B): L&lt;&lt;878.0,154.0&gt;--&lt;879.0,-4.0&gt;&gt;

* u17531 (U+17531): L&lt;&lt;858.0,158.0&gt;--&lt;859.0,-5.0&gt;&gt;

* u17533 (U+17533): L&lt;&lt;867.0,218.0&gt;--&lt;868.0,-2.0&gt;&gt;

* u17534 (U+17534): L&lt;&lt;856.0,217.0&gt;--&lt;857.0,-3.0&gt;&gt;

* u17538 (U+17538): L&lt;&lt;878.0,154.0&gt;--&lt;879.0,-4.0&gt;&gt;

* u1753B (U+1753B): L&lt;&lt;898.0,218.0&gt;--&lt;899.0,-2.0&gt;&gt;

* u1753C (U+1753C): L&lt;&lt;881.0,217.0&gt;--&lt;882.0,-3.0&gt;&gt;

* u1753F (U+1753F): L&lt;&lt;867.0,218.0&gt;--&lt;868.0,-2.0&gt;&gt;

* u17541 (U+17541): L&lt;&lt;919.0,222.0&gt;--&lt;920.0,5.0&gt;&gt;

* u17548 (U+17548): L&lt;&lt;874.0,182.0&gt;--&lt;875.0,-3.0&gt;&gt;

* u1754D (U+1754D): L&lt;&lt;904.0,133.0&gt;--&lt;905.0,-5.0&gt;&gt;

* u17551 (U+17551): L&lt;&lt;860.0,196.0&gt;--&lt;861.0,-7.0&gt;&gt;

* u17554 (U+17554): L&lt;&lt;853.0,194.0&gt;--&lt;854.0,-9.0&gt;&gt;

* u17555 (U+17555): L&lt;&lt;850.0,194.0&gt;--&lt;851.0,-9.0&gt;&gt;

* u17557 (U+17557): L&lt;&lt;807.0,187.0&gt;--&lt;808.0,-3.0&gt;&gt;

* u1755A (U+1755A): L&lt;&lt;883.0,194.0&gt;--&lt;884.0,-9.0&gt;&gt;

* u1755D (U+1755D): L&lt;&lt;875.0,171.0&gt;--&lt;876.0,-10.0&gt;&gt;

* u1755E (U+1755E): L&lt;&lt;863.0,124.0&gt;--&lt;864.0,-11.0&gt;&gt;

* u17560 (U+17560): L&lt;&lt;852.0,172.0&gt;--&lt;853.0,-3.0&gt;&gt;

* u17563 (U+17563): L&lt;&lt;851.0,118.0&gt;--&lt;852.0,-10.0&gt;&gt;

* u17567 (U+17567): L&lt;&lt;798.0,121.0&gt;--&lt;799.0,-8.0&gt;&gt;

* u1756A (U+1756A): L&lt;&lt;873.0,128.0&gt;--&lt;874.0,-11.0&gt;&gt;

* u1756D (U+1756D): L&lt;&lt;878.0,194.0&gt;--&lt;879.0,-9.0&gt;&gt;

* u1757B (U+1757B): L&lt;&lt;906.0,222.0&gt;--&lt;907.0,5.0&gt;&gt;

* u1757E (U+1757E): L&lt;&lt;903.0,200.0&gt;--&lt;904.0,-2.0&gt;&gt;

* u1757F (U+1757F): L&lt;&lt;861.0,222.0&gt;--&lt;862.0,-3.0&gt;&gt;

* u17581 (U+17581): L&lt;&lt;909.0,138.0&gt;--&lt;910.0,-3.0&gt;&gt;

* u1758B (U+1758B): L&lt;&lt;909.0,134.0&gt;--&lt;910.0,-3.0&gt;&gt;

* u1758D (U+1758D): L&lt;&lt;921.0,223.0&gt;--&lt;922.0,-2.0&gt;&gt;

* u17597 (U+17597): L&lt;&lt;891.0,128.0&gt;--&lt;892.0,-9.0&gt;&gt;

* u1759A (U+1759A): L&lt;&lt;887.0,223.0&gt;--&lt;888.0,-2.0&gt;&gt;

* u1759D (U+1759D): L&lt;&lt;889.0,214.0&gt;--&lt;890.0,-6.0&gt;&gt;

* u1759F (U+1759F): L&lt;&lt;908.0,216.0&gt;--&lt;909.0,-9.0&gt;&gt;

* u175A2 (U+175A2): L&lt;&lt;931.0,130.0&gt;--&lt;932.0,-7.0&gt;&gt;

* u175A5 (U+175A5): L&lt;&lt;899.0,181.0&gt;--&lt;900.0,-3.0&gt;&gt;

* u175AB (U+175AB): L&lt;&lt;885.0,194.0&gt;--&lt;886.0,-9.0&gt;&gt;

* u175AC (U+175AC): L&lt;&lt;921.0,223.0&gt;--&lt;922.0,-2.0&gt;&gt;

* u175B0 (U+175B0): L&lt;&lt;932.0,223.0&gt;--&lt;933.0,-2.0&gt;&gt;

* u175B4 (U+175B4): L&lt;&lt;915.0,169.0&gt;--&lt;916.0,-3.0&gt;&gt;

* u175B6 (U+175B6): L&lt;&lt;949.0,134.0&gt;--&lt;950.0,-3.0&gt;&gt;

* u175B9 (U+175B9): L&lt;&lt;944.0,148.0&gt;--&lt;945.0,1.0&gt;&gt;

* u175BA (U+175BA): L&lt;&lt;944.0,131.0&gt;--&lt;945.0,-6.0&gt;&gt;

* u175BC (U+175BC): L&lt;&lt;950.0,194.0&gt;--&lt;951.0,4.0&gt;&gt;

* u175C6 (U+175C6): L&lt;&lt;940.0,125.0&gt;--&lt;941.0,-2.0&gt;&gt;

* u175C8 (U+175C8): L&lt;&lt;919.0,170.0&gt;--&lt;920.0,1.0&gt;&gt;

* u175CA (U+175CA): L&lt;&lt;936.0,198.0&gt;--&lt;937.0,-2.0&gt;&gt;

* u175CF (U+175CF): L&lt;&lt;899.0,168.0&gt;--&lt;900.0,2.0&gt;&gt;

* u175D1 (U+175D1): L&lt;&lt;822.0,158.0&gt;--&lt;823.0,-4.0&gt;&gt;

* u175E0 (U+175E0): L&lt;&lt;906.0,214.0&gt;--&lt;907.0,-2.0&gt;&gt;

* u175E1 (U+175E1): L&lt;&lt;918.0,170.0&gt;--&lt;919.0,-4.0&gt;&gt;

* u175E2 (U+175E2): L&lt;&lt;904.0,131.0&gt;--&lt;905.0,-6.0&gt;&gt;

* u175E4 (U+175E4): L&lt;&lt;912.0,170.0&gt;--&lt;913.0,2.0&gt;&gt;

* u175E7 (U+175E7): L&lt;&lt;917.0,218.0&gt;--&lt;918.0,-2.0&gt;&gt;

* u175E8 (U+175E8): L&lt;&lt;920.0,122.0&gt;--&lt;921.0,-2.0&gt;&gt;

* u175EA (U+175EA): L&lt;&lt;901.0,189.0&gt;--&lt;902.0,-2.0&gt;&gt;

* u175EF (U+175EF): L&lt;&lt;856.0,221.0&gt;--&lt;857.0,-4.0&gt;&gt;

* u175F4 (U+175F4): L&lt;&lt;897.0,125.0&gt;--&lt;898.0,-2.0&gt;&gt;

* u175F5 (U+175F5): L&lt;&lt;923.0,135.0&gt;--&lt;924.0,-1.0&gt;&gt;

* u175F6 (U+175F6): L&lt;&lt;833.0,218.0&gt;--&lt;834.0,-2.0&gt;&gt;

* u175F7 (U+175F7): L&lt;&lt;909.0,128.0&gt;--&lt;910.0,-1.0&gt;&gt;

* u175FE (U+175FE): L&lt;&lt;903.0,218.0&gt;--&lt;904.0,-2.0&gt;&gt;

* u17602 (U+17602): L&lt;&lt;913.0,180.0&gt;--&lt;914.0,-15.0&gt;&gt;

* u17603 (U+17603): L&lt;&lt;919.0,175.0&gt;--&lt;920.0,3.0&gt;&gt;

* u1760D (U+1760D): L&lt;&lt;918.0,148.0&gt;--&lt;919.0,-4.0&gt;&gt;

* u1760F (U+1760F): L&lt;&lt;940.0,188.0&gt;--&lt;941.0,3.0&gt;&gt;

* u17611 (U+17611): L&lt;&lt;640.0,470.0&gt;--&lt;641.0,265.0&gt;&gt;

* u17614 (U+17614): L&lt;&lt;876.0,153.0&gt;--&lt;877.0,-4.0&gt;&gt;

* u17615 (U+17615): L&lt;&lt;894.0,122.0&gt;--&lt;895.0,-2.0&gt;&gt;

* u1761A (U+1761A): L&lt;&lt;896.0,219.0&gt;--&lt;897.0,-1.0&gt;&gt;

* u1761C (U+1761C): L&lt;&lt;886.0,134.0&gt;--&lt;887.0,-4.0&gt;&gt;

* u17620 (U+17620): L&lt;&lt;866.0,129.0&gt;--&lt;867.0,-2.0&gt;&gt;

* u17623 (U+17623): L&lt;&lt;878.0,197.0&gt;--&lt;879.0,-3.0&gt;&gt;

* u17627 (U+17627): L&lt;&lt;910.0,120.0&gt;--&lt;911.0,-2.0&gt;&gt;

* u17628 (U+17628): L&lt;&lt;836.0,178.0&gt;--&lt;837.0,-3.0&gt;&gt;

* u1762B (U+1762B): L&lt;&lt;871.0,154.0&gt;--&lt;872.0,-4.0&gt;&gt;

* u1762E (U+1762E): L&lt;&lt;875.0,154.0&gt;--&lt;876.0,-4.0&gt;&gt;

* u17636 (U+17636): L&lt;&lt;903.0,222.0&gt;--&lt;904.0,5.0&gt;&gt;

* u17639 (U+17639): L&lt;&lt;943.0,159.0&gt;--&lt;944.0,-4.0&gt;&gt;

* u17644 (U+17644): L&lt;&lt;902.0,218.0&gt;--&lt;903.0,-2.0&gt;&gt;

* u17645 (U+17645): L&lt;&lt;902.0,128.0&gt;--&lt;903.0,-1.0&gt;&gt;

* u1764F (U+1764F): L&lt;&lt;844.0,129.0&gt;--&lt;845.0,-2.0&gt;&gt;

* u17655 (U+17655): L&lt;&lt;938.0,188.0&gt;--&lt;939.0,3.0&gt;&gt;

* u17657 (U+17657): L&lt;&lt;908.0,218.0&gt;--&lt;909.0,-2.0&gt;&gt;

* u17658 (U+17658): L&lt;&lt;896.0,218.0&gt;--&lt;897.0,-2.0&gt;&gt;

* u17659 (U+17659): L&lt;&lt;577.0,225.0&gt;--&lt;718.0,224.0&gt;&gt;

* u17659 (U+17659): L&lt;&lt;729.0,194.0&gt;--&lt;566.0,195.0&gt;&gt;

* u17665 (U+17665): L&lt;&lt;919.0,192.0&gt;--&lt;920.0,3.0&gt;&gt;

* u17667 (U+17667): L&lt;&lt;910.0,129.0&gt;--&lt;911.0,-1.0&gt;&gt;

* u17669 (U+17669): L&lt;&lt;864.0,134.0&gt;--&lt;865.0,-4.0&gt;&gt;

* u1766C (U+1766C): L&lt;&lt;935.0,199.0&gt;--&lt;936.0,10.0&gt;&gt;

* u1766F (U+1766F): L&lt;&lt;833.0,124.0&gt;--&lt;834.0,-11.0&gt;&gt;

* u17673 (U+17673): L&lt;&lt;902.0,219.0&gt;--&lt;903.0,-6.0&gt;&gt;

* u17674 (U+17674): L&lt;&lt;908.0,216.0&gt;--&lt;909.0,-9.0&gt;&gt;

* u17675 (U+17675): L&lt;&lt;931.0,181.0&gt;--&lt;932.0,2.0&gt;&gt;

* u1767B (U+1767B): L&lt;&lt;867.0,211.0&gt;--&lt;868.0,-9.0&gt;&gt;

* u1767D (U+1767D): L&lt;&lt;903.0,223.0&gt;--&lt;904.0,-2.0&gt;&gt;

* u1767E (U+1767E): L&lt;&lt;907.0,216.0&gt;--&lt;908.0,-9.0&gt;&gt;

* u17682 (U+17682): L&lt;&lt;913.0,165.0&gt;--&lt;914.0,-4.0&gt;&gt;

* u1768C (U+1768C): L&lt;&lt;851.0,171.0&gt;--&lt;852.0,1.0&gt;&gt;

* u1768F (U+1768F): L&lt;&lt;825.0,178.0&gt;--&lt;826.0,-3.0&gt;&gt;

* u17691 (U+17691): L&lt;&lt;847.0,218.0&gt;--&lt;848.0,-2.0&gt;&gt;

* u17696 (U+17696): L&lt;&lt;891.0,128.0&gt;--&lt;892.0,-1.0&gt;&gt;

* u176A0 (U+176A0): L&lt;&lt;897.0,128.0&gt;--&lt;898.0,-1.0&gt;&gt;

* u176A2 (U+176A2): L&lt;&lt;830.0,178.0&gt;--&lt;831.0,-3.0&gt;&gt;

* u176A8 (U+176A8): L&lt;&lt;838.0,124.0&gt;--&lt;839.0,-10.0&gt;&gt;

* u176AD (U+176AD): L&lt;&lt;931.0,185.0&gt;--&lt;932.0,6.0&gt;&gt;

* u176AE (U+176AE): L&lt;&lt;889.0,124.0&gt;--&lt;890.0,-10.0&gt;&gt;

* u176AF (U+176AF): L&lt;&lt;902.0,175.0&gt;--&lt;903.0,-4.0&gt;&gt;

* u176B0 (U+176B0): L&lt;&lt;905.0,175.0&gt;--&lt;906.0,-4.0&gt;&gt;

* u176B1 (U+176B1): L&lt;&lt;843.0,157.0&gt;--&lt;844.0,-4.0&gt;&gt;

* u176B2 (U+176B2): L&lt;&lt;155.0,463.0&gt;--&lt;503.0,464.0&gt;&gt;

* u176B2 (U+176B2): L&lt;&lt;259.0,269.0&gt;--&lt;458.0,270.0&gt;&gt;

* u176B2 (U+176B2): L&lt;&lt;458.0,240.0&gt;--&lt;179.0,239.0&gt;&gt;

* u176B2 (U+176B2): L&lt;&lt;523.0,270.0&gt;--&lt;781.0,271.0&gt;&gt;

* u176B2 (U+176B2): L&lt;&lt;629.0,435.0&gt;--&lt;164.0,433.0&gt;&gt;

* u176B2 (U+176B2): L&lt;&lt;815.0,241.0&gt;--&lt;523.0,240.0&gt;&gt;

* u176B3 (U+176B3): L&lt;&lt;835.0,178.0&gt;--&lt;836.0,-3.0&gt;&gt;

* u176B5 (U+176B5): L&lt;&lt;906.0,175.0&gt;--&lt;907.0,-4.0&gt;&gt;

* u176BB (U+176BB): L&lt;&lt;827.0,129.0&gt;--&lt;828.0,-5.0&gt;&gt;

* u176C4 (U+176C4): L&lt;&lt;882.0,164.0&gt;--&lt;883.0,-3.0&gt;&gt;

* u176C6 (U+176C6): L&lt;&lt;889.0,174.0&gt;--&lt;890.0,-3.0&gt;&gt;

* u176C8 (U+176C8): L&lt;&lt;845.0,124.0&gt;--&lt;846.0,-10.0&gt;&gt;

* u176D5 (U+176D5): L&lt;&lt;137.0,585.0&gt;--&lt;577.0,586.0&gt;&gt;

* u176D5 (U+176D5): L&lt;&lt;221.0,418.0&gt;--&lt;500.0,419.0&gt;&gt;

* u176D5 (U+176D5): L&lt;&lt;558.0,419.0&gt;--&lt;795.0,420.0&gt;&gt;

* u176D5 (U+176D5): L&lt;&lt;572.0,556.0&gt;--&lt;146.0,555.0&gt;&gt;

* u176D5 (U+176D5): L&lt;&lt;661.0,389.0&gt;--&lt;166.0,388.0&gt;&gt;

* u176D5 (U+176D5): L&lt;&lt;820.0,390.0&gt;--&lt;673.0,389.0&gt;&gt;

* u176D7 (U+176D7): L&lt;&lt;884.0,124.0&gt;--&lt;885.0,-10.0&gt;&gt;

* u176DC (U+176DC): L&lt;&lt;886.0,132.0&gt;--&lt;887.0,-2.0&gt;&gt;

* u176DD (U+176DD): L&lt;&lt;892.0,124.0&gt;--&lt;893.0,-10.0&gt;&gt;

* u176DE (U+176DE): L&lt;&lt;875.0,178.0&gt;--&lt;876.0,-3.0&gt;&gt;

* u176DF (U+176DF): L&lt;&lt;908.0,124.0&gt;--&lt;909.0,-10.0&gt;&gt;

* u176E0 (U+176E0): L&lt;&lt;886.0,172.0&gt;--&lt;887.0,-3.0&gt;&gt;

* u176E4 (U+176E4): L&lt;&lt;883.0,178.0&gt;--&lt;884.0,-3.0&gt;&gt;

* u176E8 (U+176E8): L&lt;&lt;860.0,178.0&gt;--&lt;861.0,-3.0&gt;&gt;

* u176E9 (U+176E9): L&lt;&lt;902.0,124.0&gt;--&lt;903.0,-10.0&gt;&gt;

* u176EA (U+176EA): L&lt;&lt;864.0,129.0&gt;--&lt;865.0,-5.0&gt;&gt;

* u176EF (U+176EF): L&lt;&lt;821.0,114.0&gt;--&lt;822.0,-6.0&gt;&gt;

* u176F3 (U+176F3): L&lt;&lt;915.0,112.0&gt;--&lt;916.0,-4.0&gt;&gt;

* u176F6 (U+176F6): L&lt;&lt;809.0,153.0&gt;--&lt;810.0,-3.0&gt;&gt;

* u176FC (U+176FC): L&lt;&lt;823.0,127.0&gt;--&lt;824.0,-4.0&gt;&gt;

* u176FE (U+176FE): L&lt;&lt;872.0,163.0&gt;--&lt;873.0,-2.0&gt;&gt;

* u17702 (U+17702): L&lt;&lt;882.0,196.0&gt;--&lt;883.0,-2.0&gt;&gt;

* u17705 (U+17705): L&lt;&lt;917.0,176.0&gt;--&lt;918.0,-7.0&gt;&gt;

* u1770C (U+1770C): L&lt;&lt;906.0,177.0&gt;--&lt;907.0,-7.0&gt;&gt;

* u17711 (U+17711): L&lt;&lt;137.0,585.0&gt;--&lt;577.0,586.0&gt;&gt;

* u17711 (U+17711): L&lt;&lt;221.0,418.0&gt;--&lt;486.0,419.0&gt;&gt;

* u17711 (U+17711): L&lt;&lt;542.0,419.0&gt;--&lt;795.0,420.0&gt;&gt;

* u17711 (U+17711): L&lt;&lt;572.0,556.0&gt;--&lt;146.0,555.0&gt;&gt;

* u17711 (U+17711): L&lt;&lt;829.0,390.0&gt;--&lt;166.0,388.0&gt;&gt;

* u17715 (U+17715): L&lt;&lt;881.0,172.0&gt;--&lt;882.0,-3.0&gt;&gt;

* u17716 (U+17716): L&lt;&lt;834.0,153.0&gt;--&lt;835.0,-3.0&gt;&gt;

* u17718 (U+17718): L&lt;&lt;885.0,136.0&gt;--&lt;886.0,-1.0&gt;&gt;

* u1771A (U+1771A): L&lt;&lt;876.0,120.0&gt;--&lt;877.0,-3.0&gt;&gt;

* u1771D (U+1771D): L&lt;&lt;841.0,163.0&gt;--&lt;842.0,-2.0&gt;&gt;

* u1771F (U+1771F): L&lt;&lt;849.0,156.0&gt;--&lt;850.0,-7.0&gt;&gt;

* u1772C (U+1772C): L&lt;&lt;855.0,218.0&gt;--&lt;856.0,-2.0&gt;&gt;

* u17739 (U+17739): L&lt;&lt;840.0,163.0&gt;--&lt;841.0,-2.0&gt;&gt;

* u1773A (U+1773A): L&lt;&lt;837.0,163.0&gt;--&lt;838.0,-2.0&gt;&gt;

* u17744 (U+17744): L&lt;&lt;865.0,156.0&gt;--&lt;866.0,-7.0&gt;&gt;

* u17746 (U+17746): L&lt;&lt;865.0,156.0&gt;--&lt;866.0,-7.0&gt;&gt;

* u1774B (U+1774B): L&lt;&lt;859.0,156.0&gt;--&lt;860.0,-7.0&gt;&gt;

* u1774F (U+1774F): L&lt;&lt;880.0,111.0&gt;--&lt;881.0,-9.0&gt;&gt;

* u17750 (U+17750): L&lt;&lt;879.0,156.0&gt;--&lt;880.0,-7.0&gt;&gt;

* u17752 (U+17752): L&lt;&lt;865.0,156.0&gt;--&lt;866.0,-7.0&gt;&gt;

* u17753 (U+17753): L&lt;&lt;904.0,156.0&gt;--&lt;905.0,-7.0&gt;&gt;

* u17757 (U+17757): L&lt;&lt;886.0,160.0&gt;--&lt;887.0,-4.0&gt;&gt;

* u17758 (U+17758): L&lt;&lt;905.0,173.0&gt;--&lt;906.0,2.0&gt;&gt;

* u17759 (U+17759): L&lt;&lt;834.0,153.0&gt;--&lt;835.0,-3.0&gt;&gt;

* u1775C (U+1775C): L&lt;&lt;896.0,150.0&gt;--&lt;897.0,0.0&gt;&gt;

* u1775E (U+1775E): L&lt;&lt;891.0,156.0&gt;--&lt;892.0,-7.0&gt;&gt;

* u17760 (U+17760): L&lt;&lt;859.0,156.0&gt;--&lt;860.0,-7.0&gt;&gt;

* u17765 (U+17765): L&lt;&lt;883.0,156.0&gt;--&lt;884.0,-7.0&gt;&gt;

* u17766 (U+17766): L&lt;&lt;892.0,156.0&gt;--&lt;893.0,-7.0&gt;&gt;

* u17767 (U+17767): L&lt;&lt;881.0,150.0&gt;--&lt;882.0,0.0&gt;&gt;

* u1776C (U+1776C): L&lt;&lt;900.0,156.0&gt;--&lt;901.0,-7.0&gt;&gt;

* u17773 (U+17773): L&lt;&lt;861.0,156.0&gt;--&lt;862.0,-7.0&gt;&gt;

* u17779 (U+17779): L&lt;&lt;835.0,123.0&gt;--&lt;836.0,-4.0&gt;&gt;

* u1777A (U+1777A): L&lt;&lt;886.0,155.0&gt;--&lt;887.0,-8.0&gt;&gt;

* u1777F (U+1777F): L&lt;&lt;910.0,156.0&gt;--&lt;911.0,-7.0&gt;&gt;

* u17782 (U+17782): L&lt;&lt;861.0,153.0&gt;--&lt;862.0,-3.0&gt;&gt;

* u17783 (U+17783): L&lt;&lt;873.0,142.0&gt;--&lt;874.0,-5.0&gt;&gt;

* u17784 (U+17784): L&lt;&lt;900.0,156.0&gt;--&lt;901.0,-7.0&gt;&gt;

* u17788 (U+17788): L&lt;&lt;873.0,156.0&gt;--&lt;874.0,-7.0&gt;&gt;

* u1778C (U+1778C): L&lt;&lt;873.0,156.0&gt;--&lt;874.0,-7.0&gt;&gt;

* u1778D (U+1778D): L&lt;&lt;834.0,153.0&gt;--&lt;835.0,-3.0&gt;&gt;

* u17790 (U+17790): L&lt;&lt;912.0,141.0&gt;--&lt;913.0,-2.0&gt;&gt;

* u17791 (U+17791): L&lt;&lt;904.0,121.0&gt;--&lt;905.0,-8.0&gt;&gt;

* u17792 (U+17792): L&lt;&lt;907.0,141.0&gt;--&lt;908.0,-2.0&gt;&gt;

* u17793 (U+17793): L&lt;&lt;903.0,141.0&gt;--&lt;904.0,-2.0&gt;&gt;

* u17794 (U+17794): L&lt;&lt;884.0,160.0&gt;--&lt;885.0,-4.0&gt;&gt;

* u17795 (U+17795): L&lt;&lt;853.0,156.0&gt;--&lt;854.0,-7.0&gt;&gt;

* u17799 (U+17799): L&lt;&lt;911.0,150.0&gt;--&lt;912.0,0.0&gt;&gt;

* u1779A (U+1779A): L&lt;&lt;922.0,141.0&gt;--&lt;923.0,-2.0&gt;&gt;

* u1779D (U+1779D): L&lt;&lt;845.0,123.0&gt;--&lt;846.0,-4.0&gt;&gt;

* u177A0 (U+177A0): L&lt;&lt;875.0,156.0&gt;--&lt;876.0,-7.0&gt;&gt;

* u177A3 (U+177A3): L&lt;&lt;878.0,156.0&gt;--&lt;879.0,-7.0&gt;&gt;

* u177A4 (U+177A4): L&lt;&lt;886.0,156.0&gt;--&lt;887.0,-7.0&gt;&gt;

* u177AA (U+177AA): L&lt;&lt;896.0,150.0&gt;--&lt;897.0,0.0&gt;&gt;

* u177AC (U+177AC): L&lt;&lt;902.0,160.0&gt;--&lt;903.0,-4.0&gt;&gt;

* u177B1 (U+177B1): L&lt;&lt;881.0,128.0&gt;--&lt;882.0,-3.0&gt;&gt;

* u177B3 (U+177B3): L&lt;&lt;826.0,121.0&gt;--&lt;827.0,-6.0&gt;&gt;

* u177B4 (U+177B4): L&lt;&lt;869.0,153.0&gt;--&lt;870.0,-3.0&gt;&gt;

* u177B7 (U+177B7): L&lt;&lt;904.0,151.0&gt;--&lt;905.0,-8.0&gt;&gt;

* u177BA (U+177BA): L&lt;&lt;907.0,150.0&gt;--&lt;908.0,0.0&gt;&gt;

* u177BE (U+177BE): L&lt;&lt;898.0,141.0&gt;--&lt;899.0,-2.0&gt;&gt;

* u177C2 (U+177C2): L&lt;&lt;901.0,218.0&gt;--&lt;902.0,-2.0&gt;&gt;

* u177C4 (U+177C4): L&lt;&lt;878.0,156.0&gt;--&lt;879.0,-7.0&gt;&gt;

* u177C6 (U+177C6): L&lt;&lt;927.0,150.0&gt;--&lt;928.0,0.0&gt;&gt;

* u177CD (U+177CD): L&lt;&lt;856.0,217.0&gt;--&lt;857.0,-3.0&gt;&gt;

* u177CF (U+177CF): L&lt;&lt;885.0,152.0&gt;--&lt;886.0,-5.0&gt;&gt;

* u177D4 (U+177D4): L&lt;&lt;907.0,150.0&gt;--&lt;908.0,0.0&gt;&gt;

* u177DB (U+177DB): L&lt;&lt;875.0,467.0&gt;--&lt;876.0,290.0&gt;&gt;

* u177DE (U+177DE): L&lt;&lt;893.0,408.0&gt;--&lt;894.0,281.0&gt;&gt;

* u177E7 (U+177E7): L&lt;&lt;911.0,164.0&gt;--&lt;912.0,1.0&gt;&gt;

* u177EA (U+177EA): L&lt;&lt;912.0,218.0&gt;--&lt;913.0,-2.0&gt;&gt;

* u177EB (U+177EB): L&lt;&lt;884.0,175.0&gt;--&lt;885.0,-3.0&gt;&gt;

* u177EC (U+177EC): L&lt;&lt;913.0,218.0&gt;--&lt;914.0,-2.0&gt;&gt;

* u177EE (U+177EE): L&lt;&lt;905.0,171.0&gt;--&lt;906.0,1.0&gt;&gt;

* u177F0 (U+177F0): L&lt;&lt;911.0,197.0&gt;--&lt;912.0,-3.0&gt;&gt;

* u177F1 (U+177F1): L&lt;&lt;884.0,218.0&gt;--&lt;885.0,-2.0&gt;&gt;

* u177F5 (U+177F5): L&lt;&lt;891.0,218.0&gt;--&lt;892.0,-2.0&gt;&gt;

* u177F9 (U+177F9): L&lt;&lt;857.0,218.0&gt;--&lt;858.0,-2.0&gt;&gt;

* u177FB (U+177FB): L&lt;&lt;902.0,218.0&gt;--&lt;903.0,-2.0&gt;&gt;

* u17805 (U+17805): L&lt;&lt;903.0,224.0&gt;--&lt;904.0,7.0&gt;&gt;

* u17807 (U+17807): L&lt;&lt;856.0,219.0&gt;--&lt;857.0,-1.0&gt;&gt;

* u1780C (U+1780C): L&lt;&lt;894.0,219.0&gt;--&lt;895.0,-1.0&gt;&gt;

* u1780D (U+1780D): L&lt;&lt;904.0,219.0&gt;--&lt;905.0,-1.0&gt;&gt;

* u1780E (U+1780E): L&lt;&lt;896.0,218.0&gt;--&lt;897.0,-2.0&gt;&gt;

* u17812 (U+17812): L&lt;&lt;915.0,138.0&gt;--&lt;916.0,-3.0&gt;&gt;

* u17814 (U+17814): L&lt;&lt;840.0,219.0&gt;--&lt;841.0,-1.0&gt;&gt;

* u17817 (U+17817): L&lt;&lt;846.0,219.0&gt;--&lt;847.0,-1.0&gt;&gt;

* u1781C (U+1781C): L&lt;&lt;918.0,135.0&gt;--&lt;919.0,-1.0&gt;&gt;

* u17822 (U+17822): L&lt;&lt;862.0,197.0&gt;--&lt;863.0,-3.0&gt;&gt;

* u17824 (U+17824): L&lt;&lt;908.0,219.0&gt;--&lt;909.0,-1.0&gt;&gt;

* u17826 (U+17826): L&lt;&lt;903.0,219.0&gt;--&lt;904.0,-1.0&gt;&gt;

* u1782A (U+1782A): L&lt;&lt;931.0,135.0&gt;--&lt;932.0,-1.0&gt;&gt;

* u1782C (U+1782C): L&lt;&lt;950.0,157.0&gt;--&lt;951.0,1.0&gt;&gt;

* u17832 (U+17832): L&lt;&lt;903.0,219.0&gt;--&lt;904.0,-1.0&gt;&gt;

* u17837 (U+17837): L&lt;&lt;840.0,219.0&gt;--&lt;841.0,-1.0&gt;&gt;

* u17838 (U+17838): L&lt;&lt;919.0,643.0&gt;--&lt;920.0,478.0&gt;&gt;

* u17839 (U+17839): L&lt;&lt;903.0,219.0&gt;--&lt;904.0,-1.0&gt;&gt;

* u1783B (U+1783B): L&lt;&lt;924.0,135.0&gt;--&lt;925.0,-1.0&gt;&gt;

* u17843 (U+17843): L&lt;&lt;919.0,222.0&gt;--&lt;920.0,5.0&gt;&gt;

* u17844 (U+17844): L&lt;&lt;903.0,219.0&gt;--&lt;904.0,-1.0&gt;&gt;

* u17845 (U+17845): L&lt;&lt;903.0,219.0&gt;--&lt;904.0,-1.0&gt;&gt;

* u17846 (U+17846): L&lt;&lt;461.0,612.0&gt;--&lt;649.0,611.0&gt;&gt;

* u17846 (U+17846): L&lt;&lt;722.0,582.0&gt;--&lt;470.0,583.0&gt;&gt;

* u17848 (U+17848): L&lt;&lt;948.0,135.0&gt;--&lt;949.0,-1.0&gt;&gt;

* u1784B (U+1784B): L&lt;&lt;871.0,134.0&gt;--&lt;872.0,-4.0&gt;&gt;

* u1784C (U+1784C): L&lt;&lt;909.0,222.0&gt;--&lt;910.0,-3.0&gt;&gt;

* u1784E (U+1784E): L&lt;&lt;903.0,219.0&gt;--&lt;904.0,-1.0&gt;&gt;

* u17852 (U+17852): L&lt;&lt;914.0,114.0&gt;--&lt;915.0,-4.0&gt;&gt;

* u17854 (U+17854): L&lt;&lt;920.0,185.0&gt;--&lt;921.0,-4.0&gt;&gt;

* u17856 (U+17856): L&lt;&lt;892.0,114.0&gt;--&lt;893.0,-4.0&gt;&gt;

* u1785A (U+1785A): L&lt;&lt;900.0,219.0&gt;--&lt;901.0,-1.0&gt;&gt;

* u1785C (U+1785C): L&lt;&lt;924.0,135.0&gt;--&lt;925.0,-1.0&gt;&gt;

* u1785F (U+1785F): L&lt;&lt;907.0,128.0&gt;--&lt;908.0,-1.0&gt;&gt;

* u17860 (U+17860): L&lt;&lt;898.0,178.0&gt;--&lt;899.0,-3.0&gt;&gt;

* u17863 (U+17863): L&lt;&lt;888.0,178.0&gt;--&lt;889.0,-3.0&gt;&gt;

* u1786B (U+1786B): L&lt;&lt;832.0,218.0&gt;--&lt;833.0,-2.0&gt;&gt;

* u1786F (U+1786F): L&lt;&lt;906.0,192.0&gt;--&lt;907.0,3.0&gt;&gt;

* u17873 (U+17873): L&lt;&lt;896.0,175.0&gt;--&lt;897.0,-3.0&gt;&gt;

* u17874 (U+17874): L&lt;&lt;909.0,218.0&gt;--&lt;910.0,-2.0&gt;&gt;

* u17875 (U+17875): L&lt;&lt;887.0,626.0&gt;--&lt;888.0,461.0&gt;&gt;

* u17876 (U+17876): L&lt;&lt;908.0,177.0&gt;--&lt;909.0,-2.0&gt;&gt;

* u17877 (U+17877): L&lt;&lt;903.0,177.0&gt;--&lt;904.0,-2.0&gt;&gt;

* u1787C (U+1787C): L&lt;&lt;902.0,218.0&gt;--&lt;903.0,-2.0&gt;&gt;

* u17881 (U+17881): L&lt;&lt;847.0,218.0&gt;--&lt;848.0,-2.0&gt;&gt;

* u17882 (U+17882): L&lt;&lt;854.0,182.0&gt;--&lt;855.0,-4.0&gt;&gt;

* u17885 (U+17885): L&lt;&lt;886.0,148.0&gt;--&lt;887.0,-4.0&gt;&gt;

* u17887 (U+17887): L&lt;&lt;945.0,222.0&gt;--&lt;946.0,5.0&gt;&gt;

* u1788A (U+1788A): L&lt;&lt;876.0,166.0&gt;--&lt;877.0,1.0&gt;&gt;

* u1788C (U+1788C): L&lt;&lt;860.0,169.0&gt;--&lt;861.0,-3.0&gt;&gt;

* u17891 (U+17891): L&lt;&lt;827.0,124.0&gt;--&lt;828.0,-11.0&gt;&gt;

* u17896 (U+17896): L&lt;&lt;831.0,145.0&gt;--&lt;832.0,-4.0&gt;&gt;

* u1789B (U+1789B): L&lt;&lt;899.0,222.0&gt;--&lt;900.0,-3.0&gt;&gt;

* u1789C (U+1789C): L&lt;&lt;912.0,219.0&gt;--&lt;913.0,-1.0&gt;&gt;

* u1789F (U+1789F): L&lt;&lt;905.0,155.0&gt;--&lt;906.0,-2.0&gt;&gt;

* u178A0 (U+178A0): L&lt;&lt;911.0,219.0&gt;--&lt;912.0,-1.0&gt;&gt;

* u178A1 (U+178A1): L&lt;&lt;915.0,147.0&gt;--&lt;916.0,-1.0&gt;&gt;

* u178A3 (U+178A3): L&lt;&lt;911.0,219.0&gt;--&lt;912.0,-1.0&gt;&gt;

* u178A5 (U+178A5): L&lt;&lt;903.0,197.0&gt;--&lt;904.0,-3.0&gt;&gt;

* u178A6 (U+178A6): L&lt;&lt;734.0,126.0&gt;--&lt;735.0,398.0&gt;&gt;

* u178A6 (U+178A6): L&lt;&lt;794.0,155.0&gt;--&lt;793.0,14.0&gt;&gt;

* u178A6 (U+178A6): L&lt;&lt;795.0,398.0&gt;--&lt;794.0,191.0&gt;&gt;

* u178AC (U+178AC): L&lt;&lt;854.0,218.0&gt;--&lt;855.0,-2.0&gt;&gt;

* u178AD (U+178AD): L&lt;&lt;913.0,222.0&gt;--&lt;914.0,5.0&gt;&gt;

* u178B5 (U+178B5): L&lt;&lt;859.0,219.0&gt;--&lt;860.0,-1.0&gt;&gt;

* u178B9 (U+178B9): L&lt;&lt;920.0,222.0&gt;--&lt;921.0,5.0&gt;&gt;

* u178BE (U+178BE): L&lt;&lt;851.0,188.0&gt;--&lt;852.0,-2.0&gt;&gt;

* u178C2 (U+178C2): L&lt;&lt;906.0,216.0&gt;--&lt;907.0,-1.0&gt;&gt;

* u178C8 (U+178C8): L&lt;&lt;910.0,218.0&gt;--&lt;911.0,-2.0&gt;&gt;

* u178CA (U+178CA): L&lt;&lt;881.0,218.0&gt;--&lt;882.0,-2.0&gt;&gt;

* u178CB (U+178CB): L&lt;&lt;943.0,159.0&gt;--&lt;944.0,-4.0&gt;&gt;

* u178CC (U+178CC): L&lt;&lt;910.0,222.0&gt;--&lt;911.0,5.0&gt;&gt;

* u178D0 (U+178D0): L&lt;&lt;897.0,218.0&gt;--&lt;898.0,-2.0&gt;&gt;

* u178D3 (U+178D3): L&lt;&lt;914.0,192.0&gt;--&lt;915.0,3.0&gt;&gt;

* u178DA (U+178DA): L&lt;&lt;881.0,148.0&gt;--&lt;882.0,-4.0&gt;&gt;

* u178DB (U+178DB): L&lt;&lt;909.0,138.0&gt;--&lt;910.0,-3.0&gt;&gt;

* u178DC (U+178DC): L&lt;&lt;909.0,138.0&gt;--&lt;910.0,-3.0&gt;&gt;

* u178E0 (U+178E0): L&lt;&lt;904.0,167.0&gt;--&lt;905.0,2.0&gt;&gt;

* u178E1 (U+178E1): L&lt;&lt;894.0,222.0&gt;--&lt;895.0,-3.0&gt;&gt;

* u178E5 (U+178E5): L&lt;&lt;918.0,166.0&gt;--&lt;919.0,1.0&gt;&gt;

* u178E6 (U+178E6): L&lt;&lt;898.0,166.0&gt;--&lt;899.0,1.0&gt;&gt;

* u178EA (U+178EA): L&lt;&lt;919.0,222.0&gt;--&lt;920.0,5.0&gt;&gt;

* u178F1 (U+178F1): L&lt;&lt;833.0,124.0&gt;--&lt;834.0,-11.0&gt;&gt;

* u178F9 (U+178F9): L&lt;&lt;915.0,222.0&gt;--&lt;916.0,5.0&gt;&gt;

* u178FA (U+178FA): L&lt;&lt;911.0,223.0&gt;--&lt;912.0,-2.0&gt;&gt;

* u178FC (U+178FC): L&lt;&lt;898.0,175.0&gt;--&lt;899.0,-3.0&gt;&gt;

* u178FD (U+178FD): L&lt;&lt;899.0,175.0&gt;--&lt;900.0,-3.0&gt;&gt;

* u178FF (U+178FF): L&lt;&lt;896.0,218.0&gt;--&lt;897.0,-2.0&gt;&gt;

* u17900 (U+17900): L&lt;&lt;936.0,222.0&gt;--&lt;937.0,5.0&gt;&gt;

* u17904 (U+17904): L&lt;&lt;910.0,166.0&gt;--&lt;911.0,1.0&gt;&gt;

* u17907 (U+17907): L&lt;&lt;896.0,218.0&gt;--&lt;897.0,-2.0&gt;&gt;

* u1790F (U+1790F): L&lt;&lt;917.0,166.0&gt;--&lt;918.0,1.0&gt;&gt;

* u1791D (U+1791D): L&lt;&lt;910.0,218.0&gt;--&lt;911.0,-2.0&gt;&gt;

* u17921 (U+17921): L&lt;&lt;904.0,166.0&gt;--&lt;905.0,1.0&gt;&gt;

* u17923 (U+17923): L&lt;&lt;887.0,166.0&gt;--&lt;888.0,1.0&gt;&gt;

* u17924 (U+17924): L&lt;&lt;827.0,218.0&gt;--&lt;828.0,-2.0&gt;&gt;

* u1792A (U+1792A): L&lt;&lt;896.0,218.0&gt;--&lt;897.0,-2.0&gt;&gt;

* u1792C (U+1792C): L&lt;&lt;891.0,128.0&gt;--&lt;892.0,-9.0&gt;&gt;

* u1792D (U+1792D): L&lt;&lt;915.0,128.0&gt;--&lt;916.0,-1.0&gt;&gt;

* u1792F (U+1792F): L&lt;&lt;918.0,218.0&gt;--&lt;919.0,-2.0&gt;&gt;

* u17935 (U+17935): L&lt;&lt;904.0,124.0&gt;--&lt;905.0,-11.0&gt;&gt;

* u1793D (U+1793D): L&lt;&lt;881.0,218.0&gt;--&lt;882.0,-2.0&gt;&gt;

* u17945 (U+17945): L&lt;&lt;914.0,149.0&gt;--&lt;915.0,0.0&gt;&gt;

* u17949 (U+17949): L&lt;&lt;896.0,218.0&gt;--&lt;897.0,-2.0&gt;&gt;

* u17950 (U+17950): L&lt;&lt;895.0,218.0&gt;--&lt;896.0,-2.0&gt;&gt;

* u17953 (U+17953): L&lt;&lt;860.0,124.0&gt;--&lt;861.0,-11.0&gt;&gt;

* u17954 (U+17954): L&lt;&lt;907.0,218.0&gt;--&lt;908.0,-2.0&gt;&gt;

* u1795B (U+1795B): L&lt;&lt;896.0,218.0&gt;--&lt;897.0,-2.0&gt;&gt;

* u1795C (U+1795C): L&lt;&lt;898.0,166.0&gt;--&lt;899.0,1.0&gt;&gt;

* u1795E (U+1795E): L&lt;&lt;896.0,218.0&gt;--&lt;897.0,-2.0&gt;&gt;

* u1795F (U+1795F): L&lt;&lt;911.0,141.0&gt;--&lt;912.0,-1.0&gt;&gt;

* u17961 (U+17961): L&lt;&lt;862.0,218.0&gt;--&lt;863.0,-2.0&gt;&gt;

* u17964 (U+17964): L&lt;&lt;919.0,166.0&gt;--&lt;920.0,1.0&gt;&gt;

* u17966 (U+17966): L&lt;&lt;896.0,218.0&gt;--&lt;897.0,-2.0&gt;&gt;

* u17968 (U+17968): L&lt;&lt;896.0,218.0&gt;--&lt;897.0,-2.0&gt;&gt;

* u1796E (U+1796E): L&lt;&lt;896.0,218.0&gt;--&lt;897.0,-2.0&gt;&gt;

* u1796F (U+1796F): L&lt;&lt;900.0,151.0&gt;--&lt;901.0,-4.0&gt;&gt;

* u17971 (U+17971): L&lt;&lt;900.0,151.0&gt;--&lt;901.0,-4.0&gt;&gt;

* u17972 (U+17972): L&lt;&lt;896.0,218.0&gt;--&lt;897.0,-2.0&gt;&gt;

* u17973 (U+17973): L&lt;&lt;905.0,218.0&gt;--&lt;906.0,-2.0&gt;&gt;

* u17979 (U+17979): L&lt;&lt;896.0,218.0&gt;--&lt;897.0,-2.0&gt;&gt;

* u1797B (U+1797B): L&lt;&lt;896.0,218.0&gt;--&lt;897.0,-2.0&gt;&gt;

* u1797D (U+1797D): L&lt;&lt;900.0,218.0&gt;--&lt;901.0,-2.0&gt;&gt;

* u1797E (U+1797E): L&lt;&lt;900.0,218.0&gt;--&lt;901.0,-2.0&gt;&gt;

* u17983 (U+17983): L&lt;&lt;906.0,166.0&gt;--&lt;907.0,1.0&gt;&gt;

* u17985 (U+17985): L&lt;&lt;911.0,218.0&gt;--&lt;912.0,-2.0&gt;&gt;

* u17987 (U+17987): L&lt;&lt;900.0,151.0&gt;--&lt;901.0,-4.0&gt;&gt;

* u17989 (U+17989): L&lt;&lt;908.0,113.0&gt;--&lt;909.0,-3.0&gt;&gt;

* u17992 (U+17992): L&lt;&lt;915.0,222.0&gt;--&lt;916.0,-3.0&gt;&gt;

* u179A3 (U+179A3): L&lt;&lt;898.0,166.0&gt;--&lt;899.0,1.0&gt;&gt;

* u179AF (U+179AF): L&lt;&lt;910.0,218.0&gt;--&lt;911.0,-2.0&gt;&gt;

* u179B2 (U+179B2): L&lt;&lt;885.0,151.0&gt;--&lt;886.0,-4.0&gt;&gt;

* u179B5 (U+179B5): L&lt;&lt;885.0,151.0&gt;--&lt;886.0,-4.0&gt;&gt;

* u179B7 (U+179B7): L&lt;&lt;907.0,218.0&gt;--&lt;908.0,-2.0&gt;&gt;

* u179BE (U+179BE): L&lt;&lt;907.0,218.0&gt;--&lt;908.0,-2.0&gt;&gt;

* u179C5 (U+179C5): L&lt;&lt;896.0,218.0&gt;--&lt;897.0,-2.0&gt;&gt;

* u179C7 (U+179C7): L&lt;&lt;911.0,218.0&gt;--&lt;912.0,-2.0&gt;&gt;

* u179C8 (U+179C8): L&lt;&lt;920.0,133.0&gt;--&lt;921.0,-4.0&gt;&gt;

* u179CB (U+179CB): L&lt;&lt;896.0,218.0&gt;--&lt;897.0,-2.0&gt;&gt;

* u179CF (U+179CF): L&lt;&lt;911.0,218.0&gt;--&lt;912.0,-2.0&gt;&gt;

* u179D0 (U+179D0): L&lt;&lt;896.0,218.0&gt;--&lt;897.0,-2.0&gt;&gt;

* u179D2 (U+179D2): L&lt;&lt;916.0,166.0&gt;--&lt;917.0,1.0&gt;&gt;

* u179D3 (U+179D3): L&lt;&lt;917.0,139.0&gt;--&lt;918.0,-4.0&gt;&gt;

* u179DC (U+179DC): L&lt;&lt;911.0,218.0&gt;--&lt;912.0,-2.0&gt;&gt;

* u179E2 (U+179E2): L&lt;&lt;914.0,218.0&gt;--&lt;915.0,-2.0&gt;&gt;

* u179E5 (U+179E5): L&lt;&lt;849.0,124.0&gt;--&lt;850.0,-11.0&gt;&gt;

* u179E8 (U+179E8): L&lt;&lt;879.0,166.0&gt;--&lt;880.0,1.0&gt;&gt;

* u179ED (U+179ED): L&lt;&lt;909.0,547.0&gt;--&lt;910.0,382.0&gt;&gt;

* u179EF (U+179EF): L&lt;&lt;901.0,218.0&gt;--&lt;902.0,-2.0&gt;&gt;

* u179F1 (U+179F1): L&lt;&lt;893.0,124.0&gt;--&lt;894.0,-11.0&gt;&gt;

* u179F2 (U+179F2): L&lt;&lt;914.0,218.0&gt;--&lt;915.0,-2.0&gt;&gt;

* u179F5 (U+179F5): L&lt;&lt;899.0,151.0&gt;--&lt;900.0,-4.0&gt;&gt;

* u179F7 (U+179F7): L&lt;&lt;908.0,125.0&gt;--&lt;909.0,-2.0&gt;&gt;

* u179F8 (U+179F8): L&lt;&lt;908.0,125.0&gt;--&lt;909.0,-2.0&gt;&gt;

* u179FA (U+179FA): L&lt;&lt;893.0,218.0&gt;--&lt;894.0,-2.0&gt;&gt;

* u179FE (U+179FE): L&lt;&lt;900.0,223.0&gt;--&lt;901.0,-2.0&gt;&gt;

* u17A01 (U+17A01): L&lt;&lt;882.0,131.0&gt;--&lt;883.0,-4.0&gt;&gt;

* u17A04 (U+17A04): L&lt;&lt;891.0,218.0&gt;--&lt;892.0,-2.0&gt;&gt;

* u17A05 (U+17A05): L&lt;&lt;900.0,218.0&gt;--&lt;901.0,-2.0&gt;&gt;

* u17A06 (U+17A06): L&lt;&lt;919.0,120.0&gt;--&lt;920.0,-7.0&gt;&gt;

* u17A07 (U+17A07): L&lt;&lt;923.0,166.0&gt;--&lt;924.0,1.0&gt;&gt;

* u17A08 (U+17A08): L&lt;&lt;896.0,218.0&gt;--&lt;897.0,-2.0&gt;&gt;

* u17A09 (U+17A09): L&lt;&lt;903.0,218.0&gt;--&lt;904.0,-2.0&gt;&gt;

* u17A0A (U+17A0A): L&lt;&lt;891.0,218.0&gt;--&lt;892.0,-2.0&gt;&gt;

* u17A0B (U+17A0B): L&lt;&lt;891.0,218.0&gt;--&lt;892.0,-2.0&gt;&gt;

* u17A0E (U+17A0E): L&lt;&lt;874.0,218.0&gt;--&lt;875.0,-2.0&gt;&gt;

* u17A12 (U+17A12): L&lt;&lt;896.0,218.0&gt;--&lt;897.0,-2.0&gt;&gt;

* u17A13 (U+17A13): L&lt;&lt;909.0,139.0&gt;--&lt;910.0,-4.0&gt;&gt;

* u17A14 (U+17A14): L&lt;&lt;918.0,133.0&gt;--&lt;919.0,-4.0&gt;&gt;

* u17A15 (U+17A15): L&lt;&lt;932.0,133.0&gt;--&lt;933.0,-4.0&gt;&gt;

* u17A16 (U+17A16): L&lt;&lt;918.0,133.0&gt;--&lt;919.0,-4.0&gt;&gt;

* u17A1A (U+17A1A): L&lt;&lt;461.0,612.0&gt;--&lt;628.0,611.0&gt;&gt;

* u17A1A (U+17A1A): L&lt;&lt;722.0,582.0&gt;--&lt;470.0,583.0&gt;&gt;

* u17A20 (U+17A20): L&lt;&lt;900.0,218.0&gt;--&lt;901.0,-2.0&gt;&gt;

* u17A21 (U+17A21): L&lt;&lt;899.0,166.0&gt;--&lt;900.0,1.0&gt;&gt;

* u17A25 (U+17A25): L&lt;&lt;818.0,124.0&gt;--&lt;819.0,-11.0&gt;&gt;

* u17A28 (U+17A28): L&lt;&lt;900.0,218.0&gt;--&lt;901.0,-2.0&gt;&gt;

* u17A35 (U+17A35): L&lt;&lt;906.0,150.0&gt;--&lt;907.0,0.0&gt;&gt;

* u17A36 (U+17A36): L&lt;&lt;920.0,150.0&gt;--&lt;921.0,0.0&gt;&gt;

* u17A3C (U+17A3C): L&lt;&lt;892.0,165.0&gt;--&lt;893.0,-3.0&gt;&gt;

* u17A3E (U+17A3E): L&lt;&lt;871.0,139.0&gt;--&lt;872.0,-4.0&gt;&gt;

* u17A44 (U+17A44): L&lt;&lt;904.0,139.0&gt;--&lt;905.0,-4.0&gt;&gt;

* u17A4E (U+17A4E): L&lt;&lt;917.0,183.0&gt;--&lt;918.0,-3.0&gt;&gt;

* u17A51 (U+17A51): L&lt;&lt;903.0,219.0&gt;--&lt;904.0,-1.0&gt;&gt;

* u17A52 (U+17A52): L&lt;&lt;907.0,222.0&gt;--&lt;908.0,-3.0&gt;&gt;

* u17A55 (U+17A55): L&lt;&lt;917.0,139.0&gt;--&lt;918.0,-4.0&gt;&gt;

* u17A56 (U+17A56): L&lt;&lt;900.0,165.0&gt;--&lt;901.0,-3.0&gt;&gt;

* u17A58 (U+17A58): L&lt;&lt;906.0,139.0&gt;--&lt;907.0,-4.0&gt;&gt;

* u17A5C (U+17A5C): L&lt;&lt;900.0,165.0&gt;--&lt;901.0,-3.0&gt;&gt;

* u17A61 (U+17A61): L&lt;&lt;900.0,165.0&gt;--&lt;901.0,-3.0&gt;&gt;

* u17A62 (U+17A62): L&lt;&lt;925.0,133.0&gt;--&lt;926.0,-4.0&gt;&gt;

* u17A64 (U+17A64): L&lt;&lt;897.0,219.0&gt;--&lt;898.0,-1.0&gt;&gt;

* u17A67 (U+17A67): L&lt;&lt;897.0,219.0&gt;--&lt;898.0,-1.0&gt;&gt;

* u17A69 (U+17A69): L&lt;&lt;901.0,165.0&gt;--&lt;902.0,-3.0&gt;&gt;

* u17A6A (U+17A6A): L&lt;&lt;860.0,124.0&gt;--&lt;861.0,-11.0&gt;&gt;

* u17A6B (U+17A6B): L&lt;&lt;885.0,165.0&gt;--&lt;886.0,-3.0&gt;&gt;

* u17A6D (U+17A6D): L&lt;&lt;895.0,219.0&gt;--&lt;896.0,-1.0&gt;&gt;

* u17A6E (U+17A6E): L&lt;&lt;903.0,219.0&gt;--&lt;904.0,-1.0&gt;&gt;

* u17A6F (U+17A6F): L&lt;&lt;867.0,124.0&gt;--&lt;868.0,-11.0&gt;&gt;

* u17A71 (U+17A71): L&lt;&lt;894.0,219.0&gt;--&lt;895.0,-1.0&gt;&gt;

* u17A7A (U+17A7A): L&lt;&lt;896.0,218.0&gt;--&lt;897.0,-2.0&gt;&gt;

* u17A7D (U+17A7D): L&lt;&lt;917.0,183.0&gt;--&lt;918.0,-3.0&gt;&gt;

* u17A81 (U+17A81): L&lt;&lt;932.0,160.0&gt;--&lt;933.0,2.0&gt;&gt;

* u17A86 (U+17A86): L&lt;&lt;903.0,219.0&gt;--&lt;904.0,-1.0&gt;&gt;

* u17A89 (U+17A89): L&lt;&lt;896.0,218.0&gt;--&lt;897.0,-2.0&gt;&gt;

* u17A8E (U+17A8E): L&lt;&lt;879.0,166.0&gt;--&lt;880.0,1.0&gt;&gt;

* u17A8F (U+17A8F): L&lt;&lt;884.0,183.0&gt;--&lt;885.0,-3.0&gt;&gt;

* u17A95 (U+17A95): L&lt;&lt;867.0,124.0&gt;--&lt;868.0,-11.0&gt;&gt;

* u17A99 (U+17A99): L&lt;&lt;908.0,219.0&gt;--&lt;909.0,-1.0&gt;&gt;

* u17A9A (U+17A9A): L&lt;&lt;860.0,124.0&gt;--&lt;861.0,-11.0&gt;&gt;

* u17AA0 (U+17AA0): L&lt;&lt;908.0,219.0&gt;--&lt;909.0,-1.0&gt;&gt;

* u17AA5 (U+17AA5): L&lt;&lt;938.0,133.0&gt;--&lt;939.0,-4.0&gt;&gt;

* u17AA6 (U+17AA6): L&lt;&lt;933.0,133.0&gt;--&lt;934.0,-4.0&gt;&gt;

* u17AA9 (U+17AA9): L&lt;&lt;860.0,124.0&gt;--&lt;861.0,-11.0&gt;&gt;

* u17AAA (U+17AAA): L&lt;&lt;931.0,147.0&gt;--&lt;932.0,0.0&gt;&gt;

* u17AAB (U+17AAB): L&lt;&lt;924.0,147.0&gt;--&lt;925.0,0.0&gt;&gt;

* u17AAC (U+17AAC): L&lt;&lt;917.0,183.0&gt;--&lt;918.0,-3.0&gt;&gt;

* u17AAE (U+17AAE): L&lt;&lt;877.0,124.0&gt;--&lt;878.0,-11.0&gt;&gt;

* u17AAF (U+17AAF): L&lt;&lt;926.0,164.0&gt;--&lt;927.0,-2.0&gt;&gt;

* u17AB0 (U+17AB0): L&lt;&lt;920.0,164.0&gt;--&lt;921.0,-2.0&gt;&gt;

* u17AB1 (U+17AB1): L&lt;&lt;900.0,165.0&gt;--&lt;901.0,-3.0&gt;&gt;

* u17AB4 (U+17AB4): L&lt;&lt;915.0,183.0&gt;--&lt;916.0,-3.0&gt;&gt;

* u17ABB (U+17ABB): L&lt;&lt;911.0,153.0&gt;--&lt;912.0,-4.0&gt;&gt;

* u17ABC (U+17ABC): L&lt;&lt;897.0,124.0&gt;--&lt;898.0,-11.0&gt;&gt;

* u17ABD (U+17ABD): L&lt;&lt;909.0,139.0&gt;--&lt;910.0,-4.0&gt;&gt;

* u17ABF (U+17ABF): L&lt;&lt;924.0,147.0&gt;--&lt;925.0,0.0&gt;&gt;

* u17AC1 (U+17AC1): L&lt;&lt;901.0,124.0&gt;--&lt;902.0,-11.0&gt;&gt;

* u17AC2 (U+17AC2): L&lt;&lt;889.0,183.0&gt;--&lt;890.0,-3.0&gt;&gt;

* u17AC5 (U+17AC5): L&lt;&lt;927.0,133.0&gt;--&lt;928.0,-4.0&gt;&gt;

* u17AC7 (U+17AC7): L&lt;&lt;917.0,153.0&gt;--&lt;918.0,-4.0&gt;&gt;

* u17ACA (U+17ACA): L&lt;&lt;881.0,122.0&gt;--&lt;882.0,-4.0&gt;&gt;

* u17ACB (U+17ACB): L&lt;&lt;896.0,218.0&gt;--&lt;897.0,-2.0&gt;&gt;

* u17ACC (U+17ACC): L&lt;&lt;860.0,124.0&gt;--&lt;861.0,-11.0&gt;&gt;

* u17AD1 (U+17AD1): L&lt;&lt;917.0,183.0&gt;--&lt;918.0,-3.0&gt;&gt;

* u17AD5 (U+17AD5): L&lt;&lt;887.0,138.0&gt;--&lt;888.0,-6.0&gt;&gt;

* u17ADB (U+17ADB): L&lt;&lt;877.0,124.0&gt;--&lt;878.0,-11.0&gt;&gt;

* u17ADE (U+17ADE): L&lt;&lt;917.0,183.0&gt;--&lt;918.0,-3.0&gt;&gt;

* u17ADF (U+17ADF): L&lt;&lt;925.0,183.0&gt;--&lt;926.0,-3.0&gt;&gt;

* u17AE8 (U+17AE8): L&lt;&lt;920.0,170.0&gt;--&lt;921.0,1.0&gt;&gt;

* u17AE9 (U+17AE9): L&lt;&lt;903.0,138.0&gt;--&lt;904.0,-6.0&gt;&gt;

* u17AEA (U+17AEA): L&lt;&lt;903.0,138.0&gt;--&lt;904.0,-6.0&gt;&gt;

* u17AED (U+17AED): L&lt;&lt;877.0,124.0&gt;--&lt;878.0,-11.0&gt;&gt;

* u17AF0 (U+17AF0): L&lt;&lt;909.0,124.0&gt;--&lt;910.0,-3.0&gt;&gt;

* u17B14 (U+17B14): L&lt;&lt;456.0,632.0&gt;--&lt;624.0,631.0&gt;&gt;

* u17B14 (U+17B14): L&lt;&lt;719.0,602.0&gt;--&lt;465.0,603.0&gt;&gt;

* u17B15 (U+17B15): L&lt;&lt;889.0,197.0&gt;--&lt;890.0,-3.0&gt;&gt;

* u17B19 (U+17B19): L&lt;&lt;898.0,138.0&gt;--&lt;899.0,-3.0&gt;&gt;

* u17B1F (U+17B1F): L&lt;&lt;917.0,216.0&gt;--&lt;918.0,-9.0&gt;&gt;

* u17B20 (U+17B20): L&lt;&lt;905.0,216.0&gt;--&lt;906.0,-9.0&gt;&gt;

* u17B23 (U+17B23): L&lt;&lt;839.0,216.0&gt;--&lt;840.0,-9.0&gt;&gt;

* u17B24 (U+17B24): L&lt;&lt;918.0,222.0&gt;--&lt;919.0,5.0&gt;&gt;

* u17B26 (U+17B26): L&lt;&lt;901.0,138.0&gt;--&lt;902.0,-3.0&gt;&gt;

* u17B2C (U+17B2C): L&lt;&lt;887.0,220.0&gt;--&lt;888.0,-5.0&gt;&gt;

* u17B2F (U+17B2F): L&lt;&lt;914.0,168.0&gt;--&lt;915.0,-3.0&gt;&gt;

* u17B31 (U+17B31): L&lt;&lt;867.0,220.0&gt;--&lt;868.0,-5.0&gt;&gt;

* u17B32 (U+17B32): L&lt;&lt;849.0,124.0&gt;--&lt;850.0,-11.0&gt;&gt;

* u17B33 (U+17B33): L&lt;&lt;897.0,220.0&gt;--&lt;898.0,-5.0&gt;&gt;

* u17B36 (U+17B36): L&lt;&lt;901.0,167.0&gt;--&lt;902.0,3.0&gt;&gt;

* u17B46 (U+17B46): L&lt;&lt;846.0,216.0&gt;--&lt;847.0,-9.0&gt;&gt;

* u17B48 (U+17B48): L&lt;&lt;907.0,142.0&gt;--&lt;908.0,-1.0&gt;&gt;

* u17B4C (U+17B4C): L&lt;&lt;873.0,218.0&gt;--&lt;874.0,-2.0&gt;&gt;

* u17B4D (U+17B4D): L&lt;&lt;905.0,222.0&gt;--&lt;906.0,5.0&gt;&gt;

* u17B51 (U+17B51): L&lt;&lt;906.0,164.0&gt;--&lt;907.0,1.0&gt;&gt;

* u17B54 (U+17B54): L&lt;&lt;925.0,222.0&gt;--&lt;926.0,5.0&gt;&gt;

* u17B55 (U+17B55): L&lt;&lt;925.0,222.0&gt;--&lt;926.0,5.0&gt;&gt;

* u17B5C (U+17B5C): L&lt;&lt;900.0,218.0&gt;--&lt;901.0,-2.0&gt;&gt;

* u17B5F (U+17B5F): L&lt;&lt;891.0,218.0&gt;--&lt;892.0,-2.0&gt;&gt;

* u17B61 (U+17B61): L&lt;&lt;902.0,218.0&gt;--&lt;903.0,-2.0&gt;&gt;

* u17B62 (U+17B62): L&lt;&lt;904.0,218.0&gt;--&lt;905.0,-2.0&gt;&gt;

* u17B64 (U+17B64): L&lt;&lt;902.0,222.0&gt;--&lt;903.0,5.0&gt;&gt;

* u17B65 (U+17B65): L&lt;&lt;914.0,222.0&gt;--&lt;915.0,5.0&gt;&gt;

* u17B66 (U+17B66): L&lt;&lt;865.0,341.0&gt;--&lt;866.0,121.0&gt;&gt;

* u17B66 (U+17B66): L&lt;&lt;934.0,222.0&gt;--&lt;935.0,5.0&gt;&gt;

* u17B68 (U+17B68): L&lt;&lt;879.0,218.0&gt;--&lt;880.0,-2.0&gt;&gt;

* u17B6A (U+17B6A): L&lt;&lt;906.0,135.0&gt;--&lt;907.0,-1.0&gt;&gt;

* u17B6E (U+17B6E): L&lt;&lt;906.0,218.0&gt;--&lt;907.0,-2.0&gt;&gt;

* u17B70 (U+17B70): L&lt;&lt;891.0,218.0&gt;--&lt;892.0,-2.0&gt;&gt;

* u17B74 (U+17B74): L&lt;&lt;891.0,218.0&gt;--&lt;892.0,-2.0&gt;&gt;

* u17B77 (U+17B77): L&lt;&lt;889.0,218.0&gt;--&lt;890.0,-2.0&gt;&gt;

* u17B78 (U+17B78): L&lt;&lt;900.0,188.0&gt;--&lt;901.0,3.0&gt;&gt;

* u17B80 (U+17B80): L&lt;&lt;895.0,219.0&gt;--&lt;896.0,-1.0&gt;&gt;

* u17B82 (U+17B82): L&lt;&lt;893.0,219.0&gt;--&lt;894.0,-1.0&gt;&gt;

* u17B84 (U+17B84): L&lt;&lt;887.0,135.0&gt;--&lt;888.0,-1.0&gt;&gt;

* u17B85 (U+17B85): L&lt;&lt;895.0,219.0&gt;--&lt;896.0,-1.0&gt;&gt;

* u17B8C (U+17B8C): L&lt;&lt;904.0,140.0&gt;--&lt;905.0,-1.0&gt;&gt;

* u17B8D (U+17B8D): L&lt;&lt;911.0,218.0&gt;--&lt;912.0,-2.0&gt;&gt;

* u17B8E (U+17B8E): L&lt;&lt;895.0,219.0&gt;--&lt;896.0,-1.0&gt;&gt;

* u17B8F (U+17B8F): L&lt;&lt;895.0,219.0&gt;--&lt;896.0,-1.0&gt;&gt;

* u17B92 (U+17B92): L&lt;&lt;896.0,218.0&gt;--&lt;897.0,-2.0&gt;&gt;

* u17B94 (U+17B94): L&lt;&lt;890.0,124.0&gt;--&lt;891.0,-11.0&gt;&gt;

* u17B95 (U+17B95): L&lt;&lt;896.0,218.0&gt;--&lt;897.0,-2.0&gt;&gt;

* u17B97 (U+17B97): L&lt;&lt;877.0,222.0&gt;--&lt;878.0,-3.0&gt;&gt;

* u17B9A (U+17B9A): L&lt;&lt;901.0,222.0&gt;--&lt;902.0,5.0&gt;&gt;

* u17B9B (U+17B9B): L&lt;&lt;901.0,222.0&gt;--&lt;902.0,5.0&gt;&gt;

* u17B9C (U+17B9C): L&lt;&lt;901.0,222.0&gt;--&lt;902.0,5.0&gt;&gt;

* u17B9D (U+17B9D): L&lt;&lt;901.0,222.0&gt;--&lt;902.0,5.0&gt;&gt;

* u17B9E (U+17B9E): L&lt;&lt;901.0,222.0&gt;--&lt;902.0,5.0&gt;&gt;

* u17B9F (U+17B9F): L&lt;&lt;922.0,222.0&gt;--&lt;923.0,5.0&gt;&gt;

* u17BA0 (U+17BA0): L&lt;&lt;901.0,222.0&gt;--&lt;902.0,5.0&gt;&gt;

* u17BA1 (U+17BA1): L&lt;&lt;803.0,342.0&gt;--&lt;804.0,117.0&gt;&gt;

* u17BA1 (U+17BA1): L&lt;&lt;922.0,222.0&gt;--&lt;923.0,5.0&gt;&gt;

* u17BA2 (U+17BA2): L&lt;&lt;912.0,222.0&gt;--&lt;913.0,5.0&gt;&gt;

* u17BA3 (U+17BA3): L&lt;&lt;834.0,321.0&gt;--&lt;835.0,101.0&gt;&gt;

* u17BA3 (U+17BA3): L&lt;&lt;914.0,222.0&gt;--&lt;915.0,5.0&gt;&gt;

* u17BA4 (U+17BA4): L&lt;&lt;906.0,222.0&gt;--&lt;907.0,5.0&gt;&gt;

* u17BA5 (U+17BA5): L&lt;&lt;913.0,222.0&gt;--&lt;914.0,5.0&gt;&gt;

* u17BA6 (U+17BA6): L&lt;&lt;913.0,222.0&gt;--&lt;914.0,5.0&gt;&gt;

* u17BA7 (U+17BA7): L&lt;&lt;913.0,222.0&gt;--&lt;914.0,5.0&gt;&gt;

* u17BA8 (U+17BA8): L&lt;&lt;917.0,150.0&gt;--&lt;918.0,1.0&gt;&gt;

* u17BA9 (U+17BA9): L&lt;&lt;911.0,138.0&gt;--&lt;912.0,0.0&gt;&gt;

* u17BAA (U+17BAA): L&lt;&lt;907.0,222.0&gt;--&lt;908.0,5.0&gt;&gt;

* u17BAB (U+17BAB): L&lt;&lt;906.0,222.0&gt;--&lt;907.0,5.0&gt;&gt;

* u17BAC (U+17BAC): L&lt;&lt;901.0,222.0&gt;--&lt;902.0,5.0&gt;&gt;

* u17BAD (U+17BAD): L&lt;&lt;903.0,180.0&gt;--&lt;904.0,3.0&gt;&gt;

* u17BAE (U+17BAE): L&lt;&lt;903.0,180.0&gt;--&lt;904.0,3.0&gt;&gt;

* u17BAF (U+17BAF): L&lt;&lt;913.0,222.0&gt;--&lt;914.0,5.0&gt;&gt;

* u17BB0 (U+17BB0): L&lt;&lt;929.0,222.0&gt;--&lt;930.0,5.0&gt;&gt;

* u17BB1 (U+17BB1): L&lt;&lt;868.0,294.0&gt;--&lt;869.0,123.0&gt;&gt;

* u17BB1 (U+17BB1): L&lt;&lt;928.0,167.0&gt;--&lt;929.0,2.0&gt;&gt;

* u17BB2 (U+17BB2): L&lt;&lt;926.0,222.0&gt;--&lt;927.0,5.0&gt;&gt;

* u17BB3 (U+17BB3): L&lt;&lt;926.0,222.0&gt;--&lt;927.0,5.0&gt;&gt;

* u17BB4 (U+17BB4): L&lt;&lt;926.0,222.0&gt;--&lt;927.0,5.0&gt;&gt;

* u17BB5 (U+17BB5): L&lt;&lt;826.0,298.0&gt;--&lt;827.0,99.0&gt;&gt;

* u17BB5 (U+17BB5): L&lt;&lt;929.0,164.0&gt;--&lt;930.0,2.0&gt;&gt;

* u17BB6 (U+17BB6): L&lt;&lt;926.0,222.0&gt;--&lt;927.0,5.0&gt;&gt;

* u17BB7 (U+17BB7): L&lt;&lt;929.0,222.0&gt;--&lt;930.0,5.0&gt;&gt;

* u17BB8 (U+17BB8): L&lt;&lt;938.0,222.0&gt;--&lt;939.0,5.0&gt;&gt;

* u17BB9 (U+17BB9): L&lt;&lt;865.0,306.0&gt;--&lt;866.0,105.0&gt;&gt;

* u17BB9 (U+17BB9): L&lt;&lt;921.0,153.0&gt;--&lt;922.0,1.0&gt;&gt;

* u17BBA (U+17BBA): L&lt;&lt;926.0,222.0&gt;--&lt;927.0,5.0&gt;&gt;

* u17BBB (U+17BBB): L&lt;&lt;928.0,176.0&gt;--&lt;929.0,2.0&gt;&gt;

* u17BBC (U+17BBC): L&lt;&lt;921.0,222.0&gt;--&lt;922.0,5.0&gt;&gt;

* u17BBD (U+17BBD): L&lt;&lt;833.0,297.0&gt;--&lt;834.0,99.0&gt;&gt;

* u17BBD (U+17BBD): L&lt;&lt;924.0,137.0&gt;--&lt;925.0,3.0&gt;&gt;

* u17BBE (U+17BBE): L&lt;&lt;928.0,176.0&gt;--&lt;929.0,2.0&gt;&gt;

* u17BBF (U+17BBF): L&lt;&lt;924.0,114.0&gt;--&lt;925.0,-3.0&gt;&gt;

* u17BC0 (U+17BC0): L&lt;&lt;931.0,222.0&gt;--&lt;932.0,5.0&gt;&gt;

* u17BC1 (U+17BC1): L&lt;&lt;931.0,222.0&gt;--&lt;932.0,5.0&gt;&gt;

* u17BC2 (U+17BC2): L&lt;&lt;931.0,222.0&gt;--&lt;932.0,5.0&gt;&gt;

* u17BC3 (U+17BC3): L&lt;&lt;931.0,222.0&gt;--&lt;932.0,5.0&gt;&gt;

* u17BC4 (U+17BC4): L&lt;&lt;931.0,222.0&gt;--&lt;932.0,5.0&gt;&gt;

* u17BC5 (U+17BC5): L&lt;&lt;933.0,170.0&gt;--&lt;934.0,2.0&gt;&gt;

* u17BC6 (U+17BC6): L&lt;&lt;927.0,222.0&gt;--&lt;928.0,5.0&gt;&gt;

* u17BC8 (U+17BC8): L&lt;&lt;926.0,222.0&gt;--&lt;927.0,5.0&gt;&gt;

* u17BC9 (U+17BC9): L&lt;&lt;931.0,222.0&gt;--&lt;932.0,5.0&gt;&gt;

* u17BCA (U+17BCA): L&lt;&lt;869.0,286.0&gt;--&lt;870.0,103.0&gt;&gt;

* u17BCA (U+17BCA): L&lt;&lt;934.0,152.0&gt;--&lt;935.0,1.0&gt;&gt;

* u17BCB (U+17BCB): L&lt;&lt;931.0,222.0&gt;--&lt;932.0,5.0&gt;&gt;

* u17BCC (U+17BCC): L&lt;&lt;859.0,253.0&gt;--&lt;860.0,100.0&gt;&gt;

* u17BCC (U+17BCC): L&lt;&lt;934.0,128.0&gt;--&lt;935.0,-1.0&gt;&gt;

* u17BCD (U+17BCD): L&lt;&lt;870.0,253.0&gt;--&lt;871.0,101.0&gt;&gt;

* u17BCD (U+17BCD): L&lt;&lt;933.0,142.0&gt;--&lt;934.0,-1.0&gt;&gt;

* u17BCE (U+17BCE): L&lt;&lt;933.0,174.0&gt;--&lt;934.0,2.0&gt;&gt;

* u17BCF (U+17BCF): L&lt;&lt;919.0,222.0&gt;--&lt;920.0,5.0&gt;&gt;

* u17BD1 (U+17BD1): L&lt;&lt;907.0,151.0&gt;--&lt;908.0,2.0&gt;&gt;

* u17BD3 (U+17BD3): L&lt;&lt;909.0,139.0&gt;--&lt;910.0,-4.0&gt;&gt;

* u17BD5 (U+17BD5): L&lt;&lt;915.0,152.0&gt;--&lt;916.0,0.0&gt;&gt;

* u17BD6 (U+17BD6): L&lt;&lt;911.0,152.0&gt;--&lt;912.0,0.0&gt;&gt;

* u17BD7 (U+17BD7): L&lt;&lt;911.0,152.0&gt;--&lt;912.0,0.0&gt;&gt;

* u17BDB (U+17BDB): L&lt;&lt;899.0,197.0&gt;--&lt;900.0,-3.0&gt;&gt;

* u17BDC (U+17BDC): L&lt;&lt;937.0,152.0&gt;--&lt;938.0,0.0&gt;&gt;

* u17BDD (U+17BDD): L&lt;&lt;946.0,152.0&gt;--&lt;947.0,0.0&gt;&gt;

* u17BDE (U+17BDE): L&lt;&lt;889.0,197.0&gt;--&lt;890.0,-3.0&gt;&gt;

* u17BE0 (U+17BE0): L&lt;&lt;911.0,152.0&gt;--&lt;912.0,0.0&gt;&gt;

* u17BE1 (U+17BE1): L&lt;&lt;914.0,152.0&gt;--&lt;915.0,0.0&gt;&gt;

* u17BE4 (U+17BE4): L&lt;&lt;899.0,197.0&gt;--&lt;900.0,-3.0&gt;&gt;

* u17BE5 (U+17BE5): L&lt;&lt;946.0,152.0&gt;--&lt;947.0,0.0&gt;&gt;

* u17BE7 (U+17BE7): L&lt;&lt;852.0,150.0&gt;--&lt;853.0,-4.0&gt;&gt;

* u17BE8 (U+17BE8): L&lt;&lt;846.0,150.0&gt;--&lt;847.0,-4.0&gt;&gt;

* u17BE9 (U+17BE9): L&lt;&lt;879.0,197.0&gt;--&lt;880.0,-3.0&gt;&gt;

* u17BEA (U+17BEA): L&lt;&lt;877.0,197.0&gt;--&lt;878.0,-3.0&gt;&gt;

* u17BEF (U+17BEF): L&lt;&lt;882.0,222.0&gt;--&lt;883.0,-3.0&gt;&gt;

* u17C01 (U+17C01): L&lt;&lt;906.0,152.0&gt;--&lt;907.0,0.0&gt;&gt;

* u17C02 (U+17C02): L&lt;&lt;907.0,125.0&gt;--&lt;908.0,-2.0&gt;&gt;

* u17C03 (U+17C03): L&lt;&lt;897.0,197.0&gt;--&lt;898.0,-3.0&gt;&gt;

* u17C04 (U+17C04): L&lt;&lt;882.0,177.0&gt;--&lt;883.0,-3.0&gt;&gt;

* u17C05 (U+17C05): L&lt;&lt;903.0,222.0&gt;--&lt;904.0,-3.0&gt;&gt;

* u17C06 (U+17C06): L&lt;&lt;858.0,197.0&gt;--&lt;859.0,-3.0&gt;&gt;

* u17C0A (U+17C0A): L&lt;&lt;906.0,138.0&gt;--&lt;907.0,-3.0&gt;&gt;

* u17C12 (U+17C12): L&lt;&lt;876.0,197.0&gt;--&lt;877.0,-3.0&gt;&gt;

* u17C19 (U+17C19): L&lt;&lt;882.0,197.0&gt;--&lt;883.0,-3.0&gt;&gt;

* u17C1A (U+17C1A): L&lt;&lt;906.0,197.0&gt;--&lt;907.0,-3.0&gt;&gt;

* u17C1E (U+17C1E): L&lt;&lt;882.0,197.0&gt;--&lt;883.0,-3.0&gt;&gt;

* u17C1F (U+17C1F): L&lt;&lt;876.0,197.0&gt;--&lt;877.0,-3.0&gt;&gt;

* u17C21 (U+17C21): L&lt;&lt;892.0,222.0&gt;--&lt;893.0,-3.0&gt;&gt;

* u17C22 (U+17C22): L&lt;&lt;891.0,197.0&gt;--&lt;892.0,-3.0&gt;&gt;

* u17C26 (U+17C26): L&lt;&lt;879.0,124.0&gt;--&lt;880.0,-11.0&gt;&gt;

* u17C29 (U+17C29): L&lt;&lt;904.0,222.0&gt;--&lt;905.0,-3.0&gt;&gt;

* u17C2A (U+17C2A): L&lt;&lt;814.0,301.0&gt;--&lt;815.0,101.0&gt;&gt;

* u17C2A (U+17C2A): L&lt;&lt;913.0,222.0&gt;--&lt;914.0,5.0&gt;&gt;

* u17C31 (U+17C31): L&lt;&lt;900.0,125.0&gt;--&lt;901.0,-2.0&gt;&gt;

* u17C32 (U+17C32): L&lt;&lt;888.0,125.0&gt;--&lt;889.0,-2.0&gt;&gt;

* u17C37 (U+17C37): L&lt;&lt;899.0,222.0&gt;--&lt;900.0,5.0&gt;&gt;

* u17C38 (U+17C38): L&lt;&lt;875.0,139.0&gt;--&lt;876.0,-4.0&gt;&gt;

* u17C3E (U+17C3E): L&lt;&lt;913.0,152.0&gt;--&lt;914.0,0.0&gt;&gt;

* u17C41 (U+17C41): L&lt;&lt;905.0,197.0&gt;--&lt;906.0,-3.0&gt;&gt;

* u17C43 (U+17C43): L&lt;&lt;905.0,197.0&gt;--&lt;906.0,-3.0&gt;&gt;

* u17C44 (U+17C44): L&lt;&lt;905.0,197.0&gt;--&lt;906.0,-3.0&gt;&gt;

* u17C45 (U+17C45): L&lt;&lt;907.0,139.0&gt;--&lt;908.0,-4.0&gt;&gt;

* u17C46 (U+17C46): L&lt;&lt;905.0,197.0&gt;--&lt;906.0,-3.0&gt;&gt;

* u17C47 (U+17C47): L&lt;&lt;889.0,124.0&gt;--&lt;890.0,-11.0&gt;&gt;

* u17C49 (U+17C49): L&lt;&lt;907.0,125.0&gt;--&lt;908.0,-2.0&gt;&gt;

* u17C4A (U+17C4A): L&lt;&lt;908.0,154.0&gt;--&lt;909.0,0.0&gt;&gt;

* u17C4B (U+17C4B): L&lt;&lt;914.0,160.0&gt;--&lt;915.0,2.0&gt;&gt;

* u17C55 (U+17C55): L&lt;&lt;860.0,150.0&gt;--&lt;861.0,-4.0&gt;&gt;

* u17C59 (U+17C59): L&lt;&lt;886.0,218.0&gt;--&lt;887.0,-2.0&gt;&gt;

* u17C60 (U+17C60): L&lt;&lt;914.0,152.0&gt;--&lt;915.0,0.0&gt;&gt;

* u17C68 (U+17C68): L&lt;&lt;875.0,152.0&gt;--&lt;876.0,0.0&gt;&gt;

* u17C6A (U+17C6A): L&lt;&lt;878.0,150.0&gt;--&lt;879.0,-4.0&gt;&gt;

* u17C74 (U+17C74): L&lt;&lt;849.0,150.0&gt;--&lt;850.0,-4.0&gt;&gt;

* u17C75 (U+17C75): L&lt;&lt;900.0,152.0&gt;--&lt;901.0,0.0&gt;&gt;

* u17C76 (U+17C76): L&lt;&lt;877.0,150.0&gt;--&lt;878.0,-4.0&gt;&gt;

* u17C79 (U+17C79): L&lt;&lt;847.0,147.0&gt;--&lt;848.0,-7.0&gt;&gt;

* u17C7B (U+17C7B): L&lt;&lt;883.0,150.0&gt;--&lt;884.0,-4.0&gt;&gt;

* u17C7E (U+17C7E): L&lt;&lt;832.0,123.0&gt;--&lt;833.0,-4.0&gt;&gt;

* u17C7F (U+17C7F): L&lt;&lt;901.0,152.0&gt;--&lt;902.0,0.0&gt;&gt;

* u17C83 (U+17C83): L&lt;&lt;856.0,150.0&gt;--&lt;857.0,-4.0&gt;&gt;

* u17C84 (U+17C84): L&lt;&lt;818.0,123.0&gt;--&lt;819.0,-4.0&gt;&gt;

* u17C88 (U+17C88): L&lt;&lt;883.0,150.0&gt;--&lt;884.0,-4.0&gt;&gt;

* u17C8A (U+17C8A): L&lt;&lt;892.0,165.0&gt;--&lt;893.0,1.0&gt;&gt;

* u17C8E (U+17C8E): L&lt;&lt;874.0,150.0&gt;--&lt;875.0,-4.0&gt;&gt;

* u17C8F (U+17C8F): L&lt;&lt;864.0,147.0&gt;--&lt;865.0,-4.0&gt;&gt;

* u17C9C (U+17C9C): L&lt;&lt;864.0,155.0&gt;--&lt;865.0,-4.0&gt;&gt;

* u17C9D (U+17C9D): L&lt;&lt;883.0,150.0&gt;--&lt;884.0,-4.0&gt;&gt;

* u17CAE (U+17CAE): L&lt;&lt;904.0,128.0&gt;--&lt;905.0,-2.0&gt;&gt;

* u17CB1 (U+17CB1): L&lt;&lt;838.0,123.0&gt;--&lt;839.0,-4.0&gt;&gt;

* u17CB4 (U+17CB4): L&lt;&lt;864.0,123.0&gt;--&lt;865.0,-4.0&gt;&gt;

* u17CB6 (U+17CB6): L&lt;&lt;891.0,150.0&gt;--&lt;892.0,-4.0&gt;&gt;

* u17CC3 (U+17CC3): L&lt;&lt;885.0,222.0&gt;--&lt;886.0,-3.0&gt;&gt;

* u17CC4 (U+17CC4): L&lt;&lt;911.0,219.0&gt;--&lt;912.0,-1.0&gt;&gt;

* u17CC5 (U+17CC5): L&lt;&lt;918.0,138.0&gt;--&lt;919.0,-3.0&gt;&gt;

* u17CC7 (U+17CC7): L&lt;&lt;911.0,219.0&gt;--&lt;912.0,-1.0&gt;&gt;

* u17CCA (U+17CCA): L&lt;&lt;911.0,219.0&gt;--&lt;912.0,-1.0&gt;&gt;

* u17CDB (U+17CDB): L&lt;&lt;859.0,219.0&gt;--&lt;860.0,-1.0&gt;&gt;

* u17CDD (U+17CDD): L&lt;&lt;860.0,157.0&gt;--&lt;861.0,-4.0&gt;&gt;

* u17CE0 (U+17CE0): L&lt;&lt;901.0,219.0&gt;--&lt;902.0,-1.0&gt;&gt;

* u17CE1 (U+17CE1): L&lt;&lt;895.0,139.0&gt;--&lt;896.0,-4.0&gt;&gt;

* u17CE2 (U+17CE2): L&lt;&lt;911.0,152.0&gt;--&lt;912.0,0.0&gt;&gt;

* u17CE3 (U+17CE3): L&lt;&lt;901.0,152.0&gt;--&lt;902.0,0.0&gt;&gt;

* u17CE9 (U+17CE9): L&lt;&lt;840.0,225.0&gt;--&lt;841.0,5.0&gt;&gt;

* u17CEA (U+17CEA): L&lt;&lt;901.0,219.0&gt;--&lt;902.0,-1.0&gt;&gt;

* u17CF0 (U+17CF0): L&lt;&lt;868.0,124.0&gt;--&lt;869.0,-11.0&gt;&gt;

* u17CF1 (U+17CF1): L&lt;&lt;858.0,219.0&gt;--&lt;859.0,-1.0&gt;&gt;

* u17CF2 (U+17CF2): L&lt;&lt;898.0,138.0&gt;--&lt;899.0,-3.0&gt;&gt;

* u17CF5 (U+17CF5): L&lt;&lt;928.0,226.0&gt;--&lt;929.0,9.0&gt;&gt;

* u17CFA (U+17CFA): L&lt;&lt;881.0,219.0&gt;--&lt;882.0,-1.0&gt;&gt;

* u17CFB (U+17CFB): L&lt;&lt;901.0,219.0&gt;--&lt;902.0,-1.0&gt;&gt;

* u17CFC (U+17CFC): L&lt;&lt;901.0,219.0&gt;--&lt;902.0,-1.0&gt;&gt;

* u17CFE (U+17CFE): L&lt;&lt;885.0,222.0&gt;--&lt;886.0,-3.0&gt;&gt;

* u17D00 (U+17D00): L&lt;&lt;902.0,138.0&gt;--&lt;903.0,-3.0&gt;&gt;

* u17D06 (U+17D06): L&lt;&lt;891.0,135.0&gt;--&lt;892.0,-6.0&gt;&gt;

* u17D07 (U+17D07): L&lt;&lt;874.0,183.0&gt;--&lt;875.0,-3.0&gt;&gt;

* u17D0A (U+17D0A): L&lt;&lt;901.0,219.0&gt;--&lt;902.0,-1.0&gt;&gt;

* u17D0B (U+17D0B): L&lt;&lt;879.0,219.0&gt;--&lt;880.0,-1.0&gt;&gt;

* u17D10 (U+17D10): L&lt;&lt;870.0,219.0&gt;--&lt;871.0,-1.0&gt;&gt;

* u17D11 (U+17D11): L&lt;&lt;907.0,157.0&gt;--&lt;908.0,1.0&gt;&gt;

* u17D21 (U+17D21): L&lt;&lt;912.0,147.0&gt;--&lt;913.0,0.0&gt;&gt;

* u17D23 (U+17D23): L&lt;&lt;870.0,124.0&gt;--&lt;871.0,-11.0&gt;&gt;

* u17D2B (U+17D2B): L&lt;&lt;880.0,135.0&gt;--&lt;881.0,-6.0&gt;&gt;

* u17D2D (U+17D2D): L&lt;&lt;805.0,131.0&gt;--&lt;806.0,-4.0&gt;&gt;

* u17D2E (U+17D2E): L&lt;&lt;825.0,131.0&gt;--&lt;826.0,-4.0&gt;&gt;

* u17D32 (U+17D32): L&lt;&lt;850.0,137.0&gt;--&lt;851.0,-4.0&gt;&gt;

* u17D37 (U+17D37): L&lt;&lt;866.0,135.0&gt;--&lt;867.0,-6.0&gt;&gt;

* u17D3A (U+17D3A): L&lt;&lt;897.0,135.0&gt;--&lt;898.0,-6.0&gt;&gt;

* u17D3C (U+17D3C): L&lt;&lt;902.0,152.0&gt;--&lt;903.0,0.0&gt;&gt;

* u17D3D (U+17D3D): L&lt;&lt;871.0,152.0&gt;--&lt;872.0,0.0&gt;&gt;

* u17D43 (U+17D43): L&lt;&lt;898.0,135.0&gt;--&lt;899.0,-6.0&gt;&gt;

* u17D4F (U+17D4F): L&lt;&lt;892.0,135.0&gt;--&lt;893.0,-6.0&gt;&gt;

* u17D50 (U+17D50): L&lt;&lt;912.0,152.0&gt;--&lt;913.0,0.0&gt;&gt;

* u17D55 (U+17D55): L&lt;&lt;893.0,135.0&gt;--&lt;894.0,-6.0&gt;&gt;

* u17D58 (U+17D58): L&lt;&lt;889.0,135.0&gt;--&lt;890.0,-6.0&gt;&gt;

* u17D5A (U+17D5A): L&lt;&lt;860.0,155.0&gt;--&lt;861.0,-4.0&gt;&gt;

* u17D60 (U+17D60): L&lt;&lt;843.0,123.0&gt;--&lt;844.0,-4.0&gt;&gt;

* u17D64 (U+17D64): L&lt;&lt;893.0,135.0&gt;--&lt;894.0,-6.0&gt;&gt;

* u17D66 (U+17D66): L&lt;&lt;893.0,135.0&gt;--&lt;894.0,-6.0&gt;&gt;

* u17D78 (U+17D78): L&lt;&lt;915.0,135.0&gt;--&lt;916.0,-6.0&gt;&gt;

* u17D7F (U+17D7F): L&lt;&lt;876.0,222.0&gt;--&lt;877.0,-3.0&gt;&gt;

* u17D8A (U+17D8A): L&lt;&lt;868.0,124.0&gt;--&lt;869.0,-11.0&gt;&gt;

* u17D8D (U+17D8D): L&lt;&lt;906.0,222.0&gt;--&lt;907.0,-3.0&gt;&gt;

* u17D95 (U+17D95): L&lt;&lt;873.0,124.0&gt;--&lt;874.0,-11.0&gt;&gt;

* u17DAF (U+17DAF): L&lt;&lt;905.0,387.0&gt;--&lt;906.0,258.0&gt;&gt;

* u17DB0 (U+17DB0): L&lt;&lt;872.0,405.0&gt;--&lt;873.0,278.0&gt;&gt;

* u17DB7 (U+17DB7): L&lt;&lt;920.0,128.0&gt;--&lt;921.0,-1.0&gt;&gt;

* u17DB9 (U+17DB9): L&lt;&lt;894.0,136.0&gt;--&lt;895.0,-1.0&gt;&gt;

* u17DBA (U+17DBA): L&lt;&lt;882.0,128.0&gt;--&lt;883.0,1.0&gt;&gt;

* u17DBB (U+17DBB): L&lt;&lt;882.0,128.0&gt;--&lt;883.0,1.0&gt;&gt;

* u17DC1 (U+17DC1): L&lt;&lt;891.0,218.0&gt;--&lt;892.0,-2.0&gt;&gt;

* u17DC2 (U+17DC2): L&lt;&lt;876.0,119.0&gt;--&lt;877.0,-4.0&gt;&gt;

* u17DC9 (U+17DC9): L&lt;&lt;897.0,156.0&gt;--&lt;898.0,-7.0&gt;&gt;

* u17DCE (U+17DCE): L&lt;&lt;853.0,156.0&gt;--&lt;854.0,-7.0&gt;&gt;

* u17DD0 (U+17DD0): L&lt;&lt;900.0,159.0&gt;--&lt;901.0,-4.0&gt;&gt;

* u17DD1 (U+17DD1): L&lt;&lt;905.0,156.0&gt;--&lt;906.0,-7.0&gt;&gt;

* u17DD6 (U+17DD6): L&lt;&lt;909.0,121.0&gt;--&lt;910.0,-8.0&gt;&gt;

* u17DDC (U+17DDC): L&lt;&lt;890.0,160.0&gt;--&lt;891.0,-4.0&gt;&gt;

* u17DDF (U+17DDF): L&lt;&lt;907.0,156.0&gt;--&lt;908.0,-7.0&gt;&gt;

* u17DE0 (U+17DE0): L&lt;&lt;909.0,147.0&gt;--&lt;910.0,1.0&gt;&gt;

* u17DE1 (U+17DE1): L&lt;&lt;909.0,147.0&gt;--&lt;910.0,1.0&gt;&gt;

* u17DE2 (U+17DE2): L&lt;&lt;913.0,147.0&gt;--&lt;914.0,1.0&gt;&gt;

* u17DE3 (U+17DE3): L&lt;&lt;909.0,147.0&gt;--&lt;910.0,1.0&gt;&gt;

* u17DE4 (U+17DE4): L&lt;&lt;886.0,197.0&gt;--&lt;887.0,-3.0&gt;&gt;

* u17DE6 (U+17DE6): L&lt;&lt;907.0,142.0&gt;--&lt;908.0,-1.0&gt;&gt;

* u17DED (U+17DED): L&lt;&lt;886.0,197.0&gt;--&lt;887.0,-3.0&gt;&gt;

* u17DEE (U+17DEE): L&lt;&lt;886.0,197.0&gt;--&lt;887.0,-3.0&gt;&gt;

* u17DF6 (U+17DF6): L&lt;&lt;908.0,142.0&gt;--&lt;909.0,-1.0&gt;&gt;

* u17DF7 (U+17DF7): L&lt;&lt;885.0,125.0&gt;--&lt;886.0,-2.0&gt;&gt;

* u17E07 (U+17E07): L&lt;&lt;936.0,125.0&gt;--&lt;937.0,-2.0&gt;&gt;

* u17E0A (U+17E0A): L&lt;&lt;910.0,197.0&gt;--&lt;911.0,-3.0&gt;&gt;

* u17E0C (U+17E0C): L&lt;&lt;906.0,197.0&gt;--&lt;907.0,-3.0&gt;&gt;

* u17E0E (U+17E0E): L&lt;&lt;901.0,125.0&gt;--&lt;902.0,-2.0&gt;&gt;

* u17E14 (U+17E14): L&lt;&lt;908.0,132.0&gt;--&lt;909.0,-3.0&gt;&gt;

* u17E15 (U+17E15): L&lt;&lt;897.0,222.0&gt;--&lt;898.0,5.0&gt;&gt;

* u17E1B (U+17E1B): L&lt;&lt;904.0,197.0&gt;--&lt;905.0,-3.0&gt;&gt;

* u17E1F (U+17E1F): L&lt;&lt;907.0,222.0&gt;--&lt;908.0,5.0&gt;&gt;

* u17E20 (U+17E20): L&lt;&lt;907.0,222.0&gt;--&lt;908.0,5.0&gt;&gt;

* u17E22 (U+17E22): L&lt;&lt;871.0,197.0&gt;--&lt;872.0,-3.0&gt;&gt;

* u17E23 (U+17E23): L&lt;&lt;863.0,197.0&gt;--&lt;864.0,-3.0&gt;&gt;

* u17E2B (U+17E2B): L&lt;&lt;902.0,166.0&gt;--&lt;903.0,1.0&gt;&gt;

* u17E2C (U+17E2C): L&lt;&lt;840.0,225.0&gt;--&lt;841.0,5.0&gt;&gt;

* u17E31 (U+17E31): L&lt;&lt;903.0,139.0&gt;--&lt;904.0,-4.0&gt;&gt;

* u17E33 (U+17E33): L&lt;&lt;894.0,124.0&gt;--&lt;895.0,-11.0&gt;&gt;

* u17E34 (U+17E34): L&lt;&lt;895.0,135.0&gt;--&lt;896.0,-6.0&gt;&gt;

* u17E3A (U+17E3A): L&lt;&lt;900.0,225.0&gt;--&lt;901.0,5.0&gt;&gt;

* u17E3D (U+17E3D): L&lt;&lt;884.0,128.0&gt;--&lt;885.0,1.0&gt;&gt;

* u17E42 (U+17E42): L&lt;&lt;904.0,197.0&gt;--&lt;905.0,-3.0&gt;&gt;

* u17E45 (U+17E45): L&lt;&lt;893.0,126.0&gt;--&lt;894.0,-4.0&gt;&gt;

* u17E47 (U+17E47): L&lt;&lt;905.0,222.0&gt;--&lt;906.0,-3.0&gt;&gt;

* u17E49 (U+17E49): L&lt;&lt;902.0,197.0&gt;--&lt;903.0,-3.0&gt;&gt;

* u17E4B (U+17E4B): L&lt;&lt;894.0,124.0&gt;--&lt;895.0,-11.0&gt;&gt;

* u17E4C (U+17E4C): L&lt;&lt;894.0,124.0&gt;--&lt;895.0,-11.0&gt;&gt;

* u17E53 (U+17E53): L&lt;&lt;913.0,152.0&gt;--&lt;914.0,0.0&gt;&gt;

* u17E54 (U+17E54): L&lt;&lt;908.0,218.0&gt;--&lt;909.0,-2.0&gt;&gt;

* u17E58 (U+17E58): L&lt;&lt;912.0,157.0&gt;--&lt;913.0,-4.0&gt;&gt;

* u17E59 (U+17E59): L&lt;&lt;911.0,218.0&gt;--&lt;912.0,-2.0&gt;&gt;

* u17E5B (U+17E5B): L&lt;&lt;921.0,152.0&gt;--&lt;922.0,0.0&gt;&gt;

* u17E5F (U+17E5F): L&lt;&lt;896.0,128.0&gt;--&lt;897.0,1.0&gt;&gt;

* u17E60 (U+17E60): L&lt;&lt;904.0,219.0&gt;--&lt;905.0,-1.0&gt;&gt;

* u17E65 (U+17E65): L&lt;&lt;921.0,152.0&gt;--&lt;922.0,0.0&gt;&gt;

* u17E6C (U+17E6C): L&lt;&lt;922.0,152.0&gt;--&lt;923.0,0.0&gt;&gt;

* u17E6D (U+17E6D): L&lt;&lt;871.0,138.0&gt;--&lt;872.0,-3.0&gt;&gt;

* u17E6E (U+17E6E): L&lt;&lt;886.0,197.0&gt;--&lt;887.0,-3.0&gt;&gt;

* u17E73 (U+17E73): L&lt;&lt;908.0,218.0&gt;--&lt;909.0,-2.0&gt;&gt;

* u17E76 (U+17E76): L&lt;&lt;843.0,181.0&gt;--&lt;844.0,-3.0&gt;&gt;

* u17E78 (U+17E78): L&lt;&lt;906.0,218.0&gt;--&lt;907.0,-2.0&gt;&gt;

* u17E7C (U+17E7C): L&lt;&lt;910.0,218.0&gt;--&lt;911.0,-2.0&gt;&gt;

* u17E80 (U+17E80): L&lt;&lt;906.0,218.0&gt;--&lt;907.0,-2.0&gt;&gt;

* u17E81 (U+17E81): L&lt;&lt;897.0,197.0&gt;--&lt;898.0,-3.0&gt;&gt;

* u17E84 (U+17E84): L&lt;&lt;905.0,175.0&gt;--&lt;906.0,-3.0&gt;&gt;

* u17E87 (U+17E87): L&lt;&lt;876.0,222.0&gt;--&lt;877.0,-3.0&gt;&gt;

* u17E89 (U+17E89): L&lt;&lt;903.0,152.0&gt;--&lt;904.0,0.0&gt;&gt;

* u17E8B (U+17E8B): L&lt;&lt;903.0,152.0&gt;--&lt;904.0,0.0&gt;&gt;

* u17E8C (U+17E8C): L&lt;&lt;910.0,218.0&gt;--&lt;911.0,-2.0&gt;&gt;

* u17E98 (U+17E98): L&lt;&lt;862.0,197.0&gt;--&lt;863.0,-3.0&gt;&gt;

* u17E9E (U+17E9E): L&lt;&lt;901.0,219.0&gt;--&lt;902.0,-1.0&gt;&gt;

* u17EA2 (U+17EA2): L&lt;&lt;907.0,142.0&gt;--&lt;908.0,-1.0&gt;&gt;

* u17EA9 (U+17EA9): L&lt;&lt;887.0,218.0&gt;--&lt;888.0,-2.0&gt;&gt;

* u17EAA (U+17EAA): L&lt;&lt;903.0,152.0&gt;--&lt;904.0,0.0&gt;&gt;

* u17EAD (U+17EAD): L&lt;&lt;910.0,139.0&gt;--&lt;911.0,-4.0&gt;&gt;

* u17EB4 (U+17EB4): L&lt;&lt;840.0,219.0&gt;--&lt;841.0,-1.0&gt;&gt;

* u17EB8 (U+17EB8): L&lt;&lt;922.0,152.0&gt;--&lt;923.0,0.0&gt;&gt;

* u17EBD (U+17EBD): L&lt;&lt;902.0,197.0&gt;--&lt;903.0,-3.0&gt;&gt;

* u17EBE (U+17EBE): L&lt;&lt;891.0,219.0&gt;--&lt;892.0,-1.0&gt;&gt;

* u17EC1 (U+17EC1): L&lt;&lt;915.0,197.0&gt;--&lt;916.0,-3.0&gt;&gt;

* u17EC9 (U+17EC9): L&lt;&lt;874.0,218.0&gt;--&lt;875.0,-2.0&gt;&gt;

* u17ECC (U+17ECC): L&lt;&lt;898.0,166.0&gt;--&lt;899.0,1.0&gt;&gt;

* u17ECE (U+17ECE): L&lt;&lt;885.0,222.0&gt;--&lt;886.0,-3.0&gt;&gt;

* u17ED1 (U+17ED1): L&lt;&lt;907.0,197.0&gt;--&lt;908.0,-3.0&gt;&gt;

* u17ED2 (U+17ED2): L&lt;&lt;905.0,175.0&gt;--&lt;906.0,-3.0&gt;&gt;

* u17EDB (U+17EDB): L&lt;&lt;907.0,197.0&gt;--&lt;908.0,-3.0&gt;&gt;

* u17EDE (U+17EDE): L&lt;&lt;890.0,197.0&gt;--&lt;891.0,-3.0&gt;&gt;

* u17EE0 (U+17EE0): L&lt;&lt;907.0,125.0&gt;--&lt;908.0,-2.0&gt;&gt;

* u17EE2 (U+17EE2): L&lt;&lt;901.0,218.0&gt;--&lt;902.0,-2.0&gt;&gt;

* u17EE3 (U+17EE3): L&lt;&lt;906.0,199.0&gt;--&lt;907.0,-1.0&gt;&gt;

* u17EE6 (U+17EE6): L&lt;&lt;890.0,218.0&gt;--&lt;891.0,-2.0&gt;&gt;

* u17EE7 (U+17EE7): L&lt;&lt;890.0,197.0&gt;--&lt;891.0,-3.0&gt;&gt;

* u17EE8 (U+17EE8): L&lt;&lt;898.0,165.0&gt;--&lt;899.0,-3.0&gt;&gt;

* u17EEB (U+17EEB): L&lt;&lt;907.0,197.0&gt;--&lt;908.0,-3.0&gt;&gt;

* u17EED (U+17EED): L&lt;&lt;912.0,165.0&gt;--&lt;913.0,-3.0&gt;&gt;

* u17EF1 (U+17EF1): L&lt;&lt;906.0,165.0&gt;--&lt;907.0,-3.0&gt;&gt;

* u17EF6 (U+17EF6): L&lt;&lt;899.0,197.0&gt;--&lt;900.0,-3.0&gt;&gt;

* u17F00 (U+17F00): L&lt;&lt;891.0,135.0&gt;--&lt;892.0,-6.0&gt;&gt;

* u17F06 (U+17F06): L&lt;&lt;874.0,219.0&gt;--&lt;875.0,-1.0&gt;&gt;

* u17F0A (U+17F0A): L&lt;&lt;897.0,222.0&gt;--&lt;898.0,-3.0&gt;&gt;

* u17F11 (U+17F11): L&lt;&lt;906.0,165.0&gt;--&lt;907.0,-3.0&gt;&gt;

* u17F12 (U+17F12): L&lt;&lt;906.0,165.0&gt;--&lt;907.0,-3.0&gt;&gt;

* u17F18 (U+17F18): L&lt;&lt;923.0,166.0&gt;--&lt;924.0,1.0&gt;&gt;

* u17F19 (U+17F19): L&lt;&lt;903.0,197.0&gt;--&lt;904.0,-3.0&gt;&gt;

* u17F1D (U+17F1D): L&lt;&lt;903.0,197.0&gt;--&lt;904.0,-3.0&gt;&gt;

* u17F23 (U+17F23): L&lt;&lt;897.0,175.0&gt;--&lt;898.0,-3.0&gt;&gt;

* u17F24 (U+17F24): L&lt;&lt;897.0,220.0&gt;--&lt;898.0,-5.0&gt;&gt;

* u17F28 (U+17F28): L&lt;&lt;897.0,220.0&gt;--&lt;898.0,-5.0&gt;&gt;

* u17F2B (U+17F2B): L&lt;&lt;905.0,165.0&gt;--&lt;906.0,-3.0&gt;&gt;

* u17F2E (U+17F2E): L&lt;&lt;907.0,197.0&gt;--&lt;908.0,-3.0&gt;&gt;

* u17F31 (U+17F31): L&lt;&lt;880.0,197.0&gt;--&lt;881.0,-3.0&gt;&gt;

* u17F33 (U+17F33): L&lt;&lt;869.0,219.0&gt;--&lt;870.0,-1.0&gt;&gt;

* u17F37 (U+17F37): L&lt;&lt;925.0,180.0&gt;--&lt;926.0,2.0&gt;&gt;

* u17F38 (U+17F38): L&lt;&lt;908.0,138.0&gt;--&lt;909.0,-3.0&gt;&gt;

* u17F3C (U+17F3C): L&lt;&lt;896.0,128.0&gt;--&lt;897.0,1.0&gt;&gt;

* u17F4C (U+17F4C): L&lt;&lt;930.0,157.0&gt;--&lt;931.0,1.0&gt;&gt;

* u17F4D (U+17F4D): L&lt;&lt;915.0,197.0&gt;--&lt;916.0,-3.0&gt;&gt;

* u17F4E (U+17F4E): L&lt;&lt;915.0,197.0&gt;--&lt;916.0,-3.0&gt;&gt;

* u17F52 (U+17F52): L&lt;&lt;880.0,197.0&gt;--&lt;881.0,-3.0&gt;&gt;

* u17F53 (U+17F53): L&lt;&lt;880.0,197.0&gt;--&lt;881.0,-3.0&gt;&gt;

* u17F55 (U+17F55): L&lt;&lt;900.0,178.0&gt;--&lt;901.0,-3.0&gt;&gt;

* u17F5A (U+17F5A): L&lt;&lt;908.0,178.0&gt;--&lt;909.0,-3.0&gt;&gt;

* u17F5B (U+17F5B): L&lt;&lt;891.0,135.0&gt;--&lt;892.0,-6.0&gt;&gt;

* u17F62 (U+17F62): L&lt;&lt;919.0,135.0&gt;--&lt;920.0,-6.0&gt;&gt;

* u17F64 (U+17F64): L&lt;&lt;926.0,139.0&gt;--&lt;927.0,-2.0&gt;&gt;

* u17F65 (U+17F65): L&lt;&lt;903.0,197.0&gt;--&lt;904.0,-3.0&gt;&gt;

* u17F67 (U+17F67): L&lt;&lt;907.0,197.0&gt;--&lt;908.0,-3.0&gt;&gt;

* u17F6A (U+17F6A): L&lt;&lt;917.0,220.0&gt;--&lt;918.0,-5.0&gt;&gt;

* u17F6B (U+17F6B): L&lt;&lt;913.0,135.0&gt;--&lt;914.0,-6.0&gt;&gt;

* u17F6C (U+17F6C): L&lt;&lt;870.0,124.0&gt;--&lt;871.0,-11.0&gt;&gt;

* u17F6D (U+17F6D): L&lt;&lt;881.0,165.0&gt;--&lt;882.0,-3.0&gt;&gt;

* u17F70 (U+17F70): L&lt;&lt;886.0,197.0&gt;--&lt;887.0,-3.0&gt;&gt;

* u17F72 (U+17F72): L&lt;&lt;904.0,197.0&gt;--&lt;905.0,-3.0&gt;&gt;

* u17F75 (U+17F75): L&lt;&lt;916.0,165.0&gt;--&lt;917.0,-3.0&gt;&gt;

* u17F77 (U+17F77): L&lt;&lt;946.0,152.0&gt;--&lt;947.0,0.0&gt;&gt;

* u17F7A (U+17F7A): L&lt;&lt;927.0,135.0&gt;--&lt;928.0,-6.0&gt;&gt;

* u17F7C (U+17F7C): L&lt;&lt;903.0,165.0&gt;--&lt;904.0,-3.0&gt;&gt;

* u17F80 (U+17F80): L&lt;&lt;875.0,152.0&gt;--&lt;876.0,0.0&gt;&gt;

* u17F8F (U+17F8F): L&lt;&lt;886.0,222.0&gt;--&lt;887.0,-3.0&gt;&gt;

* u17F92 (U+17F92): L&lt;&lt;905.0,148.0&gt;--&lt;906.0,-4.0&gt;&gt;

* u17F93 (U+17F93): L&lt;&lt;910.0,139.0&gt;--&lt;911.0,-4.0&gt;&gt;

* u17F9B (U+17F9B): L&lt;&lt;860.0,124.0&gt;--&lt;861.0,-11.0&gt;&gt;

* u17F9D (U+17F9D): L&lt;&lt;911.0,152.0&gt;--&lt;912.0,0.0&gt;&gt;

* u17FA4 (U+17FA4): L&lt;&lt;902.0,166.0&gt;--&lt;903.0,1.0&gt;&gt;

* u17FA6 (U+17FA6): L&lt;&lt;915.0,178.0&gt;--&lt;916.0,-3.0&gt;&gt;

* u17FA9 (U+17FA9): L&lt;&lt;909.0,178.0&gt;--&lt;910.0,-3.0&gt;&gt;

* u17FAB (U+17FAB): L&lt;&lt;882.0,218.0&gt;--&lt;883.0,-2.0&gt;&gt;

* u17FAE (U+17FAE): L&lt;&lt;909.0,152.0&gt;--&lt;910.0,0.0&gt;&gt;

* u17FB0 (U+17FB0): L&lt;&lt;907.0,178.0&gt;--&lt;908.0,-3.0&gt;&gt;

* u17FB1 (U+17FB1): L&lt;&lt;904.0,178.0&gt;--&lt;905.0,-3.0&gt;&gt;

* u17FB3 (U+17FB3): L&lt;&lt;907.0,178.0&gt;--&lt;908.0,-3.0&gt;&gt;

* u17FB5 (U+17FB5): L&lt;&lt;924.0,150.0&gt;--&lt;925.0,1.0&gt;&gt;

* u17FB7 (U+17FB7): L&lt;&lt;907.0,222.0&gt;--&lt;908.0,-3.0&gt;&gt;

* u17FB8 (U+17FB8): L&lt;&lt;870.0,124.0&gt;--&lt;871.0,-11.0&gt;&gt;

* u17FB9 (U+17FB9): L&lt;&lt;887.0,218.0&gt;--&lt;888.0,-2.0&gt;&gt;

* u17FBB (U+17FBB): L&lt;&lt;887.0,218.0&gt;--&lt;888.0,-2.0&gt;&gt;

* u17FBD (U+17FBD): L&lt;&lt;909.0,125.0&gt;--&lt;910.0,-2.0&gt;&gt;

* u17FBF (U+17FBF): L&lt;&lt;941.0,152.0&gt;--&lt;942.0,0.0&gt;&gt;

* u17FC0 (U+17FC0): L&lt;&lt;908.0,218.0&gt;--&lt;909.0,-2.0&gt;&gt;

* u17FC1 (U+17FC1): L&lt;&lt;916.0,150.0&gt;--&lt;917.0,1.0&gt;&gt;

* u17FC2 (U+17FC2): L&lt;&lt;896.0,178.0&gt;--&lt;897.0,-3.0&gt;&gt;

* u17FC4 (U+17FC4): L&lt;&lt;908.0,178.0&gt;--&lt;909.0,-3.0&gt;&gt;

* u17FC7 (U+17FC7): L&lt;&lt;908.0,178.0&gt;--&lt;909.0,-3.0&gt;&gt;

* u17FC9 (U+17FC9): L&lt;&lt;508.0,623.0&gt;--&lt;662.0,622.0&gt;&gt;

* u17FC9 (U+17FC9): L&lt;&lt;760.0,593.0&gt;--&lt;517.0,594.0&gt;&gt;

* u17FCB (U+17FCB): L&lt;&lt;908.0,218.0&gt;--&lt;909.0,-2.0&gt;&gt;

* u17FCE (U+17FCE): L&lt;&lt;915.0,127.0&gt;--&lt;916.0,-4.0&gt;&gt;

* u17FD1 (U+17FD1): L&lt;&lt;892.0,197.0&gt;--&lt;893.0,-3.0&gt;&gt;

* u17FD4 (U+17FD4): L&lt;&lt;908.0,218.0&gt;--&lt;909.0,-2.0&gt;&gt;

* u17FD8 (U+17FD8): L&lt;&lt;894.0,152.0&gt;--&lt;895.0,0.0&gt;&gt;

* u17FDA (U+17FDA): L&lt;&lt;859.0,124.0&gt;--&lt;860.0,-11.0&gt;&gt;

* u17FDC (U+17FDC): L&lt;&lt;907.0,222.0&gt;--&lt;908.0,-3.0&gt;&gt;

* u17FE5 (U+17FE5): L&lt;&lt;895.0,124.0&gt;--&lt;896.0,-11.0&gt;&gt;

* u17FE7 (U+17FE7): L&lt;&lt;886.0,161.0&gt;--&lt;887.0,-3.0&gt;&gt;

* u17FEA (U+17FEA): L&lt;&lt;917.0,178.0&gt;--&lt;918.0,-3.0&gt;&gt;

* u17FED (U+17FED): L&lt;&lt;890.0,161.0&gt;--&lt;891.0,-3.0&gt;&gt;

* u17FF3 (U+17FF3): L&lt;&lt;921.0,127.0&gt;--&lt;922.0,-4.0&gt;&gt;

* u17FF4 (U+17FF4): L&lt;&lt;934.0,151.0&gt;--&lt;935.0,0.0&gt;&gt;

* u17FF5 (U+17FF5): L&lt;&lt;915.0,127.0&gt;--&lt;916.0,-4.0&gt;&gt;

* u17FF6 (U+17FF6): L&lt;&lt;915.0,127.0&gt;--&lt;916.0,-4.0&gt;&gt;

* u17FF7 (U+17FF7): L&lt;&lt;924.0,125.0&gt;--&lt;925.0,-2.0&gt;&gt;

* u18003 (U+18003): L&lt;&lt;904.0,179.0&gt;--&lt;905.0,-3.0&gt;&gt;

* u18006 (U+18006): L&lt;&lt;895.0,138.0&gt;--&lt;896.0,-3.0&gt;&gt;

* u1800D (U+1800D): L&lt;&lt;902.0,218.0&gt;--&lt;903.0,-2.0&gt;&gt;

* u1800E (U+1800E): L&lt;&lt;902.0,218.0&gt;--&lt;903.0,-2.0&gt;&gt;

* u18010 (U+18010): L&lt;&lt;902.0,218.0&gt;--&lt;903.0,-2.0&gt;&gt;

* u18012 (U+18012): L&lt;&lt;902.0,218.0&gt;--&lt;903.0,-2.0&gt;&gt;

* u18014 (U+18014): L&lt;&lt;902.0,218.0&gt;--&lt;903.0,-2.0&gt;&gt;

* u18015 (U+18015): L&lt;&lt;902.0,218.0&gt;--&lt;903.0,-2.0&gt;&gt;

* u18016 (U+18016): L&lt;&lt;902.0,218.0&gt;--&lt;903.0,-2.0&gt;&gt;

* u18018 (U+18018): L&lt;&lt;876.0,153.0&gt;--&lt;877.0,-4.0&gt;&gt;

* u18019 (U+18019): L&lt;&lt;923.0,214.0&gt;--&lt;924.0,-2.0&gt;&gt;

* u1801B (U+1801B): L&lt;&lt;914.0,124.0&gt;--&lt;915.0,-5.0&gt;&gt;

* u18020 (U+18020): L&lt;&lt;907.0,142.0&gt;--&lt;908.0,-1.0&gt;&gt;

* u18023 (U+18023): L&lt;&lt;919.0,152.0&gt;--&lt;920.0,0.0&gt;&gt;

* u18024 (U+18024): L&lt;&lt;884.0,197.0&gt;--&lt;885.0,-3.0&gt;&gt;

* u1802D (U+1802D): L&lt;&lt;902.0,218.0&gt;--&lt;903.0,-2.0&gt;&gt;

* u1802E (U+1802E): L&lt;&lt;902.0,218.0&gt;--&lt;903.0,-2.0&gt;&gt;

* u18040 (U+18040): L&lt;&lt;917.0,158.0&gt;--&lt;918.0,-4.0&gt;&gt;

* u18046 (U+18046): L&lt;&lt;905.0,222.0&gt;--&lt;906.0,5.0&gt;&gt;

* u18049 (U+18049): L&lt;&lt;896.0,166.0&gt;--&lt;897.0,1.0&gt;&gt;

* u1804A (U+1804A): L&lt;&lt;904.0,197.0&gt;--&lt;905.0,-3.0&gt;&gt;

* u1804D (U+1804D): L&lt;&lt;921.0,152.0&gt;--&lt;922.0,0.0&gt;&gt;

* u1804F (U+1804F): L&lt;&lt;831.0,133.0&gt;--&lt;832.0,-4.0&gt;&gt;

* u18050 (U+18050): L&lt;&lt;866.0,150.0&gt;--&lt;867.0,-4.0&gt;&gt;

* u18054 (U+18054): L&lt;&lt;857.0,136.0&gt;--&lt;858.0,-4.0&gt;&gt;

* u18055 (U+18055): L&lt;&lt;921.0,152.0&gt;--&lt;922.0,0.0&gt;&gt;

* u18057 (U+18057): L&lt;&lt;870.0,197.0&gt;--&lt;871.0,-3.0&gt;&gt;

* u1805E (U+1805E): L&lt;&lt;902.0,197.0&gt;--&lt;903.0,-3.0&gt;&gt;

* u1805F (U+1805F): L&lt;&lt;909.0,197.0&gt;--&lt;910.0,-3.0&gt;&gt;

* u18061 (U+18061): L&lt;&lt;849.0,124.0&gt;--&lt;850.0,-11.0&gt;&gt;

* u18063 (U+18063): L&lt;&lt;886.0,222.0&gt;--&lt;887.0,-3.0&gt;&gt;

* u18068 (U+18068): L&lt;&lt;898.0,197.0&gt;--&lt;899.0,-3.0&gt;&gt;

* u1806E (U+1806E): L&lt;&lt;901.0,152.0&gt;--&lt;902.0,0.0&gt;&gt;

* u1806F (U+1806F): L&lt;&lt;899.0,197.0&gt;--&lt;900.0,-3.0&gt;&gt;

* u18070 (U+18070): L&lt;&lt;900.0,197.0&gt;--&lt;901.0,-3.0&gt;&gt;

* u1807A (U+1807A): L&lt;&lt;920.0,184.0&gt;--&lt;921.0,-4.0&gt;&gt;

* u1807E (U+1807E): L&lt;&lt;920.0,166.0&gt;--&lt;921.0,1.0&gt;&gt;

* u18085 (U+18085): L&lt;&lt;893.0,222.0&gt;--&lt;894.0,5.0&gt;&gt;

* u18087 (U+18087): L&lt;&lt;889.0,219.0&gt;--&lt;890.0,-1.0&gt;&gt;

* u1808B (U+1808B): L&lt;&lt;869.0,219.0&gt;--&lt;870.0,-1.0&gt;&gt;

* u1808F (U+1808F): L&lt;&lt;883.0,218.0&gt;--&lt;884.0,-2.0&gt;&gt;

* u18090 (U+18090): L&lt;&lt;869.0,219.0&gt;--&lt;870.0,-1.0&gt;&gt;

* u18096 (U+18096): L&lt;&lt;920.0,166.0&gt;--&lt;921.0,1.0&gt;&gt;

* u18097 (U+18097): L&lt;&lt;918.0,166.0&gt;--&lt;919.0,1.0&gt;&gt;

* u1809B (U+1809B): L&lt;&lt;860.0,124.0&gt;--&lt;861.0,-11.0&gt;&gt;

* u1809E (U+1809E): L&lt;&lt;920.0,169.0&gt;--&lt;921.0,4.0&gt;&gt;

* u180A1 (U+180A1): L&lt;&lt;879.0,197.0&gt;--&lt;880.0,-3.0&gt;&gt;

* u180A2 (U+180A2): L&lt;&lt;891.0,160.0&gt;--&lt;892.0,-4.0&gt;&gt;

* u180A3 (U+180A3): L&lt;&lt;898.0,158.0&gt;--&lt;899.0,-4.0&gt;&gt;

* u180A6 (U+180A6): L&lt;&lt;903.0,219.0&gt;--&lt;904.0,-1.0&gt;&gt;

* u180A9 (U+180A9): L&lt;&lt;901.0,139.0&gt;--&lt;902.0,-4.0&gt;&gt;

* u180B1 (U+180B1): L&lt;&lt;916.0,125.0&gt;--&lt;917.0,-2.0&gt;&gt;

* u180B9 (U+180B9): L&lt;&lt;917.0,222.0&gt;--&lt;918.0,5.0&gt;&gt;

* u180BB (U+180BB): L&lt;&lt;891.0,160.0&gt;--&lt;892.0,-4.0&gt;&gt;

* u180BC (U+180BC): L&lt;&lt;901.0,144.0&gt;--&lt;902.0,0.0&gt;&gt;

* u180C0 (U+180C0): L&lt;&lt;887.0,218.0&gt;--&lt;888.0,-2.0&gt;&gt;

* u180C1 (U+180C1): L&lt;&lt;895.0,222.0&gt;--&lt;896.0,-3.0&gt;&gt;

* u180C2 (U+180C2): L&lt;&lt;884.0,197.0&gt;--&lt;885.0,-3.0&gt;&gt;

* u180C7 (U+180C7): L&lt;&lt;919.0,184.0&gt;--&lt;920.0,-4.0&gt;&gt;

* u180CE (U+180CE): L&lt;&lt;846.0,197.0&gt;--&lt;847.0,-3.0&gt;&gt;

* u180D6 (U+180D6): L&lt;&lt;901.0,197.0&gt;--&lt;902.0,-3.0&gt;&gt;

* u180DA (U+180DA): L&lt;&lt;868.0,197.0&gt;--&lt;869.0,-3.0&gt;&gt;

* u180DB (U+180DB): L&lt;&lt;895.0,197.0&gt;--&lt;896.0,-3.0&gt;&gt;

* u180DD (U+180DD): L&lt;&lt;895.0,222.0&gt;--&lt;896.0,5.0&gt;&gt;

* u180E4 (U+180E4): L&lt;&lt;895.0,222.0&gt;--&lt;896.0,5.0&gt;&gt;

* u180E5 (U+180E5): L&lt;&lt;907.0,178.0&gt;--&lt;908.0,-3.0&gt;&gt;

* u180E6 (U+180E6): L&lt;&lt;919.0,169.0&gt;--&lt;920.0,4.0&gt;&gt;

* u180E7 (U+180E7): L&lt;&lt;907.0,178.0&gt;--&lt;908.0,-3.0&gt;&gt;

* u180E8 (U+180E8): L&lt;&lt;905.0,175.0&gt;--&lt;906.0,-3.0&gt;&gt;

* u180EA (U+180EA): L&lt;&lt;468.0,632.0&gt;--&lt;616.0,631.0&gt;&gt;

* u180EA (U+180EA): L&lt;&lt;719.0,602.0&gt;--&lt;477.0,603.0&gt;&gt;

* u180EB (U+180EB): L&lt;&lt;901.0,178.0&gt;--&lt;902.0,-3.0&gt;&gt;

* u180EC (U+180EC): L&lt;&lt;909.0,128.0&gt;--&lt;910.0,1.0&gt;&gt;

* u180ED (U+180ED): L&lt;&lt;873.0,178.0&gt;--&lt;874.0,-3.0&gt;&gt;

* u180F0 (U+180F0): L&lt;&lt;891.0,138.0&gt;--&lt;892.0,-3.0&gt;&gt;

* u180F1 (U+180F1): L&lt;&lt;907.0,166.0&gt;--&lt;908.0,1.0&gt;&gt;

* u180F3 (U+180F3): L&lt;&lt;850.0,222.0&gt;--&lt;851.0,-3.0&gt;&gt;

* u180F4 (U+180F4): L&lt;&lt;878.0,161.0&gt;--&lt;879.0,-2.0&gt;&gt;

* u180F6 (U+180F6): L&lt;&lt;879.0,197.0&gt;--&lt;880.0,-3.0&gt;&gt;

* u180F7 (U+180F7): L&lt;&lt;895.0,197.0&gt;--&lt;896.0,-3.0&gt;&gt;

* u180F9 (U+180F9): L&lt;&lt;919.0,152.0&gt;--&lt;920.0,0.0&gt;&gt;

* u180FA (U+180FA): L&lt;&lt;895.0,222.0&gt;--&lt;896.0,5.0&gt;&gt;

* u18102 (U+18102): L&lt;&lt;903.0,169.0&gt;--&lt;904.0,4.0&gt;&gt;

* u18103 (U+18103): L&lt;&lt;903.0,169.0&gt;--&lt;904.0,4.0&gt;&gt;

* u18106 (U+18106): L&lt;&lt;898.0,197.0&gt;--&lt;899.0,-3.0&gt;&gt;

* u18107 (U+18107): L&lt;&lt;909.0,152.0&gt;--&lt;910.0,0.0&gt;&gt;

* u18108 (U+18108): L&lt;&lt;929.0,150.0&gt;--&lt;930.0,1.0&gt;&gt;

* u18109 (U+18109): L&lt;&lt;894.0,197.0&gt;--&lt;895.0,-3.0&gt;&gt;

* u1810A (U+1810A): L&lt;&lt;879.0,125.0&gt;--&lt;880.0,-2.0&gt;&gt;

* u1810C (U+1810C): L&lt;&lt;909.0,152.0&gt;--&lt;910.0,0.0&gt;&gt;

* u1810E (U+1810E): L&lt;&lt;461.0,612.0&gt;--&lt;649.0,611.0&gt;&gt;

* u1810E (U+1810E): L&lt;&lt;722.0,582.0&gt;--&lt;470.0,583.0&gt;&gt;

* u1810F (U+1810F): L&lt;&lt;898.0,197.0&gt;--&lt;899.0,-3.0&gt;&gt;

* u18110 (U+18110): L&lt;&lt;872.0,197.0&gt;--&lt;873.0,-3.0&gt;&gt;

* u18111 (U+18111): L&lt;&lt;906.0,197.0&gt;--&lt;907.0,-3.0&gt;&gt;

* u18114 (U+18114): L&lt;&lt;313.0,418.0&gt;--&lt;545.0,417.0&gt;&gt;

* u18114 (U+18114): L&lt;&lt;545.0,388.0&gt;--&lt;289.0,389.0&gt;&gt;

* u18119 (U+18119): L&lt;&lt;849.0,124.0&gt;--&lt;850.0,-11.0&gt;&gt;

* u1811C (U+1811C): L&lt;&lt;905.0,148.0&gt;--&lt;906.0,-4.0&gt;&gt;

* u18125 (U+18125): L&lt;&lt;891.0,160.0&gt;--&lt;892.0,-4.0&gt;&gt;

* u18127 (U+18127): L&lt;&lt;872.0,130.0&gt;--&lt;873.0,-5.0&gt;&gt;

* u1812F (U+1812F): L&lt;&lt;869.0,219.0&gt;--&lt;870.0,-1.0&gt;&gt;

* u1813A (U+1813A): L&lt;&lt;857.0,219.0&gt;--&lt;858.0,-1.0&gt;&gt;

* u18141 (U+18141): L&lt;&lt;908.0,166.0&gt;--&lt;909.0,1.0&gt;&gt;

* u18143 (U+18143): L&lt;&lt;910.0,218.0&gt;--&lt;911.0,-2.0&gt;&gt;

* u18144 (U+18144): L&lt;&lt;911.0,164.0&gt;--&lt;912.0,1.0&gt;&gt;

* u18146 (U+18146): L&lt;&lt;840.0,225.0&gt;--&lt;841.0,5.0&gt;&gt;

* u18148 (U+18148): L&lt;&lt;904.0,218.0&gt;--&lt;905.0,-2.0&gt;&gt;

* u18149 (U+18149): L&lt;&lt;895.0,218.0&gt;--&lt;896.0,-2.0&gt;&gt;

* u1814A (U+1814A): L&lt;&lt;903.0,175.0&gt;--&lt;904.0,-3.0&gt;&gt;

* u1814F (U+1814F): L&lt;&lt;874.0,218.0&gt;--&lt;875.0,-2.0&gt;&gt;

* u18152 (U+18152): L&lt;&lt;910.0,218.0&gt;--&lt;911.0,-2.0&gt;&gt;

* u18153 (U+18153): L&lt;&lt;903.0,218.0&gt;--&lt;904.0,-2.0&gt;&gt;

* u18155 (U+18155): L&lt;&lt;885.0,222.0&gt;--&lt;886.0,-3.0&gt;&gt;

* u1815C (U+1815C): L&lt;&lt;897.0,626.0&gt;--&lt;898.0,461.0&gt;&gt;

* u1815D (U+1815D): L&lt;&lt;909.0,152.0&gt;--&lt;910.0,0.0&gt;&gt;

* u1815E (U+1815E): L&lt;&lt;899.0,222.0&gt;--&lt;900.0,-3.0&gt;&gt;

* u18163 (U+18163): L&lt;&lt;889.0,125.0&gt;--&lt;890.0,-2.0&gt;&gt;

* u18165 (U+18165): L&lt;&lt;858.0,124.0&gt;--&lt;859.0,-11.0&gt;&gt;

* u18166 (U+18166): L&lt;&lt;909.0,222.0&gt;--&lt;910.0,-3.0&gt;&gt;

* u18168 (U+18168): L&lt;&lt;921.0,150.0&gt;--&lt;922.0,1.0&gt;&gt;

* u18169 (U+18169): L&lt;&lt;916.0,139.0&gt;--&lt;917.0,-4.0&gt;&gt;

* u1816B (U+1816B): L&lt;&lt;461.0,612.0&gt;--&lt;649.0,611.0&gt;&gt;

* u1816B (U+1816B): L&lt;&lt;722.0,582.0&gt;--&lt;470.0,583.0&gt;&gt;

* u1816C (U+1816C): L&lt;&lt;911.0,218.0&gt;--&lt;912.0,-2.0&gt;&gt;

* u1816E (U+1816E): L&lt;&lt;886.0,218.0&gt;--&lt;887.0,-2.0&gt;&gt;

* u18170 (U+18170): L&lt;&lt;870.0,124.0&gt;--&lt;871.0,-11.0&gt;&gt;

* u1817C (U+1817C): L&lt;&lt;890.0,135.0&gt;--&lt;891.0,-1.0&gt;&gt;

* u18180 (U+18180): L&lt;&lt;878.0,219.0&gt;--&lt;879.0,-1.0&gt;&gt;

* u18182 (U+18182): L&lt;&lt;872.0,139.0&gt;--&lt;873.0,-4.0&gt;&gt;

* u18185 (U+18185): L&lt;&lt;899.0,219.0&gt;--&lt;900.0,-1.0&gt;&gt;

* u18186 (U+18186): L&lt;&lt;824.0,341.0&gt;--&lt;825.0,116.0&gt;&gt;

* u18186 (U+18186): L&lt;&lt;915.0,210.0&gt;--&lt;916.0,-2.0&gt;&gt;

* u18187 (U+18187): L&lt;&lt;915.0,210.0&gt;--&lt;916.0,-2.0&gt;&gt;

* u18188 (U+18188): L&lt;&lt;875.0,197.0&gt;--&lt;876.0,-3.0&gt;&gt;

* u18189 (U+18189): L&lt;&lt;913.0,222.0&gt;--&lt;914.0,-3.0&gt;&gt;

* u18191 (U+18191): L&lt;&lt;904.0,128.0&gt;--&lt;905.0,1.0&gt;&gt;

* u18195 (U+18195): L&lt;&lt;137.0,774.0&gt;--&lt;646.0,775.0&gt;&gt;

* u18195 (U+18195): L&lt;&lt;267.0,554.0&gt;--&lt;452.0,555.0&gt;&gt;

* u18195 (U+18195): L&lt;&lt;493.0,525.0&gt;--&lt;267.0,524.0&gt;&gt;

* u18195 (U+18195): L&lt;&lt;627.0,745.0&gt;--&lt;146.0,744.0&gt;&gt;

* u18195 (U+18195): L&lt;&lt;914.0,526.0&gt;--&lt;622.0,525.0&gt;&gt;

* u18198 (U+18198): L&lt;&lt;898.0,218.0&gt;--&lt;899.0,-2.0&gt;&gt;

* u1819D (U+1819D): L&lt;&lt;877.0,219.0&gt;--&lt;878.0,-1.0&gt;&gt;

* u181A5 (U+181A5): L&lt;&lt;902.0,219.0&gt;--&lt;903.0,-1.0&gt;&gt;

* u181A8 (U+181A8): L&lt;&lt;907.0,166.0&gt;--&lt;908.0,1.0&gt;&gt;

* u181AC (U+181AC): L&lt;&lt;849.0,124.0&gt;--&lt;850.0,-11.0&gt;&gt;

* u181AE (U+181AE): L&lt;&lt;896.0,219.0&gt;--&lt;897.0,-1.0&gt;&gt;

* u181AF (U+181AF): L&lt;&lt;903.0,152.0&gt;--&lt;904.0,0.0&gt;&gt;

* u181B0 (U+181B0): L&lt;&lt;916.0,139.0&gt;--&lt;917.0,-4.0&gt;&gt;

* u181B2 (U+181B2): L&lt;&lt;919.0,152.0&gt;--&lt;920.0,0.0&gt;&gt;

* u181B3 (U+181B3): L&lt;&lt;928.0,226.0&gt;--&lt;929.0,9.0&gt;&gt;

* u181B6 (U+181B6): L&lt;&lt;901.0,169.0&gt;--&lt;902.0,4.0&gt;&gt;

* u181BC (U+181BC): L&lt;&lt;902.0,219.0&gt;--&lt;903.0,-1.0&gt;&gt;

* u181C4 (U+181C4): L&lt;&lt;917.0,135.0&gt;--&lt;918.0,-1.0&gt;&gt;

* u181C8 (U+181C8): L&lt;&lt;865.0,124.0&gt;--&lt;866.0,-11.0&gt;&gt;

* u181C9 (U+181C9): L&lt;&lt;916.0,139.0&gt;--&lt;917.0,-4.0&gt;&gt;

* u181CB (U+181CB): L&lt;&lt;909.0,113.0&gt;--&lt;910.0,-5.0&gt;&gt;

* u181CE (U+181CE): L&lt;&lt;847.0,225.0&gt;--&lt;848.0,5.0&gt;&gt;

* u181D6 (U+181D6): L&lt;&lt;861.0,225.0&gt;--&lt;862.0,5.0&gt;&gt;

* u181DA (U+181DA): L&lt;&lt;906.0,113.0&gt;--&lt;907.0,-5.0&gt;&gt;

* u181DF (U+181DF): L&lt;&lt;891.0,218.0&gt;--&lt;892.0,-2.0&gt;&gt;

* u181E1 (U+181E1): L&lt;&lt;849.0,225.0&gt;--&lt;850.0,5.0&gt;&gt;

* u181E7 (U+181E7): L&lt;&lt;874.0,218.0&gt;--&lt;875.0,-2.0&gt;&gt;

* u181EA (U+181EA): L&lt;&lt;885.0,219.0&gt;--&lt;886.0,-1.0&gt;&gt;

* u181F1 (U+181F1): L&lt;&lt;881.0,218.0&gt;--&lt;882.0,-2.0&gt;&gt;

* u181F7 (U+181F7): L&lt;&lt;909.0,218.0&gt;--&lt;910.0,-2.0&gt;&gt;

* u18200 (U+18200): L&lt;&lt;892.0,197.0&gt;--&lt;893.0,-3.0&gt;&gt;

* u18203 (U+18203): L&lt;&lt;915.0,197.0&gt;--&lt;916.0,-3.0&gt;&gt;

* u18209 (U+18209): L&lt;&lt;909.0,125.0&gt;--&lt;910.0,-4.0&gt;&gt;

* u18215 (U+18215): L&lt;&lt;928.0,226.0&gt;--&lt;929.0,9.0&gt;&gt;

* u18217 (U+18217): L&lt;&lt;897.0,197.0&gt;--&lt;898.0,-3.0&gt;&gt;

* u18219 (U+18219): L&lt;&lt;913.0,138.0&gt;--&lt;914.0,-3.0&gt;&gt;

* u1821B (U+1821B): L&lt;&lt;883.0,219.0&gt;--&lt;884.0,-1.0&gt;&gt;

* u1821D (U+1821D): L&lt;&lt;892.0,197.0&gt;--&lt;893.0,-3.0&gt;&gt;

* u18222 (U+18222): L&lt;&lt;924.0,138.0&gt;--&lt;925.0,-3.0&gt;&gt;

* u1822D (U+1822D): L&lt;&lt;920.0,166.0&gt;--&lt;921.0,1.0&gt;&gt;

* u1822E (U+1822E): L&lt;&lt;849.0,124.0&gt;--&lt;850.0,-11.0&gt;&gt;

* u18230 (U+18230): L&lt;&lt;852.0,225.0&gt;--&lt;853.0,5.0&gt;&gt;

* u1823B (U+1823B): L&lt;&lt;911.0,146.0&gt;--&lt;912.0,0.0&gt;&gt;

* u1823E (U+1823E): L&lt;&lt;908.0,125.0&gt;--&lt;909.0,-2.0&gt;&gt;

* u18242 (U+18242): L&lt;&lt;890.0,197.0&gt;--&lt;891.0,-3.0&gt;&gt;

* u18248 (U+18248): L&lt;&lt;908.0,125.0&gt;--&lt;909.0,-2.0&gt;&gt;

* u1824F (U+1824F): L&lt;&lt;897.0,139.0&gt;--&lt;898.0,-4.0&gt;&gt;

* u1825C (U+1825C): L&lt;&lt;924.0,139.0&gt;--&lt;925.0,-4.0&gt;&gt;

* u1825D (U+1825D): L&lt;&lt;902.0,390.0&gt;--&lt;903.0,173.0&gt;&gt;

* u1825E (U+1825E): L&lt;&lt;879.0,251.0&gt;--&lt;880.0,34.0&gt;&gt;

* u18264 (U+18264): L&lt;&lt;894.0,222.0&gt;--&lt;895.0,-3.0&gt;&gt;

* u18269 (U+18269): L&lt;&lt;871.0,197.0&gt;--&lt;872.0,-3.0&gt;&gt;

* u1826D (U+1826D): L&lt;&lt;848.0,219.0&gt;--&lt;849.0,-1.0&gt;&gt;

* u18270 (U+18270): L&lt;&lt;847.0,219.0&gt;--&lt;848.0,-1.0&gt;&gt;

* u18274 (U+18274): L&lt;&lt;905.0,152.0&gt;--&lt;906.0,0.0&gt;&gt;

* u18278 (U+18278): L&lt;&lt;907.0,166.0&gt;--&lt;908.0,1.0&gt;&gt;

* u1827C (U+1827C): L&lt;&lt;847.0,225.0&gt;--&lt;848.0,5.0&gt;&gt;

* u18280 (U+18280): L&lt;&lt;875.0,197.0&gt;--&lt;876.0,-3.0&gt;&gt;

* u18282 (U+18282): L&lt;&lt;899.0,218.0&gt;--&lt;900.0,-2.0&gt;&gt;

* u18288 (U+18288): L&lt;&lt;903.0,218.0&gt;--&lt;904.0,-2.0&gt;&gt;

* u1828D (U+1828D): L&lt;&lt;910.0,161.0&gt;--&lt;911.0,-4.0&gt;&gt;

* u1828E (U+1828E): L&lt;&lt;910.0,197.0&gt;--&lt;911.0,-3.0&gt;&gt;

* u18291 (U+18291): L&lt;&lt;888.0,148.0&gt;--&lt;889.0,-4.0&gt;&gt;

* u18293 (U+18293): L&lt;&lt;904.0,179.0&gt;--&lt;905.0,-3.0&gt;&gt;

* u18294 (U+18294): L&lt;&lt;840.0,225.0&gt;--&lt;841.0,5.0&gt;&gt;

* u18297 (U+18297): L&lt;&lt;910.0,197.0&gt;--&lt;911.0,-3.0&gt;&gt;

* u1829D (U+1829D): L&lt;&lt;899.0,218.0&gt;--&lt;900.0,-2.0&gt;&gt;

* u1829E (U+1829E): L&lt;&lt;877.0,158.0&gt;--&lt;878.0,-4.0&gt;&gt;

* u1829F (U+1829F): L&lt;&lt;920.0,166.0&gt;--&lt;921.0,1.0&gt;&gt;

* u182A3 (U+182A3): L&lt;&lt;906.0,138.0&gt;--&lt;907.0,-3.0&gt;&gt;

* u182A5 (U+182A5): L&lt;&lt;907.0,166.0&gt;--&lt;908.0,1.0&gt;&gt;

* u182B1 (U+182B1): L&lt;&lt;899.0,218.0&gt;--&lt;900.0,-2.0&gt;&gt;

* u182B5 (U+182B5): L&lt;&lt;936.0,166.0&gt;--&lt;937.0,1.0&gt;&gt;

* u182B9 (U+182B9): L&lt;&lt;858.0,225.0&gt;--&lt;859.0,5.0&gt;&gt;

* u182BE (U+182BE): L&lt;&lt;887.0,125.0&gt;--&lt;888.0,-2.0&gt;&gt;

* u182C0 (U+182C0): L&lt;&lt;856.0,219.0&gt;--&lt;857.0,-1.0&gt;&gt;

* u182C2 (U+182C2): L&lt;&lt;858.0,167.0&gt;--&lt;859.0,-2.0&gt;&gt;

* u182C3 (U+182C3): L&lt;&lt;907.0,178.0&gt;--&lt;908.0,-3.0&gt;&gt;

* u182CB (U+182CB): L&lt;&lt;891.0,135.0&gt;--&lt;892.0,-6.0&gt;&gt;

* u182CC (U+182CC): L&lt;&lt;905.0,178.0&gt;--&lt;906.0,-3.0&gt;&gt;

* u182CD (U+182CD): L&lt;&lt;907.0,218.0&gt;--&lt;908.0,-2.0&gt;&gt;

* u182D0 (U+182D0): L&lt;&lt;887.0,218.0&gt;--&lt;888.0,-2.0&gt;&gt;

* u182D4 (U+182D4): L&lt;&lt;900.0,218.0&gt;--&lt;901.0,-2.0&gt;&gt;

* u182D6 (U+182D6): L&lt;&lt;856.0,219.0&gt;--&lt;857.0,-1.0&gt;&gt;

* u182DA (U+182DA): L&lt;&lt;909.0,152.0&gt;--&lt;910.0,0.0&gt;&gt;

* u182DC (U+182DC): L&lt;&lt;868.0,124.0&gt;--&lt;869.0,-11.0&gt;&gt;

* u182DE (U+182DE): L&lt;&lt;867.0,222.0&gt;--&lt;868.0,-3.0&gt;&gt;

* u182DF (U+182DF): L&lt;&lt;917.0,138.0&gt;--&lt;918.0,-3.0&gt;&gt;

* u182E1 (U+182E1): L&lt;&lt;913.0,169.0&gt;--&lt;914.0,4.0&gt;&gt;

* u182E2 (U+182E2): L&lt;&lt;903.0,218.0&gt;--&lt;904.0,-2.0&gt;&gt;

* u182E4 (U+182E4): L&lt;&lt;918.0,131.0&gt;--&lt;919.0,-5.0&gt;&gt;

* u182E9 (U+182E9): L&lt;&lt;906.0,165.0&gt;--&lt;907.0,-3.0&gt;&gt;

* u182EA (U+182EA): L&lt;&lt;893.0,142.0&gt;--&lt;894.0,-1.0&gt;&gt;

* u182EB (U+182EB): L&lt;&lt;896.0,128.0&gt;--&lt;897.0,1.0&gt;&gt;

* u182ED (U+182ED): L&lt;&lt;910.0,180.0&gt;--&lt;911.0,-5.0&gt;&gt;

* u182F0 (U+182F0): L&lt;&lt;909.0,218.0&gt;--&lt;910.0,-2.0&gt;&gt;

* u182F3 (U+182F3): L&lt;&lt;904.0,135.0&gt;--&lt;905.0,-6.0&gt;&gt;

* u182F5 (U+182F5): L&lt;&lt;899.0,218.0&gt;--&lt;900.0,-2.0&gt;&gt;

* u182F6 (U+182F6): L&lt;&lt;912.0,139.0&gt;--&lt;913.0,-5.0&gt;&gt;

* u182FA (U+182FA): L&lt;&lt;147.0,-80.0&gt;--&lt;146.0,400.0&gt;&gt;

* u182FA (U+182FA): L&lt;&lt;209.0,444.0&gt;--&lt;210.0,-59.0&gt;&gt;

* u182FB (U+182FB): L&lt;&lt;138.0,-80.0&gt;--&lt;137.0,395.0&gt;&gt;

* u182FB (U+182FB): L&lt;&lt;200.0,437.0&gt;--&lt;201.0,-59.0&gt;&gt;

* u182FC (U+182FC): L&lt;&lt;147.0,-80.0&gt;--&lt;146.0,400.0&gt;&gt;

* u182FC (U+182FC): L&lt;&lt;209.0,444.0&gt;--&lt;210.0,-59.0&gt;&gt;

* u182FD (U+182FD): L&lt;&lt;147.0,-80.0&gt;--&lt;146.0,400.0&gt;&gt;

* u182FD (U+182FD): L&lt;&lt;209.0,444.0&gt;--&lt;210.0,-59.0&gt;&gt;

* u182FD (U+182FD): L&lt;&lt;894.0,222.0&gt;--&lt;895.0,-3.0&gt;&gt;

* u182FE (U+182FE): L&lt;&lt;147.0,-80.0&gt;--&lt;146.0,400.0&gt;&gt;

* u182FE (U+182FE): L&lt;&lt;209.0,444.0&gt;--&lt;210.0,-59.0&gt;&gt;

* u182FF (U+182FF): L&lt;&lt;125.0,-80.0&gt;--&lt;124.0,396.0&gt;&gt;

* u182FF (U+182FF): L&lt;&lt;187.0,449.0&gt;--&lt;188.0,-59.0&gt;&gt;

* u18300 (U+18300): L&lt;&lt;125.0,-80.0&gt;--&lt;124.0,406.0&gt;&gt;

* u18300 (U+18300): L&lt;&lt;187.0,449.0&gt;--&lt;188.0,-59.0&gt;&gt;

* u18300 (U+18300): L&lt;&lt;914.0,152.0&gt;--&lt;915.0,0.0&gt;&gt;

* u18301 (U+18301): L&lt;&lt;125.0,-80.0&gt;--&lt;124.0,396.0&gt;&gt;

* u18301 (U+18301): L&lt;&lt;187.0,449.0&gt;--&lt;188.0,-59.0&gt;&gt;

* u18301 (U+18301): L&lt;&lt;916.0,218.0&gt;--&lt;917.0,-2.0&gt;&gt;

* u18303 (U+18303): L&lt;&lt;856.0,219.0&gt;--&lt;857.0,-1.0&gt;&gt;

* u18308 (U+18308): L&lt;&lt;930.0,138.0&gt;--&lt;931.0,-3.0&gt;&gt;

* u1830E (U+1830E): L&lt;&lt;906.0,218.0&gt;--&lt;907.0,-2.0&gt;&gt;

* u18315 (U+18315): L&lt;&lt;893.0,218.0&gt;--&lt;894.0,-2.0&gt;&gt;

* u18316 (U+18316): L&lt;&lt;893.0,218.0&gt;--&lt;894.0,-2.0&gt;&gt;

* u18317 (U+18317): L&lt;&lt;907.0,139.0&gt;--&lt;908.0,-4.0&gt;&gt;

* u1831F (U+1831F): L&lt;&lt;903.0,222.0&gt;--&lt;904.0,5.0&gt;&gt;

* u18320 (U+18320): L&lt;&lt;828.0,338.0&gt;--&lt;829.0,118.0&gt;&gt;

* u18320 (U+18320): L&lt;&lt;900.0,222.0&gt;--&lt;901.0,5.0&gt;&gt;

* u18321 (U+18321): L&lt;&lt;903.0,222.0&gt;--&lt;904.0,5.0&gt;&gt;

* u18322 (U+18322): L&lt;&lt;881.0,160.0&gt;--&lt;882.0,6.0&gt;&gt;

* u18329 (U+18329): L&lt;&lt;866.0,219.0&gt;--&lt;867.0,-1.0&gt;&gt;

* u1832C (U+1832C): L&lt;&lt;854.0,219.0&gt;--&lt;855.0,-1.0&gt;&gt;

* u1832E (U+1832E): L&lt;&lt;926.0,170.0&gt;--&lt;927.0,1.0&gt;&gt;

* u18336 (U+18336): L&lt;&lt;905.0,142.0&gt;--&lt;906.0,-1.0&gt;&gt;

* u1833E (U+1833E): L&lt;&lt;904.0,218.0&gt;--&lt;905.0,-2.0&gt;&gt;

* u18341 (U+18341): L&lt;&lt;885.0,112.0&gt;--&lt;886.0,-5.0&gt;&gt;

* u18342 (U+18342): L&lt;&lt;899.0,128.0&gt;--&lt;900.0,1.0&gt;&gt;

* u18344 (U+18344): L&lt;&lt;890.0,160.0&gt;--&lt;891.0,-4.0&gt;&gt;

* u18348 (U+18348): L&lt;&lt;889.0,124.0&gt;--&lt;890.0,-11.0&gt;&gt;

* u1834A (U+1834A): L&lt;&lt;917.0,139.0&gt;--&lt;918.0,-4.0&gt;&gt;

* u1834C (U+1834C): L&lt;&lt;920.0,164.0&gt;--&lt;921.0,-2.0&gt;&gt;

* u1834D (U+1834D): L&lt;&lt;925.0,164.0&gt;--&lt;926.0,-2.0&gt;&gt;

* u1834F (U+1834F): L&lt;&lt;873.0,218.0&gt;--&lt;874.0,-2.0&gt;&gt;

* u18351 (U+18351): L&lt;&lt;881.0,218.0&gt;--&lt;882.0,-2.0&gt;&gt;

* u18352 (U+18352): L&lt;&lt;866.0,216.0&gt;--&lt;867.0,-9.0&gt;&gt;

* u1835E (U+1835E): L&lt;&lt;889.0,218.0&gt;--&lt;890.0,-2.0&gt;&gt;

* u18366 (U+18366): L&lt;&lt;907.0,125.0&gt;--&lt;908.0,-2.0&gt;&gt;

* u1836A (U+1836A): L&lt;&lt;907.0,125.0&gt;--&lt;908.0,-2.0&gt;&gt;

* u1836F (U+1836F): L&lt;&lt;914.0,172.0&gt;--&lt;915.0,-3.0&gt;&gt;

* u18374 (U+18374): L&lt;&lt;866.0,216.0&gt;--&lt;867.0,-9.0&gt;&gt;

* u18376 (U+18376): L&lt;&lt;906.0,138.0&gt;--&lt;907.0,-3.0&gt;&gt;

* u18377 (U+18377): L&lt;&lt;892.0,197.0&gt;--&lt;893.0,-3.0&gt;&gt;

* u1837C (U+1837C): L&lt;&lt;905.0,163.0&gt;--&lt;906.0,-3.0&gt;&gt;

* u1837F (U+1837F): L&lt;&lt;899.0,197.0&gt;--&lt;900.0,-3.0&gt;&gt;

* u18382 (U+18382): L&lt;&lt;911.0,222.0&gt;--&lt;912.0,-3.0&gt;&gt;

* u18384 (U+18384): L&lt;&lt;914.0,165.0&gt;--&lt;915.0,-3.0&gt;&gt;

* u18386 (U+18386): L&lt;&lt;858.0,152.0&gt;--&lt;859.0,0.0&gt;&gt;

* u1838B (U+1838B): L&lt;&lt;842.0,127.0&gt;--&lt;843.0,-2.0&gt;&gt;

* u1838F (U+1838F): L&lt;&lt;860.0,119.0&gt;--&lt;861.0,-4.0&gt;&gt;

* u18399 (U+18399): L&lt;&lt;914.0,218.0&gt;--&lt;915.0,-2.0&gt;&gt;

* u1839A (U+1839A): L&lt;&lt;899.0,181.0&gt;--&lt;900.0,-3.0&gt;&gt;

* u1839C (U+1839C): L&lt;&lt;889.0,218.0&gt;--&lt;890.0,-2.0&gt;&gt;

* u183A6 (U+183A6): L&lt;&lt;856.0,219.0&gt;--&lt;857.0,-1.0&gt;&gt;

* u183A7 (U+183A7): L&lt;&lt;856.0,219.0&gt;--&lt;857.0,-1.0&gt;&gt;

* u183A8 (U+183A8): L&lt;&lt;906.0,135.0&gt;--&lt;907.0,-1.0&gt;&gt;

* u183AB (U+183AB): L&lt;&lt;865.0,216.0&gt;--&lt;866.0,-9.0&gt;&gt;

* u183AD (U+183AD): L&lt;&lt;895.0,222.0&gt;--&lt;896.0,5.0&gt;&gt;

* u183B6 (U+183B6): L&lt;&lt;881.0,218.0&gt;--&lt;882.0,-2.0&gt;&gt;

* u183B8 (U+183B8): L&lt;&lt;856.0,219.0&gt;--&lt;857.0,-1.0&gt;&gt;

* u183BB (U+183BB): L&lt;&lt;894.0,222.0&gt;--&lt;895.0,-3.0&gt;&gt;

* u183BF (U+183BF): L&lt;&lt;891.0,218.0&gt;--&lt;892.0,-2.0&gt;&gt;

* u183C1 (U+183C1): L&lt;&lt;892.0,218.0&gt;--&lt;893.0,-2.0&gt;&gt;

* u183C2 (U+183C2): L&lt;&lt;862.0,197.0&gt;--&lt;863.0,-3.0&gt;&gt;

* u183C4 (U+183C4): L&lt;&lt;917.0,152.0&gt;--&lt;918.0,0.0&gt;&gt;

* u183C5 (U+183C5): L&lt;&lt;900.0,218.0&gt;--&lt;901.0,-2.0&gt;&gt;

* u183C6 (U+183C6): L&lt;&lt;857.0,124.0&gt;--&lt;858.0,-11.0&gt;&gt;

* u183C7 (U+183C7): L&lt;&lt;903.0,218.0&gt;--&lt;904.0,-2.0&gt;&gt;

* u183C8 (U+183C8): L&lt;&lt;906.0,138.0&gt;--&lt;907.0,-3.0&gt;&gt;

* u183CB (U+183CB): L&lt;&lt;905.0,142.0&gt;--&lt;906.0,-1.0&gt;&gt;

* u183D4 (U+183D4): L&lt;&lt;898.0,166.0&gt;--&lt;899.0,1.0&gt;&gt;

* u183D9 (U+183D9): L&lt;&lt;847.0,184.0&gt;--&lt;848.0,-1.0&gt;&gt;

* u183DB (U+183DB): L&lt;&lt;833.0,124.0&gt;--&lt;834.0,-11.0&gt;&gt;

* u183E0 (U+183E0): L&lt;&lt;899.0,218.0&gt;--&lt;900.0,-2.0&gt;&gt;

* u183E2 (U+183E2): L&lt;&lt;903.0,222.0&gt;--&lt;904.0,5.0&gt;&gt;

* u183E3 (U+183E3): L&lt;&lt;907.0,218.0&gt;--&lt;908.0,-2.0&gt;&gt;

* u183E6 (U+183E6): L&lt;&lt;893.0,142.0&gt;--&lt;894.0,-1.0&gt;&gt;

* u183EB (U+183EB): L&lt;&lt;849.0,124.0&gt;--&lt;850.0,-11.0&gt;&gt;

* u183F4 (U+183F4): L&lt;&lt;918.0,164.0&gt;--&lt;919.0,1.0&gt;&gt;

* u183F6 (U+183F6): L&lt;&lt;909.0,128.0&gt;--&lt;910.0,-9.0&gt;&gt;

* u183F8 (U+183F8): L&lt;&lt;896.0,218.0&gt;--&lt;897.0,-2.0&gt;&gt;

* u183F9 (U+183F9): L&lt;&lt;857.0,124.0&gt;--&lt;858.0,-11.0&gt;&gt;

* u183FE (U+183FE): L&lt;&lt;904.0,140.0&gt;--&lt;905.0,-1.0&gt;&gt;

* u18405 (U+18405): L&lt;&lt;905.0,178.0&gt;--&lt;906.0,-3.0&gt;&gt;

* u1840B (U+1840B): L&lt;&lt;898.0,166.0&gt;--&lt;899.0,1.0&gt;&gt;

* u1840D (U+1840D): L&lt;&lt;899.0,181.0&gt;--&lt;900.0,-3.0&gt;&gt;

* u1840E (U+1840E): L&lt;&lt;896.0,218.0&gt;--&lt;897.0,-2.0&gt;&gt;

* u1840F (U+1840F): L&lt;&lt;908.0,218.0&gt;--&lt;909.0,-2.0&gt;&gt;

* u18411 (U+18411): L&lt;&lt;902.0,218.0&gt;--&lt;903.0,-2.0&gt;&gt;

* u18413 (U+18413): L&lt;&lt;896.0,218.0&gt;--&lt;897.0,-2.0&gt;&gt;

* u18415 (U+18415): L&lt;&lt;905.0,175.0&gt;--&lt;906.0,-3.0&gt;&gt;

* u1841A (U+1841A): L&lt;&lt;898.0,166.0&gt;--&lt;899.0,1.0&gt;&gt;

* u1841B (U+1841B): L&lt;&lt;931.0,147.0&gt;--&lt;932.0,0.0&gt;&gt;

* u1841C (U+1841C): L&lt;&lt;905.0,175.0&gt;--&lt;906.0,-3.0&gt;&gt;

* u1841F (U+1841F): L&lt;&lt;896.0,218.0&gt;--&lt;897.0,-2.0&gt;&gt;

* u18420 (U+18420): L&lt;&lt;915.0,147.0&gt;--&lt;916.0,-1.0&gt;&gt;

* u18421 (U+18421): L&lt;&lt;905.0,178.0&gt;--&lt;906.0,-3.0&gt;&gt;

* u18422 (U+18422): L&lt;&lt;915.0,222.0&gt;--&lt;916.0,-3.0&gt;&gt;

* u18428 (U+18428): L&lt;&lt;833.0,123.0&gt;--&lt;834.0,-4.0&gt;&gt;

* u18430 (U+18430): L&lt;&lt;899.0,124.0&gt;--&lt;900.0,-11.0&gt;&gt;

* u18434 (U+18434): L&lt;&lt;826.0,127.0&gt;--&lt;827.0,-4.0&gt;&gt;

* u1843B (U+1843B): L&lt;&lt;885.0,136.0&gt;--&lt;886.0,-1.0&gt;&gt;

* u18440 (U+18440): L&lt;&lt;915.0,147.0&gt;--&lt;916.0,-1.0&gt;&gt;

* u18447 (U+18447): L&lt;&lt;904.0,197.0&gt;--&lt;905.0,-3.0&gt;&gt;

* u18448 (U+18448): L&lt;&lt;905.0,183.0&gt;--&lt;906.0,-3.0&gt;&gt;

* u1844C (U+1844C): L&lt;&lt;879.0,124.0&gt;--&lt;880.0,-11.0&gt;&gt;

* u1844E (U+1844E): L&lt;&lt;910.0,165.0&gt;--&lt;911.0,-3.0&gt;&gt;

* u18450 (U+18450): L&lt;&lt;894.0,112.0&gt;--&lt;895.0,-3.0&gt;&gt;

* u18454 (U+18454): L&lt;&lt;910.0,165.0&gt;--&lt;911.0,-3.0&gt;&gt;

* u18455 (U+18455): L&lt;&lt;902.0,413.0&gt;--&lt;903.0,276.0&gt;&gt;

* u1845C (U+1845C): L&lt;&lt;883.0,219.0&gt;--&lt;884.0,-1.0&gt;&gt;

* u1845D (U+1845D): L&lt;&lt;865.0,216.0&gt;--&lt;866.0,-9.0&gt;&gt;

* u18465 (U+18465): L&lt;&lt;878.0,160.0&gt;--&lt;879.0,-4.0&gt;&gt;

* u18468 (U+18468): L&lt;&lt;898.0,166.0&gt;--&lt;899.0,1.0&gt;&gt;

* u1846B (U+1846B): L&lt;&lt;850.0,219.0&gt;--&lt;851.0,-1.0&gt;&gt;

* u1846D (U+1846D): L&lt;&lt;881.0,218.0&gt;--&lt;882.0,-2.0&gt;&gt;

* u18473 (U+18473): L&lt;&lt;855.0,219.0&gt;--&lt;856.0,-1.0&gt;&gt;

* u18474 (U+18474): L&lt;&lt;891.0,140.0&gt;--&lt;892.0,-1.0&gt;&gt;

* u18477 (U+18477): L&lt;&lt;897.0,218.0&gt;--&lt;898.0,-2.0&gt;&gt;

* u1847A (U+1847A): L&lt;&lt;887.0,218.0&gt;--&lt;888.0,-2.0&gt;&gt;

* u1847C (U+1847C): L&lt;&lt;904.0,218.0&gt;--&lt;905.0,-2.0&gt;&gt;

* u18492 (U+18492): L&lt;&lt;857.0,119.0&gt;--&lt;858.0,-4.0&gt;&gt;

* u18493 (U+18493): L&lt;&lt;881.0,144.0&gt;--&lt;882.0,-10.0&gt;&gt;

* u18494 (U+18494): L&lt;&lt;852.0,123.0&gt;--&lt;853.0,-4.0&gt;&gt;

* u18498 (U+18498): L&lt;&lt;881.0,144.0&gt;--&lt;882.0,-10.0&gt;&gt;

* u184A1 (U+184A1): L&lt;&lt;896.0,135.0&gt;--&lt;897.0,-1.0&gt;&gt;

* u184A4 (U+184A4): L&lt;&lt;856.0,219.0&gt;--&lt;857.0,-1.0&gt;&gt;

* u184A8 (U+184A8): L&lt;&lt;896.0,197.0&gt;--&lt;897.0,-3.0&gt;&gt;

* u184AF (U+184AF): L&lt;&lt;889.0,166.0&gt;--&lt;890.0,1.0&gt;&gt;

* u184B1 (U+184B1): L&lt;&lt;926.0,164.0&gt;--&lt;927.0,1.0&gt;&gt;

* u184B7 (U+184B7): L&lt;&lt;887.0,166.0&gt;--&lt;888.0,1.0&gt;&gt;

* u184BA (U+184BA): L&lt;&lt;879.0,124.0&gt;--&lt;880.0,-11.0&gt;&gt;

* u184BB (U+184BB): L&lt;&lt;894.0,219.0&gt;--&lt;895.0,-1.0&gt;&gt;

* u184BC (U+184BC): L&lt;&lt;869.0,124.0&gt;--&lt;870.0,-11.0&gt;&gt;

* u184BD (U+184BD): L&lt;&lt;898.0,166.0&gt;--&lt;899.0,1.0&gt;&gt;

* u184BF (U+184BF): L&lt;&lt;898.0,166.0&gt;--&lt;899.0,1.0&gt;&gt;

* u184CD (U+184CD): L&lt;&lt;878.0,218.0&gt;--&lt;879.0,-2.0&gt;&gt;

* u184D2 (U+184D2): L&lt;&lt;891.0,139.0&gt;--&lt;892.0,-4.0&gt;&gt;

* u184DE (U+184DE): L&lt;&lt;907.0,165.0&gt;--&lt;908.0,1.0&gt;&gt;

* u184E0 (U+184E0): L&lt;&lt;898.0,197.0&gt;--&lt;899.0,-3.0&gt;&gt;

* u184E2 (U+184E2): L&lt;&lt;868.0,134.0&gt;--&lt;869.0,-3.0&gt;&gt;

* u184E3 (U+184E3): L&lt;&lt;886.0,219.0&gt;--&lt;887.0,-1.0&gt;&gt;

* u184E4 (U+184E4): L&lt;&lt;916.0,138.0&gt;--&lt;917.0,-3.0&gt;&gt;

* u184E5 (U+184E5): L&lt;&lt;853.0,124.0&gt;--&lt;854.0,-11.0&gt;&gt;

* u184E9 (U+184E9): L&lt;&lt;906.0,218.0&gt;--&lt;907.0,-2.0&gt;&gt;

* u184ED (U+184ED): L&lt;&lt;905.0,203.0&gt;--&lt;906.0,-9.0&gt;&gt;

* u184F3 (U+184F3): L&lt;&lt;925.0,166.0&gt;--&lt;926.0,1.0&gt;&gt;

* u184FC (U+184FC): L&lt;&lt;864.0,178.0&gt;--&lt;865.0,-3.0&gt;&gt;

* u184FD (U+184FD): L&lt;&lt;873.0,219.0&gt;--&lt;874.0,-1.0&gt;&gt;

* u184FF (U+184FF): L&lt;&lt;915.0,128.0&gt;--&lt;916.0,1.0&gt;&gt;

* u18504 (U+18504): L&lt;&lt;917.0,125.0&gt;--&lt;918.0,-2.0&gt;&gt;

* u1850D (U+1850D): L&lt;&lt;907.0,218.0&gt;--&lt;908.0,-2.0&gt;&gt;

* u1850F (U+1850F): L&lt;&lt;856.0,219.0&gt;--&lt;857.0,-1.0&gt;&gt;

* u18510 (U+18510): L&lt;&lt;898.0,166.0&gt;--&lt;899.0,1.0&gt;&gt;

* u18516 (U+18516): L&lt;&lt;904.0,128.0&gt;--&lt;905.0,1.0&gt;&gt;

* u1851A (U+1851A): L&lt;&lt;860.0,225.0&gt;--&lt;861.0,5.0&gt;&gt;

* u1851C (U+1851C): L&lt;&lt;880.0,197.0&gt;--&lt;881.0,-3.0&gt;&gt;

* u1851F (U+1851F): L&lt;&lt;910.0,197.0&gt;--&lt;911.0,-3.0&gt;&gt;

* u18523 (U+18523): L&lt;&lt;878.0,160.0&gt;--&lt;879.0,-4.0&gt;&gt;

* u1852E (U+1852E): L&lt;&lt;915.0,125.0&gt;--&lt;916.0,-2.0&gt;&gt;

* u18535 (U+18535): L&lt;&lt;911.0,128.0&gt;--&lt;912.0,-9.0&gt;&gt;

* u18538 (U+18538): L&lt;&lt;891.0,219.0&gt;--&lt;892.0,-1.0&gt;&gt;

* u1853A (U+1853A): L&lt;&lt;911.0,219.0&gt;--&lt;912.0,-1.0&gt;&gt;

* u18542 (U+18542): L&lt;&lt;853.0,219.0&gt;--&lt;854.0,-1.0&gt;&gt;

* u18548 (U+18548): L&lt;&lt;903.0,162.0&gt;--&lt;904.0,1.0&gt;&gt;

* u18549 (U+18549): L&lt;&lt;906.0,125.0&gt;--&lt;907.0,-2.0&gt;&gt;

* u18551 (U+18551): L&lt;&lt;880.0,139.0&gt;--&lt;881.0,-4.0&gt;&gt;

* u1855A (U+1855A): L&lt;&lt;883.0,166.0&gt;--&lt;884.0,-2.0&gt;&gt;

* u1855C (U+1855C): L&lt;&lt;893.0,152.0&gt;--&lt;894.0,0.0&gt;&gt;

* u1855D (U+1855D): L&lt;&lt;904.0,128.0&gt;--&lt;905.0,1.0&gt;&gt;

* u18560 (U+18560): L&lt;&lt;911.0,128.0&gt;--&lt;912.0,-9.0&gt;&gt;

* u18565 (U+18565): L&lt;&lt;918.0,166.0&gt;--&lt;919.0,1.0&gt;&gt;

* u18567 (U+18567): L&lt;&lt;891.0,219.0&gt;--&lt;892.0,-1.0&gt;&gt;

* u1856A (U+1856A): L&lt;&lt;897.0,218.0&gt;--&lt;898.0,-2.0&gt;&gt;

* u18571 (U+18571): L&lt;&lt;853.0,219.0&gt;--&lt;854.0,-1.0&gt;&gt;

* u18574 (U+18574): L&lt;&lt;885.0,162.0&gt;--&lt;886.0,1.0&gt;&gt;

* u18578 (U+18578): L&lt;&lt;867.0,219.0&gt;--&lt;868.0,-1.0&gt;&gt;

* u18579 (U+18579): L&lt;&lt;921.0,134.0&gt;--&lt;922.0,-3.0&gt;&gt;

* u1857A (U+1857A): L&lt;&lt;900.0,140.0&gt;--&lt;901.0,-1.0&gt;&gt;

* u1857D (U+1857D): L&lt;&lt;893.0,218.0&gt;--&lt;894.0,-2.0&gt;&gt;

* u1857E (U+1857E): L&lt;&lt;916.0,138.0&gt;--&lt;917.0,-3.0&gt;&gt;

* u1857F (U+1857F): L&lt;&lt;864.0,219.0&gt;--&lt;865.0,-1.0&gt;&gt;

* u18580 (U+18580): L&lt;&lt;881.0,218.0&gt;--&lt;882.0,-2.0&gt;&gt;

* u18582 (U+18582): L&lt;&lt;899.0,218.0&gt;--&lt;900.0,-2.0&gt;&gt;

* u18584 (U+18584): L&lt;&lt;880.0,139.0&gt;--&lt;881.0,-4.0&gt;&gt;

* u18592 (U+18592): L&lt;&lt;898.0,218.0&gt;--&lt;899.0,-2.0&gt;&gt;

* u18595 (U+18595): L&lt;&lt;906.0,113.0&gt;--&lt;907.0,-5.0&gt;&gt;

* u18599 (U+18599): L&lt;&lt;880.0,139.0&gt;--&lt;881.0,-4.0&gt;&gt;

* u185A3 (U+185A3): L&lt;&lt;803.0,123.0&gt;--&lt;804.0,-4.0&gt;&gt;

* u185A5 (U+185A5): L&lt;&lt;856.0,123.0&gt;--&lt;857.0,-4.0&gt;&gt;

* u185A6 (U+185A6): L&lt;&lt;889.0,139.0&gt;--&lt;890.0,-1.0&gt;&gt;

* u185A8 (U+185A8): L&lt;&lt;884.0,173.0&gt;--&lt;885.0,-3.0&gt;&gt;

* u185AB (U+185AB): L&lt;&lt;867.0,131.0&gt;--&lt;868.0,-4.0&gt;&gt;

* u185AD (U+185AD): L&lt;&lt;831.0,131.0&gt;--&lt;832.0,-4.0&gt;&gt;

* u185B1 (U+185B1): L&lt;&lt;872.0,131.0&gt;--&lt;873.0,-4.0&gt;&gt;

* u185B2 (U+185B2): L&lt;&lt;872.0,131.0&gt;--&lt;873.0,-4.0&gt;&gt;

* u185B4 (U+185B4): L&lt;&lt;869.0,123.0&gt;--&lt;870.0,-4.0&gt;&gt;

* u185B7 (U+185B7): L&lt;&lt;834.0,123.0&gt;--&lt;835.0,-4.0&gt;&gt;

* u185BA (U+185BA): L&lt;&lt;869.0,123.0&gt;--&lt;870.0,-4.0&gt;&gt;

* u185BF (U+185BF): L&lt;&lt;838.0,131.0&gt;--&lt;839.0,-4.0&gt;&gt;

* u185C1 (U+185C1): L&lt;&lt;872.0,131.0&gt;--&lt;873.0,-4.0&gt;&gt;

* u185C4 (U+185C4): L&lt;&lt;893.0,131.0&gt;--&lt;894.0,-4.0&gt;&gt;

* u185C6 (U+185C6): L&lt;&lt;893.0,131.0&gt;--&lt;894.0,-4.0&gt;&gt;

* u185C7 (U+185C7): L&lt;&lt;827.0,123.0&gt;--&lt;828.0,-4.0&gt;&gt;

* u185CA (U+185CA): L&lt;&lt;823.0,123.0&gt;--&lt;824.0,-4.0&gt;&gt;

* u185D5 (U+185D5): L&lt;&lt;843.0,181.0&gt;--&lt;844.0,-3.0&gt;&gt;

* u185D7 (U+185D7): L&lt;&lt;902.0,218.0&gt;--&lt;903.0,-2.0&gt;&gt;

* u185DB (U+185DB): L&lt;&lt;907.0,178.0&gt;--&lt;908.0,-3.0&gt;&gt;

* u185DC (U+185DC): L&lt;&lt;905.0,139.0&gt;--&lt;906.0,-4.0&gt;&gt;

* u185E5 (U+185E5): L&lt;&lt;862.0,219.0&gt;--&lt;863.0,-1.0&gt;&gt;

* u185EA (U+185EA): L&lt;&lt;890.0,143.0&gt;--&lt;891.0,0.0&gt;&gt;

* u185EB (U+185EB): L&lt;&lt;858.0,219.0&gt;--&lt;859.0,-1.0&gt;&gt;

* u185ED (U+185ED): L&lt;&lt;906.0,128.0&gt;--&lt;907.0,1.0&gt;&gt;

* u185F0 (U+185F0): L&lt;&lt;846.0,182.0&gt;--&lt;847.0,-4.0&gt;&gt;

* u185F1 (U+185F1): L&lt;&lt;890.0,150.0&gt;--&lt;891.0,1.0&gt;&gt;

* u185F2 (U+185F2): L&lt;&lt;880.0,139.0&gt;--&lt;881.0,-4.0&gt;&gt;

* u185F3 (U+185F3): L&lt;&lt;872.0,219.0&gt;--&lt;873.0,-1.0&gt;&gt;

* u185F6 (U+185F6): L&lt;&lt;906.0,219.0&gt;--&lt;907.0,-1.0&gt;&gt;

* u185FC (U+185FC): L&lt;&lt;862.0,219.0&gt;--&lt;863.0,-1.0&gt;&gt;

* u18600 (U+18600): L&lt;&lt;885.0,166.0&gt;--&lt;886.0,1.0&gt;&gt;

* u18602 (U+18602): L&lt;&lt;880.0,131.0&gt;--&lt;881.0,-4.0&gt;&gt;

* u18603 (U+18603): L&lt;&lt;862.0,218.0&gt;--&lt;863.0,-2.0&gt;&gt;

* u18604 (U+18604): L&lt;&lt;845.0,219.0&gt;--&lt;846.0,-1.0&gt;&gt;

* u18606 (U+18606): L&lt;&lt;908.0,171.0&gt;--&lt;909.0,1.0&gt;&gt;

* u1860B (U+1860B): L&lt;&lt;894.0,231.0&gt;--&lt;895.0,6.0&gt;&gt;

* u1860C (U+1860C): L&lt;&lt;895.0,231.0&gt;--&lt;896.0,6.0&gt;&gt;

* u1860D (U+1860D): L&lt;&lt;896.0,231.0&gt;--&lt;897.0,6.0&gt;&gt;

* u1860E (U+1860E): L&lt;&lt;895.0,231.0&gt;--&lt;896.0,6.0&gt;&gt;

* u1860F (U+1860F): L&lt;&lt;889.0,231.0&gt;--&lt;890.0,6.0&gt;&gt;

* u18616 (U+18616): L&lt;&lt;901.0,169.0&gt;--&lt;902.0,4.0&gt;&gt;

* u18619 (U+18619): L&lt;&lt;867.0,218.0&gt;--&lt;868.0,-2.0&gt;&gt;

* u1861B (U+1861B): L&lt;&lt;909.0,137.0&gt;--&lt;910.0,-4.0&gt;&gt;

* u18621 (U+18621): L&lt;&lt;915.0,218.0&gt;--&lt;916.0,-2.0&gt;&gt;

* u18622 (U+18622): L&lt;&lt;919.0,219.0&gt;--&lt;920.0,2.0&gt;&gt;

* u18628 (U+18628): L&lt;&lt;915.0,222.0&gt;--&lt;916.0,5.0&gt;&gt;

* u1862B (U+1862B): L&lt;&lt;879.0,218.0&gt;--&lt;880.0,-2.0&gt;&gt;

* u1862E (U+1862E): L&lt;&lt;922.0,122.0&gt;--&lt;923.0,-2.0&gt;&gt;

* u1862F (U+1862F): L&lt;&lt;915.0,192.0&gt;--&lt;916.0,3.0&gt;&gt;

* u18632 (U+18632): L&lt;&lt;869.0,125.0&gt;--&lt;870.0,-10.0&gt;&gt;

* u18633 (U+18633): L&lt;&lt;921.0,125.0&gt;--&lt;922.0,-2.0&gt;&gt;

* u18635 (U+18635): L&lt;&lt;896.0,181.0&gt;--&lt;897.0,2.0&gt;&gt;

* u1863A (U+1863A): L&lt;&lt;891.0,196.0&gt;--&lt;892.0,-3.0&gt;&gt;

* u1863B (U+1863B): L&lt;&lt;912.0,188.0&gt;--&lt;913.0,3.0&gt;&gt;

* u1863F (U+1863F): L&lt;&lt;894.0,218.0&gt;--&lt;895.0,-2.0&gt;&gt;

* u18641 (U+18641): L&lt;&lt;850.0,124.0&gt;--&lt;851.0,-11.0&gt;&gt;

* u18646 (U+18646): L&lt;&lt;909.0,152.0&gt;--&lt;910.0,0.0&gt;&gt;

* u18647 (U+18647): L&lt;&lt;907.0,218.0&gt;--&lt;908.0,-2.0&gt;&gt;

* u1864B (U+1864B): L&lt;&lt;900.0,218.0&gt;--&lt;901.0,-2.0&gt;&gt;

* u1864F (U+1864F): L&lt;&lt;934.0,218.0&gt;--&lt;935.0,-2.0&gt;&gt;

* u18653 (U+18653): L&lt;&lt;900.0,218.0&gt;--&lt;901.0,-2.0&gt;&gt;

* u18654 (U+18654): L&lt;&lt;887.0,218.0&gt;--&lt;888.0,-2.0&gt;&gt;

* u1865B (U+1865B): L&lt;&lt;911.0,133.0&gt;--&lt;912.0,-4.0&gt;&gt;

* u1865C (U+1865C): L&lt;&lt;898.0,133.0&gt;--&lt;899.0,-4.0&gt;&gt;

* u1865D (U+1865D): L&lt;&lt;915.0,218.0&gt;--&lt;916.0,-2.0&gt;&gt;

* u1865E (U+1865E): L&lt;&lt;904.0,179.0&gt;--&lt;905.0,-3.0&gt;&gt;

* u18666 (U+18666): L&lt;&lt;891.0,138.0&gt;--&lt;892.0,-6.0&gt;&gt;

* u18668 (U+18668): L&lt;&lt;898.0,159.0&gt;--&lt;899.0,1.0&gt;&gt;

* u18669 (U+18669): L&lt;&lt;918.0,174.0&gt;--&lt;919.0,2.0&gt;&gt;

* u18670 (U+18670): L&lt;&lt;847.0,218.0&gt;--&lt;848.0,-2.0&gt;&gt;

* u18672 (U+18672): L&lt;&lt;876.0,218.0&gt;--&lt;877.0,-2.0&gt;&gt;

* u18676 (U+18676): L&lt;&lt;914.0,186.0&gt;--&lt;915.0,3.0&gt;&gt;

* u18677 (U+18677): L&lt;&lt;898.0,182.0&gt;--&lt;899.0,-3.0&gt;&gt;

* u1867E (U+1867E): L&lt;&lt;908.0,114.0&gt;--&lt;909.0,-2.0&gt;&gt;

* u18684 (U+18684): L&lt;&lt;886.0,138.0&gt;--&lt;887.0,-3.0&gt;&gt;

* u18688 (U+18688): L&lt;&lt;909.0,138.0&gt;--&lt;910.0,-3.0&gt;&gt;

* u18689 (U+18689): L&lt;&lt;841.0,128.0&gt;--&lt;842.0,-4.0&gt;&gt;

* u1868C (U+1868C): L&lt;&lt;851.0,219.0&gt;--&lt;852.0,-1.0&gt;&gt;

* u1868D (U+1868D): L&lt;&lt;897.0,138.0&gt;--&lt;898.0,-3.0&gt;&gt;

* u18692 (U+18692): L&lt;&lt;910.0,128.0&gt;--&lt;911.0,-9.0&gt;&gt;

* u18693 (U+18693): L&lt;&lt;888.0,138.0&gt;--&lt;889.0,-3.0&gt;&gt;

* u18699 (U+18699): L&lt;&lt;904.0,181.0&gt;--&lt;905.0,2.0&gt;&gt;

* u1869F (U+1869F): L&lt;&lt;933.0,188.0&gt;--&lt;934.0,3.0&gt;&gt;

* u186A2 (U+186A2): L&lt;&lt;861.0,218.0&gt;--&lt;862.0,-2.0&gt;&gt;

* u186A5 (U+186A5): L&lt;&lt;882.0,219.0&gt;--&lt;883.0,-1.0&gt;&gt;

* u186AB (U+186AB): L&lt;&lt;842.0,218.0&gt;--&lt;843.0,-2.0&gt;&gt;

* u186B2 (U+186B2): L&lt;&lt;844.0,124.0&gt;--&lt;845.0,-11.0&gt;&gt;

* u186B3 (U+186B3): L&lt;&lt;905.0,188.0&gt;--&lt;906.0,3.0&gt;&gt;

* u186B5 (U+186B5): L&lt;&lt;912.0,166.0&gt;--&lt;913.0,1.0&gt;&gt;

* u186B6 (U+186B6): L&lt;&lt;883.0,218.0&gt;--&lt;884.0,-2.0&gt;&gt;

* u186B7 (U+186B7): L&lt;&lt;884.0,218.0&gt;--&lt;885.0,-2.0&gt;&gt;

* u186BB (U+186BB): L&lt;&lt;891.0,648.0&gt;--&lt;892.0,488.0&gt;&gt;

* u186BD (U+186BD): L&lt;&lt;895.0,161.0&gt;--&lt;896.0,1.0&gt;&gt;

* u186BF (U+186BF): L&lt;&lt;233.0,682.0&gt;--&lt;232.0,823.0&gt;&gt;

* u186BF (U+186BF): L&lt;&lt;465.0,653.0&gt;--&lt;97.0,651.0&gt;&gt;

* u186C0 (U+186C0): L&lt;&lt;238.0,682.0&gt;--&lt;237.0,823.0&gt;&gt;

* u186C0 (U+186C0): L&lt;&lt;489.0,654.0&gt;--&lt;217.0,652.0&gt;&gt;

* u186C1 (U+186C1): L&lt;&lt;238.0,682.0&gt;--&lt;237.0,823.0&gt;&gt;

* u186C1 (U+186C1): L&lt;&lt;489.0,654.0&gt;--&lt;217.0,652.0&gt;&gt;

* u186C2 (U+186C2): L&lt;&lt;238.0,682.0&gt;--&lt;237.0,823.0&gt;&gt;

* u186C2 (U+186C2): L&lt;&lt;489.0,654.0&gt;--&lt;217.0,652.0&gt;&gt;

* u186C4 (U+186C4): L&lt;&lt;925.0,138.0&gt;--&lt;926.0,-3.0&gt;&gt;

* u186C8 (U+186C8): L&lt;&lt;918.0,188.0&gt;--&lt;919.0,3.0&gt;&gt;

* u186C9 (U+186C9): L&lt;&lt;910.0,122.0&gt;--&lt;911.0,-2.0&gt;&gt;

* u186D2 (U+186D2): L&lt;&lt;893.0,218.0&gt;--&lt;894.0,-2.0&gt;&gt;

* u186D3 (U+186D3): L&lt;&lt;859.0,219.0&gt;--&lt;860.0,-1.0&gt;&gt;

* u186D6 (U+186D6): L&lt;&lt;869.0,199.0&gt;--&lt;870.0,10.0&gt;&gt;

* u186DA (U+186DA): L&lt;&lt;910.0,188.0&gt;--&lt;911.0,3.0&gt;&gt;

* u186E0 (U+186E0): L&lt;&lt;864.0,219.0&gt;--&lt;865.0,-1.0&gt;&gt;

* u186E2 (U+186E2): L&lt;&lt;876.0,219.0&gt;--&lt;877.0,-1.0&gt;&gt;

* u186E3 (U+186E3): L&lt;&lt;886.0,222.0&gt;--&lt;887.0,-3.0&gt;&gt;

* u186E7 (U+186E7): L&lt;&lt;848.0,219.0&gt;--&lt;849.0,-1.0&gt;&gt;

* u186EB (U+186EB): L&lt;&lt;873.0,218.0&gt;--&lt;874.0,-2.0&gt;&gt;

* u186F2 (U+186F2): L&lt;&lt;869.0,219.0&gt;--&lt;870.0,-1.0&gt;&gt;

* u186FA (U+186FA): L&lt;&lt;896.0,218.0&gt;--&lt;897.0,-2.0&gt;&gt;

* u186FB (U+186FB): L&lt;&lt;902.0,188.0&gt;--&lt;903.0,3.0&gt;&gt;

* u186FC (U+186FC): L&lt;&lt;905.0,152.0&gt;--&lt;906.0,0.0&gt;&gt;

* u18702 (U+18702): L&lt;&lt;853.0,218.0&gt;--&lt;854.0,-2.0&gt;&gt;

* u18709 (U+18709): L&lt;&lt;907.0,156.0&gt;--&lt;908.0,-1.0&gt;&gt;

* u1870D (U+1870D): L&lt;&lt;880.0,218.0&gt;--&lt;881.0,-2.0&gt;&gt;

* u1870F (U+1870F): L&lt;&lt;890.0,153.0&gt;--&lt;891.0,-3.0&gt;&gt;

* u18712 (U+18712): L&lt;&lt;875.0,218.0&gt;--&lt;876.0,-2.0&gt;&gt;

* u18713 (U+18713): L&lt;&lt;910.0,188.0&gt;--&lt;911.0,3.0&gt;&gt;

* u18717 (U+18717): L&lt;&lt;895.0,218.0&gt;--&lt;896.0,-2.0&gt;&gt;

* u18718 (U+18718): L&lt;&lt;912.0,164.0&gt;--&lt;913.0,1.0&gt;&gt;

* u1871B (U+1871B): L&lt;&lt;903.0,125.0&gt;--&lt;904.0,-2.0&gt;&gt;

* u18722 (U+18722): L&lt;&lt;855.0,219.0&gt;--&lt;856.0,-1.0&gt;&gt;

* u18726 (U+18726): L&lt;&lt;904.0,188.0&gt;--&lt;905.0,3.0&gt;&gt;

* u18728 (U+18728): L&lt;&lt;871.0,139.0&gt;--&lt;872.0,-4.0&gt;&gt;

* u18729 (U+18729): L&lt;&lt;899.0,139.0&gt;--&lt;900.0,-4.0&gt;&gt;

* u1872A (U+1872A): L&lt;&lt;909.0,167.0&gt;--&lt;910.0,2.0&gt;&gt;

* u18734 (U+18734): L&lt;&lt;881.0,219.0&gt;--&lt;882.0,-1.0&gt;&gt;

* u18738 (U+18738): L&lt;&lt;907.0,181.0&gt;--&lt;908.0,2.0&gt;&gt;

* u1873A (U+1873A): L&lt;&lt;923.0,222.0&gt;--&lt;924.0,-3.0&gt;&gt;

* u1873D (U+1873D): L&lt;&lt;857.0,132.0&gt;--&lt;858.0,-3.0&gt;&gt;

* u1873E (U+1873E): L&lt;&lt;912.0,138.0&gt;--&lt;913.0,-3.0&gt;&gt;

* u18741 (U+18741): L&lt;&lt;855.0,197.0&gt;--&lt;856.0,-3.0&gt;&gt;

* u18744 (U+18744): L&lt;&lt;911.0,128.0&gt;--&lt;912.0,-9.0&gt;&gt;

* u18745 (U+18745): L&lt;&lt;893.0,218.0&gt;--&lt;894.0,-2.0&gt;&gt;

* u18746 (U+18746): L&lt;&lt;888.0,218.0&gt;--&lt;889.0,-2.0&gt;&gt;

* u1874C (U+1874C): L&lt;&lt;907.0,222.0&gt;--&lt;908.0,-3.0&gt;&gt;

* u1874F (U+1874F): L&lt;&lt;906.0,218.0&gt;--&lt;907.0,-2.0&gt;&gt;

* u18753 (U+18753): L&lt;&lt;818.0,181.0&gt;--&lt;819.0,-3.0&gt;&gt;

* u18754 (U+18754): L&lt;&lt;902.0,172.0&gt;--&lt;903.0,7.0&gt;&gt;

* u18759 (U+18759): L&lt;&lt;850.0,219.0&gt;--&lt;851.0,-1.0&gt;&gt;

* u1875A (U+1875A): L&lt;&lt;913.0,222.0&gt;--&lt;914.0,5.0&gt;&gt;

* u1875B (U+1875B): L&lt;&lt;913.0,222.0&gt;--&lt;914.0,5.0&gt;&gt;

* u1875C (U+1875C): L&lt;&lt;828.0,323.0&gt;--&lt;829.0,103.0&gt;&gt;

* u1875C (U+1875C): L&lt;&lt;907.0,222.0&gt;--&lt;908.0,5.0&gt;&gt;

* u1875D (U+1875D): L&lt;&lt;866.0,219.0&gt;--&lt;867.0,-1.0&gt;&gt;

* u1875F (U+1875F): L&lt;&lt;889.0,219.0&gt;--&lt;890.0,-1.0&gt;&gt;

* u18764 (U+18764): L&lt;&lt;912.0,218.0&gt;--&lt;913.0,-2.0&gt;&gt;

* u18766 (U+18766): L&lt;&lt;925.0,152.0&gt;--&lt;926.0,0.0&gt;&gt;

* u18769 (U+18769): L&lt;&lt;893.0,219.0&gt;--&lt;894.0,-1.0&gt;&gt;

* u1876A (U+1876A): L&lt;&lt;857.0,219.0&gt;--&lt;858.0,-1.0&gt;&gt;

* u1876D (U+1876D): L&lt;&lt;903.0,218.0&gt;--&lt;904.0,-2.0&gt;&gt;

* u1876F (U+1876F): L&lt;&lt;892.0,152.0&gt;--&lt;893.0,0.0&gt;&gt;

* u18772 (U+18772): L&lt;&lt;912.0,197.0&gt;--&lt;913.0,-3.0&gt;&gt;

* u18774 (U+18774): L&lt;&lt;903.0,219.0&gt;--&lt;904.0,-1.0&gt;&gt;

* u18779 (U+18779): L&lt;&lt;854.0,219.0&gt;--&lt;855.0,-1.0&gt;&gt;

* u1877C (U+1877C): L&lt;&lt;913.0,150.0&gt;--&lt;914.0,1.0&gt;&gt;

* u18784 (U+18784): L&lt;&lt;899.0,138.0&gt;--&lt;900.0,-1.0&gt;&gt;

* u18788 (U+18788): L&lt;&lt;906.0,181.0&gt;--&lt;907.0,-3.0&gt;&gt;

* u18789 (U+18789): L&lt;&lt;889.0,152.0&gt;--&lt;890.0,0.0&gt;&gt;

* u1878D (U+1878D): L&lt;&lt;874.0,197.0&gt;--&lt;875.0,-3.0&gt;&gt;

* u1878E (U+1878E): L&lt;&lt;900.0,152.0&gt;--&lt;901.0,0.0&gt;&gt;

* u18791 (U+18791): L&lt;&lt;565.0,-73.0&gt;--&lt;564.0,429.0&gt;&gt;

* u18791 (U+18791): L&lt;&lt;626.0,479.0&gt;--&lt;627.0,152.0&gt;&gt;

* u18793 (U+18793): L&lt;&lt;918.0,152.0&gt;--&lt;919.0,0.0&gt;&gt;

* u18795 (U+18795): L&lt;&lt;911.0,175.0&gt;--&lt;912.0,-3.0&gt;&gt;

* u18797 (U+18797): L&lt;&lt;882.0,539.0&gt;--&lt;883.0,369.0&gt;&gt;

* u18798 (U+18798): L&lt;&lt;892.0,222.0&gt;--&lt;893.0,5.0&gt;&gt;

* u1879A (U+1879A): L&lt;&lt;914.0,197.0&gt;--&lt;915.0,-3.0&gt;&gt;

* u1879B (U+1879B): L&lt;&lt;905.0,197.0&gt;--&lt;906.0,-3.0&gt;&gt;

* u187A2 (U+187A2): L&lt;&lt;911.0,128.0&gt;--&lt;912.0,-9.0&gt;&gt;

* u187A4 (U+187A4): L&lt;&lt;874.0,124.0&gt;--&lt;875.0,6.0&gt;&gt;

* u187A8 (U+187A8): L&lt;&lt;887.0,197.0&gt;--&lt;888.0,-3.0&gt;&gt;

* u187AA (U+187AA): L&lt;&lt;852.0,197.0&gt;--&lt;853.0,-3.0&gt;&gt;

* u187AC (U+187AC): L&lt;&lt;903.0,172.0&gt;--&lt;904.0,7.0&gt;&gt;

* u187AF (U+187AF): L&lt;&lt;882.0,197.0&gt;--&lt;883.0,-3.0&gt;&gt;

* u187C9 (U+187C9): L&lt;&lt;912.0,178.0&gt;--&lt;913.0,-3.0&gt;&gt;

* u187CB (U+187CB): L&lt;&lt;882.0,580.0&gt;--&lt;883.0,410.0&gt;&gt;

* u187CD (U+187CD): L&lt;&lt;932.0,135.0&gt;--&lt;933.0,-1.0&gt;&gt;

* u187CE (U+187CE): L&lt;&lt;926.0,135.0&gt;--&lt;927.0,-1.0&gt;&gt;

* u187D1 (U+187D1): L&lt;&lt;915.0,137.0&gt;--&lt;916.0,1.0&gt;&gt;

* u187D2 (U+187D2): L&lt;&lt;926.0,135.0&gt;--&lt;927.0,-1.0&gt;&gt;

* u187D5 (U+187D5): L&lt;&lt;878.0,197.0&gt;--&lt;879.0,-3.0&gt;&gt;

* u187DB (U+187DB): L&lt;&lt;865.0,152.0&gt;--&lt;866.0,0.0&gt;&gt;

* u187DC (U+187DC): L&lt;&lt;887.0,197.0&gt;--&lt;888.0,-3.0&gt;&gt;

* u187DD (U+187DD): L&lt;&lt;914.0,222.0&gt;--&lt;915.0,5.0&gt;&gt;

* u187E3 (U+187E3): L&lt;&lt;917.0,125.0&gt;--&lt;918.0,-2.0&gt;&gt;

* u187E4 (U+187E4): L&lt;&lt;904.0,205.0&gt;--&lt;905.0,5.0&gt;&gt;

* u187E8 (U+187E8): L&lt;&lt;923.0,154.0&gt;--&lt;924.0,0.0&gt;&gt;

* u187EB (U+187EB): L&lt;&lt;880.0,218.0&gt;--&lt;881.0,-2.0&gt;&gt;

* u187EC (U+187EC): L&lt;&lt;906.0,128.0&gt;--&lt;907.0,-1.0&gt;&gt;

* u18806 (U+18806): L&lt;&lt;676.0,218.0&gt;--&lt;677.0,-2.0&gt;&gt;

* u18807 (U+18807): L&lt;&lt;870.0,218.0&gt;--&lt;871.0,-2.0&gt;&gt;

* u18813 (U+18813): L&lt;&lt;775.0,222.0&gt;--&lt;776.0,5.0&gt;&gt;

* u18814 (U+18814): L&lt;&lt;884.0,222.0&gt;--&lt;885.0,5.0&gt;&gt;

* u18822 (U+18822): L&lt;&lt;651.0,218.0&gt;--&lt;652.0,-2.0&gt;&gt;

* u1882A (U+1882A): L&lt;&lt;862.0,218.0&gt;--&lt;863.0,-2.0&gt;&gt;

* u18830 (U+18830): L&lt;&lt;825.0,222.0&gt;--&lt;826.0,5.0&gt;&gt;

* u18834 (U+18834): L&lt;&lt;651.0,218.0&gt;--&lt;652.0,-2.0&gt;&gt;

* u18837 (U+18837): L&lt;&lt;709.0,158.0&gt;--&lt;710.0,-6.0&gt;&gt;

* u1883A (U+1883A): L&lt;&lt;775.0,222.0&gt;--&lt;776.0,5.0&gt;&gt;

* u1883E (U+1883E): L&lt;&lt;669.0,152.0&gt;--&lt;670.0,0.0&gt;&gt;

* u18846 (U+18846): L&lt;&lt;686.0,218.0&gt;--&lt;687.0,-2.0&gt;&gt;

* u1885E (U+1885E): L&lt;&lt;653.0,218.0&gt;--&lt;654.0,-2.0&gt;&gt;

* u18865 (U+18865): L&lt;&lt;731.0,146.0&gt;--&lt;732.0,0.0&gt;&gt;

* u18867 (U+18867): L&lt;&lt;656.0,219.0&gt;--&lt;657.0,-1.0&gt;&gt;

* u18868 (U+18868): L&lt;&lt;660.0,220.0&gt;--&lt;661.0,0.0&gt;&gt;

* u1886C (U+1886C): L&lt;&lt;736.0,222.0&gt;--&lt;737.0,5.0&gt;&gt;

* u1886D (U+1886D): L&lt;&lt;733.0,152.0&gt;--&lt;734.0,0.0&gt;&gt;

* u18874 (U+18874): L&lt;&lt;640.0,157.0&gt;--&lt;641.0,-4.0&gt;&gt;

* u1887A (U+1887A): L&lt;&lt;766.0,222.0&gt;--&lt;767.0,5.0&gt;&gt;

* u1887C (U+1887C): L&lt;&lt;752.0,222.0&gt;--&lt;753.0,5.0&gt;&gt;

* u1887E (U+1887E): L&lt;&lt;771.0,169.0&gt;--&lt;772.0,-3.0&gt;&gt;

* u18880 (U+18880): L&lt;&lt;720.0,159.0&gt;--&lt;721.0,1.0&gt;&gt;

* u18881 (U+18881): L&lt;&lt;753.0,192.0&gt;--&lt;754.0,3.0&gt;&gt;

* u18887 (U+18887): L&lt;&lt;740.0,175.0&gt;--&lt;741.0,-4.0&gt;&gt;

* u18895 (U+18895): L&lt;&lt;703.0,225.0&gt;--&lt;704.0,5.0&gt;&gt;

* u18896 (U+18896): L&lt;&lt;901.0,167.0&gt;--&lt;902.0,3.0&gt;&gt;

* u1889B (U+1889B): L&lt;&lt;914.0,222.0&gt;--&lt;915.0,5.0&gt;&gt;

* u1889E (U+1889E): L&lt;&lt;656.0,219.0&gt;--&lt;657.0,-1.0&gt;&gt;

* u188A6 (U+188A6): L&lt;&lt;901.0,222.0&gt;--&lt;902.0,5.0&gt;&gt;

* u188B1 (U+188B1): L&lt;&lt;731.0,146.0&gt;--&lt;732.0,0.0&gt;&gt;

* u188B2 (U+188B2): L&lt;&lt;868.0,222.0&gt;--&lt;869.0,5.0&gt;&gt;

* u188B6 (U+188B6): L&lt;&lt;673.0,226.0&gt;--&lt;674.0,1.0&gt;&gt;

* u188C8 (U+188C8): L&lt;&lt;677.0,161.0&gt;--&lt;678.0,-2.0&gt;&gt;

* u188C9 (U+188C9): L&lt;&lt;860.0,218.0&gt;--&lt;861.0,-2.0&gt;&gt;

* u188D2 (U+188D2): L&lt;&lt;662.0,198.0&gt;--&lt;663.0,-2.0&gt;&gt;

* u188D3 (U+188D3): L&lt;&lt;662.0,199.0&gt;--&lt;663.0,-1.0&gt;&gt;

* u188DB (U+188DB): L&lt;&lt;906.0,206.0&gt;--&lt;907.0,4.0&gt;&gt;

* u188DE (U+188DE): L&lt;&lt;751.0,126.0&gt;--&lt;752.0,2.0&gt;&gt;

* u188E1 (U+188E1): L&lt;&lt;749.0,192.0&gt;--&lt;750.0,3.0&gt;&gt;

* u188E2 (U+188E2): L&lt;&lt;907.0,222.0&gt;--&lt;908.0,5.0&gt;&gt;

* u188ED (U+188ED): L&lt;&lt;668.0,125.0&gt;--&lt;669.0,-10.0&gt;&gt;

* u188EE (U+188EE): L&lt;&lt;685.0,148.0&gt;--&lt;686.0,-4.0&gt;&gt;

* u188F5 (U+188F5): L&lt;&lt;676.0,138.0&gt;--&lt;677.0,-3.0&gt;&gt;

* u188F7 (U+188F7): L&lt;&lt;746.0,138.0&gt;--&lt;747.0,-3.0&gt;&gt;

* u188F8 (U+188F8): L&lt;&lt;777.0,142.0&gt;--&lt;778.0,-1.0&gt;&gt;

* u188FA (U+188FA): L&lt;&lt;709.0,222.0&gt;--&lt;710.0,5.0&gt;&gt;

* u188FB (U+188FB): L&lt;&lt;773.0,222.0&gt;--&lt;774.0,5.0&gt;&gt;

* u188FC (U+188FC): L&lt;&lt;749.0,170.0&gt;--&lt;750.0,9.0&gt;&gt;

* u18908 (U+18908): L&lt;&lt;640.0,225.0&gt;--&lt;641.0,5.0&gt;&gt;

* u18911 (U+18911): L&lt;&lt;671.0,180.0&gt;--&lt;672.0,-2.0&gt;&gt;

* u18913 (U+18913): L&lt;&lt;736.0,125.0&gt;--&lt;737.0,-2.0&gt;&gt;

* u18914 (U+18914): L&lt;&lt;744.0,166.0&gt;--&lt;745.0,1.0&gt;&gt;

* u18917 (U+18917): L&lt;&lt;687.0,197.0&gt;--&lt;688.0,-3.0&gt;&gt;

* u18922 (U+18922): L&lt;&lt;742.0,201.0&gt;--&lt;743.0,4.0&gt;&gt;

* u18924 (U+18924): L&lt;&lt;720.0,114.0&gt;--&lt;721.0,-2.0&gt;&gt;

* u18925 (U+18925): L&lt;&lt;718.0,166.0&gt;--&lt;719.0,1.0&gt;&gt;

* u1892F (U+1892F): L&lt;&lt;688.0,131.0&gt;--&lt;689.0,-4.0&gt;&gt;

* u18938 (U+18938): L&lt;&lt;746.0,125.0&gt;--&lt;747.0,-2.0&gt;&gt;

* u1893A (U+1893A): L&lt;&lt;739.0,125.0&gt;--&lt;740.0,-2.0&gt;&gt;

* u1893E (U+1893E): L&lt;&lt;672.0,124.0&gt;--&lt;673.0,-11.0&gt;&gt;

* u1893F (U+1893F): L&lt;&lt;818.0,218.0&gt;--&lt;819.0,-2.0&gt;&gt;

* u18945 (U+18945): L&lt;&lt;137.0,774.0&gt;--&lt;646.0,775.0&gt;&gt;

* u18945 (U+18945): L&lt;&lt;267.0,554.0&gt;--&lt;452.0,555.0&gt;&gt;

* u18945 (U+18945): L&lt;&lt;493.0,525.0&gt;--&lt;267.0,524.0&gt;&gt;

* u18945 (U+18945): L&lt;&lt;627.0,745.0&gt;--&lt;146.0,744.0&gt;&gt;

* u18945 (U+18945): L&lt;&lt;914.0,526.0&gt;--&lt;622.0,525.0&gt;&gt;

* u18960 (U+18960): L&lt;&lt;696.0,129.0&gt;--&lt;697.0,-2.0&gt;&gt;

* u18966 (U+18966): L&lt;&lt;742.0,188.0&gt;--&lt;743.0,3.0&gt;&gt;

* u1896C (U+1896C): L&lt;&lt;777.0,128.0&gt;--&lt;778.0,-1.0&gt;&gt;

* u18978 (U+18978): L&lt;&lt;778.0,226.0&gt;--&lt;779.0,9.0&gt;&gt;

* u18979 (U+18979): L&lt;&lt;878.0,226.0&gt;--&lt;879.0,9.0&gt;&gt;

* u18987 (U+18987): L&lt;&lt;708.0,166.0&gt;--&lt;709.0,1.0&gt;&gt;

* u18995 (U+18995): L&lt;&lt;621.0,124.0&gt;--&lt;622.0,-11.0&gt;&gt;

* u18997 (U+18997): L&lt;&lt;740.0,164.0&gt;--&lt;741.0,1.0&gt;&gt;

* u18999 (U+18999): L&lt;&lt;702.0,169.0&gt;--&lt;703.0,4.0&gt;&gt;

* u1899C (U+1899C): L&lt;&lt;656.0,225.0&gt;--&lt;657.0,5.0&gt;&gt;

* u1899D (U+1899D): L&lt;&lt;397.0,-80.0&gt;--&lt;396.0,408.0&gt;&gt;

* u1899D (U+1899D): L&lt;&lt;459.0,452.0&gt;--&lt;460.0,141.0&gt;&gt;

* u1899F (U+1899F): L&lt;&lt;903.0,222.0&gt;--&lt;904.0,5.0&gt;&gt;

* u189A7 (U+189A7): L&lt;&lt;740.0,134.0&gt;--&lt;741.0,0.0&gt;&gt;

* u189B2 (U+189B2): L&lt;&lt;748.0,128.0&gt;--&lt;749.0,-1.0&gt;&gt;

* u189BA (U+189BA): L&lt;&lt;646.0,134.0&gt;--&lt;647.0,-4.0&gt;&gt;

* u189BC (U+189BC): L&lt;&lt;759.0,152.0&gt;--&lt;760.0,0.0&gt;&gt;

* u189C8 (U+189C8): L&lt;&lt;695.0,222.0&gt;--&lt;696.0,-3.0&gt;&gt;

* u189CE (U+189CE): L&lt;&lt;642.0,148.0&gt;--&lt;643.0,-1.0&gt;&gt;

* u189DC (U+189DC): L&lt;&lt;737.0,156.0&gt;--&lt;738.0,0.0&gt;&gt;

* u189E0 (U+189E0): L&lt;&lt;655.0,185.0&gt;--&lt;656.0,-1.0&gt;&gt;

* u189E1 (U+189E1): L&lt;&lt;744.0,140.0&gt;--&lt;745.0,-1.0&gt;&gt;

* u189FA (U+189FA): L&lt;&lt;698.0,166.0&gt;--&lt;699.0,1.0&gt;&gt;

* u189FD (U+189FD): L&lt;&lt;702.0,218.0&gt;--&lt;703.0,-2.0&gt;&gt;

* u18A04 (U+18A04): L&lt;&lt;801.0,130.0&gt;--&lt;802.0,-7.0&gt;&gt;

* u18A05 (U+18A05): L&lt;&lt;771.0,130.0&gt;--&lt;772.0,-7.0&gt;&gt;

* u18A0A (U+18A0A): L&lt;&lt;684.0,129.0&gt;--&lt;685.0,-2.0&gt;&gt;

* u18A0B (U+18A0B): L&lt;&lt;897.0,218.0&gt;--&lt;898.0,-2.0&gt;&gt;

* u18A10 (U+18A10): L&lt;&lt;718.0,166.0&gt;--&lt;719.0,1.0&gt;&gt;

* u18A27 (U+18A27): L&lt;&lt;788.0,147.0&gt;--&lt;789.0,0.0&gt;&gt;

* u18A29 (U+18A29): L&lt;&lt;754.0,152.0&gt;--&lt;755.0,0.0&gt;&gt;

* u18A31 (U+18A31): L&lt;&lt;674.0,160.0&gt;--&lt;675.0,-4.0&gt;&gt;

* u18A32 (U+18A32): L&lt;&lt;863.0,231.0&gt;--&lt;864.0,6.0&gt;&gt;

* u18A35 (U+18A35): L&lt;&lt;919.0,219.0&gt;--&lt;920.0,2.0&gt;&gt;

* u18A3E (U+18A3E): L&lt;&lt;738.0,219.0&gt;--&lt;739.0,2.0&gt;&gt;

* u18A46 (U+18A46): L&lt;&lt;687.0,219.0&gt;--&lt;688.0,-1.0&gt;&gt;

* u18A55 (U+18A55): L&lt;&lt;739.0,124.0&gt;--&lt;740.0,-2.0&gt;&gt;

* u18A59 (U+18A59): L&lt;&lt;721.0,648.0&gt;--&lt;722.0,488.0&gt;&gt;

* u18A5B (U+18A5B): L&lt;&lt;715.0,161.0&gt;--&lt;716.0,1.0&gt;&gt;

* u18A5E (U+18A5E): L&lt;&lt;453.0,682.0&gt;--&lt;452.0,823.0&gt;&gt;

* u18A5E (U+18A5E): L&lt;&lt;685.0,653.0&gt;--&lt;317.0,651.0&gt;&gt;

* u18A5F (U+18A5F): L&lt;&lt;438.0,682.0&gt;--&lt;437.0,823.0&gt;&gt;

* u18A5F (U+18A5F): L&lt;&lt;689.0,654.0&gt;--&lt;417.0,652.0&gt;&gt;

* u18A66 (U+18A66): L&lt;&lt;878.0,218.0&gt;--&lt;879.0,-2.0&gt;&gt;

* u18A6B (U+18A6B): L&lt;&lt;745.0,222.0&gt;--&lt;746.0,5.0&gt;&gt;

* u18A75 (U+18A75): L&lt;&lt;688.0,125.0&gt;--&lt;689.0,-2.0&gt;&gt;

* u18A94 (U+18A94): L&lt;&lt;906.0,214.0&gt;--&lt;907.0,4.0&gt;&gt;

* u18AAA (U+18AAA): L&lt;&lt;764.0,166.0&gt;--&lt;765.0,1.0&gt;&gt;

* u18AAB (U+18AAB): L&lt;&lt;904.0,222.0&gt;--&lt;905.0,5.0&gt;&gt;

* u18ABA (U+18ABA): L&lt;&lt;719.0,166.0&gt;--&lt;720.0,1.0&gt;&gt;

* u18ACA (U+18ACA): L&lt;&lt;749.0,522.0&gt;--&lt;750.0,357.0&gt;&gt;

* u18ADC (U+18ADC): L&lt;&lt;746.0,629.0&gt;--&lt;747.0,464.0&gt;&gt;

* u18AE6 (U+18AE6): L&lt;&lt;724.0,152.0&gt;--&lt;725.0,0.0&gt;&gt;

* u18AE7 (U+18AE7): L&lt;&lt;915.0,222.0&gt;--&lt;916.0,5.0&gt;&gt;

* u18AEB (U+18AEB): L&lt;&lt;904.0,205.0&gt;--&lt;905.0,5.0&gt;&gt;

* u18AEF (U+18AEF): L&lt;&lt;914.0,154.0&gt;--&lt;915.0,0.0&gt;&gt;

* u18AF4 (U+18AF4): L&lt;&lt;708.0,125.0&gt;--&lt;709.0,-2.0&gt;&gt;

* u18AF5 (U+18AF5): L&lt;&lt;758.0,181.0&gt;--&lt;759.0,-3.0&gt;&gt;

* u18AF6 (U+18AF6): L&lt;&lt;740.0,218.0&gt;--&lt;741.0,-2.0&gt;&gt;

* u18AF8 (U+18AF8): L&lt;&lt;792.0,197.0&gt;--&lt;793.0,-3.0&gt;&gt;

* u18D01 (U+18D01): L&lt;&lt;840.0,225.0&gt;--&lt;841.0,5.0&gt;&gt;

* u1F6D4 (U+1F6D4): L&lt;&lt;602.0,544.0&gt;--&lt;406.0,543.0&gt;&gt;

* u1F6D4 (U+1F6D4): L&lt;&lt;607.0,464.0&gt;--&lt;402.0,463.0&gt;&gt;

* u1F6D4 (U+1F6D4): L&lt;&lt;611.0,376.0&gt;--&lt;396.0,375.0&gt;&gt;

* u1F6D4 (U+1F6D4): L&lt;&lt;616.0,293.0&gt;--&lt;392.0,292.0&gt;&gt;

* u1F6D4 (U+1F6D4): L&lt;&lt;621.0,198.0&gt;--&lt;386.0,197.0&gt;&gt;

* u1F6D4 (U+1F6D4): L&lt;&lt;625.0,111.0&gt;--&lt;381.0,110.0&gt;&gt;
</code></pre>
 [code: found-semi-vertical]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Ensure files are not too large. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>Font file is 5.4Mb; ideally it should be less than 1.0Mb</p>
 [code: large-font]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.meta.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>This font file does not have a 'meta' table.</p>
 [code: lacks-meta-table]



</div>
</details>
</div>
</details>




### Summary

| 💥 ERROR | ☠ FATAL | 🔥 FAIL | ⚠️ WARN | ⏩ SKIP | ℹ️ INFO | ✅ PASS | 🔎 DEBUG | 
| ---|---|---|---|---|---|---|---|
| 0 | 0 | 3 | 11 | 117 | 6 | 114 | 0 | 
| 0% | 0% | 1% | 4% | 47% | 2% | 45% | 0% | 



**Note:** The following loglevels were omitted in this report:


* SKIP
* INFO
* PASS
* DEBUG
