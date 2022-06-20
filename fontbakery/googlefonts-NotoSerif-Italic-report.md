## Fontbakery report

Fontbakery version: 0.8.9

<details><summary><b>[4] Family checks</b></summary><div><details><summary>🔥 <b>FAIL:</b> Ensure that all variable font files have the same set of axes and axis ranges. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/varfont/consistent_axes">com.google.fonts/check/varfont/consistent_axes</a>)</summary><div>


* 🔥 **FAIL** NotoSerif-ItalicMM[wght].ttf: lacks a 'CTGR' variation axis. [code: missing-axis]
* 🔥 **FAIL** NotoSerif-ItalicMM[wdth,wght].ttf: lacks a 'CTGR' variation axis. [code: missing-axis]
</div></details><details><summary>🔥 <b>FAIL:</b> Ensure Italic styles have Roman counterparts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/family/italics_have_roman_counterparts">com.google.fonts/check/family/italics_have_roman_counterparts</a>)</summary><div>


* 🔥 **FAIL** Italics missing a Roman counterpart: fonts/NotoSerif-Italic/googlefonts/slim-variable-ttf/NotoSerif-ItalicMM[wght].ttf, fonts/NotoSerif-Italic/googlefonts/slim-variable-ttf/NotoSerif-MM[wght].ttf, fonts/NotoSerif-Italic/googlefonts/ttf/NotoSerif-Black.ttf, fonts/NotoSerif-Italic/googlefonts/ttf/NotoSerif-BlackItalic.ttf, fonts/NotoSerif-Italic/googlefonts/ttf/NotoSerif-Bold.ttf, fonts/NotoSerif-Italic/googlefonts/ttf/NotoSerif-BoldItalic.ttf, fonts/NotoSerif-Italic/googlefonts/ttf/NotoSerif-ExtraBold.ttf, fonts/NotoSerif-Italic/googlefonts/ttf/NotoSerif-ExtraBoldItalic.ttf, fonts/NotoSerif-Italic/googlefonts/ttf/NotoSerif-ExtraLight.ttf, fonts/NotoSerif-Italic/googlefonts/ttf/NotoSerif-ExtraLightItalic.ttf and 12 more.

Use -F or --full-lists to disable shortening of long lists. [code: missing-roman]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking all files are in the same directory. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/single_directory">com.google.fonts/check/family/single_directory</a>)</summary><div>


* 🔥 **FAIL** Not all fonts passed in the command line are in the same directory. This may lead to bad results as the tool will interpret all font files as belonging to a single font family. The detected directories are: ['fonts/NotoSerif-Italic/googlefonts/slim-variable-ttf', 'fonts/NotoSerif-Italic/googlefonts/ttf', 'fonts/NotoSerif-Italic/googlefonts/variable-ttf'] [code: single-directory]
</div></details><details><summary>🔥 <b>FAIL:</b> Verify that each group of fonts with the same nameID 1 has maximum of 4 fonts (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/name.html#com.adobe.fonts/check/family/max_4_fonts_per_family_name">com.adobe.fonts/check/family/max_4_fonts_per_family_name</a>)</summary><div>


* 🔥 **FAIL** Family 'Noto Serif' has 5 fonts (should be 4 or fewer). [code: too-many]
</div></details><br></div></details><details><summary><b>[20] NotoSerif-ItalicMM[wght].ttf</b></summary><div><details><summary>💔 <b>ERROR:</b> STAT table has Axis Value tables? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/stat.html#com.adobe.fonts/check/stat_has_axis_value_tables">com.adobe.fonts/check/stat_has_axis_value_tables</a>)</summary><div>


* 💔 **ERROR** Failed with AttributeError: 'NoneType' object has no attribute 'AxisValue'
</div></details><details><summary>🔥 <b>FAIL:</b> Checking file is named canonically. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/canonical_filename">com.google.fonts/check/canonical_filename</a>)</summary><div>


* 🔥 **FAIL** The file 'NotoSerif-ItalicMM[wght].ttf' must be renamed to 'NotoSerif-Italic[wdth,wght].ttf' according to the Google Fonts naming policy for variable fonts. [code: bad-varfont-filename]
</div></details><details><summary>🔥 <b>FAIL:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* 🔥 **FAIL** Missing required codepoints:

	- 0x00AF (MACRON)
 [code: missing-codepoints]
</div></details><details><summary>🔥 <b>FAIL:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* 🔥 **FAIL** License file OFL.txt exists but NameID 13 (LICENSE DESCRIPTION) value on platform 3 (WINDOWS) is not specified for that. Value was: "This Font Software is licensed under the SIL Open Font License, Version 1.1. This Font Software is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the SIL Open Font License for the specific language, permissions and limitations governing your use of this Font Software." Must be changed to "This Font Software is licensed under the SIL Open Font License, Version 1.1. This license is available with a FAQ at: https://scripts.sil.org/OFL" [code: wrong]
</div></details><details><summary>🔥 <b>FAIL:</b> Is the Grid-fitting and Scan-conversion Procedure ('gasp') table set to optimize rendering? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/gasp">com.google.fonts/check/gasp</a>)</summary><div>


* 🔥 **FAIL** Font is missing the 'gasp' table. Try exporting the font with autohinting enabled.
If you are dealing with an unhinted font, it can be fixed by running the fonts through the command 'gftools fix-nonhinting'
GFTools is available at https://pypi.org/project/gftools/ [code: lacks-gasp]
</div></details><details><summary>🔥 <b>FAIL:</b> Font enables smart dropout control in "prep" table instructions? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/smart_dropout">com.google.fonts/check/smart_dropout</a>)</summary><div>


* 🔥 **FAIL** The 'prep' table does not contain TrueType instructions enabling smart dropout control. To fix, export the font with autohinting enabled, or run ttfautohint on the font, or run the `gftools fix-nonhinting` script. [code: lacks-smart-dropout]
</div></details><details><summary>🔥 <b>FAIL:</b> Validate STAT particle names and values match the fallback names in GFAxisRegistry.  (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/STAT/gf-axisregistry">com.google.fonts/check/STAT/gf-axisregistry</a>)</summary><div>


* 🔥 **FAIL** STAT table is missing Axis Value Records [code: missing-axis-values]
</div></details><details><summary>🔥 <b>FAIL:</b> OS/2.fsSelection bit 7 (USE_TYPO_METRICS) is set in all fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/os2/use_typo_metrics">com.google.fonts/check/os2/use_typo_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2.fsSelection bit 7 (USE_TYPO_METRICS) wasNOT set in the following fonts: ['fonts/NotoSerif-Italic/googlefonts/slim-variable-ttf/NotoSerif-ItalicMM[wght].ttf', 'fonts/NotoSerif-Italic/googlefonts/slim-variable-ttf/NotoSerif-MM[wght].ttf', 'fonts/NotoSerif-Italic/googlefonts/ttf/NotoSerif-Black.ttf', 'fonts/NotoSerif-Italic/googlefonts/ttf/NotoSerif-BlackItalic.ttf', 'fonts/NotoSerif-Italic/googlefonts/ttf/NotoSerif-Bold.ttf', 'fonts/NotoSerif-Italic/googlefonts/ttf/NotoSerif-BoldItalic.ttf', 'fonts/NotoSerif-Italic/googlefonts/ttf/NotoSerif-ExtraBold.ttf', 'fonts/NotoSerif-Italic/googlefonts/ttf/NotoSerif-ExtraBoldItalic.ttf', 'fonts/NotoSerif-Italic/googlefonts/ttf/NotoSerif-ExtraLight.ttf', 'fonts/NotoSerif-Italic/googlefonts/ttf/NotoSerif-ExtraLightItalic.ttf', 'fonts/NotoSerif-Italic/googlefonts/ttf/NotoSerif-Italic.ttf', 'fonts/NotoSerif-Italic/googlefonts/ttf/NotoSerif-Light.ttf', 'fonts/NotoSerif-Italic/googlefonts/ttf/NotoSerif-LightItalic.ttf', 'fonts/NotoSerif-Italic/googlefonts/ttf/NotoSerif-Medium.ttf', 'fonts/NotoSerif-Italic/googlefonts/ttf/NotoSerif-MediumItalic.ttf', 'fonts/NotoSerif-Italic/googlefonts/ttf/NotoSerif-Regular.ttf', 'fonts/NotoSerif-Italic/googlefonts/ttf/NotoSerif-SemiBold.ttf', 'fonts/NotoSerif-Italic/googlefonts/ttf/NotoSerif-SemiBoldItalic.ttf', 'fonts/NotoSerif-Italic/googlefonts/ttf/NotoSerif-Thin.ttf', 'fonts/NotoSerif-Italic/googlefonts/ttf/NotoSerif-ThinItalic.ttf', 'fonts/NotoSerif-Italic/googlefonts/variable-ttf/NotoSerif-ItalicMM[wdth,wght].ttf', 'fonts/NotoSerif-Italic/googlefonts/variable-ttf/NotoSerif-MM[CTGR,wdth,wght].ttf']. [code: missing-os2-fsselection-bit7]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinAscent value should be equal or greater than 1080, but got 1069 instead [code: ascent]
* 🔥 **FAIL** OS/2.usWinDescent value should be equal or greater than 389, but got 293 instead. [code: descent]
</div></details><details><summary>🔥 <b>FAIL:</b> The variable font 'wght' (Weight) axis coordinate must be 400 on the 'Regular' instance. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/fvar.html#com.google.fonts/check/varfont/regular_wght_coord">com.google.fonts/check/varfont/regular_wght_coord</a>)</summary><div>


* 🔥 **FAIL** The "wght" axis coordinate of the "Regular" instance must be 400. Got None instead. [code: wght-not-400]
</div></details><details><summary>🔥 <b>FAIL:</b> The variable font 'wdth' (Width) axis coordinate must be 100 on the 'Regular' instance. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/fvar.html#com.google.fonts/check/varfont/regular_wdth_coord">com.google.fonts/check/varfont/regular_wdth_coord</a>)</summary><div>


* 🔥 **FAIL** The "wdth" axis coordinate of the "Regular" instance must be 100. Got None as a default value instead. [code: wdth-not-100]
</div></details><details><summary>🔥 <b>FAIL:</b> The variable font 'wght' (Weight) axis coordinate must be 700 on the 'Bold' instance. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/fvar.html#com.google.fonts/check/varfont/bold_wght_coord">com.google.fonts/check/varfont/bold_wght_coord</a>)</summary><div>


* 🔥 **FAIL** The "wght" axis coordinate of the "Bold" instance must be 700. Got None instead. [code: wght-not-700]
</div></details><details><summary>🔥 <b>FAIL:</b> Validates that when an instance record is included for the default instance, its subfamilyNameID value is set to either 2 or 17, and its postScriptNameID value is set to 6. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/fvar.html#com.adobe.fonts/check/varfont/valid_default_instance_nameids">com.adobe.fonts/check/varfont/valid_default_instance_nameids</a>)</summary><div>


* 🔥 **FAIL** 'Italic' instance has the same coordinates as the default instance; its subfamilyNameID should be either 2 or 17, instead of 262. [code: invalid-default-instance-subfamily-nameid:262]
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

	- uni03B1030603140300

	- uni1FCD0306

	- uni1FDE0306

	- uni03C5030803040301

	- uni03B9030603140300

	- uni03B9030803040300

	- uni03B9030603130301

	- uni03C5030803060301

	- uni03C5030603140301

	- uni03C5030403140301 

	- And 31 more.

Use -F or --full-lists to disable shortening of long lists.
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check mark characters are in GDEF mark glyph class. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_mark_chars">com.google.fonts/check/gdef_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following mark characters could be in the GDEF mark glyph class:
	 uni0488 (U+0488), uni0489 (U+0489), uni1ABE (U+1ABE), uniA670 (U+A670), uniA671 (U+A671) and uniA672 (U+A672) [code: mark-chars]
</div></details><br></div></details><details><summary><b>[18] NotoSerif-MM[wght].ttf</b></summary><div><details><summary>💔 <b>ERROR:</b> STAT table has Axis Value tables? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/stat.html#com.adobe.fonts/check/stat_has_axis_value_tables">com.adobe.fonts/check/stat_has_axis_value_tables</a>)</summary><div>


* 💔 **ERROR** Failed with AttributeError: 'NoneType' object has no attribute 'AxisValue'
</div></details><details><summary>🔥 <b>FAIL:</b> Checking file is named canonically. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/canonical_filename">com.google.fonts/check/canonical_filename</a>)</summary><div>


* 🔥 **FAIL** The file 'NotoSerif-MM[wght].ttf' must be renamed to 'NotoSerif[CTGR,wdth,wght].ttf' according to the Google Fonts naming policy for variable fonts. [code: bad-varfont-filename]
</div></details><details><summary>🔥 <b>FAIL:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* 🔥 **FAIL** Missing required codepoints:

	- 0x00AF (MACRON)
 [code: missing-codepoints]
</div></details><details><summary>🔥 <b>FAIL:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* 🔥 **FAIL** License file OFL.txt exists but NameID 13 (LICENSE DESCRIPTION) value on platform 3 (WINDOWS) is not specified for that. Value was: "This Font Software is licensed under the SIL Open Font License, Version 1.1. This Font Software is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the SIL Open Font License for the specific language, permissions and limitations governing your use of this Font Software." Must be changed to "This Font Software is licensed under the SIL Open Font License, Version 1.1. This license is available with a FAQ at: https://scripts.sil.org/OFL" [code: wrong]
</div></details><details><summary>🔥 <b>FAIL:</b> Is the Grid-fitting and Scan-conversion Procedure ('gasp') table set to optimize rendering? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/gasp">com.google.fonts/check/gasp</a>)</summary><div>


* 🔥 **FAIL** Font is missing the 'gasp' table. Try exporting the font with autohinting enabled.
If you are dealing with an unhinted font, it can be fixed by running the fonts through the command 'gftools fix-nonhinting'
GFTools is available at https://pypi.org/project/gftools/ [code: lacks-gasp]
</div></details><details><summary>🔥 <b>FAIL:</b> Font enables smart dropout control in "prep" table instructions? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/smart_dropout">com.google.fonts/check/smart_dropout</a>)</summary><div>


* 🔥 **FAIL** The 'prep' table does not contain TrueType instructions enabling smart dropout control. To fix, export the font with autohinting enabled, or run ttfautohint on the font, or run the `gftools fix-nonhinting` script. [code: lacks-smart-dropout]
</div></details><details><summary>🔥 <b>FAIL:</b> Validate STAT particle names and values match the fallback names in GFAxisRegistry.  (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/STAT/gf-axisregistry">com.google.fonts/check/STAT/gf-axisregistry</a>)</summary><div>


* 🔥 **FAIL** STAT table is missing Axis Value Records [code: missing-axis-values]
</div></details><details><summary>🔥 <b>FAIL:</b> OS/2.fsSelection bit 7 (USE_TYPO_METRICS) is set in all fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/os2/use_typo_metrics">com.google.fonts/check/os2/use_typo_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2.fsSelection bit 7 (USE_TYPO_METRICS) wasNOT set in the following fonts: ['fonts/NotoSerif-Italic/googlefonts/slim-variable-ttf/NotoSerif-ItalicMM[wght].ttf', 'fonts/NotoSerif-Italic/googlefonts/slim-variable-ttf/NotoSerif-MM[wght].ttf', 'fonts/NotoSerif-Italic/googlefonts/ttf/NotoSerif-Black.ttf', 'fonts/NotoSerif-Italic/googlefonts/ttf/NotoSerif-BlackItalic.ttf', 'fonts/NotoSerif-Italic/googlefonts/ttf/NotoSerif-Bold.ttf', 'fonts/NotoSerif-Italic/googlefonts/ttf/NotoSerif-BoldItalic.ttf', 'fonts/NotoSerif-Italic/googlefonts/ttf/NotoSerif-ExtraBold.ttf', 'fonts/NotoSerif-Italic/googlefonts/ttf/NotoSerif-ExtraBoldItalic.ttf', 'fonts/NotoSerif-Italic/googlefonts/ttf/NotoSerif-ExtraLight.ttf', 'fonts/NotoSerif-Italic/googlefonts/ttf/NotoSerif-ExtraLightItalic.ttf', 'fonts/NotoSerif-Italic/googlefonts/ttf/NotoSerif-Italic.ttf', 'fonts/NotoSerif-Italic/googlefonts/ttf/NotoSerif-Light.ttf', 'fonts/NotoSerif-Italic/googlefonts/ttf/NotoSerif-LightItalic.ttf', 'fonts/NotoSerif-Italic/googlefonts/ttf/NotoSerif-Medium.ttf', 'fonts/NotoSerif-Italic/googlefonts/ttf/NotoSerif-MediumItalic.ttf', 'fonts/NotoSerif-Italic/googlefonts/ttf/NotoSerif-Regular.ttf', 'fonts/NotoSerif-Italic/googlefonts/ttf/NotoSerif-SemiBold.ttf', 'fonts/NotoSerif-Italic/googlefonts/ttf/NotoSerif-SemiBoldItalic.ttf', 'fonts/NotoSerif-Italic/googlefonts/ttf/NotoSerif-Thin.ttf', 'fonts/NotoSerif-Italic/googlefonts/ttf/NotoSerif-ThinItalic.ttf', 'fonts/NotoSerif-Italic/googlefonts/variable-ttf/NotoSerif-ItalicMM[wdth,wght].ttf', 'fonts/NotoSerif-Italic/googlefonts/variable-ttf/NotoSerif-MM[CTGR,wdth,wght].ttf']. [code: missing-os2-fsselection-bit7]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinAscent value should be equal or greater than 1080, but got 1069 instead [code: ascent]
* 🔥 **FAIL** OS/2.usWinDescent value should be equal or greater than 389, but got 293 instead. [code: descent]
</div></details><details><summary>🔥 <b>FAIL:</b> Validates that when an instance record is included for the default instance, its subfamilyNameID value is set to either 2 or 17, and its postScriptNameID value is set to 6. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/fvar.html#com.adobe.fonts/check/varfont/valid_default_instance_nameids">com.adobe.fonts/check/varfont/valid_default_instance_nameids</a>)</summary><div>


* 🔥 **FAIL** 'Regular' instance has the same coordinates as the default instance; its subfamilyNameID should be either 2 or 17, instead of 263. [code: invalid-default-instance-subfamily-nameid:263]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure files are not too large. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/file_size">com.google.fonts/check/file_size</a>)</summary><div>


* ⚠ **WARN** Font file is 2.8Mb; ideally it should be less than 1.0Mb [code: large-font]
</div></details><details><summary>⚠ <b>WARN:</b> Is there kerning info for non-ligated sequences? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/kerning_for_non_ligated_sequences">com.google.fonts/check/kerning_for_non_ligated_sequences</a>)</summary><div>


* ⚠ **WARN** GPOS table lacks kerning info for the following non-ligated sequences:

	- f + f

	- f + i

	- i + f

	- f + l

	- l + f 

	- And i + l [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure Stylistic Sets have description. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/stylisticset_description">com.google.fonts/check/stylisticset_description</a>)</summary><div>


* ⚠ **WARN** The stylistic set ss03 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss06 lacks a description string on the 'name' table. [code: missing-description]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Glyph names are all valid? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/valid_glyphnames">com.google.fonts/check/valid_glyphnames</a>)</summary><div>


* ⚠ **WARN** The following glyph names may be too long for some legacy systems which may expect a maximum 31-char length limit:
kavykawithkavykaaboveinvertedlow [code: legacy-long-names]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- uni03B1030603140300

	- uni1FCD0306

	- uni1FDE0306

	- uni03C5030803040301

	- uni03B9030603140300

	- uni03B9030803040300

	- uni03B9030603130301

	- uni03C5030803060301

	- uni03C5030603140301

	- uni03C5030403140301 

	- And 31 more.

Use -F or --full-lists to disable shortening of long lists.
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Does the font have a DSIG table? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/dsig.html#com.google.fonts/check/dsig">com.google.fonts/check/dsig</a>)</summary><div>


* ⚠ **WARN** This font has a digital signature (DSIG table) which is only required - even if only a placeholder - on old programs like MS Office 2013 in order to work properly.
The current recommendation is to completely remove the DSIG table. [code: found-DSIG]
</div></details><details><summary>⚠ <b>WARN:</b> Check mark characters are in GDEF mark glyph class. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_mark_chars">com.google.fonts/check/gdef_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following mark characters could be in the GDEF mark glyph class:
	 uni0488 (U+0488), uni0489 (U+0489), uni1ABE (U+1ABE), uniA670 (U+A670), uniA671 (U+A671) and uniA672 (U+A672) [code: mark-chars]
</div></details><br></div></details><details><summary><b>[14] NotoSerif-Black.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* 🔥 **FAIL** Missing required codepoints:

	- 0x00AF (MACRON)
 [code: missing-codepoints]
</div></details><details><summary>🔥 <b>FAIL:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* 🔥 **FAIL** License file OFL.txt exists but NameID 13 (LICENSE DESCRIPTION) value on platform 3 (WINDOWS) is not specified for that. Value was: "This Font Software is licensed under the SIL Open Font License, Version 1.1. This Font Software is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the SIL Open Font License for the specific language, permissions and limitations governing your use of this Font Software." Must be changed to "This Font Software is licensed under the SIL Open Font License, Version 1.1. This license is available with a FAQ at: https://scripts.sil.org/OFL" [code: wrong]
</div></details><details><summary>🔥 <b>FAIL:</b> OS/2.fsSelection bit 7 (USE_TYPO_METRICS) is set in all fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/os2/use_typo_metrics">com.google.fonts/check/os2/use_typo_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2.fsSelection bit 7 (USE_TYPO_METRICS) wasNOT set in the following fonts: ['fonts/NotoSerif-Italic/googlefonts/slim-variable-ttf/NotoSerif-ItalicMM[wght].ttf', 'fonts/NotoSerif-Italic/googlefonts/slim-variable-ttf/NotoSerif-MM[wght].ttf', 'fonts/NotoSerif-Italic/googlefonts/ttf/NotoSerif-Black.ttf', 'fonts/NotoSerif-Italic/googlefonts/ttf/NotoSerif-BlackItalic.ttf', 'fonts/NotoSerif-Italic/googlefonts/ttf/NotoSerif-Bold.ttf', 'fonts/NotoSerif-Italic/googlefonts/ttf/NotoSerif-BoldItalic.ttf', 'fonts/NotoSerif-Italic/googlefonts/ttf/NotoSerif-ExtraBold.ttf', 'fonts/NotoSerif-Italic/googlefonts/ttf/NotoSerif-ExtraBoldItalic.ttf', 'fonts/NotoSerif-Italic/googlefonts/ttf/NotoSerif-ExtraLight.ttf', 'fonts/NotoSerif-Italic/googlefonts/ttf/NotoSerif-ExtraLightItalic.ttf', 'fonts/NotoSerif-Italic/googlefonts/ttf/NotoSerif-Italic.ttf', 'fonts/NotoSerif-Italic/googlefonts/ttf/NotoSerif-Light.ttf', 'fonts/NotoSerif-Italic/googlefonts/ttf/NotoSerif-LightItalic.ttf', 'fonts/NotoSerif-Italic/googlefonts/ttf/NotoSerif-Medium.ttf', 'fonts/NotoSerif-Italic/googlefonts/ttf/NotoSerif-MediumItalic.ttf', 'fonts/NotoSerif-Italic/googlefonts/ttf/NotoSerif-Regular.ttf', 'fonts/NotoSerif-Italic/googlefonts/ttf/NotoSerif-SemiBold.ttf', 'fonts/NotoSerif-Italic/googlefonts/ttf/NotoSerif-SemiBoldItalic.ttf', 'fonts/NotoSerif-Italic/googlefonts/ttf/NotoSerif-Thin.ttf', 'fonts/NotoSerif-Italic/googlefonts/ttf/NotoSerif-ThinItalic.ttf', 'fonts/NotoSerif-Italic/googlefonts/variable-ttf/NotoSerif-ItalicMM[wdth,wght].ttf', 'fonts/NotoSerif-Italic/googlefonts/variable-ttf/NotoSerif-MM[CTGR,wdth,wght].ttf']. [code: missing-os2-fsselection-bit7]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinAscent value should be equal or greater than 1080, but got 1069 instead [code: ascent]
* 🔥 **FAIL** OS/2.usWinDescent value should be equal or greater than 389, but got 293 instead. [code: descent]
</div></details><details><summary>⚠ <b>WARN:</b> Is there kerning info for non-ligated sequences? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/kerning_for_non_ligated_sequences">com.google.fonts/check/kerning_for_non_ligated_sequences</a>)</summary><div>


* ⚠ **WARN** GPOS table lacks kerning info for the following non-ligated sequences:

	- f + f

	- f + i

	- i + f

	- f + l

	- l + f 

	- And i + l [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure Stylistic Sets have description. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/stylisticset_description">com.google.fonts/check/stylisticset_description</a>)</summary><div>


* ⚠ **WARN** The stylistic set ss03 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss06 lacks a description string on the 'name' table. [code: missing-description]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Glyph names are all valid? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/valid_glyphnames">com.google.fonts/check/valid_glyphnames</a>)</summary><div>


* ⚠ **WARN** The following glyph names may be too long for some legacy systems which may expect a maximum 31-char length limit:
kavykawithkavykaaboveinvertedlow [code: legacy-long-names]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- uni03B1030603140300

	- uni1FCD0306

	- uni1FDE0306

	- uni03C5030803040301

	- uni03B9030603140300

	- uni03B9030803040300

	- uni03B9030603130301

	- uni03C5030803060301

	- uni03C5030603140301

	- uni03C5030403140301 

	- And 31 more.

Use -F or --full-lists to disable shortening of long lists.
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character (codepoint 0x00AD) which is supposed to be zero-width and invisible, and is used to mark a hyphenation possibility within a word in the absence of or overriding dictionary hyphenation. It is mostly an obsolete mechanism now, and the character is only included in fonts for legacy codepage coverage. [code: softhyphen]
* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: uni00AD	Contours detected: 1	Expected: 0

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uni01E5	Contours detected: 3	Expected: 2

	- Glyph name: uni01EA	Contours detected: 3	Expected: 2

	- Glyph name: uni01EB	Contours detected: 3	Expected: 2

	- Glyph name: uni01EC	Contours detected: 4	Expected: 3

	- Glyph name: uni01ED	Contours detected: 4	Expected: 3

	- Glyph name: uni01F5	Contours detected: 4	Expected: 3 

	- And 43 more.

Use -F or --full-lists to disable shortening of long lists.
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check mark characters are in GDEF mark glyph class. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_mark_chars">com.google.fonts/check/gdef_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following mark characters could be in the GDEF mark glyph class:
	 uni0488 (U+0488), uni0489 (U+0489), uni1ABE (U+1ABE), uniA670 (U+A670), uniA671 (U+A671) and uniA672 (U+A672) [code: mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* Zpalatalhook (U+A7C6): L<<675.0,229.0>--<670.0,0.0>> -> L<<670.0,0.0>--<670.0,-36.0>>

	* beta (U+03B2): L<<64.0,-220.0>--<66.0,100.0>> -> L<<66.0,100.0>--<64.0,494.0>>

	* dzdigraphretroflexhook (U+AB66): L<<1088.0,195.0>--<1083.0,0.0>> -> L<<1083.0,0.0>--<1083.0,-22.0>>

	* rho (U+03C1): L<<49.0,-221.0>--<51.0,53.0>> -> L<<51.0,53.0>--<51.0,263.0>>

	* uni03BC (U+03BC): L<<66.0,-221.0>--<68.0,225.0>> -> L<<68.0,225.0>--<64.0,536.0>>

	* uni03FC (U+03FC): L<<50.0,-82.0>--<51.0,53.0>> -> L<<51.0,53.0>--<51.0,263.0>>

	* uni1D5D (U+1D5D): L<<42.0,155.0>--<43.0,347.0>> -> L<<43.0,347.0>--<42.0,583.0>>

	* uni1D66 (U+1D66): L<<42.0,-132.0>--<43.0,60.0>> -> L<<43.0,60.0>--<42.0,296.0>>

	* uni1D68 (U+1D68): L<<32.0,-133.0>--<33.0,32.0>> -> L<<33.0,32.0>--<33.0,158.0>>

	* uni1D8E (U+1D8E): L<<531.0,195.0>--<527.0,0.0>> -> L<<527.0,0.0>--<527.0,-22.0>> 

	* And 3 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* V (U+0056): B<<402.5,227.0>-<406.0,208.0>-<407.0,194.0>>/B<<407.0,194.0>-<409.0,211.0>-<416.0,238.5>> = 10.79545358773178

	* eogonek (U+0119): B<<282.5,-58.0>-<309.0,-25.0>-<346.0,-9.0>>/B<<346.0,-9.0>-<340.0,-10.0>-<333.5,-10.0>> = 13.922898849188117

	* uni01B4 (U+01B4): B<<336.0,187.0>-<342.0,160.0>-<343.0,142.0>>/B<<343.0,142.0>-<346.0,164.0>-<349.5,180.0>> = 10.944996138289511

	* uni0233 (U+0233): B<<336.0,187.0>-<342.0,160.0>-<343.0,142.0>>/B<<343.0,142.0>-<346.0,164.0>-<349.5,180.0>> = 10.944996138289511

	* uni024F (U+024F): B<<336.0,187.0>-<342.0,160.0>-<343.0,142.0>>/B<<343.0,142.0>-<346.0,164.0>-<349.5,180.0>> = 10.944996138289511

	* uni028E (U+028E): B<<250.5,349.5>-<245.0,376.0>-<243.0,394.0>>/B<<243.0,394.0>-<240.0,372.0>-<236.5,356.0>> = 14.10535776433523

	* uni02B8 (U+02B8): B<<218.0,399.0>-<222.0,383.0>-<223.0,372.0>>/B<<223.0,372.0>-<225.0,385.0>-<227.5,394.5>> = 13.94059117029001

	* uni0377 (U+0377): B<<436.0,258.5>-<451.0,311.0>-<483.0,367.0>>/L<<483.0,367.0>--<198.0,0.0>> = 8.086843940697037

	* uni03D7 (U+03D7): B<<641.0,36.0>-<640.0,35.0>-<639.0,35.0>>/L<<639.0,35.0>--<646.0,36.0>> = 8.13010235415596

	* uni03F0 (U+03F0): B<<273.5,223.5>-<256.0,186.0>-<241.0,162.0>>/L<<241.0,162.0>--<532.0,536.0>> = 5.880204881078469 

	* And 32 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-jaggy-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

	* beta (U+03B2): L<<64.0,-220.0>--<66.0,100.0>>

	* beta (U+03B2): L<<66.0,100.0>--<64.0,494.0>>

	* eta (U+03B7): L<<627.0,360.0>--<630.0,-221.0>>

	* etatonos (U+03AE): L<<627.0,360.0>--<630.0,-221.0>>

	* iota (U+03B9): L<<65.0,175.0>--<64.0,536.0>>

	* iotadieresis (U+03CA): L<<65.0,175.0>--<64.0,536.0>>

	* iotadieresistonos (U+0390): L<<65.0,175.0>--<64.0,536.0>>

	* iotatonos (U+03AF): L<<65.0,175.0>--<64.0,536.0>>

	* kappa (U+03BA): L<<46.0,0.0>--<44.0,536.0>>

	* rho (U+03C1): L<<49.0,-221.0>--<51.0,53.0>> 

	* And 59 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-semi-vertical]
</div></details><br></div></details><details><summary><b>[13] NotoSerif-BlackItalic.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* 🔥 **FAIL** Missing required codepoints:

	- 0x00AF (MACRON)
 [code: missing-codepoints]
</div></details><details><summary>🔥 <b>FAIL:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* 🔥 **FAIL** License file OFL.txt exists but NameID 13 (LICENSE DESCRIPTION) value on platform 3 (WINDOWS) is not specified for that. Value was: "This Font Software is licensed under the SIL Open Font License, Version 1.1. This Font Software is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the SIL Open Font License for the specific language, permissions and limitations governing your use of this Font Software." Must be changed to "This Font Software is licensed under the SIL Open Font License, Version 1.1. This license is available with a FAQ at: https://scripts.sil.org/OFL" [code: wrong]
</div></details><details><summary>🔥 <b>FAIL:</b> OS/2.fsSelection bit 7 (USE_TYPO_METRICS) is set in all fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/os2/use_typo_metrics">com.google.fonts/check/os2/use_typo_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2.fsSelection bit 7 (USE_TYPO_METRICS) wasNOT set in the following fonts: ['fonts/NotoSerif-Italic/googlefonts/slim-variable-ttf/NotoSerif-ItalicMM[wght].ttf', 'fonts/NotoSerif-Italic/googlefonts/slim-variable-ttf/NotoSerif-MM[wght].ttf', 'fonts/NotoSerif-Italic/googlefonts/ttf/NotoSerif-Black.ttf', 'fonts/NotoSerif-Italic/googlefonts/ttf/NotoSerif-BlackItalic.ttf', 'fonts/NotoSerif-Italic/googlefonts/ttf/NotoSerif-Bold.ttf', 'fonts/NotoSerif-Italic/googlefonts/ttf/NotoSerif-BoldItalic.ttf', 'fonts/NotoSerif-Italic/googlefonts/ttf/NotoSerif-ExtraBold.ttf', 'fonts/NotoSerif-Italic/googlefonts/ttf/NotoSerif-ExtraBoldItalic.ttf', 'fonts/NotoSerif-Italic/googlefonts/ttf/NotoSerif-ExtraLight.ttf', 'fonts/NotoSerif-Italic/googlefonts/ttf/NotoSerif-ExtraLightItalic.ttf', 'fonts/NotoSerif-Italic/googlefonts/ttf/NotoSerif-Italic.ttf', 'fonts/NotoSerif-Italic/googlefonts/ttf/NotoSerif-Light.ttf', 'fonts/NotoSerif-Italic/googlefonts/ttf/NotoSerif-LightItalic.ttf', 'fonts/NotoSerif-Italic/googlefonts/ttf/NotoSerif-Medium.ttf', 'fonts/NotoSerif-Italic/googlefonts/ttf/NotoSerif-MediumItalic.ttf', 'fonts/NotoSerif-Italic/googlefonts/ttf/NotoSerif-Regular.ttf', 'fonts/NotoSerif-Italic/googlefonts/ttf/NotoSerif-SemiBold.ttf', 'fonts/NotoSerif-Italic/googlefonts/ttf/NotoSerif-SemiBoldItalic.ttf', 'fonts/NotoSerif-Italic/googlefonts/ttf/NotoSerif-Thin.ttf', 'fonts/NotoSerif-Italic/googlefonts/ttf/NotoSerif-ThinItalic.ttf', 'fonts/NotoSerif-Italic/googlefonts/variable-ttf/NotoSerif-ItalicMM[wdth,wght].ttf', 'fonts/NotoSerif-Italic/googlefonts/variable-ttf/NotoSerif-MM[CTGR,wdth,wght].ttf']. [code: missing-os2-fsselection-bit7]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinAscent value should be equal or greater than 1080, but got 1069 instead [code: ascent]
* 🔥 **FAIL** OS/2.usWinDescent value should be equal or greater than 389, but got 293 instead. [code: descent]
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

	- uni03B1030603140300

	- uni1FCD0306

	- uni1FDE0306

	- uni03C5030803040301

	- uni03B9030603140300

	- uni03B9030803040300

	- uni03B9030603130301

	- uni03C5030803060301

	- uni03C5030603140301

	- uni03C5030403140301 

	- And 31 more.

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

	- And 43 more.

Use -F or --full-lists to disable shortening of long lists.
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check mark characters are in GDEF mark glyph class. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_mark_chars">com.google.fonts/check/gdef_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following mark characters could be in the GDEF mark glyph class:
	 uni0488 (U+0488), uni0489 (U+0489), uni1ABE (U+1ABE), uniA670 (U+A670), uniA671 (U+A671) and uniA672 (U+A672) [code: mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* beta (U+03B2): L<<-57.0,-220.0>--<13.0,100.0>> -> L<<13.0,100.0>--<93.0,494.0>>

	* dzdigraphretroflexhook (U+AB66): L<<1059.0,195.0>--<1013.0,0.0>> -> L<<1013.0,0.0>--<1008.0,-22.0>>

	* f_f (U+FB00): L<<358.0,536.0>--<511.0,536.0>> -> L<<511.0,536.0>--<511.0,536.0>>

	* f_f (U+FB00): L<<511.0,536.0>--<511.0,536.0>> -> L<<511.0,536.0>--<512.0,536.0>>

	* rho (U+03C1): L<<-79.0,-221.0>--<-20.0,53.0>> -> L<<-20.0,53.0>--<24.0,263.0>>

	* uni03BC (U+03BC): L<<-54.0,-221.0>--<41.0,225.0>> -> L<<41.0,225.0>--<102.0,536.0>>

	* uni03FC (U+03FC): L<<-49.0,-82.0>--<-20.0,53.0>> -> L<<-20.0,53.0>--<24.0,263.0>>

	* uni1D0B (U+1D0B): L<<342.0,445.0>--<314.0,327.0>> -> L<<314.0,327.0>--<307.0,300.0>>

	* uni1D27 (U+1D27): L<<328.0,99.0>--<328.0,126.0>> -> L<<328.0,126.0>--<316.0,366.0>>

	* uni1D5D (U+1D5D): L<<16.0,155.0>--<61.0,347.0>> -> L<<61.0,347.0>--<113.0,583.0>> 

	* And 6 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* Ereversedopen (U+A7AB): B<<533.5,403.5>-<488.0,379.0>-<431.0,372.0>>/B<<431.0,372.0>-<463.0,369.0>-<498.5,351.5>> = 12.357092600350505

	* kacombcy (U+2DE6): B<<118.0,745.5>-<110.0,739.0>-<101.0,738.0>>/B<<101.0,738.0>-<128.0,738.0>-<145.5,728.0>> = 6.340191745909908

	* uni0246 (U+0246): L<<335.0,339.0>--<295.0,151.0>>/L<<295.0,151.0>--<379.0,339.0>> = 12.064019868713396

	* uni024A (U+024A): L<<556.0,29.0>--<587.0,135.0>>/B<<587.0,135.0>-<568.0,101.0>-<528.5,68.0>> = 12.89577770175709

	* uni0377 (U+0377): B<<469.0,344.0>-<483.0,374.0>-<492.0,393.0>>/L<<492.0,393.0>--<197.0,0.0>> = 11.54704110819093

	* uni03F0 (U+03F0): B<<347.0,230.0>-<326.0,180.0>-<305.0,136.0>>/L<<305.0,136.0>--<596.0,536.0>> = 10.522018977053735

	* uni03F0 (U+03F0): B<<554.0,344.0>-<568.0,374.0>-<577.0,393.0>>/L<<577.0,393.0>--<282.0,0.0>> = 11.54704110819093

	* uni0417 (U+0417): B<<533.5,403.5>-<488.0,379.0>-<431.0,372.0>>/B<<431.0,372.0>-<463.0,369.0>-<498.5,351.5>> = 12.357092600350505

	* uni0432 (U+0432): B<<512.5,321.5>-<468.0,275.0>-<385.0,258.0>>/B<<385.0,258.0>-<418.0,258.0>-<448.0,243.0>> = 11.575188817396182

	* uni043A (U+043A): B<<366.5,314.0>-<348.0,299.0>-<328.0,294.0>>/B<<328.0,294.0>-<389.0,296.0>-<428.0,270.0>> = 12.158366020641097 

	* And 25 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-jaggy-segments]
</div></details><br></div></details><details><summary><b>[22] NotoSerif-Bold.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* 🔥 **FAIL** Missing required codepoints:

	- 0x00AF (MACRON)
 [code: missing-codepoints]
</div></details><details><summary>🔥 <b>FAIL:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* 🔥 **FAIL** License file OFL.txt exists but NameID 13 (LICENSE DESCRIPTION) value on platform 3 (WINDOWS) is not specified for that. Value was: "This Font Software is licensed under the SIL Open Font License, Version 1.1. This Font Software is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the SIL Open Font License for the specific language, permissions and limitations governing your use of this Font Software." Must be changed to "This Font Software is licensed under the SIL Open Font License, Version 1.1. This license is available with a FAQ at: https://scripts.sil.org/OFL" [code: wrong]
</div></details><details><summary>🔥 <b>FAIL:</b> Is the Grid-fitting and Scan-conversion Procedure ('gasp') table set to optimize rendering? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/gasp">com.google.fonts/check/gasp</a>)</summary><div>


* 🔥 **FAIL** Font is missing the 'gasp' table. Try exporting the font with autohinting enabled.
If you are dealing with an unhinted font, it can be fixed by running the fonts through the command 'gftools fix-nonhinting'
GFTools is available at https://pypi.org/project/gftools/ [code: lacks-gasp]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 fsSelection value. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/fsselection">com.google.fonts/check/fsselection</a>)</summary><div>


* 🔥 **FAIL** OS/2 fsSelection REGULAR bit should be unset. [code: bad-REGULAR]
* 🔥 **FAIL** OS/2 fsSelection BOLD bit should be set. [code: bad-BOLD]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking head.macStyle value. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/mac_style">com.google.fonts/check/mac_style</a>)</summary><div>


* 🔥 **FAIL** head macStyle BOLD bit should be set. [code: bad-BOLD]
</div></details><details><summary>🔥 <b>FAIL:</b> Check name table: FONT_FAMILY_NAME entries. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/familyname">com.google.fonts/check/name/familyname</a>)</summary><div>


* 🔥 **FAIL** Entry [FONT_FAMILY_NAME(1):WINDOWS(3)] on the "name" table: Expected "Noto Serif" but got "Noto Serif Bold". [code: mismatch]
</div></details><details><summary>🔥 <b>FAIL:</b> Check name table: FONT_SUBFAMILY_NAME entries. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/subfamilyname">com.google.fonts/check/name/subfamilyname</a>)</summary><div>


* 🔥 **FAIL** SUBFAMILY_NAME for Win "Regular" must be "Bold" [code: bad-familyname]
</div></details><details><summary>🔥 <b>FAIL:</b> Check name table: TYPOGRAPHIC_FAMILY_NAME entries. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/typographicfamilyname">com.google.fonts/check/name/typographicfamilyname</a>)</summary><div>


* 🔥 **FAIL** Font style is "Bold" and, for that reason, it is not expected to have a [TYPOGRAPHIC_FAMILY_NAME(16):WINDOWS(3)] entry! [code: ribbi]
</div></details><details><summary>🔥 <b>FAIL:</b> Font enables smart dropout control in "prep" table instructions? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/smart_dropout">com.google.fonts/check/smart_dropout</a>)</summary><div>


* 🔥 **FAIL** The 'prep' table does not contain TrueType instructions enabling smart dropout control. To fix, export the font with autohinting enabled, or run ttfautohint on the font, or run the `gftools fix-nonhinting` script. [code: lacks-smart-dropout]
</div></details><details><summary>🔥 <b>FAIL:</b> OS/2.fsSelection bit 7 (USE_TYPO_METRICS) is set in all fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/os2/use_typo_metrics">com.google.fonts/check/os2/use_typo_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2.fsSelection bit 7 (USE_TYPO_METRICS) wasNOT set in the following fonts: ['fonts/NotoSerif-Italic/googlefonts/slim-variable-ttf/NotoSerif-ItalicMM[wght].ttf', 'fonts/NotoSerif-Italic/googlefonts/slim-variable-ttf/NotoSerif-MM[wght].ttf', 'fonts/NotoSerif-Italic/googlefonts/ttf/NotoSerif-Black.ttf', 'fonts/NotoSerif-Italic/googlefonts/ttf/NotoSerif-BlackItalic.ttf', 'fonts/NotoSerif-Italic/googlefonts/ttf/NotoSerif-Bold.ttf', 'fonts/NotoSerif-Italic/googlefonts/ttf/NotoSerif-BoldItalic.ttf', 'fonts/NotoSerif-Italic/googlefonts/ttf/NotoSerif-ExtraBold.ttf', 'fonts/NotoSerif-Italic/googlefonts/ttf/NotoSerif-ExtraBoldItalic.ttf', 'fonts/NotoSerif-Italic/googlefonts/ttf/NotoSerif-ExtraLight.ttf', 'fonts/NotoSerif-Italic/googlefonts/ttf/NotoSerif-ExtraLightItalic.ttf', 'fonts/NotoSerif-Italic/googlefonts/ttf/NotoSerif-Italic.ttf', 'fonts/NotoSerif-Italic/googlefonts/ttf/NotoSerif-Light.ttf', 'fonts/NotoSerif-Italic/googlefonts/ttf/NotoSerif-LightItalic.ttf', 'fonts/NotoSerif-Italic/googlefonts/ttf/NotoSerif-Medium.ttf', 'fonts/NotoSerif-Italic/googlefonts/ttf/NotoSerif-MediumItalic.ttf', 'fonts/NotoSerif-Italic/googlefonts/ttf/NotoSerif-Regular.ttf', 'fonts/NotoSerif-Italic/googlefonts/ttf/NotoSerif-SemiBold.ttf', 'fonts/NotoSerif-Italic/googlefonts/ttf/NotoSerif-SemiBoldItalic.ttf', 'fonts/NotoSerif-Italic/googlefonts/ttf/NotoSerif-Thin.ttf', 'fonts/NotoSerif-Italic/googlefonts/ttf/NotoSerif-ThinItalic.ttf', 'fonts/NotoSerif-Italic/googlefonts/variable-ttf/NotoSerif-ItalicMM[wdth,wght].ttf', 'fonts/NotoSerif-Italic/googlefonts/variable-ttf/NotoSerif-MM[CTGR,wdth,wght].ttf']. [code: missing-os2-fsselection-bit7]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinAscent value should be equal or greater than 1080, but got 1069 instead [code: ascent]
* 🔥 **FAIL** OS/2.usWinDescent value should be equal or greater than 389, but got 293 instead. [code: descent]
</div></details><details><summary>⚠ <b>WARN:</b> Glyphs are similiar to Google Fonts version? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/production_glyphs_similarity">com.google.fonts/check/production_glyphs_similarity</a>)</summary><div>


* ⚠ **WARN** Following glyphs differ greatly from Google Fonts version:
	* uni1D5E
	* uni1F83
	* uni1D33
	* rho
	* uni1FD6
	* uni1F45
	* uni1DA8
	* uni1FCE
	* uni1F0F
	* uni1F0E and 380 more.

Use -F or --full-lists to disable shortening of long lists.
</div></details><details><summary>⚠ <b>WARN:</b> Is there kerning info for non-ligated sequences? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/kerning_for_non_ligated_sequences">com.google.fonts/check/kerning_for_non_ligated_sequences</a>)</summary><div>


* ⚠ **WARN** GPOS table lacks kerning info for the following non-ligated sequences:

	- f + f

	- f + i

	- i + f

	- f + l

	- l + f 

	- And i + l [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure Stylistic Sets have description. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/stylisticset_description">com.google.fonts/check/stylisticset_description</a>)</summary><div>


* ⚠ **WARN** The stylistic set ss03 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss06 lacks a description string on the 'name' table. [code: missing-description]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Glyph names are all valid? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/valid_glyphnames">com.google.fonts/check/valid_glyphnames</a>)</summary><div>


* ⚠ **WARN** The following glyph names may be too long for some legacy systems which may expect a maximum 31-char length limit:
kavykawithkavykaaboveinvertedlow [code: legacy-long-names]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- uni03B1030603140300

	- uni1FCD0306

	- uni1FDE0306

	- uni03C5030803040301

	- uni03B9030603140300

	- uni03B9030803040300

	- uni03B9030603130301

	- uni03C5030803060301

	- uni03C5030603140301

	- uni03C5030403140301 

	- And 31 more.

Use -F or --full-lists to disable shortening of long lists.
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character (codepoint 0x00AD) which is supposed to be zero-width and invisible, and is used to mark a hyphenation possibility within a word in the absence of or overriding dictionary hyphenation. It is mostly an obsolete mechanism now, and the character is only included in fonts for legacy codepage coverage. [code: softhyphen]
* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: uni00AD	Contours detected: 1	Expected: 0

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uni01E5	Contours detected: 3	Expected: 2

	- Glyph name: uni01EA	Contours detected: 3	Expected: 2

	- Glyph name: uni01EB	Contours detected: 3	Expected: 2

	- Glyph name: uni01EC	Contours detected: 4	Expected: 3

	- Glyph name: uni01ED	Contours detected: 4	Expected: 3

	- Glyph name: uni01F5	Contours detected: 4	Expected: 3 

	- And 39 more.

Use -F or --full-lists to disable shortening of long lists.
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check mark characters are in GDEF mark glyph class. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_mark_chars">com.google.fonts/check/gdef_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following mark characters could be in the GDEF mark glyph class:
	 uni0488 (U+0488), uni0489 (U+0489), uni1ABE (U+1ABE), uniA670 (U+A670), uniA671 (U+A671) and uniA672 (U+A672) [code: mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* Zpalatalhook (U+A7C6): L<<622.0,206.0>--<617.0,0.0>> -> L<<617.0,0.0>--<617.0,-61.0>>

	* beta (U+03B2): L<<73.0,-240.0>--<77.0,126.0>> -> L<<77.0,126.0>--<68.0,527.0>>

	* dzdigraphretroflexhook (U+AB66): L<<1010.0,181.0>--<1005.0,0.0>> -> L<<1005.0,0.0>--<1005.0,-51.0>>

	* rho (U+03C1): L<<53.0,-240.0>--<57.0,122.0>> -> L<<57.0,122.0>--<57.0,263.0>>

	* uni03BC (U+03BC): L<<71.0,-240.0>--<75.0,75.0>> -> L<<75.0,75.0>--<68.0,536.0>>

	* uni03FC (U+03FC): L<<55.0,-81.0>--<57.0,122.0>> -> L<<57.0,122.0>--<57.0,263.0>>

	* uni1D5D (U+1D5D): L<<47.0,143.0>--<50.0,363.0>> -> L<<50.0,363.0>--<44.0,603.0>>

	* uni1D66 (U+1D66): L<<47.0,-144.0>--<50.0,76.0>> -> L<<50.0,76.0>--<44.0,316.0>>

	* uni1D68 (U+1D68): L<<34.0,-144.0>--<37.0,73.0>> -> L<<37.0,73.0>--<37.0,158.0>>

	* uni1D7A (U+1D7A): L<<248.0,468.0>--<248.0,158.0>> -> L<<248.0,158.0>--<248.0,155.0>> 

	* And 4 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* uni01B4 (U+01B4): B<<320.0,162.5>-<327.0,138.0>-<329.0,118.0>>/B<<329.0,118.0>-<330.0,132.0>-<335.0,149.0>> = 9.796209917474465

	* uni0233 (U+0233): B<<321.0,162.0>-<327.0,138.0>-<329.0,118.0>>/B<<329.0,118.0>-<331.0,139.0>-<339.5,165.0>> = 11.150925168505127

	* uni0246 (U+0246): L<<280.0,343.0>--<280.0,94.0>>/L<<280.0,94.0>--<341.0,343.0>> = 13.765215312007642

	* uni024F (U+024F): B<<321.0,162.0>-<327.0,138.0>-<329.0,118.0>>/B<<329.0,118.0>-<331.0,139.0>-<339.5,165.0>> = 11.150925168505127

	* uni028E (U+028E): B<<258.0,374.0>-<252.0,398.0>-<250.0,418.0>>/B<<250.0,418.0>-<249.0,397.0>-<240.0,371.5>> = 8.436904131405898

	* uni02B8 (U+02B8): B<<208.5,384.0>-<212.0,370.0>-<214.0,358.0>>/B<<214.0,358.0>-<215.0,370.0>-<220.5,385.5>> = 14.22596389875178

	* uni03F0 (U+03F0): B<<233.5,219.0>-<220.0,180.0>-<208.0,155.0>>/L<<208.0,155.0>--<481.0,536.0>> = 9.981933481390366

	* uni0443 (U+0443): B<<321.0,162.0>-<327.0,138.0>-<329.0,118.0>>/B<<329.0,118.0>-<331.0,139.0>-<339.5,165.0>> = 11.150925168505127

	* uni045E (U+045E): B<<321.0,162.0>-<327.0,138.0>-<329.0,118.0>>/B<<329.0,118.0>-<331.0,139.0>-<339.5,165.0>> = 11.150925168505127

	* uni0478 (U+0478): B<<1047.0,162.0>-<1053.0,138.0>-<1055.0,118.0>>/B<<1055.0,118.0>-<1057.0,139.0>-<1065.5,165.0>> = 11.150925168505127 

	* And 19 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-jaggy-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

	* eta (U+03B7): L<<578.0,356.0>--<583.0,-240.0>>

	* etatonos (U+03AE): L<<578.0,356.0>--<583.0,-240.0>>

	* h (U+0068): L<<101.0,122.0>--<100.0,646.0>>

	* h (U+0068): L<<252.0,309.0>--<253.0,118.0>>

	* hcircumflex (U+0125): L<<101.0,122.0>--<100.0,646.0>>

	* hcircumflex (U+0125): L<<252.0,309.0>--<253.0,118.0>>

	* hpalatalhook (U+A795): L<<101.0,122.0>--<100.0,646.0>>

	* hpalatalhook (U+A795): L<<252.0,309.0>--<253.0,118.0>>

	* kappa (U+03BA): L<<52.0,0.0>--<48.0,536.0>>

	* sterling (U+00A3): L<<428.0,346.0>--<270.0,347.0>> 

	* And 44 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-semi-vertical]
</div></details><br></div></details><details><summary><b>[22] NotoSerif-BoldItalic.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* 🔥 **FAIL** Missing required codepoints:

	- 0x00AF (MACRON)
 [code: missing-codepoints]
</div></details><details><summary>🔥 <b>FAIL:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* 🔥 **FAIL** License file OFL.txt exists but NameID 13 (LICENSE DESCRIPTION) value on platform 3 (WINDOWS) is not specified for that. Value was: "This Font Software is licensed under the SIL Open Font License, Version 1.1. This Font Software is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the SIL Open Font License for the specific language, permissions and limitations governing your use of this Font Software." Must be changed to "This Font Software is licensed under the SIL Open Font License, Version 1.1. This license is available with a FAQ at: https://scripts.sil.org/OFL" [code: wrong]
</div></details><details><summary>🔥 <b>FAIL:</b> Is the Grid-fitting and Scan-conversion Procedure ('gasp') table set to optimize rendering? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/gasp">com.google.fonts/check/gasp</a>)</summary><div>


* 🔥 **FAIL** Font is missing the 'gasp' table. Try exporting the font with autohinting enabled.
If you are dealing with an unhinted font, it can be fixed by running the fonts through the command 'gftools fix-nonhinting'
GFTools is available at https://pypi.org/project/gftools/ [code: lacks-gasp]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 fsSelection value. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/fsselection">com.google.fonts/check/fsselection</a>)</summary><div>


* 🔥 **FAIL** OS/2 fsSelection REGULAR bit should be unset. [code: bad-REGULAR]
* 🔥 **FAIL** OS/2 fsSelection ITALIC bit should be set. [code: bad-ITALIC]
* 🔥 **FAIL** OS/2 fsSelection BOLD bit should be set. [code: bad-BOLD]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking head.macStyle value. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/mac_style">com.google.fonts/check/mac_style</a>)</summary><div>


* 🔥 **FAIL** head macStyle ITALIC bit should be set. [code: bad-ITALIC]
* 🔥 **FAIL** head macStyle BOLD bit should be set. [code: bad-BOLD]
</div></details><details><summary>🔥 <b>FAIL:</b> Check name table: FONT_FAMILY_NAME entries. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/familyname">com.google.fonts/check/name/familyname</a>)</summary><div>


* 🔥 **FAIL** Entry [FONT_FAMILY_NAME(1):WINDOWS(3)] on the "name" table: Expected "Noto Serif" but got "Noto Serif Bold Italic". [code: mismatch]
</div></details><details><summary>🔥 <b>FAIL:</b> Check name table: FONT_SUBFAMILY_NAME entries. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/subfamilyname">com.google.fonts/check/name/subfamilyname</a>)</summary><div>


* 🔥 **FAIL** SUBFAMILY_NAME for Win "Regular" must be "Bold Italic" [code: bad-familyname]
</div></details><details><summary>🔥 <b>FAIL:</b> Check name table: TYPOGRAPHIC_FAMILY_NAME entries. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/typographicfamilyname">com.google.fonts/check/name/typographicfamilyname</a>)</summary><div>


* 🔥 **FAIL** Font style is "BoldItalic" and, for that reason, it is not expected to have a [TYPOGRAPHIC_FAMILY_NAME(16):WINDOWS(3)] entry! [code: ribbi]
</div></details><details><summary>🔥 <b>FAIL:</b> Font enables smart dropout control in "prep" table instructions? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/smart_dropout">com.google.fonts/check/smart_dropout</a>)</summary><div>


* 🔥 **FAIL** The 'prep' table does not contain TrueType instructions enabling smart dropout control. To fix, export the font with autohinting enabled, or run ttfautohint on the font, or run the `gftools fix-nonhinting` script. [code: lacks-smart-dropout]
</div></details><details><summary>🔥 <b>FAIL:</b> OS/2.fsSelection bit 7 (USE_TYPO_METRICS) is set in all fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/os2/use_typo_metrics">com.google.fonts/check/os2/use_typo_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2.fsSelection bit 7 (USE_TYPO_METRICS) wasNOT set in the following fonts: ['fonts/NotoSerif-Italic/googlefonts/slim-variable-ttf/NotoSerif-ItalicMM[wght].ttf', 'fonts/NotoSerif-Italic/googlefonts/slim-variable-ttf/NotoSerif-MM[wght].ttf', 'fonts/NotoSerif-Italic/googlefonts/ttf/NotoSerif-Black.ttf', 'fonts/NotoSerif-Italic/googlefonts/ttf/NotoSerif-BlackItalic.ttf', 'fonts/NotoSerif-Italic/googlefonts/ttf/NotoSerif-Bold.ttf', 'fonts/NotoSerif-Italic/googlefonts/ttf/NotoSerif-BoldItalic.ttf', 'fonts/NotoSerif-Italic/googlefonts/ttf/NotoSerif-ExtraBold.ttf', 'fonts/NotoSerif-Italic/googlefonts/ttf/NotoSerif-ExtraBoldItalic.ttf', 'fonts/NotoSerif-Italic/googlefonts/ttf/NotoSerif-ExtraLight.ttf', 'fonts/NotoSerif-Italic/googlefonts/ttf/NotoSerif-ExtraLightItalic.ttf', 'fonts/NotoSerif-Italic/googlefonts/ttf/NotoSerif-Italic.ttf', 'fonts/NotoSerif-Italic/googlefonts/ttf/NotoSerif-Light.ttf', 'fonts/NotoSerif-Italic/googlefonts/ttf/NotoSerif-LightItalic.ttf', 'fonts/NotoSerif-Italic/googlefonts/ttf/NotoSerif-Medium.ttf', 'fonts/NotoSerif-Italic/googlefonts/ttf/NotoSerif-MediumItalic.ttf', 'fonts/NotoSerif-Italic/googlefonts/ttf/NotoSerif-Regular.ttf', 'fonts/NotoSerif-Italic/googlefonts/ttf/NotoSerif-SemiBold.ttf', 'fonts/NotoSerif-Italic/googlefonts/ttf/NotoSerif-SemiBoldItalic.ttf', 'fonts/NotoSerif-Italic/googlefonts/ttf/NotoSerif-Thin.ttf', 'fonts/NotoSerif-Italic/googlefonts/ttf/NotoSerif-ThinItalic.ttf', 'fonts/NotoSerif-Italic/googlefonts/variable-ttf/NotoSerif-ItalicMM[wdth,wght].ttf', 'fonts/NotoSerif-Italic/googlefonts/variable-ttf/NotoSerif-MM[CTGR,wdth,wght].ttf']. [code: missing-os2-fsselection-bit7]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinAscent value should be equal or greater than 1080, but got 1069 instead [code: ascent]
* 🔥 **FAIL** OS/2.usWinDescent value should be equal or greater than 389, but got 293 instead. [code: descent]
</div></details><details><summary>⚠ <b>WARN:</b> Glyphs are similiar to Google Fonts version? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/production_glyphs_similarity">com.google.fonts/check/production_glyphs_similarity</a>)</summary><div>


* ⚠ **WARN** Following glyphs differ greatly from Google Fonts version:
	* uni04F1
	* uni1D5E
	* uni1F83
	* uni1D33
	* rho
	* uni1FD6
	* uni1F45
	* uni1DA8
	* uni1FCE
	* uni04D3 and 438 more.

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
 FONT_FAMILY_NAME = 'Noto Serif Bold Italic' / SUBFAMILY_NAME = 'Regular'

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

	- uni03B1030603140300

	- uni1FCD0306

	- uni1FDE0306

	- uni03C5030803040301

	- uni03B9030603140300

	- uni03B9030803040300

	- uni03B9030603130301

	- uni03C5030803060301

	- uni03C5030603140301

	- uni03C5030403140301 

	- And 31 more.

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

	* Zpalatalhook (U+A7C6): L<<621.0,206.0>--<573.0,1.0>> -> L<<573.0,1.0>--<560.0,-61.0>>

	* beta (U+03B2): L<<-48.0,-240.0>--<32.0,126.0>> -> L<<32.0,126.0>--<109.0,527.0>>

	* dzdigraphretroflexhook (U+AB66): L<<987.0,181.0>--<946.0,7.0>> -> L<<946.0,7.0>--<938.0,-26.0>>

	* rho (U+03C1): L<<-74.0,-240.0>--<6.0,122.0>> -> L<<6.0,122.0>--<35.0,263.0>>

	* uni03BC (U+03BC): L<<-48.0,-240.0>--<22.0,75.0>> -> L<<22.0,75.0>--<111.0,536.0>>

	* uni03FC (U+03FC): L<<-39.0,-81.0>--<6.0,122.0>> -> L<<6.0,122.0>--<35.0,263.0>>

	* uni1D0B (U+1D0B): L<<304.0,444.0>--<276.0,322.0>> -> L<<276.0,322.0>--<268.0,285.0>>

	* uni1D5D (U+1D5D): L<<22.0,143.0>--<74.0,363.0>> -> L<<74.0,363.0>--<124.0,603.0>>

	* uni1D66 (U+1D66): L<<-83.0,-240.0>--<-31.0,-20.0>> -> L<<-31.0,-20.0>--<19.0,220.0>>

	* uni1D68 (U+1D68): L<<-100.0,-240.0>--<-48.0,-23.0>> -> L<<-48.0,-23.0>--<-29.0,62.0>> 

	* And 3 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* Ereversedopen (U+A7AB): B<<508.0,402.0>-<462.0,377.0>-<405.0,370.0>>/B<<405.0,370.0>-<437.0,367.0>-<472.5,349.5>> = 12.357092600350505

	* uni0246 (U+0246): L<<299.0,343.0>--<242.0,73.0>>/L<<242.0,73.0>--<364.0,343.0>> = 12.395181192130876

	* uni03F0 (U+03F0): B<<282.5,231.5>-<262.0,182.0>-<240.0,135.0>>/L<<240.0,135.0>--<555.0,536.0>> = 13.067321778305404

	* uni0417 (U+0417): B<<508.0,402.0>-<462.0,377.0>-<405.0,370.0>>/B<<405.0,370.0>-<437.0,367.0>-<472.5,349.5>> = 12.357092600350505

	* uni046E (U+046E): B<<498.0,402.0>-<452.0,377.0>-<395.0,370.0>>/B<<395.0,370.0>-<427.0,367.0>-<462.5,349.5>> = 12.357092600350505

	* uni0498 (U+0498): B<<508.0,402.0>-<462.0,377.0>-<405.0,370.0>>/B<<405.0,370.0>-<437.0,367.0>-<472.5,349.5>> = 12.357092600350505

	* uni04DE (U+04DE): B<<508.0,402.0>-<462.0,377.0>-<405.0,370.0>>/B<<405.0,370.0>-<437.0,367.0>-<472.5,349.5>> = 12.357092600350505

	* uni0506 (U+0506): B<<476.0,402.0>-<430.0,377.0>-<373.0,370.0>>/B<<373.0,370.0>-<394.0,368.0>-<419.0,362.5>> = 12.4415995885008

	* uni1D95 (U+1D95): L<<449.0,-39.0>--<496.0,217.0>>/B<<496.0,217.0>-<474.0,159.0>-<431.5,107.0>> = 10.368961953607531

	* uni210A (U+210A): B<<93.5,165.0>-<104.0,193.0>-<117.0,209.0>>/L<<117.0,209.0>--<52.0,145.0>> = 6.350285546882426 

	* And 6 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-jaggy-segments]
</div></details><br></div></details><details><summary><b>[14] NotoSerif-ExtraBold.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* 🔥 **FAIL** Missing required codepoints:

	- 0x00AF (MACRON)
 [code: missing-codepoints]
</div></details><details><summary>🔥 <b>FAIL:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* 🔥 **FAIL** License file OFL.txt exists but NameID 13 (LICENSE DESCRIPTION) value on platform 3 (WINDOWS) is not specified for that. Value was: "This Font Software is licensed under the SIL Open Font License, Version 1.1. This Font Software is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the SIL Open Font License for the specific language, permissions and limitations governing your use of this Font Software." Must be changed to "This Font Software is licensed under the SIL Open Font License, Version 1.1. This license is available with a FAQ at: https://scripts.sil.org/OFL" [code: wrong]
</div></details><details><summary>🔥 <b>FAIL:</b> OS/2.fsSelection bit 7 (USE_TYPO_METRICS) is set in all fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/os2/use_typo_metrics">com.google.fonts/check/os2/use_typo_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2.fsSelection bit 7 (USE_TYPO_METRICS) wasNOT set in the following fonts: ['fonts/NotoSerif-Italic/googlefonts/slim-variable-ttf/NotoSerif-ItalicMM[wght].ttf', 'fonts/NotoSerif-Italic/googlefonts/slim-variable-ttf/NotoSerif-MM[wght].ttf', 'fonts/NotoSerif-Italic/googlefonts/ttf/NotoSerif-Black.ttf', 'fonts/NotoSerif-Italic/googlefonts/ttf/NotoSerif-BlackItalic.ttf', 'fonts/NotoSerif-Italic/googlefonts/ttf/NotoSerif-Bold.ttf', 'fonts/NotoSerif-Italic/googlefonts/ttf/NotoSerif-BoldItalic.ttf', 'fonts/NotoSerif-Italic/googlefonts/ttf/NotoSerif-ExtraBold.ttf', 'fonts/NotoSerif-Italic/googlefonts/ttf/NotoSerif-ExtraBoldItalic.ttf', 'fonts/NotoSerif-Italic/googlefonts/ttf/NotoSerif-ExtraLight.ttf', 'fonts/NotoSerif-Italic/googlefonts/ttf/NotoSerif-ExtraLightItalic.ttf', 'fonts/NotoSerif-Italic/googlefonts/ttf/NotoSerif-Italic.ttf', 'fonts/NotoSerif-Italic/googlefonts/ttf/NotoSerif-Light.ttf', 'fonts/NotoSerif-Italic/googlefonts/ttf/NotoSerif-LightItalic.ttf', 'fonts/NotoSerif-Italic/googlefonts/ttf/NotoSerif-Medium.ttf', 'fonts/NotoSerif-Italic/googlefonts/ttf/NotoSerif-MediumItalic.ttf', 'fonts/NotoSerif-Italic/googlefonts/ttf/NotoSerif-Regular.ttf', 'fonts/NotoSerif-Italic/googlefonts/ttf/NotoSerif-SemiBold.ttf', 'fonts/NotoSerif-Italic/googlefonts/ttf/NotoSerif-SemiBoldItalic.ttf', 'fonts/NotoSerif-Italic/googlefonts/ttf/NotoSerif-Thin.ttf', 'fonts/NotoSerif-Italic/googlefonts/ttf/NotoSerif-ThinItalic.ttf', 'fonts/NotoSerif-Italic/googlefonts/variable-ttf/NotoSerif-ItalicMM[wdth,wght].ttf', 'fonts/NotoSerif-Italic/googlefonts/variable-ttf/NotoSerif-MM[CTGR,wdth,wght].ttf']. [code: missing-os2-fsselection-bit7]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinAscent value should be equal or greater than 1080, but got 1069 instead [code: ascent]
* 🔥 **FAIL** OS/2.usWinDescent value should be equal or greater than 389, but got 293 instead. [code: descent]
</div></details><details><summary>⚠ <b>WARN:</b> Is there kerning info for non-ligated sequences? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/kerning_for_non_ligated_sequences">com.google.fonts/check/kerning_for_non_ligated_sequences</a>)</summary><div>


* ⚠ **WARN** GPOS table lacks kerning info for the following non-ligated sequences:

	- f + f

	- f + i

	- i + f

	- f + l

	- l + f 

	- And i + l [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure Stylistic Sets have description. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/stylisticset_description">com.google.fonts/check/stylisticset_description</a>)</summary><div>


* ⚠ **WARN** The stylistic set ss03 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss06 lacks a description string on the 'name' table. [code: missing-description]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Glyph names are all valid? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/valid_glyphnames">com.google.fonts/check/valid_glyphnames</a>)</summary><div>


* ⚠ **WARN** The following glyph names may be too long for some legacy systems which may expect a maximum 31-char length limit:
kavykawithkavykaaboveinvertedlow [code: legacy-long-names]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- uni03B1030603140300

	- uni1FCD0306

	- uni1FDE0306

	- uni03C5030803040301

	- uni03B9030603140300

	- uni03B9030803040300

	- uni03B9030603130301

	- uni03C5030803060301

	- uni03C5030603140301

	- uni03C5030403140301 

	- And 31 more.

Use -F or --full-lists to disable shortening of long lists.
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character (codepoint 0x00AD) which is supposed to be zero-width and invisible, and is used to mark a hyphenation possibility within a word in the absence of or overriding dictionary hyphenation. It is mostly an obsolete mechanism now, and the character is only included in fonts for legacy codepage coverage. [code: softhyphen]
* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: uni00AD	Contours detected: 1	Expected: 0

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uni01E5	Contours detected: 3	Expected: 2

	- Glyph name: uni01EA	Contours detected: 3	Expected: 2

	- Glyph name: uni01EB	Contours detected: 3	Expected: 2

	- Glyph name: uni01EC	Contours detected: 4	Expected: 3

	- Glyph name: uni01ED	Contours detected: 4	Expected: 3

	- Glyph name: uni01F5	Contours detected: 4	Expected: 3 

	- And 41 more.

Use -F or --full-lists to disable shortening of long lists.
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check mark characters are in GDEF mark glyph class. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_mark_chars">com.google.fonts/check/gdef_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following mark characters could be in the GDEF mark glyph class:
	 uni0488 (U+0488), uni0489 (U+0489), uni1ABE (U+1ABE), uniA670 (U+A670), uniA671 (U+A671) and uniA672 (U+A672) [code: mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* Zpalatalhook (U+A7C6): L<<651.0,219.0>--<646.0,0.0>> -> L<<646.0,0.0>--<646.0,-47.0>>

	* beta (U+03B2): L<<68.0,-229.0>--<71.0,112.0>> -> L<<71.0,112.0>--<66.0,509.0>>

	* cpalatalhook (U+A794): L<<503.0,105.0>--<503.0,105.0>> -> L<<503.0,105.0>--<503.0,105.0>>

	* dzdigraphretroflexhook (U+AB66): L<<1053.0,189.0>--<1048.0,0.0>> -> L<<1048.0,0.0>--<1048.0,-35.0>>

	* rho (U+03C1): L<<51.0,-230.0>--<54.0,84.0>> -> L<<54.0,84.0>--<54.0,263.0>>

	* uni03BC (U+03BC): L<<68.0,-230.0>--<71.0,157.0>> -> L<<71.0,157.0>--<66.0,536.0>>

	* uni03FC (U+03FC): L<<52.0,-82.0>--<54.0,84.0>> -> L<<54.0,84.0>--<54.0,263.0>>

	* uni04B1 (U+04B1): L<<103.0,7.0>--<234.0,7.0>> -> L<<234.0,7.0>--<234.0,7.0>>

	* uni1D5D (U+1D5D): L<<44.0,150.0>--<46.0,354.0>> -> L<<46.0,354.0>--<43.0,592.0>>

	* uni1D66 (U+1D66): L<<44.0,-137.0>--<46.0,67.0>> -> L<<46.0,67.0>--<43.0,305.0>> 

	* And 6 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* eogonek (U+0119): B<<270.5,-58.5>-<297.0,-26.0>-<333.0,-9.0>>/B<<333.0,-9.0>-<329.0,-10.0>-<324.0,-10.0>> = 11.24147876762648

	* uni01B4 (U+01B4): B<<328.5,175.5>-<335.0,150.0>-<337.0,131.0>>/B<<337.0,131.0>-<339.0,153.0>-<345.0,173.0>> = 11.203434865229296

	* uni0233 (U+0233): B<<329.0,175.5>-<335.0,150.0>-<337.0,131.0>>/B<<337.0,131.0>-<339.0,153.0>-<345.0,173.0>> = 11.203434865229296

	* uni0247 (U+0247): L<<215.0,2.0>--<170.0,-129.0>>/L<<170.0,-129.0>--<201.0,7.0>> = 6.11750439301343

	* uni0247 (U+0247): L<<348.0,547.0>--<404.0,714.0>>/L<<404.0,714.0>--<367.0,544.0>> = 6.259048295683005

	* uni024F (U+024F): B<<329.0,175.5>-<335.0,150.0>-<337.0,131.0>>/B<<337.0,131.0>-<339.0,153.0>-<345.0,173.0>> = 11.203434865229296

	* uni028E (U+028E): B<<254.0,360.5>-<248.0,386.0>-<246.0,405.0>>/B<<246.0,405.0>-<244.0,383.0>-<238.0,363.0>> = 11.203434865229296

	* uni02B8 (U+02B8): B<<214.0,392.5>-<218.0,377.0>-<219.0,366.0>>/B<<219.0,366.0>-<220.0,379.0>-<224.0,391.0>> = 9.593134262730318

	* uni0377 (U+0377): B<<443.5,261.5>-<460.0,318.0>-<487.0,376.0>>/L<<487.0,376.0>--<199.0,0.0>> = 12.487788400929684

	* uni03F0 (U+03F0): B<<255.0,221.5>-<239.0,183.0>-<226.0,159.0>>/L<<226.0,159.0>--<509.0,536.0>> = 8.451277793680566 

	* And 24 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-jaggy-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

	* eta (U+03B7): L<<605.0,358.0>--<609.0,-230.0>>

	* etatonos (U+03AE): L<<605.0,358.0>--<609.0,-230.0>>

	* iota (U+03B9): L<<69.0,166.0>--<66.0,536.0>>

	* iotadieresis (U+03CA): L<<69.0,166.0>--<66.0,536.0>>

	* iotadieresistonos (U+0390): L<<69.0,166.0>--<66.0,536.0>>

	* iotatonos (U+03AF): L<<69.0,166.0>--<66.0,536.0>>

	* kappa (U+03BA): L<<49.0,0.0>--<46.0,536.0>>

	* sterling (U+00A3): L<<442.0,340.0>--<284.0,341.0>>

	* uni0269 (U+0269): L<<69.0,166.0>--<66.0,536.0>>

	* uni03BC (U+03BC): L<<388.0,235.0>--<386.0,536.0>> 

	* And 47 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-semi-vertical]
</div></details><br></div></details><details><summary><b>[13] NotoSerif-ExtraBoldItalic.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* 🔥 **FAIL** Missing required codepoints:

	- 0x00AF (MACRON)
 [code: missing-codepoints]
</div></details><details><summary>🔥 <b>FAIL:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* 🔥 **FAIL** License file OFL.txt exists but NameID 13 (LICENSE DESCRIPTION) value on platform 3 (WINDOWS) is not specified for that. Value was: "This Font Software is licensed under the SIL Open Font License, Version 1.1. This Font Software is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the SIL Open Font License for the specific language, permissions and limitations governing your use of this Font Software." Must be changed to "This Font Software is licensed under the SIL Open Font License, Version 1.1. This license is available with a FAQ at: https://scripts.sil.org/OFL" [code: wrong]
</div></details><details><summary>🔥 <b>FAIL:</b> OS/2.fsSelection bit 7 (USE_TYPO_METRICS) is set in all fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/os2/use_typo_metrics">com.google.fonts/check/os2/use_typo_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2.fsSelection bit 7 (USE_TYPO_METRICS) wasNOT set in the following fonts: ['fonts/NotoSerif-Italic/googlefonts/slim-variable-ttf/NotoSerif-ItalicMM[wght].ttf', 'fonts/NotoSerif-Italic/googlefonts/slim-variable-ttf/NotoSerif-MM[wght].ttf', 'fonts/NotoSerif-Italic/googlefonts/ttf/NotoSerif-Black.ttf', 'fonts/NotoSerif-Italic/googlefonts/ttf/NotoSerif-BlackItalic.ttf', 'fonts/NotoSerif-Italic/googlefonts/ttf/NotoSerif-Bold.ttf', 'fonts/NotoSerif-Italic/googlefonts/ttf/NotoSerif-BoldItalic.ttf', 'fonts/NotoSerif-Italic/googlefonts/ttf/NotoSerif-ExtraBold.ttf', 'fonts/NotoSerif-Italic/googlefonts/ttf/NotoSerif-ExtraBoldItalic.ttf', 'fonts/NotoSerif-Italic/googlefonts/ttf/NotoSerif-ExtraLight.ttf', 'fonts/NotoSerif-Italic/googlefonts/ttf/NotoSerif-ExtraLightItalic.ttf', 'fonts/NotoSerif-Italic/googlefonts/ttf/NotoSerif-Italic.ttf', 'fonts/NotoSerif-Italic/googlefonts/ttf/NotoSerif-Light.ttf', 'fonts/NotoSerif-Italic/googlefonts/ttf/NotoSerif-LightItalic.ttf', 'fonts/NotoSerif-Italic/googlefonts/ttf/NotoSerif-Medium.ttf', 'fonts/NotoSerif-Italic/googlefonts/ttf/NotoSerif-MediumItalic.ttf', 'fonts/NotoSerif-Italic/googlefonts/ttf/NotoSerif-Regular.ttf', 'fonts/NotoSerif-Italic/googlefonts/ttf/NotoSerif-SemiBold.ttf', 'fonts/NotoSerif-Italic/googlefonts/ttf/NotoSerif-SemiBoldItalic.ttf', 'fonts/NotoSerif-Italic/googlefonts/ttf/NotoSerif-Thin.ttf', 'fonts/NotoSerif-Italic/googlefonts/ttf/NotoSerif-ThinItalic.ttf', 'fonts/NotoSerif-Italic/googlefonts/variable-ttf/NotoSerif-ItalicMM[wdth,wght].ttf', 'fonts/NotoSerif-Italic/googlefonts/variable-ttf/NotoSerif-MM[CTGR,wdth,wght].ttf']. [code: missing-os2-fsselection-bit7]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinAscent value should be equal or greater than 1080, but got 1069 instead [code: ascent]
* 🔥 **FAIL** OS/2.usWinDescent value should be equal or greater than 389, but got 293 instead. [code: descent]
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

	- uni03B1030603140300

	- uni1FCD0306

	- uni1FDE0306

	- uni03C5030803040301

	- uni03B9030603140300

	- uni03B9030803040300

	- uni03B9030603130301

	- uni03C5030803060301

	- uni03C5030603140301

	- uni03C5030403140301 

	- And 31 more.

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

	* beta (U+03B2): L<<-53.0,-229.0>--<22.0,112.0>> -> L<<22.0,112.0>--<100.0,509.0>>

	* dzdigraphretroflexhook (U+AB66): L<<1026.0,189.0>--<982.0,1.0>> -> L<<982.0,1.0>--<976.0,-24.0>>

	* f_f (U+FB00): L<<338.0,536.0>--<500.0,536.0>> -> L<<500.0,536.0>--<500.0,536.0>>

	* f_f (U+FB00): L<<500.0,536.0>--<500.0,536.0>> -> L<<500.0,536.0>--<500.0,536.0>>

	* rho (U+03C1): L<<-77.0,-230.0>--<-8.0,84.0>> -> L<<-8.0,84.0>--<29.0,263.0>>

	* uni03BC (U+03BC): L<<-51.0,-230.0>--<32.0,157.0>> -> L<<32.0,157.0>--<106.0,536.0>>

	* uni03FC (U+03FC): L<<-44.0,-82.0>--<-8.0,84.0>> -> L<<-8.0,84.0>--<29.0,263.0>>

	* uni1D0B (U+1D0B): L<<325.0,445.0>--<297.0,325.0>> -> L<<297.0,325.0>--<289.0,293.0>>

	* uni1D5D (U+1D5D): L<<19.0,150.0>--<67.0,354.0>> -> L<<67.0,354.0>--<118.0,592.0>>

	* uni1D66 (U+1D66): L<<-86.0,-233.0>--<-38.0,-29.0>> -> L<<-38.0,-29.0>--<13.0,209.0>> 

	* And 5 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* Ereversedopen (U+A7AB): B<<521.5,402.5>-<476.0,378.0>-<419.0,371.0>>/B<<419.0,371.0>-<451.0,368.0>-<486.5,350.5>> = 12.357092600350505

	* uni0246 (U+0246): L<<319.0,341.0>--<271.0,116.0>>/L<<271.0,116.0>--<372.0,341.0>> = 12.132206814749741

	* uni03F0 (U+03F0): B<<317.5,231.0>-<297.0,181.0>-<276.0,136.0>>/L<<276.0,136.0>--<577.0,536.0>> = 11.944567460972712

	* uni0417 (U+0417): B<<521.5,402.5>-<476.0,378.0>-<419.0,371.0>>/B<<419.0,371.0>-<451.0,368.0>-<486.5,350.5>> = 12.357092600350505

	* uni046E (U+046E): B<<507.5,402.5>-<462.0,378.0>-<405.0,371.0>>/B<<405.0,371.0>-<437.0,368.0>-<473.0,350.5>> = 12.357092600350505

	* uni0498 (U+0498): B<<521.5,402.5>-<476.0,378.0>-<419.0,371.0>>/B<<419.0,371.0>-<451.0,368.0>-<486.5,350.5>> = 12.357092600350505

	* uni04DE (U+04DE): B<<521.5,402.5>-<476.0,378.0>-<419.0,371.0>>/B<<419.0,371.0>-<451.0,368.0>-<486.5,350.5>> = 12.357092600350505

	* uni0506 (U+0506): B<<490.5,402.5>-<445.0,378.0>-<388.0,371.0>>/B<<388.0,371.0>-<409.0,369.0>-<434.0,364.0>> = 12.4415995885008

	* uni1D95 (U+1D95): L<<479.0,-35.0>--<522.0,215.0>>/B<<522.0,215.0>-<499.0,157.0>-<454.0,105.5>> = 11.871505568848043

	* uni210A (U+210A): B<<93.5,165.0>-<104.0,193.0>-<117.0,209.0>>/L<<117.0,209.0>--<52.0,145.0>> = 6.350285546882426 

	* And 8 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-jaggy-segments]
</div></details><br></div></details><details><summary><b>[15] NotoSerif-ExtraLight.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* 🔥 **FAIL** Missing required codepoints:

	- 0x00AF (MACRON)
 [code: missing-codepoints]
</div></details><details><summary>🔥 <b>FAIL:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* 🔥 **FAIL** License file OFL.txt exists but NameID 13 (LICENSE DESCRIPTION) value on platform 3 (WINDOWS) is not specified for that. Value was: "This Font Software is licensed under the SIL Open Font License, Version 1.1. This Font Software is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the SIL Open Font License for the specific language, permissions and limitations governing your use of this Font Software." Must be changed to "This Font Software is licensed under the SIL Open Font License, Version 1.1. This license is available with a FAQ at: https://scripts.sil.org/OFL" [code: wrong]
</div></details><details><summary>🔥 <b>FAIL:</b> OS/2.fsSelection bit 7 (USE_TYPO_METRICS) is set in all fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/os2/use_typo_metrics">com.google.fonts/check/os2/use_typo_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2.fsSelection bit 7 (USE_TYPO_METRICS) wasNOT set in the following fonts: ['fonts/NotoSerif-Italic/googlefonts/slim-variable-ttf/NotoSerif-ItalicMM[wght].ttf', 'fonts/NotoSerif-Italic/googlefonts/slim-variable-ttf/NotoSerif-MM[wght].ttf', 'fonts/NotoSerif-Italic/googlefonts/ttf/NotoSerif-Black.ttf', 'fonts/NotoSerif-Italic/googlefonts/ttf/NotoSerif-BlackItalic.ttf', 'fonts/NotoSerif-Italic/googlefonts/ttf/NotoSerif-Bold.ttf', 'fonts/NotoSerif-Italic/googlefonts/ttf/NotoSerif-BoldItalic.ttf', 'fonts/NotoSerif-Italic/googlefonts/ttf/NotoSerif-ExtraBold.ttf', 'fonts/NotoSerif-Italic/googlefonts/ttf/NotoSerif-ExtraBoldItalic.ttf', 'fonts/NotoSerif-Italic/googlefonts/ttf/NotoSerif-ExtraLight.ttf', 'fonts/NotoSerif-Italic/googlefonts/ttf/NotoSerif-ExtraLightItalic.ttf', 'fonts/NotoSerif-Italic/googlefonts/ttf/NotoSerif-Italic.ttf', 'fonts/NotoSerif-Italic/googlefonts/ttf/NotoSerif-Light.ttf', 'fonts/NotoSerif-Italic/googlefonts/ttf/NotoSerif-LightItalic.ttf', 'fonts/NotoSerif-Italic/googlefonts/ttf/NotoSerif-Medium.ttf', 'fonts/NotoSerif-Italic/googlefonts/ttf/NotoSerif-MediumItalic.ttf', 'fonts/NotoSerif-Italic/googlefonts/ttf/NotoSerif-Regular.ttf', 'fonts/NotoSerif-Italic/googlefonts/ttf/NotoSerif-SemiBold.ttf', 'fonts/NotoSerif-Italic/googlefonts/ttf/NotoSerif-SemiBoldItalic.ttf', 'fonts/NotoSerif-Italic/googlefonts/ttf/NotoSerif-Thin.ttf', 'fonts/NotoSerif-Italic/googlefonts/ttf/NotoSerif-ThinItalic.ttf', 'fonts/NotoSerif-Italic/googlefonts/variable-ttf/NotoSerif-ItalicMM[wdth,wght].ttf', 'fonts/NotoSerif-Italic/googlefonts/variable-ttf/NotoSerif-MM[CTGR,wdth,wght].ttf']. [code: missing-os2-fsselection-bit7]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinAscent value should be equal or greater than 1080, but got 1069 instead [code: ascent]
* 🔥 **FAIL** OS/2.usWinDescent value should be equal or greater than 389, but got 293 instead. [code: descent]
</div></details><details><summary>⚠ <b>WARN:</b> Is there kerning info for non-ligated sequences? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/kerning_for_non_ligated_sequences">com.google.fonts/check/kerning_for_non_ligated_sequences</a>)</summary><div>


* ⚠ **WARN** GPOS table lacks kerning info for the following non-ligated sequences:

	- f + f

	- f + i

	- i + f

	- f + l

	- l + f 

	- And i + l [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Noto Serif ExtraLight' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/googlefonts/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure Stylistic Sets have description. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/stylisticset_description">com.google.fonts/check/stylisticset_description</a>)</summary><div>


* ⚠ **WARN** The stylistic set ss03 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss06 lacks a description string on the 'name' table. [code: missing-description]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Glyph names are all valid? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/valid_glyphnames">com.google.fonts/check/valid_glyphnames</a>)</summary><div>


* ⚠ **WARN** The following glyph names may be too long for some legacy systems which may expect a maximum 31-char length limit:
kavykawithkavykaaboveinvertedlow [code: legacy-long-names]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- uni03B1030603140300

	- uni1FCD0306

	- uni1FDE0306

	- uni03C5030803040301

	- uni03B9030603140300

	- uni03B9030803040300

	- uni03B9030603130301

	- uni03C5030803060301

	- uni03C5030603140301

	- uni03C5030403140301 

	- And 31 more.

Use -F or --full-lists to disable shortening of long lists.
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character (codepoint 0x00AD) which is supposed to be zero-width and invisible, and is used to mark a hyphenation possibility within a word in the absence of or overriding dictionary hyphenation. It is mostly an obsolete mechanism now, and the character is only included in fonts for legacy codepage coverage. [code: softhyphen]
* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: uni00AD	Contours detected: 1	Expected: 0

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uni01E5	Contours detected: 3	Expected: 2

	- Glyph name: uni01EA	Contours detected: 3	Expected: 2

	- Glyph name: uni01EB	Contours detected: 3	Expected: 2

	- Glyph name: uni01EC	Contours detected: 4	Expected: 3

	- Glyph name: uni01ED	Contours detected: 4	Expected: 3

	- Glyph name: uni01F5	Contours detected: 4	Expected: 3 

	- And 41 more.

Use -F or --full-lists to disable shortening of long lists.
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check mark characters are in GDEF mark glyph class. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_mark_chars">com.google.fonts/check/gdef_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following mark characters could be in the GDEF mark glyph class:
	 uni0488 (U+0488), uni0489 (U+0489), uni1ABE (U+1ABE), uniA670 (U+A670), uniA671 (U+A671) and uniA672 (U+A672) [code: mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* Zpalatalhook (U+A7C6): L<<478.0,143.0>--<473.0,0.0>> -> L<<473.0,0.0>--<473.0,-98.0>>

	* beta (U+03B2): L<<59.0,-240.0>--<61.0,120.0>> -> L<<61.0,120.0>--<60.0,560.0>>

	* dzdigraphretroflexhook (U+AB66): L<<823.0,143.0>--<818.0,0.0>> -> L<<818.0,0.0>--<818.0,-93.0>>

	* rho (U+03C1): L<<44.0,-240.0>--<46.0,63.0>> -> L<<46.0,63.0>--<46.0,287.0>>

	* tripledagger (U+2E4B): L<<383.0,304.0>--<220.0,319.0>> -> L<<220.0,319.0>--<218.0,319.0>>

	* uni023E (U+023E): L<<449.0,684.0>--<447.0,684.0>> -> L<<447.0,684.0>--<306.0,684.0>>

	* uni0246 (U+0246): L<<414.0,684.0>--<410.0,684.0>> -> L<<410.0,684.0>--<189.0,684.0>>

	* uni0290 (U+0290): L<<413.0,143.0>--<408.0,0.0>> -> L<<408.0,0.0>--<408.0,-82.0>>

	* uni03BC (U+03BC): L<<59.0,-240.0>--<61.0,134.0>> -> L<<61.0,134.0>--<59.0,536.0>>

	* uni03FC (U+03FC): L<<45.0,-88.0>--<46.0,63.0>> -> L<<46.0,63.0>--<46.0,287.0>> 

	* And 10 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* eth (U+00F0): B<<356.5,474.5>-<399.0,456.0>-<423.0,417.0>>/B<<423.0,417.0>-<401.0,487.0>-<370.5,540.5>> = 14.160313822966648

	* uni1D7A (U+1D7A): B<<463.0,439.0>-<468.0,454.0>-<476.0,467.0>>/L<<476.0,467.0>--<461.0,447.0>> = 5.2623953995950545

	* uni1D7A (U+1D7A): L<<694.0,760.0>--<495.0,493.0>>/B<<495.0,493.0>-<515.0,515.0>-<547.5,529.0>> = 5.575850240977497

	* uni1D95 (U+1D95): L<<435.0,-87.0>--<435.0,229.0>>/B<<435.0,229.0>-<428.0,109.0>-<377.0,49.5>> = 3.338470543764357

	* uni210A (U+210A): B<<93.5,165.0>-<104.0,193.0>-<117.0,209.0>>/L<<117.0,209.0>--<52.0,145.0>> = 6.350285546882426 

	* And uni2133 (U+2133): B<<1101.5,668.0>-<1119.0,688.0>-<1125.0,694.0>>/B<<1125.0,694.0>-<1109.0,683.0>-<1066.5,648.5>> = 10.491477012331565 [code: found-jaggy-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

	* beta (U+03B2): L<<59.0,-240.0>--<61.0,120.0>>

	* beta (U+03B2): L<<61.0,120.0>--<60.0,560.0>>

	* eta (U+03B7): L<<442.0,-240.0>--<447.0,354.0>>

	* eta (U+03B7): L<<485.0,356.0>--<489.0,-240.0>>

	* etatonos (U+03AE): L<<442.0,-240.0>--<447.0,354.0>>

	* etatonos (U+03AE): L<<485.0,356.0>--<489.0,-240.0>>

	* iota (U+03B9): L<<105.0,536.0>--<102.0,138.0>>

	* iota (U+03B9): L<<61.0,139.0>--<59.0,536.0>>

	* iotadieresis (U+03CA): L<<105.0,536.0>--<102.0,138.0>>

	* iotadieresis (U+03CA): L<<61.0,139.0>--<59.0,536.0>> 

	* And 136 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-semi-vertical]
</div></details><br></div></details><details><summary><b>[13] NotoSerif-ExtraLightItalic.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* 🔥 **FAIL** Missing required codepoints:

	- 0x00AF (MACRON)
 [code: missing-codepoints]
</div></details><details><summary>🔥 <b>FAIL:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* 🔥 **FAIL** License file OFL.txt exists but NameID 13 (LICENSE DESCRIPTION) value on platform 3 (WINDOWS) is not specified for that. Value was: "This Font Software is licensed under the SIL Open Font License, Version 1.1. This Font Software is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the SIL Open Font License for the specific language, permissions and limitations governing your use of this Font Software." Must be changed to "This Font Software is licensed under the SIL Open Font License, Version 1.1. This license is available with a FAQ at: https://scripts.sil.org/OFL" [code: wrong]
</div></details><details><summary>🔥 <b>FAIL:</b> OS/2.fsSelection bit 7 (USE_TYPO_METRICS) is set in all fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/os2/use_typo_metrics">com.google.fonts/check/os2/use_typo_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2.fsSelection bit 7 (USE_TYPO_METRICS) wasNOT set in the following fonts: ['fonts/NotoSerif-Italic/googlefonts/slim-variable-ttf/NotoSerif-ItalicMM[wght].ttf', 'fonts/NotoSerif-Italic/googlefonts/slim-variable-ttf/NotoSerif-MM[wght].ttf', 'fonts/NotoSerif-Italic/googlefonts/ttf/NotoSerif-Black.ttf', 'fonts/NotoSerif-Italic/googlefonts/ttf/NotoSerif-BlackItalic.ttf', 'fonts/NotoSerif-Italic/googlefonts/ttf/NotoSerif-Bold.ttf', 'fonts/NotoSerif-Italic/googlefonts/ttf/NotoSerif-BoldItalic.ttf', 'fonts/NotoSerif-Italic/googlefonts/ttf/NotoSerif-ExtraBold.ttf', 'fonts/NotoSerif-Italic/googlefonts/ttf/NotoSerif-ExtraBoldItalic.ttf', 'fonts/NotoSerif-Italic/googlefonts/ttf/NotoSerif-ExtraLight.ttf', 'fonts/NotoSerif-Italic/googlefonts/ttf/NotoSerif-ExtraLightItalic.ttf', 'fonts/NotoSerif-Italic/googlefonts/ttf/NotoSerif-Italic.ttf', 'fonts/NotoSerif-Italic/googlefonts/ttf/NotoSerif-Light.ttf', 'fonts/NotoSerif-Italic/googlefonts/ttf/NotoSerif-LightItalic.ttf', 'fonts/NotoSerif-Italic/googlefonts/ttf/NotoSerif-Medium.ttf', 'fonts/NotoSerif-Italic/googlefonts/ttf/NotoSerif-MediumItalic.ttf', 'fonts/NotoSerif-Italic/googlefonts/ttf/NotoSerif-Regular.ttf', 'fonts/NotoSerif-Italic/googlefonts/ttf/NotoSerif-SemiBold.ttf', 'fonts/NotoSerif-Italic/googlefonts/ttf/NotoSerif-SemiBoldItalic.ttf', 'fonts/NotoSerif-Italic/googlefonts/ttf/NotoSerif-Thin.ttf', 'fonts/NotoSerif-Italic/googlefonts/ttf/NotoSerif-ThinItalic.ttf', 'fonts/NotoSerif-Italic/googlefonts/variable-ttf/NotoSerif-ItalicMM[wdth,wght].ttf', 'fonts/NotoSerif-Italic/googlefonts/variable-ttf/NotoSerif-MM[CTGR,wdth,wght].ttf']. [code: missing-os2-fsselection-bit7]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinAscent value should be equal or greater than 1080, but got 1069 instead [code: ascent]
* 🔥 **FAIL** OS/2.usWinDescent value should be equal or greater than 389, but got 293 instead. [code: descent]
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

	- uni03B1030603140300

	- uni1FCD0306

	- uni1FDE0306

	- uni03C5030803040301

	- uni03B9030603140300

	- uni03B9030803040300

	- uni03B9030603130301

	- uni03C5030803060301

	- uni03C5030603140301

	- uni03C5030403140301 

	- And 31 more.

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

	* Zpalatalhook (U+A7C6): L<<491.0,143.0>--<457.0,9.0>> -> L<<457.0,9.0>--<435.0,-98.0>>

	* beta (U+03B2): L<<-41.0,-240.0>--<36.0,120.0>> -> L<<36.0,120.0>--<129.0,560.0>>

	* rho (U+03C1): L<<-61.0,-240.0>--<4.0,63.0>> -> L<<4.0,63.0>--<52.0,287.0>>

	* tripledagger (U+2E4B): L<<231.0,338.0>--<234.0,338.0>> -> L<<234.0,338.0>--<397.0,347.0>>

	* tripledagger (U+2E4B): L<<387.0,305.0>--<230.0,313.0>> -> L<<230.0,313.0>--<225.0,313.0>>

	* tripledagger (U+2E4B): L<<49.0,347.0>--<207.0,338.0>> -> L<<207.0,338.0>--<207.0,338.0>>

	* uni0246 (U+0246): L<<496.0,684.0>--<490.0,684.0>> -> L<<490.0,684.0>--<272.0,684.0>>

	* uni03BC (U+03BC): L<<-38.0,-240.0>--<42.0,134.0>> -> L<<42.0,134.0>--<124.0,536.0>>

	* uni03FC (U+03FC): L<<-28.0,-88.0>--<4.0,63.0>> -> L<<4.0,63.0>--<52.0,287.0>>

	* uni1D0B (U+1D0B): L<<176.0,451.0>--<141.0,285.0>> -> L<<141.0,285.0>--<130.0,232.0>> 

	* And 9 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* three (U+0033): B<<427.5,442.5>-<381.0,387.0>-<288.0,375.0>>/B<<288.0,375.0>-<323.0,372.0>-<354.0,353.0>> = 12.251471813680151

	* uni0504 (U+0504): B<<404.5,401.5>-<364.0,375.0>-<314.0,368.0>>/B<<314.0,368.0>-<364.0,365.0>-<398.5,340.0>> = 11.403240756771877

	* uni1D95 (U+1D95): L<<313.0,-33.0>--<371.0,217.0>>/B<<371.0,217.0>-<354.0,156.0>-<320.0,104.0>> = 2.51099251348214

	* uni210A (U+210A): B<<93.5,165.0>-<104.0,193.0>-<117.0,209.0>>/L<<117.0,209.0>--<52.0,145.0>> = 6.350285546882426

	* uni210B (U+210B): B<<466.5,433.0>-<506.0,504.0>-<569.0,581.0>>/B<<569.0,581.0>-<545.0,559.0>-<515.5,535.0>> = 8.200146059498772

	* uni2133 (U+2133): B<<1101.5,668.0>-<1119.0,688.0>-<1125.0,694.0>>/B<<1125.0,694.0>-<1109.0,683.0>-<1066.5,648.5>> = 10.491477012331565

	* uniA737 (U+A737): B<<334.0,119.5>-<336.0,132.0>-<339.0,145.0>>/B<<339.0,145.0>-<301.0,70.0>-<252.0,30.0>> = 13.87519629558255 

	* And uniA7A0 (U+A7A0): L<<650.0,354.0>--<492.0,319.0>>/L<<492.0,319.0>--<645.0,319.0>> = 12.49040571790919 [code: found-jaggy-segments]
</div></details><br></div></details><details><summary><b>[21] NotoSerif-Italic.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* 🔥 **FAIL** Missing required codepoints:

	- 0x00AF (MACRON)
 [code: missing-codepoints]
</div></details><details><summary>🔥 <b>FAIL:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* 🔥 **FAIL** License file OFL.txt exists but NameID 13 (LICENSE DESCRIPTION) value on platform 3 (WINDOWS) is not specified for that. Value was: "This Font Software is licensed under the SIL Open Font License, Version 1.1. This Font Software is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the SIL Open Font License for the specific language, permissions and limitations governing your use of this Font Software." Must be changed to "This Font Software is licensed under the SIL Open Font License, Version 1.1. This license is available with a FAQ at: https://scripts.sil.org/OFL" [code: wrong]
</div></details><details><summary>🔥 <b>FAIL:</b> Is the Grid-fitting and Scan-conversion Procedure ('gasp') table set to optimize rendering? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/gasp">com.google.fonts/check/gasp</a>)</summary><div>


* 🔥 **FAIL** Font is missing the 'gasp' table. Try exporting the font with autohinting enabled.
If you are dealing with an unhinted font, it can be fixed by running the fonts through the command 'gftools fix-nonhinting'
GFTools is available at https://pypi.org/project/gftools/ [code: lacks-gasp]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 fsSelection value. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/fsselection">com.google.fonts/check/fsselection</a>)</summary><div>


* 🔥 **FAIL** OS/2 fsSelection REGULAR bit should be unset. [code: bad-REGULAR]
* 🔥 **FAIL** OS/2 fsSelection ITALIC bit should be set. [code: bad-ITALIC]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking head.macStyle value. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/mac_style">com.google.fonts/check/mac_style</a>)</summary><div>


* 🔥 **FAIL** head macStyle ITALIC bit should be set. [code: bad-ITALIC]
</div></details><details><summary>🔥 <b>FAIL:</b> Check name table: FONT_FAMILY_NAME entries. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/familyname">com.google.fonts/check/name/familyname</a>)</summary><div>


* 🔥 **FAIL** Entry [FONT_FAMILY_NAME(1):WINDOWS(3)] on the "name" table: Expected "Noto Serif" but got "Noto Serif Italic". [code: mismatch]
</div></details><details><summary>🔥 <b>FAIL:</b> Check name table: FONT_SUBFAMILY_NAME entries. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/subfamilyname">com.google.fonts/check/name/subfamilyname</a>)</summary><div>


* 🔥 **FAIL** SUBFAMILY_NAME for Win "Regular" must be "Italic" [code: bad-familyname]
</div></details><details><summary>🔥 <b>FAIL:</b> Check name table: TYPOGRAPHIC_FAMILY_NAME entries. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/typographicfamilyname">com.google.fonts/check/name/typographicfamilyname</a>)</summary><div>


* 🔥 **FAIL** Font style is "Italic" and, for that reason, it is not expected to have a [TYPOGRAPHIC_FAMILY_NAME(16):WINDOWS(3)] entry! [code: ribbi]
</div></details><details><summary>🔥 <b>FAIL:</b> Font enables smart dropout control in "prep" table instructions? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/smart_dropout">com.google.fonts/check/smart_dropout</a>)</summary><div>


* 🔥 **FAIL** The 'prep' table does not contain TrueType instructions enabling smart dropout control. To fix, export the font with autohinting enabled, or run ttfautohint on the font, or run the `gftools fix-nonhinting` script. [code: lacks-smart-dropout]
</div></details><details><summary>🔥 <b>FAIL:</b> OS/2.fsSelection bit 7 (USE_TYPO_METRICS) is set in all fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/os2/use_typo_metrics">com.google.fonts/check/os2/use_typo_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2.fsSelection bit 7 (USE_TYPO_METRICS) wasNOT set in the following fonts: ['fonts/NotoSerif-Italic/googlefonts/slim-variable-ttf/NotoSerif-ItalicMM[wght].ttf', 'fonts/NotoSerif-Italic/googlefonts/slim-variable-ttf/NotoSerif-MM[wght].ttf', 'fonts/NotoSerif-Italic/googlefonts/ttf/NotoSerif-Black.ttf', 'fonts/NotoSerif-Italic/googlefonts/ttf/NotoSerif-BlackItalic.ttf', 'fonts/NotoSerif-Italic/googlefonts/ttf/NotoSerif-Bold.ttf', 'fonts/NotoSerif-Italic/googlefonts/ttf/NotoSerif-BoldItalic.ttf', 'fonts/NotoSerif-Italic/googlefonts/ttf/NotoSerif-ExtraBold.ttf', 'fonts/NotoSerif-Italic/googlefonts/ttf/NotoSerif-ExtraBoldItalic.ttf', 'fonts/NotoSerif-Italic/googlefonts/ttf/NotoSerif-ExtraLight.ttf', 'fonts/NotoSerif-Italic/googlefonts/ttf/NotoSerif-ExtraLightItalic.ttf', 'fonts/NotoSerif-Italic/googlefonts/ttf/NotoSerif-Italic.ttf', 'fonts/NotoSerif-Italic/googlefonts/ttf/NotoSerif-Light.ttf', 'fonts/NotoSerif-Italic/googlefonts/ttf/NotoSerif-LightItalic.ttf', 'fonts/NotoSerif-Italic/googlefonts/ttf/NotoSerif-Medium.ttf', 'fonts/NotoSerif-Italic/googlefonts/ttf/NotoSerif-MediumItalic.ttf', 'fonts/NotoSerif-Italic/googlefonts/ttf/NotoSerif-Regular.ttf', 'fonts/NotoSerif-Italic/googlefonts/ttf/NotoSerif-SemiBold.ttf', 'fonts/NotoSerif-Italic/googlefonts/ttf/NotoSerif-SemiBoldItalic.ttf', 'fonts/NotoSerif-Italic/googlefonts/ttf/NotoSerif-Thin.ttf', 'fonts/NotoSerif-Italic/googlefonts/ttf/NotoSerif-ThinItalic.ttf', 'fonts/NotoSerif-Italic/googlefonts/variable-ttf/NotoSerif-ItalicMM[wdth,wght].ttf', 'fonts/NotoSerif-Italic/googlefonts/variable-ttf/NotoSerif-MM[CTGR,wdth,wght].ttf']. [code: missing-os2-fsselection-bit7]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinAscent value should be equal or greater than 1080, but got 1069 instead [code: ascent]
* 🔥 **FAIL** OS/2.usWinDescent value should be equal or greater than 389, but got 293 instead. [code: descent]
</div></details><details><summary>⚠ <b>WARN:</b> Glyphs are similiar to Google Fonts version? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/production_glyphs_similarity">com.google.fonts/check/production_glyphs_similarity</a>)</summary><div>


* ⚠ **WARN** Following glyphs differ greatly from Google Fonts version:
	* uni1D5E
	* uni1F83
	* uni1D33
	* uni1F45
	* uni1DA8
	* uni1FCE
	* uni1F0F
	* uni1FE0
	* uni1D2C
	* uni1FA1 and 357 more.

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

	- uni03B1030603140300

	- uni1FCD0306

	- uni1FDE0306

	- uni03C5030803040301

	- uni03B9030603140300

	- uni03B9030803040300

	- uni03B9030603130301

	- uni03C5030803060301

	- uni03C5030603140301

	- uni03C5030403140301 

	- And 31 more.

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

	* Zpalatalhook (U+A7C6): L<<553.0,175.0>--<518.0,29.0>> -> L<<518.0,29.0>--<498.0,-62.0>>

	* beta (U+03B2): L<<-38.0,-240.0>--<42.0,126.0>> -> L<<42.0,126.0>--<127.0,543.0>>

	* dzdigraphretroflexhook (U+AB66): L<<890.0,162.0>--<851.0,1.0>> -> L<<851.0,1.0>--<844.0,-31.0>>

	* f_f (U+FB00): L<<251.0,536.0>--<454.0,536.0>> -> L<<454.0,536.0>--<454.0,536.0>>

	* f_f (U+FB00): L<<454.0,536.0>--<454.0,536.0>> -> L<<454.0,536.0>--<455.0,536.0>>

	* rho (U+03C1): L<<-59.0,-240.0>--<17.0,109.0>> -> L<<17.0,109.0>--<47.0,253.0>>

	* uni03BC (U+03BC): L<<-34.0,-240.0>--<45.0,126.0>> -> L<<45.0,126.0>--<126.0,536.0>>

	* uni03FC (U+03FC): L<<-24.0,-80.0>--<17.0,109.0>> -> L<<17.0,109.0>--<47.0,253.0>>

	* uni049D (U+049D): L<<200.0,294.0>--<252.0,294.0>> -> L<<252.0,294.0>--<252.0,294.0>>

	* uni049D (U+049D): L<<243.0,248.0>--<242.0,248.0>> -> L<<242.0,248.0>--<190.0,248.0>> 

	* And 7 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* Ereversedopen (U+A7AB): B<<473.5,399.0>-<427.0,374.0>-<370.0,367.0>>/B<<370.0,367.0>-<402.0,364.0>-<437.5,347.0>> = 12.357092600350505

	* uni03D0 (U+03D0): B<<316.0,703.0>-<273.0,681.0>-<238.0,624.0>>/L<<238.0,624.0>--<240.0,627.0>> = 2.1386825776662226

	* uni0417 (U+0417): B<<473.5,399.0>-<427.0,374.0>-<370.0,367.0>>/B<<370.0,367.0>-<402.0,364.0>-<437.5,347.0>> = 12.357092600350505

	* uni046E (U+046E): B<<473.5,399.0>-<427.0,374.0>-<370.0,367.0>>/B<<370.0,367.0>-<402.0,364.0>-<437.5,347.0>> = 12.357092600350505

	* uni0498 (U+0498): B<<473.5,399.0>-<427.0,374.0>-<370.0,367.0>>/B<<370.0,367.0>-<402.0,364.0>-<437.5,347.0>> = 12.357092600350505

	* uni04DE (U+04DE): B<<473.5,399.0>-<427.0,374.0>-<370.0,367.0>>/B<<370.0,367.0>-<402.0,364.0>-<437.5,347.0>> = 12.357092600350505

	* uni0504 (U+0504): B<<438.5,399.0>-<392.0,374.0>-<335.0,367.0>>/B<<335.0,367.0>-<357.0,365.0>-<382.5,358.0>> = 12.19569646523012

	* uni0506 (U+0506): B<<438.5,399.0>-<392.0,374.0>-<335.0,367.0>>/B<<335.0,367.0>-<357.0,365.0>-<382.5,358.0>> = 12.19569646523012

	* uni1D95 (U+1D95): L<<374.0,-49.0>--<431.0,223.0>>/B<<431.0,223.0>-<412.0,163.0>-<374.5,110.0>> = 5.735691697844572

	* uni210A (U+210A): B<<93.5,165.0>-<104.0,193.0>-<117.0,209.0>>/L<<117.0,209.0>--<52.0,145.0>> = 6.350285546882426 

	* And 5 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-jaggy-segments]
</div></details><br></div></details><details><summary><b>[14] NotoSerif-Light.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* 🔥 **FAIL** Missing required codepoints:

	- 0x00AF (MACRON)
 [code: missing-codepoints]
</div></details><details><summary>🔥 <b>FAIL:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* 🔥 **FAIL** License file OFL.txt exists but NameID 13 (LICENSE DESCRIPTION) value on platform 3 (WINDOWS) is not specified for that. Value was: "This Font Software is licensed under the SIL Open Font License, Version 1.1. This Font Software is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the SIL Open Font License for the specific language, permissions and limitations governing your use of this Font Software." Must be changed to "This Font Software is licensed under the SIL Open Font License, Version 1.1. This license is available with a FAQ at: https://scripts.sil.org/OFL" [code: wrong]
</div></details><details><summary>🔥 <b>FAIL:</b> OS/2.fsSelection bit 7 (USE_TYPO_METRICS) is set in all fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/os2/use_typo_metrics">com.google.fonts/check/os2/use_typo_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2.fsSelection bit 7 (USE_TYPO_METRICS) wasNOT set in the following fonts: ['fonts/NotoSerif-Italic/googlefonts/slim-variable-ttf/NotoSerif-ItalicMM[wght].ttf', 'fonts/NotoSerif-Italic/googlefonts/slim-variable-ttf/NotoSerif-MM[wght].ttf', 'fonts/NotoSerif-Italic/googlefonts/ttf/NotoSerif-Black.ttf', 'fonts/NotoSerif-Italic/googlefonts/ttf/NotoSerif-BlackItalic.ttf', 'fonts/NotoSerif-Italic/googlefonts/ttf/NotoSerif-Bold.ttf', 'fonts/NotoSerif-Italic/googlefonts/ttf/NotoSerif-BoldItalic.ttf', 'fonts/NotoSerif-Italic/googlefonts/ttf/NotoSerif-ExtraBold.ttf', 'fonts/NotoSerif-Italic/googlefonts/ttf/NotoSerif-ExtraBoldItalic.ttf', 'fonts/NotoSerif-Italic/googlefonts/ttf/NotoSerif-ExtraLight.ttf', 'fonts/NotoSerif-Italic/googlefonts/ttf/NotoSerif-ExtraLightItalic.ttf', 'fonts/NotoSerif-Italic/googlefonts/ttf/NotoSerif-Italic.ttf', 'fonts/NotoSerif-Italic/googlefonts/ttf/NotoSerif-Light.ttf', 'fonts/NotoSerif-Italic/googlefonts/ttf/NotoSerif-LightItalic.ttf', 'fonts/NotoSerif-Italic/googlefonts/ttf/NotoSerif-Medium.ttf', 'fonts/NotoSerif-Italic/googlefonts/ttf/NotoSerif-MediumItalic.ttf', 'fonts/NotoSerif-Italic/googlefonts/ttf/NotoSerif-Regular.ttf', 'fonts/NotoSerif-Italic/googlefonts/ttf/NotoSerif-SemiBold.ttf', 'fonts/NotoSerif-Italic/googlefonts/ttf/NotoSerif-SemiBoldItalic.ttf', 'fonts/NotoSerif-Italic/googlefonts/ttf/NotoSerif-Thin.ttf', 'fonts/NotoSerif-Italic/googlefonts/ttf/NotoSerif-ThinItalic.ttf', 'fonts/NotoSerif-Italic/googlefonts/variable-ttf/NotoSerif-ItalicMM[wdth,wght].ttf', 'fonts/NotoSerif-Italic/googlefonts/variable-ttf/NotoSerif-MM[CTGR,wdth,wght].ttf']. [code: missing-os2-fsselection-bit7]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinAscent value should be equal or greater than 1080, but got 1069 instead [code: ascent]
* 🔥 **FAIL** OS/2.usWinDescent value should be equal or greater than 389, but got 293 instead. [code: descent]
</div></details><details><summary>⚠ <b>WARN:</b> Is there kerning info for non-ligated sequences? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/kerning_for_non_ligated_sequences">com.google.fonts/check/kerning_for_non_ligated_sequences</a>)</summary><div>


* ⚠ **WARN** GPOS table lacks kerning info for the following non-ligated sequences:

	- f + f

	- f + i

	- i + f

	- f + l

	- l + f 

	- And i + l [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure Stylistic Sets have description. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/stylisticset_description">com.google.fonts/check/stylisticset_description</a>)</summary><div>


* ⚠ **WARN** The stylistic set ss03 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss06 lacks a description string on the 'name' table. [code: missing-description]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Glyph names are all valid? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/valid_glyphnames">com.google.fonts/check/valid_glyphnames</a>)</summary><div>


* ⚠ **WARN** The following glyph names may be too long for some legacy systems which may expect a maximum 31-char length limit:
kavykawithkavykaaboveinvertedlow [code: legacy-long-names]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- uni03B1030603140300

	- uni1FCD0306

	- uni1FDE0306

	- uni03C5030803040301

	- uni03B9030603140300

	- uni03B9030803040300

	- uni03B9030603130301

	- uni03C5030803060301

	- uni03C5030603140301

	- uni03C5030403140301 

	- And 31 more.

Use -F or --full-lists to disable shortening of long lists.
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character (codepoint 0x00AD) which is supposed to be zero-width and invisible, and is used to mark a hyphenation possibility within a word in the absence of or overriding dictionary hyphenation. It is mostly an obsolete mechanism now, and the character is only included in fonts for legacy codepage coverage. [code: softhyphen]
* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: uni00AD	Contours detected: 1	Expected: 0

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uni01E5	Contours detected: 3	Expected: 2

	- Glyph name: uni01EA	Contours detected: 3	Expected: 2

	- Glyph name: uni01EB	Contours detected: 3	Expected: 2

	- Glyph name: uni01EC	Contours detected: 4	Expected: 3

	- Glyph name: uni01ED	Contours detected: 4	Expected: 3

	- Glyph name: uni01F5	Contours detected: 4	Expected: 3 

	- And 41 more.

Use -F or --full-lists to disable shortening of long lists.
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check mark characters are in GDEF mark glyph class. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_mark_chars">com.google.fonts/check/gdef_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following mark characters could be in the GDEF mark glyph class:
	 uni0488 (U+0488), uni0489 (U+0489), uni1ABE (U+1ABE), uniA670 (U+A670), uniA671 (U+A671) and uniA672 (U+A672) [code: mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* Zpalatalhook (U+A7C6): L<<508.0,157.0>--<503.0,0.0>> -> L<<503.0,0.0>--<503.0,-83.0>>

	* beta (U+03B2): L<<63.0,-240.0>--<65.0,122.0>> -> L<<65.0,122.0>--<64.0,553.0>>

	* dzdigraphretroflexhook (U+AB66): L<<858.0,151.0>--<853.0,0.0>> -> L<<853.0,0.0>--<853.0,-80.0>>

	* rho (U+03C1): L<<48.0,-240.0>--<50.0,83.0>> -> L<<50.0,83.0>--<50.0,273.0>>

	* uni0290 (U+0290): L<<431.0,151.0>--<426.0,0.0>> -> L<<426.0,0.0>--<426.0,-68.0>>

	* uni03BC (U+03BC): L<<64.0,-240.0>--<66.0,131.0>> -> L<<66.0,131.0>--<63.0,536.0>>

	* uni03FC (U+03FC): L<<49.0,-85.0>--<50.0,83.0>> -> L<<50.0,83.0>--<50.0,273.0>>

	* uni04B1 (U+04B1): L<<312.0,0.0>--<312.0,0.0>> -> L<<312.0,0.0>--<438.0,0.0>>

	* uni1D5D (U+1D5D): L<<41.0,143.0>--<42.0,360.0>> -> L<<42.0,360.0>--<42.0,619.0>>

	* uni1D66 (U+1D66): L<<41.0,-188.0>--<42.0,30.0>> -> L<<42.0,30.0>--<42.0,288.0>> 

	* And 7 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* uni1D95 (U+1D95): L<<453.0,-71.0>--<453.0,226.0>>/B<<453.0,226.0>-<445.0,108.0>-<391.5,49.0>> = 3.8785245028476374

	* uni210A (U+210A): B<<93.5,165.0>-<104.0,193.0>-<117.0,209.0>>/L<<117.0,209.0>--<52.0,145.0>> = 6.350285546882426

	* uni2133 (U+2133): B<<1101.5,668.0>-<1119.0,688.0>-<1125.0,694.0>>/B<<1125.0,694.0>-<1109.0,683.0>-<1066.5,648.5>> = 10.491477012331565

	* uni2C66 (U+2C66): B<<159.0,137.0>-<159.0,130.0>-<159.0,124.0>>/L<<159.0,124.0>--<243.0,494.0>> = 12.790879201158143 

	* And uniA7A0 (U+A7A0): L<<676.0,376.0>--<456.0,326.0>>/L<<456.0,326.0>--<669.0,326.0>> = 12.80426606528674 [code: found-jaggy-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

	* beta (U+03B2): L<<63.0,-240.0>--<65.0,122.0>>

	* beta (U+03B2): L<<65.0,122.0>--<64.0,553.0>>

	* eta (U+03B7): L<<191.0,326.0>--<193.0,0.0>>

	* eta (U+03B7): L<<509.0,353.0>--<513.0,-240.0>>

	* etatonos (U+03AE): L<<191.0,326.0>--<193.0,0.0>>

	* etatonos (U+03AE): L<<509.0,353.0>--<513.0,-240.0>>

	* iota (U+03B9): L<<65.0,141.0>--<63.0,536.0>>

	* iotadieresis (U+03CA): L<<65.0,141.0>--<63.0,536.0>>

	* iotadieresistonos (U+0390): L<<65.0,141.0>--<63.0,536.0>>

	* iotatonos (U+03AF): L<<65.0,141.0>--<63.0,536.0>> 

	* And 89 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-semi-vertical]
</div></details><br></div></details><details><summary><b>[13] NotoSerif-LightItalic.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* 🔥 **FAIL** Missing required codepoints:

	- 0x00AF (MACRON)
 [code: missing-codepoints]
</div></details><details><summary>🔥 <b>FAIL:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* 🔥 **FAIL** License file OFL.txt exists but NameID 13 (LICENSE DESCRIPTION) value on platform 3 (WINDOWS) is not specified for that. Value was: "This Font Software is licensed under the SIL Open Font License, Version 1.1. This Font Software is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the SIL Open Font License for the specific language, permissions and limitations governing your use of this Font Software." Must be changed to "This Font Software is licensed under the SIL Open Font License, Version 1.1. This license is available with a FAQ at: https://scripts.sil.org/OFL" [code: wrong]
</div></details><details><summary>🔥 <b>FAIL:</b> OS/2.fsSelection bit 7 (USE_TYPO_METRICS) is set in all fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/os2/use_typo_metrics">com.google.fonts/check/os2/use_typo_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2.fsSelection bit 7 (USE_TYPO_METRICS) wasNOT set in the following fonts: ['fonts/NotoSerif-Italic/googlefonts/slim-variable-ttf/NotoSerif-ItalicMM[wght].ttf', 'fonts/NotoSerif-Italic/googlefonts/slim-variable-ttf/NotoSerif-MM[wght].ttf', 'fonts/NotoSerif-Italic/googlefonts/ttf/NotoSerif-Black.ttf', 'fonts/NotoSerif-Italic/googlefonts/ttf/NotoSerif-BlackItalic.ttf', 'fonts/NotoSerif-Italic/googlefonts/ttf/NotoSerif-Bold.ttf', 'fonts/NotoSerif-Italic/googlefonts/ttf/NotoSerif-BoldItalic.ttf', 'fonts/NotoSerif-Italic/googlefonts/ttf/NotoSerif-ExtraBold.ttf', 'fonts/NotoSerif-Italic/googlefonts/ttf/NotoSerif-ExtraBoldItalic.ttf', 'fonts/NotoSerif-Italic/googlefonts/ttf/NotoSerif-ExtraLight.ttf', 'fonts/NotoSerif-Italic/googlefonts/ttf/NotoSerif-ExtraLightItalic.ttf', 'fonts/NotoSerif-Italic/googlefonts/ttf/NotoSerif-Italic.ttf', 'fonts/NotoSerif-Italic/googlefonts/ttf/NotoSerif-Light.ttf', 'fonts/NotoSerif-Italic/googlefonts/ttf/NotoSerif-LightItalic.ttf', 'fonts/NotoSerif-Italic/googlefonts/ttf/NotoSerif-Medium.ttf', 'fonts/NotoSerif-Italic/googlefonts/ttf/NotoSerif-MediumItalic.ttf', 'fonts/NotoSerif-Italic/googlefonts/ttf/NotoSerif-Regular.ttf', 'fonts/NotoSerif-Italic/googlefonts/ttf/NotoSerif-SemiBold.ttf', 'fonts/NotoSerif-Italic/googlefonts/ttf/NotoSerif-SemiBoldItalic.ttf', 'fonts/NotoSerif-Italic/googlefonts/ttf/NotoSerif-Thin.ttf', 'fonts/NotoSerif-Italic/googlefonts/ttf/NotoSerif-ThinItalic.ttf', 'fonts/NotoSerif-Italic/googlefonts/variable-ttf/NotoSerif-ItalicMM[wdth,wght].ttf', 'fonts/NotoSerif-Italic/googlefonts/variable-ttf/NotoSerif-MM[CTGR,wdth,wght].ttf']. [code: missing-os2-fsselection-bit7]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinAscent value should be equal or greater than 1080, but got 1069 instead [code: ascent]
* 🔥 **FAIL** OS/2.usWinDescent value should be equal or greater than 389, but got 293 instead. [code: descent]
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

	- uni03B1030603140300

	- uni1FCD0306

	- uni1FDE0306

	- uni03C5030803040301

	- uni03B9030603140300

	- uni03B9030803040300

	- uni03B9030603130301

	- uni03C5030803060301

	- uni03C5030603140301

	- uni03C5030403140301 

	- And 31 more.

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

	* Zpalatalhook (U+A7C6): L<<517.0,156.0>--<483.0,19.0>> -> L<<483.0,19.0>--<462.0,-83.0>>

	* beta (U+03B2): L<<-40.0,-240.0>--<39.0,122.0>> -> L<<39.0,122.0>--<128.0,553.0>>

	* f_f (U+FB00): L<<221.0,536.0>--<439.0,536.0>> -> L<<439.0,536.0>--<439.0,536.0>>

	* f_f (U+FB00): L<<439.0,536.0>--<439.0,536.0>> -> L<<439.0,536.0>--<439.0,536.0>>

	* rho (U+03C1): L<<-60.0,-240.0>--<10.0,83.0>> -> L<<10.0,83.0>--<50.0,273.0>>

	* s_t (U+FB06): L<<403.0,443.0>--<403.0,443.0>> -> L<<403.0,443.0>--<403.0,443.0>>

	* tripledagger (U+2E4B): L<<242.0,339.0>--<249.0,339.0>> -> L<<249.0,339.0>--<416.0,355.0>>

	* uni0246 (U+0246): L<<494.0,675.0>--<488.0,675.0>> -> L<<488.0,675.0>--<291.0,675.0>>

	* uni03BC (U+03BC): L<<-36.0,-240.0>--<43.0,131.0>> -> L<<43.0,131.0>--<125.0,536.0>>

	* uni03FC (U+03FC): L<<-27.0,-85.0>--<10.0,83.0>> -> L<<10.0,83.0>--<50.0,273.0>> 

	* And 9 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* uni0504 (U+0504): B<<419.0,401.0>-<376.0,375.0>-<323.0,367.0>>/B<<323.0,367.0>-<354.0,365.0>-<384.5,353.5>> = 12.275007466565206

	* uni1D95 (U+1D95): L<<339.0,-40.0>--<396.0,220.0>>/B<<396.0,220.0>-<378.0,159.0>-<342.5,106.5>> = 4.075006763141359

	* uni210A (U+210A): B<<93.5,165.0>-<104.0,193.0>-<117.0,209.0>>/L<<117.0,209.0>--<52.0,145.0>> = 6.350285546882426

	* uni210B (U+210B): B<<466.5,433.0>-<506.0,504.0>-<569.0,581.0>>/B<<569.0,581.0>-<545.0,559.0>-<515.5,535.0>> = 8.200146059498772

	* uni2133 (U+2133): B<<1101.5,668.0>-<1119.0,688.0>-<1125.0,694.0>>/B<<1125.0,694.0>-<1109.0,683.0>-<1066.5,648.5>> = 10.491477012331565 

	* And uniA7A0 (U+A7A0): L<<669.0,362.0>--<497.0,324.0>>/L<<497.0,324.0>--<668.0,324.0>> = 12.458246440004897 [code: found-jaggy-segments]
</div></details><br></div></details><details><summary><b>[14] NotoSerif-Medium.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* 🔥 **FAIL** Missing required codepoints:

	- 0x00AF (MACRON)
 [code: missing-codepoints]
</div></details><details><summary>🔥 <b>FAIL:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* 🔥 **FAIL** License file OFL.txt exists but NameID 13 (LICENSE DESCRIPTION) value on platform 3 (WINDOWS) is not specified for that. Value was: "This Font Software is licensed under the SIL Open Font License, Version 1.1. This Font Software is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the SIL Open Font License for the specific language, permissions and limitations governing your use of this Font Software." Must be changed to "This Font Software is licensed under the SIL Open Font License, Version 1.1. This license is available with a FAQ at: https://scripts.sil.org/OFL" [code: wrong]
</div></details><details><summary>🔥 <b>FAIL:</b> OS/2.fsSelection bit 7 (USE_TYPO_METRICS) is set in all fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/os2/use_typo_metrics">com.google.fonts/check/os2/use_typo_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2.fsSelection bit 7 (USE_TYPO_METRICS) wasNOT set in the following fonts: ['fonts/NotoSerif-Italic/googlefonts/slim-variable-ttf/NotoSerif-ItalicMM[wght].ttf', 'fonts/NotoSerif-Italic/googlefonts/slim-variable-ttf/NotoSerif-MM[wght].ttf', 'fonts/NotoSerif-Italic/googlefonts/ttf/NotoSerif-Black.ttf', 'fonts/NotoSerif-Italic/googlefonts/ttf/NotoSerif-BlackItalic.ttf', 'fonts/NotoSerif-Italic/googlefonts/ttf/NotoSerif-Bold.ttf', 'fonts/NotoSerif-Italic/googlefonts/ttf/NotoSerif-BoldItalic.ttf', 'fonts/NotoSerif-Italic/googlefonts/ttf/NotoSerif-ExtraBold.ttf', 'fonts/NotoSerif-Italic/googlefonts/ttf/NotoSerif-ExtraBoldItalic.ttf', 'fonts/NotoSerif-Italic/googlefonts/ttf/NotoSerif-ExtraLight.ttf', 'fonts/NotoSerif-Italic/googlefonts/ttf/NotoSerif-ExtraLightItalic.ttf', 'fonts/NotoSerif-Italic/googlefonts/ttf/NotoSerif-Italic.ttf', 'fonts/NotoSerif-Italic/googlefonts/ttf/NotoSerif-Light.ttf', 'fonts/NotoSerif-Italic/googlefonts/ttf/NotoSerif-LightItalic.ttf', 'fonts/NotoSerif-Italic/googlefonts/ttf/NotoSerif-Medium.ttf', 'fonts/NotoSerif-Italic/googlefonts/ttf/NotoSerif-MediumItalic.ttf', 'fonts/NotoSerif-Italic/googlefonts/ttf/NotoSerif-Regular.ttf', 'fonts/NotoSerif-Italic/googlefonts/ttf/NotoSerif-SemiBold.ttf', 'fonts/NotoSerif-Italic/googlefonts/ttf/NotoSerif-SemiBoldItalic.ttf', 'fonts/NotoSerif-Italic/googlefonts/ttf/NotoSerif-Thin.ttf', 'fonts/NotoSerif-Italic/googlefonts/ttf/NotoSerif-ThinItalic.ttf', 'fonts/NotoSerif-Italic/googlefonts/variable-ttf/NotoSerif-ItalicMM[wdth,wght].ttf', 'fonts/NotoSerif-Italic/googlefonts/variable-ttf/NotoSerif-MM[CTGR,wdth,wght].ttf']. [code: missing-os2-fsselection-bit7]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinAscent value should be equal or greater than 1080, but got 1069 instead [code: ascent]
* 🔥 **FAIL** OS/2.usWinDescent value should be equal or greater than 389, but got 293 instead. [code: descent]
</div></details><details><summary>⚠ <b>WARN:</b> Is there kerning info for non-ligated sequences? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/kerning_for_non_ligated_sequences">com.google.fonts/check/kerning_for_non_ligated_sequences</a>)</summary><div>


* ⚠ **WARN** GPOS table lacks kerning info for the following non-ligated sequences:

	- f + f

	- f + i

	- i + f

	- f + l

	- l + f 

	- And i + l [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure Stylistic Sets have description. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/stylisticset_description">com.google.fonts/check/stylisticset_description</a>)</summary><div>


* ⚠ **WARN** The stylistic set ss03 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss06 lacks a description string on the 'name' table. [code: missing-description]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Glyph names are all valid? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/valid_glyphnames">com.google.fonts/check/valid_glyphnames</a>)</summary><div>


* ⚠ **WARN** The following glyph names may be too long for some legacy systems which may expect a maximum 31-char length limit:
kavykawithkavykaaboveinvertedlow [code: legacy-long-names]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- uni03B1030603140300

	- uni1FCD0306

	- uni1FDE0306

	- uni03C5030803040301

	- uni03B9030603140300

	- uni03B9030803040300

	- uni03B9030603130301

	- uni03C5030803060301

	- uni03C5030603140301

	- uni03C5030403140301 

	- And 31 more.

Use -F or --full-lists to disable shortening of long lists.
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character (codepoint 0x00AD) which is supposed to be zero-width and invisible, and is used to mark a hyphenation possibility within a word in the absence of or overriding dictionary hyphenation. It is mostly an obsolete mechanism now, and the character is only included in fonts for legacy codepage coverage. [code: softhyphen]
* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: uni00AD	Contours detected: 1	Expected: 0

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uni01E5	Contours detected: 3	Expected: 2

	- Glyph name: uni01EA	Contours detected: 3	Expected: 2

	- Glyph name: uni01EB	Contours detected: 3	Expected: 2

	- Glyph name: uni01EC	Contours detected: 4	Expected: 3

	- Glyph name: uni01ED	Contours detected: 4	Expected: 3

	- Glyph name: uni01F5	Contours detected: 4	Expected: 3 

	- And 41 more.

Use -F or --full-lists to disable shortening of long lists.
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check mark characters are in GDEF mark glyph class. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_mark_chars">com.google.fonts/check/gdef_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following mark characters could be in the GDEF mark glyph class:
	 uni0488 (U+0488), uni0489 (U+0489), uni1ABE (U+1ABE), uniA670 (U+A670), uniA671 (U+A671) and uniA672 (U+A672) [code: mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* Zpalatalhook (U+A7C6): L<<570.0,184.0>--<565.0,0.0>> -> L<<565.0,0.0>--<565.0,-62.0>>

	* beta (U+03B2): L<<69.0,-240.0>--<73.0,126.0>> -> L<<73.0,126.0>--<69.0,539.0>>

	* dzdigraphretroflexhook (U+AB66): L<<934.0,167.0>--<929.0,0.0>> -> L<<929.0,0.0>--<929.0,-59.0>>

	* rho (U+03C1): L<<53.0,-240.0>--<56.0,113.0>> -> L<<56.0,113.0>--<56.0,256.0>>

	* uni0290 (U+0290): L<<466.0,167.0>--<463.0,0.0>> -> L<<463.0,0.0>--<463.0,-46.0>>

	* uni03BC (U+03BC): L<<70.0,-240.0>--<74.0,112.0>> -> L<<74.0,112.0>--<68.0,536.0>>

	* uni03FC (U+03FC): L<<54.0,-80.0>--<56.0,113.0>> -> L<<56.0,113.0>--<56.0,256.0>>

	* uni1D5D (U+1D5D): L<<45.0,143.0>--<47.0,363.0>> -> L<<47.0,363.0>--<45.0,610.0>>

	* uni1D66 (U+1D66): L<<45.0,-144.0>--<47.0,76.0>> -> L<<47.0,76.0>--<45.0,323.0>>

	* uni1D68 (U+1D68): L<<34.0,-144.0>--<37.0,68.0>> -> L<<37.0,68.0>--<37.0,153.0>> 

	* And 6 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* onequarter (U+00BC): B<<636.5,319.5>-<638.0,338.0>-<640.0,356.0>>/B<<640.0,356.0>-<637.0,348.0>-<632.5,339.5>> = 14.21585347367354

	* threequarters (U+00BE): B<<636.5,319.5>-<638.0,338.0>-<640.0,356.0>>/B<<640.0,356.0>-<637.0,348.0>-<632.5,339.5>> = 14.21585347367354

	* uni0247 (U+0247): L<<230.0,-4.0>--<158.0,-196.0>>/L<<158.0,-196.0>--<197.0,6.0>> = 9.628443063611087

	* uni0247 (U+0247): L<<316.0,545.0>--<380.0,714.0>>/L<<380.0,714.0>--<346.0,540.0>> = 9.685174918189212

	* uni03D7 (U+03D7): B<<550.0,28.0>-<548.0,26.0>-<546.0,25.0>>/L<<546.0,25.0>--<555.0,28.0>> = 8.13010235415587

	* uni1D95 (U+1D95): L<<490.0,-46.0>--<490.0,221.0>>/B<<490.0,221.0>-<479.0,106.0>-<420.5,48.0>> = 5.463842813236589

	* uni2074 (U+2074): B<<198.5,706.5>-<200.0,725.0>-<202.0,743.0>>/B<<202.0,743.0>-<199.0,735.0>-<194.5,726.5>> = 14.21585347367354

	* uni2084 (U+2084): B<<198.5,221.5>-<200.0,240.0>-<202.0,258.0>>/B<<202.0,258.0>-<199.0,250.0>-<194.5,241.5>> = 14.21585347367354

	* uni210A (U+210A): B<<93.5,165.0>-<104.0,193.0>-<117.0,209.0>>/L<<117.0,209.0>--<52.0,145.0>> = 6.350285546882426

	* uni2133 (U+2133): B<<1101.5,668.0>-<1119.0,688.0>-<1125.0,694.0>>/B<<1125.0,694.0>-<1109.0,683.0>-<1066.5,648.5>> = 10.491477012331565 

	* And 3 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-jaggy-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

	* Lstrokesmall (U+1D0C): L<<475.0,171.0>--<474.0,0.0>>

	* eta (U+03B7): L<<236.0,317.0>--<237.0,0.0>>

	* eta (U+03B7): L<<552.0,352.0>--<556.0,-240.0>>

	* etatonos (U+03AE): L<<236.0,317.0>--<237.0,0.0>>

	* etatonos (U+03AE): L<<552.0,352.0>--<556.0,-240.0>>

	* rho (U+03C1): L<<53.0,-240.0>--<56.0,113.0>>

	* sterling (U+00A3): L<<408.0,339.0>--<251.0,340.0>>

	* uni03BC (U+03BC): L<<391.0,191.0>--<388.0,536.0>>

	* uni03DD (U+03DD): L<<410.0,227.0>--<411.0,92.0>>

	* uni04AC (U+04AC): L<<370.0,661.0>--<369.0,111.0>> 

	* And 56 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-semi-vertical]
</div></details><br></div></details><details><summary><b>[13] NotoSerif-MediumItalic.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* 🔥 **FAIL** Missing required codepoints:

	- 0x00AF (MACRON)
 [code: missing-codepoints]
</div></details><details><summary>🔥 <b>FAIL:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* 🔥 **FAIL** License file OFL.txt exists but NameID 13 (LICENSE DESCRIPTION) value on platform 3 (WINDOWS) is not specified for that. Value was: "This Font Software is licensed under the SIL Open Font License, Version 1.1. This Font Software is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the SIL Open Font License for the specific language, permissions and limitations governing your use of this Font Software." Must be changed to "This Font Software is licensed under the SIL Open Font License, Version 1.1. This license is available with a FAQ at: https://scripts.sil.org/OFL" [code: wrong]
</div></details><details><summary>🔥 <b>FAIL:</b> OS/2.fsSelection bit 7 (USE_TYPO_METRICS) is set in all fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/os2/use_typo_metrics">com.google.fonts/check/os2/use_typo_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2.fsSelection bit 7 (USE_TYPO_METRICS) wasNOT set in the following fonts: ['fonts/NotoSerif-Italic/googlefonts/slim-variable-ttf/NotoSerif-ItalicMM[wght].ttf', 'fonts/NotoSerif-Italic/googlefonts/slim-variable-ttf/NotoSerif-MM[wght].ttf', 'fonts/NotoSerif-Italic/googlefonts/ttf/NotoSerif-Black.ttf', 'fonts/NotoSerif-Italic/googlefonts/ttf/NotoSerif-BlackItalic.ttf', 'fonts/NotoSerif-Italic/googlefonts/ttf/NotoSerif-Bold.ttf', 'fonts/NotoSerif-Italic/googlefonts/ttf/NotoSerif-BoldItalic.ttf', 'fonts/NotoSerif-Italic/googlefonts/ttf/NotoSerif-ExtraBold.ttf', 'fonts/NotoSerif-Italic/googlefonts/ttf/NotoSerif-ExtraBoldItalic.ttf', 'fonts/NotoSerif-Italic/googlefonts/ttf/NotoSerif-ExtraLight.ttf', 'fonts/NotoSerif-Italic/googlefonts/ttf/NotoSerif-ExtraLightItalic.ttf', 'fonts/NotoSerif-Italic/googlefonts/ttf/NotoSerif-Italic.ttf', 'fonts/NotoSerif-Italic/googlefonts/ttf/NotoSerif-Light.ttf', 'fonts/NotoSerif-Italic/googlefonts/ttf/NotoSerif-LightItalic.ttf', 'fonts/NotoSerif-Italic/googlefonts/ttf/NotoSerif-Medium.ttf', 'fonts/NotoSerif-Italic/googlefonts/ttf/NotoSerif-MediumItalic.ttf', 'fonts/NotoSerif-Italic/googlefonts/ttf/NotoSerif-Regular.ttf', 'fonts/NotoSerif-Italic/googlefonts/ttf/NotoSerif-SemiBold.ttf', 'fonts/NotoSerif-Italic/googlefonts/ttf/NotoSerif-SemiBoldItalic.ttf', 'fonts/NotoSerif-Italic/googlefonts/ttf/NotoSerif-Thin.ttf', 'fonts/NotoSerif-Italic/googlefonts/ttf/NotoSerif-ThinItalic.ttf', 'fonts/NotoSerif-Italic/googlefonts/variable-ttf/NotoSerif-ItalicMM[wdth,wght].ttf', 'fonts/NotoSerif-Italic/googlefonts/variable-ttf/NotoSerif-MM[CTGR,wdth,wght].ttf']. [code: missing-os2-fsselection-bit7]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinAscent value should be equal or greater than 1080, but got 1069 instead [code: ascent]
* 🔥 **FAIL** OS/2.usWinDescent value should be equal or greater than 389, but got 293 instead. [code: descent]
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

	- uni03B1030603140300

	- uni1FCD0306

	- uni1FDE0306

	- uni03C5030803040301

	- uni03B9030603140300

	- uni03B9030803040300

	- uni03B9030603130301

	- uni03C5030803060301

	- uni03C5030603140301

	- uni03C5030403140301 

	- And 31 more.

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

	* Zpalatalhook (U+A7C6): L<<572.0,184.0>--<533.0,21.0>> -> L<<533.0,21.0>--<515.0,-62.0>>

	* beta (U+03B2): L<<-41.0,-240.0>--<39.0,126.0>> -> L<<39.0,126.0>--<122.0,539.0>>

	* dzdigraphretroflexhook (U+AB66): L<<917.0,167.0>--<877.0,3.0>> -> L<<877.0,3.0>--<870.0,-30.0>>

	* f_f (U+FB00): L<<268.0,536.0>--<463.0,536.0>> -> L<<463.0,536.0>--<463.0,536.0>>

	* f_f (U+FB00): L<<463.0,536.0>--<463.0,536.0>> -> L<<463.0,536.0>--<464.0,536.0>>

	* rho (U+03C1): L<<-63.0,-240.0>--<14.0,113.0>> -> L<<14.0,113.0>--<44.0,256.0>>

	* s_t (U+FB06): L<<451.0,451.0>--<451.0,451.0>> -> L<<451.0,451.0>--<451.0,451.0>>

	* uni023E (U+023E): L<<547.0,661.0>--<546.0,661.0>> -> L<<546.0,661.0>--<454.0,661.0>>

	* uni03BC (U+03BC): L<<-38.0,-240.0>--<39.0,112.0>> -> L<<39.0,112.0>--<122.0,536.0>>

	* uni03FC (U+03FC): L<<-28.0,-80.0>--<14.0,113.0>> -> L<<14.0,113.0>--<44.0,256.0>> 

	* And 8 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* Ereversedopen (U+A7AB): B<<482.5,400.0>-<436.0,375.0>-<380.0,368.0>>/B<<380.0,368.0>-<412.0,364.0>-<447.5,347.5>> = 14.250032697803546

	* onequarter (U+00BC): B<<687.5,318.5>-<693.0,337.0>-<698.0,356.0>>/B<<698.0,356.0>-<693.0,347.0>-<682.5,334.0>> = 14.311041262606366

	* threequarters (U+00BE): B<<687.5,318.5>-<693.0,337.0>-<698.0,356.0>>/B<<698.0,356.0>-<693.0,347.0>-<682.5,334.0>> = 14.311041262606366

	* uni0417 (U+0417): B<<482.5,400.0>-<436.0,375.0>-<380.0,368.0>>/B<<380.0,368.0>-<412.0,364.0>-<447.5,347.5>> = 14.250032697803546

	* uni046E (U+046E): B<<479.5,400.0>-<433.0,375.0>-<377.0,368.0>>/B<<377.0,368.0>-<409.0,364.0>-<444.5,347.5>> = 14.250032697803546

	* uni0498 (U+0498): B<<482.5,400.0>-<436.0,375.0>-<380.0,368.0>>/B<<380.0,368.0>-<412.0,364.0>-<447.5,347.5>> = 14.250032697803546

	* uni04DE (U+04DE): B<<482.5,400.0>-<436.0,375.0>-<380.0,368.0>>/B<<380.0,368.0>-<412.0,364.0>-<447.5,347.5>> = 14.250032697803546

	* uni0504 (U+0504): B<<448.5,400.0>-<402.0,375.0>-<345.0,368.0>>/B<<345.0,368.0>-<377.0,364.0>-<411.5,350.5>> = 14.126283906397104

	* uni0506 (U+0506): B<<448.5,400.0>-<402.0,375.0>-<345.0,368.0>>/B<<345.0,368.0>-<367.0,366.0>-<392.5,359.5>> = 12.19569646523012

	* uni1D95 (U+1D95): L<<395.0,-46.0>--<449.0,221.0>>/B<<449.0,221.0>-<429.0,162.0>-<390.0,109.0>> = 7.292106579845833 

	* And 9 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-jaggy-segments]
</div></details><br></div></details><details><summary><b>[15] NotoSerif-Regular.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* 🔥 **FAIL** Missing required codepoints:

	- 0x00AF (MACRON)
 [code: missing-codepoints]
</div></details><details><summary>🔥 <b>FAIL:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* 🔥 **FAIL** License file OFL.txt exists but NameID 13 (LICENSE DESCRIPTION) value on platform 3 (WINDOWS) is not specified for that. Value was: "This Font Software is licensed under the SIL Open Font License, Version 1.1. This Font Software is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the SIL Open Font License for the specific language, permissions and limitations governing your use of this Font Software." Must be changed to "This Font Software is licensed under the SIL Open Font License, Version 1.1. This license is available with a FAQ at: https://scripts.sil.org/OFL" [code: wrong]
</div></details><details><summary>🔥 <b>FAIL:</b> OS/2.fsSelection bit 7 (USE_TYPO_METRICS) is set in all fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/os2/use_typo_metrics">com.google.fonts/check/os2/use_typo_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2.fsSelection bit 7 (USE_TYPO_METRICS) wasNOT set in the following fonts: ['fonts/NotoSerif-Italic/googlefonts/slim-variable-ttf/NotoSerif-ItalicMM[wght].ttf', 'fonts/NotoSerif-Italic/googlefonts/slim-variable-ttf/NotoSerif-MM[wght].ttf', 'fonts/NotoSerif-Italic/googlefonts/ttf/NotoSerif-Black.ttf', 'fonts/NotoSerif-Italic/googlefonts/ttf/NotoSerif-BlackItalic.ttf', 'fonts/NotoSerif-Italic/googlefonts/ttf/NotoSerif-Bold.ttf', 'fonts/NotoSerif-Italic/googlefonts/ttf/NotoSerif-BoldItalic.ttf', 'fonts/NotoSerif-Italic/googlefonts/ttf/NotoSerif-ExtraBold.ttf', 'fonts/NotoSerif-Italic/googlefonts/ttf/NotoSerif-ExtraBoldItalic.ttf', 'fonts/NotoSerif-Italic/googlefonts/ttf/NotoSerif-ExtraLight.ttf', 'fonts/NotoSerif-Italic/googlefonts/ttf/NotoSerif-ExtraLightItalic.ttf', 'fonts/NotoSerif-Italic/googlefonts/ttf/NotoSerif-Italic.ttf', 'fonts/NotoSerif-Italic/googlefonts/ttf/NotoSerif-Light.ttf', 'fonts/NotoSerif-Italic/googlefonts/ttf/NotoSerif-LightItalic.ttf', 'fonts/NotoSerif-Italic/googlefonts/ttf/NotoSerif-Medium.ttf', 'fonts/NotoSerif-Italic/googlefonts/ttf/NotoSerif-MediumItalic.ttf', 'fonts/NotoSerif-Italic/googlefonts/ttf/NotoSerif-Regular.ttf', 'fonts/NotoSerif-Italic/googlefonts/ttf/NotoSerif-SemiBold.ttf', 'fonts/NotoSerif-Italic/googlefonts/ttf/NotoSerif-SemiBoldItalic.ttf', 'fonts/NotoSerif-Italic/googlefonts/ttf/NotoSerif-Thin.ttf', 'fonts/NotoSerif-Italic/googlefonts/ttf/NotoSerif-ThinItalic.ttf', 'fonts/NotoSerif-Italic/googlefonts/variable-ttf/NotoSerif-ItalicMM[wdth,wght].ttf', 'fonts/NotoSerif-Italic/googlefonts/variable-ttf/NotoSerif-MM[CTGR,wdth,wght].ttf']. [code: missing-os2-fsselection-bit7]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinAscent value should be equal or greater than 1080, but got 1069 instead [code: ascent]
* 🔥 **FAIL** OS/2.usWinDescent value should be equal or greater than 389, but got 293 instead. [code: descent]
</div></details><details><summary>⚠ <b>WARN:</b> Glyphs are similiar to Google Fonts version? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/production_glyphs_similarity">com.google.fonts/check/production_glyphs_similarity</a>)</summary><div>


* ⚠ **WARN** Following glyphs differ greatly from Google Fonts version:
	* uni1D5E
	* uni1F83
	* uni1D33
	* uni1F45
	* uni1DA8
	* uni1FCE
	* uni1FE0
	* uni1D2C
	* nu
	* uni1FA1 and 368 more.

Use -F or --full-lists to disable shortening of long lists.
</div></details><details><summary>⚠ <b>WARN:</b> Is there kerning info for non-ligated sequences? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/kerning_for_non_ligated_sequences">com.google.fonts/check/kerning_for_non_ligated_sequences</a>)</summary><div>


* ⚠ **WARN** GPOS table lacks kerning info for the following non-ligated sequences:

	- f + f

	- f + i

	- i + f

	- f + l

	- l + f 

	- And i + l [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure Stylistic Sets have description. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/stylisticset_description">com.google.fonts/check/stylisticset_description</a>)</summary><div>


* ⚠ **WARN** The stylistic set ss03 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss06 lacks a description string on the 'name' table. [code: missing-description]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Glyph names are all valid? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/valid_glyphnames">com.google.fonts/check/valid_glyphnames</a>)</summary><div>


* ⚠ **WARN** The following glyph names may be too long for some legacy systems which may expect a maximum 31-char length limit:
kavykawithkavykaaboveinvertedlow [code: legacy-long-names]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- uni03B1030603140300

	- uni1FCD0306

	- uni1FDE0306

	- uni03C5030803040301

	- uni03B9030603140300

	- uni03B9030803040300

	- uni03B9030603130301

	- uni03C5030803060301

	- uni03C5030603140301

	- uni03C5030403140301 

	- And 31 more.

Use -F or --full-lists to disable shortening of long lists.
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character (codepoint 0x00AD) which is supposed to be zero-width and invisible, and is used to mark a hyphenation possibility within a word in the absence of or overriding dictionary hyphenation. It is mostly an obsolete mechanism now, and the character is only included in fonts for legacy codepage coverage. [code: softhyphen]
* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: uni00AD	Contours detected: 1	Expected: 0

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uni01E5	Contours detected: 3	Expected: 2

	- Glyph name: uni01EA	Contours detected: 3	Expected: 2

	- Glyph name: uni01EB	Contours detected: 3	Expected: 2

	- Glyph name: uni01EC	Contours detected: 4	Expected: 3

	- Glyph name: uni01ED	Contours detected: 4	Expected: 3

	- Glyph name: uni01F5	Contours detected: 4	Expected: 3 

	- And 43 more.

Use -F or --full-lists to disable shortening of long lists.
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check mark characters are in GDEF mark glyph class. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_mark_chars">com.google.fonts/check/gdef_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following mark characters could be in the GDEF mark glyph class:
	 uni0488 (U+0488), uni0489 (U+0489), uni1ABE (U+1ABE), uniA670 (U+A670), uniA671 (U+A671) and uniA672 (U+A672) [code: mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* Zpalatalhook (U+A7C6): L<<550.0,175.0>--<545.0,0.0>> -> L<<545.0,0.0>--<545.0,-62.0>>

	* beta (U+03B2): L<<68.0,-240.0>--<71.0,126.0>> -> L<<71.0,126.0>--<69.0,543.0>>

	* dzdigraphretroflexhook (U+AB66): L<<905.0,162.0>--<900.0,0.0>> -> L<<900.0,0.0>--<900.0,-62.0>>

	* rho (U+03C1): L<<53.0,-240.0>--<56.0,109.0>> -> L<<56.0,109.0>--<56.0,253.0>>

	* uni0290 (U+0290): L<<455.0,162.0>--<450.0,0.0>> -> L<<450.0,0.0>--<450.0,-49.0>>

	* uni03BC (U+03BC): L<<70.0,-240.0>--<73.0,126.0>> -> L<<73.0,126.0>--<68.0,536.0>>

	* uni03FC (U+03FC): L<<54.0,-80.0>--<56.0,109.0>> -> L<<56.0,109.0>--<56.0,253.0>>

	* uni1D5D (U+1D5D): L<<44.0,143.0>--<46.0,363.0>> -> L<<46.0,363.0>--<45.0,613.0>>

	* uni1D66 (U+1D66): L<<44.0,-144.0>--<46.0,76.0>> -> L<<46.0,76.0>--<45.0,326.0>>

	* uni1D68 (U+1D68): L<<34.0,-144.0>--<36.0,65.0>> -> L<<36.0,65.0>--<36.0,152.0>> 

	* And 6 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* uni03D0 (U+03D0): B<<264.0,703.5>-<224.0,682.0>-<197.0,625.0>>/L<<197.0,625.0>--<198.0,627.0>> = 1.2188752351310335

	* uni03D7 (U+03D7): B<<531.0,29.0>-<527.0,26.0>-<524.0,24.0>>/L<<524.0,24.0>--<536.0,29.0>> = 11.070202577939344

	* uni1D95 (U+1D95): L<<478.0,-49.0>--<478.0,223.0>>/B<<478.0,223.0>-<468.0,107.0>-<411.5,48.5>> = 4.927109947648964

	* uni210A (U+210A): B<<93.5,165.0>-<104.0,193.0>-<117.0,209.0>>/L<<117.0,209.0>--<52.0,145.0>> = 6.350285546882426

	* uni2133 (U+2133): B<<1101.5,668.0>-<1119.0,688.0>-<1125.0,694.0>>/B<<1125.0,694.0>-<1109.0,683.0>-<1066.5,648.5>> = 10.491477012331565

	* uni2137 (U+2137): L<<272.0,0.0>--<233.0,174.0>>/B<<233.0,174.0>-<233.0,126.0>-<214.5,102.0>> = 12.633361935275003

	* uni2C66 (U+2C66): L<<189.0,479.0>--<189.0,209.0>>/L<<189.0,209.0>--<250.0,479.0>> = 12.730868789806387 

	* And uniA7A0 (U+A7A0): L<<695.0,373.0>--<503.0,330.0>>/L<<503.0,330.0>--<695.0,330.0>> = 12.623563597702594 [code: found-jaggy-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

	* beta (U+03B2): L<<68.0,-240.0>--<71.0,126.0>>

	* beta (U+03B2): L<<71.0,126.0>--<69.0,543.0>>

	* eta (U+03B7): L<<542.0,350.0>--<546.0,-240.0>>

	* etatonos (U+03AE): L<<542.0,350.0>--<546.0,-240.0>>

	* iota (U+03B9): L<<71.0,145.0>--<68.0,536.0>>

	* iotadieresis (U+03CA): L<<71.0,145.0>--<68.0,536.0>>

	* iotadieresistonos (U+0390): L<<71.0,145.0>--<68.0,536.0>>

	* iotatonos (U+03AF): L<<71.0,145.0>--<68.0,536.0>>

	* rho (U+03C1): L<<53.0,-240.0>--<56.0,109.0>>

	* tau (U+03C4): L<<293.0,453.0>--<295.0,142.0>> 

	* And 54 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-semi-vertical]
</div></details><br></div></details><details><summary><b>[14] NotoSerif-SemiBold.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* 🔥 **FAIL** Missing required codepoints:

	- 0x00AF (MACRON)
 [code: missing-codepoints]
</div></details><details><summary>🔥 <b>FAIL:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* 🔥 **FAIL** License file OFL.txt exists but NameID 13 (LICENSE DESCRIPTION) value on platform 3 (WINDOWS) is not specified for that. Value was: "This Font Software is licensed under the SIL Open Font License, Version 1.1. This Font Software is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the SIL Open Font License for the specific language, permissions and limitations governing your use of this Font Software." Must be changed to "This Font Software is licensed under the SIL Open Font License, Version 1.1. This license is available with a FAQ at: https://scripts.sil.org/OFL" [code: wrong]
</div></details><details><summary>🔥 <b>FAIL:</b> OS/2.fsSelection bit 7 (USE_TYPO_METRICS) is set in all fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/os2/use_typo_metrics">com.google.fonts/check/os2/use_typo_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2.fsSelection bit 7 (USE_TYPO_METRICS) wasNOT set in the following fonts: ['fonts/NotoSerif-Italic/googlefonts/slim-variable-ttf/NotoSerif-ItalicMM[wght].ttf', 'fonts/NotoSerif-Italic/googlefonts/slim-variable-ttf/NotoSerif-MM[wght].ttf', 'fonts/NotoSerif-Italic/googlefonts/ttf/NotoSerif-Black.ttf', 'fonts/NotoSerif-Italic/googlefonts/ttf/NotoSerif-BlackItalic.ttf', 'fonts/NotoSerif-Italic/googlefonts/ttf/NotoSerif-Bold.ttf', 'fonts/NotoSerif-Italic/googlefonts/ttf/NotoSerif-BoldItalic.ttf', 'fonts/NotoSerif-Italic/googlefonts/ttf/NotoSerif-ExtraBold.ttf', 'fonts/NotoSerif-Italic/googlefonts/ttf/NotoSerif-ExtraBoldItalic.ttf', 'fonts/NotoSerif-Italic/googlefonts/ttf/NotoSerif-ExtraLight.ttf', 'fonts/NotoSerif-Italic/googlefonts/ttf/NotoSerif-ExtraLightItalic.ttf', 'fonts/NotoSerif-Italic/googlefonts/ttf/NotoSerif-Italic.ttf', 'fonts/NotoSerif-Italic/googlefonts/ttf/NotoSerif-Light.ttf', 'fonts/NotoSerif-Italic/googlefonts/ttf/NotoSerif-LightItalic.ttf', 'fonts/NotoSerif-Italic/googlefonts/ttf/NotoSerif-Medium.ttf', 'fonts/NotoSerif-Italic/googlefonts/ttf/NotoSerif-MediumItalic.ttf', 'fonts/NotoSerif-Italic/googlefonts/ttf/NotoSerif-Regular.ttf', 'fonts/NotoSerif-Italic/googlefonts/ttf/NotoSerif-SemiBold.ttf', 'fonts/NotoSerif-Italic/googlefonts/ttf/NotoSerif-SemiBoldItalic.ttf', 'fonts/NotoSerif-Italic/googlefonts/ttf/NotoSerif-Thin.ttf', 'fonts/NotoSerif-Italic/googlefonts/ttf/NotoSerif-ThinItalic.ttf', 'fonts/NotoSerif-Italic/googlefonts/variable-ttf/NotoSerif-ItalicMM[wdth,wght].ttf', 'fonts/NotoSerif-Italic/googlefonts/variable-ttf/NotoSerif-MM[CTGR,wdth,wght].ttf']. [code: missing-os2-fsselection-bit7]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinAscent value should be equal or greater than 1080, but got 1069 instead [code: ascent]
* 🔥 **FAIL** OS/2.usWinDescent value should be equal or greater than 389, but got 293 instead. [code: descent]
</div></details><details><summary>⚠ <b>WARN:</b> Is there kerning info for non-ligated sequences? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/kerning_for_non_ligated_sequences">com.google.fonts/check/kerning_for_non_ligated_sequences</a>)</summary><div>


* ⚠ **WARN** GPOS table lacks kerning info for the following non-ligated sequences:

	- f + f

	- f + i

	- i + f

	- f + l

	- l + f 

	- And i + l [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure Stylistic Sets have description. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/stylisticset_description">com.google.fonts/check/stylisticset_description</a>)</summary><div>


* ⚠ **WARN** The stylistic set ss03 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss06 lacks a description string on the 'name' table. [code: missing-description]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Glyph names are all valid? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/valid_glyphnames">com.google.fonts/check/valid_glyphnames</a>)</summary><div>


* ⚠ **WARN** The following glyph names may be too long for some legacy systems which may expect a maximum 31-char length limit:
kavykawithkavykaaboveinvertedlow [code: legacy-long-names]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- uni03B1030603140300

	- uni1FCD0306

	- uni1FDE0306

	- uni03C5030803040301

	- uni03B9030603140300

	- uni03B9030803040300

	- uni03B9030603130301

	- uni03C5030803060301

	- uni03C5030603140301

	- uni03C5030403140301 

	- And 31 more.

Use -F or --full-lists to disable shortening of long lists.
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character (codepoint 0x00AD) which is supposed to be zero-width and invisible, and is used to mark a hyphenation possibility within a word in the absence of or overriding dictionary hyphenation. It is mostly an obsolete mechanism now, and the character is only included in fonts for legacy codepage coverage. [code: softhyphen]
* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: uni00AD	Contours detected: 1	Expected: 0

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uni01E5	Contours detected: 3	Expected: 2

	- Glyph name: uni01EA	Contours detected: 3	Expected: 2

	- Glyph name: uni01EB	Contours detected: 3	Expected: 2

	- Glyph name: uni01EC	Contours detected: 4	Expected: 3

	- Glyph name: uni01ED	Contours detected: 4	Expected: 3

	- Glyph name: uni01F5	Contours detected: 4	Expected: 3 

	- And 39 more.

Use -F or --full-lists to disable shortening of long lists.
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check mark characters are in GDEF mark glyph class. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_mark_chars">com.google.fonts/check/gdef_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following mark characters could be in the GDEF mark glyph class:
	 uni0488 (U+0488), uni0489 (U+0489), uni1ABE (U+1ABE), uniA670 (U+A670), uniA671 (U+A671) and uniA672 (U+A672) [code: mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* Cpalatalhook (U+A7C4): L<<608.0,114.0>--<608.0,114.0>> -> L<<608.0,114.0>--<608.0,114.0>>

	* Zpalatalhook (U+A7C6): L<<595.0,194.0>--<590.0,0.0>> -> L<<590.0,0.0>--<590.0,-61.0>>

	* beta (U+03B2): L<<71.0,-240.0>--<75.0,126.0>> -> L<<75.0,126.0>--<68.0,533.0>>

	* dzdigraphretroflexhook (U+AB66): L<<970.0,174.0>--<965.0,0.0>> -> L<<965.0,0.0>--<965.0,-55.0>>

	* rho (U+03C1): L<<53.0,-240.0>--<57.0,117.0>> -> L<<57.0,117.0>--<57.0,259.0>>

	* uni0290 (U+0290): L<<480.0,174.0>--<479.0,0.0>> -> L<<479.0,0.0>--<479.0,-43.0>>

	* uni03BC (U+03BC): L<<71.0,-240.0>--<74.0,94.0>> -> L<<74.0,94.0>--<68.0,536.0>>

	* uni03FC (U+03FC): L<<55.0,-81.0>--<57.0,117.0>> -> L<<57.0,117.0>--<57.0,259.0>>

	* uni04FF (U+04FF): L<<253.0,269.0>--<252.0,269.0>> -> L<<252.0,269.0>--<78.0,269.0>>

	* uni1D5D (U+1D5D): L<<46.0,143.0>--<49.0,363.0>> -> L<<49.0,363.0>--<44.0,607.0>> 

	* And 7 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* uni0247 (U+0247): L<<232.0,-3.0>--<186.0,-183.0>>/L<<186.0,-183.0>--<204.0,4.0>> = 8.837272694539108

	* uni0247 (U+0247): L<<319.0,546.0>--<362.0,714.0>>/L<<362.0,714.0>--<345.0,543.0>> = 8.679359291411195

	* uni03F0 (U+03F0): B<<228.0,261.0>-<212.0,203.0>-<195.0,164.0>>/L<<195.0,164.0>--<478.0,536.0>> = 13.709896766824125

	* uni1D95 (U+1D95): L<<505.0,-43.0>--<505.0,219.0>>/B<<505.0,219.0>-<493.0,105.0>-<432.5,47.5>> = 6.009005957494474

	* uni210A (U+210A): B<<93.5,165.0>-<104.0,193.0>-<117.0,209.0>>/L<<117.0,209.0>--<52.0,145.0>> = 6.350285546882426

	* uni2133 (U+2133): B<<1101.5,668.0>-<1119.0,688.0>-<1125.0,694.0>>/B<<1125.0,694.0>-<1109.0,683.0>-<1066.5,648.5>> = 10.491477012331565

	* uni2C66 (U+2C66): L<<226.0,472.0>--<226.0,362.0>>/L<<226.0,362.0>--<254.0,472.0>> = 14.281095735970814 

	* And uniA7A0 (U+A7A0): L<<724.0,382.0>--<509.0,334.0>>/L<<509.0,334.0>--<724.0,334.0>> = 12.585228941050142 [code: found-jaggy-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

	* eta (U+03B7): L<<247.0,313.0>--<249.0,0.0>>

	* eta (U+03B7): L<<564.0,354.0>--<569.0,-240.0>>

	* etatonos (U+03AE): L<<247.0,313.0>--<249.0,0.0>>

	* etatonos (U+03AE): L<<564.0,354.0>--<569.0,-240.0>>

	* h (U+0068): L<<104.0,119.0>--<103.0,648.0>>

	* h (U+0068): L<<233.0,313.0>--<234.0,115.0>>

	* hcircumflex (U+0125): L<<104.0,119.0>--<103.0,648.0>>

	* hcircumflex (U+0125): L<<233.0,313.0>--<234.0,115.0>>

	* hpalatalhook (U+A795): L<<104.0,119.0>--<103.0,648.0>>

	* hpalatalhook (U+A795): L<<233.0,313.0>--<234.0,115.0>> 

	* And 73 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-semi-vertical]
</div></details><br></div></details><details><summary><b>[13] NotoSerif-SemiBoldItalic.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* 🔥 **FAIL** Missing required codepoints:

	- 0x00AF (MACRON)
 [code: missing-codepoints]
</div></details><details><summary>🔥 <b>FAIL:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* 🔥 **FAIL** License file OFL.txt exists but NameID 13 (LICENSE DESCRIPTION) value on platform 3 (WINDOWS) is not specified for that. Value was: "This Font Software is licensed under the SIL Open Font License, Version 1.1. This Font Software is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the SIL Open Font License for the specific language, permissions and limitations governing your use of this Font Software." Must be changed to "This Font Software is licensed under the SIL Open Font License, Version 1.1. This license is available with a FAQ at: https://scripts.sil.org/OFL" [code: wrong]
</div></details><details><summary>🔥 <b>FAIL:</b> OS/2.fsSelection bit 7 (USE_TYPO_METRICS) is set in all fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/os2/use_typo_metrics">com.google.fonts/check/os2/use_typo_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2.fsSelection bit 7 (USE_TYPO_METRICS) wasNOT set in the following fonts: ['fonts/NotoSerif-Italic/googlefonts/slim-variable-ttf/NotoSerif-ItalicMM[wght].ttf', 'fonts/NotoSerif-Italic/googlefonts/slim-variable-ttf/NotoSerif-MM[wght].ttf', 'fonts/NotoSerif-Italic/googlefonts/ttf/NotoSerif-Black.ttf', 'fonts/NotoSerif-Italic/googlefonts/ttf/NotoSerif-BlackItalic.ttf', 'fonts/NotoSerif-Italic/googlefonts/ttf/NotoSerif-Bold.ttf', 'fonts/NotoSerif-Italic/googlefonts/ttf/NotoSerif-BoldItalic.ttf', 'fonts/NotoSerif-Italic/googlefonts/ttf/NotoSerif-ExtraBold.ttf', 'fonts/NotoSerif-Italic/googlefonts/ttf/NotoSerif-ExtraBoldItalic.ttf', 'fonts/NotoSerif-Italic/googlefonts/ttf/NotoSerif-ExtraLight.ttf', 'fonts/NotoSerif-Italic/googlefonts/ttf/NotoSerif-ExtraLightItalic.ttf', 'fonts/NotoSerif-Italic/googlefonts/ttf/NotoSerif-Italic.ttf', 'fonts/NotoSerif-Italic/googlefonts/ttf/NotoSerif-Light.ttf', 'fonts/NotoSerif-Italic/googlefonts/ttf/NotoSerif-LightItalic.ttf', 'fonts/NotoSerif-Italic/googlefonts/ttf/NotoSerif-Medium.ttf', 'fonts/NotoSerif-Italic/googlefonts/ttf/NotoSerif-MediumItalic.ttf', 'fonts/NotoSerif-Italic/googlefonts/ttf/NotoSerif-Regular.ttf', 'fonts/NotoSerif-Italic/googlefonts/ttf/NotoSerif-SemiBold.ttf', 'fonts/NotoSerif-Italic/googlefonts/ttf/NotoSerif-SemiBoldItalic.ttf', 'fonts/NotoSerif-Italic/googlefonts/ttf/NotoSerif-Thin.ttf', 'fonts/NotoSerif-Italic/googlefonts/ttf/NotoSerif-ThinItalic.ttf', 'fonts/NotoSerif-Italic/googlefonts/variable-ttf/NotoSerif-ItalicMM[wdth,wght].ttf', 'fonts/NotoSerif-Italic/googlefonts/variable-ttf/NotoSerif-MM[CTGR,wdth,wght].ttf']. [code: missing-os2-fsselection-bit7]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinAscent value should be equal or greater than 1080, but got 1069 instead [code: ascent]
* 🔥 **FAIL** OS/2.usWinDescent value should be equal or greater than 389, but got 293 instead. [code: descent]
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

	- uni03B1030603140300

	- uni1FCD0306

	- uni1FDE0306

	- uni03C5030803040301

	- uni03B9030603140300

	- uni03B9030803040300

	- uni03B9030603130301

	- uni03C5030803060301

	- uni03C5030603140301

	- uni03C5030403140301 

	- And 31 more.

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

	* Zpalatalhook (U+A7C6): L<<595.0,194.0>--<552.0,12.0>> -> L<<552.0,12.0>--<536.0,-61.0>>

	* beta (U+03B2): L<<-44.0,-240.0>--<36.0,126.0>> -> L<<36.0,126.0>--<116.0,533.0>>

	* dzdigraphretroflexhook (U+AB66): L<<950.0,174.0>--<910.0,4.0>> -> L<<910.0,4.0>--<902.0,-28.0>>

	* rho (U+03C1): L<<-68.0,-240.0>--<10.0,117.0>> -> L<<10.0,117.0>--<40.0,259.0>>

	* uni03BC (U+03BC): L<<-43.0,-240.0>--<31.0,94.0>> -> L<<31.0,94.0>--<117.0,536.0>>

	* uni03FC (U+03FC): L<<-33.0,-81.0>--<10.0,117.0>> -> L<<10.0,117.0>--<40.0,259.0>>

	* uni049D (U+049D): L<<222.0,300.0>--<263.0,300.0>> -> L<<263.0,300.0>--<263.0,300.0>>

	* uni1D0B (U+1D0B): L<<279.0,444.0>--<251.0,319.0>> -> L<<251.0,319.0>--<242.0,277.0>>

	* uni1D5D (U+1D5D): L<<24.0,143.0>--<76.0,363.0>> -> L<<76.0,363.0>--<128.0,607.0>>

	* uni1D66 (U+1D66): L<<-81.0,-240.0>--<-29.0,-20.0>> -> L<<-29.0,-20.0>--<23.0,224.0>> 

	* And 5 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* Ereversedopen (U+A7AB): B<<494.5,401.0>-<448.0,376.0>-<392.0,369.0>>/B<<392.0,369.0>-<424.0,365.0>-<459.5,348.0>> = 14.250032697803546

	* onequarter (U+00BC): B<<694.5,316.0>-<700.0,333.0>-<705.0,352.0>>/B<<705.0,352.0>-<700.0,343.0>-<691.5,332.5>> = 14.311041262606366

	* threequarters (U+00BE): B<<694.5,316.0>-<700.0,333.0>-<705.0,352.0>>/B<<705.0,352.0>-<700.0,343.0>-<691.5,332.5>> = 14.311041262606366

	* uni03F0 (U+03F0): B<<280.5,279.0>-<255.0,207.0>-<221.0,135.0>>/L<<221.0,135.0>--<547.0,536.0>> = 13.832270246884178

	* uni0417 (U+0417): B<<494.5,401.0>-<448.0,376.0>-<392.0,369.0>>/B<<392.0,369.0>-<424.0,365.0>-<459.5,348.0>> = 14.250032697803546

	* uni046E (U+046E): B<<488.0,401.0>-<442.0,376.0>-<386.0,369.0>>/B<<386.0,369.0>-<418.0,365.0>-<453.5,348.0>> = 14.250032697803546

	* uni0498 (U+0498): B<<494.5,401.0>-<448.0,376.0>-<392.0,369.0>>/B<<392.0,369.0>-<424.0,365.0>-<459.5,348.0>> = 14.250032697803546

	* uni04DE (U+04DE): B<<494.5,401.0>-<448.0,376.0>-<392.0,369.0>>/B<<392.0,369.0>-<424.0,365.0>-<459.5,348.0>> = 14.250032697803546

	* uni0506 (U+0506): B<<461.5,401.0>-<415.0,376.0>-<359.0,369.0>>/B<<359.0,369.0>-<380.0,367.0>-<405.5,360.5>> = 12.565348379907268

	* uni1D95 (U+1D95): L<<421.0,-43.0>--<471.0,219.0>>/B<<471.0,219.0>-<450.0,160.0>-<409.5,107.5>> = 8.78788729351228 

	* And 9 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-jaggy-segments]
</div></details><br></div></details><details><summary><b>[14] NotoSerif-Thin.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* 🔥 **FAIL** Missing required codepoints:

	- 0x00AF (MACRON)
 [code: missing-codepoints]
</div></details><details><summary>🔥 <b>FAIL:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* 🔥 **FAIL** License file OFL.txt exists but NameID 13 (LICENSE DESCRIPTION) value on platform 3 (WINDOWS) is not specified for that. Value was: "This Font Software is licensed under the SIL Open Font License, Version 1.1. This Font Software is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the SIL Open Font License for the specific language, permissions and limitations governing your use of this Font Software." Must be changed to "This Font Software is licensed under the SIL Open Font License, Version 1.1. This license is available with a FAQ at: https://scripts.sil.org/OFL" [code: wrong]
</div></details><details><summary>🔥 <b>FAIL:</b> OS/2.fsSelection bit 7 (USE_TYPO_METRICS) is set in all fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/os2/use_typo_metrics">com.google.fonts/check/os2/use_typo_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2.fsSelection bit 7 (USE_TYPO_METRICS) wasNOT set in the following fonts: ['fonts/NotoSerif-Italic/googlefonts/slim-variable-ttf/NotoSerif-ItalicMM[wght].ttf', 'fonts/NotoSerif-Italic/googlefonts/slim-variable-ttf/NotoSerif-MM[wght].ttf', 'fonts/NotoSerif-Italic/googlefonts/ttf/NotoSerif-Black.ttf', 'fonts/NotoSerif-Italic/googlefonts/ttf/NotoSerif-BlackItalic.ttf', 'fonts/NotoSerif-Italic/googlefonts/ttf/NotoSerif-Bold.ttf', 'fonts/NotoSerif-Italic/googlefonts/ttf/NotoSerif-BoldItalic.ttf', 'fonts/NotoSerif-Italic/googlefonts/ttf/NotoSerif-ExtraBold.ttf', 'fonts/NotoSerif-Italic/googlefonts/ttf/NotoSerif-ExtraBoldItalic.ttf', 'fonts/NotoSerif-Italic/googlefonts/ttf/NotoSerif-ExtraLight.ttf', 'fonts/NotoSerif-Italic/googlefonts/ttf/NotoSerif-ExtraLightItalic.ttf', 'fonts/NotoSerif-Italic/googlefonts/ttf/NotoSerif-Italic.ttf', 'fonts/NotoSerif-Italic/googlefonts/ttf/NotoSerif-Light.ttf', 'fonts/NotoSerif-Italic/googlefonts/ttf/NotoSerif-LightItalic.ttf', 'fonts/NotoSerif-Italic/googlefonts/ttf/NotoSerif-Medium.ttf', 'fonts/NotoSerif-Italic/googlefonts/ttf/NotoSerif-MediumItalic.ttf', 'fonts/NotoSerif-Italic/googlefonts/ttf/NotoSerif-Regular.ttf', 'fonts/NotoSerif-Italic/googlefonts/ttf/NotoSerif-SemiBold.ttf', 'fonts/NotoSerif-Italic/googlefonts/ttf/NotoSerif-SemiBoldItalic.ttf', 'fonts/NotoSerif-Italic/googlefonts/ttf/NotoSerif-Thin.ttf', 'fonts/NotoSerif-Italic/googlefonts/ttf/NotoSerif-ThinItalic.ttf', 'fonts/NotoSerif-Italic/googlefonts/variable-ttf/NotoSerif-ItalicMM[wdth,wght].ttf', 'fonts/NotoSerif-Italic/googlefonts/variable-ttf/NotoSerif-MM[CTGR,wdth,wght].ttf']. [code: missing-os2-fsselection-bit7]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinAscent value should be equal or greater than 1080, but got 1069 instead [code: ascent]
* 🔥 **FAIL** OS/2.usWinDescent value should be equal or greater than 389, but got 293 instead. [code: descent]
</div></details><details><summary>⚠ <b>WARN:</b> Is there kerning info for non-ligated sequences? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/kerning_for_non_ligated_sequences">com.google.fonts/check/kerning_for_non_ligated_sequences</a>)</summary><div>


* ⚠ **WARN** GPOS table lacks kerning info for the following non-ligated sequences:

	- f + f

	- f + i

	- i + f

	- f + l

	- l + f 

	- And i + l [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure Stylistic Sets have description. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/stylisticset_description">com.google.fonts/check/stylisticset_description</a>)</summary><div>


* ⚠ **WARN** The stylistic set ss03 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss06 lacks a description string on the 'name' table. [code: missing-description]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Glyph names are all valid? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/valid_glyphnames">com.google.fonts/check/valid_glyphnames</a>)</summary><div>


* ⚠ **WARN** The following glyph names may be too long for some legacy systems which may expect a maximum 31-char length limit:
kavykawithkavykaaboveinvertedlow [code: legacy-long-names]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- uni03B1030603140300

	- uni1FCD0306

	- uni1FDE0306

	- uni03C5030803040301

	- uni03B9030603140300

	- uni03B9030803040300

	- uni03B9030603130301

	- uni03C5030803060301

	- uni03C5030603140301

	- uni03C5030403140301 

	- And 31 more.

Use -F or --full-lists to disable shortening of long lists.
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character (codepoint 0x00AD) which is supposed to be zero-width and invisible, and is used to mark a hyphenation possibility within a word in the absence of or overriding dictionary hyphenation. It is mostly an obsolete mechanism now, and the character is only included in fonts for legacy codepage coverage. [code: softhyphen]
* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: uni00AD	Contours detected: 1	Expected: 0

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uni01E5	Contours detected: 3	Expected: 2

	- Glyph name: uni01EA	Contours detected: 3	Expected: 2

	- Glyph name: uni01EB	Contours detected: 3	Expected: 2

	- Glyph name: uni01EC	Contours detected: 4	Expected: 3

	- Glyph name: uni01ED	Contours detected: 4	Expected: 3

	- Glyph name: uni01F5	Contours detected: 4	Expected: 3 

	- And 41 more.

Use -F or --full-lists to disable shortening of long lists.
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check mark characters are in GDEF mark glyph class. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_mark_chars">com.google.fonts/check/gdef_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following mark characters could be in the GDEF mark glyph class:
	 uni0488 (U+0488), uni0489 (U+0489), uni1ABE (U+1ABE), uniA670 (U+A670), uniA671 (U+A671) and uniA672 (U+A672) [code: mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* Zpalatalhook (U+A7C6): L<<458.0,135.0>--<453.0,0.0>> -> L<<453.0,0.0>--<453.0,-108.0>>

	* beta (U+03B2): L<<56.0,-240.0>--<58.0,118.0>> -> L<<58.0,118.0>--<58.0,565.0>>

	* dzdigraphretroflexhook (U+AB66): L<<801.0,138.0>--<796.0,0.0>> -> L<<796.0,0.0>--<796.0,-101.0>>

	* rho (U+03C1): L<<41.0,-240.0>--<43.0,51.0>> -> L<<43.0,51.0>--<43.0,296.0>>

	* tripledagger (U+2E4B): L<<375.0,309.0>--<213.0,321.0>> -> L<<213.0,321.0>--<212.0,321.0>>

	* uni023E (U+023E): L<<448.0,689.0>--<445.0,689.0>> -> L<<445.0,689.0>--<293.0,689.0>>

	* uni0290 (U+0290): L<<402.0,138.0>--<397.0,0.0>> -> L<<397.0,0.0>--<397.0,-91.0>>

	* uni03BC (U+03BC): L<<56.0,-240.0>--<58.0,136.0>> -> L<<58.0,136.0>--<56.0,536.0>>

	* uni03FC (U+03FC): L<<42.0,-90.0>--<43.0,51.0>> -> L<<43.0,51.0>--<43.0,296.0>>

	* uni1D5D (U+1D5D): L<<36.0,143.0>--<38.0,358.0>> -> L<<38.0,358.0>--<38.0,626.0>> 

	* And 10 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* eth (U+00F0): B<<385.5,450.5>-<412.0,431.0>-<428.0,400.0>>/B<<428.0,400.0>-<403.0,480.0>-<371.5,537.5>> = 9.945547575071476

	* sterling (U+00A3): B<<192.0,89.0>-<173.0,58.0>-<145.0,40.0>>/L<<145.0,40.0>--<149.0,42.0>> = 6.170175095029526

	* uni1D95 (U+1D95): L<<424.0,-97.0>--<424.0,232.0>>/B<<424.0,232.0>-<417.0,110.0>-<368.0,50.0>> = 3.2838622879063513

	* uni1D9E (U+1D9E): B<<250.5,557.0>-<268.0,545.0>-<278.0,527.0>>/B<<278.0,527.0>-<262.0,575.0>-<241.5,609.5>> = 10.619655276155106

	* uni1DD9 (U+1DD9): B<<64.0,800.0>-<76.0,792.0>-<84.0,780.0>>/B<<84.0,780.0>-<72.0,812.0>-<58.0,835.0>> = 13.134022306396327

	* uni210A (U+210A): B<<93.5,165.0>-<104.0,193.0>-<117.0,209.0>>/L<<117.0,209.0>--<52.0,145.0>> = 6.350285546882426 

	* And uni2133 (U+2133): B<<1101.5,668.0>-<1119.0,688.0>-<1125.0,694.0>>/B<<1125.0,694.0>-<1109.0,683.0>-<1066.5,648.5>> = 10.491477012331565 [code: found-jaggy-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

	* beta (U+03B2): L<<56.0,-240.0>--<58.0,118.0>>

	* beta (U+03B2): L<<86.0,83.0>--<88.0,-240.0>>

	* eta (U+03B7): L<<442.0,-240.0>--<445.0,357.0>>

	* eta (U+03B7): L<<470.0,357.0>--<474.0,-240.0>>

	* etatonos (U+03AE): L<<442.0,-240.0>--<445.0,357.0>>

	* etatonos (U+03AE): L<<470.0,357.0>--<474.0,-240.0>>

	* exclam (U+0021): L<<123.0,167.0>--<120.0,714.0>>

	* exclam (U+0021): L<<149.0,714.0>--<148.0,167.0>>

	* exclamdbl (U+203C): L<<123.0,167.0>--<120.0,714.0>>

	* exclamdbl (U+203C): L<<149.0,714.0>--<148.0,167.0>> 

	* And 178 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-semi-vertical]
</div></details><br></div></details><details><summary><b>[13] NotoSerif-ThinItalic.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* 🔥 **FAIL** Missing required codepoints:

	- 0x00AF (MACRON)
 [code: missing-codepoints]
</div></details><details><summary>🔥 <b>FAIL:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* 🔥 **FAIL** License file OFL.txt exists but NameID 13 (LICENSE DESCRIPTION) value on platform 3 (WINDOWS) is not specified for that. Value was: "This Font Software is licensed under the SIL Open Font License, Version 1.1. This Font Software is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the SIL Open Font License for the specific language, permissions and limitations governing your use of this Font Software." Must be changed to "This Font Software is licensed under the SIL Open Font License, Version 1.1. This license is available with a FAQ at: https://scripts.sil.org/OFL" [code: wrong]
</div></details><details><summary>🔥 <b>FAIL:</b> OS/2.fsSelection bit 7 (USE_TYPO_METRICS) is set in all fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/os2/use_typo_metrics">com.google.fonts/check/os2/use_typo_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2.fsSelection bit 7 (USE_TYPO_METRICS) wasNOT set in the following fonts: ['fonts/NotoSerif-Italic/googlefonts/slim-variable-ttf/NotoSerif-ItalicMM[wght].ttf', 'fonts/NotoSerif-Italic/googlefonts/slim-variable-ttf/NotoSerif-MM[wght].ttf', 'fonts/NotoSerif-Italic/googlefonts/ttf/NotoSerif-Black.ttf', 'fonts/NotoSerif-Italic/googlefonts/ttf/NotoSerif-BlackItalic.ttf', 'fonts/NotoSerif-Italic/googlefonts/ttf/NotoSerif-Bold.ttf', 'fonts/NotoSerif-Italic/googlefonts/ttf/NotoSerif-BoldItalic.ttf', 'fonts/NotoSerif-Italic/googlefonts/ttf/NotoSerif-ExtraBold.ttf', 'fonts/NotoSerif-Italic/googlefonts/ttf/NotoSerif-ExtraBoldItalic.ttf', 'fonts/NotoSerif-Italic/googlefonts/ttf/NotoSerif-ExtraLight.ttf', 'fonts/NotoSerif-Italic/googlefonts/ttf/NotoSerif-ExtraLightItalic.ttf', 'fonts/NotoSerif-Italic/googlefonts/ttf/NotoSerif-Italic.ttf', 'fonts/NotoSerif-Italic/googlefonts/ttf/NotoSerif-Light.ttf', 'fonts/NotoSerif-Italic/googlefonts/ttf/NotoSerif-LightItalic.ttf', 'fonts/NotoSerif-Italic/googlefonts/ttf/NotoSerif-Medium.ttf', 'fonts/NotoSerif-Italic/googlefonts/ttf/NotoSerif-MediumItalic.ttf', 'fonts/NotoSerif-Italic/googlefonts/ttf/NotoSerif-Regular.ttf', 'fonts/NotoSerif-Italic/googlefonts/ttf/NotoSerif-SemiBold.ttf', 'fonts/NotoSerif-Italic/googlefonts/ttf/NotoSerif-SemiBoldItalic.ttf', 'fonts/NotoSerif-Italic/googlefonts/ttf/NotoSerif-Thin.ttf', 'fonts/NotoSerif-Italic/googlefonts/ttf/NotoSerif-ThinItalic.ttf', 'fonts/NotoSerif-Italic/googlefonts/variable-ttf/NotoSerif-ItalicMM[wdth,wght].ttf', 'fonts/NotoSerif-Italic/googlefonts/variable-ttf/NotoSerif-MM[CTGR,wdth,wght].ttf']. [code: missing-os2-fsselection-bit7]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinAscent value should be equal or greater than 1080, but got 1069 instead [code: ascent]
* 🔥 **FAIL** OS/2.usWinDescent value should be equal or greater than 389, but got 293 instead. [code: descent]
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

	- uni03B1030603140300

	- uni1FCD0306

	- uni1FDE0306

	- uni03C5030803040301

	- uni03B9030603140300

	- uni03B9030803040300

	- uni03B9030603130301

	- uni03C5030803060301

	- uni03C5030603140301

	- uni03C5030403140301 

	- And 31 more.

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

	* Cpalatalhook (U+A7C4): L<<484.0,82.0>--<484.0,82.0>> -> L<<484.0,82.0>--<484.0,82.0>>

	* Lslash (U+0141): L<<153.0,315.0>--<151.0,314.0>> -> L<<151.0,314.0>--<23.0,249.0>>

	* Ustroke (U+A7B8): L<<529.0,185.0>--<619.0,606.0>> -> L<<619.0,606.0>--<620.0,610.0>>

	* Zpalatalhook (U+A7C6): L<<474.0,134.0>--<441.0,2.0>> -> L<<441.0,2.0>--<418.0,-108.0>>

	* beta (U+03B2): L<<-42.0,-240.0>--<35.0,118.0>> -> L<<35.0,118.0>--<129.0,565.0>>

	* rho (U+03C1): L<<-62.0,-240.0>--<1.0,51.0>> -> L<<1.0,51.0>--<53.0,296.0>>

	* tripledagger (U+2E4B): L<<224.0,338.0>--<225.0,338.0>> -> L<<225.0,338.0>--<384.0,342.0>>

	* tripledagger (U+2E4B): L<<377.0,312.0>--<221.0,314.0>> -> L<<221.0,314.0>--<219.0,314.0>>

	* tripledagger (U+2E4B): L<<45.0,342.0>--<201.0,338.0>> -> L<<201.0,338.0>--<203.0,338.0>>

	* uni0246 (U+0246): L<<497.0,689.0>--<492.0,689.0>> -> L<<492.0,689.0>--<260.0,689.0>> 

	* And 12 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* eturnedopenmod (U+1D4C): B<<280.5,468.0>-<256.0,442.0>-<211.0,436.0>>/L<<211.0,436.0>--<211.0,436.0>> = 7.594643368591447

	* three (U+0033): B<<417.0,440.0>-<372.0,385.0>-<280.0,375.0>>/B<<280.0,375.0>-<313.0,372.0>-<343.0,353.0>> = 11.397876809426648

	* tripledagger (U+2E4B): L<<197.0,314.0>--<197.0,314.0>>/L<<197.0,314.0>--<38.0,312.0>> = 0.7206636225178014

	* uni024A (U+024A): L<<431.0,-64.0>--<480.0,168.0>>/B<<480.0,168.0>-<439.0,80.0>-<379.5,33.5>> = 13.055247223796592

	* uni04BF (U+04BF): B<<371.5,13.5>-<346.0,-3.0>-<310.0,-8.0>>/L<<310.0,-8.0>--<310.0,-8.0>> = 7.907162702958418

	* uni04BF (U+04BF): L<<310.0,-8.0>--<310.0,-8.0>>/B<<310.0,-8.0>-<287.0,-12.0>-<273.0,-18.0>> = 9.865806943084365

	* uni0504 (U+0504): B<<395.5,403.0>-<357.0,376.0>-<308.0,368.0>>/B<<308.0,368.0>-<361.0,366.0>-<390.0,341.0>> = 11.433681265426625

	* uni1D95 (U+1D95): L<<297.0,-29.0>--<355.0,216.0>>/B<<355.0,216.0>-<338.0,154.0>-<305.5,102.5>> = 2.0145810107512325

	* uni20A5 (U+20A5): B<<334.0,84.0>-<339.0,126.0>-<348.0,169.0>>/L<<348.0,169.0>--<235.0,-96.0>> = 11.272643255936822

	* uni210A (U+210A): B<<93.5,165.0>-<104.0,193.0>-<117.0,209.0>>/L<<117.0,209.0>--<52.0,145.0>> = 6.350285546882426 

	* And 5 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-jaggy-segments]
</div></details><br></div></details><details><summary><b>[20] NotoSerif-ItalicMM[wdth,wght].ttf</b></summary><div><details><summary>💔 <b>ERROR:</b> STAT table has Axis Value tables? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/stat.html#com.adobe.fonts/check/stat_has_axis_value_tables">com.adobe.fonts/check/stat_has_axis_value_tables</a>)</summary><div>


* 💔 **ERROR** Failed with AttributeError: 'NoneType' object has no attribute 'AxisValue'
</div></details><details><summary>🔥 <b>FAIL:</b> Checking file is named canonically. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/canonical_filename">com.google.fonts/check/canonical_filename</a>)</summary><div>


* 🔥 **FAIL** The file 'NotoSerif-ItalicMM[wdth,wght].ttf' must be renamed to 'NotoSerif-Italic[wdth,wght].ttf' according to the Google Fonts naming policy for variable fonts. [code: bad-varfont-filename]
</div></details><details><summary>🔥 <b>FAIL:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* 🔥 **FAIL** Missing required codepoints:

	- 0x00AF (MACRON)
 [code: missing-codepoints]
</div></details><details><summary>🔥 <b>FAIL:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* 🔥 **FAIL** License file OFL.txt exists but NameID 13 (LICENSE DESCRIPTION) value on platform 3 (WINDOWS) is not specified for that. Value was: "This Font Software is licensed under the SIL Open Font License, Version 1.1. This Font Software is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the SIL Open Font License for the specific language, permissions and limitations governing your use of this Font Software." Must be changed to "This Font Software is licensed under the SIL Open Font License, Version 1.1. This license is available with a FAQ at: https://scripts.sil.org/OFL" [code: wrong]
</div></details><details><summary>🔥 <b>FAIL:</b> Is the Grid-fitting and Scan-conversion Procedure ('gasp') table set to optimize rendering? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/gasp">com.google.fonts/check/gasp</a>)</summary><div>


* 🔥 **FAIL** Font is missing the 'gasp' table. Try exporting the font with autohinting enabled.
If you are dealing with an unhinted font, it can be fixed by running the fonts through the command 'gftools fix-nonhinting'
GFTools is available at https://pypi.org/project/gftools/ [code: lacks-gasp]
</div></details><details><summary>🔥 <b>FAIL:</b> Font enables smart dropout control in "prep" table instructions? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/smart_dropout">com.google.fonts/check/smart_dropout</a>)</summary><div>


* 🔥 **FAIL** The 'prep' table does not contain TrueType instructions enabling smart dropout control. To fix, export the font with autohinting enabled, or run ttfautohint on the font, or run the `gftools fix-nonhinting` script. [code: lacks-smart-dropout]
</div></details><details><summary>🔥 <b>FAIL:</b> Validate STAT particle names and values match the fallback names in GFAxisRegistry.  (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/STAT/gf-axisregistry">com.google.fonts/check/STAT/gf-axisregistry</a>)</summary><div>


* 🔥 **FAIL** STAT table is missing Axis Value Records [code: missing-axis-values]
</div></details><details><summary>🔥 <b>FAIL:</b> OS/2.fsSelection bit 7 (USE_TYPO_METRICS) is set in all fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/os2/use_typo_metrics">com.google.fonts/check/os2/use_typo_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2.fsSelection bit 7 (USE_TYPO_METRICS) wasNOT set in the following fonts: ['fonts/NotoSerif-Italic/googlefonts/slim-variable-ttf/NotoSerif-ItalicMM[wght].ttf', 'fonts/NotoSerif-Italic/googlefonts/slim-variable-ttf/NotoSerif-MM[wght].ttf', 'fonts/NotoSerif-Italic/googlefonts/ttf/NotoSerif-Black.ttf', 'fonts/NotoSerif-Italic/googlefonts/ttf/NotoSerif-BlackItalic.ttf', 'fonts/NotoSerif-Italic/googlefonts/ttf/NotoSerif-Bold.ttf', 'fonts/NotoSerif-Italic/googlefonts/ttf/NotoSerif-BoldItalic.ttf', 'fonts/NotoSerif-Italic/googlefonts/ttf/NotoSerif-ExtraBold.ttf', 'fonts/NotoSerif-Italic/googlefonts/ttf/NotoSerif-ExtraBoldItalic.ttf', 'fonts/NotoSerif-Italic/googlefonts/ttf/NotoSerif-ExtraLight.ttf', 'fonts/NotoSerif-Italic/googlefonts/ttf/NotoSerif-ExtraLightItalic.ttf', 'fonts/NotoSerif-Italic/googlefonts/ttf/NotoSerif-Italic.ttf', 'fonts/NotoSerif-Italic/googlefonts/ttf/NotoSerif-Light.ttf', 'fonts/NotoSerif-Italic/googlefonts/ttf/NotoSerif-LightItalic.ttf', 'fonts/NotoSerif-Italic/googlefonts/ttf/NotoSerif-Medium.ttf', 'fonts/NotoSerif-Italic/googlefonts/ttf/NotoSerif-MediumItalic.ttf', 'fonts/NotoSerif-Italic/googlefonts/ttf/NotoSerif-Regular.ttf', 'fonts/NotoSerif-Italic/googlefonts/ttf/NotoSerif-SemiBold.ttf', 'fonts/NotoSerif-Italic/googlefonts/ttf/NotoSerif-SemiBoldItalic.ttf', 'fonts/NotoSerif-Italic/googlefonts/ttf/NotoSerif-Thin.ttf', 'fonts/NotoSerif-Italic/googlefonts/ttf/NotoSerif-ThinItalic.ttf', 'fonts/NotoSerif-Italic/googlefonts/variable-ttf/NotoSerif-ItalicMM[wdth,wght].ttf', 'fonts/NotoSerif-Italic/googlefonts/variable-ttf/NotoSerif-MM[CTGR,wdth,wght].ttf']. [code: missing-os2-fsselection-bit7]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinAscent value should be equal or greater than 1080, but got 1069 instead [code: ascent]
* 🔥 **FAIL** OS/2.usWinDescent value should be equal or greater than 389, but got 293 instead. [code: descent]
</div></details><details><summary>🔥 <b>FAIL:</b> The variable font 'wght' (Weight) axis coordinate must be 400 on the 'Regular' instance. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/fvar.html#com.google.fonts/check/varfont/regular_wght_coord">com.google.fonts/check/varfont/regular_wght_coord</a>)</summary><div>


* 🔥 **FAIL** The "wght" axis coordinate of the "Regular" instance must be 400. Got None instead. [code: wght-not-400]
</div></details><details><summary>🔥 <b>FAIL:</b> The variable font 'wdth' (Width) axis coordinate must be 100 on the 'Regular' instance. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/fvar.html#com.google.fonts/check/varfont/regular_wdth_coord">com.google.fonts/check/varfont/regular_wdth_coord</a>)</summary><div>


* 🔥 **FAIL** The "wdth" axis coordinate of the "Regular" instance must be 100. Got None as a default value instead. [code: wdth-not-100]
</div></details><details><summary>🔥 <b>FAIL:</b> The variable font 'wght' (Weight) axis coordinate must be 700 on the 'Bold' instance. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/fvar.html#com.google.fonts/check/varfont/bold_wght_coord">com.google.fonts/check/varfont/bold_wght_coord</a>)</summary><div>


* 🔥 **FAIL** The "wght" axis coordinate of the "Bold" instance must be 700. Got None instead. [code: wght-not-700]
</div></details><details><summary>🔥 <b>FAIL:</b> Validates that when an instance record is included for the default instance, its subfamilyNameID value is set to either 2 or 17, and its postScriptNameID value is set to 6. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/fvar.html#com.adobe.fonts/check/varfont/valid_default_instance_nameids">com.adobe.fonts/check/varfont/valid_default_instance_nameids</a>)</summary><div>


* 🔥 **FAIL** 'Italic' instance has the same coordinates as the default instance; its subfamilyNameID should be either 2 or 17, instead of 262. [code: invalid-default-instance-subfamily-nameid:262]
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

	- uni03B1030603140300

	- uni1FCD0306

	- uni1FDE0306

	- uni03C5030803040301

	- uni03B9030603140300

	- uni03B9030803040300

	- uni03B9030603130301

	- uni03C5030803060301

	- uni03C5030603140301

	- uni03C5030403140301 

	- And 31 more.

Use -F or --full-lists to disable shortening of long lists.
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check mark characters are in GDEF mark glyph class. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_mark_chars">com.google.fonts/check/gdef_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following mark characters could be in the GDEF mark glyph class:
	 uni0488 (U+0488), uni0489 (U+0489), uni1ABE (U+1ABE), uniA670 (U+A670), uniA671 (U+A671) and uniA672 (U+A672) [code: mark-chars]
</div></details><br></div></details><details><summary><b>[18] NotoSerif-MM[CTGR,wdth,wght].ttf</b></summary><div><details><summary>💔 <b>ERROR:</b> STAT table has Axis Value tables? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/stat.html#com.adobe.fonts/check/stat_has_axis_value_tables">com.adobe.fonts/check/stat_has_axis_value_tables</a>)</summary><div>


* 💔 **ERROR** Failed with AttributeError: 'NoneType' object has no attribute 'AxisValue'
</div></details><details><summary>🔥 <b>FAIL:</b> Checking file is named canonically. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/canonical_filename">com.google.fonts/check/canonical_filename</a>)</summary><div>


* 🔥 **FAIL** The file 'NotoSerif-MM[CTGR,wdth,wght].ttf' must be renamed to 'NotoSerif[CTGR,wdth,wght].ttf' according to the Google Fonts naming policy for variable fonts. [code: bad-varfont-filename]
</div></details><details><summary>🔥 <b>FAIL:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* 🔥 **FAIL** Missing required codepoints:

	- 0x00AF (MACRON)
 [code: missing-codepoints]
</div></details><details><summary>🔥 <b>FAIL:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* 🔥 **FAIL** License file OFL.txt exists but NameID 13 (LICENSE DESCRIPTION) value on platform 3 (WINDOWS) is not specified for that. Value was: "This Font Software is licensed under the SIL Open Font License, Version 1.1. This Font Software is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the SIL Open Font License for the specific language, permissions and limitations governing your use of this Font Software." Must be changed to "This Font Software is licensed under the SIL Open Font License, Version 1.1. This license is available with a FAQ at: https://scripts.sil.org/OFL" [code: wrong]
</div></details><details><summary>🔥 <b>FAIL:</b> Is the Grid-fitting and Scan-conversion Procedure ('gasp') table set to optimize rendering? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/gasp">com.google.fonts/check/gasp</a>)</summary><div>


* 🔥 **FAIL** Font is missing the 'gasp' table. Try exporting the font with autohinting enabled.
If you are dealing with an unhinted font, it can be fixed by running the fonts through the command 'gftools fix-nonhinting'
GFTools is available at https://pypi.org/project/gftools/ [code: lacks-gasp]
</div></details><details><summary>🔥 <b>FAIL:</b> Font enables smart dropout control in "prep" table instructions? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/smart_dropout">com.google.fonts/check/smart_dropout</a>)</summary><div>


* 🔥 **FAIL** The 'prep' table does not contain TrueType instructions enabling smart dropout control. To fix, export the font with autohinting enabled, or run ttfautohint on the font, or run the `gftools fix-nonhinting` script. [code: lacks-smart-dropout]
</div></details><details><summary>🔥 <b>FAIL:</b> Validate STAT particle names and values match the fallback names in GFAxisRegistry.  (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/STAT/gf-axisregistry">com.google.fonts/check/STAT/gf-axisregistry</a>)</summary><div>


* 🔥 **FAIL** STAT table is missing Axis Value Records [code: missing-axis-values]
</div></details><details><summary>🔥 <b>FAIL:</b> OS/2.fsSelection bit 7 (USE_TYPO_METRICS) is set in all fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/os2/use_typo_metrics">com.google.fonts/check/os2/use_typo_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2.fsSelection bit 7 (USE_TYPO_METRICS) wasNOT set in the following fonts: ['fonts/NotoSerif-Italic/googlefonts/slim-variable-ttf/NotoSerif-ItalicMM[wght].ttf', 'fonts/NotoSerif-Italic/googlefonts/slim-variable-ttf/NotoSerif-MM[wght].ttf', 'fonts/NotoSerif-Italic/googlefonts/ttf/NotoSerif-Black.ttf', 'fonts/NotoSerif-Italic/googlefonts/ttf/NotoSerif-BlackItalic.ttf', 'fonts/NotoSerif-Italic/googlefonts/ttf/NotoSerif-Bold.ttf', 'fonts/NotoSerif-Italic/googlefonts/ttf/NotoSerif-BoldItalic.ttf', 'fonts/NotoSerif-Italic/googlefonts/ttf/NotoSerif-ExtraBold.ttf', 'fonts/NotoSerif-Italic/googlefonts/ttf/NotoSerif-ExtraBoldItalic.ttf', 'fonts/NotoSerif-Italic/googlefonts/ttf/NotoSerif-ExtraLight.ttf', 'fonts/NotoSerif-Italic/googlefonts/ttf/NotoSerif-ExtraLightItalic.ttf', 'fonts/NotoSerif-Italic/googlefonts/ttf/NotoSerif-Italic.ttf', 'fonts/NotoSerif-Italic/googlefonts/ttf/NotoSerif-Light.ttf', 'fonts/NotoSerif-Italic/googlefonts/ttf/NotoSerif-LightItalic.ttf', 'fonts/NotoSerif-Italic/googlefonts/ttf/NotoSerif-Medium.ttf', 'fonts/NotoSerif-Italic/googlefonts/ttf/NotoSerif-MediumItalic.ttf', 'fonts/NotoSerif-Italic/googlefonts/ttf/NotoSerif-Regular.ttf', 'fonts/NotoSerif-Italic/googlefonts/ttf/NotoSerif-SemiBold.ttf', 'fonts/NotoSerif-Italic/googlefonts/ttf/NotoSerif-SemiBoldItalic.ttf', 'fonts/NotoSerif-Italic/googlefonts/ttf/NotoSerif-Thin.ttf', 'fonts/NotoSerif-Italic/googlefonts/ttf/NotoSerif-ThinItalic.ttf', 'fonts/NotoSerif-Italic/googlefonts/variable-ttf/NotoSerif-ItalicMM[wdth,wght].ttf', 'fonts/NotoSerif-Italic/googlefonts/variable-ttf/NotoSerif-MM[CTGR,wdth,wght].ttf']. [code: missing-os2-fsselection-bit7]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinAscent value should be equal or greater than 1080, but got 1069 instead [code: ascent]
* 🔥 **FAIL** OS/2.usWinDescent value should be equal or greater than 389, but got 293 instead. [code: descent]
</div></details><details><summary>🔥 <b>FAIL:</b> Validates that when an instance record is included for the default instance, its subfamilyNameID value is set to either 2 or 17, and its postScriptNameID value is set to 6. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/fvar.html#com.adobe.fonts/check/varfont/valid_default_instance_nameids">com.adobe.fonts/check/varfont/valid_default_instance_nameids</a>)</summary><div>


* 🔥 **FAIL** 'Regular' instance has the same coordinates as the default instance; its subfamilyNameID should be either 2 or 17, instead of 263. [code: invalid-default-instance-subfamily-nameid:263]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure files are not too large. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/file_size">com.google.fonts/check/file_size</a>)</summary><div>


* ⚠ **WARN** Font file is 4.0Mb; ideally it should be less than 1.0Mb [code: large-font]
</div></details><details><summary>⚠ <b>WARN:</b> Is there kerning info for non-ligated sequences? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/kerning_for_non_ligated_sequences">com.google.fonts/check/kerning_for_non_ligated_sequences</a>)</summary><div>


* ⚠ **WARN** GPOS table lacks kerning info for the following non-ligated sequences:

	- f + f

	- f + i

	- i + f

	- f + l

	- l + f 

	- And i + l [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure Stylistic Sets have description. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/stylisticset_description">com.google.fonts/check/stylisticset_description</a>)</summary><div>


* ⚠ **WARN** The stylistic set ss03 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss06 lacks a description string on the 'name' table. [code: missing-description]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Glyph names are all valid? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/valid_glyphnames">com.google.fonts/check/valid_glyphnames</a>)</summary><div>


* ⚠ **WARN** The following glyph names may be too long for some legacy systems which may expect a maximum 31-char length limit:
kavykawithkavykaaboveinvertedlow [code: legacy-long-names]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- uni03B1030603140300

	- uni1FCD0306

	- uni1FDE0306

	- uni03C5030803040301

	- uni03B9030603140300

	- uni03B9030803040300

	- uni03B9030603130301

	- uni03C5030803060301

	- uni03C5030603140301

	- uni03C5030403140301 

	- And 31 more.

Use -F or --full-lists to disable shortening of long lists.
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Does the font have a DSIG table? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/dsig.html#com.google.fonts/check/dsig">com.google.fonts/check/dsig</a>)</summary><div>


* ⚠ **WARN** This font has a digital signature (DSIG table) which is only required - even if only a placeholder - on old programs like MS Office 2013 in order to work properly.
The current recommendation is to completely remove the DSIG table. [code: found-DSIG]
</div></details><details><summary>⚠ <b>WARN:</b> Check mark characters are in GDEF mark glyph class. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_mark_chars">com.google.fonts/check/gdef_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following mark characters could be in the GDEF mark glyph class:
	 uni0488 (U+0488), uni0489 (U+0489), uni1ABE (U+1ABE), uniA670 (U+A670), uniA671 (U+A671) and uniA672 (U+A672) [code: mark-chars]
</div></details><br></div></details>
### Summary

| 💔 ERROR | 🔥 FAIL | ⚠ WARN | 💤 SKIP | ℹ INFO | 🍞 PASS | 🔎 DEBUG |
|:-----:|:----:|:----:|:----:|:----:|:----:|:----:|
| 4 | 139 | 207 | 2458 | 170 | 1877 | 0 |
| 0% | 3% | 4% | 51% | 4% | 39% | 0% |

**Note:** The following loglevels were omitted in this report:
* **SKIP**
* **INFO**
* **PASS**
* **DEBUG**
