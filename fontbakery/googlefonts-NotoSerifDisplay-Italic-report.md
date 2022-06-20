## Fontbakery report

Fontbakery version: 0.8.9

<details><summary><b>[2] Family checks</b></summary><div><details><summary>🔥 <b>FAIL:</b> Ensure Italic styles have Roman counterparts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/family/italics_have_roman_counterparts">com.google.fonts/check/family/italics_have_roman_counterparts</a>)</summary><div>


* 🔥 **FAIL** Italics missing a Roman counterpart: fonts/NotoSerifDisplay-Italic/googlefonts/slim-variable-ttf/NotoSerifDisplay-ItalicMM[wght].ttf, fonts/NotoSerifDisplay-Italic/googlefonts/ttf/NotoSerifDisplay-BlackItalic.ttf, fonts/NotoSerifDisplay-Italic/googlefonts/ttf/NotoSerifDisplay-BoldItalic.ttf, fonts/NotoSerifDisplay-Italic/googlefonts/ttf/NotoSerifDisplay-ExtraBoldItalic.ttf, fonts/NotoSerifDisplay-Italic/googlefonts/ttf/NotoSerifDisplay-ExtraLightItalic.ttf, fonts/NotoSerifDisplay-Italic/googlefonts/ttf/NotoSerifDisplay-Italic.ttf, fonts/NotoSerifDisplay-Italic/googlefonts/ttf/NotoSerifDisplay-LightItalic.ttf, fonts/NotoSerifDisplay-Italic/googlefonts/ttf/NotoSerifDisplay-MediumItalic.ttf, fonts/NotoSerifDisplay-Italic/googlefonts/ttf/NotoSerifDisplay-SemiBoldItalic.ttf, fonts/NotoSerifDisplay-Italic/googlefonts/ttf/NotoSerifDisplay-ThinItalic.ttf and fonts/NotoSerifDisplay-Italic/googlefonts/variable-ttf/NotoSerifDisplay-ItalicMM[wdth,wght].ttf [code: missing-roman]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking all files are in the same directory. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/single_directory">com.google.fonts/check/family/single_directory</a>)</summary><div>


* 🔥 **FAIL** Not all fonts passed in the command line are in the same directory. This may lead to bad results as the tool will interpret all font files as belonging to a single font family. The detected directories are: ['fonts/NotoSerifDisplay-Italic/googlefonts/slim-variable-ttf', 'fonts/NotoSerifDisplay-Italic/googlefonts/ttf', 'fonts/NotoSerifDisplay-Italic/googlefonts/variable-ttf'] [code: single-directory]
</div></details><br></div></details><details><summary><b>[18] NotoSerifDisplay-ItalicMM[wght].ttf</b></summary><div><details><summary>💔 <b>ERROR:</b> Check if the vertical metrics of a family are similar to the same family hosted on Google Fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vertical_metrics_regressions">com.google.fonts/check/vertical_metrics_regressions</a>)</summary><div>


* 💔 **ERROR** Failed with TypeError: 'NoneType' object is not subscriptable
</div></details><details><summary>🔥 <b>FAIL:</b> Checking file is named canonically. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/canonical_filename">com.google.fonts/check/canonical_filename</a>)</summary><div>


* 🔥 **FAIL** The file 'NotoSerifDisplay-ItalicMM[wght].ttf' must be renamed to 'NotoSerifDisplay-Italic[wdth,wght].ttf' according to the Google Fonts naming policy for variable fonts. [code: bad-varfont-filename]
</div></details><details><summary>🔥 <b>FAIL:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* 🔥 **FAIL** Missing required codepoints:

	- 0x2212 (MINUS SIGN)
 

	- And 0x00AF (MACRON)
 [code: missing-codepoints]
</div></details><details><summary>🔥 <b>FAIL:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* 🔥 **FAIL** License file OFL.txt exists but NameID 13 (LICENSE DESCRIPTION) value on platform 3 (WINDOWS) is not specified for that. Value was: "This Font Software is licensed under the SIL Open Font License, Version 1.1. This Font Software is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the SIL Open Font License for the specific language, permissions and limitations governing your use of this Font Software." Must be changed to "This Font Software is licensed under the SIL Open Font License, Version 1.1. This license is available with a FAQ at: https://scripts.sil.org/OFL" [code: wrong]
</div></details><details><summary>🔥 <b>FAIL:</b> Copyright notices match canonical pattern in fonts (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/font_copyright">com.google.fonts/check/font_copyright</a>)</summary><div>


* 🔥 **FAIL** Name Table entry: Copyright notices should match a pattern similar to: "Copyright 2019 The Familyname Project Authors (git url)"
But instead we have got:
"Copyright 2016-2021 Google Inc. All Rights Reserved." [code: bad-notice-format]
</div></details><details><summary>🔥 <b>FAIL:</b> OS/2.fsSelection bit 7 (USE_TYPO_METRICS) is set in all fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/os2/use_typo_metrics">com.google.fonts/check/os2/use_typo_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2.fsSelection bit 7 (USE_TYPO_METRICS) wasNOT set in the following fonts: ['fonts/NotoSerifDisplay-Italic/googlefonts/slim-variable-ttf/NotoSerifDisplay-ItalicMM[wght].ttf', 'fonts/NotoSerifDisplay-Italic/googlefonts/ttf/NotoSerifDisplay-BlackItalic.ttf', 'fonts/NotoSerifDisplay-Italic/googlefonts/ttf/NotoSerifDisplay-BoldItalic.ttf', 'fonts/NotoSerifDisplay-Italic/googlefonts/ttf/NotoSerifDisplay-ExtraBoldItalic.ttf', 'fonts/NotoSerifDisplay-Italic/googlefonts/ttf/NotoSerifDisplay-ExtraLightItalic.ttf', 'fonts/NotoSerifDisplay-Italic/googlefonts/ttf/NotoSerifDisplay-Italic.ttf', 'fonts/NotoSerifDisplay-Italic/googlefonts/ttf/NotoSerifDisplay-LightItalic.ttf', 'fonts/NotoSerifDisplay-Italic/googlefonts/ttf/NotoSerifDisplay-MediumItalic.ttf', 'fonts/NotoSerifDisplay-Italic/googlefonts/ttf/NotoSerifDisplay-SemiBoldItalic.ttf', 'fonts/NotoSerifDisplay-Italic/googlefonts/ttf/NotoSerifDisplay-ThinItalic.ttf', 'fonts/NotoSerifDisplay-Italic/googlefonts/variable-ttf/NotoSerifDisplay-ItalicMM[wdth,wght].ttf']. [code: missing-os2-fsselection-bit7]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinAscent value should be equal or greater than 1143, but got 1069 instead [code: ascent]
* 🔥 **FAIL** OS/2.usWinDescent value should be equal or greater than 470, but got 293 instead. [code: descent]
</div></details><details><summary>🔥 <b>FAIL:</b> The variable font 'wght' (Weight) axis coordinate must be 400 on the 'Regular' instance. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/fvar.html#com.google.fonts/check/varfont/regular_wght_coord">com.google.fonts/check/varfont/regular_wght_coord</a>)</summary><div>


* 🔥 **FAIL** The "wght" axis coordinate of the "Regular" instance must be 400. Got None instead. [code: wght-not-400]
</div></details><details><summary>🔥 <b>FAIL:</b> The variable font 'wdth' (Width) axis coordinate must be 100 on the 'Regular' instance. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/fvar.html#com.google.fonts/check/varfont/regular_wdth_coord">com.google.fonts/check/varfont/regular_wdth_coord</a>)</summary><div>


* 🔥 **FAIL** The "wdth" axis coordinate of the "Regular" instance must be 100. Got None as a default value instead. [code: wdth-not-100]
</div></details><details><summary>🔥 <b>FAIL:</b> The variable font 'wght' (Weight) axis coordinate must be 700 on the 'Bold' instance. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/fvar.html#com.google.fonts/check/varfont/bold_wght_coord">com.google.fonts/check/varfont/bold_wght_coord</a>)</summary><div>


* 🔥 **FAIL** The "wght" axis coordinate of the "Bold" instance must be 700. Got None instead. [code: wght-not-700]
</div></details><details><summary>🔥 <b>FAIL:</b> Validates that when an instance record is included for the default instance, its subfamilyNameID value is set to either 2 or 17, and its postScriptNameID value is set to 6. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/fvar.html#com.adobe.fonts/check/varfont/valid_default_instance_nameids">com.adobe.fonts/check/varfont/valid_default_instance_nameids</a>)</summary><div>


* 🔥 **FAIL** 'Italic' instance has the same coordinates as the default instance; its subfamilyNameID should be either 2 or 17, instead of 293. [code: invalid-default-instance-subfamily-nameid:293]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure files are not too large. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/file_size">com.google.fonts/check/file_size</a>)</summary><div>


* ⚠ **WARN** Font file is 1.7Mb; ideally it should be less than 1.0Mb [code: large-font]
</div></details><details><summary>⚠ <b>WARN:</b> Is there kerning info for non-ligated sequences? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/kerning_for_non_ligated_sequences">com.google.fonts/check/kerning_for_non_ligated_sequences</a>)</summary><div>


* ⚠ **WARN** GPOS table lacks kerning info for the following non-ligated sequences:

	- f + f

	- f + i

	- i + f

	- f + l

	- l + f

	- i + l

	- f.ss02 + f.ss02

	- f.ss02 + i

	- i + f.ss02

	- f.ss02 + l 

	- And l + f.ss02 [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure Stylistic Sets have description. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/stylisticset_description">com.google.fonts/check/stylisticset_description</a>)</summary><div>


* ⚠ **WARN** The stylistic set ss01 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss02 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss03 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss06 lacks a description string on the 'name' table. [code: missing-description]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Glyph names are all valid? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/valid_glyphnames">com.google.fonts/check/valid_glyphnames</a>)</summary><div>


* ⚠ **WARN** The following glyph names may be too long for some legacy systems which may expect a maximum 31-char length limit:
kavykawithkavykaaboveinvertedlow [code: legacy-long-names]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- uni1FCE0306

	- dasiavaria_macronmod

	- uni1FCD0306

	- uni03B1030603140301

	- uni1FCE02C9

	- dasiaoxia_macronmod

	- beta.alt1

	- uni03B9030803040300

	- uni03C5030603140301

	- uni03C5030603130301 

	- And 35 more.

Use -F or --full-lists to disable shortening of long lists.
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check mark characters are in GDEF mark glyph class. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_mark_chars">com.google.fonts/check/gdef_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following mark characters could be in the GDEF mark glyph class:
	 uni0488 (U+0488), uni0489 (U+0489), uni1ABE (U+1ABE), uniA670 (U+A670), uniA671 (U+A671) and uniA672 (U+A672) [code: mark-chars]
</div></details><br></div></details><details><summary><b>[17] NotoSerifDisplay-BlackItalic.ttf</b></summary><div><details><summary>💔 <b>ERROR:</b> Check if the vertical metrics of a family are similar to the same family hosted on Google Fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vertical_metrics_regressions">com.google.fonts/check/vertical_metrics_regressions</a>)</summary><div>


* 💔 **ERROR** Failed with TypeError: 'NoneType' object is not subscriptable
</div></details><details><summary>🔥 <b>FAIL:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* 🔥 **FAIL** Missing required codepoints:

	- 0x2212 (MINUS SIGN)
 

	- And 0x00AF (MACRON)
 [code: missing-codepoints]
</div></details><details><summary>🔥 <b>FAIL:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* 🔥 **FAIL** License file OFL.txt exists but NameID 13 (LICENSE DESCRIPTION) value on platform 3 (WINDOWS) is not specified for that. Value was: "This Font Software is licensed under the SIL Open Font License, Version 1.1. This Font Software is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the SIL Open Font License for the specific language, permissions and limitations governing your use of this Font Software." Must be changed to "This Font Software is licensed under the SIL Open Font License, Version 1.1. This license is available with a FAQ at: https://scripts.sil.org/OFL" [code: wrong]
</div></details><details><summary>🔥 <b>FAIL:</b> Copyright notices match canonical pattern in fonts (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/font_copyright">com.google.fonts/check/font_copyright</a>)</summary><div>


* 🔥 **FAIL** Name Table entry: Copyright notices should match a pattern similar to: "Copyright 2019 The Familyname Project Authors (git url)"
But instead we have got:
"Copyright 2016-2021 Google Inc. All Rights Reserved." [code: bad-notice-format]
</div></details><details><summary>🔥 <b>FAIL:</b> OS/2.fsSelection bit 7 (USE_TYPO_METRICS) is set in all fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/os2/use_typo_metrics">com.google.fonts/check/os2/use_typo_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2.fsSelection bit 7 (USE_TYPO_METRICS) wasNOT set in the following fonts: ['fonts/NotoSerifDisplay-Italic/googlefonts/slim-variable-ttf/NotoSerifDisplay-ItalicMM[wght].ttf', 'fonts/NotoSerifDisplay-Italic/googlefonts/ttf/NotoSerifDisplay-BlackItalic.ttf', 'fonts/NotoSerifDisplay-Italic/googlefonts/ttf/NotoSerifDisplay-BoldItalic.ttf', 'fonts/NotoSerifDisplay-Italic/googlefonts/ttf/NotoSerifDisplay-ExtraBoldItalic.ttf', 'fonts/NotoSerifDisplay-Italic/googlefonts/ttf/NotoSerifDisplay-ExtraLightItalic.ttf', 'fonts/NotoSerifDisplay-Italic/googlefonts/ttf/NotoSerifDisplay-Italic.ttf', 'fonts/NotoSerifDisplay-Italic/googlefonts/ttf/NotoSerifDisplay-LightItalic.ttf', 'fonts/NotoSerifDisplay-Italic/googlefonts/ttf/NotoSerifDisplay-MediumItalic.ttf', 'fonts/NotoSerifDisplay-Italic/googlefonts/ttf/NotoSerifDisplay-SemiBoldItalic.ttf', 'fonts/NotoSerifDisplay-Italic/googlefonts/ttf/NotoSerifDisplay-ThinItalic.ttf', 'fonts/NotoSerifDisplay-Italic/googlefonts/variable-ttf/NotoSerifDisplay-ItalicMM[wdth,wght].ttf']. [code: missing-os2-fsselection-bit7]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinAscent value should be equal or greater than 1143, but got 1069 instead [code: ascent]
* 🔥 **FAIL** OS/2.usWinDescent value should be equal or greater than 470, but got 293 instead. [code: descent]
</div></details><details><summary>⚠ <b>WARN:</b> Glyphs are similiar to Google Fonts version? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/production_glyphs_similarity">com.google.fonts/check/production_glyphs_similarity</a>)</summary><div>


* ⚠ **WARN** Following glyphs differ greatly from Google Fonts version:
	* pi
	* uni1F57
	* uni0424
	* uni1F42
	* uni1F3B
	* uni1FCE
	* four.lf
	* uni0278
	* uni1F6A
	* uni0345 and 220 more.

Use -F or --full-lists to disable shortening of long lists.
</div></details><details><summary>⚠ <b>WARN:</b> Is there kerning info for non-ligated sequences? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/kerning_for_non_ligated_sequences">com.google.fonts/check/kerning_for_non_ligated_sequences</a>)</summary><div>


* ⚠ **WARN** GPOS table lacks kerning info for the following non-ligated sequences:

	- f + f

	- f + i

	- i + f

	- f + l

	- l + f

	- i + l

	- f.ss02 + f.ss02

	- f.ss02 + i

	- i + f.ss02

	- f.ss02 + l 

	- And l + f.ss02 [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Noto Serif Display Black' / SUBFAMILY_NAME = 'Italic'

Please take a look at the conversation at https://github.com/googlefonts/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure Stylistic Sets have description. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/stylisticset_description">com.google.fonts/check/stylisticset_description</a>)</summary><div>


* ⚠ **WARN** The stylistic set ss01 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss02 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss03 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss06 lacks a description string on the 'name' table. [code: missing-description]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Glyph names are all valid? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/valid_glyphnames">com.google.fonts/check/valid_glyphnames</a>)</summary><div>


* ⚠ **WARN** The following glyph names may be too long for some legacy systems which may expect a maximum 31-char length limit:
kavykawithkavykaaboveinvertedlow [code: legacy-long-names]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- uni1FCE0306

	- dasiavaria_macronmod

	- uni1FCD0306

	- uni03B1030603140301

	- uni1FCE02C9

	- dasiaoxia_macronmod

	- beta.alt1

	- uni03B9030803040300

	- uni03C5030603140301

	- uni03C5030603130301 

	- And 35 more.

Use -F or --full-lists to disable shortening of long lists.
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character (codepoint 0x00AD) which is supposed to be zero-width and invisible, and is used to mark a hyphenation possibility within a word in the absence of or overriding dictionary hyphenation. It is mostly an obsolete mechanism now, and the character is only included in fonts for legacy codepage coverage. [code: softhyphen]
* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: uni00AD	Contours detected: 1	Expected: 0

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: eogonek	Contours detected: 3	Expected: 2

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uni0193	Contours detected: 2	Expected: 1

	- Glyph name: uni01E5	Contours detected: 3	Expected: 2

	- Glyph name: uni01EA	Contours detected: 3	Expected: 2

	- Glyph name: uni01EB	Contours detected: 3	Expected: 2

	- Glyph name: uni01EC	Contours detected: 4	Expected: 3 

	- And 43 more.

Use -F or --full-lists to disable shortening of long lists.
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check mark characters are in GDEF mark glyph class. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_mark_chars">com.google.fonts/check/gdef_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following mark characters could be in the GDEF mark glyph class:
	 uni0488 (U+0488), uni0489 (U+0489), uni1ABE (U+1ABE), uniA670 (U+A670), uniA671 (U+A671) and uniA672 (U+A672) [code: mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* Zpalatalhook (U+A7C6): L<<654.0,229.0>--<602.0,0.0>> -> L<<602.0,0.0>--<596.0,-26.0>>

	* beta (U+03B2): L<<-30.0,-220.0>--<40.0,100.0>> -> L<<40.0,100.0>--<118.0,494.0>>

	* rho (U+03C1): L<<-44.0,-221.0>--<15.0,53.0>> -> L<<15.0,53.0>--<59.0,263.0>>

	* uni024D (U+024D): L<<285.0,288.0>--<284.0,282.0>> -> L<<284.0,282.0>--<221.0,0.0>>

	* uni03BC (U+03BC): L<<-31.0,-221.0>--<65.0,225.0>> -> L<<65.0,225.0>--<127.0,536.0>>

	* uni03FC (U+03FC): L<<-14.0,-82.0>--<15.0,53.0>> -> L<<15.0,53.0>--<59.0,263.0>>

	* uni04CA (U+04CA): L<<467.0,-210.0>--<686.0,46.0>> -> L<<686.0,46.0>--<687.0,47.0>>

	* uni1D0B (U+1D0B): L<<353.0,496.0>--<305.0,292.0>> -> L<<305.0,292.0>--<298.0,265.0>>

	* uni1D5D (U+1D5D): L<<21.0,155.0>--<66.0,347.0>> -> L<<66.0,347.0>--<117.0,583.0>>

	* uni1D66 (U+1D66): L<<-60.0,-228.0>--<-15.0,-36.0>> -> L<<-15.0,-36.0>--<36.0,200.0>> 

	* And 4 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* Bbarredmod (U+1D2F): B<<456.5,554.5>-<425.0,525.0>-<351.0,517.0>>/L<<351.0,517.0>--<505.0,517.0>> = 6.1701750950295855

	* Bbarredmod (U+1D2F): L<<504.0,510.0>--<345.0,510.0>>/B<<345.0,510.0>-<461.0,495.0>-<461.0,411.0>> = 7.368051071622163

	* Bbarredsmall (U+1D03): B<<563.0,330.0>-<525.0,300.0>-<461.0,289.0>>/L<<461.0,289.0>--<615.0,289.0>> = 9.752424941653764

	* Bbarredsmall (U+1D03): L<<613.0,279.0>--<432.0,279.0>>/B<<432.0,279.0>-<497.0,270.0>-<531.5,245.5>> = 7.883139316729715

	* Emsoftcy (U+A666): L<<614.0,70.0>--<742.0,689.0>>/L<<742.0,689.0>--<409.0,0.0>> = 14.111655477268902

	* Ereversedopen (U+A7AB): B<<506.5,407.0>-<440.0,383.0>-<328.0,373.0>>/B<<328.0,373.0>-<455.0,366.0>-<519.5,329.5>> = 8.25700811715012

	* cpalatalhook (U+A794): B<<445.5,74.5>-<464.0,106.0>-<481.0,144.0>>/L<<481.0,144.0>--<443.0,-44.0>> = 12.675132907215996

	* iotifiedbigyuscombcy (U+2DFF): B<<31.5,681.5>-<42.0,690.0>-<65.0,693.0>>/L<<65.0,693.0>--<-55.0,693.0>> = 7.431407971172489

	* lambda (U+03BB): L<<398.0,101.0>--<364.0,355.0>>/L<<364.0,355.0>--<364.0,353.0>> = 7.624192504451797

	* sigma (U+03C3): L<<645.0,401.0>--<420.0,401.0>>/B<<420.0,401.0>-<467.0,396.0>-<509.0,373.0>> = 6.0724564072076905 

	* And 58 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-jaggy-segments]
</div></details><br></div></details><details><summary><b>[24] NotoSerifDisplay-BoldItalic.ttf</b></summary><div><details><summary>💔 <b>ERROR:</b> Check if the vertical metrics of a family are similar to the same family hosted on Google Fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vertical_metrics_regressions">com.google.fonts/check/vertical_metrics_regressions</a>)</summary><div>


* 💔 **ERROR** Failed with TypeError: 'NoneType' object is not subscriptable
</div></details><details><summary>🔥 <b>FAIL:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* 🔥 **FAIL** Missing required codepoints:

	- 0x2212 (MINUS SIGN)
 

	- And 0x00AF (MACRON)
 [code: missing-codepoints]
</div></details><details><summary>🔥 <b>FAIL:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* 🔥 **FAIL** License file OFL.txt exists but NameID 13 (LICENSE DESCRIPTION) value on platform 3 (WINDOWS) is not specified for that. Value was: "This Font Software is licensed under the SIL Open Font License, Version 1.1. This Font Software is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the SIL Open Font License for the specific language, permissions and limitations governing your use of this Font Software." Must be changed to "This Font Software is licensed under the SIL Open Font License, Version 1.1. This license is available with a FAQ at: https://scripts.sil.org/OFL" [code: wrong]
</div></details><details><summary>🔥 <b>FAIL:</b> Is the Grid-fitting and Scan-conversion Procedure ('gasp') table set to optimize rendering? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/gasp">com.google.fonts/check/gasp</a>)</summary><div>


* 🔥 **FAIL** Font is missing the 'gasp' table. Try exporting the font with autohinting enabled.
If you are dealing with an unhinted font, it can be fixed by running the fonts through the command 'gftools fix-nonhinting'
GFTools is available at https://pypi.org/project/gftools/ [code: lacks-gasp]
</div></details><details><summary>🔥 <b>FAIL:</b> Copyright notices match canonical pattern in fonts (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/font_copyright">com.google.fonts/check/font_copyright</a>)</summary><div>


* 🔥 **FAIL** Name Table entry: Copyright notices should match a pattern similar to: "Copyright 2019 The Familyname Project Authors (git url)"
But instead we have got:
"Copyright 2016-2021 Google Inc. All Rights Reserved." [code: bad-notice-format]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 fsSelection value. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/fsselection">com.google.fonts/check/fsselection</a>)</summary><div>


* 🔥 **FAIL** OS/2 fsSelection REGULAR bit should be unset. [code: bad-REGULAR]
* 🔥 **FAIL** OS/2 fsSelection ITALIC bit should be set. [code: bad-ITALIC]
* 🔥 **FAIL** OS/2 fsSelection BOLD bit should be set. [code: bad-BOLD]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking head.macStyle value. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/mac_style">com.google.fonts/check/mac_style</a>)</summary><div>


* 🔥 **FAIL** head macStyle ITALIC bit should be set. [code: bad-ITALIC]
* 🔥 **FAIL** head macStyle BOLD bit should be set. [code: bad-BOLD]
</div></details><details><summary>🔥 <b>FAIL:</b> Check name table: FONT_FAMILY_NAME entries. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/familyname">com.google.fonts/check/name/familyname</a>)</summary><div>


* 🔥 **FAIL** Entry [FONT_FAMILY_NAME(1):WINDOWS(3)] on the "name" table: Expected "Noto Serif Display" but got "Noto Serif Display Bold Italic". [code: mismatch]
</div></details><details><summary>🔥 <b>FAIL:</b> Check name table: FONT_SUBFAMILY_NAME entries. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/subfamilyname">com.google.fonts/check/name/subfamilyname</a>)</summary><div>


* 🔥 **FAIL** SUBFAMILY_NAME for Win "Regular" must be "Bold Italic" [code: bad-familyname]
</div></details><details><summary>🔥 <b>FAIL:</b> Check name table: TYPOGRAPHIC_FAMILY_NAME entries. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/typographicfamilyname">com.google.fonts/check/name/typographicfamilyname</a>)</summary><div>


* 🔥 **FAIL** Font style is "BoldItalic" and, for that reason, it is not expected to have a [TYPOGRAPHIC_FAMILY_NAME(16):WINDOWS(3)] entry! [code: ribbi]
</div></details><details><summary>🔥 <b>FAIL:</b> Font enables smart dropout control in "prep" table instructions? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/smart_dropout">com.google.fonts/check/smart_dropout</a>)</summary><div>


* 🔥 **FAIL** The 'prep' table does not contain TrueType instructions enabling smart dropout control. To fix, export the font with autohinting enabled, or run ttfautohint on the font, or run the `gftools fix-nonhinting` script. [code: lacks-smart-dropout]
</div></details><details><summary>🔥 <b>FAIL:</b> OS/2.fsSelection bit 7 (USE_TYPO_METRICS) is set in all fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/os2/use_typo_metrics">com.google.fonts/check/os2/use_typo_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2.fsSelection bit 7 (USE_TYPO_METRICS) wasNOT set in the following fonts: ['fonts/NotoSerifDisplay-Italic/googlefonts/slim-variable-ttf/NotoSerifDisplay-ItalicMM[wght].ttf', 'fonts/NotoSerifDisplay-Italic/googlefonts/ttf/NotoSerifDisplay-BlackItalic.ttf', 'fonts/NotoSerifDisplay-Italic/googlefonts/ttf/NotoSerifDisplay-BoldItalic.ttf', 'fonts/NotoSerifDisplay-Italic/googlefonts/ttf/NotoSerifDisplay-ExtraBoldItalic.ttf', 'fonts/NotoSerifDisplay-Italic/googlefonts/ttf/NotoSerifDisplay-ExtraLightItalic.ttf', 'fonts/NotoSerifDisplay-Italic/googlefonts/ttf/NotoSerifDisplay-Italic.ttf', 'fonts/NotoSerifDisplay-Italic/googlefonts/ttf/NotoSerifDisplay-LightItalic.ttf', 'fonts/NotoSerifDisplay-Italic/googlefonts/ttf/NotoSerifDisplay-MediumItalic.ttf', 'fonts/NotoSerifDisplay-Italic/googlefonts/ttf/NotoSerifDisplay-SemiBoldItalic.ttf', 'fonts/NotoSerifDisplay-Italic/googlefonts/ttf/NotoSerifDisplay-ThinItalic.ttf', 'fonts/NotoSerifDisplay-Italic/googlefonts/variable-ttf/NotoSerifDisplay-ItalicMM[wdth,wght].ttf']. [code: missing-os2-fsselection-bit7]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinAscent value should be equal or greater than 1143, but got 1069 instead [code: ascent]
* 🔥 **FAIL** OS/2.usWinDescent value should be equal or greater than 470, but got 293 instead. [code: descent]
</div></details><details><summary>⚠ <b>WARN:</b> Glyphs are similiar to Google Fonts version? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/production_glyphs_similarity">com.google.fonts/check/production_glyphs_similarity</a>)</summary><div>


* ⚠ **WARN** Following glyphs differ greatly from Google Fonts version:
	* pi
	* uni1F57
	* uni1F3B
	* four.lf
	* uni0278
	* uni1F6A
	* uni0345
	* uni1F62
	* uni1FE0
	* uni1F92 and 191 more.

Use -F or --full-lists to disable shortening of long lists.
</div></details><details><summary>⚠ <b>WARN:</b> Is there kerning info for non-ligated sequences? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/kerning_for_non_ligated_sequences">com.google.fonts/check/kerning_for_non_ligated_sequences</a>)</summary><div>


* ⚠ **WARN** GPOS table lacks kerning info for the following non-ligated sequences:

	- f + f

	- f + i

	- i + f

	- f + l

	- l + f

	- i + l

	- f.ss02 + f.ss02

	- f.ss02 + i

	- i + f.ss02

	- f.ss02 + l 

	- And l + f.ss02 [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Noto Serif Display Bold Italic' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/googlefonts/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure Stylistic Sets have description. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/stylisticset_description">com.google.fonts/check/stylisticset_description</a>)</summary><div>


* ⚠ **WARN** The stylistic set ss01 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss02 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss03 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss06 lacks a description string on the 'name' table. [code: missing-description]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Glyph names are all valid? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/valid_glyphnames">com.google.fonts/check/valid_glyphnames</a>)</summary><div>


* ⚠ **WARN** The following glyph names may be too long for some legacy systems which may expect a maximum 31-char length limit:
kavykawithkavykaaboveinvertedlow [code: legacy-long-names]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- uni1FCE0306

	- dasiavaria_macronmod

	- uni1FCD0306

	- uni03B1030603140301

	- uni1FCE02C9

	- dasiaoxia_macronmod

	- beta.alt1

	- uni03B9030803040300

	- uni03C5030603140301

	- uni03C5030603130301 

	- And 35 more.

Use -F or --full-lists to disable shortening of long lists.
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character (codepoint 0x00AD) which is supposed to be zero-width and invisible, and is used to mark a hyphenation possibility within a word in the absence of or overriding dictionary hyphenation. It is mostly an obsolete mechanism now, and the character is only included in fonts for legacy codepage coverage. [code: softhyphen]
* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: uni00AD	Contours detected: 1	Expected: 0

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: eogonek	Contours detected: 3	Expected: 2

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uni01E5	Contours detected: 3	Expected: 2

	- Glyph name: uni01EA	Contours detected: 3	Expected: 2

	- Glyph name: uni01EB	Contours detected: 3	Expected: 2

	- Glyph name: uni01EC	Contours detected: 4	Expected: 3

	- Glyph name: uni01ED	Contours detected: 4	Expected: 3 

	- And 39 more.

Use -F or --full-lists to disable shortening of long lists.
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check mark characters are in GDEF mark glyph class. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_mark_chars">com.google.fonts/check/gdef_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following mark characters could be in the GDEF mark glyph class:
	 uni0488 (U+0488), uni0489 (U+0489), uni1ABE (U+1ABE), uniA670 (U+A670), uniA671 (U+A671) and uniA672 (U+A672) [code: mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* Zpalatalhook (U+A7C6): L<<610.0,206.0>--<562.0,0.0>> -> L<<562.0,0.0>--<554.0,-32.0>>

	* beta (U+03B2): L<<-37.0,-240.0>--<44.0,126.0>> -> L<<44.0,126.0>--<125.0,527.0>>

	* rho (U+03C1): L<<-48.0,-240.0>--<32.0,122.0>> -> L<<32.0,122.0>--<61.0,263.0>>

	* uni03BC (U+03BC): L<<-34.0,-240.0>--<36.0,75.0>> -> L<<36.0,75.0>--<127.0,536.0>>

	* uni03FC (U+03FC): L<<-13.0,-81.0>--<32.0,122.0>> -> L<<32.0,122.0>--<61.0,263.0>>

	* uni1D0B (U+1D0B): L<<309.0,480.0>--<268.0,299.0>> -> L<<268.0,299.0>--<256.0,244.0>>

	* uni1D5D (U+1D5D): L<<9.0,143.0>--<62.0,363.0>> -> L<<62.0,363.0>--<114.0,603.0>>

	* uni1D66 (U+1D66): L<<-73.0,-240.0>--<-20.0,-20.0>> -> L<<-20.0,-20.0>--<32.0,220.0>>

	* uni1D68 (U+1D68): L<<-83.0,-240.0>--<-31.0,-23.0>> -> L<<-31.0,-23.0>--<-12.0,62.0>>

	* uni1DE9 (U+1DE9): L<<-54.0,586.0>--<-17.0,732.0>> -> L<<-17.0,732.0>--<19.0,893.0>>

	* uni1FE4 (U+1FE4): L<<-48.0,-240.0>--<32.0,122.0>> -> L<<32.0,122.0>--<61.0,263.0>> 

	* And uni1FE5 (U+1FE5): L<<-48.0,-240.0>--<32.0,122.0>> -> L<<32.0,122.0>--<61.0,263.0>> [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* Bbarredmod (U+1D2F): B<<445.5,554.5>-<415.0,528.0>-<359.0,518.0>>/L<<359.0,518.0>--<488.0,518.0>> = 10.124671655397806

	* Bbarredmod (U+1D2F): L<<487.0,508.0>--<355.0,508.0>>/B<<355.0,508.0>-<448.0,492.0>-<448.0,419.0>> = 9.761774775042225

	* Bbarredsmall (U+1D03): B<<515.5,334.0>-<476.0,300.0>-<400.0,288.0>>/L<<400.0,288.0>--<577.0,288.0>> = 8.972626614896358

	* Bbarredsmall (U+1D03): L<<574.0,278.0>--<395.0,278.0>>/B<<395.0,278.0>-<523.0,259.0>-<523.0,166.0>> = 8.443190929176641

	* Ereversedopen (U+A7AB): B<<462.5,405.0>-<398.0,382.0>-<321.0,373.0>>/B<<321.0,373.0>-<434.0,365.0>-<494.5,331.5>> = 10.71624159417269

	* hardsigntallcy (U+1C86): B<<250.5,556.0>-<345.0,646.0>-<472.0,730.0>>/B<<472.0,730.0>-<432.0,715.0>-<394.0,705.5>> = 12.925295435537027

	* iotifiedbigyuscombcy (U+2DFF): B<<33.5,687.0>-<46.0,696.0>-<66.0,699.0>>/L<<66.0,699.0>--<-42.0,699.0>> = 8.530765609948139

	* sigma (U+03C3): L<<610.0,423.0>--<412.0,423.0>>/B<<412.0,423.0>-<456.0,414.0>-<491.0,391.5>> = 11.56013079421777

	* three (U+0033): B<<423.0,405.0>-<360.0,382.0>-<283.0,373.0>>/B<<283.0,373.0>-<396.0,365.0>-<453.5,331.5>> = 10.71624159417269

	* uni0222 (U+0222): B<<118.0,355.0>-<190.0,418.0>-<317.0,431.0>>/B<<317.0,431.0>-<257.0,438.0>-<222.5,459.0>> = 12.498990923393444 

	* And 42 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-jaggy-segments]
</div></details><br></div></details><details><summary><b>[17] NotoSerifDisplay-ExtraBoldItalic.ttf</b></summary><div><details><summary>💔 <b>ERROR:</b> Check if the vertical metrics of a family are similar to the same family hosted on Google Fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vertical_metrics_regressions">com.google.fonts/check/vertical_metrics_regressions</a>)</summary><div>


* 💔 **ERROR** Failed with TypeError: 'NoneType' object is not subscriptable
</div></details><details><summary>🔥 <b>FAIL:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* 🔥 **FAIL** Missing required codepoints:

	- 0x2212 (MINUS SIGN)
 

	- And 0x00AF (MACRON)
 [code: missing-codepoints]
</div></details><details><summary>🔥 <b>FAIL:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* 🔥 **FAIL** License file OFL.txt exists but NameID 13 (LICENSE DESCRIPTION) value on platform 3 (WINDOWS) is not specified for that. Value was: "This Font Software is licensed under the SIL Open Font License, Version 1.1. This Font Software is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the SIL Open Font License for the specific language, permissions and limitations governing your use of this Font Software." Must be changed to "This Font Software is licensed under the SIL Open Font License, Version 1.1. This license is available with a FAQ at: https://scripts.sil.org/OFL" [code: wrong]
</div></details><details><summary>🔥 <b>FAIL:</b> Copyright notices match canonical pattern in fonts (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/font_copyright">com.google.fonts/check/font_copyright</a>)</summary><div>


* 🔥 **FAIL** Name Table entry: Copyright notices should match a pattern similar to: "Copyright 2019 The Familyname Project Authors (git url)"
But instead we have got:
"Copyright 2016-2021 Google Inc. All Rights Reserved." [code: bad-notice-format]
</div></details><details><summary>🔥 <b>FAIL:</b> OS/2.fsSelection bit 7 (USE_TYPO_METRICS) is set in all fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/os2/use_typo_metrics">com.google.fonts/check/os2/use_typo_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2.fsSelection bit 7 (USE_TYPO_METRICS) wasNOT set in the following fonts: ['fonts/NotoSerifDisplay-Italic/googlefonts/slim-variable-ttf/NotoSerifDisplay-ItalicMM[wght].ttf', 'fonts/NotoSerifDisplay-Italic/googlefonts/ttf/NotoSerifDisplay-BlackItalic.ttf', 'fonts/NotoSerifDisplay-Italic/googlefonts/ttf/NotoSerifDisplay-BoldItalic.ttf', 'fonts/NotoSerifDisplay-Italic/googlefonts/ttf/NotoSerifDisplay-ExtraBoldItalic.ttf', 'fonts/NotoSerifDisplay-Italic/googlefonts/ttf/NotoSerifDisplay-ExtraLightItalic.ttf', 'fonts/NotoSerifDisplay-Italic/googlefonts/ttf/NotoSerifDisplay-Italic.ttf', 'fonts/NotoSerifDisplay-Italic/googlefonts/ttf/NotoSerifDisplay-LightItalic.ttf', 'fonts/NotoSerifDisplay-Italic/googlefonts/ttf/NotoSerifDisplay-MediumItalic.ttf', 'fonts/NotoSerifDisplay-Italic/googlefonts/ttf/NotoSerifDisplay-SemiBoldItalic.ttf', 'fonts/NotoSerifDisplay-Italic/googlefonts/ttf/NotoSerifDisplay-ThinItalic.ttf', 'fonts/NotoSerifDisplay-Italic/googlefonts/variable-ttf/NotoSerifDisplay-ItalicMM[wdth,wght].ttf']. [code: missing-os2-fsselection-bit7]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinAscent value should be equal or greater than 1143, but got 1069 instead [code: ascent]
* 🔥 **FAIL** OS/2.usWinDescent value should be equal or greater than 470, but got 293 instead. [code: descent]
</div></details><details><summary>⚠ <b>WARN:</b> Glyphs are similiar to Google Fonts version? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/production_glyphs_similarity">com.google.fonts/check/production_glyphs_similarity</a>)</summary><div>


* ⚠ **WARN** Following glyphs differ greatly from Google Fonts version:
	* pi
	* uni1F57
	* uni0424
	* uni1F42
	* uni1F3B
	* uni1FCE
	* four.lf
	* uni0278
	* uni1F6A
	* uni0345 and 216 more.

Use -F or --full-lists to disable shortening of long lists.
</div></details><details><summary>⚠ <b>WARN:</b> Is there kerning info for non-ligated sequences? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/kerning_for_non_ligated_sequences">com.google.fonts/check/kerning_for_non_ligated_sequences</a>)</summary><div>


* ⚠ **WARN** GPOS table lacks kerning info for the following non-ligated sequences:

	- f + f

	- f + i

	- i + f

	- f + l

	- l + f

	- i + l

	- f.ss02 + f.ss02

	- f.ss02 + i

	- i + f.ss02

	- f.ss02 + l 

	- And l + f.ss02 [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Noto Serif Display ExtraBold' / SUBFAMILY_NAME = 'Italic'

Please take a look at the conversation at https://github.com/googlefonts/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure Stylistic Sets have description. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/stylisticset_description">com.google.fonts/check/stylisticset_description</a>)</summary><div>


* ⚠ **WARN** The stylistic set ss01 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss02 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss03 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss06 lacks a description string on the 'name' table. [code: missing-description]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Glyph names are all valid? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/valid_glyphnames">com.google.fonts/check/valid_glyphnames</a>)</summary><div>


* ⚠ **WARN** The following glyph names may be too long for some legacy systems which may expect a maximum 31-char length limit:
kavykawithkavykaaboveinvertedlow [code: legacy-long-names]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- uni1FCE0306

	- dasiavaria_macronmod

	- uni1FCD0306

	- uni03B1030603140301

	- uni1FCE02C9

	- dasiaoxia_macronmod

	- beta.alt1

	- uni03B9030803040300

	- uni03C5030603140301

	- uni03C5030603130301 

	- And 35 more.

Use -F or --full-lists to disable shortening of long lists.
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character (codepoint 0x00AD) which is supposed to be zero-width and invisible, and is used to mark a hyphenation possibility within a word in the absence of or overriding dictionary hyphenation. It is mostly an obsolete mechanism now, and the character is only included in fonts for legacy codepage coverage. [code: softhyphen]
* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: uni00AD	Contours detected: 1	Expected: 0

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: eogonek	Contours detected: 3	Expected: 2

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uni01E5	Contours detected: 3	Expected: 2

	- Glyph name: uni01EA	Contours detected: 3	Expected: 2

	- Glyph name: uni01EB	Contours detected: 3	Expected: 2

	- Glyph name: uni01EC	Contours detected: 4	Expected: 3

	- Glyph name: uni01ED	Contours detected: 4	Expected: 3 

	- And 39 more.

Use -F or --full-lists to disable shortening of long lists.
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check mark characters are in GDEF mark glyph class. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_mark_chars">com.google.fonts/check/gdef_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following mark characters could be in the GDEF mark glyph class:
	 uni0488 (U+0488), uni0489 (U+0489), uni1ABE (U+1ABE), uniA670 (U+A670), uniA671 (U+A671) and uniA672 (U+A672) [code: mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* Zpalatalhook (U+A7C6): L<<634.0,219.0>--<584.0,0.0>> -> L<<584.0,0.0>--<577.0,-29.0>>

	* beta (U+03B2): L<<-33.0,-229.0>--<42.0,112.0>> -> L<<42.0,112.0>--<121.0,509.0>>

	* rho (U+03C1): L<<-46.0,-230.0>--<23.0,84.0>> -> L<<23.0,84.0>--<60.0,263.0>>

	* uni03BC (U+03BC): L<<-32.0,-230.0>--<52.0,157.0>> -> L<<52.0,157.0>--<127.0,536.0>>

	* uni03FC (U+03FC): L<<-13.0,-82.0>--<23.0,84.0>> -> L<<23.0,84.0>--<60.0,263.0>>

	* uni044D (U+044D): L<<135.0,279.0>--<244.0,284.0>> -> L<<244.0,284.0>--<332.0,281.0>>

	* uni04ED (U+04ED): L<<135.0,279.0>--<244.0,284.0>> -> L<<244.0,284.0>--<332.0,281.0>>

	* uni1D0B (U+1D0B): L<<333.0,489.0>--<288.0,295.0>> -> L<<288.0,295.0>--<279.0,256.0>>

	* uni1D5D (U+1D5D): L<<15.0,150.0>--<64.0,354.0>> -> L<<64.0,354.0>--<116.0,592.0>>

	* uni1D66 (U+1D66): L<<-66.0,-233.0>--<-17.0,-29.0>> -> L<<-17.0,-29.0>--<34.0,209.0>> 

	* And 4 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* Bbarredmod (U+1D2F): B<<452.0,554.5>-<421.0,526.0>-<356.0,517.0>>/L<<356.0,517.0>--<497.0,517.0>> = 7.883139316729715

	* Bbarredmod (U+1D2F): L<<496.0,509.0>--<350.0,509.0>>/B<<350.0,509.0>-<455.0,493.0>-<455.0,415.0>> = 8.664135433108044

	* Bbarredsmall (U+1D03): B<<541.5,332.0>-<503.0,300.0>-<433.0,289.0>>/L<<433.0,289.0>--<598.0,289.0>> = 8.93059010041899

	* Bbarredsmall (U+1D03): L<<595.0,279.0>--<415.0,279.0>>/B<<415.0,279.0>-<480.0,270.0>-<513.5,243.5>> = 7.883139316729715

	* Ereversedopen (U+A7AB): B<<544.0,434.0>-<468.0,387.0>-<325.0,373.0>>/B<<325.0,373.0>-<445.0,366.0>-<508.0,330.5>> = 8.930028299521528

	* iotifiedbigyuscombcy (U+2DFF): B<<32.5,683.5>-<44.0,692.0>-<65.0,696.0>>/L<<65.0,696.0>--<-49.0,696.0>> = 10.784297867562596

	* sigma (U+03C3): L<<629.0,411.0>--<416.0,411.0>>/B<<416.0,411.0>-<462.0,404.0>-<501.0,381.0>> = 8.652541791114704

	* three (U+0033): B<<390.5,390.0>-<338.0,378.0>-<279.0,372.0>>/B<<279.0,372.0>-<408.0,365.0>-<465.0,324.5>> = 8.912754001147944

	* uni0193 (U+0193): B<<741.5,672.5>-<767.0,649.0>-<772.0,620.0>>/L<<772.0,620.0>--<772.0,622.0>> = 9.782407031807285

	* uni0193 (U+0193): L<<776.0,595.0>--<774.0,608.0>>/B<<774.0,608.0>-<774.0,605.0>-<774.0,601.0>> = 8.746162262555211 

	* And 51 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-jaggy-segments]
</div></details><br></div></details><details><summary><b>[17] NotoSerifDisplay-ExtraLightItalic.ttf</b></summary><div><details><summary>💔 <b>ERROR:</b> Check if the vertical metrics of a family are similar to the same family hosted on Google Fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vertical_metrics_regressions">com.google.fonts/check/vertical_metrics_regressions</a>)</summary><div>


* 💔 **ERROR** Failed with TypeError: 'NoneType' object is not subscriptable
</div></details><details><summary>🔥 <b>FAIL:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* 🔥 **FAIL** Missing required codepoints:

	- 0x2212 (MINUS SIGN)
 

	- And 0x00AF (MACRON)
 [code: missing-codepoints]
</div></details><details><summary>🔥 <b>FAIL:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* 🔥 **FAIL** License file OFL.txt exists but NameID 13 (LICENSE DESCRIPTION) value on platform 3 (WINDOWS) is not specified for that. Value was: "This Font Software is licensed under the SIL Open Font License, Version 1.1. This Font Software is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the SIL Open Font License for the specific language, permissions and limitations governing your use of this Font Software." Must be changed to "This Font Software is licensed under the SIL Open Font License, Version 1.1. This license is available with a FAQ at: https://scripts.sil.org/OFL" [code: wrong]
</div></details><details><summary>🔥 <b>FAIL:</b> Copyright notices match canonical pattern in fonts (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/font_copyright">com.google.fonts/check/font_copyright</a>)</summary><div>


* 🔥 **FAIL** Name Table entry: Copyright notices should match a pattern similar to: "Copyright 2019 The Familyname Project Authors (git url)"
But instead we have got:
"Copyright 2016-2021 Google Inc. All Rights Reserved." [code: bad-notice-format]
</div></details><details><summary>🔥 <b>FAIL:</b> OS/2.fsSelection bit 7 (USE_TYPO_METRICS) is set in all fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/os2/use_typo_metrics">com.google.fonts/check/os2/use_typo_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2.fsSelection bit 7 (USE_TYPO_METRICS) wasNOT set in the following fonts: ['fonts/NotoSerifDisplay-Italic/googlefonts/slim-variable-ttf/NotoSerifDisplay-ItalicMM[wght].ttf', 'fonts/NotoSerifDisplay-Italic/googlefonts/ttf/NotoSerifDisplay-BlackItalic.ttf', 'fonts/NotoSerifDisplay-Italic/googlefonts/ttf/NotoSerifDisplay-BoldItalic.ttf', 'fonts/NotoSerifDisplay-Italic/googlefonts/ttf/NotoSerifDisplay-ExtraBoldItalic.ttf', 'fonts/NotoSerifDisplay-Italic/googlefonts/ttf/NotoSerifDisplay-ExtraLightItalic.ttf', 'fonts/NotoSerifDisplay-Italic/googlefonts/ttf/NotoSerifDisplay-Italic.ttf', 'fonts/NotoSerifDisplay-Italic/googlefonts/ttf/NotoSerifDisplay-LightItalic.ttf', 'fonts/NotoSerifDisplay-Italic/googlefonts/ttf/NotoSerifDisplay-MediumItalic.ttf', 'fonts/NotoSerifDisplay-Italic/googlefonts/ttf/NotoSerifDisplay-SemiBoldItalic.ttf', 'fonts/NotoSerifDisplay-Italic/googlefonts/ttf/NotoSerifDisplay-ThinItalic.ttf', 'fonts/NotoSerifDisplay-Italic/googlefonts/variable-ttf/NotoSerifDisplay-ItalicMM[wdth,wght].ttf']. [code: missing-os2-fsselection-bit7]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinAscent value should be equal or greater than 1143, but got 1069 instead [code: ascent]
* 🔥 **FAIL** OS/2.usWinDescent value should be equal or greater than 470, but got 293 instead. [code: descent]
</div></details><details><summary>⚠ <b>WARN:</b> Glyphs are similiar to Google Fonts version? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/production_glyphs_similarity">com.google.fonts/check/production_glyphs_similarity</a>)</summary><div>


* ⚠ **WARN** Following glyphs differ greatly from Google Fonts version:
	* uni1F57
	* uni1F62
	* uni1FA5
	* uni1FF6
	* uni1FA8
	* uni1F9D
	* uni1FA6
	* uni1F8D
	* uni1F64
	* uni1F9A and 68 more.

Use -F or --full-lists to disable shortening of long lists.
</div></details><details><summary>⚠ <b>WARN:</b> Is there kerning info for non-ligated sequences? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/kerning_for_non_ligated_sequences">com.google.fonts/check/kerning_for_non_ligated_sequences</a>)</summary><div>


* ⚠ **WARN** GPOS table lacks kerning info for the following non-ligated sequences:

	- f + f

	- f + i

	- i + f

	- f + l

	- l + f

	- i + l

	- f.ss02 + f.ss02

	- f.ss02 + i

	- i + f.ss02

	- f.ss02 + l 

	- And l + f.ss02 [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Noto Serif Display ExtraLight' / SUBFAMILY_NAME = 'Italic'

Please take a look at the conversation at https://github.com/googlefonts/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure Stylistic Sets have description. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/stylisticset_description">com.google.fonts/check/stylisticset_description</a>)</summary><div>


* ⚠ **WARN** The stylistic set ss01 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss02 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss03 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss06 lacks a description string on the 'name' table. [code: missing-description]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Glyph names are all valid? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/valid_glyphnames">com.google.fonts/check/valid_glyphnames</a>)</summary><div>


* ⚠ **WARN** The following glyph names may be too long for some legacy systems which may expect a maximum 31-char length limit:
kavykawithkavykaaboveinvertedlow [code: legacy-long-names]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- uni1FCE0306

	- dasiavaria_macronmod

	- uni1FCD0306

	- uni03B1030603140301

	- uni1FCE02C9

	- dasiaoxia_macronmod

	- beta.alt1

	- uni03B9030803040300

	- uni03C5030603140301

	- uni03C5030603130301 

	- And 35 more.

Use -F or --full-lists to disable shortening of long lists.
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character (codepoint 0x00AD) which is supposed to be zero-width and invisible, and is used to mark a hyphenation possibility within a word in the absence of or overriding dictionary hyphenation. It is mostly an obsolete mechanism now, and the character is only included in fonts for legacy codepage coverage. [code: softhyphen]
* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: uni00AD	Contours detected: 1	Expected: 0

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: eogonek	Contours detected: 3	Expected: 2

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uni01E5	Contours detected: 3	Expected: 2

	- Glyph name: uni01EA	Contours detected: 3	Expected: 2

	- Glyph name: uni01EB	Contours detected: 3	Expected: 2

	- Glyph name: uni01EC	Contours detected: 4	Expected: 3

	- Glyph name: uni01ED	Contours detected: 4	Expected: 3 

	- And 39 more.

Use -F or --full-lists to disable shortening of long lists.
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check mark characters are in GDEF mark glyph class. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_mark_chars">com.google.fonts/check/gdef_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following mark characters could be in the GDEF mark glyph class:
	 uni0488 (U+0488), uni0489 (U+0489), uni1ABE (U+1ABE), uniA670 (U+A670), uniA671 (U+A671) and uniA672 (U+A672) [code: mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* Zpalatalhook (U+A7C6): L<<493.0,143.0>--<458.0,0.0>> -> L<<458.0,0.0>--<438.0,-72.0>>

	* beta (U+03B2): L<<-38.0,-240.0>--<39.0,118.0>> -> L<<39.0,118.0>--<133.0,559.0>>

	* rho (U+03C1): L<<-48.0,-240.0>--<19.0,63.0>> -> L<<19.0,63.0>--<65.0,285.0>>

	* tripledagger (U+2E4B): L<<50.0,346.0>--<212.0,331.0>> -> L<<212.0,331.0>--<212.0,331.0>>

	* uni0246 (U+0246): L<<515.0,704.0>--<514.0,704.0>> -> L<<514.0,704.0>--<280.0,704.0>>

	* uni03BC (U+03BC): L<<-37.0,-240.0>--<44.0,134.0>> -> L<<44.0,134.0>--<127.0,536.0>>

	* uni03FC (U+03FC): L<<-15.0,-88.0>--<19.0,63.0>> -> L<<19.0,63.0>--<65.0,285.0>>

	* uni1D0B (U+1D0B): L<<179.0,464.0>--<140.0,280.0>> -> L<<140.0,280.0>--<126.0,216.0>>

	* uni1D5D (U+1D5D): L<<-10.0,143.0>--<40.0,358.0>> -> L<<40.0,358.0>--<101.0,622.0>>

	* uni1D66 (U+1D66): L<<-91.0,-240.0>--<-41.0,-25.0>> -> L<<-41.0,-25.0>--<20.0,239.0>> 

	* And 5 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* Bbarredmod (U+1D2F): B<<394.0,552.5>-<366.0,526.0>-<321.0,517.0>>/L<<321.0,517.0>--<436.0,517.0>> = 11.309932474020195

	* Bbarredmod (U+1D2F): L<<434.0,508.0>--<316.0,508.0>>/B<<316.0,508.0>-<350.0,500.0>-<372.0,478.0>> = 13.240519915187184

	* Bbarredsmall (U+1D03): B<<423.0,332.5>-<390.0,299.0>-<331.0,287.0>>/L<<331.0,287.0>--<467.0,287.0>> = 11.496563017585768

	* Bbarredsmall (U+1D03): L<<464.0,277.0>--<320.0,277.0>>/B<<320.0,277.0>-<367.0,268.0>-<399.0,242.5>> = 10.840305454330565

	* chi (U+03C7): L<<245.0,181.0>--<268.0,221.0>>/L<<268.0,221.0>--<245.0,180.0>> = 0.6075396676301458

	* chi (U+03C7): L<<97.0,-75.0>--<12.0,-155.0>>/L<<12.0,-155.0>--<209.0,125.0>> = 11.606580609192578

	* iotifiedbigyuscombcy (U+2DFF): B<<56.0,689.5>-<65.0,696.0>-<84.0,699.0>>/L<<84.0,699.0>--<-18.0,699.0>> = 8.972626614896358

	* kacombcy (U+2DE6): B<<100.5,716.0>-<84.0,698.0>-<66.0,695.0>>/B<<66.0,695.0>-<91.0,694.0>-<103.0,686.5>> = 11.752932250664111

	* three (U+0033): B<<391.5,410.5>-<348.0,383.0>-<290.0,377.0>>/B<<290.0,377.0>-<349.0,371.0>-<391.0,330.5>> = 11.712868019302054

	* uni024A (U+024A): L<<439.0,-59.0>--<490.0,177.0>>/B<<490.0,177.0>-<446.0,76.0>-<387.0,31.5>> = 11.34583922695676 

	* And 38 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-jaggy-segments]
</div></details><br></div></details><details><summary><b>[24] NotoSerifDisplay-Italic.ttf</b></summary><div><details><summary>💔 <b>ERROR:</b> Check if the vertical metrics of a family are similar to the same family hosted on Google Fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vertical_metrics_regressions">com.google.fonts/check/vertical_metrics_regressions</a>)</summary><div>


* 💔 **ERROR** Failed with TypeError: 'NoneType' object is not subscriptable
</div></details><details><summary>🔥 <b>FAIL:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* 🔥 **FAIL** Missing required codepoints:

	- 0x2212 (MINUS SIGN)
 

	- And 0x00AF (MACRON)
 [code: missing-codepoints]
</div></details><details><summary>🔥 <b>FAIL:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* 🔥 **FAIL** License file OFL.txt exists but NameID 13 (LICENSE DESCRIPTION) value on platform 3 (WINDOWS) is not specified for that. Value was: "This Font Software is licensed under the SIL Open Font License, Version 1.1. This Font Software is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the SIL Open Font License for the specific language, permissions and limitations governing your use of this Font Software." Must be changed to "This Font Software is licensed under the SIL Open Font License, Version 1.1. This license is available with a FAQ at: https://scripts.sil.org/OFL" [code: wrong]
</div></details><details><summary>🔥 <b>FAIL:</b> Is the Grid-fitting and Scan-conversion Procedure ('gasp') table set to optimize rendering? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/gasp">com.google.fonts/check/gasp</a>)</summary><div>


* 🔥 **FAIL** Font is missing the 'gasp' table. Try exporting the font with autohinting enabled.
If you are dealing with an unhinted font, it can be fixed by running the fonts through the command 'gftools fix-nonhinting'
GFTools is available at https://pypi.org/project/gftools/ [code: lacks-gasp]
</div></details><details><summary>🔥 <b>FAIL:</b> Copyright notices match canonical pattern in fonts (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/font_copyright">com.google.fonts/check/font_copyright</a>)</summary><div>


* 🔥 **FAIL** Name Table entry: Copyright notices should match a pattern similar to: "Copyright 2019 The Familyname Project Authors (git url)"
But instead we have got:
"Copyright 2016-2021 Google Inc. All Rights Reserved." [code: bad-notice-format]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 fsSelection value. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/fsselection">com.google.fonts/check/fsselection</a>)</summary><div>


* 🔥 **FAIL** OS/2 fsSelection REGULAR bit should be unset. [code: bad-REGULAR]
* 🔥 **FAIL** OS/2 fsSelection ITALIC bit should be set. [code: bad-ITALIC]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking head.macStyle value. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/mac_style">com.google.fonts/check/mac_style</a>)</summary><div>


* 🔥 **FAIL** head macStyle ITALIC bit should be set. [code: bad-ITALIC]
</div></details><details><summary>🔥 <b>FAIL:</b> Check name table: FONT_FAMILY_NAME entries. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/familyname">com.google.fonts/check/name/familyname</a>)</summary><div>


* 🔥 **FAIL** Entry [FONT_FAMILY_NAME(1):WINDOWS(3)] on the "name" table: Expected "Noto Serif Display" but got "Noto Serif Display Italic". [code: mismatch]
</div></details><details><summary>🔥 <b>FAIL:</b> Check name table: FONT_SUBFAMILY_NAME entries. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/subfamilyname">com.google.fonts/check/name/subfamilyname</a>)</summary><div>


* 🔥 **FAIL** SUBFAMILY_NAME for Win "Regular" must be "Italic" [code: bad-familyname]
</div></details><details><summary>🔥 <b>FAIL:</b> Check name table: TYPOGRAPHIC_FAMILY_NAME entries. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/typographicfamilyname">com.google.fonts/check/name/typographicfamilyname</a>)</summary><div>


* 🔥 **FAIL** Font style is "Italic" and, for that reason, it is not expected to have a [TYPOGRAPHIC_FAMILY_NAME(16):WINDOWS(3)] entry! [code: ribbi]
</div></details><details><summary>🔥 <b>FAIL:</b> Font enables smart dropout control in "prep" table instructions? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/smart_dropout">com.google.fonts/check/smart_dropout</a>)</summary><div>


* 🔥 **FAIL** The 'prep' table does not contain TrueType instructions enabling smart dropout control. To fix, export the font with autohinting enabled, or run ttfautohint on the font, or run the `gftools fix-nonhinting` script. [code: lacks-smart-dropout]
</div></details><details><summary>🔥 <b>FAIL:</b> OS/2.fsSelection bit 7 (USE_TYPO_METRICS) is set in all fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/os2/use_typo_metrics">com.google.fonts/check/os2/use_typo_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2.fsSelection bit 7 (USE_TYPO_METRICS) wasNOT set in the following fonts: ['fonts/NotoSerifDisplay-Italic/googlefonts/slim-variable-ttf/NotoSerifDisplay-ItalicMM[wght].ttf', 'fonts/NotoSerifDisplay-Italic/googlefonts/ttf/NotoSerifDisplay-BlackItalic.ttf', 'fonts/NotoSerifDisplay-Italic/googlefonts/ttf/NotoSerifDisplay-BoldItalic.ttf', 'fonts/NotoSerifDisplay-Italic/googlefonts/ttf/NotoSerifDisplay-ExtraBoldItalic.ttf', 'fonts/NotoSerifDisplay-Italic/googlefonts/ttf/NotoSerifDisplay-ExtraLightItalic.ttf', 'fonts/NotoSerifDisplay-Italic/googlefonts/ttf/NotoSerifDisplay-Italic.ttf', 'fonts/NotoSerifDisplay-Italic/googlefonts/ttf/NotoSerifDisplay-LightItalic.ttf', 'fonts/NotoSerifDisplay-Italic/googlefonts/ttf/NotoSerifDisplay-MediumItalic.ttf', 'fonts/NotoSerifDisplay-Italic/googlefonts/ttf/NotoSerifDisplay-SemiBoldItalic.ttf', 'fonts/NotoSerifDisplay-Italic/googlefonts/ttf/NotoSerifDisplay-ThinItalic.ttf', 'fonts/NotoSerifDisplay-Italic/googlefonts/variable-ttf/NotoSerifDisplay-ItalicMM[wdth,wght].ttf']. [code: missing-os2-fsselection-bit7]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinAscent value should be equal or greater than 1143, but got 1069 instead [code: ascent]
* 🔥 **FAIL** OS/2.usWinDescent value should be equal or greater than 470, but got 293 instead. [code: descent]
</div></details><details><summary>⚠ <b>WARN:</b> Glyphs are similiar to Google Fonts version? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/production_glyphs_similarity">com.google.fonts/check/production_glyphs_similarity</a>)</summary><div>


* ⚠ **WARN** Following glyphs differ greatly from Google Fonts version:
	* uni1F57
	* uni0424
	* uni0278
	* uni1F62
	* uni1F92
	* uni1FA5
	* uni1FC2
	* uni1D72
	* uni1FF6
	* uni1FA8 and 100 more.

Use -F or --full-lists to disable shortening of long lists.
</div></details><details><summary>⚠ <b>WARN:</b> Is there kerning info for non-ligated sequences? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/kerning_for_non_ligated_sequences">com.google.fonts/check/kerning_for_non_ligated_sequences</a>)</summary><div>


* ⚠ **WARN** GPOS table lacks kerning info for the following non-ligated sequences:

	- f + f

	- f + i

	- i + f

	- f + l

	- l + f

	- i + l

	- f.ss02 + f.ss02

	- f.ss02 + i

	- i + f.ss02

	- f.ss02 + l 

	- And l + f.ss02 [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Noto Serif Display Italic' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/googlefonts/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure Stylistic Sets have description. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/stylisticset_description">com.google.fonts/check/stylisticset_description</a>)</summary><div>


* ⚠ **WARN** The stylistic set ss01 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss02 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss03 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss06 lacks a description string on the 'name' table. [code: missing-description]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Glyph names are all valid? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/valid_glyphnames">com.google.fonts/check/valid_glyphnames</a>)</summary><div>


* ⚠ **WARN** The following glyph names may be too long for some legacy systems which may expect a maximum 31-char length limit:
kavykawithkavykaaboveinvertedlow [code: legacy-long-names]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- uni1FCE0306

	- dasiavaria_macronmod

	- uni1FCD0306

	- uni03B1030603140301

	- uni1FCE02C9

	- dasiaoxia_macronmod

	- beta.alt1

	- uni03B9030803040300

	- uni03C5030603140301

	- uni03C5030603130301 

	- And 35 more.

Use -F or --full-lists to disable shortening of long lists.
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character (codepoint 0x00AD) which is supposed to be zero-width and invisible, and is used to mark a hyphenation possibility within a word in the absence of or overriding dictionary hyphenation. It is mostly an obsolete mechanism now, and the character is only included in fonts for legacy codepage coverage. [code: softhyphen]
* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: uni00AD	Contours detected: 1	Expected: 0

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: eogonek	Contours detected: 3	Expected: 2

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uni01E5	Contours detected: 3	Expected: 2

	- Glyph name: uni01EA	Contours detected: 3	Expected: 2

	- Glyph name: uni01EB	Contours detected: 3	Expected: 2

	- Glyph name: uni01EC	Contours detected: 4	Expected: 3

	- Glyph name: uni01ED	Contours detected: 4	Expected: 3 

	- And 41 more.

Use -F or --full-lists to disable shortening of long lists.
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check mark characters are in GDEF mark glyph class. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_mark_chars">com.google.fonts/check/gdef_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following mark characters could be in the GDEF mark glyph class:
	 uni0488 (U+0488), uni0489 (U+0489), uni1ABE (U+1ABE), uniA670 (U+A670), uniA671 (U+A671) and uniA672 (U+A672) [code: mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* Zpalatalhook (U+A7C6): L<<550.0,175.0>--<508.0,0.0>> -> L<<508.0,0.0>--<498.0,-37.0>>

	* beta (U+03B2): L<<-38.0,-240.0>--<41.0,116.0>> -> L<<41.0,116.0>--<128.0,536.0>>

	* rho (U+03C1): L<<-48.0,-240.0>--<32.0,109.0>> -> L<<32.0,109.0>--<59.0,243.0>>

	* uni03BC (U+03BC): L<<-35.0,-240.0>--<45.0,126.0>> -> L<<45.0,126.0>--<127.0,536.0>>

	* uni03FC (U+03FC): L<<-11.0,-80.0>--<32.0,109.0>> -> L<<32.0,109.0>--<59.0,243.0>>

	* uni1D0B (U+1D0B): L<<247.0,475.0>--<205.0,290.0>> -> L<<205.0,290.0>--<188.0,217.0>>

	* uni1D5D (U+1D5D): L<<0.0,143.0>--<52.0,357.0>> -> L<<52.0,357.0>--<108.0,609.0>>

	* uni1D66 (U+1D66): L<<-82.0,-240.0>--<-30.0,-26.0>> -> L<<-30.0,-26.0>--<26.0,226.0>>

	* uni1D68 (U+1D68): L<<-83.0,-240.0>--<-31.0,-31.0>> -> L<<-31.0,-31.0>--<-14.0,50.0>>

	* uni1DE9 (U+1DE9): L<<-49.0,586.0>--<-14.0,728.0>> -> L<<-14.0,728.0>--<26.0,896.0>> 

	* And 3 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* Bbarredmod (U+1D2F): B<<417.0,551.5>-<384.0,525.0>-<333.0,516.0>>/L<<333.0,516.0>--<460.0,516.0>> = 10.00797980144135

	* Bbarredmod (U+1D2F): L<<457.0,506.0>--<343.0,506.0>>/B<<343.0,506.0>-<423.0,489.0>-<423.0,420.0>> = 11.996899307923568

	* Bbarredsmall (U+1D03): B<<472.5,332.0>-<438.0,298.0>-<363.0,285.0>>/L<<363.0,285.0>--<510.0,285.0>> = 9.833563964207102

	* Bbarredsmall (U+1D03): L<<508.0,275.0>--<362.0,275.0>>/B<<362.0,275.0>-<424.0,264.0>-<451.5,233.0>> = 10.060689795322984

	* Ereversedopen (U+A7AB): B<<448.5,397.0>-<391.0,374.0>-<320.0,367.0>>/B<<320.0,367.0>-<352.0,364.0>-<387.0,355.5>> = 10.986507800490408

	* cpalatalhook (U+A794): B<<377.5,65.5>-<402.0,93.0>-<414.0,121.0>>/L<<414.0,121.0>--<383.0,-55.0>> = 13.209183087411478

	* eopenmod (U+1D4B): L<<185.0,457.0>--<185.0,457.0>>/B<<185.0,457.0>-<139.0,462.0>-<118.5,479.5>> = 6.203447901691829

	* eturnedopenmod (U+1D4C): B<<355.0,530.0>-<355.0,451.0>-<221.0,438.0>>/L<<221.0,438.0>--<221.0,438.0>> = 5.541204778039828

	* hardsigntallcy (U+1C86): B<<345.0,685.5>-<382.0,728.0>-<412.0,754.0>>/B<<412.0,754.0>-<410.0,752.0>-<355.5,751.0>> = 4.085616779974888

	* three (U+0033): B<<469.0,446.5>-<409.0,390.0>-<288.0,375.0>>/B<<288.0,375.0>-<377.0,369.0>-<427.5,328.5>> = 10.923530701990947 

	* And 30 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-jaggy-segments]
</div></details><br></div></details><details><summary><b>[17] NotoSerifDisplay-LightItalic.ttf</b></summary><div><details><summary>💔 <b>ERROR:</b> Check if the vertical metrics of a family are similar to the same family hosted on Google Fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vertical_metrics_regressions">com.google.fonts/check/vertical_metrics_regressions</a>)</summary><div>


* 💔 **ERROR** Failed with TypeError: 'NoneType' object is not subscriptable
</div></details><details><summary>🔥 <b>FAIL:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* 🔥 **FAIL** Missing required codepoints:

	- 0x2212 (MINUS SIGN)
 

	- And 0x00AF (MACRON)
 [code: missing-codepoints]
</div></details><details><summary>🔥 <b>FAIL:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* 🔥 **FAIL** License file OFL.txt exists but NameID 13 (LICENSE DESCRIPTION) value on platform 3 (WINDOWS) is not specified for that. Value was: "This Font Software is licensed under the SIL Open Font License, Version 1.1. This Font Software is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the SIL Open Font License for the specific language, permissions and limitations governing your use of this Font Software." Must be changed to "This Font Software is licensed under the SIL Open Font License, Version 1.1. This license is available with a FAQ at: https://scripts.sil.org/OFL" [code: wrong]
</div></details><details><summary>🔥 <b>FAIL:</b> Copyright notices match canonical pattern in fonts (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/font_copyright">com.google.fonts/check/font_copyright</a>)</summary><div>


* 🔥 **FAIL** Name Table entry: Copyright notices should match a pattern similar to: "Copyright 2019 The Familyname Project Authors (git url)"
But instead we have got:
"Copyright 2016-2021 Google Inc. All Rights Reserved." [code: bad-notice-format]
</div></details><details><summary>🔥 <b>FAIL:</b> OS/2.fsSelection bit 7 (USE_TYPO_METRICS) is set in all fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/os2/use_typo_metrics">com.google.fonts/check/os2/use_typo_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2.fsSelection bit 7 (USE_TYPO_METRICS) wasNOT set in the following fonts: ['fonts/NotoSerifDisplay-Italic/googlefonts/slim-variable-ttf/NotoSerifDisplay-ItalicMM[wght].ttf', 'fonts/NotoSerifDisplay-Italic/googlefonts/ttf/NotoSerifDisplay-BlackItalic.ttf', 'fonts/NotoSerifDisplay-Italic/googlefonts/ttf/NotoSerifDisplay-BoldItalic.ttf', 'fonts/NotoSerifDisplay-Italic/googlefonts/ttf/NotoSerifDisplay-ExtraBoldItalic.ttf', 'fonts/NotoSerifDisplay-Italic/googlefonts/ttf/NotoSerifDisplay-ExtraLightItalic.ttf', 'fonts/NotoSerifDisplay-Italic/googlefonts/ttf/NotoSerifDisplay-Italic.ttf', 'fonts/NotoSerifDisplay-Italic/googlefonts/ttf/NotoSerifDisplay-LightItalic.ttf', 'fonts/NotoSerifDisplay-Italic/googlefonts/ttf/NotoSerifDisplay-MediumItalic.ttf', 'fonts/NotoSerifDisplay-Italic/googlefonts/ttf/NotoSerifDisplay-SemiBoldItalic.ttf', 'fonts/NotoSerifDisplay-Italic/googlefonts/ttf/NotoSerifDisplay-ThinItalic.ttf', 'fonts/NotoSerifDisplay-Italic/googlefonts/variable-ttf/NotoSerifDisplay-ItalicMM[wdth,wght].ttf']. [code: missing-os2-fsselection-bit7]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinAscent value should be equal or greater than 1143, but got 1069 instead [code: ascent]
* 🔥 **FAIL** OS/2.usWinDescent value should be equal or greater than 470, but got 293 instead. [code: descent]
</div></details><details><summary>⚠ <b>WARN:</b> Glyphs are similiar to Google Fonts version? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/production_glyphs_similarity">com.google.fonts/check/production_glyphs_similarity</a>)</summary><div>


* ⚠ **WARN** Following glyphs differ greatly from Google Fonts version:
	* uni1F57
	* uni0424
	* uni1F62
	* uni1FA5
	* uni1FF6
	* uni1FA8
	* uni1F9D
	* uni1FA6
	* uni1F8D
	* uni1F64 and 86 more.

Use -F or --full-lists to disable shortening of long lists.
</div></details><details><summary>⚠ <b>WARN:</b> Is there kerning info for non-ligated sequences? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/kerning_for_non_ligated_sequences">com.google.fonts/check/kerning_for_non_ligated_sequences</a>)</summary><div>


* ⚠ **WARN** GPOS table lacks kerning info for the following non-ligated sequences:

	- f + f

	- f + i

	- i + f

	- f + l

	- l + f

	- i + l

	- f.ss02 + f.ss02

	- f.ss02 + i

	- i + f.ss02

	- f.ss02 + l 

	- And l + f.ss02 [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Noto Serif Display Light' / SUBFAMILY_NAME = 'Italic'

Please take a look at the conversation at https://github.com/googlefonts/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure Stylistic Sets have description. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/stylisticset_description">com.google.fonts/check/stylisticset_description</a>)</summary><div>


* ⚠ **WARN** The stylistic set ss01 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss02 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss03 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss06 lacks a description string on the 'name' table. [code: missing-description]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Glyph names are all valid? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/valid_glyphnames">com.google.fonts/check/valid_glyphnames</a>)</summary><div>


* ⚠ **WARN** The following glyph names may be too long for some legacy systems which may expect a maximum 31-char length limit:
kavykawithkavykaaboveinvertedlow [code: legacy-long-names]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- uni1FCE0306

	- dasiavaria_macronmod

	- uni1FCD0306

	- uni03B1030603140301

	- uni1FCE02C9

	- dasiaoxia_macronmod

	- beta.alt1

	- uni03B9030803040300

	- uni03C5030603140301

	- uni03C5030603130301 

	- And 35 more.

Use -F or --full-lists to disable shortening of long lists.
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character (codepoint 0x00AD) which is supposed to be zero-width and invisible, and is used to mark a hyphenation possibility within a word in the absence of or overriding dictionary hyphenation. It is mostly an obsolete mechanism now, and the character is only included in fonts for legacy codepage coverage. [code: softhyphen]
* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: uni00AD	Contours detected: 1	Expected: 0

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: eogonek	Contours detected: 3	Expected: 2

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uni01E5	Contours detected: 3	Expected: 2

	- Glyph name: uni01EA	Contours detected: 3	Expected: 2

	- Glyph name: uni01EB	Contours detected: 3	Expected: 2

	- Glyph name: uni01EC	Contours detected: 4	Expected: 3

	- Glyph name: uni01ED	Contours detected: 4	Expected: 3 

	- And 39 more.

Use -F or --full-lists to disable shortening of long lists.
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check mark characters are in GDEF mark glyph class. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_mark_chars">com.google.fonts/check/gdef_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following mark characters could be in the GDEF mark glyph class:
	 uni0488 (U+0488), uni0489 (U+0489), uni1ABE (U+1ABE), uniA670 (U+A670), uniA671 (U+A671) and uniA672 (U+A672) [code: mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* Zpalatalhook (U+A7C6): L<<517.0,156.0>--<479.0,0.0>> -> L<<479.0,0.0>--<463.0,-57.0>>

	* beta (U+03B2): L<<-38.0,-240.0>--<40.0,117.0>> -> L<<40.0,117.0>--<131.0,549.0>>

	* rho (U+03C1): L<<-48.0,-240.0>--<24.0,83.0>> -> L<<24.0,83.0>--<62.0,267.0>>

	* uni03BC (U+03BC): L<<-36.0,-240.0>--<45.0,131.0>> -> L<<45.0,131.0>--<127.0,536.0>>

	* uni03FC (U+03FC): L<<-13.0,-85.0>--<24.0,83.0>> -> L<<24.0,83.0>--<62.0,267.0>>

	* uni1D0B (U+1D0B): L<<208.0,469.0>--<167.0,284.0>> -> L<<167.0,284.0>--<152.0,217.0>>

	* uni1D5D (U+1D5D): L<<-6.0,143.0>--<45.0,357.0>> -> L<<45.0,357.0>--<104.0,617.0>>

	* uni1D66 (U+1D66): L<<-87.0,-240.0>--<-36.0,-26.0>> -> L<<-36.0,-26.0>--<23.0,234.0>>

	* uni1D68 (U+1D68): L<<-83.0,-240.0>--<-36.0,-46.0>> -> L<<-36.0,-46.0>--<-12.0,64.0>>

	* uni1D9A (U+1D9A): L<<422.0,525.0>--<161.0,296.0>> -> L<<161.0,296.0>--<160.0,295.0>> 

	* And 3 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* Bbarredmod (U+1D2F): B<<403.5,551.5>-<373.0,525.0>-<326.0,516.0>>/L<<326.0,516.0>--<446.0,516.0>> = 10.840305454330565

	* Bbarredmod (U+1D2F): L<<444.0,507.0>--<326.0,507.0>>/B<<326.0,507.0>-<364.0,499.0>-<385.0,477.5>> = 11.888658039627968

	* Bbarredsmall (U+1D03): B<<477.0,421.0>-<477.0,311.0>-<345.0,286.0>>/L<<345.0,286.0>--<485.0,286.0>> = 10.724448537471174

	* Bbarredsmall (U+1D03): L<<483.0,276.0>--<337.0,276.0>>/B<<337.0,276.0>-<391.0,266.0>-<421.0,238.5>> = 10.491477012331599

	* Ereversedopen (U+A7AB): B<<444.5,397.5>-<394.0,372.0>-<331.0,366.0>>/B<<331.0,366.0>-<373.0,360.0>-<412.5,342.5>> = 13.570434385161475

	* chi (U+03C7): L<<221.0,88.0>--<133.0,-22.0>>/L<<133.0,-22.0>--<218.0,102.0>> = 4.22979947491706

	* chi (U+03C7): L<<268.0,180.0>--<361.0,354.0>>/L<<361.0,354.0>--<297.0,183.0>> = 7.604418222465043

	* eopenmod (U+1D4B): L<<169.0,458.0>--<169.0,458.0>>/B<<169.0,458.0>-<99.0,470.0>-<99.0,523.0>> = 9.727578551401587

	* iotifiedbigyuscombcy (U+2DFF): B<<52.5,691.0>-<62.0,698.0>-<78.0,700.0>>/L<<78.0,700.0>--<-23.0,700.0>> = 7.125016348901757

	* three (U+0033): B<<446.5,443.5>-<390.0,388.0>-<289.0,376.0>>/B<<289.0,376.0>-<361.0,370.0>-<406.5,329.5>> = 11.539297860125181 

	* And 30 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-jaggy-segments]
</div></details><br></div></details><details><summary><b>[17] NotoSerifDisplay-MediumItalic.ttf</b></summary><div><details><summary>💔 <b>ERROR:</b> Check if the vertical metrics of a family are similar to the same family hosted on Google Fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vertical_metrics_regressions">com.google.fonts/check/vertical_metrics_regressions</a>)</summary><div>


* 💔 **ERROR** Failed with TypeError: 'NoneType' object is not subscriptable
</div></details><details><summary>🔥 <b>FAIL:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* 🔥 **FAIL** Missing required codepoints:

	- 0x2212 (MINUS SIGN)
 

	- And 0x00AF (MACRON)
 [code: missing-codepoints]
</div></details><details><summary>🔥 <b>FAIL:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* 🔥 **FAIL** License file OFL.txt exists but NameID 13 (LICENSE DESCRIPTION) value on platform 3 (WINDOWS) is not specified for that. Value was: "This Font Software is licensed under the SIL Open Font License, Version 1.1. This Font Software is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the SIL Open Font License for the specific language, permissions and limitations governing your use of this Font Software." Must be changed to "This Font Software is licensed under the SIL Open Font License, Version 1.1. This license is available with a FAQ at: https://scripts.sil.org/OFL" [code: wrong]
</div></details><details><summary>🔥 <b>FAIL:</b> Copyright notices match canonical pattern in fonts (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/font_copyright">com.google.fonts/check/font_copyright</a>)</summary><div>


* 🔥 **FAIL** Name Table entry: Copyright notices should match a pattern similar to: "Copyright 2019 The Familyname Project Authors (git url)"
But instead we have got:
"Copyright 2016-2021 Google Inc. All Rights Reserved." [code: bad-notice-format]
</div></details><details><summary>🔥 <b>FAIL:</b> OS/2.fsSelection bit 7 (USE_TYPO_METRICS) is set in all fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/os2/use_typo_metrics">com.google.fonts/check/os2/use_typo_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2.fsSelection bit 7 (USE_TYPO_METRICS) wasNOT set in the following fonts: ['fonts/NotoSerifDisplay-Italic/googlefonts/slim-variable-ttf/NotoSerifDisplay-ItalicMM[wght].ttf', 'fonts/NotoSerifDisplay-Italic/googlefonts/ttf/NotoSerifDisplay-BlackItalic.ttf', 'fonts/NotoSerifDisplay-Italic/googlefonts/ttf/NotoSerifDisplay-BoldItalic.ttf', 'fonts/NotoSerifDisplay-Italic/googlefonts/ttf/NotoSerifDisplay-ExtraBoldItalic.ttf', 'fonts/NotoSerifDisplay-Italic/googlefonts/ttf/NotoSerifDisplay-ExtraLightItalic.ttf', 'fonts/NotoSerifDisplay-Italic/googlefonts/ttf/NotoSerifDisplay-Italic.ttf', 'fonts/NotoSerifDisplay-Italic/googlefonts/ttf/NotoSerifDisplay-LightItalic.ttf', 'fonts/NotoSerifDisplay-Italic/googlefonts/ttf/NotoSerifDisplay-MediumItalic.ttf', 'fonts/NotoSerifDisplay-Italic/googlefonts/ttf/NotoSerifDisplay-SemiBoldItalic.ttf', 'fonts/NotoSerifDisplay-Italic/googlefonts/ttf/NotoSerifDisplay-ThinItalic.ttf', 'fonts/NotoSerifDisplay-Italic/googlefonts/variable-ttf/NotoSerifDisplay-ItalicMM[wdth,wght].ttf']. [code: missing-os2-fsselection-bit7]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinAscent value should be equal or greater than 1143, but got 1069 instead [code: ascent]
* 🔥 **FAIL** OS/2.usWinDescent value should be equal or greater than 470, but got 293 instead. [code: descent]
</div></details><details><summary>⚠ <b>WARN:</b> Glyphs are similiar to Google Fonts version? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/production_glyphs_similarity">com.google.fonts/check/production_glyphs_similarity</a>)</summary><div>


* ⚠ **WARN** Following glyphs differ greatly from Google Fonts version:
	* pi
	* uni1F57
	* uni0424
	* uni0278
	* uni1F62
	* uni1F92
	* uni1FA5
	* uni1FC2
	* uni1D72
	* uni1FF6 and 121 more.

Use -F or --full-lists to disable shortening of long lists.
</div></details><details><summary>⚠ <b>WARN:</b> Is there kerning info for non-ligated sequences? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/kerning_for_non_ligated_sequences">com.google.fonts/check/kerning_for_non_ligated_sequences</a>)</summary><div>


* ⚠ **WARN** GPOS table lacks kerning info for the following non-ligated sequences:

	- f + f

	- f + i

	- i + f

	- f + l

	- l + f

	- i + l

	- f.ss02 + f.ss02

	- f.ss02 + i

	- i + f.ss02

	- f.ss02 + l 

	- And l + f.ss02 [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Noto Serif Display Medium' / SUBFAMILY_NAME = 'Italic'

Please take a look at the conversation at https://github.com/googlefonts/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure Stylistic Sets have description. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/stylisticset_description">com.google.fonts/check/stylisticset_description</a>)</summary><div>


* ⚠ **WARN** The stylistic set ss01 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss02 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss03 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss06 lacks a description string on the 'name' table. [code: missing-description]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Glyph names are all valid? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/valid_glyphnames">com.google.fonts/check/valid_glyphnames</a>)</summary><div>


* ⚠ **WARN** The following glyph names may be too long for some legacy systems which may expect a maximum 31-char length limit:
kavykawithkavykaaboveinvertedlow [code: legacy-long-names]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- uni1FCE0306

	- dasiavaria_macronmod

	- uni1FCD0306

	- uni03B1030603140301

	- uni1FCE02C9

	- dasiaoxia_macronmod

	- beta.alt1

	- uni03B9030803040300

	- uni03C5030603140301

	- uni03C5030603130301 

	- And 35 more.

Use -F or --full-lists to disable shortening of long lists.
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character (codepoint 0x00AD) which is supposed to be zero-width and invisible, and is used to mark a hyphenation possibility within a word in the absence of or overriding dictionary hyphenation. It is mostly an obsolete mechanism now, and the character is only included in fonts for legacy codepage coverage. [code: softhyphen]
* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: uni00AD	Contours detected: 1	Expected: 0

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: eogonek	Contours detected: 3	Expected: 2

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uni01E5	Contours detected: 3	Expected: 2

	- Glyph name: uni01EA	Contours detected: 3	Expected: 2

	- Glyph name: uni01EB	Contours detected: 3	Expected: 2

	- Glyph name: uni01EC	Contours detected: 4	Expected: 3

	- Glyph name: uni01ED	Contours detected: 4	Expected: 3 

	- And 41 more.

Use -F or --full-lists to disable shortening of long lists.
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check mark characters are in GDEF mark glyph class. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_mark_chars">com.google.fonts/check/gdef_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following mark characters could be in the GDEF mark glyph class:
	 uni0488 (U+0488), uni0489 (U+0489), uni1ABE (U+1ABE), uniA670 (U+A670), uniA671 (U+A671) and uniA672 (U+A672) [code: mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* Zpalatalhook (U+A7C6): L<<567.0,184.0>--<523.0,0.0>> -> L<<523.0,0.0>--<513.0,-36.0>>

	* beta (U+03B2): L<<-38.0,-240.0>--<42.0,119.0>> -> L<<42.0,119.0>--<127.0,534.0>>

	* rho (U+03C1): L<<-48.0,-240.0>--<32.0,113.0>> -> L<<32.0,113.0>--<60.0,249.0>>

	* uni03BC (U+03BC): L<<-35.0,-240.0>--<43.0,112.0>> -> L<<43.0,112.0>--<127.0,536.0>>

	* uni03FC (U+03FC): L<<-12.0,-80.0>--<32.0,113.0>> -> L<<32.0,113.0>--<60.0,249.0>>

	* uni1D0B (U+1D0B): L<<264.0,476.0>--<222.0,292.0>> -> L<<222.0,292.0>--<207.0,224.0>>

	* uni1D5D (U+1D5D): L<<3.0,143.0>--<54.0,358.0>> -> L<<54.0,358.0>--<110.0,607.0>>

	* uni1D66 (U+1D66): L<<-79.0,-240.0>--<-28.0,-25.0>> -> L<<-28.0,-25.0>--<28.0,224.0>>

	* uni1D68 (U+1D68): L<<-83.0,-240.0>--<-31.0,-28.0>> -> L<<-31.0,-28.0>--<-13.0,53.0>>

	* uni1DE9 (U+1DE9): L<<-50.0,586.0>--<-15.0,730.0>> -> L<<-15.0,730.0>--<24.0,895.0>>

	* uni1FE4 (U+1FE4): L<<-48.0,-240.0>--<32.0,113.0>> -> L<<32.0,113.0>--<60.0,249.0>> 

	* And uni1FE5 (U+1FE5): L<<-48.0,-240.0>--<32.0,113.0>> -> L<<32.0,113.0>--<60.0,249.0>> [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* Bbarredmod (U+1D2F): B<<425.0,552.5>-<393.0,526.0>-<340.0,517.0>>/L<<340.0,517.0>--<468.0,517.0>> = 9.637538112930923

	* Bbarredmod (U+1D2F): L<<465.0,507.0>--<347.0,507.0>>/B<<347.0,507.0>-<430.0,490.0>-<430.0,420.0>> = 11.575188817396182

	* Bbarredsmall (U+1D03): B<<520.0,423.0>-<520.0,310.0>-<373.0,286.0>>/L<<373.0,286.0>--<528.0,286.0>> = 9.272601777200284

	* Bbarredsmall (U+1D03): L<<526.0,276.0>--<370.0,276.0>>/B<<370.0,276.0>-<433.0,266.0>-<462.0,235.5>> = 9.019322431381651

	* Ereversedopen (U+A7AB): B<<452.0,399.0>-<392.0,376.0>-<320.0,369.0>>/B<<320.0,369.0>-<372.0,365.0>-<420.5,349.5>> = 9.951676388032272

	* three (U+0033): B<<472.0,443.0>-<406.0,389.0>-<287.0,374.0>>/B<<287.0,374.0>-<382.0,368.0>-<434.5,329.0>> = 10.798148144430469

	* uni00B5 (U+00B5): B<<116.5,24.5>-<79.0,59.0>-<77.0,134.0>>/B<<77.0,134.0>-<67.0,87.0>-<59.0,49.0>> = 13.539003828578338

	* uni024C (U+024C): L<<132.0,334.0>--<34.0,337.0>>/L<<34.0,337.0>--<78.0,344.0>> = 10.79288766342662

	* uni0377 (U+0377): B<<403.5,282.5>-<430.0,373.0>-<474.0,469.0>>/L<<474.0,469.0>--<111.0,0.0>> = 13.115847915308922

	* uni0417 (U+0417): B<<452.0,399.0>-<392.0,376.0>-<320.0,369.0>>/B<<320.0,369.0>-<372.0,365.0>-<420.5,349.5>> = 9.951676388032272 

	* And 29 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-jaggy-segments]
</div></details><br></div></details><details><summary><b>[17] NotoSerifDisplay-SemiBoldItalic.ttf</b></summary><div><details><summary>💔 <b>ERROR:</b> Check if the vertical metrics of a family are similar to the same family hosted on Google Fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vertical_metrics_regressions">com.google.fonts/check/vertical_metrics_regressions</a>)</summary><div>


* 💔 **ERROR** Failed with TypeError: 'NoneType' object is not subscriptable
</div></details><details><summary>🔥 <b>FAIL:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* 🔥 **FAIL** Missing required codepoints:

	- 0x2212 (MINUS SIGN)
 

	- And 0x00AF (MACRON)
 [code: missing-codepoints]
</div></details><details><summary>🔥 <b>FAIL:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* 🔥 **FAIL** License file OFL.txt exists but NameID 13 (LICENSE DESCRIPTION) value on platform 3 (WINDOWS) is not specified for that. Value was: "This Font Software is licensed under the SIL Open Font License, Version 1.1. This Font Software is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the SIL Open Font License for the specific language, permissions and limitations governing your use of this Font Software." Must be changed to "This Font Software is licensed under the SIL Open Font License, Version 1.1. This license is available with a FAQ at: https://scripts.sil.org/OFL" [code: wrong]
</div></details><details><summary>🔥 <b>FAIL:</b> Copyright notices match canonical pattern in fonts (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/font_copyright">com.google.fonts/check/font_copyright</a>)</summary><div>


* 🔥 **FAIL** Name Table entry: Copyright notices should match a pattern similar to: "Copyright 2019 The Familyname Project Authors (git url)"
But instead we have got:
"Copyright 2016-2021 Google Inc. All Rights Reserved." [code: bad-notice-format]
</div></details><details><summary>🔥 <b>FAIL:</b> OS/2.fsSelection bit 7 (USE_TYPO_METRICS) is set in all fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/os2/use_typo_metrics">com.google.fonts/check/os2/use_typo_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2.fsSelection bit 7 (USE_TYPO_METRICS) wasNOT set in the following fonts: ['fonts/NotoSerifDisplay-Italic/googlefonts/slim-variable-ttf/NotoSerifDisplay-ItalicMM[wght].ttf', 'fonts/NotoSerifDisplay-Italic/googlefonts/ttf/NotoSerifDisplay-BlackItalic.ttf', 'fonts/NotoSerifDisplay-Italic/googlefonts/ttf/NotoSerifDisplay-BoldItalic.ttf', 'fonts/NotoSerifDisplay-Italic/googlefonts/ttf/NotoSerifDisplay-ExtraBoldItalic.ttf', 'fonts/NotoSerifDisplay-Italic/googlefonts/ttf/NotoSerifDisplay-ExtraLightItalic.ttf', 'fonts/NotoSerifDisplay-Italic/googlefonts/ttf/NotoSerifDisplay-Italic.ttf', 'fonts/NotoSerifDisplay-Italic/googlefonts/ttf/NotoSerifDisplay-LightItalic.ttf', 'fonts/NotoSerifDisplay-Italic/googlefonts/ttf/NotoSerifDisplay-MediumItalic.ttf', 'fonts/NotoSerifDisplay-Italic/googlefonts/ttf/NotoSerifDisplay-SemiBoldItalic.ttf', 'fonts/NotoSerifDisplay-Italic/googlefonts/ttf/NotoSerifDisplay-ThinItalic.ttf', 'fonts/NotoSerifDisplay-Italic/googlefonts/variable-ttf/NotoSerifDisplay-ItalicMM[wdth,wght].ttf']. [code: missing-os2-fsselection-bit7]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinAscent value should be equal or greater than 1143, but got 1069 instead [code: ascent]
* 🔥 **FAIL** OS/2.usWinDescent value should be equal or greater than 470, but got 293 instead. [code: descent]
</div></details><details><summary>⚠ <b>WARN:</b> Glyphs are similiar to Google Fonts version? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/production_glyphs_similarity">com.google.fonts/check/production_glyphs_similarity</a>)</summary><div>


* ⚠ **WARN** Following glyphs differ greatly from Google Fonts version:
	* pi
	* uni1F57
	* uni0424
	* four.lf
	* uni0278
	* uni1F62
	* uni1FE0
	* uni1F92
	* uni1FA5
	* uni1FC2 and 145 more.

Use -F or --full-lists to disable shortening of long lists.
</div></details><details><summary>⚠ <b>WARN:</b> Is there kerning info for non-ligated sequences? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/kerning_for_non_ligated_sequences">com.google.fonts/check/kerning_for_non_ligated_sequences</a>)</summary><div>


* ⚠ **WARN** GPOS table lacks kerning info for the following non-ligated sequences:

	- f + f

	- f + i

	- i + f

	- f + l

	- l + f

	- i + l

	- f.ss02 + f.ss02

	- f.ss02 + i

	- i + f.ss02

	- f.ss02 + l 

	- And l + f.ss02 [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Noto Serif Display SemiBold' / SUBFAMILY_NAME = 'Italic'

Please take a look at the conversation at https://github.com/googlefonts/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure Stylistic Sets have description. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/stylisticset_description">com.google.fonts/check/stylisticset_description</a>)</summary><div>


* ⚠ **WARN** The stylistic set ss01 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss02 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss03 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss06 lacks a description string on the 'name' table. [code: missing-description]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Glyph names are all valid? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/valid_glyphnames">com.google.fonts/check/valid_glyphnames</a>)</summary><div>


* ⚠ **WARN** The following glyph names may be too long for some legacy systems which may expect a maximum 31-char length limit:
kavykawithkavykaaboveinvertedlow [code: legacy-long-names]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- uni1FCE0306

	- dasiavaria_macronmod

	- uni1FCD0306

	- uni03B1030603140301

	- uni1FCE02C9

	- dasiaoxia_macronmod

	- beta.alt1

	- uni03B9030803040300

	- uni03C5030603140301

	- uni03C5030603130301 

	- And 35 more.

Use -F or --full-lists to disable shortening of long lists.
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character (codepoint 0x00AD) which is supposed to be zero-width and invisible, and is used to mark a hyphenation possibility within a word in the absence of or overriding dictionary hyphenation. It is mostly an obsolete mechanism now, and the character is only included in fonts for legacy codepage coverage. [code: softhyphen]
* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: uni00AD	Contours detected: 1	Expected: 0

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: eogonek	Contours detected: 3	Expected: 2

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uni01E5	Contours detected: 3	Expected: 2

	- Glyph name: uni01EA	Contours detected: 3	Expected: 2

	- Glyph name: uni01EB	Contours detected: 3	Expected: 2

	- Glyph name: uni01EC	Contours detected: 4	Expected: 3

	- Glyph name: uni01ED	Contours detected: 4	Expected: 3 

	- And 41 more.

Use -F or --full-lists to disable shortening of long lists.
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check mark characters are in GDEF mark glyph class. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_mark_chars">com.google.fonts/check/gdef_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following mark characters could be in the GDEF mark glyph class:
	 uni0488 (U+0488), uni0489 (U+0489), uni1ABE (U+1ABE), uniA670 (U+A670), uniA671 (U+A671) and uniA672 (U+A672) [code: mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* Zpalatalhook (U+A7C6): L<<587.0,194.0>--<542.0,0.0>> -> L<<542.0,0.0>--<533.0,-34.0>>

	* beta (U+03B2): L<<-37.0,-240.0>--<43.0,122.0>> -> L<<43.0,122.0>--<126.0,530.0>>

	* rho (U+03C1): L<<-48.0,-240.0>--<32.0,117.0>> -> L<<32.0,117.0>--<60.0,255.0>>

	* uni03BC (U+03BC): L<<-34.0,-240.0>--<39.0,94.0>> -> L<<39.0,94.0>--<127.0,536.0>>

	* uni03FC (U+03FC): L<<-12.0,-81.0>--<32.0,117.0>> -> L<<32.0,117.0>--<60.0,255.0>>

	* uni1D0B (U+1D0B): L<<285.0,478.0>--<244.0,296.0>> -> L<<244.0,296.0>--<230.0,234.0>>

	* uni1D5D (U+1D5D): L<<6.0,143.0>--<58.0,360.0>> -> L<<58.0,360.0>--<112.0,605.0>>

	* uni1D66 (U+1D66): L<<-76.0,-240.0>--<-24.0,-23.0>> -> L<<-24.0,-23.0>--<30.0,222.0>>

	* uni1D68 (U+1D68): L<<-83.0,-240.0>--<-31.0,-26.0>> -> L<<-31.0,-26.0>--<-13.0,57.0>>

	* uni1DE9 (U+1DE9): L<<-52.0,586.0>--<-16.0,731.0>> -> L<<-16.0,731.0>--<22.0,894.0>> 

	* And 3 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* Bbarredmod (U+1D2F): B<<435.0,553.5>-<404.0,527.0>-<349.0,517.0>>/L<<349.0,517.0>--<477.0,517.0>> = 10.304846468766044

	* Bbarredmod (U+1D2F): L<<476.0,507.0>--<351.0,507.0>>/B<<351.0,507.0>-<439.0,491.0>-<439.0,419.0>> = 10.304846468766044

	* Bbarredsmall (U+1D03): B<<537.0,424.0>-<537.0,311.0>-<385.0,287.0>>/L<<385.0,287.0>--<552.0,287.0>> = 8.972626614896358

	* Bbarredsmall (U+1D03): L<<549.0,277.0>--<382.0,277.0>>/B<<382.0,277.0>-<446.0,267.0>-<476.0,237.5>> = 8.880659150520234

	* Ereversedopen (U+A7AB): B<<457.0,402.0>-<395.0,379.0>-<321.0,371.0>>/B<<321.0,371.0>-<383.0,366.0>-<433.5,350.5>> = 10.780824413690203

	* hardsigntallcy (U+1C86): B<<302.5,616.0>-<373.0,685.0>-<449.0,739.0>>/B<<449.0,739.0>-<424.0,729.0>-<379.5,722.5>> = 13.593386358635234

	* iotifiedbigyuscombcy (U+2DFF): B<<38.5,688.5>-<50.0,697.0>-<68.0,701.0>>/L<<68.0,701.0>--<-38.0,701.0>> = 12.528807709151492

	* three (U+0033): B<<422.5,408.5>-<363.0,383.0>-<285.0,374.0>>/B<<285.0,374.0>-<389.0,366.0>-<443.5,330.0>> = 10.980650010173553

	* uni024C (U+024C): L<<89.0,336.0>--<39.0,342.0>>/L<<39.0,342.0>--<135.0,346.0>> = 9.228717443019724

	* uni0377 (U+0377): B<<412.0,279.5>-<438.0,362.0>-<476.0,439.0>>/L<<476.0,439.0>--<124.0,0.0>> = 12.456778840635982 

	* And 32 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-jaggy-segments]
</div></details><br></div></details><details><summary><b>[17] NotoSerifDisplay-ThinItalic.ttf</b></summary><div><details><summary>💔 <b>ERROR:</b> Check if the vertical metrics of a family are similar to the same family hosted on Google Fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vertical_metrics_regressions">com.google.fonts/check/vertical_metrics_regressions</a>)</summary><div>


* 💔 **ERROR** Failed with TypeError: 'NoneType' object is not subscriptable
</div></details><details><summary>🔥 <b>FAIL:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* 🔥 **FAIL** Missing required codepoints:

	- 0x2212 (MINUS SIGN)
 

	- And 0x00AF (MACRON)
 [code: missing-codepoints]
</div></details><details><summary>🔥 <b>FAIL:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* 🔥 **FAIL** License file OFL.txt exists but NameID 13 (LICENSE DESCRIPTION) value on platform 3 (WINDOWS) is not specified for that. Value was: "This Font Software is licensed under the SIL Open Font License, Version 1.1. This Font Software is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the SIL Open Font License for the specific language, permissions and limitations governing your use of this Font Software." Must be changed to "This Font Software is licensed under the SIL Open Font License, Version 1.1. This license is available with a FAQ at: https://scripts.sil.org/OFL" [code: wrong]
</div></details><details><summary>🔥 <b>FAIL:</b> Copyright notices match canonical pattern in fonts (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/font_copyright">com.google.fonts/check/font_copyright</a>)</summary><div>


* 🔥 **FAIL** Name Table entry: Copyright notices should match a pattern similar to: "Copyright 2019 The Familyname Project Authors (git url)"
But instead we have got:
"Copyright 2016-2021 Google Inc. All Rights Reserved." [code: bad-notice-format]
</div></details><details><summary>🔥 <b>FAIL:</b> OS/2.fsSelection bit 7 (USE_TYPO_METRICS) is set in all fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/os2/use_typo_metrics">com.google.fonts/check/os2/use_typo_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2.fsSelection bit 7 (USE_TYPO_METRICS) wasNOT set in the following fonts: ['fonts/NotoSerifDisplay-Italic/googlefonts/slim-variable-ttf/NotoSerifDisplay-ItalicMM[wght].ttf', 'fonts/NotoSerifDisplay-Italic/googlefonts/ttf/NotoSerifDisplay-BlackItalic.ttf', 'fonts/NotoSerifDisplay-Italic/googlefonts/ttf/NotoSerifDisplay-BoldItalic.ttf', 'fonts/NotoSerifDisplay-Italic/googlefonts/ttf/NotoSerifDisplay-ExtraBoldItalic.ttf', 'fonts/NotoSerifDisplay-Italic/googlefonts/ttf/NotoSerifDisplay-ExtraLightItalic.ttf', 'fonts/NotoSerifDisplay-Italic/googlefonts/ttf/NotoSerifDisplay-Italic.ttf', 'fonts/NotoSerifDisplay-Italic/googlefonts/ttf/NotoSerifDisplay-LightItalic.ttf', 'fonts/NotoSerifDisplay-Italic/googlefonts/ttf/NotoSerifDisplay-MediumItalic.ttf', 'fonts/NotoSerifDisplay-Italic/googlefonts/ttf/NotoSerifDisplay-SemiBoldItalic.ttf', 'fonts/NotoSerifDisplay-Italic/googlefonts/ttf/NotoSerifDisplay-ThinItalic.ttf', 'fonts/NotoSerifDisplay-Italic/googlefonts/variable-ttf/NotoSerifDisplay-ItalicMM[wdth,wght].ttf']. [code: missing-os2-fsselection-bit7]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinAscent value should be equal or greater than 1143, but got 1069 instead [code: ascent]
* 🔥 **FAIL** OS/2.usWinDescent value should be equal or greater than 470, but got 293 instead. [code: descent]
</div></details><details><summary>⚠ <b>WARN:</b> Glyphs are similiar to Google Fonts version? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/production_glyphs_similarity">com.google.fonts/check/production_glyphs_similarity</a>)</summary><div>


* ⚠ **WARN** Following glyphs differ greatly from Google Fonts version:
	* uni1F57
	* uni1F62
	* uni1FA5
	* uni1FF6
	* uni1FA8
	* uni1F9D
	* uni1FA6
	* uni1F8D
	* uni1F64
	* uni1F9A and 65 more.

Use -F or --full-lists to disable shortening of long lists.
</div></details><details><summary>⚠ <b>WARN:</b> Is there kerning info for non-ligated sequences? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/kerning_for_non_ligated_sequences">com.google.fonts/check/kerning_for_non_ligated_sequences</a>)</summary><div>


* ⚠ **WARN** GPOS table lacks kerning info for the following non-ligated sequences:

	- f + f

	- f + i

	- i + f

	- f + l

	- l + f

	- i + l

	- f.ss02 + f.ss02

	- f.ss02 + i

	- i + f.ss02

	- f.ss02 + l 

	- And l + f.ss02 [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Noto Serif Display Thin' / SUBFAMILY_NAME = 'Italic'

Please take a look at the conversation at https://github.com/googlefonts/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure Stylistic Sets have description. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/stylisticset_description">com.google.fonts/check/stylisticset_description</a>)</summary><div>


* ⚠ **WARN** The stylistic set ss01 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss02 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss03 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss06 lacks a description string on the 'name' table. [code: missing-description]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Glyph names are all valid? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/valid_glyphnames">com.google.fonts/check/valid_glyphnames</a>)</summary><div>


* ⚠ **WARN** The following glyph names may be too long for some legacy systems which may expect a maximum 31-char length limit:
kavykawithkavykaaboveinvertedlow [code: legacy-long-names]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- uni1FCE0306

	- dasiavaria_macronmod

	- uni1FCD0306

	- uni03B1030603140301

	- uni1FCE02C9

	- dasiaoxia_macronmod

	- beta.alt1

	- uni03B9030803040300

	- uni03C5030603140301

	- uni03C5030603130301 

	- And 35 more.

Use -F or --full-lists to disable shortening of long lists.
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character (codepoint 0x00AD) which is supposed to be zero-width and invisible, and is used to mark a hyphenation possibility within a word in the absence of or overriding dictionary hyphenation. It is mostly an obsolete mechanism now, and the character is only included in fonts for legacy codepage coverage. [code: softhyphen]
* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: uni00AD	Contours detected: 1	Expected: 0

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: eogonek	Contours detected: 3	Expected: 2

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uni01E5	Contours detected: 3	Expected: 2

	- Glyph name: uni01EA	Contours detected: 3	Expected: 2

	- Glyph name: uni01EB	Contours detected: 3	Expected: 2

	- Glyph name: uni01EC	Contours detected: 4	Expected: 3

	- Glyph name: uni01ED	Contours detected: 4	Expected: 3 

	- And 39 more.

Use -F or --full-lists to disable shortening of long lists.
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check mark characters are in GDEF mark glyph class. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_mark_chars">com.google.fonts/check/gdef_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following mark characters could be in the GDEF mark glyph class:
	 uni0488 (U+0488), uni0489 (U+0489), uni1ABE (U+1ABE), uniA670 (U+A670), uniA671 (U+A671) and uniA672 (U+A672) [code: mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* Zpalatalhook (U+A7C6): L<<478.0,134.0>--<444.0,0.0>> -> L<<444.0,0.0>--<422.0,-81.0>>

	* beta (U+03B2): L<<-38.0,-240.0>--<39.0,118.0>> -> L<<39.0,118.0>--<134.0,565.0>>

	* estecombcy (U+2DF5): L<<166.0,777.0>--<166.0,777.0>> -> L<<166.0,777.0>--<167.0,777.0>>

	* rho (U+03C1): L<<-48.0,-240.0>--<15.0,51.0>> -> L<<15.0,51.0>--<66.0,296.0>>

	* tripledagger (U+2E4B): L<<48.0,341.0>--<206.0,331.0>> -> L<<206.0,331.0>--<206.0,331.0>>

	* uni03BC (U+03BC): L<<-37.0,-240.0>--<44.0,136.0>> -> L<<44.0,136.0>--<127.0,536.0>>

	* uni03FC (U+03FC): L<<-16.0,-90.0>--<15.0,51.0>> -> L<<15.0,51.0>--<66.0,296.0>>

	* uni1D0B (U+1D0B): L<<161.0,461.0>--<122.0,277.0>> -> L<<122.0,277.0>--<109.0,216.0>>

	* uni1D5D (U+1D5D): L<<-13.0,143.0>--<37.0,358.0>> -> L<<37.0,358.0>--<99.0,626.0>>

	* uni1D66 (U+1D66): L<<-94.0,-240.0>--<-44.0,-25.0>> -> L<<-44.0,-25.0>--<18.0,243.0>> 

	* And 5 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* Bbarredmod (U+1D2F): B<<388.0,552.5>-<362.0,526.0>-<319.0,517.0>>/L<<319.0,517.0>--<430.0,517.0>> = 11.821488340607226

	* Bbarredsmall (U+1D03): B<<409.5,332.5>-<377.0,299.0>-<322.0,287.0>>/L<<322.0,287.0>--<455.0,287.0>> = 12.308015817427924

	* Bbarredsmall (U+1D03): L<<452.0,277.0>--<309.0,277.0>>/B<<309.0,277.0>-<338.0,271.0>-<362.5,259.5>> = 11.689369175439202

	* iotifiedbigyuscombcy (U+2DFF): B<<66.0,693.0>-<74.0,696.0>-<87.0,698.0>>/L<<87.0,698.0>--<-14.0,698.0>> = 8.746162262555211

	* kacombcy (U+2DE6): B<<91.0,706.0>-<79.0,696.0>-<66.0,694.0>>/B<<66.0,694.0>-<91.0,694.0>-<101.5,686.0>> = 8.746162262555211

	* three (U+0033): B<<383.5,410.0>-<343.0,383.0>-<291.0,377.0>>/B<<291.0,377.0>-<325.0,373.0>-<354.5,353.5>> = 13.291781462934923

	* uni024A (U+024A): B<<501.5,670.5>-<549.0,616.0>-<552.0,498.0>>/L<<552.0,498.0>--<597.0,714.0>> = 13.22464756636032

	* uni024A (U+024A): L<<431.0,-64.0>--<487.0,197.0>>/B<<487.0,197.0>-<442.0,82.0>-<381.0,34.5>> = 9.260874146228073

	* uni0275 (U+0275): L<<73.0,268.0>--<73.0,270.0>>/B<<73.0,270.0>-<66.0,229.0>-<66.0,190.0>> = 9.68878656036679

	* uni0432 (U+0432): B<<335.0,317.0>-<287.0,298.0>-<233.0,290.0>>/B<<233.0,290.0>-<313.0,282.0>-<362.5,251.0>> = 14.137562158980275 

	* And 35 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-jaggy-segments]
</div></details><br></div></details><details><summary><b>[18] NotoSerifDisplay-ItalicMM[wdth,wght].ttf</b></summary><div><details><summary>💔 <b>ERROR:</b> Check if the vertical metrics of a family are similar to the same family hosted on Google Fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vertical_metrics_regressions">com.google.fonts/check/vertical_metrics_regressions</a>)</summary><div>


* 💔 **ERROR** Failed with TypeError: 'NoneType' object is not subscriptable
</div></details><details><summary>🔥 <b>FAIL:</b> Checking file is named canonically. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/canonical_filename">com.google.fonts/check/canonical_filename</a>)</summary><div>


* 🔥 **FAIL** The file 'NotoSerifDisplay-ItalicMM[wdth,wght].ttf' must be renamed to 'NotoSerifDisplay-Italic[wdth,wght].ttf' according to the Google Fonts naming policy for variable fonts. [code: bad-varfont-filename]
</div></details><details><summary>🔥 <b>FAIL:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* 🔥 **FAIL** Missing required codepoints:

	- 0x2212 (MINUS SIGN)
 

	- And 0x00AF (MACRON)
 [code: missing-codepoints]
</div></details><details><summary>🔥 <b>FAIL:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* 🔥 **FAIL** License file OFL.txt exists but NameID 13 (LICENSE DESCRIPTION) value on platform 3 (WINDOWS) is not specified for that. Value was: "This Font Software is licensed under the SIL Open Font License, Version 1.1. This Font Software is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the SIL Open Font License for the specific language, permissions and limitations governing your use of this Font Software." Must be changed to "This Font Software is licensed under the SIL Open Font License, Version 1.1. This license is available with a FAQ at: https://scripts.sil.org/OFL" [code: wrong]
</div></details><details><summary>🔥 <b>FAIL:</b> Copyright notices match canonical pattern in fonts (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/font_copyright">com.google.fonts/check/font_copyright</a>)</summary><div>


* 🔥 **FAIL** Name Table entry: Copyright notices should match a pattern similar to: "Copyright 2019 The Familyname Project Authors (git url)"
But instead we have got:
"Copyright 2016-2021 Google Inc. All Rights Reserved." [code: bad-notice-format]
</div></details><details><summary>🔥 <b>FAIL:</b> OS/2.fsSelection bit 7 (USE_TYPO_METRICS) is set in all fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/os2/use_typo_metrics">com.google.fonts/check/os2/use_typo_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2.fsSelection bit 7 (USE_TYPO_METRICS) wasNOT set in the following fonts: ['fonts/NotoSerifDisplay-Italic/googlefonts/slim-variable-ttf/NotoSerifDisplay-ItalicMM[wght].ttf', 'fonts/NotoSerifDisplay-Italic/googlefonts/ttf/NotoSerifDisplay-BlackItalic.ttf', 'fonts/NotoSerifDisplay-Italic/googlefonts/ttf/NotoSerifDisplay-BoldItalic.ttf', 'fonts/NotoSerifDisplay-Italic/googlefonts/ttf/NotoSerifDisplay-ExtraBoldItalic.ttf', 'fonts/NotoSerifDisplay-Italic/googlefonts/ttf/NotoSerifDisplay-ExtraLightItalic.ttf', 'fonts/NotoSerifDisplay-Italic/googlefonts/ttf/NotoSerifDisplay-Italic.ttf', 'fonts/NotoSerifDisplay-Italic/googlefonts/ttf/NotoSerifDisplay-LightItalic.ttf', 'fonts/NotoSerifDisplay-Italic/googlefonts/ttf/NotoSerifDisplay-MediumItalic.ttf', 'fonts/NotoSerifDisplay-Italic/googlefonts/ttf/NotoSerifDisplay-SemiBoldItalic.ttf', 'fonts/NotoSerifDisplay-Italic/googlefonts/ttf/NotoSerifDisplay-ThinItalic.ttf', 'fonts/NotoSerifDisplay-Italic/googlefonts/variable-ttf/NotoSerifDisplay-ItalicMM[wdth,wght].ttf']. [code: missing-os2-fsselection-bit7]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinAscent value should be equal or greater than 1143, but got 1069 instead [code: ascent]
* 🔥 **FAIL** OS/2.usWinDescent value should be equal or greater than 470, but got 293 instead. [code: descent]
</div></details><details><summary>🔥 <b>FAIL:</b> The variable font 'wght' (Weight) axis coordinate must be 400 on the 'Regular' instance. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/fvar.html#com.google.fonts/check/varfont/regular_wght_coord">com.google.fonts/check/varfont/regular_wght_coord</a>)</summary><div>


* 🔥 **FAIL** The "wght" axis coordinate of the "Regular" instance must be 400. Got None instead. [code: wght-not-400]
</div></details><details><summary>🔥 <b>FAIL:</b> The variable font 'wdth' (Width) axis coordinate must be 100 on the 'Regular' instance. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/fvar.html#com.google.fonts/check/varfont/regular_wdth_coord">com.google.fonts/check/varfont/regular_wdth_coord</a>)</summary><div>


* 🔥 **FAIL** The "wdth" axis coordinate of the "Regular" instance must be 100. Got None as a default value instead. [code: wdth-not-100]
</div></details><details><summary>🔥 <b>FAIL:</b> The variable font 'wght' (Weight) axis coordinate must be 700 on the 'Bold' instance. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/fvar.html#com.google.fonts/check/varfont/bold_wght_coord">com.google.fonts/check/varfont/bold_wght_coord</a>)</summary><div>


* 🔥 **FAIL** The "wght" axis coordinate of the "Bold" instance must be 700. Got None instead. [code: wght-not-700]
</div></details><details><summary>🔥 <b>FAIL:</b> Validates that when an instance record is included for the default instance, its subfamilyNameID value is set to either 2 or 17, and its postScriptNameID value is set to 6. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/fvar.html#com.adobe.fonts/check/varfont/valid_default_instance_nameids">com.adobe.fonts/check/varfont/valid_default_instance_nameids</a>)</summary><div>


* 🔥 **FAIL** 'Italic' instance has the same coordinates as the default instance; its subfamilyNameID should be either 2 or 17, instead of 293. [code: invalid-default-instance-subfamily-nameid:293]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure files are not too large. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/file_size">com.google.fonts/check/file_size</a>)</summary><div>


* ⚠ **WARN** Font file is 2.2Mb; ideally it should be less than 1.0Mb [code: large-font]
</div></details><details><summary>⚠ <b>WARN:</b> Is there kerning info for non-ligated sequences? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/kerning_for_non_ligated_sequences">com.google.fonts/check/kerning_for_non_ligated_sequences</a>)</summary><div>


* ⚠ **WARN** GPOS table lacks kerning info for the following non-ligated sequences:

	- f + f

	- f + i

	- i + f

	- f + l

	- l + f

	- i + l

	- f.ss02 + f.ss02

	- f.ss02 + i

	- i + f.ss02

	- f.ss02 + l 

	- And l + f.ss02 [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure Stylistic Sets have description. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/stylisticset_description">com.google.fonts/check/stylisticset_description</a>)</summary><div>


* ⚠ **WARN** The stylistic set ss01 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss02 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss03 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss06 lacks a description string on the 'name' table. [code: missing-description]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Glyph names are all valid? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/valid_glyphnames">com.google.fonts/check/valid_glyphnames</a>)</summary><div>


* ⚠ **WARN** The following glyph names may be too long for some legacy systems which may expect a maximum 31-char length limit:
kavykawithkavykaaboveinvertedlow [code: legacy-long-names]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- uni1FCE0306

	- dasiavaria_macronmod

	- uni1FCD0306

	- uni03B1030603140301

	- uni1FCE02C9

	- dasiaoxia_macronmod

	- beta.alt1

	- uni03B9030803040300

	- uni03C5030603140301

	- uni03C5030603130301 

	- And 35 more.

Use -F or --full-lists to disable shortening of long lists.
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check mark characters are in GDEF mark glyph class. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_mark_chars">com.google.fonts/check/gdef_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following mark characters could be in the GDEF mark glyph class:
	 uni0488 (U+0488), uni0489 (U+0489), uni1ABE (U+1ABE), uniA670 (U+A670), uniA671 (U+A671) and uniA672 (U+A672) [code: mark-chars]
</div></details><br></div></details>
### Summary

| 💔 ERROR | 🔥 FAIL | ⚠ WARN | 💤 SKIP | ℹ INFO | 🍞 PASS | 🔎 DEBUG |
|:-----:|:----:|:----:|:----:|:----:|:----:|:----:|
| 11 | 81 | 113 | 1229 | 76 | 925 | 0 |
| 0% | 3% | 5% | 50% | 3% | 38% | 0% |

**Note:** The following loglevels were omitted in this report:
* **SKIP**
* **INFO**
* **PASS**
* **DEBUG**
