## Fontbakery report

Fontbakery version: 0.8.11b0

<details><summary><b>[11] NotoSerifTangut-Regular.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Noto fonts must have an ARTICLE.en_us.html file (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/description/noto_has_article">com.google.fonts/check/description/noto_has_article</a>)</summary><div>


* 🔥 **FAIL** This is a Noto font but it lacks an ARTICLE.en_us.html file [code: missing-article]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinAscent value should be equal or greater than 979, but got 856 instead [code: ascent]
* 🔥 **FAIL** OS/2.usWinDescent value should be equal or greater than 240, but got 150 instead. [code: descent]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure files are not too large. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/file_size">com.google.fonts/check/file_size</a>)</summary><div>


* ⚠ **WARN** Font file is 5.4Mb; ideally it should be less than 1.0Mb [code: large-font]
</div></details><details><summary>⚠ <b>WARN:</b> Glyphs are similiar to Google Fonts version? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/production_glyphs_similarity">com.google.fonts/check/production_glyphs_similarity</a>)</summary><div>


* ⚠ **WARN** Following glyphs differ greatly from Google Fonts version:
	* .notdef
	* u17000
	* u17001
	* u17004
	* u17008
	* u1700B
	* u1700D
	* u17013
	* u17014
	* u1701A and 4106 more.

Use -F or --full-lists to disable shortening of long lists.
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- glyph1 

	- glyph2
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2 

	- Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure dotted circle glyph is present and can attach marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/dotted_circle">com.google.fonts/check/dotted_circle</a>)</summary><div>


* ⚠ **WARN** No dotted circle glyph present [code: missing-dotted-circle]
</div></details><details><summary>⚠ <b>WARN:</b> Check math signs have the same width. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/math_signs_width">com.google.fonts/check/math_signs_width</a>)</summary><div>


* ⚠ **WARN** The most common width is 559 among a set of 6 math glyphs.
The following math glyphs have a different width, though:

Width = 310:
minus
 [code: width-outliers]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* u17013 (U+17013): L<<508.0,544.0>--<247.0,478.0>>/L<<247.0,478.0>--<542.0,478.0>> = 14.191096549023982

	* u170B3 (U+170B3): L<<322.0,103.0>--<597.0,165.0>>/L<<597.0,165.0>--<332.0,165.0>> = 12.705169690097586

	* u170B3 (U+170B3): L<<742.0,161.0>--<421.0,81.0>>/L<<421.0,81.0>--<700.0,81.0>> = 13.994237771997035

	* u170F1 (U+170F1): L<<276.0,-26.0>--<276.0,381.0>>/B<<276.0,381.0>-<242.0,207.0>-<236.0,158.0>> = 11.056412980248197

	* u170F2 (U+170F2): L<<273.0,-34.0>--<273.0,384.0>>/B<<273.0,384.0>-<241.0,240.0>-<227.0,157.0>> = 12.528807709151492

	* u170F5 (U+170F5): L<<313.0,-75.0>--<313.0,447.0>>/B<<313.0,447.0>-<257.0,223.0>-<245.0,159.0>> = 14.036243467926484

	* u17105 (U+17105): B<<337.0,492.0>-<257.0,354.0>-<164.0,274.0>>/L<<164.0,274.0>--<172.0,278.0>> = 14.137562158980275

	* u17114 (U+17114): B<<273.0,168.0>-<211.0,98.0>-<134.0,57.0>>/L<<134.0,57.0>--<136.0,58.0>> = 1.4688007143857

	* u17171 (U+17171): B<<545.0,120.0>-<488.0,70.0>-<418.0,41.0>>/L<<418.0,41.0>--<429.0,45.0>> = 2.52042197786743

	* u1717D (U+1717D): B<<549.0,183.0>-<484.0,100.0>-<410.0,51.0>>/L<<410.0,51.0>--<415.0,53.0>> = 11.709609311488988 

	* 137 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-jaggy-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

	* u17000 (U+17000): L<<871.0,218.0>--<872.0,-2.0>>

	* u17004 (U+17004): L<<581.0,-1.0>--<578.0,682.0>>

	* u17004 (U+17004): L<<645.0,642.0>--<647.0,291.0>>

	* u17004 (U+17004): L<<647.0,269.0>--<648.0,14.0>>

	* u17005 (U+17005): L<<891.0,218.0>--<892.0,-2.0>>

	* u17006 (U+17006): L<<871.0,202.0>--<872.0,-2.0>>

	* u17007 (U+17007): L<<899.0,169.0>--<900.0,-1.0>>

	* u17008 (U+17008): L<<860.0,206.0>--<861.0,-2.0>>

	* u17009 (U+17009): L<<871.0,202.0>--<872.0,-2.0>>

	* u1700B (U+1700B): L<<886.0,223.0>--<887.0,-2.0>> 

	* 2089 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-semi-vertical]
</div></details><br></div></details>

### Summary

| 💔 ERROR | 🔥 FAIL | ⚠ WARN | 💤 SKIP | ℹ INFO | 🍞 PASS | 🔎 DEBUG |
|:-----:|:----:|:----:|:----:|:----:|:----:|:----:|
| 0 | 2 | 9 | 117 | 7 | 105 | 0 |
| 0% | 1% | 4% | 49% | 3% | 44% | 0% |

**Note:** The following loglevels were omitted in this report:
* **SKIP**
* **INFO**
* **PASS**
* **DEBUG**
