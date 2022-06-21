## Fontbakery report

Fontbakery version: 0.8.9

<details><summary><b>[14] NotoSerifTangut-Regular.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* 🔥 **FAIL** Missing required codepoints:

	- 0x00AF (MACRON)
 [code: missing-codepoints]
</div></details><details><summary>🔥 <b>FAIL:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* 🔥 **FAIL** License file OFL.txt exists but NameID 13 (LICENSE DESCRIPTION) value on platform 3 (WINDOWS) is not specified for that. Value was: "This Font Software is licensed under the SIL Open Font License, Version 1.1. This Font Software is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the SIL Open Font License for the specific language, permissions and limitations governing your use of this Font Software." Must be changed to "This Font Software is licensed under the SIL Open Font License, Version 1.1. This license is available with a FAQ at: https://scripts.sil.org/OFL" [code: wrong]
</div></details><details><summary>🔥 <b>FAIL:</b> Check if the vertical metrics of a CJK family are similar to the same family hosted on Google Fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/cjk_vertical_metrics_regressions">com.google.fonts/check/cjk_vertical_metrics_regressions</a>)</summary><div>


* 🔥 **FAIL**  OS/2 sTypoAscender is 836 when it should be 856 [code: cjk-metric-regression]
* 🔥 **FAIL**  OS/2 sTypoDescender is -146 when it should be -150 [code: cjk-metric-regression]
* 🔥 **FAIL**  OS/2 usWinAscent is 836 when it should be 856 [code: cjk-metric-regression]
* 🔥 **FAIL**  OS/2 usWinDescent is 146 when it should be 150 [code: cjk-metric-regression]
* 🔥 **FAIL**  hhea ascent is 836 when it should be 856 [code: cjk-metric-regression]
* 🔥 **FAIL**  hhea descent is -146 when it should be -150 [code: cjk-metric-regression]
</div></details><details><summary>⚠ <b>WARN:</b> Description strings in the name table must not exceed 200 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/description_max_length">com.google.fonts/check/name/description_max_length</a>)</summary><div>


* ⚠ **WARN** A few name table entries with ID=10 (NameID.DESCRIPTION) are longer than 200 characters. Please check whether those entries are copyright notices mistakenly stored in the description string entries by a bug in an old FontLab version. If that's the case, then such copyright notices must be removed from these entries. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure files are not too large. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/file_size">com.google.fonts/check/file_size</a>)</summary><div>


* ⚠ **WARN** Font file is 3.0Mb; ideally it should be less than 1.0Mb [code: large-font]
</div></details><details><summary>⚠ <b>WARN:</b> Glyphs are similiar to Google Fonts version? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/production_glyphs_similarity">com.google.fonts/check/production_glyphs_similarity</a>)</summary><div>


* ⚠ **WARN** Following glyphs differ greatly from Google Fonts version:
	* u183E1
	* u17FEF
	* u178FB
	* u17AE9
	* u1797A
	* u17A70
	* u17B2A
	* u17C61
	* u17D9B
	* u188C0 and 4106 more.

Use -F or --full-lists to disable shortening of long lists.
</div></details><details><summary>⚠ <b>WARN:</b> Does the font contain less than 40 CJK characters? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/cjk_not_enough_glyphs">com.google.fonts/check/cjk_not_enough_glyphs</a>)</summary><div>


* ⚠ **WARN** There are only 18 CJK glyphs when there needs to be at least 40 in order to support the smallest CJK writing system, Hangul.
The following CJK glyphs were found:
['uni2FF0', 'uni2FF1', 'uni2FF2', 'uni2FF3', 'uni2FF4', 'uni2FF5', 'uni2FF6', 'uni2FF7', 'uni2FF8', 'uni2FF9', 'uni2FFA', 'uni2FFB', 'uni4E00', 'uni4F53', 'uni590F', 'uni5B8B', 'uni897F', 'uni9AD4']
Please check that these glyphs have the correct unicodes. [code: cjk-not-enough-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- glyph1 

	- And glyph2
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2 

	- And Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Does the font contain chws and vchw features? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/cjk_chws_feature">com.google.fonts/check/cjk_chws_feature</a>)</summary><div>


* ⚠ **WARN** chws feature not found in font. Use chws_tool (https://github.com/googlefonts/chws_tool) to add it. [code: missing-chws-feature]
* ⚠ **WARN** vchw feature not found in font. Use chws_tool (https://github.com/googlefonts/chws_tool) to add it. [code: missing-vchw-feature]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure dotted circle glyph is present and can attach marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/dotted_circle">com.google.fonts/check/dotted_circle</a>)</summary><div>


* ⚠ **WARN** No dotted circle glyph present [code: missing-dotted-circle]
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

	* And 137 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-jaggy-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

	* M (U+004D): L<<139.0,47.0>--<140.0,666.0>>

	* M (U+004D): L<<721.0,326.0>--<722.0,620.0>>

	* N (U+004E): L<<134.0,47.0>--<135.0,656.0>>

	* N (U+004E): L<<179.0,595.0>--<180.0,48.0>>

	* N (U+004E): L<<603.0,146.0>--<602.0,664.0>>

	* Nacute (U+0143): L<<134.0,47.0>--<135.0,656.0>>

	* Nacute (U+0143): L<<179.0,595.0>--<180.0,48.0>>

	* Nacute (U+0143): L<<603.0,146.0>--<602.0,664.0>>

	* Ncaron (U+0147): L<<134.0,47.0>--<135.0,656.0>>

	* Ncaron (U+0147): L<<179.0,595.0>--<180.0,48.0>> 

	* And 2148 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-semi-vertical]
</div></details><br></div></details>
### Summary

| 💔 ERROR | 🔥 FAIL | ⚠ WARN | 💤 SKIP | ℹ INFO | 🍞 PASS | 🔎 DEBUG |
|:-----:|:----:|:----:|:----:|:----:|:----:|:----:|
| 0 | 3 | 11 | 117 | 8 | 96 | 0 |
| 0% | 1% | 5% | 50% | 3% | 41% | 0% |

**Note:** The following loglevels were omitted in this report:
* **SKIP**
* **INFO**
* **PASS**
* **DEBUG**
