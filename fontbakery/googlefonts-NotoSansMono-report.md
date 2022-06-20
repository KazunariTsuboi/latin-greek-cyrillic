## Fontbakery report

Fontbakery version: 0.8.9

<details><summary><b>[1] Family checks</b></summary><div><details><summary>🔥 <b>FAIL:</b> Checking all files are in the same directory. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/single_directory">com.google.fonts/check/family/single_directory</a>)</summary><div>


* 🔥 **FAIL** Not all fonts passed in the command line are in the same directory. This may lead to bad results as the tool will interpret all font files as belonging to a single font family. The detected directories are: ['fonts/NotoSansMono/googlefonts/slim-variable-ttf', 'fonts/NotoSansMono/googlefonts/ttf', 'fonts/NotoSansMono/googlefonts/variable-ttf'] [code: single-directory]
</div></details><br></div></details><details><summary><b>[13] NotoSansMono-MM[wght].ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Checking file is named canonically. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/canonical_filename">com.google.fonts/check/canonical_filename</a>)</summary><div>


* 🔥 **FAIL** The file 'NotoSansMono-MM[wght].ttf' must be renamed to 'NotoSansMono[wdth,wght].ttf' according to the Google Fonts naming policy for variable fonts. [code: bad-varfont-filename]
</div></details><details><summary>🔥 <b>FAIL:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* 🔥 **FAIL** Missing required codepoints:

	- 0x00AF (MACRON)
 [code: missing-codepoints]
</div></details><details><summary>🔥 <b>FAIL:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* 🔥 **FAIL** License file OFL.txt exists but NameID 13 (LICENSE DESCRIPTION) value on platform 3 (WINDOWS) is not specified for that. Value was: "This Font Software is licensed under the SIL Open Font License, Version 1.1. This Font Software is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the SIL Open Font License for the specific language, permissions and limitations governing your use of this Font Software." Must be changed to "This Font Software is licensed under the SIL Open Font License, Version 1.1. This license is available with a FAQ at: https://scripts.sil.org/OFL" [code: wrong]
</div></details><details><summary>🔥 <b>FAIL:</b> OS/2.fsSelection bit 7 (USE_TYPO_METRICS) is set in all fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/os2/use_typo_metrics">com.google.fonts/check/os2/use_typo_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2.fsSelection bit 7 (USE_TYPO_METRICS) wasNOT set in the following fonts: ['fonts/NotoSansMono/googlefonts/slim-variable-ttf/NotoSansMono-MM[wght].ttf', 'fonts/NotoSansMono/googlefonts/ttf/NotoSansMono-Black.ttf', 'fonts/NotoSansMono/googlefonts/ttf/NotoSansMono-Bold.ttf', 'fonts/NotoSansMono/googlefonts/ttf/NotoSansMono-ExtraBold.ttf', 'fonts/NotoSansMono/googlefonts/ttf/NotoSansMono-ExtraLight.ttf', 'fonts/NotoSansMono/googlefonts/ttf/NotoSansMono-Light.ttf', 'fonts/NotoSansMono/googlefonts/ttf/NotoSansMono-Medium.ttf', 'fonts/NotoSansMono/googlefonts/ttf/NotoSansMono-Regular.ttf', 'fonts/NotoSansMono/googlefonts/ttf/NotoSansMono-SemiBold.ttf', 'fonts/NotoSansMono/googlefonts/ttf/NotoSansMono-Thin.ttf', 'fonts/NotoSansMono/googlefonts/variable-ttf/NotoSansMono-MM[wdth,wght].ttf']. [code: missing-os2-fsselection-bit7]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinAscent value should be equal or greater than 1239, but got 1069 instead [code: ascent]
* 🔥 **FAIL** OS/2.usWinDescent value should be equal or greater than 389, but got 293 instead. [code: descent]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking correctness of monospaced metadata. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/name.html#com.google.fonts/check/monospace">com.google.fonts/check/monospace</a>)</summary><div>


* 🔥 **FAIL** On monospaced fonts, the value of post.isFixedPitch must be set to a non-zero value (meaning 'fixed width monospaced'), but got 0 instead. [code: mono-bad-post-isFixedPitch]
* ⚠ **WARN** Font is monospaced but 250 glyphs (6.60%) have a different width. You should check the widths of: ['oneeighth', 'threeeighths', 'fiveeighths', 'seveneighths', 'uniFFFC', 'uniFFFD', 'uni0468', 'uni046C', 'uni046D', 'uni0478', 'uni0479', 'uni01A2', 'uni01C4', 'uni01C5', 'uni01C6', 'uni01C7', 'uni01C8', 'uni01C9', 'uni01CA', 'uni01CB', 'uni01CC', 'uni01F1', 'uni01F2', 'uni01F3', 'uni02A5', 'uni02A8', 'uni1D7A', 'uni1F0A', 'uni1F0B', 'uni1F0C', 'uni1F0D', 'uni1F0E', 'uni1F0F', 'uni1F1A', 'uni1F1B', 'uni1F1C', 'uni1F1D', 'uni1F2A', 'uni1F2B', 'uni1F2C', 'uni1F2D', 'uni1F2E', 'uni1F2F', 'uni1F4A', 'uni1F4B', 'uni1F4C', 'uni1F4D', 'uni1F5B', 'uni1F5D', 'uni1F5F', 'uni1F6A', 'uni1F6B', 'uni1F6C', 'uni1F6D', 'uni1F6E', 'uni1F6F', 'uni1F88', 'uni1F89', 'uni1F8A', 'uni1F8B', 'uni1F8C', 'uni1F8D', 'uni1F8E', 'uni1F8F', 'uni1F98', 'uni1F99', 'uni1F9A', 'uni1F9B', 'uni1F9C', 'uni1F9D', 'uni1F9E', 'uni1F9F', 'uni1FA8', 'uni1FA9', 'uni1FAA', 'uni1FAB', 'uni1FAC', 'uni1FAD', 'uni1FAE', 'uni1FAF', 'uni1FBC', 'uni1FCC', 'uni1FFC', 'uni20A8', 'uni2153', 'uni2154', 'uni0518', 'uni0520', 'uni0521', 'uni0522', 'uni0523', 'uniA728', 'uniA732', 'uniA734', 'uniA736', 'uniA738', 'uniA73A', 'uniA73C', 'uniA74E', 'uniA729', 'uniA74F', 'uniA773', 'sakhayat', 'uniA7FF', 'Iotifiedacy', 'Yusiotifiedclosedlittlecy', 'Emsoftcy', 'Odoublemonocularcy', 'uniA684', 'Odoublecy', 'uni052A', 'uniA657', 'yusiotifiedclosedlittlecy', 'emsoftcy', 'odoublemonocularcy', 'odoublecy', 'uni052B', 'uni211C', 'uni212C', 'uni210B', 'uni2110', 'uni2112', 'uni211B', 'uni2131', 'uni2133', 'uni2474', 'uni2475', 'uni2189', 'uni2155', 'uni2156', 'uni2157', 'uni2158', 'uni2159', 'uni215A', 'uni2150', 'uni2151', 'uni2152', 'uni2042', 'uni2E0E', 'uni2047', 'uni203B', 'uni2053', 'uni2E3B', 'uni2E3A', 'uni2057', 'uni20B7', 'uni23DF', 'uni23DD', 'uni23E1', 'uni27D7', 'uni27D5', 'uni2A00', 'emptyset', 'uni2031', 'uni27D6', 'uni23DE', 'uni23DC', 'uni23E0', 'uni229B', 'uni229C', 'uni2298', 'uni2296', 'circlemultiply', 'uni2299', 'circleplus', 'uni29B8', 'uni229A', 'uni219C', 'uni219D', 'uni219E', 'uni21A0', 'uni21A2', 'uni21A3', 'uni21A4', 'uni21A6', 'arrowdblright', 'arrowdblleft', 'arrowdblboth', 'uni21DA', 'uni21DB', 'uni21E8', 'uni21E6', 'uni27F5', 'uni27F6', 'uni25EF', 'uni25CD', 'uni25C6', 'uni25C7', 'uni25C8', 'uni25B0', 'uni25B1', 'uni25AD', 'uni25A2', 'uni25A3', 'uni25A4', 'uni25A5', 'uni25A6', 'uni25A7', 'uni25A8', 'uni25A9', 'uni25E7', 'uni25E8', 'uni25E9', 'uni25EA', 'uni25EB', 'uni25F0', 'uni25F1', 'uni25F2', 'uni25F3', 'uni25B6', 'uni25C0', 'uni25B3', 'uni25B7', 'uni25BD', 'uni25C1', 'uni25EC', 'uni25ED', 'uni25EE', 'uni25BB', 'uni25C5', 'uni25E5', 'uni25E2', 'uni25E3', 'uni25E4', 'uni2349', 'uni2365', 'uni233E', 'uni235F', 'uni233D', 'uni235C', 'uni236B', 'uni235A', 'uni2371', 'uni2366', 'uni2367', 'uni236D', 'uni2372', 'uni235D', 'uni236C', 'uni2736', 'uni213A', 'uni2103', 'u1F67C', 'u1F67D', 'u1F67E', 'u1F67F', 'uni2109', 'uni2114', 'uni214F', 'weierstrass'] [code: mono-outliers]
</div></details><details><summary>🔥 <b>FAIL:</b> Validates that when an instance record is included for the default instance, its subfamilyNameID value is set to either 2 or 17, and its postScriptNameID value is set to 6. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/fvar.html#com.adobe.fonts/check/varfont/valid_default_instance_nameids">com.adobe.fonts/check/varfont/valid_default_instance_nameids</a>)</summary><div>


* 🔥 **FAIL** 'Regular' instance has the same coordinates as the default instance; its subfamilyNameID should be either 2 or 17, instead of 283. [code: invalid-default-instance-subfamily-nameid:283]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure files are not too large. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/file_size">com.google.fonts/check/file_size</a>)</summary><div>


* ⚠ **WARN** Font file is 1.1Mb; ideally it should be less than 1.0Mb [code: large-font]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure Stylistic Sets have description. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/stylisticset_description">com.google.fonts/check/stylisticset_description</a>)</summary><div>


* ⚠ **WARN** The stylistic set ss03 lacks a description string on the 'name' table. [code: missing-description]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Glyph names are all valid? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/valid_glyphnames">com.google.fonts/check/valid_glyphnames</a>)</summary><div>


* ⚠ **WARN** The following glyph names may be too long for some legacy systems which may expect a maximum 31-char length limit:
kavykawithkavykaaboveinvertedlow [code: legacy-long-names]
</div></details><details><summary>⚠ <b>WARN:</b> Check mark characters are in GDEF mark glyph class. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_mark_chars">com.google.fonts/check/gdef_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following mark characters could be in the GDEF mark glyph class:
	 uni0488 (U+0488), uni0489 (U+0489), uni1ABE (U+1ABE), uniA670 (U+A670), uniA671 (U+A671) and uniA672 (U+A672) [code: mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Does GPOS table have kerning information? This check skips monospaced fonts as defined by post.isFixedPitch value (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gpos.html#com.google.fonts/check/gpos_kerning_info">com.google.fonts/check/gpos_kerning_info</a>)</summary><div>


* ⚠ **WARN** GPOS table lacks kerning information. [code: lacks-kern-info]
</div></details><br></div></details><details><summary><b>[15] NotoSansMono-Black.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* 🔥 **FAIL** Missing required codepoints:

	- 0x00AF (MACRON)
 [code: missing-codepoints]
</div></details><details><summary>🔥 <b>FAIL:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* 🔥 **FAIL** License file OFL.txt exists but NameID 13 (LICENSE DESCRIPTION) value on platform 3 (WINDOWS) is not specified for that. Value was: "This Font Software is licensed under the SIL Open Font License, Version 1.1. This Font Software is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the SIL Open Font License for the specific language, permissions and limitations governing your use of this Font Software." Must be changed to "This Font Software is licensed under the SIL Open Font License, Version 1.1. This license is available with a FAQ at: https://scripts.sil.org/OFL" [code: wrong]
</div></details><details><summary>🔥 <b>FAIL:</b> OS/2.fsSelection bit 7 (USE_TYPO_METRICS) is set in all fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/os2/use_typo_metrics">com.google.fonts/check/os2/use_typo_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2.fsSelection bit 7 (USE_TYPO_METRICS) wasNOT set in the following fonts: ['fonts/NotoSansMono/googlefonts/slim-variable-ttf/NotoSansMono-MM[wght].ttf', 'fonts/NotoSansMono/googlefonts/ttf/NotoSansMono-Black.ttf', 'fonts/NotoSansMono/googlefonts/ttf/NotoSansMono-Bold.ttf', 'fonts/NotoSansMono/googlefonts/ttf/NotoSansMono-ExtraBold.ttf', 'fonts/NotoSansMono/googlefonts/ttf/NotoSansMono-ExtraLight.ttf', 'fonts/NotoSansMono/googlefonts/ttf/NotoSansMono-Light.ttf', 'fonts/NotoSansMono/googlefonts/ttf/NotoSansMono-Medium.ttf', 'fonts/NotoSansMono/googlefonts/ttf/NotoSansMono-Regular.ttf', 'fonts/NotoSansMono/googlefonts/ttf/NotoSansMono-SemiBold.ttf', 'fonts/NotoSansMono/googlefonts/ttf/NotoSansMono-Thin.ttf', 'fonts/NotoSansMono/googlefonts/variable-ttf/NotoSansMono-MM[wdth,wght].ttf']. [code: missing-os2-fsselection-bit7]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinAscent value should be equal or greater than 1239, but got 1069 instead [code: ascent]
* 🔥 **FAIL** OS/2.usWinDescent value should be equal or greater than 389, but got 293 instead. [code: descent]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking correctness of monospaced metadata. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/name.html#com.google.fonts/check/monospace">com.google.fonts/check/monospace</a>)</summary><div>


* 🔥 **FAIL** On monospaced fonts, the value of post.isFixedPitch must be set to a non-zero value (meaning 'fixed width monospaced'), but got 0 instead. [code: mono-bad-post-isFixedPitch]
* ⚠ **WARN** Font is monospaced but 250 glyphs (6.60%) have a different width. You should check the widths of: ['oneeighth', 'threeeighths', 'fiveeighths', 'seveneighths', 'uniFFFC', 'uniFFFD', 'uni0468', 'uni046C', 'uni046D', 'uni0478', 'uni0479', 'uni01A2', 'uni01C4', 'uni01C5', 'uni01C6', 'uni01C7', 'uni01C8', 'uni01C9', 'uni01CA', 'uni01CB', 'uni01CC', 'uni01F1', 'uni01F2', 'uni01F3', 'uni02A5', 'uni02A8', 'uni1D7A', 'uni1F0A', 'uni1F0B', 'uni1F0C', 'uni1F0D', 'uni1F0E', 'uni1F0F', 'uni1F1A', 'uni1F1B', 'uni1F1C', 'uni1F1D', 'uni1F2A', 'uni1F2B', 'uni1F2C', 'uni1F2D', 'uni1F2E', 'uni1F2F', 'uni1F4A', 'uni1F4B', 'uni1F4C', 'uni1F4D', 'uni1F5B', 'uni1F5D', 'uni1F5F', 'uni1F6A', 'uni1F6B', 'uni1F6C', 'uni1F6D', 'uni1F6E', 'uni1F6F', 'uni1F88', 'uni1F89', 'uni1F8A', 'uni1F8B', 'uni1F8C', 'uni1F8D', 'uni1F8E', 'uni1F8F', 'uni1F98', 'uni1F99', 'uni1F9A', 'uni1F9B', 'uni1F9C', 'uni1F9D', 'uni1F9E', 'uni1F9F', 'uni1FA8', 'uni1FA9', 'uni1FAA', 'uni1FAB', 'uni1FAC', 'uni1FAD', 'uni1FAE', 'uni1FAF', 'uni1FBC', 'uni1FCC', 'uni1FFC', 'uni20A8', 'uni2153', 'uni2154', 'uni0518', 'uni0520', 'uni0521', 'uni0522', 'uni0523', 'uniA728', 'uniA732', 'uniA734', 'uniA736', 'uniA738', 'uniA73A', 'uniA73C', 'uniA74E', 'uniA729', 'uniA74F', 'uniA773', 'sakhayat', 'uniA7FF', 'Iotifiedacy', 'Yusiotifiedclosedlittlecy', 'Emsoftcy', 'Odoublemonocularcy', 'uniA684', 'Odoublecy', 'uni052A', 'uniA657', 'yusiotifiedclosedlittlecy', 'emsoftcy', 'odoublemonocularcy', 'odoublecy', 'uni052B', 'uni211C', 'uni212C', 'uni210B', 'uni2110', 'uni2112', 'uni211B', 'uni2131', 'uni2133', 'uni2474', 'uni2475', 'uni2189', 'uni2155', 'uni2156', 'uni2157', 'uni2158', 'uni2159', 'uni215A', 'uni2150', 'uni2151', 'uni2152', 'uni2042', 'uni2E0E', 'uni2047', 'uni203B', 'uni2053', 'uni2E3B', 'uni2E3A', 'uni2057', 'uni20B7', 'uni23DF', 'uni23DD', 'uni23E1', 'uni27D7', 'uni27D5', 'uni2A00', 'emptyset', 'uni2031', 'uni27D6', 'uni23DE', 'uni23DC', 'uni23E0', 'uni229B', 'uni229C', 'uni2298', 'uni2296', 'circlemultiply', 'uni2299', 'circleplus', 'uni29B8', 'uni229A', 'uni219C', 'uni219D', 'uni219E', 'uni21A0', 'uni21A2', 'uni21A3', 'uni21A4', 'uni21A6', 'arrowdblright', 'arrowdblleft', 'arrowdblboth', 'uni21DA', 'uni21DB', 'uni21E8', 'uni21E6', 'uni27F5', 'uni27F6', 'uni25EF', 'uni25CD', 'uni25C6', 'uni25C7', 'uni25C8', 'uni25B0', 'uni25B1', 'uni25AD', 'uni25A2', 'uni25A3', 'uni25A4', 'uni25A5', 'uni25A6', 'uni25A7', 'uni25A8', 'uni25A9', 'uni25E7', 'uni25E8', 'uni25E9', 'uni25EA', 'uni25EB', 'uni25F0', 'uni25F1', 'uni25F2', 'uni25F3', 'uni25B6', 'uni25C0', 'uni25B3', 'uni25B7', 'uni25BD', 'uni25C1', 'uni25EC', 'uni25ED', 'uni25EE', 'uni25BB', 'uni25C5', 'uni25E5', 'uni25E2', 'uni25E3', 'uni25E4', 'uni2349', 'uni2365', 'uni233E', 'uni235F', 'uni233D', 'uni235C', 'uni236B', 'uni235A', 'uni2371', 'uni2366', 'uni2367', 'uni236D', 'uni2372', 'uni235D', 'uni236C', 'uni2736', 'uni213A', 'uni2103', 'u1F67C', 'u1F67D', 'u1F67E', 'u1F67F', 'uni2109', 'uni2114', 'uni214F', 'weierstrass'] [code: mono-outliers]
</div></details><details><summary>⚠ <b>WARN:</b> Glyphs are similiar to Google Fonts version? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/production_glyphs_similarity">com.google.fonts/check/production_glyphs_similarity</a>)</summary><div>


* ⚠ **WARN** Following glyphs differ greatly from Google Fonts version:
	* uni0224
	* uniA643
	* uniA773
	* uni20BF
	* uniA738
	* uni023B
	* uni20BB
	* uni1FB8
	* uni019E
	* uni04C5 and 531 more.

Use -F or --full-lists to disable shortening of long lists.
</div></details><details><summary>⚠ <b>WARN:</b> Ensure Stylistic Sets have description. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/stylisticset_description">com.google.fonts/check/stylisticset_description</a>)</summary><div>


* ⚠ **WARN** The stylistic set ss03 lacks a description string on the 'name' table. [code: missing-description]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Glyph names are all valid? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/valid_glyphnames">com.google.fonts/check/valid_glyphnames</a>)</summary><div>


* ⚠ **WARN** The following glyph names may be too long for some legacy systems which may expect a maximum 31-char length limit:
kavykawithkavykaaboveinvertedlow [code: legacy-long-names]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character (codepoint 0x00AD) which is supposed to be zero-width and invisible, and is used to mark a hyphenation possibility within a word in the absence of or overriding dictionary hyphenation. It is mostly an obsolete mechanism now, and the character is only included in fonts for legacy codepage coverage. [code: softhyphen]
* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: uni00AD	Contours detected: 1	Expected: 0

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: ohorn	Contours detected: 3	Expected: 2

	- Glyph name: Uhorn	Contours detected: 2	Expected: 1

	- Glyph name: uhorn	Contours detected: 2	Expected: 1

	- Glyph name: uni01EA	Contours detected: 3	Expected: 2

	- Glyph name: uni01EB	Contours detected: 3	Expected: 2

	- Glyph name: uni01EC	Contours detected: 4	Expected: 3

	- Glyph name: uni01ED	Contours detected: 4	Expected: 3 

	- And 107 more.

Use -F or --full-lists to disable shortening of long lists.
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check mark characters are in GDEF mark glyph class. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_mark_chars">com.google.fonts/check/gdef_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following mark characters could be in the GDEF mark glyph class:
	 uni0488 (U+0488), uni0489 (U+0489), uni1ABE (U+1ABE), uniA670 (U+A670), uniA671 (U+A671) and uniA672 (U+A672) [code: mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Does GPOS table have kerning information? This check skips monospaced fonts as defined by post.isFixedPitch value (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gpos.html#com.google.fonts/check/gpos_kerning_info">com.google.fonts/check/gpos_kerning_info</a>)</summary><div>


* ⚠ **WARN** GPOS table lacks kerning information. [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* uni2E36 (U+2E36): L<<360.0,556.0>--<360.0,444.0>> -> L<<360.0,444.0>--<393.0,0.0>>

	* uni2E37 (U+2E37): L<<215.0,0.0>--<248.0,444.0>> -> L<<248.0,444.0>--<248.0,556.0>>

	* uniA73C (U+A73C): L<<1032.0,714.0>--<853.0,0.0>> -> L<<853.0,0.0>--<841.0,-40.0>> 

	* And uniA779 (U+A779): L<<0.0,725.0>--<304.0,725.0>> -> L<<304.0,725.0>--<304.0,725.0>> [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* Gammalatin (U+0194): B<<293.0,328.0>-<300.0,297.0>-<302.0,273.0>>/B<<302.0,273.0>-<306.0,311.0>-<318.5,360.0>> = 10.772647648220648

	* Lambda (U+039B): B<<307.0,501.0>-<302.0,533.0>-<300.0,552.0>>/B<<300.0,552.0>-<298.0,533.0>-<293.0,501.5>> = 12.018011914988996

	* Nreversedsmall (U+1D0E): B<<199.5,258.5>-<195.0,209.0>-<190.0,145.0>>/L<<190.0,145.0>--<326.0,553.0>> = 13.967789761532726

	* Wanglicana (U+A7C2): B<<176.5,236.0>-<179.0,204.0>-<180.0,184.0>>/B<<180.0,184.0>-<195.0,331.0>-<218.0,440.5>> = 8.688747255667465

	* Wanglicana (U+A7C2): B<<290.0,161.5>-<278.0,229.0>-<273.0,298.0>>/B<<273.0,298.0>-<265.0,239.0>-<257.0,165.0>> = 11.866449541235255

	* onequarter (U+00BC): B<<437.5,213.5>-<438.0,225.0>-<439.0,238.0>>/B<<439.0,238.0>-<434.0,223.0>-<426.5,209.5>> = 14.036243467926457

	* threequarters (U+00BE): B<<437.5,213.5>-<438.0,225.0>-<439.0,238.0>>/B<<439.0,238.0>-<434.0,223.0>-<426.5,209.5>> = 14.036243467926457

	* uni0245 (U+0245): B<<307.0,501.0>-<302.0,533.0>-<300.0,552.0>>/B<<300.0,552.0>-<298.0,533.0>-<293.0,501.5>> = 12.018011914988996

	* uni0274 (U+0274): L<<274.0,553.0>--<410.0,145.0>>/B<<410.0,145.0>-<405.0,209.0>-<400.5,258.5>> = 13.967789761532726

	* uni0394 (U+0394): B<<309.5,536.5>-<302.0,561.0>-<300.0,577.0>>/B<<300.0,577.0>-<298.0,561.0>-<290.5,535.5>> = 14.25003269780357 

	* And 56 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-jaggy-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

	* element (U+2208): L<<381.0,203.0>--<549.0,202.0>>

	* element (U+2208): L<<549.0,62.0>--<381.0,63.0>>

	* notelement (U+2209): L<<381.0,203.0>--<549.0,202.0>>

	* notelement (U+2209): L<<549.0,62.0>--<381.0,63.0>>

	* suchthat (U+220B): L<<219.0,63.0>--<51.0,62.0>>

	* suchthat (U+220B): L<<51.0,202.0>--<219.0,203.0>>

	* uni220A (U+220A): L<<199.0,406.0>--<527.0,405.0>>

	* uni220A (U+220A): L<<323.0,573.0>--<527.0,572.0>>

	* uni220A (U+220A): L<<527.0,133.0>--<328.0,134.0>>

	* uni220A (U+220A): L<<527.0,300.0>--<199.0,301.0>> 

	* And 25 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-semi-vertical]
</div></details><br></div></details><details><summary><b>[15] NotoSansMono-Bold.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* 🔥 **FAIL** Missing required codepoints:

	- 0x00AF (MACRON)
 [code: missing-codepoints]
</div></details><details><summary>🔥 <b>FAIL:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* 🔥 **FAIL** License file OFL.txt exists but NameID 13 (LICENSE DESCRIPTION) value on platform 3 (WINDOWS) is not specified for that. Value was: "This Font Software is licensed under the SIL Open Font License, Version 1.1. This Font Software is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the SIL Open Font License for the specific language, permissions and limitations governing your use of this Font Software." Must be changed to "This Font Software is licensed under the SIL Open Font License, Version 1.1. This license is available with a FAQ at: https://scripts.sil.org/OFL" [code: wrong]
</div></details><details><summary>🔥 <b>FAIL:</b> OS/2.fsSelection bit 7 (USE_TYPO_METRICS) is set in all fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/os2/use_typo_metrics">com.google.fonts/check/os2/use_typo_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2.fsSelection bit 7 (USE_TYPO_METRICS) wasNOT set in the following fonts: ['fonts/NotoSansMono/googlefonts/slim-variable-ttf/NotoSansMono-MM[wght].ttf', 'fonts/NotoSansMono/googlefonts/ttf/NotoSansMono-Black.ttf', 'fonts/NotoSansMono/googlefonts/ttf/NotoSansMono-Bold.ttf', 'fonts/NotoSansMono/googlefonts/ttf/NotoSansMono-ExtraBold.ttf', 'fonts/NotoSansMono/googlefonts/ttf/NotoSansMono-ExtraLight.ttf', 'fonts/NotoSansMono/googlefonts/ttf/NotoSansMono-Light.ttf', 'fonts/NotoSansMono/googlefonts/ttf/NotoSansMono-Medium.ttf', 'fonts/NotoSansMono/googlefonts/ttf/NotoSansMono-Regular.ttf', 'fonts/NotoSansMono/googlefonts/ttf/NotoSansMono-SemiBold.ttf', 'fonts/NotoSansMono/googlefonts/ttf/NotoSansMono-Thin.ttf', 'fonts/NotoSansMono/googlefonts/variable-ttf/NotoSansMono-MM[wdth,wght].ttf']. [code: missing-os2-fsselection-bit7]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinAscent value should be equal or greater than 1239, but got 1069 instead [code: ascent]
* 🔥 **FAIL** OS/2.usWinDescent value should be equal or greater than 389, but got 293 instead. [code: descent]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking correctness of monospaced metadata. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/name.html#com.google.fonts/check/monospace">com.google.fonts/check/monospace</a>)</summary><div>


* 🔥 **FAIL** On monospaced fonts, the value of post.isFixedPitch must be set to a non-zero value (meaning 'fixed width monospaced'), but got 0 instead. [code: mono-bad-post-isFixedPitch]
* ⚠ **WARN** Font is monospaced but 250 glyphs (6.60%) have a different width. You should check the widths of: ['oneeighth', 'threeeighths', 'fiveeighths', 'seveneighths', 'uniFFFC', 'uniFFFD', 'uni0468', 'uni046C', 'uni046D', 'uni0478', 'uni0479', 'uni01A2', 'uni01C4', 'uni01C5', 'uni01C6', 'uni01C7', 'uni01C8', 'uni01C9', 'uni01CA', 'uni01CB', 'uni01CC', 'uni01F1', 'uni01F2', 'uni01F3', 'uni02A5', 'uni02A8', 'uni1D7A', 'uni1F0A', 'uni1F0B', 'uni1F0C', 'uni1F0D', 'uni1F0E', 'uni1F0F', 'uni1F1A', 'uni1F1B', 'uni1F1C', 'uni1F1D', 'uni1F2A', 'uni1F2B', 'uni1F2C', 'uni1F2D', 'uni1F2E', 'uni1F2F', 'uni1F4A', 'uni1F4B', 'uni1F4C', 'uni1F4D', 'uni1F5B', 'uni1F5D', 'uni1F5F', 'uni1F6A', 'uni1F6B', 'uni1F6C', 'uni1F6D', 'uni1F6E', 'uni1F6F', 'uni1F88', 'uni1F89', 'uni1F8A', 'uni1F8B', 'uni1F8C', 'uni1F8D', 'uni1F8E', 'uni1F8F', 'uni1F98', 'uni1F99', 'uni1F9A', 'uni1F9B', 'uni1F9C', 'uni1F9D', 'uni1F9E', 'uni1F9F', 'uni1FA8', 'uni1FA9', 'uni1FAA', 'uni1FAB', 'uni1FAC', 'uni1FAD', 'uni1FAE', 'uni1FAF', 'uni1FBC', 'uni1FCC', 'uni1FFC', 'uni20A8', 'uni2153', 'uni2154', 'uni0518', 'uni0520', 'uni0521', 'uni0522', 'uni0523', 'uniA728', 'uniA732', 'uniA734', 'uniA736', 'uniA738', 'uniA73A', 'uniA73C', 'uniA74E', 'uniA729', 'uniA74F', 'uniA773', 'sakhayat', 'uniA7FF', 'Iotifiedacy', 'Yusiotifiedclosedlittlecy', 'Emsoftcy', 'Odoublemonocularcy', 'uniA684', 'Odoublecy', 'uni052A', 'uniA657', 'yusiotifiedclosedlittlecy', 'emsoftcy', 'odoublemonocularcy', 'odoublecy', 'uni052B', 'uni211C', 'uni212C', 'uni210B', 'uni2110', 'uni2112', 'uni211B', 'uni2131', 'uni2133', 'uni2474', 'uni2475', 'uni2189', 'uni2155', 'uni2156', 'uni2157', 'uni2158', 'uni2159', 'uni215A', 'uni2150', 'uni2151', 'uni2152', 'uni2042', 'uni2E0E', 'uni2047', 'uni203B', 'uni2053', 'uni2E3B', 'uni2E3A', 'uni2057', 'uni20B7', 'uni23DF', 'uni23DD', 'uni23E1', 'uni27D7', 'uni27D5', 'uni2A00', 'emptyset', 'uni2031', 'uni27D6', 'uni23DE', 'uni23DC', 'uni23E0', 'uni229B', 'uni229C', 'uni2298', 'uni2296', 'circlemultiply', 'uni2299', 'circleplus', 'uni29B8', 'uni229A', 'uni219C', 'uni219D', 'uni219E', 'uni21A0', 'uni21A2', 'uni21A3', 'uni21A4', 'uni21A6', 'arrowdblright', 'arrowdblleft', 'arrowdblboth', 'uni21DA', 'uni21DB', 'uni21E8', 'uni21E6', 'uni27F5', 'uni27F6', 'uni25EF', 'uni25CD', 'uni25C6', 'uni25C7', 'uni25C8', 'uni25B0', 'uni25B1', 'uni25AD', 'uni25A2', 'uni25A3', 'uni25A4', 'uni25A5', 'uni25A6', 'uni25A7', 'uni25A8', 'uni25A9', 'uni25E7', 'uni25E8', 'uni25E9', 'uni25EA', 'uni25EB', 'uni25F0', 'uni25F1', 'uni25F2', 'uni25F3', 'uni25B6', 'uni25C0', 'uni25B3', 'uni25B7', 'uni25BD', 'uni25C1', 'uni25EC', 'uni25ED', 'uni25EE', 'uni25BB', 'uni25C5', 'uni25E5', 'uni25E2', 'uni25E3', 'uni25E4', 'uni2349', 'uni2365', 'uni233E', 'uni235F', 'uni233D', 'uni235C', 'uni236B', 'uni235A', 'uni2371', 'uni2366', 'uni2367', 'uni236D', 'uni2372', 'uni235D', 'uni236C', 'uni2736', 'uni213A', 'uni2103', 'u1F67C', 'u1F67D', 'u1F67E', 'u1F67F', 'uni2109', 'uni2114', 'uni214F', 'weierstrass'] [code: mono-outliers]
</div></details><details><summary>⚠ <b>WARN:</b> Glyphs are similiar to Google Fonts version? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/production_glyphs_similarity">com.google.fonts/check/production_glyphs_similarity</a>)</summary><div>


* ⚠ **WARN** Following glyphs differ greatly from Google Fonts version:
	* uni0224
	* uniA643
	* uniA773
	* uni20BF
	* uniA738
	* uni023B
	* uni20BB
	* uni019E
	* uni04C5
	* uni04FC and 440 more.

Use -F or --full-lists to disable shortening of long lists.
</div></details><details><summary>⚠ <b>WARN:</b> Ensure Stylistic Sets have description. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/stylisticset_description">com.google.fonts/check/stylisticset_description</a>)</summary><div>


* ⚠ **WARN** The stylistic set ss03 lacks a description string on the 'name' table. [code: missing-description]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Glyph names are all valid? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/valid_glyphnames">com.google.fonts/check/valid_glyphnames</a>)</summary><div>


* ⚠ **WARN** The following glyph names may be too long for some legacy systems which may expect a maximum 31-char length limit:
kavykawithkavykaaboveinvertedlow [code: legacy-long-names]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character (codepoint 0x00AD) which is supposed to be zero-width and invisible, and is used to mark a hyphenation possibility within a word in the absence of or overriding dictionary hyphenation. It is mostly an obsolete mechanism now, and the character is only included in fonts for legacy codepage coverage. [code: softhyphen]
* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: uni00AD	Contours detected: 1	Expected: 0

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: ohorn	Contours detected: 3	Expected: 2

	- Glyph name: Uhorn	Contours detected: 2	Expected: 1

	- Glyph name: uhorn	Contours detected: 2	Expected: 1

	- Glyph name: uni01EA	Contours detected: 3	Expected: 2

	- Glyph name: uni01EB	Contours detected: 3	Expected: 2

	- Glyph name: uni01EC	Contours detected: 4	Expected: 3

	- Glyph name: uni01ED	Contours detected: 4	Expected: 3 

	- And 107 more.

Use -F or --full-lists to disable shortening of long lists.
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check mark characters are in GDEF mark glyph class. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_mark_chars">com.google.fonts/check/gdef_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following mark characters could be in the GDEF mark glyph class:
	 uni0488 (U+0488), uni0489 (U+0489), uni1ABE (U+1ABE), uniA670 (U+A670), uniA671 (U+A671) and uniA672 (U+A672) [code: mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Does GPOS table have kerning information? This check skips monospaced fonts as defined by post.isFixedPitch value (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gpos.html#com.google.fonts/check/gpos_kerning_info">com.google.fonts/check/gpos_kerning_info</a>)</summary><div>


* ⚠ **WARN** GPOS table lacks kerning information. [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* Ukmonographcy (U+A64A): L<<365.0,336.0>--<365.0,335.0>> -> L<<365.0,335.0>--<365.0,201.0>>

	* uni0181 (U+0181): L<<164.0,714.0>--<164.0,714.0>> -> L<<164.0,714.0>--<327.0,714.0>>

	* uni018A (U+018A): L<<168.0,714.0>--<168.0,714.0>> -> L<<168.0,714.0>--<329.0,714.0>>

	* uni2E36 (U+2E36): L<<344.0,556.0>--<344.0,468.0>> -> L<<344.0,468.0>--<371.0,0.0>>

	* uni2E37 (U+2E37): L<<225.0,0.0>--<252.0,468.0>> -> L<<252.0,468.0>--<252.0,556.0>>

	* uniA73C (U+A73C): L<<1053.0,714.0>--<841.0,0.0>> -> L<<841.0,0.0>--<827.0,-44.0>> 

	* And uniA779 (U+A779): L<<0.0,726.0>--<304.0,726.0>> -> L<<304.0,726.0>--<304.0,726.0>> [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* Wanglicana (U+A7C2): B<<158.5,185.5>-<161.0,153.0>-<161.0,132.0>>/B<<161.0,132.0>-<181.0,280.0>-<205.0,392.0>> = 7.696051722016556

	* Wanglicana (U+A7C2): B<<267.0,169.0>-<256.0,241.0>-<252.0,316.0>>/B<<252.0,316.0>-<242.0,254.0>-<232.5,175.5>> = 12.215229560514134

	* uni20A9 (U+20A9): L<<156.0,320.0>--<173.0,147.0>>/L<<173.0,147.0>--<194.0,320.0>> = 12.533320867759878

	* uni20A9 (U+20A9): L<<323.0,394.0>--<302.0,559.0>>/L<<302.0,559.0>--<283.0,394.0>> = 13.821958734546453

	* uni20A9 (U+20A9): L<<412.0,320.0>--<432.0,147.0>>/L<<432.0,147.0>--<451.0,320.0>> = 12.861996437077291

	* uni210A (U+210A): B<<90.5,185.5>-<98.0,204.0>-<104.0,211.0>>/B<<104.0,211.0>-<72.0,173.0>-<33.0,145.0>> = 0.50038709879258

	* uni210B (U+210B): B<<526.5,433.0>-<566.0,504.0>-<629.0,581.0>>/B<<629.0,581.0>-<612.0,565.0>-<585.0,542.0>> = 7.4462977264280115

	* uni211F (U+211F): L<<225.0,269.0>--<225.0,84.0>>/L<<225.0,84.0>--<269.0,269.0>> = 13.37854019507151

	* uni2133 (U+2133): B<<822.0,667.5>-<838.0,690.0>-<844.0,697.0>>/B<<844.0,697.0>-<821.0,680.0>-<789.0,648.0>> = 12.929470964943654

	* uni2137 (U+2137): L<<372.0,0.0>--<333.0,174.0>>/B<<333.0,174.0>-<333.0,126.0>-<314.5,102.0>> = 12.633361935275003 

	* And 6 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-jaggy-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

	* element (U+2208): L<<378.0,176.0>--<549.0,175.0>>

	* element (U+2208): L<<549.0,62.0>--<378.0,63.0>>

	* notelement (U+2209): L<<378.0,176.0>--<549.0,175.0>>

	* notelement (U+2209): L<<549.0,62.0>--<378.0,63.0>>

	* suchthat (U+220B): L<<221.0,63.0>--<51.0,62.0>>

	* suchthat (U+220B): L<<51.0,175.0>--<221.0,176.0>>

	* uni220A (U+220A): L<<177.0,399.0>--<527.0,398.0>>

	* uni220A (U+220A): L<<326.0,573.0>--<527.0,572.0>>

	* uni220A (U+220A): L<<527.0,133.0>--<329.0,134.0>>

	* uni220A (U+220A): L<<527.0,480.0>--<326.0,481.0>> 

	* And 18 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-semi-vertical]
</div></details><br></div></details><details><summary><b>[16] NotoSansMono-ExtraBold.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* 🔥 **FAIL** Missing required codepoints:

	- 0x00AF (MACRON)
 [code: missing-codepoints]
</div></details><details><summary>🔥 <b>FAIL:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* 🔥 **FAIL** License file OFL.txt exists but NameID 13 (LICENSE DESCRIPTION) value on platform 3 (WINDOWS) is not specified for that. Value was: "This Font Software is licensed under the SIL Open Font License, Version 1.1. This Font Software is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the SIL Open Font License for the specific language, permissions and limitations governing your use of this Font Software." Must be changed to "This Font Software is licensed under the SIL Open Font License, Version 1.1. This license is available with a FAQ at: https://scripts.sil.org/OFL" [code: wrong]
</div></details><details><summary>🔥 <b>FAIL:</b> OS/2.fsSelection bit 7 (USE_TYPO_METRICS) is set in all fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/os2/use_typo_metrics">com.google.fonts/check/os2/use_typo_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2.fsSelection bit 7 (USE_TYPO_METRICS) wasNOT set in the following fonts: ['fonts/NotoSansMono/googlefonts/slim-variable-ttf/NotoSansMono-MM[wght].ttf', 'fonts/NotoSansMono/googlefonts/ttf/NotoSansMono-Black.ttf', 'fonts/NotoSansMono/googlefonts/ttf/NotoSansMono-Bold.ttf', 'fonts/NotoSansMono/googlefonts/ttf/NotoSansMono-ExtraBold.ttf', 'fonts/NotoSansMono/googlefonts/ttf/NotoSansMono-ExtraLight.ttf', 'fonts/NotoSansMono/googlefonts/ttf/NotoSansMono-Light.ttf', 'fonts/NotoSansMono/googlefonts/ttf/NotoSansMono-Medium.ttf', 'fonts/NotoSansMono/googlefonts/ttf/NotoSansMono-Regular.ttf', 'fonts/NotoSansMono/googlefonts/ttf/NotoSansMono-SemiBold.ttf', 'fonts/NotoSansMono/googlefonts/ttf/NotoSansMono-Thin.ttf', 'fonts/NotoSansMono/googlefonts/variable-ttf/NotoSansMono-MM[wdth,wght].ttf']. [code: missing-os2-fsselection-bit7]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinAscent value should be equal or greater than 1239, but got 1069 instead [code: ascent]
* 🔥 **FAIL** OS/2.usWinDescent value should be equal or greater than 389, but got 293 instead. [code: descent]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking correctness of monospaced metadata. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/name.html#com.google.fonts/check/monospace">com.google.fonts/check/monospace</a>)</summary><div>


* 🔥 **FAIL** On monospaced fonts, the value of post.isFixedPitch must be set to a non-zero value (meaning 'fixed width monospaced'), but got 0 instead. [code: mono-bad-post-isFixedPitch]
* ⚠ **WARN** Font is monospaced but 250 glyphs (6.60%) have a different width. You should check the widths of: ['oneeighth', 'threeeighths', 'fiveeighths', 'seveneighths', 'uniFFFC', 'uniFFFD', 'uni0468', 'uni046C', 'uni046D', 'uni0478', 'uni0479', 'uni01A2', 'uni01C4', 'uni01C5', 'uni01C6', 'uni01C7', 'uni01C8', 'uni01C9', 'uni01CA', 'uni01CB', 'uni01CC', 'uni01F1', 'uni01F2', 'uni01F3', 'uni02A5', 'uni02A8', 'uni1D7A', 'uni1F0A', 'uni1F0B', 'uni1F0C', 'uni1F0D', 'uni1F0E', 'uni1F0F', 'uni1F1A', 'uni1F1B', 'uni1F1C', 'uni1F1D', 'uni1F2A', 'uni1F2B', 'uni1F2C', 'uni1F2D', 'uni1F2E', 'uni1F2F', 'uni1F4A', 'uni1F4B', 'uni1F4C', 'uni1F4D', 'uni1F5B', 'uni1F5D', 'uni1F5F', 'uni1F6A', 'uni1F6B', 'uni1F6C', 'uni1F6D', 'uni1F6E', 'uni1F6F', 'uni1F88', 'uni1F89', 'uni1F8A', 'uni1F8B', 'uni1F8C', 'uni1F8D', 'uni1F8E', 'uni1F8F', 'uni1F98', 'uni1F99', 'uni1F9A', 'uni1F9B', 'uni1F9C', 'uni1F9D', 'uni1F9E', 'uni1F9F', 'uni1FA8', 'uni1FA9', 'uni1FAA', 'uni1FAB', 'uni1FAC', 'uni1FAD', 'uni1FAE', 'uni1FAF', 'uni1FBC', 'uni1FCC', 'uni1FFC', 'uni20A8', 'uni2153', 'uni2154', 'uni0518', 'uni0520', 'uni0521', 'uni0522', 'uni0523', 'uniA728', 'uniA732', 'uniA734', 'uniA736', 'uniA738', 'uniA73A', 'uniA73C', 'uniA74E', 'uniA729', 'uniA74F', 'uniA773', 'sakhayat', 'uniA7FF', 'Iotifiedacy', 'Yusiotifiedclosedlittlecy', 'Emsoftcy', 'Odoublemonocularcy', 'uniA684', 'Odoublecy', 'uni052A', 'uniA657', 'yusiotifiedclosedlittlecy', 'emsoftcy', 'odoublemonocularcy', 'odoublecy', 'uni052B', 'uni211C', 'uni212C', 'uni210B', 'uni2110', 'uni2112', 'uni211B', 'uni2131', 'uni2133', 'uni2474', 'uni2475', 'uni2189', 'uni2155', 'uni2156', 'uni2157', 'uni2158', 'uni2159', 'uni215A', 'uni2150', 'uni2151', 'uni2152', 'uni2042', 'uni2E0E', 'uni2047', 'uni203B', 'uni2053', 'uni2E3B', 'uni2E3A', 'uni2057', 'uni20B7', 'uni23DF', 'uni23DD', 'uni23E1', 'uni27D7', 'uni27D5', 'uni2A00', 'emptyset', 'uni2031', 'uni27D6', 'uni23DE', 'uni23DC', 'uni23E0', 'uni229B', 'uni229C', 'uni2298', 'uni2296', 'circlemultiply', 'uni2299', 'circleplus', 'uni29B8', 'uni229A', 'uni219C', 'uni219D', 'uni219E', 'uni21A0', 'uni21A2', 'uni21A3', 'uni21A4', 'uni21A6', 'arrowdblright', 'arrowdblleft', 'arrowdblboth', 'uni21DA', 'uni21DB', 'uni21E8', 'uni21E6', 'uni27F5', 'uni27F6', 'uni25EF', 'uni25CD', 'uni25C6', 'uni25C7', 'uni25C8', 'uni25B0', 'uni25B1', 'uni25AD', 'uni25A2', 'uni25A3', 'uni25A4', 'uni25A5', 'uni25A6', 'uni25A7', 'uni25A8', 'uni25A9', 'uni25E7', 'uni25E8', 'uni25E9', 'uni25EA', 'uni25EB', 'uni25F0', 'uni25F1', 'uni25F2', 'uni25F3', 'uni25B6', 'uni25C0', 'uni25B3', 'uni25B7', 'uni25BD', 'uni25C1', 'uni25EC', 'uni25ED', 'uni25EE', 'uni25BB', 'uni25C5', 'uni25E5', 'uni25E2', 'uni25E3', 'uni25E4', 'uni2349', 'uni2365', 'uni233E', 'uni235F', 'uni233D', 'uni235C', 'uni236B', 'uni235A', 'uni2371', 'uni2366', 'uni2367', 'uni236D', 'uni2372', 'uni235D', 'uni236C', 'uni2736', 'uni213A', 'uni2103', 'u1F67C', 'u1F67D', 'u1F67E', 'u1F67F', 'uni2109', 'uni2114', 'uni214F', 'weierstrass'] [code: mono-outliers]
</div></details><details><summary>⚠ <b>WARN:</b> Glyphs are similiar to Google Fonts version? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/production_glyphs_similarity">com.google.fonts/check/production_glyphs_similarity</a>)</summary><div>


* ⚠ **WARN** Following glyphs differ greatly from Google Fonts version:
	* uni0224
	* uniA643
	* uniA773
	* uni20BF
	* uniA738
	* uni023B
	* uni20BB
	* uni019E
	* uni04C5
	* uni04FC and 465 more.

Use -F or --full-lists to disable shortening of long lists.
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Noto Sans Mono ExtraBold' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/googlefonts/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure Stylistic Sets have description. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/stylisticset_description">com.google.fonts/check/stylisticset_description</a>)</summary><div>


* ⚠ **WARN** The stylistic set ss03 lacks a description string on the 'name' table. [code: missing-description]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Glyph names are all valid? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/valid_glyphnames">com.google.fonts/check/valid_glyphnames</a>)</summary><div>


* ⚠ **WARN** The following glyph names may be too long for some legacy systems which may expect a maximum 31-char length limit:
kavykawithkavykaaboveinvertedlow [code: legacy-long-names]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character (codepoint 0x00AD) which is supposed to be zero-width and invisible, and is used to mark a hyphenation possibility within a word in the absence of or overriding dictionary hyphenation. It is mostly an obsolete mechanism now, and the character is only included in fonts for legacy codepage coverage. [code: softhyphen]
* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: uni00AD	Contours detected: 1	Expected: 0

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: ohorn	Contours detected: 3	Expected: 2

	- Glyph name: Uhorn	Contours detected: 2	Expected: 1

	- Glyph name: uhorn	Contours detected: 2	Expected: 1

	- Glyph name: uni01EA	Contours detected: 3	Expected: 2

	- Glyph name: uni01EB	Contours detected: 3	Expected: 2

	- Glyph name: uni01EC	Contours detected: 4	Expected: 3

	- Glyph name: uni01ED	Contours detected: 4	Expected: 3 

	- And 107 more.

Use -F or --full-lists to disable shortening of long lists.
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check mark characters are in GDEF mark glyph class. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_mark_chars">com.google.fonts/check/gdef_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following mark characters could be in the GDEF mark glyph class:
	 uni0488 (U+0488), uni0489 (U+0489), uni1ABE (U+1ABE), uniA670 (U+A670), uniA671 (U+A671) and uniA672 (U+A672) [code: mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Does GPOS table have kerning information? This check skips monospaced fonts as defined by post.isFixedPitch value (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gpos.html#com.google.fonts/check/gpos_kerning_info">com.google.fonts/check/gpos_kerning_info</a>)</summary><div>


* ⚠ **WARN** GPOS table lacks kerning information. [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* uni0181 (U+0181): L<<176.0,714.0>--<176.0,714.0>> -> L<<176.0,714.0>--<343.0,714.0>>

	* uni018A (U+018A): L<<172.0,714.0>--<172.0,714.0>> -> L<<172.0,714.0>--<337.0,714.0>>

	* uni2E36 (U+2E36): L<<351.0,556.0>--<351.0,457.0>> -> L<<351.0,457.0>--<381.0,0.0>>

	* uni2E37 (U+2E37): L<<220.0,0.0>--<250.0,457.0>> -> L<<250.0,457.0>--<250.0,556.0>>

	* uniA737 (U+A737): L<<235.0,184.0>--<235.0,190.0>> -> L<<235.0,190.0>--<235.0,244.0>>

	* uniA73C (U+A73C): L<<1043.0,714.0>--<847.0,0.0>> -> L<<847.0,0.0>--<833.0,-42.0>> 

	* And uniA779 (U+A779): L<<0.0,726.0>--<304.0,726.0>> -> L<<304.0,726.0>--<304.0,726.0>> [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* Gammalatin (U+0194): B<<285.5,360.0>-<297.0,317.0>-<301.0,283.0>>/B<<301.0,283.0>-<305.0,318.0>-<316.5,361.5>> = 13.229638559413885

	* Wanglicana (U+A7C2): B<<166.5,209.0>-<169.0,177.0>-<170.0,156.0>>/B<<170.0,156.0>-<188.0,305.0>-<211.5,416.0>> = 9.614569270900917

	* Wanglicana (U+A7C2): B<<277.5,165.5>-<266.0,235.0>-<262.0,307.0>>/B<<262.0,307.0>-<244.0,187.0>-<226.0,0.0>> = 11.71059572981233

	* uni0394 (U+0394): B<<306.0,560.0>-<301.0,578.0>-<300.0,587.0>>/B<<300.0,587.0>-<299.0,578.0>-<294.0,560.0>> = 12.680383491819825

	* uni0416 (U+0416): L<<153.0,714.0>--<232.0,368.0>>/L<<232.0,368.0>--<232.0,714.0>> = 12.861511735772941

	* uni0416 (U+0416): L<<232.0,0.0>--<232.0,362.0>>/L<<232.0,362.0>--<149.0,0.0>> = 12.913674271275106

	* uni0416 (U+0416): L<<370.0,714.0>--<370.0,368.0>>/L<<370.0,368.0>--<450.0,714.0>> = 13.018802429784794

	* uni0416 (U+0416): L<<454.0,0.0>--<370.0,362.0>>/L<<370.0,362.0>--<370.0,0.0>> = 13.06395412738628

	* uni0474 (U+0474): B<<274.5,212.5>-<280.0,182.0>-<282.0,160.0>>/B<<282.0,160.0>-<285.0,181.0>-<290.5,211.0>> = 13.324531261890755

	* uni0476 (U+0476): B<<274.5,212.5>-<280.0,182.0>-<282.0,160.0>>/B<<282.0,160.0>-<285.0,181.0>-<290.5,211.0>> = 13.324531261890755 

	* And 29 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-jaggy-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

	* element (U+2208): L<<379.0,188.0>--<549.0,187.0>>

	* element (U+2208): L<<549.0,62.0>--<379.0,63.0>>

	* notelement (U+2209): L<<379.0,188.0>--<549.0,187.0>>

	* notelement (U+2209): L<<549.0,62.0>--<379.0,63.0>>

	* suchthat (U+220B): L<<220.0,63.0>--<51.0,62.0>>

	* suchthat (U+220B): L<<51.0,187.0>--<220.0,188.0>>

	* uni1EFA (U+1EFA): L<<451.0,141.0>--<577.0,140.0>>

	* uni220A (U+220A): L<<187.0,402.0>--<527.0,401.0>>

	* uni220A (U+220A): L<<325.0,573.0>--<527.0,572.0>>

	* uni220A (U+220A): L<<527.0,133.0>--<329.0,134.0>> 

	* And 20 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-semi-vertical]
</div></details><br></div></details><details><summary><b>[16] NotoSansMono-ExtraLight.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* 🔥 **FAIL** Missing required codepoints:

	- 0x00AF (MACRON)
 [code: missing-codepoints]
</div></details><details><summary>🔥 <b>FAIL:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* 🔥 **FAIL** License file OFL.txt exists but NameID 13 (LICENSE DESCRIPTION) value on platform 3 (WINDOWS) is not specified for that. Value was: "This Font Software is licensed under the SIL Open Font License, Version 1.1. This Font Software is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the SIL Open Font License for the specific language, permissions and limitations governing your use of this Font Software." Must be changed to "This Font Software is licensed under the SIL Open Font License, Version 1.1. This license is available with a FAQ at: https://scripts.sil.org/OFL" [code: wrong]
</div></details><details><summary>🔥 <b>FAIL:</b> OS/2.fsSelection bit 7 (USE_TYPO_METRICS) is set in all fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/os2/use_typo_metrics">com.google.fonts/check/os2/use_typo_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2.fsSelection bit 7 (USE_TYPO_METRICS) wasNOT set in the following fonts: ['fonts/NotoSansMono/googlefonts/slim-variable-ttf/NotoSansMono-MM[wght].ttf', 'fonts/NotoSansMono/googlefonts/ttf/NotoSansMono-Black.ttf', 'fonts/NotoSansMono/googlefonts/ttf/NotoSansMono-Bold.ttf', 'fonts/NotoSansMono/googlefonts/ttf/NotoSansMono-ExtraBold.ttf', 'fonts/NotoSansMono/googlefonts/ttf/NotoSansMono-ExtraLight.ttf', 'fonts/NotoSansMono/googlefonts/ttf/NotoSansMono-Light.ttf', 'fonts/NotoSansMono/googlefonts/ttf/NotoSansMono-Medium.ttf', 'fonts/NotoSansMono/googlefonts/ttf/NotoSansMono-Regular.ttf', 'fonts/NotoSansMono/googlefonts/ttf/NotoSansMono-SemiBold.ttf', 'fonts/NotoSansMono/googlefonts/ttf/NotoSansMono-Thin.ttf', 'fonts/NotoSansMono/googlefonts/variable-ttf/NotoSansMono-MM[wdth,wght].ttf']. [code: missing-os2-fsselection-bit7]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinAscent value should be equal or greater than 1239, but got 1069 instead [code: ascent]
* 🔥 **FAIL** OS/2.usWinDescent value should be equal or greater than 389, but got 293 instead. [code: descent]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking correctness of monospaced metadata. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/name.html#com.google.fonts/check/monospace">com.google.fonts/check/monospace</a>)</summary><div>


* 🔥 **FAIL** On monospaced fonts, the value of post.isFixedPitch must be set to a non-zero value (meaning 'fixed width monospaced'), but got 0 instead. [code: mono-bad-post-isFixedPitch]
* ⚠ **WARN** Font is monospaced but 250 glyphs (6.60%) have a different width. You should check the widths of: ['oneeighth', 'threeeighths', 'fiveeighths', 'seveneighths', 'uniFFFC', 'uniFFFD', 'uni0468', 'uni046C', 'uni046D', 'uni0478', 'uni0479', 'uni01A2', 'uni01C4', 'uni01C5', 'uni01C6', 'uni01C7', 'uni01C8', 'uni01C9', 'uni01CA', 'uni01CB', 'uni01CC', 'uni01F1', 'uni01F2', 'uni01F3', 'uni02A5', 'uni02A8', 'uni1D7A', 'uni1F0A', 'uni1F0B', 'uni1F0C', 'uni1F0D', 'uni1F0E', 'uni1F0F', 'uni1F1A', 'uni1F1B', 'uni1F1C', 'uni1F1D', 'uni1F2A', 'uni1F2B', 'uni1F2C', 'uni1F2D', 'uni1F2E', 'uni1F2F', 'uni1F4A', 'uni1F4B', 'uni1F4C', 'uni1F4D', 'uni1F5B', 'uni1F5D', 'uni1F5F', 'uni1F6A', 'uni1F6B', 'uni1F6C', 'uni1F6D', 'uni1F6E', 'uni1F6F', 'uni1F88', 'uni1F89', 'uni1F8A', 'uni1F8B', 'uni1F8C', 'uni1F8D', 'uni1F8E', 'uni1F8F', 'uni1F98', 'uni1F99', 'uni1F9A', 'uni1F9B', 'uni1F9C', 'uni1F9D', 'uni1F9E', 'uni1F9F', 'uni1FA8', 'uni1FA9', 'uni1FAA', 'uni1FAB', 'uni1FAC', 'uni1FAD', 'uni1FAE', 'uni1FAF', 'uni1FBC', 'uni1FCC', 'uni1FFC', 'uni20A8', 'uni2153', 'uni2154', 'uni0518', 'uni0520', 'uni0521', 'uni0522', 'uni0523', 'uniA728', 'uniA732', 'uniA734', 'uniA736', 'uniA738', 'uniA73A', 'uniA73C', 'uniA74E', 'uniA729', 'uniA74F', 'uniA773', 'sakhayat', 'uniA7FF', 'Iotifiedacy', 'Yusiotifiedclosedlittlecy', 'Emsoftcy', 'Odoublemonocularcy', 'uniA684', 'Odoublecy', 'uni052A', 'uniA657', 'yusiotifiedclosedlittlecy', 'emsoftcy', 'odoublemonocularcy', 'odoublecy', 'uni052B', 'uni211C', 'uni212C', 'uni210B', 'uni2110', 'uni2112', 'uni211B', 'uni2131', 'uni2133', 'uni2474', 'uni2475', 'uni2189', 'uni2155', 'uni2156', 'uni2157', 'uni2158', 'uni2159', 'uni215A', 'uni2150', 'uni2151', 'uni2152', 'uni2042', 'uni2E0E', 'uni2047', 'uni203B', 'uni2053', 'uni2E3B', 'uni2E3A', 'uni2057', 'uni20B7', 'uni23DF', 'uni23DD', 'uni23E1', 'uni27D7', 'uni27D5', 'uni2A00', 'emptyset', 'uni2031', 'uni27D6', 'uni23DE', 'uni23DC', 'uni23E0', 'uni229B', 'uni229C', 'uni2298', 'uni2296', 'circlemultiply', 'uni2299', 'circleplus', 'uni29B8', 'uni229A', 'uni219C', 'uni219D', 'uni219E', 'uni21A0', 'uni21A2', 'uni21A3', 'uni21A4', 'uni21A6', 'arrowdblright', 'arrowdblleft', 'arrowdblboth', 'uni21DA', 'uni21DB', 'uni21E8', 'uni21E6', 'uni27F5', 'uni27F6', 'uni25EF', 'uni25CD', 'uni25C6', 'uni25C7', 'uni25C8', 'uni25B0', 'uni25B1', 'uni25AD', 'uni25A2', 'uni25A3', 'uni25A4', 'uni25A5', 'uni25A6', 'uni25A7', 'uni25A8', 'uni25A9', 'uni25E7', 'uni25E8', 'uni25E9', 'uni25EA', 'uni25EB', 'uni25F0', 'uni25F1', 'uni25F2', 'uni25F3', 'uni25B6', 'uni25C0', 'uni25B3', 'uni25B7', 'uni25BD', 'uni25C1', 'uni25EC', 'uni25ED', 'uni25EE', 'uni25BB', 'uni25C5', 'uni25E5', 'uni25E2', 'uni25E3', 'uni25E4', 'uni2349', 'uni2365', 'uni233E', 'uni235F', 'uni233D', 'uni235C', 'uni236B', 'uni235A', 'uni2371', 'uni2366', 'uni2367', 'uni236D', 'uni2372', 'uni235D', 'uni236C', 'uni2736', 'uni213A', 'uni2103', 'u1F67C', 'u1F67D', 'u1F67E', 'u1F67F', 'uni2109', 'uni2114', 'uni214F', 'weierstrass'] [code: mono-outliers]
</div></details><details><summary>⚠ <b>WARN:</b> Glyphs are similiar to Google Fonts version? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/production_glyphs_similarity">com.google.fonts/check/production_glyphs_similarity</a>)</summary><div>


* ⚠ **WARN** Following glyphs differ greatly from Google Fonts version:
	* uni2475
	* backslash
	* uni020F
	* uni2035
	* uni04ED
	* uni0295
	* radical.mir
	* uniA684
	* uni020A
	* uni0207 and 73 more.

Use -F or --full-lists to disable shortening of long lists.
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Noto Sans Mono ExtraLight' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/googlefonts/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure Stylistic Sets have description. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/stylisticset_description">com.google.fonts/check/stylisticset_description</a>)</summary><div>


* ⚠ **WARN** The stylistic set ss03 lacks a description string on the 'name' table. [code: missing-description]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Glyph names are all valid? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/valid_glyphnames">com.google.fonts/check/valid_glyphnames</a>)</summary><div>


* ⚠ **WARN** The following glyph names may be too long for some legacy systems which may expect a maximum 31-char length limit:
kavykawithkavykaaboveinvertedlow [code: legacy-long-names]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character (codepoint 0x00AD) which is supposed to be zero-width and invisible, and is used to mark a hyphenation possibility within a word in the absence of or overriding dictionary hyphenation. It is mostly an obsolete mechanism now, and the character is only included in fonts for legacy codepage coverage. [code: softhyphen]
* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: uni00AD	Contours detected: 1	Expected: 0

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: ohorn	Contours detected: 3	Expected: 2

	- Glyph name: Uhorn	Contours detected: 2	Expected: 1

	- Glyph name: uhorn	Contours detected: 2	Expected: 1

	- Glyph name: uni01EA	Contours detected: 3	Expected: 2

	- Glyph name: uni01EB	Contours detected: 3	Expected: 2

	- Glyph name: uni01EC	Contours detected: 4	Expected: 3

	- Glyph name: uni01ED	Contours detected: 4	Expected: 3 

	- And 105 more.

Use -F or --full-lists to disable shortening of long lists.
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check mark characters are in GDEF mark glyph class. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_mark_chars">com.google.fonts/check/gdef_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following mark characters could be in the GDEF mark glyph class:
	 uni0488 (U+0488), uni0489 (U+0489), uni1ABE (U+1ABE), uniA670 (U+A670), uniA671 (U+A671) and uniA672 (U+A672) [code: mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Does GPOS table have kerning information? This check skips monospaced fonts as defined by post.isFixedPitch value (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gpos.html#com.google.fonts/check/gpos_kerning_info">com.google.fonts/check/gpos_kerning_info</a>)</summary><div>


* ⚠ **WARN** GPOS table lacks kerning information. [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* crosspattyleft (U+2E51): L<<407.0,632.0>--<398.0,361.0>> -> L<<398.0,361.0>--<407.0,88.0>>

	* crosspattyright (U+2E50): L<<193.0,88.0>--<202.0,361.0>> -> L<<202.0,361.0>--<193.0,632.0>>

	* daggerdbl (U+2021): L<<286.0,226.0>--<280.0,383.0>> -> L<<280.0,383.0>--<286.0,534.0>>

	* daggerdbl (U+2021): L<<312.0,534.0>--<318.0,383.0>> -> L<<318.0,383.0>--<312.0,226.0>>

	* uni2E36 (U+2E36): L<<327.0,557.0>--<327.0,531.0>> -> L<<327.0,531.0>--<334.0,0.0>>

	* uni2E36 (U+2E36): L<<334.0,760.0>--<327.0,557.0>> -> L<<327.0,557.0>--<327.0,531.0>>

	* uni2E37 (U+2E37): L<<267.0,0.0>--<274.0,531.0>> -> L<<274.0,531.0>--<274.0,557.0>>

	* uni2E37 (U+2E37): L<<274.0,531.0>--<274.0,557.0>> -> L<<274.0,557.0>--<267.0,760.0>>

	* uniA73C (U+A73C): L<<1022.0,714.0>--<769.0,0.0>> -> L<<769.0,0.0>--<755.0,-35.0>>

	* uniA772 (U+A772): L<<306.0,35.0>--<325.0,35.0>> -> L<<325.0,35.0>--<416.0,35.0>> 

	* And uniA779 (U+A779): L<<0.0,724.0>--<303.0,724.0>> -> L<<303.0,724.0>--<303.0,724.0>> [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* Wanglicana (U+A7C2): B<<284.0,377.0>-<284.0,403.0>-<285.0,429.0>>/B<<285.0,429.0>-<265.0,343.0>-<244.5,234.5>> = 10.889294902581023

	* uni03D7 (U+03D7): B<<429.0,331.0>-<445.0,396.0>-<462.0,430.0>>/L<<462.0,430.0>--<91.0,0.0>> = 14.222268072434

	* uni03F0 (U+03F0): B<<429.0,331.0>-<445.0,396.0>-<462.0,430.0>>/L<<462.0,430.0>--<91.0,0.0>> = 14.222268072434

	* uni1D95 (U+1D95): L<<489.0,-86.0>--<489.0,189.0>>/B<<489.0,189.0>-<471.0,102.0>-<415.5,46.5>> = 11.689369175439202

	* uni210A (U+210A): B<<90.5,185.5>-<98.0,204.0>-<104.0,211.0>>/B<<104.0,211.0>-<72.0,173.0>-<33.0,145.0>> = 0.50038709879258

	* uni210B (U+210B): B<<526.5,433.0>-<566.0,504.0>-<629.0,581.0>>/B<<629.0,581.0>-<612.0,565.0>-<585.0,542.0>> = 7.4462977264280115

	* uni2133 (U+2133): B<<822.0,667.5>-<838.0,690.0>-<844.0,697.0>>/B<<844.0,697.0>-<821.0,680.0>-<789.0,648.0>> = 12.929470964943654 

	* And xi (U+03BE): B<<232.5,696.5>-<269.0,717.0>-<313.0,728.0>>/B<<313.0,728.0>-<288.0,727.0>-<263.0,726.0>> = 11.745633425287961 [code: found-jaggy-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

	* uni203D (U+203D): L<<277.0,691.0>--<274.0,316.0>>

	* uni25AE (U+25AE): L<<150.0,-287.0>--<151.0,713.0>>

	* uniA65E (U+A65E): L<<317.0,-130.0>--<321.0,645.0>>

	* uniA65E (U+A65E): L<<352.0,645.0>--<356.0,-130.0>>

	* uniA65F (U+A65F): L<<306.0,-240.0>--<307.0,455.0>> 

	* And uniA65F (U+A65F): L<<341.0,455.0>--<342.0,-240.0>> [code: found-semi-vertical]
</div></details><br></div></details><details><summary><b>[15] NotoSansMono-Light.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* 🔥 **FAIL** Missing required codepoints:

	- 0x00AF (MACRON)
 [code: missing-codepoints]
</div></details><details><summary>🔥 <b>FAIL:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* 🔥 **FAIL** License file OFL.txt exists but NameID 13 (LICENSE DESCRIPTION) value on platform 3 (WINDOWS) is not specified for that. Value was: "This Font Software is licensed under the SIL Open Font License, Version 1.1. This Font Software is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the SIL Open Font License for the specific language, permissions and limitations governing your use of this Font Software." Must be changed to "This Font Software is licensed under the SIL Open Font License, Version 1.1. This license is available with a FAQ at: https://scripts.sil.org/OFL" [code: wrong]
</div></details><details><summary>🔥 <b>FAIL:</b> OS/2.fsSelection bit 7 (USE_TYPO_METRICS) is set in all fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/os2/use_typo_metrics">com.google.fonts/check/os2/use_typo_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2.fsSelection bit 7 (USE_TYPO_METRICS) wasNOT set in the following fonts: ['fonts/NotoSansMono/googlefonts/slim-variable-ttf/NotoSansMono-MM[wght].ttf', 'fonts/NotoSansMono/googlefonts/ttf/NotoSansMono-Black.ttf', 'fonts/NotoSansMono/googlefonts/ttf/NotoSansMono-Bold.ttf', 'fonts/NotoSansMono/googlefonts/ttf/NotoSansMono-ExtraBold.ttf', 'fonts/NotoSansMono/googlefonts/ttf/NotoSansMono-ExtraLight.ttf', 'fonts/NotoSansMono/googlefonts/ttf/NotoSansMono-Light.ttf', 'fonts/NotoSansMono/googlefonts/ttf/NotoSansMono-Medium.ttf', 'fonts/NotoSansMono/googlefonts/ttf/NotoSansMono-Regular.ttf', 'fonts/NotoSansMono/googlefonts/ttf/NotoSansMono-SemiBold.ttf', 'fonts/NotoSansMono/googlefonts/ttf/NotoSansMono-Thin.ttf', 'fonts/NotoSansMono/googlefonts/variable-ttf/NotoSansMono-MM[wdth,wght].ttf']. [code: missing-os2-fsselection-bit7]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinAscent value should be equal or greater than 1239, but got 1069 instead [code: ascent]
* 🔥 **FAIL** OS/2.usWinDescent value should be equal or greater than 389, but got 293 instead. [code: descent]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking correctness of monospaced metadata. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/name.html#com.google.fonts/check/monospace">com.google.fonts/check/monospace</a>)</summary><div>


* 🔥 **FAIL** On monospaced fonts, the value of post.isFixedPitch must be set to a non-zero value (meaning 'fixed width monospaced'), but got 0 instead. [code: mono-bad-post-isFixedPitch]
* ⚠ **WARN** Font is monospaced but 250 glyphs (6.60%) have a different width. You should check the widths of: ['oneeighth', 'threeeighths', 'fiveeighths', 'seveneighths', 'uniFFFC', 'uniFFFD', 'uni0468', 'uni046C', 'uni046D', 'uni0478', 'uni0479', 'uni01A2', 'uni01C4', 'uni01C5', 'uni01C6', 'uni01C7', 'uni01C8', 'uni01C9', 'uni01CA', 'uni01CB', 'uni01CC', 'uni01F1', 'uni01F2', 'uni01F3', 'uni02A5', 'uni02A8', 'uni1D7A', 'uni1F0A', 'uni1F0B', 'uni1F0C', 'uni1F0D', 'uni1F0E', 'uni1F0F', 'uni1F1A', 'uni1F1B', 'uni1F1C', 'uni1F1D', 'uni1F2A', 'uni1F2B', 'uni1F2C', 'uni1F2D', 'uni1F2E', 'uni1F2F', 'uni1F4A', 'uni1F4B', 'uni1F4C', 'uni1F4D', 'uni1F5B', 'uni1F5D', 'uni1F5F', 'uni1F6A', 'uni1F6B', 'uni1F6C', 'uni1F6D', 'uni1F6E', 'uni1F6F', 'uni1F88', 'uni1F89', 'uni1F8A', 'uni1F8B', 'uni1F8C', 'uni1F8D', 'uni1F8E', 'uni1F8F', 'uni1F98', 'uni1F99', 'uni1F9A', 'uni1F9B', 'uni1F9C', 'uni1F9D', 'uni1F9E', 'uni1F9F', 'uni1FA8', 'uni1FA9', 'uni1FAA', 'uni1FAB', 'uni1FAC', 'uni1FAD', 'uni1FAE', 'uni1FAF', 'uni1FBC', 'uni1FCC', 'uni1FFC', 'uni20A8', 'uni2153', 'uni2154', 'uni0518', 'uni0520', 'uni0521', 'uni0522', 'uni0523', 'uniA728', 'uniA732', 'uniA734', 'uniA736', 'uniA738', 'uniA73A', 'uniA73C', 'uniA74E', 'uniA729', 'uniA74F', 'uniA773', 'sakhayat', 'uniA7FF', 'Iotifiedacy', 'Yusiotifiedclosedlittlecy', 'Emsoftcy', 'Odoublemonocularcy', 'uniA684', 'Odoublecy', 'uni052A', 'uniA657', 'yusiotifiedclosedlittlecy', 'emsoftcy', 'odoublemonocularcy', 'odoublecy', 'uni052B', 'uni211C', 'uni212C', 'uni210B', 'uni2110', 'uni2112', 'uni211B', 'uni2131', 'uni2133', 'uni2474', 'uni2475', 'uni2189', 'uni2155', 'uni2156', 'uni2157', 'uni2158', 'uni2159', 'uni215A', 'uni2150', 'uni2151', 'uni2152', 'uni2042', 'uni2E0E', 'uni2047', 'uni203B', 'uni2053', 'uni2E3B', 'uni2E3A', 'uni2057', 'uni20B7', 'uni23DF', 'uni23DD', 'uni23E1', 'uni27D7', 'uni27D5', 'uni2A00', 'emptyset', 'uni2031', 'uni27D6', 'uni23DE', 'uni23DC', 'uni23E0', 'uni229B', 'uni229C', 'uni2298', 'uni2296', 'circlemultiply', 'uni2299', 'circleplus', 'uni29B8', 'uni229A', 'uni219C', 'uni219D', 'uni219E', 'uni21A0', 'uni21A2', 'uni21A3', 'uni21A4', 'uni21A6', 'arrowdblright', 'arrowdblleft', 'arrowdblboth', 'uni21DA', 'uni21DB', 'uni21E8', 'uni21E6', 'uni27F5', 'uni27F6', 'uni25EF', 'uni25CD', 'uni25C6', 'uni25C7', 'uni25C8', 'uni25B0', 'uni25B1', 'uni25AD', 'uni25A2', 'uni25A3', 'uni25A4', 'uni25A5', 'uni25A6', 'uni25A7', 'uni25A8', 'uni25A9', 'uni25E7', 'uni25E8', 'uni25E9', 'uni25EA', 'uni25EB', 'uni25F0', 'uni25F1', 'uni25F2', 'uni25F3', 'uni25B6', 'uni25C0', 'uni25B3', 'uni25B7', 'uni25BD', 'uni25C1', 'uni25EC', 'uni25ED', 'uni25EE', 'uni25BB', 'uni25C5', 'uni25E5', 'uni25E2', 'uni25E3', 'uni25E4', 'uni2349', 'uni2365', 'uni233E', 'uni235F', 'uni233D', 'uni235C', 'uni236B', 'uni235A', 'uni2371', 'uni2366', 'uni2367', 'uni236D', 'uni2372', 'uni235D', 'uni236C', 'uni2736', 'uni213A', 'uni2103', 'u1F67C', 'u1F67D', 'u1F67E', 'u1F67F', 'uni2109', 'uni2114', 'uni214F', 'weierstrass'] [code: mono-outliers]
</div></details><details><summary>⚠ <b>WARN:</b> Glyphs are similiar to Google Fonts version? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/production_glyphs_similarity">com.google.fonts/check/production_glyphs_similarity</a>)</summary><div>


* ⚠ **WARN** Following glyphs differ greatly from Google Fonts version:
	* uni2475
	* uni20B3
	* backslash
	* uni020F
	* uni20B6
	* uni2035
	* uni04ED
	* uni0295
	* radical.mir
	* uniA684 and 102 more.

Use -F or --full-lists to disable shortening of long lists.
</div></details><details><summary>⚠ <b>WARN:</b> Ensure Stylistic Sets have description. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/stylisticset_description">com.google.fonts/check/stylisticset_description</a>)</summary><div>


* ⚠ **WARN** The stylistic set ss03 lacks a description string on the 'name' table. [code: missing-description]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Glyph names are all valid? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/valid_glyphnames">com.google.fonts/check/valid_glyphnames</a>)</summary><div>


* ⚠ **WARN** The following glyph names may be too long for some legacy systems which may expect a maximum 31-char length limit:
kavykawithkavykaaboveinvertedlow [code: legacy-long-names]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character (codepoint 0x00AD) which is supposed to be zero-width and invisible, and is used to mark a hyphenation possibility within a word in the absence of or overriding dictionary hyphenation. It is mostly an obsolete mechanism now, and the character is only included in fonts for legacy codepage coverage. [code: softhyphen]
* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: uni00AD	Contours detected: 1	Expected: 0

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: ohorn	Contours detected: 3	Expected: 2

	- Glyph name: Uhorn	Contours detected: 2	Expected: 1

	- Glyph name: uhorn	Contours detected: 2	Expected: 1

	- Glyph name: uni01EA	Contours detected: 3	Expected: 2

	- Glyph name: uni01EB	Contours detected: 3	Expected: 2

	- Glyph name: uni01EC	Contours detected: 4	Expected: 3

	- Glyph name: uni01ED	Contours detected: 4	Expected: 3 

	- And 105 more.

Use -F or --full-lists to disable shortening of long lists.
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check mark characters are in GDEF mark glyph class. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_mark_chars">com.google.fonts/check/gdef_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following mark characters could be in the GDEF mark glyph class:
	 uni0488 (U+0488), uni0489 (U+0489), uni1ABE (U+1ABE), uniA670 (U+A670), uniA671 (U+A671) and uniA672 (U+A672) [code: mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Does GPOS table have kerning information? This check skips monospaced fonts as defined by post.isFixedPitch value (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gpos.html#com.google.fonts/check/gpos_kerning_info">com.google.fonts/check/gpos_kerning_info</a>)</summary><div>


* ⚠ **WARN** GPOS table lacks kerning information. [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* crosspattyleft (U+2E51): L<<414.0,632.0>--<402.0,361.0>> -> L<<402.0,361.0>--<414.0,88.0>>

	* crosspattyright (U+2E50): L<<186.0,88.0>--<198.0,361.0>> -> L<<198.0,361.0>--<186.0,632.0>>

	* uni2E36 (U+2E36): L<<332.0,557.0>--<332.0,521.0>> -> L<<332.0,521.0>--<344.0,0.0>>

	* uni2E36 (U+2E36): L<<344.0,760.0>--<332.0,557.0>> -> L<<332.0,557.0>--<332.0,521.0>>

	* uni2E37 (U+2E37): L<<263.0,0.0>--<274.0,521.0>> -> L<<274.0,521.0>--<274.0,557.0>>

	* uni2E37 (U+2E37): L<<274.0,521.0>--<274.0,557.0>> -> L<<274.0,557.0>--<263.0,760.0>>

	* uniA640 (U+A640): L<<105.0,0.0>--<105.0,1.0>> -> L<<105.0,1.0>--<105.0,45.0>>

	* uniA640 (U+A640): L<<170.0,50.0>--<170.0,50.0>> -> L<<170.0,50.0>--<343.0,50.0>>

	* uniA642 (U+A642): L<<105.0,0.0>--<105.0,1.0>> -> L<<105.0,1.0>--<105.0,45.0>>

	* uniA642 (U+A642): L<<170.0,50.0>--<170.0,50.0>> -> L<<170.0,50.0>--<343.0,50.0>> 

	* And 4 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* Wanglicana (U+A7C2): L<<278.0,385.0>--<278.0,387.0>>/B<<278.0,387.0>-<260.0,308.0>-<242.5,210.0>> = 12.835609486401424

	* uni1D95 (U+1D95): L<<482.0,-77.0>--<482.0,176.0>>/B<<482.0,176.0>-<462.0,92.0>-<406.5,41.5>> = 13.392497753751098

	* uni210A (U+210A): B<<90.5,185.5>-<98.0,204.0>-<104.0,211.0>>/B<<104.0,211.0>-<72.0,173.0>-<33.0,145.0>> = 0.50038709879258

	* uni210B (U+210B): B<<526.5,433.0>-<566.0,504.0>-<629.0,581.0>>/B<<629.0,581.0>-<612.0,565.0>-<585.0,542.0>> = 7.4462977264280115

	* uni2133 (U+2133): B<<822.0,667.5>-<838.0,690.0>-<844.0,697.0>>/B<<844.0,697.0>-<821.0,680.0>-<789.0,648.0>> = 12.929470964943654

	* uniA7A1 (U+A7A1): L<<454.0,281.0>--<454.0,281.0>>/L<<454.0,281.0>--<125.0,206.0>> = 12.841896284172142 

	* And xi (U+03BE): B<<227.0,684.5>-<262.0,704.0>-<304.0,715.0>>/B<<304.0,715.0>-<283.0,714.0>-<256.0,712.5>> = 11.950082143543746 [code: found-jaggy-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

	* Uogonek (U+0172): L<<518.0,714.0>--<517.0,252.0>>

	* uni1D7A (U+1D7A): L<<287.0,482.0>--<286.0,182.0>>

	* uni211F (U+211F): L<<163.0,358.0>--<283.0,357.0>>

	* uni25AE (U+25AE): L<<150.0,-287.0>--<151.0,713.0>>

	* uniA648 (U+A648): L<<81.0,0.0>--<80.0,186.0>>

	* uniA65E (U+A65E): L<<355.0,624.0>--<361.0,-130.0>>

	* uniA65F (U+A65F): L<<295.0,-240.0>--<298.0,441.0>>

	* uniA65F (U+A65F): L<<348.0,440.0>--<350.0,-240.0>>

	* uniAB3C (U+AB3C): L<<513.0,356.0>--<512.0,-47.0>> 

	* And uniAB45 (U+AB45): L<<79.0,0.0>--<78.0,126.0>> [code: found-semi-vertical]
</div></details><br></div></details><details><summary><b>[16] NotoSansMono-Medium.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* 🔥 **FAIL** Missing required codepoints:

	- 0x00AF (MACRON)
 [code: missing-codepoints]
</div></details><details><summary>🔥 <b>FAIL:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* 🔥 **FAIL** License file OFL.txt exists but NameID 13 (LICENSE DESCRIPTION) value on platform 3 (WINDOWS) is not specified for that. Value was: "This Font Software is licensed under the SIL Open Font License, Version 1.1. This Font Software is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the SIL Open Font License for the specific language, permissions and limitations governing your use of this Font Software." Must be changed to "This Font Software is licensed under the SIL Open Font License, Version 1.1. This license is available with a FAQ at: https://scripts.sil.org/OFL" [code: wrong]
</div></details><details><summary>🔥 <b>FAIL:</b> OS/2.fsSelection bit 7 (USE_TYPO_METRICS) is set in all fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/os2/use_typo_metrics">com.google.fonts/check/os2/use_typo_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2.fsSelection bit 7 (USE_TYPO_METRICS) wasNOT set in the following fonts: ['fonts/NotoSansMono/googlefonts/slim-variable-ttf/NotoSansMono-MM[wght].ttf', 'fonts/NotoSansMono/googlefonts/ttf/NotoSansMono-Black.ttf', 'fonts/NotoSansMono/googlefonts/ttf/NotoSansMono-Bold.ttf', 'fonts/NotoSansMono/googlefonts/ttf/NotoSansMono-ExtraBold.ttf', 'fonts/NotoSansMono/googlefonts/ttf/NotoSansMono-ExtraLight.ttf', 'fonts/NotoSansMono/googlefonts/ttf/NotoSansMono-Light.ttf', 'fonts/NotoSansMono/googlefonts/ttf/NotoSansMono-Medium.ttf', 'fonts/NotoSansMono/googlefonts/ttf/NotoSansMono-Regular.ttf', 'fonts/NotoSansMono/googlefonts/ttf/NotoSansMono-SemiBold.ttf', 'fonts/NotoSansMono/googlefonts/ttf/NotoSansMono-Thin.ttf', 'fonts/NotoSansMono/googlefonts/variable-ttf/NotoSansMono-MM[wdth,wght].ttf']. [code: missing-os2-fsselection-bit7]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinAscent value should be equal or greater than 1239, but got 1069 instead [code: ascent]
* 🔥 **FAIL** OS/2.usWinDescent value should be equal or greater than 389, but got 293 instead. [code: descent]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking correctness of monospaced metadata. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/name.html#com.google.fonts/check/monospace">com.google.fonts/check/monospace</a>)</summary><div>


* 🔥 **FAIL** On monospaced fonts, the value of post.isFixedPitch must be set to a non-zero value (meaning 'fixed width monospaced'), but got 0 instead. [code: mono-bad-post-isFixedPitch]
* ⚠ **WARN** Font is monospaced but 250 glyphs (6.60%) have a different width. You should check the widths of: ['oneeighth', 'threeeighths', 'fiveeighths', 'seveneighths', 'uniFFFC', 'uniFFFD', 'uni0468', 'uni046C', 'uni046D', 'uni0478', 'uni0479', 'uni01A2', 'uni01C4', 'uni01C5', 'uni01C6', 'uni01C7', 'uni01C8', 'uni01C9', 'uni01CA', 'uni01CB', 'uni01CC', 'uni01F1', 'uni01F2', 'uni01F3', 'uni02A5', 'uni02A8', 'uni1D7A', 'uni1F0A', 'uni1F0B', 'uni1F0C', 'uni1F0D', 'uni1F0E', 'uni1F0F', 'uni1F1A', 'uni1F1B', 'uni1F1C', 'uni1F1D', 'uni1F2A', 'uni1F2B', 'uni1F2C', 'uni1F2D', 'uni1F2E', 'uni1F2F', 'uni1F4A', 'uni1F4B', 'uni1F4C', 'uni1F4D', 'uni1F5B', 'uni1F5D', 'uni1F5F', 'uni1F6A', 'uni1F6B', 'uni1F6C', 'uni1F6D', 'uni1F6E', 'uni1F6F', 'uni1F88', 'uni1F89', 'uni1F8A', 'uni1F8B', 'uni1F8C', 'uni1F8D', 'uni1F8E', 'uni1F8F', 'uni1F98', 'uni1F99', 'uni1F9A', 'uni1F9B', 'uni1F9C', 'uni1F9D', 'uni1F9E', 'uni1F9F', 'uni1FA8', 'uni1FA9', 'uni1FAA', 'uni1FAB', 'uni1FAC', 'uni1FAD', 'uni1FAE', 'uni1FAF', 'uni1FBC', 'uni1FCC', 'uni1FFC', 'uni20A8', 'uni2153', 'uni2154', 'uni0518', 'uni0520', 'uni0521', 'uni0522', 'uni0523', 'uniA728', 'uniA732', 'uniA734', 'uniA736', 'uniA738', 'uniA73A', 'uniA73C', 'uniA74E', 'uniA729', 'uniA74F', 'uniA773', 'sakhayat', 'uniA7FF', 'Iotifiedacy', 'Yusiotifiedclosedlittlecy', 'Emsoftcy', 'Odoublemonocularcy', 'uniA684', 'Odoublecy', 'uni052A', 'uniA657', 'yusiotifiedclosedlittlecy', 'emsoftcy', 'odoublemonocularcy', 'odoublecy', 'uni052B', 'uni211C', 'uni212C', 'uni210B', 'uni2110', 'uni2112', 'uni211B', 'uni2131', 'uni2133', 'uni2474', 'uni2475', 'uni2189', 'uni2155', 'uni2156', 'uni2157', 'uni2158', 'uni2159', 'uni215A', 'uni2150', 'uni2151', 'uni2152', 'uni2042', 'uni2E0E', 'uni2047', 'uni203B', 'uni2053', 'uni2E3B', 'uni2E3A', 'uni2057', 'uni20B7', 'uni23DF', 'uni23DD', 'uni23E1', 'uni27D7', 'uni27D5', 'uni2A00', 'emptyset', 'uni2031', 'uni27D6', 'uni23DE', 'uni23DC', 'uni23E0', 'uni229B', 'uni229C', 'uni2298', 'uni2296', 'circlemultiply', 'uni2299', 'circleplus', 'uni29B8', 'uni229A', 'uni219C', 'uni219D', 'uni219E', 'uni21A0', 'uni21A2', 'uni21A3', 'uni21A4', 'uni21A6', 'arrowdblright', 'arrowdblleft', 'arrowdblboth', 'uni21DA', 'uni21DB', 'uni21E8', 'uni21E6', 'uni27F5', 'uni27F6', 'uni25EF', 'uni25CD', 'uni25C6', 'uni25C7', 'uni25C8', 'uni25B0', 'uni25B1', 'uni25AD', 'uni25A2', 'uni25A3', 'uni25A4', 'uni25A5', 'uni25A6', 'uni25A7', 'uni25A8', 'uni25A9', 'uni25E7', 'uni25E8', 'uni25E9', 'uni25EA', 'uni25EB', 'uni25F0', 'uni25F1', 'uni25F2', 'uni25F3', 'uni25B6', 'uni25C0', 'uni25B3', 'uni25B7', 'uni25BD', 'uni25C1', 'uni25EC', 'uni25ED', 'uni25EE', 'uni25BB', 'uni25C5', 'uni25E5', 'uni25E2', 'uni25E3', 'uni25E4', 'uni2349', 'uni2365', 'uni233E', 'uni235F', 'uni233D', 'uni235C', 'uni236B', 'uni235A', 'uni2371', 'uni2366', 'uni2367', 'uni236D', 'uni2372', 'uni235D', 'uni236C', 'uni2736', 'uni213A', 'uni2103', 'u1F67C', 'u1F67D', 'u1F67E', 'u1F67F', 'uni2109', 'uni2114', 'uni214F', 'weierstrass'] [code: mono-outliers]
</div></details><details><summary>⚠ <b>WARN:</b> Glyphs are similiar to Google Fonts version? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/production_glyphs_similarity">com.google.fonts/check/production_glyphs_similarity</a>)</summary><div>


* ⚠ **WARN** Following glyphs differ greatly from Google Fonts version:
	* uni0224
	* uniA643
	* uniA773
	* uni20BF
	* uni023B
	* uni20BB
	* uni019E
	* uniA7A9
	* uni1FC3
	* uni2249.mir and 334 more.

Use -F or --full-lists to disable shortening of long lists.
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Noto Sans Mono Medium' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/googlefonts/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure Stylistic Sets have description. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/stylisticset_description">com.google.fonts/check/stylisticset_description</a>)</summary><div>


* ⚠ **WARN** The stylistic set ss03 lacks a description string on the 'name' table. [code: missing-description]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Glyph names are all valid? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/valid_glyphnames">com.google.fonts/check/valid_glyphnames</a>)</summary><div>


* ⚠ **WARN** The following glyph names may be too long for some legacy systems which may expect a maximum 31-char length limit:
kavykawithkavykaaboveinvertedlow [code: legacy-long-names]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character (codepoint 0x00AD) which is supposed to be zero-width and invisible, and is used to mark a hyphenation possibility within a word in the absence of or overriding dictionary hyphenation. It is mostly an obsolete mechanism now, and the character is only included in fonts for legacy codepage coverage. [code: softhyphen]
* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: uni00AD	Contours detected: 1	Expected: 0

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: ohorn	Contours detected: 3	Expected: 2

	- Glyph name: Uhorn	Contours detected: 2	Expected: 1

	- Glyph name: uhorn	Contours detected: 2	Expected: 1

	- Glyph name: uni01EA	Contours detected: 3	Expected: 2

	- Glyph name: uni01EB	Contours detected: 3	Expected: 2

	- Glyph name: uni01EC	Contours detected: 4	Expected: 3

	- Glyph name: uni01ED	Contours detected: 4	Expected: 3 

	- And 101 more.

Use -F or --full-lists to disable shortening of long lists.
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check mark characters are in GDEF mark glyph class. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_mark_chars">com.google.fonts/check/gdef_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following mark characters could be in the GDEF mark glyph class:
	 uni0488 (U+0488), uni0489 (U+0489), uni1ABE (U+1ABE), uniA670 (U+A670), uniA671 (U+A671) and uniA672 (U+A672) [code: mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Does GPOS table have kerning information? This check skips monospaced fonts as defined by post.isFixedPitch value (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gpos.html#com.google.fonts/check/gpos_kerning_info">com.google.fonts/check/gpos_kerning_info</a>)</summary><div>


* ⚠ **WARN** GPOS table lacks kerning information. [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* uni2E36 (U+2E36): L<<342.0,556.0>--<342.0,493.0>> -> L<<342.0,493.0>--<363.0,0.0>>

	* uni2E37 (U+2E37): L<<246.0,0.0>--<268.0,493.0>> -> L<<268.0,493.0>--<268.0,556.0>>

	* uniA73C (U+A73C): L<<1047.0,714.0>--<811.0,0.0>> -> L<<811.0,0.0>--<796.0,-42.0>>

	* uniA779 (U+A779): L<<0.0,726.0>--<300.0,726.0>> -> L<<300.0,726.0>--<300.0,726.0>> 

	* And uniA779 (U+A779): L<<300.0,726.0>--<300.0,726.0>> -> L<<300.0,726.0>--<300.0,726.0>> [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* Wanglicana (U+A7C2): B<<161.0,186.5>-<165.0,144.0>-<167.0,109.0>>/B<<167.0,109.0>-<191.0,267.0>-<216.5,378.0>> = 11.907619338254307

	* Wanglicana (U+A7C2): B<<318.0,30.0>-<272.0,168.0>-<263.0,324.0>>/B<<263.0,324.0>-<251.0,257.0>-<239.0,176.5>> = 13.456132254635271

	* uni20A9 (U+20A9): L<<146.0,329.0>--<169.0,120.0>>/L<<169.0,120.0>--<197.0,329.0>> = 13.910561351082569

	* uni20A9 (U+20A9): L<<408.0,329.0>--<436.0,117.0>>/L<<436.0,117.0>--<459.0,329.0>> = 13.715654723480688

	* uni210A (U+210A): B<<90.5,185.5>-<98.0,204.0>-<104.0,211.0>>/B<<104.0,211.0>-<72.0,173.0>-<33.0,145.0>> = 0.50038709879258

	* uni210B (U+210B): B<<526.5,433.0>-<566.0,504.0>-<629.0,581.0>>/B<<629.0,581.0>-<612.0,565.0>-<585.0,542.0>> = 7.4462977264280115

	* uni2133 (U+2133): B<<822.0,667.5>-<838.0,690.0>-<844.0,697.0>>/B<<844.0,697.0>-<821.0,680.0>-<789.0,648.0>> = 12.929470964943654

	* uni2137 (U+2137): L<<383.0,0.0>--<343.0,178.0>>/B<<343.0,178.0>-<343.0,140.0>-<324.5,111.5>> = 12.665063765042364

	* uni213B (U+213B): B<<286.5,621.5>-<283.0,648.0>-<281.0,664.0>>/B<<281.0,664.0>-<279.0,648.0>-<275.5,621.5>> = 14.25003269780357 

	* And xi (U+03BE): B<<182.0,632.5>-<222.0,666.0>-<283.0,684.0>>/B<<283.0,684.0>-<266.0,682.0>-<234.5,680.0>> = 9.730542713923196 [code: found-jaggy-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

	* element (U+2208): L<<375.0,146.0>--<549.0,145.0>>

	* notelement (U+2209): L<<375.0,146.0>--<549.0,145.0>>

	* suchthat (U+220B): L<<51.0,145.0>--<224.0,146.0>>

	* uni0469 (U+0469): L<<348.0,0.0>--<349.0,230.0>>

	* uni0469 (U+0469): L<<424.0,230.0>--<426.0,0.0>>

	* uni220C (U+220C): L<<51.0,145.0>--<224.0,146.0>>

	* uni25AE (U+25AE): L<<148.0,-284.0>--<149.0,713.0>> 

	* And uni27D7 (U+27D7): L<<77.0,658.0>--<287.0,659.0>> [code: found-semi-vertical]
</div></details><br></div></details><details><summary><b>[15] NotoSansMono-Regular.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* 🔥 **FAIL** Missing required codepoints:

	- 0x00AF (MACRON)
 [code: missing-codepoints]
</div></details><details><summary>🔥 <b>FAIL:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* 🔥 **FAIL** License file OFL.txt exists but NameID 13 (LICENSE DESCRIPTION) value on platform 3 (WINDOWS) is not specified for that. Value was: "This Font Software is licensed under the SIL Open Font License, Version 1.1. This Font Software is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the SIL Open Font License for the specific language, permissions and limitations governing your use of this Font Software." Must be changed to "This Font Software is licensed under the SIL Open Font License, Version 1.1. This license is available with a FAQ at: https://scripts.sil.org/OFL" [code: wrong]
</div></details><details><summary>🔥 <b>FAIL:</b> OS/2.fsSelection bit 7 (USE_TYPO_METRICS) is set in all fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/os2/use_typo_metrics">com.google.fonts/check/os2/use_typo_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2.fsSelection bit 7 (USE_TYPO_METRICS) wasNOT set in the following fonts: ['fonts/NotoSansMono/googlefonts/slim-variable-ttf/NotoSansMono-MM[wght].ttf', 'fonts/NotoSansMono/googlefonts/ttf/NotoSansMono-Black.ttf', 'fonts/NotoSansMono/googlefonts/ttf/NotoSansMono-Bold.ttf', 'fonts/NotoSansMono/googlefonts/ttf/NotoSansMono-ExtraBold.ttf', 'fonts/NotoSansMono/googlefonts/ttf/NotoSansMono-ExtraLight.ttf', 'fonts/NotoSansMono/googlefonts/ttf/NotoSansMono-Light.ttf', 'fonts/NotoSansMono/googlefonts/ttf/NotoSansMono-Medium.ttf', 'fonts/NotoSansMono/googlefonts/ttf/NotoSansMono-Regular.ttf', 'fonts/NotoSansMono/googlefonts/ttf/NotoSansMono-SemiBold.ttf', 'fonts/NotoSansMono/googlefonts/ttf/NotoSansMono-Thin.ttf', 'fonts/NotoSansMono/googlefonts/variable-ttf/NotoSansMono-MM[wdth,wght].ttf']. [code: missing-os2-fsselection-bit7]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinAscent value should be equal or greater than 1239, but got 1069 instead [code: ascent]
* 🔥 **FAIL** OS/2.usWinDescent value should be equal or greater than 389, but got 293 instead. [code: descent]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking correctness of monospaced metadata. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/name.html#com.google.fonts/check/monospace">com.google.fonts/check/monospace</a>)</summary><div>


* 🔥 **FAIL** On monospaced fonts, the value of post.isFixedPitch must be set to a non-zero value (meaning 'fixed width monospaced'), but got 0 instead. [code: mono-bad-post-isFixedPitch]
* ⚠ **WARN** Font is monospaced but 250 glyphs (6.60%) have a different width. You should check the widths of: ['oneeighth', 'threeeighths', 'fiveeighths', 'seveneighths', 'uniFFFC', 'uniFFFD', 'uni0468', 'uni046C', 'uni046D', 'uni0478', 'uni0479', 'uni01A2', 'uni01C4', 'uni01C5', 'uni01C6', 'uni01C7', 'uni01C8', 'uni01C9', 'uni01CA', 'uni01CB', 'uni01CC', 'uni01F1', 'uni01F2', 'uni01F3', 'uni02A5', 'uni02A8', 'uni1D7A', 'uni1F0A', 'uni1F0B', 'uni1F0C', 'uni1F0D', 'uni1F0E', 'uni1F0F', 'uni1F1A', 'uni1F1B', 'uni1F1C', 'uni1F1D', 'uni1F2A', 'uni1F2B', 'uni1F2C', 'uni1F2D', 'uni1F2E', 'uni1F2F', 'uni1F4A', 'uni1F4B', 'uni1F4C', 'uni1F4D', 'uni1F5B', 'uni1F5D', 'uni1F5F', 'uni1F6A', 'uni1F6B', 'uni1F6C', 'uni1F6D', 'uni1F6E', 'uni1F6F', 'uni1F88', 'uni1F89', 'uni1F8A', 'uni1F8B', 'uni1F8C', 'uni1F8D', 'uni1F8E', 'uni1F8F', 'uni1F98', 'uni1F99', 'uni1F9A', 'uni1F9B', 'uni1F9C', 'uni1F9D', 'uni1F9E', 'uni1F9F', 'uni1FA8', 'uni1FA9', 'uni1FAA', 'uni1FAB', 'uni1FAC', 'uni1FAD', 'uni1FAE', 'uni1FAF', 'uni1FBC', 'uni1FCC', 'uni1FFC', 'uni20A8', 'uni2153', 'uni2154', 'uni0518', 'uni0520', 'uni0521', 'uni0522', 'uni0523', 'uniA728', 'uniA732', 'uniA734', 'uniA736', 'uniA738', 'uniA73A', 'uniA73C', 'uniA74E', 'uniA729', 'uniA74F', 'uniA773', 'sakhayat', 'uniA7FF', 'Iotifiedacy', 'Yusiotifiedclosedlittlecy', 'Emsoftcy', 'Odoublemonocularcy', 'uniA684', 'Odoublecy', 'uni052A', 'uniA657', 'yusiotifiedclosedlittlecy', 'emsoftcy', 'odoublemonocularcy', 'odoublecy', 'uni052B', 'uni211C', 'uni212C', 'uni210B', 'uni2110', 'uni2112', 'uni211B', 'uni2131', 'uni2133', 'uni2474', 'uni2475', 'uni2189', 'uni2155', 'uni2156', 'uni2157', 'uni2158', 'uni2159', 'uni215A', 'uni2150', 'uni2151', 'uni2152', 'uni2042', 'uni2E0E', 'uni2047', 'uni203B', 'uni2053', 'uni2E3B', 'uni2E3A', 'uni2057', 'uni20B7', 'uni23DF', 'uni23DD', 'uni23E1', 'uni27D7', 'uni27D5', 'uni2A00', 'emptyset', 'uni2031', 'uni27D6', 'uni23DE', 'uni23DC', 'uni23E0', 'uni229B', 'uni229C', 'uni2298', 'uni2296', 'circlemultiply', 'uni2299', 'circleplus', 'uni29B8', 'uni229A', 'uni219C', 'uni219D', 'uni219E', 'uni21A0', 'uni21A2', 'uni21A3', 'uni21A4', 'uni21A6', 'arrowdblright', 'arrowdblleft', 'arrowdblboth', 'uni21DA', 'uni21DB', 'uni21E8', 'uni21E6', 'uni27F5', 'uni27F6', 'uni25EF', 'uni25CD', 'uni25C6', 'uni25C7', 'uni25C8', 'uni25B0', 'uni25B1', 'uni25AD', 'uni25A2', 'uni25A3', 'uni25A4', 'uni25A5', 'uni25A6', 'uni25A7', 'uni25A8', 'uni25A9', 'uni25E7', 'uni25E8', 'uni25E9', 'uni25EA', 'uni25EB', 'uni25F0', 'uni25F1', 'uni25F2', 'uni25F3', 'uni25B6', 'uni25C0', 'uni25B3', 'uni25B7', 'uni25BD', 'uni25C1', 'uni25EC', 'uni25ED', 'uni25EE', 'uni25BB', 'uni25C5', 'uni25E5', 'uni25E2', 'uni25E3', 'uni25E4', 'uni2349', 'uni2365', 'uni233E', 'uni235F', 'uni233D', 'uni235C', 'uni236B', 'uni235A', 'uni2371', 'uni2366', 'uni2367', 'uni236D', 'uni2372', 'uni235D', 'uni236C', 'uni2736', 'uni213A', 'uni2103', 'u1F67C', 'u1F67D', 'u1F67E', 'u1F67F', 'uni2109', 'uni2114', 'uni214F', 'weierstrass'] [code: mono-outliers]
</div></details><details><summary>⚠ <b>WARN:</b> Glyphs are similiar to Google Fonts version? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/production_glyphs_similarity">com.google.fonts/check/production_glyphs_similarity</a>)</summary><div>


* ⚠ **WARN** Following glyphs differ greatly from Google Fonts version:
	* uniA643
	* uniA773
	* uni20BF
	* uni023B
	* uni20BB
	* uni019E
	* uniA7A9
	* uni1FC3
	* uni2249.mir
	* uni04EB and 242 more.

Use -F or --full-lists to disable shortening of long lists.
</div></details><details><summary>⚠ <b>WARN:</b> Ensure Stylistic Sets have description. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/stylisticset_description">com.google.fonts/check/stylisticset_description</a>)</summary><div>


* ⚠ **WARN** The stylistic set ss03 lacks a description string on the 'name' table. [code: missing-description]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Glyph names are all valid? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/valid_glyphnames">com.google.fonts/check/valid_glyphnames</a>)</summary><div>


* ⚠ **WARN** The following glyph names may be too long for some legacy systems which may expect a maximum 31-char length limit:
kavykawithkavykaaboveinvertedlow [code: legacy-long-names]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character (codepoint 0x00AD) which is supposed to be zero-width and invisible, and is used to mark a hyphenation possibility within a word in the absence of or overriding dictionary hyphenation. It is mostly an obsolete mechanism now, and the character is only included in fonts for legacy codepage coverage. [code: softhyphen]
* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: uni00AD	Contours detected: 1	Expected: 0

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: ohorn	Contours detected: 3	Expected: 2

	- Glyph name: Uhorn	Contours detected: 2	Expected: 1

	- Glyph name: uhorn	Contours detected: 2	Expected: 1

	- Glyph name: uni01EA	Contours detected: 3	Expected: 2

	- Glyph name: uni01EB	Contours detected: 3	Expected: 2

	- Glyph name: uni01EC	Contours detected: 4	Expected: 3

	- Glyph name: uni01ED	Contours detected: 4	Expected: 3 

	- And 101 more.

Use -F or --full-lists to disable shortening of long lists.
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check mark characters are in GDEF mark glyph class. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_mark_chars">com.google.fonts/check/gdef_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following mark characters could be in the GDEF mark glyph class:
	 uni0488 (U+0488), uni0489 (U+0489), uni1ABE (U+1ABE), uniA670 (U+A670), uniA671 (U+A671) and uniA672 (U+A672) [code: mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Does GPOS table have kerning information? This check skips monospaced fonts as defined by post.isFixedPitch value (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gpos.html#com.google.fonts/check/gpos_kerning_info">com.google.fonts/check/gpos_kerning_info</a>)</summary><div>


* ⚠ **WARN** GPOS table lacks kerning information. [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* uni20A6 (U+20A6): L<<163.0,403.0>--<163.0,398.0>> -> L<<163.0,398.0>--<163.0,321.0>>

	* uni2E36 (U+2E36): L<<341.0,556.0>--<341.0,503.0>> -> L<<341.0,503.0>--<360.0,0.0>>

	* uni2E36 (U+2E36): L<<360.0,760.0>--<341.0,556.0>> -> L<<341.0,556.0>--<341.0,503.0>>

	* uni2E37 (U+2E37): L<<255.0,0.0>--<274.0,503.0>> -> L<<274.0,503.0>--<274.0,556.0>>

	* uni2E37 (U+2E37): L<<274.0,503.0>--<274.0,556.0>> -> L<<274.0,556.0>--<255.0,760.0>>

	* uniA73C (U+A73C): L<<1044.0,714.0>--<798.0,0.0>> -> L<<798.0,0.0>--<783.0,-41.0>>

	* uniA772 (U+A772): L<<341.0,75.0>--<376.0,72.0>> -> L<<376.0,72.0>--<410.0,72.0>>

	* uniA779 (U+A779): L<<0.0,726.0>--<298.0,726.0>> -> L<<298.0,726.0>--<298.0,726.0>> 

	* And uniA779 (U+A779): L<<298.0,726.0>--<298.0,726.0>> -> L<<298.0,726.0>--<300.0,726.0>> [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* Wanglicana (U+A7C2): B<<163.0,173.5>-<167.0,135.0>-<170.0,100.0>>/B<<170.0,100.0>-<195.0,260.0>-<221.0,371.5>> = 13.779751604307991

	* Wanglicana (U+A7C2): B<<327.0,30.0>-<277.0,168.0>-<268.0,326.0>>/B<<268.0,326.0>-<255.0,256.0>-<242.0,174.5>> = 13.780944951749198

	* uni20A9 (U+20A9): L<<142.0,333.0>--<168.0,108.0>>/L<<168.0,108.0>--<198.0,333.0>> = 14.18625330362263

	* uni20A9 (U+20A9): L<<406.0,333.0>--<437.0,104.0>>/L<<437.0,104.0>--<463.0,333.0>> = 14.186792841975823

	* uni210A (U+210A): B<<90.5,185.5>-<98.0,204.0>-<104.0,211.0>>/B<<104.0,211.0>-<72.0,173.0>-<33.0,145.0>> = 0.50038709879258

	* uni210B (U+210B): B<<526.5,433.0>-<566.0,504.0>-<629.0,581.0>>/B<<629.0,581.0>-<612.0,565.0>-<585.0,542.0>> = 7.4462977264280115

	* uni2133 (U+2133): B<<822.0,667.5>-<838.0,690.0>-<844.0,697.0>>/B<<844.0,697.0>-<821.0,680.0>-<789.0,648.0>> = 12.929470964943654

	* uni2137 (U+2137): L<<387.0,0.0>--<347.0,180.0>>/B<<347.0,180.0>-<347.0,146.0>-<328.5,115.5>> = 12.528807709151492

	* uni213B (U+213B): B<<286.5,623.5>-<283.0,649.0>-<281.0,665.0>>/B<<281.0,665.0>-<279.0,649.0>-<275.5,623.5>> = 14.25003269780357 

	* And xi (U+03BE): B<<218.0,663.5>-<250.0,682.0>-<288.0,693.0>>/B<<288.0,693.0>-<275.0,692.0>-<243.5,689.5>> = 11.745633425287899 [code: found-jaggy-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

	* uni25AE (U+25AE): L<<150.0,-287.0>--<151.0,713.0>>

	* uni27D7 (U+27D7): L<<81.0,658.0>--<282.0,659.0>> 

	* And uniA65F (U+A65F): L<<358.0,415.0>--<362.0,-240.0>> [code: found-semi-vertical]
</div></details><br></div></details><details><summary><b>[16] NotoSansMono-SemiBold.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* 🔥 **FAIL** Missing required codepoints:

	- 0x00AF (MACRON)
 [code: missing-codepoints]
</div></details><details><summary>🔥 <b>FAIL:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* 🔥 **FAIL** License file OFL.txt exists but NameID 13 (LICENSE DESCRIPTION) value on platform 3 (WINDOWS) is not specified for that. Value was: "This Font Software is licensed under the SIL Open Font License, Version 1.1. This Font Software is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the SIL Open Font License for the specific language, permissions and limitations governing your use of this Font Software." Must be changed to "This Font Software is licensed under the SIL Open Font License, Version 1.1. This license is available with a FAQ at: https://scripts.sil.org/OFL" [code: wrong]
</div></details><details><summary>🔥 <b>FAIL:</b> OS/2.fsSelection bit 7 (USE_TYPO_METRICS) is set in all fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/os2/use_typo_metrics">com.google.fonts/check/os2/use_typo_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2.fsSelection bit 7 (USE_TYPO_METRICS) wasNOT set in the following fonts: ['fonts/NotoSansMono/googlefonts/slim-variable-ttf/NotoSansMono-MM[wght].ttf', 'fonts/NotoSansMono/googlefonts/ttf/NotoSansMono-Black.ttf', 'fonts/NotoSansMono/googlefonts/ttf/NotoSansMono-Bold.ttf', 'fonts/NotoSansMono/googlefonts/ttf/NotoSansMono-ExtraBold.ttf', 'fonts/NotoSansMono/googlefonts/ttf/NotoSansMono-ExtraLight.ttf', 'fonts/NotoSansMono/googlefonts/ttf/NotoSansMono-Light.ttf', 'fonts/NotoSansMono/googlefonts/ttf/NotoSansMono-Medium.ttf', 'fonts/NotoSansMono/googlefonts/ttf/NotoSansMono-Regular.ttf', 'fonts/NotoSansMono/googlefonts/ttf/NotoSansMono-SemiBold.ttf', 'fonts/NotoSansMono/googlefonts/ttf/NotoSansMono-Thin.ttf', 'fonts/NotoSansMono/googlefonts/variable-ttf/NotoSansMono-MM[wdth,wght].ttf']. [code: missing-os2-fsselection-bit7]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinAscent value should be equal or greater than 1239, but got 1069 instead [code: ascent]
* 🔥 **FAIL** OS/2.usWinDescent value should be equal or greater than 389, but got 293 instead. [code: descent]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking correctness of monospaced metadata. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/name.html#com.google.fonts/check/monospace">com.google.fonts/check/monospace</a>)</summary><div>


* 🔥 **FAIL** On monospaced fonts, the value of post.isFixedPitch must be set to a non-zero value (meaning 'fixed width monospaced'), but got 0 instead. [code: mono-bad-post-isFixedPitch]
* ⚠ **WARN** Font is monospaced but 250 glyphs (6.60%) have a different width. You should check the widths of: ['oneeighth', 'threeeighths', 'fiveeighths', 'seveneighths', 'uniFFFC', 'uniFFFD', 'uni0468', 'uni046C', 'uni046D', 'uni0478', 'uni0479', 'uni01A2', 'uni01C4', 'uni01C5', 'uni01C6', 'uni01C7', 'uni01C8', 'uni01C9', 'uni01CA', 'uni01CB', 'uni01CC', 'uni01F1', 'uni01F2', 'uni01F3', 'uni02A5', 'uni02A8', 'uni1D7A', 'uni1F0A', 'uni1F0B', 'uni1F0C', 'uni1F0D', 'uni1F0E', 'uni1F0F', 'uni1F1A', 'uni1F1B', 'uni1F1C', 'uni1F1D', 'uni1F2A', 'uni1F2B', 'uni1F2C', 'uni1F2D', 'uni1F2E', 'uni1F2F', 'uni1F4A', 'uni1F4B', 'uni1F4C', 'uni1F4D', 'uni1F5B', 'uni1F5D', 'uni1F5F', 'uni1F6A', 'uni1F6B', 'uni1F6C', 'uni1F6D', 'uni1F6E', 'uni1F6F', 'uni1F88', 'uni1F89', 'uni1F8A', 'uni1F8B', 'uni1F8C', 'uni1F8D', 'uni1F8E', 'uni1F8F', 'uni1F98', 'uni1F99', 'uni1F9A', 'uni1F9B', 'uni1F9C', 'uni1F9D', 'uni1F9E', 'uni1F9F', 'uni1FA8', 'uni1FA9', 'uni1FAA', 'uni1FAB', 'uni1FAC', 'uni1FAD', 'uni1FAE', 'uni1FAF', 'uni1FBC', 'uni1FCC', 'uni1FFC', 'uni20A8', 'uni2153', 'uni2154', 'uni0518', 'uni0520', 'uni0521', 'uni0522', 'uni0523', 'uniA728', 'uniA732', 'uniA734', 'uniA736', 'uniA738', 'uniA73A', 'uniA73C', 'uniA74E', 'uniA729', 'uniA74F', 'uniA773', 'sakhayat', 'uniA7FF', 'Iotifiedacy', 'Yusiotifiedclosedlittlecy', 'Emsoftcy', 'Odoublemonocularcy', 'uniA684', 'Odoublecy', 'uni052A', 'uniA657', 'yusiotifiedclosedlittlecy', 'emsoftcy', 'odoublemonocularcy', 'odoublecy', 'uni052B', 'uni211C', 'uni212C', 'uni210B', 'uni2110', 'uni2112', 'uni211B', 'uni2131', 'uni2133', 'uni2474', 'uni2475', 'uni2189', 'uni2155', 'uni2156', 'uni2157', 'uni2158', 'uni2159', 'uni215A', 'uni2150', 'uni2151', 'uni2152', 'uni2042', 'uni2E0E', 'uni2047', 'uni203B', 'uni2053', 'uni2E3B', 'uni2E3A', 'uni2057', 'uni20B7', 'uni23DF', 'uni23DD', 'uni23E1', 'uni27D7', 'uni27D5', 'uni2A00', 'emptyset', 'uni2031', 'uni27D6', 'uni23DE', 'uni23DC', 'uni23E0', 'uni229B', 'uni229C', 'uni2298', 'uni2296', 'circlemultiply', 'uni2299', 'circleplus', 'uni29B8', 'uni229A', 'uni219C', 'uni219D', 'uni219E', 'uni21A0', 'uni21A2', 'uni21A3', 'uni21A4', 'uni21A6', 'arrowdblright', 'arrowdblleft', 'arrowdblboth', 'uni21DA', 'uni21DB', 'uni21E8', 'uni21E6', 'uni27F5', 'uni27F6', 'uni25EF', 'uni25CD', 'uni25C6', 'uni25C7', 'uni25C8', 'uni25B0', 'uni25B1', 'uni25AD', 'uni25A2', 'uni25A3', 'uni25A4', 'uni25A5', 'uni25A6', 'uni25A7', 'uni25A8', 'uni25A9', 'uni25E7', 'uni25E8', 'uni25E9', 'uni25EA', 'uni25EB', 'uni25F0', 'uni25F1', 'uni25F2', 'uni25F3', 'uni25B6', 'uni25C0', 'uni25B3', 'uni25B7', 'uni25BD', 'uni25C1', 'uni25EC', 'uni25ED', 'uni25EE', 'uni25BB', 'uni25C5', 'uni25E5', 'uni25E2', 'uni25E3', 'uni25E4', 'uni2349', 'uni2365', 'uni233E', 'uni235F', 'uni233D', 'uni235C', 'uni236B', 'uni235A', 'uni2371', 'uni2366', 'uni2367', 'uni236D', 'uni2372', 'uni235D', 'uni236C', 'uni2736', 'uni213A', 'uni2103', 'u1F67C', 'u1F67D', 'u1F67E', 'u1F67F', 'uni2109', 'uni2114', 'uni214F', 'weierstrass'] [code: mono-outliers]
</div></details><details><summary>⚠ <b>WARN:</b> Glyphs are similiar to Google Fonts version? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/production_glyphs_similarity">com.google.fonts/check/production_glyphs_similarity</a>)</summary><div>


* ⚠ **WARN** Following glyphs differ greatly from Google Fonts version:
	* uni0224
	* uniA643
	* uniA773
	* uni20BF
	* uni023B
	* uni20BB
	* uni019E
	* uni04C5
	* uni04FC
	* uniA7A9 and 393 more.

Use -F or --full-lists to disable shortening of long lists.
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Noto Sans Mono SemiBold' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/googlefonts/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure Stylistic Sets have description. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/stylisticset_description">com.google.fonts/check/stylisticset_description</a>)</summary><div>


* ⚠ **WARN** The stylistic set ss03 lacks a description string on the 'name' table. [code: missing-description]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Glyph names are all valid? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/valid_glyphnames">com.google.fonts/check/valid_glyphnames</a>)</summary><div>


* ⚠ **WARN** The following glyph names may be too long for some legacy systems which may expect a maximum 31-char length limit:
kavykawithkavykaaboveinvertedlow [code: legacy-long-names]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character (codepoint 0x00AD) which is supposed to be zero-width and invisible, and is used to mark a hyphenation possibility within a word in the absence of or overriding dictionary hyphenation. It is mostly an obsolete mechanism now, and the character is only included in fonts for legacy codepage coverage. [code: softhyphen]
* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: uni00AD	Contours detected: 1	Expected: 0

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: ohorn	Contours detected: 3	Expected: 2

	- Glyph name: Uhorn	Contours detected: 2	Expected: 1

	- Glyph name: uhorn	Contours detected: 2	Expected: 1

	- Glyph name: uni01EA	Contours detected: 3	Expected: 2

	- Glyph name: uni01EB	Contours detected: 3	Expected: 2

	- Glyph name: uni01EC	Contours detected: 4	Expected: 3

	- Glyph name: uni01ED	Contours detected: 4	Expected: 3 

	- And 103 more.

Use -F or --full-lists to disable shortening of long lists.
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check mark characters are in GDEF mark glyph class. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_mark_chars">com.google.fonts/check/gdef_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following mark characters could be in the GDEF mark glyph class:
	 uni0488 (U+0488), uni0489 (U+0489), uni1ABE (U+1ABE), uniA670 (U+A670), uniA671 (U+A671) and uniA672 (U+A672) [code: mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Does GPOS table have kerning information? This check skips monospaced fonts as defined by post.isFixedPitch value (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gpos.html#com.google.fonts/check/gpos_kerning_info">com.google.fonts/check/gpos_kerning_info</a>)</summary><div>


* ⚠ **WARN** GPOS table lacks kerning information. [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* uni0181 (U+0181): L<<162.0,714.0>--<162.0,714.0>> -> L<<162.0,714.0>--<321.0,714.0>>

	* uni018A (U+018A): L<<161.0,714.0>--<161.0,714.0>> -> L<<161.0,714.0>--<310.0,714.0>>

	* uni20BF (U+20BF): L<<326.0,0.0>--<323.0,0.0>> -> L<<323.0,0.0>--<248.0,0.0>>

	* uni2E36 (U+2E36): L<<343.0,556.0>--<343.0,481.0>> -> L<<343.0,481.0>--<367.0,0.0>>

	* uni2E37 (U+2E37): L<<236.0,0.0>--<260.0,481.0>> -> L<<260.0,481.0>--<260.0,556.0>>

	* uniA640 (U+A640): L<<215.0,94.0>--<215.0,94.0>> -> L<<215.0,94.0>--<316.0,94.0>>

	* uniA642 (U+A642): L<<215.0,94.0>--<215.0,94.0>> -> L<<215.0,94.0>--<316.0,94.0>>

	* uniA73C (U+A73C): L<<1050.0,714.0>--<825.0,0.0>> -> L<<825.0,0.0>--<810.0,-43.0>> 

	* And uniA779 (U+A779): L<<0.0,726.0>--<302.0,726.0>> -> L<<302.0,726.0>--<302.0,726.0>> [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* Wanglicana (U+A7C2): B<<161.5,171.5>-<164.0,142.0>-<164.0,120.0>>/B<<164.0,120.0>-<187.0,274.0>-<211.5,385.0>> = 8.494375789808995

	* Wanglicana (U+A7C2): B<<307.0,29.0>-<266.0,168.0>-<258.0,321.0>>/B<<258.0,321.0>-<247.0,257.0>-<236.0,177.0>> = 12.745556947632808

	* uni20A9 (U+20A9): L<<151.0,325.0>--<171.0,132.0>>/L<<171.0,132.0>--<196.0,325.0>> = 13.296905770104036

	* uni20A9 (U+20A9): L<<410.0,325.0>--<434.0,131.0>>/L<<434.0,131.0>--<456.0,325.0>> = 13.522125993014349

	* uni210A (U+210A): B<<90.5,185.5>-<98.0,204.0>-<104.0,211.0>>/B<<104.0,211.0>-<72.0,173.0>-<33.0,145.0>> = 0.50038709879258

	* uni210B (U+210B): B<<526.5,433.0>-<566.0,504.0>-<629.0,581.0>>/B<<629.0,581.0>-<612.0,565.0>-<585.0,542.0>> = 7.4462977264280115

	* uni211F (U+211F): L<<210.0,278.0>--<210.0,7.0>>/L<<210.0,7.0>--<274.0,278.0>> = 13.287647833420039

	* uni2133 (U+2133): B<<822.0,667.5>-<838.0,690.0>-<844.0,697.0>>/B<<844.0,697.0>-<821.0,680.0>-<789.0,648.0>> = 12.929470964943654

	* uni2137 (U+2137): L<<378.0,0.0>--<338.0,176.0>>/B<<338.0,176.0>-<338.0,133.0>-<319.5,106.5>> = 12.80426606528674

	* uni213B (U+213B): B<<286.5,618.5>-<283.0,646.0>-<281.0,662.0>>/B<<281.0,662.0>-<279.0,646.0>-<275.0,618.5>> = 14.25003269780357 

	* And xi (U+03BE): B<<173.5,623.5>-<211.0,656.0>-<277.0,673.0>>/B<<277.0,673.0>-<256.0,671.0>-<224.5,669.0>> = 9.003703693486726 [code: found-jaggy-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

	* element (U+2208): L<<376.0,160.0>--<549.0,159.0>>

	* element (U+2208): L<<549.0,62.0>--<376.0,63.0>>

	* notelement (U+2209): L<<376.0,160.0>--<549.0,159.0>>

	* notelement (U+2209): L<<549.0,62.0>--<376.0,63.0>>

	* suchthat (U+220B): L<<223.0,63.0>--<51.0,62.0>>

	* suchthat (U+220B): L<<51.0,159.0>--<223.0,160.0>>

	* uni220A (U+220A): L<<164.0,395.0>--<527.0,394.0>>

	* uni220A (U+220A): L<<328.0,573.0>--<527.0,572.0>>

	* uni220A (U+220A): L<<527.0,133.0>--<329.0,134.0>>

	* uni220A (U+220A): L<<527.0,488.0>--<328.0,489.0>> 

	* And 17 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-semi-vertical]
</div></details><br></div></details><details><summary><b>[15] NotoSansMono-Thin.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* 🔥 **FAIL** Missing required codepoints:

	- 0x00AF (MACRON)
 [code: missing-codepoints]
</div></details><details><summary>🔥 <b>FAIL:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* 🔥 **FAIL** License file OFL.txt exists but NameID 13 (LICENSE DESCRIPTION) value on platform 3 (WINDOWS) is not specified for that. Value was: "This Font Software is licensed under the SIL Open Font License, Version 1.1. This Font Software is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the SIL Open Font License for the specific language, permissions and limitations governing your use of this Font Software." Must be changed to "This Font Software is licensed under the SIL Open Font License, Version 1.1. This license is available with a FAQ at: https://scripts.sil.org/OFL" [code: wrong]
</div></details><details><summary>🔥 <b>FAIL:</b> OS/2.fsSelection bit 7 (USE_TYPO_METRICS) is set in all fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/os2/use_typo_metrics">com.google.fonts/check/os2/use_typo_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2.fsSelection bit 7 (USE_TYPO_METRICS) wasNOT set in the following fonts: ['fonts/NotoSansMono/googlefonts/slim-variable-ttf/NotoSansMono-MM[wght].ttf', 'fonts/NotoSansMono/googlefonts/ttf/NotoSansMono-Black.ttf', 'fonts/NotoSansMono/googlefonts/ttf/NotoSansMono-Bold.ttf', 'fonts/NotoSansMono/googlefonts/ttf/NotoSansMono-ExtraBold.ttf', 'fonts/NotoSansMono/googlefonts/ttf/NotoSansMono-ExtraLight.ttf', 'fonts/NotoSansMono/googlefonts/ttf/NotoSansMono-Light.ttf', 'fonts/NotoSansMono/googlefonts/ttf/NotoSansMono-Medium.ttf', 'fonts/NotoSansMono/googlefonts/ttf/NotoSansMono-Regular.ttf', 'fonts/NotoSansMono/googlefonts/ttf/NotoSansMono-SemiBold.ttf', 'fonts/NotoSansMono/googlefonts/ttf/NotoSansMono-Thin.ttf', 'fonts/NotoSansMono/googlefonts/variable-ttf/NotoSansMono-MM[wdth,wght].ttf']. [code: missing-os2-fsselection-bit7]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinAscent value should be equal or greater than 1239, but got 1069 instead [code: ascent]
* 🔥 **FAIL** OS/2.usWinDescent value should be equal or greater than 389, but got 293 instead. [code: descent]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking correctness of monospaced metadata. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/name.html#com.google.fonts/check/monospace">com.google.fonts/check/monospace</a>)</summary><div>


* 🔥 **FAIL** On monospaced fonts, the value of post.isFixedPitch must be set to a non-zero value (meaning 'fixed width monospaced'), but got 0 instead. [code: mono-bad-post-isFixedPitch]
* ⚠ **WARN** Font is monospaced but 248 glyphs (6.55%) have a different width. You should check the widths of: ['oneeighth', 'threeeighths', 'fiveeighths', 'seveneighths', 'uniFFFC', 'uniFFFD', 'uni0468', 'uni046C', 'uni046D', 'uni0478', 'uni0479', 'uni01A2', 'uni01C4', 'uni01C5', 'uni01C6', 'uni01C7', 'uni01C8', 'uni01C9', 'uni01CA', 'uni01CB', 'uni01CC', 'uni01F1', 'uni01F2', 'uni01F3', 'uni02A5', 'uni02A8', 'uni1D7A', 'uni1F0A', 'uni1F0B', 'uni1F0C', 'uni1F0D', 'uni1F0E', 'uni1F0F', 'uni1F1A', 'uni1F1B', 'uni1F1C', 'uni1F1D', 'uni1F2A', 'uni1F2B', 'uni1F2C', 'uni1F2D', 'uni1F2E', 'uni1F2F', 'uni1F4A', 'uni1F4B', 'uni1F4C', 'uni1F4D', 'uni1F5B', 'uni1F5D', 'uni1F5F', 'uni1F6A', 'uni1F6B', 'uni1F6C', 'uni1F6D', 'uni1F6E', 'uni1F6F', 'uni1F88', 'uni1F89', 'uni1F8A', 'uni1F8B', 'uni1F8C', 'uni1F8D', 'uni1F8E', 'uni1F8F', 'uni1F98', 'uni1F99', 'uni1F9A', 'uni1F9B', 'uni1F9C', 'uni1F9D', 'uni1F9E', 'uni1F9F', 'uni1FA8', 'uni1FA9', 'uni1FAA', 'uni1FAB', 'uni1FAC', 'uni1FAD', 'uni1FAE', 'uni1FAF', 'uni1FBC', 'uni1FCC', 'uni1FFC', 'uni20A8', 'uni2153', 'uni2154', 'uni0518', 'uni0520', 'uni0521', 'uni0522', 'uni0523', 'uniA728', 'uniA732', 'uniA734', 'uniA736', 'uniA738', 'uniA73A', 'uniA73C', 'uniA74E', 'uniA729', 'uniA74F', 'uniA773', 'sakhayat', 'uniA7FF', 'Iotifiedacy', 'Yusiotifiedclosedlittlecy', 'Emsoftcy', 'Odoublemonocularcy', 'uniA684', 'Odoublecy', 'uni052A', 'uniA657', 'yusiotifiedclosedlittlecy', 'emsoftcy', 'odoublemonocularcy', 'odoublecy', 'uni052B', 'uni211C', 'uni212C', 'uni210B', 'uni2110', 'uni2112', 'uni211B', 'uni2131', 'uni2133', 'uni2474', 'uni2475', 'uni2189', 'uni2155', 'uni2156', 'uni2157', 'uni2158', 'uni2159', 'uni215A', 'uni2150', 'uni2151', 'uni2152', 'uni2042', 'uni2E0E', 'uni2047', 'uni203B', 'uni2053', 'uni2E3B', 'uni2E3A', 'uni2057', 'uni20B7', 'uni23DF', 'uni23DD', 'uni23E1', 'uni27D7', 'uni27D5', 'uni2A00', 'emptyset', 'uni2031', 'uni27D6', 'uni23DE', 'uni23DC', 'uni23E0', 'uni229B', 'uni229C', 'uni2298', 'uni2296', 'circlemultiply', 'uni2299', 'circleplus', 'uni29B8', 'uni229A', 'uni219C', 'uni219D', 'uni219E', 'uni21A0', 'uni21A2', 'uni21A3', 'uni21A4', 'uni21A6', 'arrowdblright', 'arrowdblleft', 'arrowdblboth', 'uni21DA', 'uni21DB', 'uni21E8', 'uni21E6', 'uni25EF', 'uni25CD', 'uni25C6', 'uni25C7', 'uni25C8', 'uni25B0', 'uni25B1', 'uni25AD', 'uni25A2', 'uni25A3', 'uni25A4', 'uni25A5', 'uni25A6', 'uni25A7', 'uni25A8', 'uni25A9', 'uni25E7', 'uni25E8', 'uni25E9', 'uni25EA', 'uni25EB', 'uni25F0', 'uni25F1', 'uni25F2', 'uni25F3', 'uni25B6', 'uni25C0', 'uni25B3', 'uni25B7', 'uni25BD', 'uni25C1', 'uni25EC', 'uni25ED', 'uni25EE', 'uni25BB', 'uni25C5', 'uni25E5', 'uni25E2', 'uni25E3', 'uni25E4', 'uni2349', 'uni2365', 'uni233E', 'uni235F', 'uni233D', 'uni235C', 'uni236B', 'uni235A', 'uni2371', 'uni2366', 'uni2367', 'uni236D', 'uni2372', 'uni235D', 'uni236C', 'uni2736', 'uni213A', 'uni2103', 'u1F67C', 'u1F67D', 'u1F67E', 'u1F67F', 'uni2109', 'uni2114', 'uni214F', 'weierstrass'] [code: mono-outliers]
</div></details><details><summary>⚠ <b>WARN:</b> Glyphs are similiar to Google Fonts version? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/production_glyphs_similarity">com.google.fonts/check/production_glyphs_similarity</a>)</summary><div>


* ⚠ **WARN** Following glyphs differ greatly from Google Fonts version:
	* uni2475
	* backslash
	* uni020F
	* uni2035
	* uni04ED
	* uni0295
	* radical.mir
	* uni020A
	* uni0207
	* uni2037 and 66 more.

Use -F or --full-lists to disable shortening of long lists.
</div></details><details><summary>⚠ <b>WARN:</b> Ensure Stylistic Sets have description. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/stylisticset_description">com.google.fonts/check/stylisticset_description</a>)</summary><div>


* ⚠ **WARN** The stylistic set ss03 lacks a description string on the 'name' table. [code: missing-description]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Glyph names are all valid? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/valid_glyphnames">com.google.fonts/check/valid_glyphnames</a>)</summary><div>


* ⚠ **WARN** The following glyph names may be too long for some legacy systems which may expect a maximum 31-char length limit:
kavykawithkavykaaboveinvertedlow [code: legacy-long-names]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character (codepoint 0x00AD) which is supposed to be zero-width and invisible, and is used to mark a hyphenation possibility within a word in the absence of or overriding dictionary hyphenation. It is mostly an obsolete mechanism now, and the character is only included in fonts for legacy codepage coverage. [code: softhyphen]
* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: uni00AD	Contours detected: 1	Expected: 0

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: ohorn	Contours detected: 3	Expected: 2

	- Glyph name: Uhorn	Contours detected: 2	Expected: 1

	- Glyph name: uhorn	Contours detected: 2	Expected: 1

	- Glyph name: uni01EA	Contours detected: 3	Expected: 2

	- Glyph name: uni01EB	Contours detected: 3	Expected: 2

	- Glyph name: uni01EC	Contours detected: 4	Expected: 3

	- Glyph name: uni01ED	Contours detected: 4	Expected: 3 

	- And 105 more.

Use -F or --full-lists to disable shortening of long lists.
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check mark characters are in GDEF mark glyph class. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_mark_chars">com.google.fonts/check/gdef_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following mark characters could be in the GDEF mark glyph class:
	 uni0488 (U+0488), uni0489 (U+0489), uni1ABE (U+1ABE), uniA670 (U+A670), uniA671 (U+A671) and uniA672 (U+A672) [code: mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Does GPOS table have kerning information? This check skips monospaced fonts as defined by post.isFixedPitch value (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gpos.html#com.google.fonts/check/gpos_kerning_info">com.google.fonts/check/gpos_kerning_info</a>)</summary><div>


* ⚠ **WARN** GPOS table lacks kerning information. [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* crosspattyleft (U+2E51): L<<402.0,632.0>--<395.0,361.0>> -> L<<395.0,361.0>--<402.0,88.0>>

	* crosspattyright (U+2E50): L<<198.0,88.0>--<205.0,361.0>> -> L<<205.0,361.0>--<198.0,632.0>>

	* daggerdbl (U+2021): L<<290.0,222.0>--<288.0,383.0>> -> L<<288.0,383.0>--<290.0,538.0>>

	* daggerdbl (U+2021): L<<309.0,538.0>--<311.0,383.0>> -> L<<311.0,383.0>--<309.0,222.0>>

	* pi (U+03C0): L<<47.0,523.0>--<133.0,528.0>> -> L<<133.0,528.0>--<553.0,528.0>>

	* tau (U+03C4): L<<109.0,524.0>--<182.0,528.0>> -> L<<182.0,528.0>--<490.0,528.0>>

	* uni03D6 (U+03D6): L<<47.0,523.0>--<133.0,528.0>> -> L<<133.0,528.0>--<553.0,528.0>>

	* uni1D84 (U+1D84): L<<167.0,201.0>--<235.0,269.0>> -> L<<235.0,269.0>--<491.0,528.0>>

	* uni2C6A (U+2C6A): L<<167.0,201.0>--<235.0,269.0>> -> L<<235.0,269.0>--<491.0,528.0>>

	* uni2E36 (U+2E36): L<<323.0,557.0>--<323.0,538.0>> -> L<<323.0,538.0>--<327.0,0.0>> 

	* And 9 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* Wanglicana (U+A7C2): B<<289.0,372.0>-<289.0,416.0>-<291.0,459.0>>/B<<291.0,459.0>-<268.0,370.0>-<245.5,253.5>> = 11.826761827817293

	* ae (U+00E6): B<<265.5,502.5>-<299.0,468.0>-<304.0,395.0>>/B<<304.0,395.0>-<315.0,460.0>-<348.0,499.0>> = 13.523453019080295

	* aeacute (U+01FD): B<<265.5,502.5>-<299.0,468.0>-<304.0,395.0>>/B<<304.0,395.0>-<315.0,460.0>-<348.0,499.0>> = 13.523453019080295

	* aeturned (U+1D02): B<<334.5,25.5>-<301.0,60.0>-<296.0,133.0>>/B<<296.0,133.0>-<285.0,68.0>-<252.0,29.0>> = 13.523453019080295

	* uni01E3 (U+01E3): B<<265.5,502.5>-<299.0,468.0>-<304.0,395.0>>/B<<304.0,395.0>-<315.0,460.0>-<348.0,499.0>> = 13.523453019080295

	* uni03D7 (U+03D7): B<<437.5,344.0>-<456.0,415.0>-<475.0,451.0>>/L<<475.0,451.0>--<81.0,0.0>> = 13.316827393040278

	* uni03F0 (U+03F0): B<<437.5,344.0>-<456.0,415.0>-<475.0,451.0>>/L<<475.0,451.0>--<81.0,0.0>> = 13.316827393040278

	* uni04D5 (U+04D5): B<<265.5,502.5>-<299.0,468.0>-<304.0,395.0>>/B<<304.0,395.0>-<315.0,460.0>-<348.0,499.0>> = 13.523453019080295

	* uni1D95 (U+1D95): L<<493.0,-92.0>--<493.0,200.0>>/B<<493.0,200.0>-<483.0,140.0>-<455.0,93.0>> = 9.462322208025613

	* uni20B9 (U+20B9): L<<541.0,689.0>--<314.0,689.0>>/B<<314.0,689.0>-<361.0,677.0>-<391.0,636.5>> = 14.32271997820355 

	* And 4 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-jaggy-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

	* dagger (U+2020): L<<286.0,0.0>--<290.0,538.0>>

	* dagger (U+2020): L<<309.0,538.0>--<313.0,0.0>>

	* exclam (U+0021): L<<288.0,174.0>--<286.0,714.0>>

	* exclam (U+0021): L<<315.0,714.0>--<313.0,174.0>>

	* exclamdbl (U+203C): L<<158.0,174.0>--<156.0,714.0>>

	* exclamdbl (U+203C): L<<185.0,714.0>--<183.0,174.0>>

	* exclamdbl (U+203C): L<<418.0,174.0>--<416.0,714.0>>

	* exclamdbl (U+203C): L<<445.0,714.0>--<443.0,174.0>>

	* exclamdown (U+00A1): L<<285.0,-185.0>--<287.0,355.0>>

	* exclamdown (U+00A1): L<<312.0,355.0>--<314.0,-185.0>> 

	* And 37 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-semi-vertical]
</div></details><br></div></details><details><summary><b>[13] NotoSansMono-MM[wdth,wght].ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Checking file is named canonically. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/canonical_filename">com.google.fonts/check/canonical_filename</a>)</summary><div>


* 🔥 **FAIL** The file 'NotoSansMono-MM[wdth,wght].ttf' must be renamed to 'NotoSansMono[wdth,wght].ttf' according to the Google Fonts naming policy for variable fonts. [code: bad-varfont-filename]
</div></details><details><summary>🔥 <b>FAIL:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* 🔥 **FAIL** Missing required codepoints:

	- 0x00AF (MACRON)
 [code: missing-codepoints]
</div></details><details><summary>🔥 <b>FAIL:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* 🔥 **FAIL** License file OFL.txt exists but NameID 13 (LICENSE DESCRIPTION) value on platform 3 (WINDOWS) is not specified for that. Value was: "This Font Software is licensed under the SIL Open Font License, Version 1.1. This Font Software is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the SIL Open Font License for the specific language, permissions and limitations governing your use of this Font Software." Must be changed to "This Font Software is licensed under the SIL Open Font License, Version 1.1. This license is available with a FAQ at: https://scripts.sil.org/OFL" [code: wrong]
</div></details><details><summary>🔥 <b>FAIL:</b> OS/2.fsSelection bit 7 (USE_TYPO_METRICS) is set in all fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/os2/use_typo_metrics">com.google.fonts/check/os2/use_typo_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2.fsSelection bit 7 (USE_TYPO_METRICS) wasNOT set in the following fonts: ['fonts/NotoSansMono/googlefonts/slim-variable-ttf/NotoSansMono-MM[wght].ttf', 'fonts/NotoSansMono/googlefonts/ttf/NotoSansMono-Black.ttf', 'fonts/NotoSansMono/googlefonts/ttf/NotoSansMono-Bold.ttf', 'fonts/NotoSansMono/googlefonts/ttf/NotoSansMono-ExtraBold.ttf', 'fonts/NotoSansMono/googlefonts/ttf/NotoSansMono-ExtraLight.ttf', 'fonts/NotoSansMono/googlefonts/ttf/NotoSansMono-Light.ttf', 'fonts/NotoSansMono/googlefonts/ttf/NotoSansMono-Medium.ttf', 'fonts/NotoSansMono/googlefonts/ttf/NotoSansMono-Regular.ttf', 'fonts/NotoSansMono/googlefonts/ttf/NotoSansMono-SemiBold.ttf', 'fonts/NotoSansMono/googlefonts/ttf/NotoSansMono-Thin.ttf', 'fonts/NotoSansMono/googlefonts/variable-ttf/NotoSansMono-MM[wdth,wght].ttf']. [code: missing-os2-fsselection-bit7]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinAscent value should be equal or greater than 1239, but got 1069 instead [code: ascent]
* 🔥 **FAIL** OS/2.usWinDescent value should be equal or greater than 389, but got 293 instead. [code: descent]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking correctness of monospaced metadata. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/name.html#com.google.fonts/check/monospace">com.google.fonts/check/monospace</a>)</summary><div>


* 🔥 **FAIL** On monospaced fonts, the value of post.isFixedPitch must be set to a non-zero value (meaning 'fixed width monospaced'), but got 0 instead. [code: mono-bad-post-isFixedPitch]
* ⚠ **WARN** Font is monospaced but 250 glyphs (6.60%) have a different width. You should check the widths of: ['oneeighth', 'threeeighths', 'fiveeighths', 'seveneighths', 'uniFFFC', 'uniFFFD', 'uni0468', 'uni046C', 'uni046D', 'uni0478', 'uni0479', 'uni01A2', 'uni01C4', 'uni01C5', 'uni01C6', 'uni01C7', 'uni01C8', 'uni01C9', 'uni01CA', 'uni01CB', 'uni01CC', 'uni01F1', 'uni01F2', 'uni01F3', 'uni02A5', 'uni02A8', 'uni1D7A', 'uni1F0A', 'uni1F0B', 'uni1F0C', 'uni1F0D', 'uni1F0E', 'uni1F0F', 'uni1F1A', 'uni1F1B', 'uni1F1C', 'uni1F1D', 'uni1F2A', 'uni1F2B', 'uni1F2C', 'uni1F2D', 'uni1F2E', 'uni1F2F', 'uni1F4A', 'uni1F4B', 'uni1F4C', 'uni1F4D', 'uni1F5B', 'uni1F5D', 'uni1F5F', 'uni1F6A', 'uni1F6B', 'uni1F6C', 'uni1F6D', 'uni1F6E', 'uni1F6F', 'uni1F88', 'uni1F89', 'uni1F8A', 'uni1F8B', 'uni1F8C', 'uni1F8D', 'uni1F8E', 'uni1F8F', 'uni1F98', 'uni1F99', 'uni1F9A', 'uni1F9B', 'uni1F9C', 'uni1F9D', 'uni1F9E', 'uni1F9F', 'uni1FA8', 'uni1FA9', 'uni1FAA', 'uni1FAB', 'uni1FAC', 'uni1FAD', 'uni1FAE', 'uni1FAF', 'uni1FBC', 'uni1FCC', 'uni1FFC', 'uni20A8', 'uni2153', 'uni2154', 'uni0518', 'uni0520', 'uni0521', 'uni0522', 'uni0523', 'uniA728', 'uniA732', 'uniA734', 'uniA736', 'uniA738', 'uniA73A', 'uniA73C', 'uniA74E', 'uniA729', 'uniA74F', 'uniA773', 'sakhayat', 'uniA7FF', 'Iotifiedacy', 'Yusiotifiedclosedlittlecy', 'Emsoftcy', 'Odoublemonocularcy', 'uniA684', 'Odoublecy', 'uni052A', 'uniA657', 'yusiotifiedclosedlittlecy', 'emsoftcy', 'odoublemonocularcy', 'odoublecy', 'uni052B', 'uni211C', 'uni212C', 'uni210B', 'uni2110', 'uni2112', 'uni211B', 'uni2131', 'uni2133', 'uni2474', 'uni2475', 'uni2189', 'uni2155', 'uni2156', 'uni2157', 'uni2158', 'uni2159', 'uni215A', 'uni2150', 'uni2151', 'uni2152', 'uni2042', 'uni2E0E', 'uni2047', 'uni203B', 'uni2053', 'uni2E3B', 'uni2E3A', 'uni2057', 'uni20B7', 'uni23DF', 'uni23DD', 'uni23E1', 'uni27D7', 'uni27D5', 'uni2A00', 'emptyset', 'uni2031', 'uni27D6', 'uni23DE', 'uni23DC', 'uni23E0', 'uni229B', 'uni229C', 'uni2298', 'uni2296', 'circlemultiply', 'uni2299', 'circleplus', 'uni29B8', 'uni229A', 'uni219C', 'uni219D', 'uni219E', 'uni21A0', 'uni21A2', 'uni21A3', 'uni21A4', 'uni21A6', 'arrowdblright', 'arrowdblleft', 'arrowdblboth', 'uni21DA', 'uni21DB', 'uni21E8', 'uni21E6', 'uni27F5', 'uni27F6', 'uni25EF', 'uni25CD', 'uni25C6', 'uni25C7', 'uni25C8', 'uni25B0', 'uni25B1', 'uni25AD', 'uni25A2', 'uni25A3', 'uni25A4', 'uni25A5', 'uni25A6', 'uni25A7', 'uni25A8', 'uni25A9', 'uni25E7', 'uni25E8', 'uni25E9', 'uni25EA', 'uni25EB', 'uni25F0', 'uni25F1', 'uni25F2', 'uni25F3', 'uni25B6', 'uni25C0', 'uni25B3', 'uni25B7', 'uni25BD', 'uni25C1', 'uni25EC', 'uni25ED', 'uni25EE', 'uni25BB', 'uni25C5', 'uni25E5', 'uni25E2', 'uni25E3', 'uni25E4', 'uni2349', 'uni2365', 'uni233E', 'uni235F', 'uni233D', 'uni235C', 'uni236B', 'uni235A', 'uni2371', 'uni2366', 'uni2367', 'uni236D', 'uni2372', 'uni235D', 'uni236C', 'uni2736', 'uni213A', 'uni2103', 'u1F67C', 'u1F67D', 'u1F67E', 'u1F67F', 'uni2109', 'uni2114', 'uni214F', 'weierstrass'] [code: mono-outliers]
</div></details><details><summary>🔥 <b>FAIL:</b> Validates that when an instance record is included for the default instance, its subfamilyNameID value is set to either 2 or 17, and its postScriptNameID value is set to 6. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/fvar.html#com.adobe.fonts/check/varfont/valid_default_instance_nameids">com.adobe.fonts/check/varfont/valid_default_instance_nameids</a>)</summary><div>


* 🔥 **FAIL** 'Regular' instance has the same coordinates as the default instance; its subfamilyNameID should be either 2 or 17, instead of 283. [code: invalid-default-instance-subfamily-nameid:283]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure files are not too large. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/file_size">com.google.fonts/check/file_size</a>)</summary><div>


* ⚠ **WARN** Font file is 1.5Mb; ideally it should be less than 1.0Mb [code: large-font]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure Stylistic Sets have description. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/stylisticset_description">com.google.fonts/check/stylisticset_description</a>)</summary><div>


* ⚠ **WARN** The stylistic set ss03 lacks a description string on the 'name' table. [code: missing-description]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Glyph names are all valid? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/valid_glyphnames">com.google.fonts/check/valid_glyphnames</a>)</summary><div>


* ⚠ **WARN** The following glyph names may be too long for some legacy systems which may expect a maximum 31-char length limit:
kavykawithkavykaaboveinvertedlow [code: legacy-long-names]
</div></details><details><summary>⚠ <b>WARN:</b> Check mark characters are in GDEF mark glyph class. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_mark_chars">com.google.fonts/check/gdef_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following mark characters could be in the GDEF mark glyph class:
	 uni0488 (U+0488), uni0489 (U+0489), uni1ABE (U+1ABE), uniA670 (U+A670), uniA671 (U+A671) and uniA672 (U+A672) [code: mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Does GPOS table have kerning information? This check skips monospaced fonts as defined by post.isFixedPitch value (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gpos.html#com.google.fonts/check/gpos_kerning_info">com.google.fonts/check/gpos_kerning_info</a>)</summary><div>


* ⚠ **WARN** GPOS table lacks kerning information. [code: lacks-kern-info]
</div></details><br></div></details>
### Summary

| 💔 ERROR | 🔥 FAIL | ⚠ WARN | 💤 SKIP | ℹ INFO | 🍞 PASS | 🔎 DEBUG |
|:-----:|:----:|:----:|:----:|:----:|:----:|:----:|
| 0 | 60 | 106 | 1242 | 78 | 949 | 0 |
| 0% | 2% | 4% | 51% | 3% | 39% | 0% |

**Note:** The following loglevels were omitted in this report:
* **SKIP**
* **INFO**
* **PASS**
* **DEBUG**
