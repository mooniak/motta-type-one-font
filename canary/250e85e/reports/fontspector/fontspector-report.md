## FontSpector report

fontspector version: 1.9.0






## Check results




<details><summary>[18] fonts/ttf/MottaTypeOneCANARY-Regular.ttf</summary>
<div>


<details>
    <summary>🔥 <b>FAIL</b> Shapes languages in all GF glyphsets. (googlefonts/glyphsets/shape_languages)</summary>
    <div>








- 🔥 **FAIL** No GF glyphset was found to be supported >80%, so language shaping support couldn't get checked. [code: no-glyphset-supported]
  
  

</div>
</details>





<details>
    <summary>🔥 <b>FAIL</b> Check family name for GF Guide compliance. (googlefonts/family_name_compliance)</summary>
    <div>








- 🔥 **FAIL** "MottaTypeOne CANARY" is a CamelCased name. To solve this, simply use spaces instead in the font name. [code: camelcase]
  
  

</div>
</details>





<details>
    <summary>🔥 <b>FAIL</b> Directory name in GFonts repo structure must
    match NameID 1 of the regular. (googlefonts/repo/dirname_matches_nameid_1)</summary>
    <div>








- 🔥 **FAIL** Family name on the name table ('MottaTypeOne CANARY') does not match directory name in the repo structure ('ttf'). Expected 'mottatypeonecanary'. [code: mismatch]
  
  

</div>
</details>





<details>
    <summary>🔥 <b>FAIL</b> Ensure font can render its own name. (googlefonts/render_own_name)</summary>
    <div>








- 🔥 **FAIL** .notdef glyphs were found when attempting to render MottaTypeOne CANARY [code: render-own-name]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Check that OS/2 fsSelection WWS bit is set correctly. (opentype/fsselection_wws)</summary>
    <div>








- ⚠️ **WARN** OS/2 fsSelection WWS bit is not set, and the font does not have name IDs 21/22 (WWS Family/Subfamily). If the font's naming is WWS-conformant, the WWS bit should be set. [code: no-wws-without-wws-names]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Check if each glyph has the recommended amount of contours. (contour_count)</summary>
    <div>








- ⚠️ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are
     inferred from the typical amounts of contours observed in a
     large collection of reference font families. The divergences
     listed below may simply indicate a significantly different
     design on some of your glyphs. On the other hand, some of these
     may flag actual bugs in the font such as glyphs mapped to an
     incorrect codepoint. Please consider reviewing the design and
     codepoint assignment of these to make sure they are correct.


    The following glyphs do not have the recommended number of contours:
* uni0D96 (U+0D96): found 5, expected one of: [2, 3, 4]
* uni0D89 (U+0D89): found 1, expected one of: [2, 3, 4]
* uni0D9E (U+0D9E): found 1, expected one of: [2, 3, 4]
* uni0D9F (U+0D9F): found 2, expected one of: [1, 3, 5]
* uni0DA4 (U+0DA4): found 2, expected one of: [3, 4, 6]
* uni0D94 (U+0D94): found 4, expected one of: [1, 2, 3] [code: contour-count]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Ensure indic fonts have the Indian Rupee Sign glyph. (rupee)</summary>
    <div>








- ⚠️ **WARN** Font is missing the Indian Rupee Sign glyph. Please add a glyph for Indian Rupee Sign (₹) at codepoint U+20B9. [code: missing-rupee]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Ensure font has overlaps bit set correctly. (overlaps_bit)</summary>
    <div>








- ⚠️ **WARN** The following glyphs have overlaps but the overlaps bit is not set:
* ghsinh
* ddRasinh
* bUusinh
* sRIisinh
* uni0DDD (U+0DDD)
* ksinh
* nnUusinh
* gIsinh
* nysinh
* pRIsinh
* dhUusinh
* sUusinh
* hsinh
* phsinh
* pRIisinh
* thUusinh
* ttUsinh
* fRIsinh
* mbUsinh
* fRsinh
* jhRasinh
* ghRIsinh
* ddRIsinh
* jUsinh
* khUusinh
* tRIisinh
* nUusinh
* jhRIisinh
* vUsinh
* ysinh
* fUsinh
* jhUsinh
* ssIsinh
* gUusinh
* dhRsinh
* ssIisinh
* dhRIisinh
* bhRIisinh
* shIsinh
* nIsinh
* ddhsinh
* jnysinh
* kRasinh
* hRIisinh
* yUsinh
* bRasinh
* nsinh
* jRasinh
* llsinh
* cRIisinh
* khRIisinh
* tUusinh
* ttRIisinh
* ghIsinh
* jhUusinh
* shUsinh
* ssUusinh
* bhIsinh
* ddUusinh
* khRsinh
* ndsinh
* bhRsinh
* dsinh
* dhRIsinh
* kRIisinh
* pRasinh
* gsinh
* chUsinh
* chUusinh
* hRsinh
* kRIsinh
* mRasinh
* nDsinh
* pUusinh
* kSssinh
* sIisinh
* tRasinh
* gRIsinh
* psinh
* gRasinh
* hIsinh
* kUusinh
* tIisinh
* ghRIisinh
* bRsinh
* khUsinh
* tthUusinh
* bhsinh
* kIisinh
* shRasinh
* kSsUusinh
* jRIisinh
* shIisinh
* sssinh
* kSsIisinh
* phUusinh
* sIsinh
* tthsinh
* bhIisinh
* kIsinh
* shRsinh
* vRIsinh
* ssRIisinh
* bhRasinh
* kSsIsinh
* shRIsinh
* bRIisinh
* uni0D92 (U+0D92)
* nUsinh
* cRsinh
* mbUusinh
* hRIsinh
* ssRsinh
* jRsinh
* gRsinh
* phUsinh
* tIsinh
* sRIsinh
* khRIsinh
* tRsinh
* vUusinh
* tRIsinh
* vRsinh
* cRasinh
* fRasinh
* tUsinh
* ddRIisinh
* fUusinh
* shRIisinh
* dRsinh
* sRasinh
* dhRasinh
* pRsinh
* hUsinh
* ssRasinh
* thsinh
* dhUsinh
* gRIisinh
* thUsinh
* ttRsinh
* hRasinh
* shsinh
* bhRIsinh
* cRIsinh
* mUusinh
* ssinh
* jhRIsinh
* cUsinh
* bUsinh
* ddhUusinh
* gUsinh
* nngsinh
* ssUsinh
* cUusinh
* kSsUsinh
* ssRIsinh
* ttRasinh
* sRsinh
* jRIsinh
* ddRsinh
* nngUusinh
* tthUsinh
* ghIisinh
* jUusinh
* tsinh
* nIisinh
* vRIisinh
* ttRIsinh
* vRasinh
* lsinh
* hUusinh
* ttUusinh
* ghRasinh
* khRasinh
* bRIsinh
* fsinh [code: no-overlaps-bit]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Font has correct separator glyphs? (googlefonts/separator_glyphs)</summary>
    <div>








- ⚠️ **WARN** Missing separator glyph U+2028 [code: missing-separator-glyphs]
  
  


- ⚠️ **WARN** Missing separator glyph U+2029 [code: missing-separator-glyphs]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Do any segments have colinear vectors? (outline_colinear_vectors)</summary>
    <div>








- ⚠️ **WARN** The following glyphs have colinear vectors:

* jIisinh: from (481.0, 705.0) to (481.0, 705.0) is colinear with segment from (481.0, 705.0) to (481.0, 705.0)
* jIisinh: from (481.0, 705.0) to (481.0, 705.0) is colinear with segment from (481.0, 705.0) to (481.0, 705.0)
* jRIisinh: from (481.0, 705.0) to (481.0, 705.0) is colinear with segment from (481.0, 705.0) to (481.0, 705.0)
* jRIisinh: from (481.0, 705.0) to (481.0, 705.0) is colinear with segment from (481.0, 705.0) to (481.0, 705.0)
* nyjIisinh: from (585.0, 705.0) to (585.0, 705.0) is colinear with segment from (585.0, 705.0) to (585.0, 705.0)
* nyjIisinh: from (585.0, 705.0) to (585.0, 705.0) is colinear with segment from (585.0, 705.0) to (585.0, 705.0)
* tThIsinh: from (913.0, 556.0) to (913.0, 556.0) is colinear with segment from (913.0, 556.0) to (913.0, 556.0)
* tThIsinh: from (894.0, 802.0) to (894.0, 802.0) is colinear with segment from (894.0, 802.0) to (894.0, 802.0)
* yasign_viramasinh: from (442.0, 594.0) to (442.0, 594.0) is colinear with segment from (442.0, 594.0) to (442.0, 594.0) [code: found-colinear-vectors]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Check the direction of the outermost contour in each glyph (outline_direction)</summary>
    <div>








- ⚠️ **WARN** The following glyphs have a counter-clockwise outer contour:

* ddhIisinh has a path with no bounds (probably a single point)
* jIisinh has a path with no bounds (probably a single point)
* jRIisinh has a path with no bounds (probably a single point)
* nyjIisinh has a path with no bounds (probably a single point)
* tThIisinh has a path with no bounds (probably a single point)
* thIisinh has a path with no bounds (probably a single point)
* tthIisinh has a path with no bounds (probably a single point) [code: ccw-outer-contour]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Do outlines contain any jaggy segments? (outline_jaggy_segments)</summary>
    <div>








- ⚠️ **WARN** The following glyphs have jaggy segments:

* uni0D85 (U+0D85): Quad(QuadBez { p0: (485.0, 406.0), p1: (477.0, 426.0), p2: (476.0, 433.0) })/Quad(QuadBez { p0: (476.0, 433.0), p1: (477.0, 382.0), p2: (477.0, 331.5) }) = 7.006799640080604 degrees
* uni0D86 (U+0D86): Quad(QuadBez { p0: (485.0, 406.0), p1: (477.0, 426.0), p2: (476.0, 433.0) })/Quad(QuadBez { p0: (476.0, 433.0), p1: (477.0, 382.0), p2: (477.0, 331.5) }) = 7.006799640080604 degrees
* uni0D88 (U+0D88): Quad(QuadBez { p0: (485.0, 406.0), p1: (477.0, 426.0), p2: (476.0, 433.0) })/Quad(QuadBez { p0: (476.0, 433.0), p1: (477.0, 382.0), p2: (477.0, 331.5) }) = 7.006799640080604 degrees
* uni0D87 (U+0D87): Quad(QuadBez { p0: (485.0, 406.0), p1: (477.0, 426.0), p2: (476.0, 433.0) })/Quad(QuadBez { p0: (476.0, 433.0), p1: (477.0, 382.0), p2: (477.0, 331.5) }) = 7.006799640080604 degrees
* uni0D93 (U+0D93): Quad(QuadBez { p0: (895.5, 598.0), p1: (864.0, 610.0), p2: (835.0, 634.0) })/Quad(QuadBez { p0: (835.0, 634.0), p1: (857.0, 605.0), p2: (863.5, 574.0) }) = 13.204605306740262 degrees
* bhUusinh: Line(Line { p0: (696.0, 10.0), p1: (629.0, -7.0) })/Line(Line { p0: (629.0, -7.0), p1: (727.0, -7.0) }) = 14.237280465761097 degrees
* chsinh: Quad(QuadBez { p0: (586.0, 298.0), p1: (608.0, 326.0), p2: (614.0, 375.0) })/Quad(QuadBez { p0: (614.0, 375.0), p1: (611.0, 367.0), p2: (602.0, 349.5) }) = 13.574987812753653 degrees
* chIsinh: Quad(QuadBez { p0: (175.0, 711.0), p1: (228.0, 711.0), p2: (275.0, 679.0) })/Quad(QuadBez { p0: (275.0, 679.0), p1: (261.0, 693.0), p2: (255.5, 713.5) }) = 10.750966993188074 degrees
* chIsinh: Line(Line { p0: (293.0, 665.0), p1: (291.0, 666.0) })/Quad(QuadBez { p0: (291.0, 666.0), p1: (318.0, 644.0), p2: (334.5, 612.0) }) = 12.60860679336625 degrees
* dDhsinh: Quad(QuadBez { p0: (401.0, 538.0), p1: (344.0, 554.0), p2: (293.0, 556.0) })/Quad(QuadBez { p0: (293.0, 556.0), p1: (310.0, 559.0), p2: (329.0, 559.0) }) = 12.25372236733639 degrees
* dDhsinh: Quad(QuadBez { p0: (162.5, 529.5), p1: (216.0, 558.0), p2: (293.0, 556.0) })/Quad(QuadBez { p0: (293.0, 556.0), p1: (259.0, 550.0), p2: (233.0, 532.5) }) = 11.495847330269116 degrees
* dDhIisinh: Quad(QuadBez { p0: (424.0, 536.0), p1: (373.0, 550.0), p2: (327.0, 553.0) })/Quad(QuadBez { p0: (327.0, 553.0), p1: (335.0, 554.0), p2: (343.0, 554.0) }) = 10.856413348062235 degrees
* dDhIisinh: Quad(QuadBez { p0: (186.5, 531.5), p1: (245.0, 559.0), p2: (327.0, 553.0) })/Quad(QuadBez { p0: (327.0, 553.0), p1: (288.0, 550.0), p2: (258.5, 534.0) }) = 8.583621480113925 degrees
* ddhsinh: Quad(QuadBez { p0: (361.5, 27.0), p1: (329.0, 54.0), p2: (328.0, 102.0) })/Quad(QuadBez { p0: (328.0, 102.0), p1: (327.0, 96.0), p2: (318.5, 80.0) }) = 10.655811632007621 degrees
* ddhIisinh: Quad(QuadBez { p0: (361.5, 27.0), p1: (329.0, 54.0), p2: (328.0, 102.0) })/Quad(QuadBez { p0: (328.0, 102.0), p1: (327.0, 96.0), p2: (318.5, 80.0) }) = 10.655811632007621 degrees
* uni0DAA (U+0DAA): Quad(QuadBez { p0: (361.5, 27.0), p1: (329.0, 54.0), p2: (328.0, 102.0) })/Quad(QuadBez { p0: (328.0, 102.0), p1: (327.0, 96.0), p2: (318.5, 80.0) }) = 10.655811632007621 degrees
* dvocalicr._csinh: Quad(QuadBez { p0: (706.5, 461.5), p1: (713.0, 450.0), p2: (720.0, 442.0) })/Quad(QuadBez { p0: (720.0, 442.0), p1: (714.0, 447.0), p2: (697.0, 464.0) }) = 9.00850374202515 degrees
* dvocalicrr._csinh: Quad(QuadBez { p0: (1102.5, 461.5), p1: (1109.0, 450.0), p2: (1116.0, 442.0) })/Quad(QuadBez { p0: (1116.0, 442.0), p1: (1110.0, 447.0), p2: (1093.0, 464.0) }) = 9.00850374202515 degrees
* dvocalicrr._csinh: Quad(QuadBez { p0: (702.5, 461.5), p1: (709.0, 450.0), p2: (716.0, 442.0) })/Quad(QuadBez { p0: (716.0, 442.0), p1: (710.0, 447.0), p2: (693.0, 464.0) }) = 9.00850374202515 degrees
* uni0D91 (U+0D91): Quad(QuadBez { p0: (401.5, 598.0), p1: (370.0, 610.0), p2: (341.0, 634.0) })/Quad(QuadBez { p0: (341.0, 634.0), p1: (363.0, 605.0), p2: (369.5, 574.0) }) = 13.204605306740262 degrees
* uni0D92 (U+0D92): Quad(QuadBez { p0: (418.5, 598.0), p1: (387.0, 610.0), p2: (358.0, 634.0) })/Quad(QuadBez { p0: (358.0, 634.0), p1: (380.0, 605.0), p2: (386.5, 574.0) }) = 13.204605306740262 degrees
* jhIsinh: Quad(QuadBez { p0: (520.0, 469.0), p1: (503.0, 469.0), p2: (487.0, 472.0) })/Quad(QuadBez { p0: (487.0, 472.0), p1: (552.0, 450.0), p2: (597.0, 389.0) }) = 8.079327528025978 degrees
* jhIsinh: Quad(QuadBez { p0: (135.0, 158.0), p1: (121.0, 198.0), p2: (97.0, 222.0) })/Quad(QuadBez { p0: (97.0, 222.0), p1: (111.0, 202.0), p2: (111.0, 181.0) }) = 10.007979801441312 degrees
* jhIsinh: Quad(QuadBez { p0: (350.0, 463.0), p1: (353.0, 466.0), p2: (356.0, 467.0) })/Quad(QuadBez { p0: (356.0, 467.0), p1: (289.0, 461.0), p2: (222.0, 402.0) }) = 13.317633972949405 degrees
* jhIisinh: Quad(QuadBez { p0: (504.0, 469.0), p1: (487.0, 469.0), p2: (471.0, 472.0) })/Quad(QuadBez { p0: (471.0, 472.0), p1: (538.0, 449.0), p2: (582.0, 389.0) }) = 8.326849413353978 degrees
* jhIisinh: Quad(QuadBez { p0: (120.0, 158.0), p1: (104.0, 199.0), p2: (81.0, 222.0) })/Quad(QuadBez { p0: (81.0, 222.0), p1: (96.0, 203.0), p2: (96.0, 181.0) }) = 6.70983680775695 degrees
* jhIisinh: Quad(QuadBez { p0: (335.0, 463.0), p1: (338.0, 466.0), p2: (341.0, 467.0) })/Quad(QuadBez { p0: (341.0, 467.0), p1: (274.0, 461.0), p2: (206.0, 402.0) }) = 13.317633972949405 degrees
* jhRIsinh: Quad(QuadBez { p0: (520.0, 469.0), p1: (503.0, 469.0), p2: (487.0, 472.0) })/Quad(QuadBez { p0: (487.0, 472.0), p1: (552.0, 450.0), p2: (597.0, 389.0) }) = 8.079327528025978 degrees
* jhRIsinh: Quad(QuadBez { p0: (135.0, 158.0), p1: (121.0, 198.0), p2: (97.0, 222.0) })/Quad(QuadBez { p0: (97.0, 222.0), p1: (111.0, 202.0), p2: (111.0, 181.0) }) = 10.007979801441312 degrees
* jhRIsinh: Quad(QuadBez { p0: (350.0, 463.0), p1: (353.0, 466.0), p2: (356.0, 467.0) })/Quad(QuadBez { p0: (356.0, 467.0), p1: (289.0, 461.0), p2: (222.0, 402.0) }) = 13.317633972949405 degrees
* jhRIisinh: Quad(QuadBez { p0: (504.0, 469.0), p1: (487.0, 469.0), p2: (471.0, 472.0) })/Quad(QuadBez { p0: (471.0, 472.0), p1: (538.0, 449.0), p2: (582.0, 389.0) }) = 8.326849413353978 degrees
* jhRIisinh: Quad(QuadBez { p0: (120.0, 158.0), p1: (104.0, 199.0), p2: (81.0, 222.0) })/Quad(QuadBez { p0: (81.0, 222.0), p1: (96.0, 203.0), p2: (96.0, 181.0) }) = 6.70983680775695 degrees
* jhRIisinh: Quad(QuadBez { p0: (335.0, 463.0), p1: (338.0, 466.0), p2: (341.0, 467.0) })/Quad(QuadBez { p0: (341.0, 467.0), p1: (274.0, 461.0), p2: (206.0, 402.0) }) = 13.317633972949405 degrees
* jhRasinh: Quad(QuadBez { p0: (135.0, 152.0), p1: (121.0, 192.0), p2: (97.0, 216.0) })/Quad(QuadBez { p0: (97.0, 216.0), p1: (112.0, 197.0), p2: (112.0, 174.0) }) = 6.709836807756896 degrees
* jhRasinh: Quad(QuadBez { p0: (456.5, 472.5), p1: (451.0, 473.0), p2: (450.0, 473.0) })/Quad(QuadBez { p0: (450.0, 473.0), p1: (535.0, 456.0), p2: (587.0, 382.0) }) = 11.309932474020227 degrees
* jhUsinh: Quad(QuadBez { p0: (135.0, 152.0), p1: (121.0, 192.0), p2: (97.0, 216.0) })/Quad(QuadBez { p0: (97.0, 216.0), p1: (112.0, 197.0), p2: (112.0, 174.0) }) = 6.709836807756896 degrees
* jhUsinh: Quad(QuadBez { p0: (456.5, 472.5), p1: (451.0, 473.0), p2: (450.0, 473.0) })/Quad(QuadBez { p0: (450.0, 473.0), p1: (535.0, 456.0), p2: (587.0, 382.0) }) = 11.309932474020227 degrees
* jhUusinh: Quad(QuadBez { p0: (135.0, 152.0), p1: (121.0, 192.0), p2: (97.0, 216.0) })/Quad(QuadBez { p0: (97.0, 216.0), p1: (112.0, 197.0), p2: (112.0, 174.0) }) = 6.709836807756896 degrees
* jhUusinh: Quad(QuadBez { p0: (456.5, 472.5), p1: (451.0, 473.0), p2: (450.0, 473.0) })/Quad(QuadBez { p0: (450.0, 473.0), p1: (535.0, 456.0), p2: (587.0, 382.0) }) = 11.309932474020227 degrees
* uni0DA3 (U+0DA3): Quad(QuadBez { p0: (135.0, 152.0), p1: (121.0, 192.0), p2: (97.0, 216.0) })/Quad(QuadBez { p0: (97.0, 216.0), p1: (112.0, 197.0), p2: (112.0, 174.0) }) = 6.709836807756896 degrees
* uni0DA3 (U+0DA3): Quad(QuadBez { p0: (456.5, 472.5), p1: (451.0, 473.0), p2: (450.0, 473.0) })/Quad(QuadBez { p0: (450.0, 473.0), p1: (535.0, 456.0), p2: (587.0, 382.0) }) = 11.309932474020227 degrees
* ksinh: Quad(QuadBez { p0: (543.0, 477.5), p1: (490.0, 475.0), p2: (450.0, 473.0) })/Quad(QuadBez { p0: (450.0, 473.0), p1: (507.0, 462.0), p2: (550.0, 424.0) }) = 13.785209945981022 degrees
* ksinh: Quad(QuadBez { p0: (130.0, 166.0), p1: (119.0, 195.0), p2: (97.0, 216.0) })/Quad(QuadBez { p0: (97.0, 216.0), p1: (100.0, 212.0), p2: (106.0, 201.0) }) = 9.462322208025613 degrees
* kIsinh: Quad(QuadBez { p0: (543.0, 477.5), p1: (490.0, 475.0), p2: (450.0, 473.0) })/Quad(QuadBez { p0: (450.0, 473.0), p1: (507.0, 462.0), p2: (550.0, 424.0) }) = 13.785209945981022 degrees
* kIsinh: Quad(QuadBez { p0: (130.0, 166.0), p1: (119.0, 195.0), p2: (97.0, 216.0) })/Quad(QuadBez { p0: (97.0, 216.0), p1: (100.0, 212.0), p2: (106.0, 201.0) }) = 9.462322208025613 degrees
* kIisinh: Quad(QuadBez { p0: (543.0, 477.5), p1: (490.0, 475.0), p2: (450.0, 473.0) })/Quad(QuadBez { p0: (450.0, 473.0), p1: (507.0, 462.0), p2: (550.0, 424.0) }) = 13.785209945981022 degrees
* kIisinh: Quad(QuadBez { p0: (130.0, 166.0), p1: (119.0, 195.0), p2: (97.0, 216.0) })/Quad(QuadBez { p0: (97.0, 216.0), p1: (100.0, 212.0), p2: (106.0, 201.0) }) = 9.462322208025613 degrees
* kRIsinh: Quad(QuadBez { p0: (542.0, 477.5), p1: (489.0, 475.0), p2: (449.0, 473.0) })/Quad(QuadBez { p0: (449.0, 473.0), p1: (506.0, 462.0), p2: (549.0, 424.0) }) = 13.785209945981022 degrees
* kRIsinh: Quad(QuadBez { p0: (129.0, 166.0), p1: (118.0, 195.0), p2: (96.0, 216.0) })/Quad(QuadBez { p0: (96.0, 216.0), p1: (99.0, 212.0), p2: (105.0, 201.0) }) = 9.462322208025613 degrees
* kRIisinh: Quad(QuadBez { p0: (537.0, 477.5), p1: (484.0, 475.0), p2: (444.0, 473.0) })/Quad(QuadBez { p0: (444.0, 473.0), p1: (501.0, 462.0), p2: (544.0, 424.0) }) = 13.785209945981022 degrees
* kRIisinh: Quad(QuadBez { p0: (124.0, 166.0), p1: (113.0, 195.0), p2: (91.0, 216.0) })/Quad(QuadBez { p0: (91.0, 216.0), p1: (94.0, 212.0), p2: (100.0, 201.0) }) = 9.462322208025613 degrees
* kRasinh: Quad(QuadBez { p0: (543.0, 477.5), p1: (490.0, 475.0), p2: (450.0, 473.0) })/Quad(QuadBez { p0: (450.0, 473.0), p1: (507.0, 462.0), p2: (550.0, 424.0) }) = 13.785209945981022 degrees
* kRasinh: Quad(QuadBez { p0: (130.0, 166.0), p1: (119.0, 195.0), p2: (97.0, 216.0) })/Quad(QuadBez { p0: (97.0, 216.0), p1: (100.0, 212.0), p2: (106.0, 201.0) }) = 9.462322208025613 degrees
* kSssinh: Quad(QuadBez { p0: (488.0, 469.0), p1: (471.0, 469.0), p2: (453.0, 473.0) })/Quad(QuadBez { p0: (453.0, 473.0), p1: (503.0, 456.0), p2: (540.5, 418.0) }) = 6.249225513294006 degrees
* kSssinh: Quad(QuadBez { p0: (357.0, 90.0), p1: (351.0, 108.0), p2: (351.0, 113.0) })/Quad(QuadBez { p0: (351.0, 113.0), p1: (345.0, 68.0), p2: (316.0, 34.5) }) = 7.594643368591447 degrees
* kSssinh: Quad(QuadBez { p0: (98.5, 172.0), p1: (87.0, 201.0), p2: (65.0, 222.0) })/Quad(QuadBez { p0: (65.0, 222.0), p1: (68.0, 218.0), p2: (73.5, 207.5) }) = 9.462322208025613 degrees
* kSsIsinh: Quad(QuadBez { p0: (515.0, 469.0), p1: (498.0, 469.0), p2: (480.0, 473.0) })/Quad(QuadBez { p0: (480.0, 473.0), p1: (530.0, 456.0), p2: (567.5, 418.0) }) = 6.249225513294006 degrees
* kSsIsinh: Quad(QuadBez { p0: (384.0, 90.0), p1: (378.0, 108.0), p2: (378.0, 113.0) })/Quad(QuadBez { p0: (378.0, 113.0), p1: (372.0, 68.0), p2: (343.0, 34.5) }) = 7.594643368591447 degrees
* kSsIsinh: Quad(QuadBez { p0: (125.5, 172.0), p1: (114.0, 201.0), p2: (92.0, 222.0) })/Quad(QuadBez { p0: (92.0, 222.0), p1: (95.0, 218.0), p2: (100.5, 207.5) }) = 9.462322208025613 degrees
* kSsIisinh: Quad(QuadBez { p0: (507.0, 469.0), p1: (490.0, 469.0), p2: (472.0, 473.0) })/Quad(QuadBez { p0: (472.0, 473.0), p1: (522.0, 456.0), p2: (559.5, 418.0) }) = 6.249225513294006 degrees
* kSsIisinh: Quad(QuadBez { p0: (376.0, 90.0), p1: (370.0, 108.0), p2: (370.0, 113.0) })/Quad(QuadBez { p0: (370.0, 113.0), p1: (364.0, 68.0), p2: (335.0, 34.5) }) = 7.594643368591447 degrees
* kSsIisinh: Quad(QuadBez { p0: (117.5, 172.0), p1: (106.0, 201.0), p2: (84.0, 222.0) })/Quad(QuadBez { p0: (84.0, 222.0), p1: (87.0, 218.0), p2: (92.5, 207.5) }) = 9.462322208025613 degrees
* kSsUsinh: Quad(QuadBez { p0: (507.0, 469.0), p1: (490.0, 469.0), p2: (472.0, 473.0) })/Quad(QuadBez { p0: (472.0, 473.0), p1: (522.0, 456.0), p2: (559.5, 418.0) }) = 6.249225513294006 degrees
* kSsUsinh: Quad(QuadBez { p0: (376.0, 90.0), p1: (370.0, 108.0), p2: (370.0, 113.0) })/Quad(QuadBez { p0: (370.0, 113.0), p1: (364.0, 68.0), p2: (335.0, 34.5) }) = 7.594643368591447 degrees
* kSsUsinh: Quad(QuadBez { p0: (117.5, 172.0), p1: (106.0, 201.0), p2: (84.0, 222.0) })/Quad(QuadBez { p0: (84.0, 222.0), p1: (87.0, 218.0), p2: (92.5, 207.5) }) = 9.462322208025613 degrees
* kSsUusinh: Quad(QuadBez { p0: (507.0, 469.0), p1: (490.0, 469.0), p2: (472.0, 473.0) })/Quad(QuadBez { p0: (472.0, 473.0), p1: (522.0, 456.0), p2: (559.5, 418.0) }) = 6.249225513294006 degrees
* kSsUusinh: Quad(QuadBez { p0: (376.0, 90.0), p1: (370.0, 108.0), p2: (370.0, 113.0) })/Quad(QuadBez { p0: (370.0, 113.0), p1: (364.0, 68.0), p2: (335.0, 34.5) }) = 7.594643368591447 degrees
* kSsUusinh: Quad(QuadBez { p0: (117.5, 172.0), p1: (106.0, 201.0), p2: (84.0, 222.0) })/Quad(QuadBez { p0: (84.0, 222.0), p1: (87.0, 218.0), p2: (92.5, 207.5) }) = 9.462322208025613 degrees
* kSsasinh: Quad(QuadBez { p0: (507.0, 469.0), p1: (490.0, 469.0), p2: (472.0, 473.0) })/Quad(QuadBez { p0: (472.0, 473.0), p1: (522.0, 456.0), p2: (559.5, 418.0) }) = 6.249225513294006 degrees
* kSsasinh: Quad(QuadBez { p0: (376.0, 90.0), p1: (370.0, 108.0), p2: (370.0, 113.0) })/Quad(QuadBez { p0: (370.0, 113.0), p1: (364.0, 68.0), p2: (335.0, 34.5) }) = 7.594643368591447 degrees
* kSsasinh: Quad(QuadBez { p0: (117.5, 172.0), p1: (106.0, 201.0), p2: (84.0, 222.0) })/Quad(QuadBez { p0: (84.0, 222.0), p1: (87.0, 218.0), p2: (92.5, 207.5) }) = 9.462322208025613 degrees
* kUsinh: Quad(QuadBez { p0: (543.0, 477.5), p1: (490.0, 475.0), p2: (450.0, 473.0) })/Quad(QuadBez { p0: (450.0, 473.0), p1: (507.0, 462.0), p2: (550.0, 424.0) }) = 13.785209945981022 degrees
* kUsinh: Quad(QuadBez { p0: (130.0, 166.0), p1: (119.0, 195.0), p2: (97.0, 216.0) })/Quad(QuadBez { p0: (97.0, 216.0), p1: (100.0, 212.0), p2: (106.0, 201.0) }) = 9.462322208025613 degrees
* kUusinh: Quad(QuadBez { p0: (543.0, 477.5), p1: (490.0, 475.0), p2: (450.0, 473.0) })/Quad(QuadBez { p0: (450.0, 473.0), p1: (507.0, 462.0), p2: (550.0, 424.0) }) = 13.785209945981022 degrees
* kUusinh: Quad(QuadBez { p0: (130.0, 166.0), p1: (119.0, 195.0), p2: (97.0, 216.0) })/Quad(QuadBez { p0: (97.0, 216.0), p1: (100.0, 212.0), p2: (106.0, 201.0) }) = 9.462322208025613 degrees
* kVsinh: Quad(QuadBez { p0: (507.0, 469.0), p1: (490.0, 469.0), p2: (472.0, 473.0) })/Quad(QuadBez { p0: (472.0, 473.0), p1: (522.0, 456.0), p2: (559.5, 418.0) }) = 6.249225513294006 degrees
* kVsinh: Quad(QuadBez { p0: (376.0, 90.0), p1: (370.0, 108.0), p2: (370.0, 113.0) })/Quad(QuadBez { p0: (370.0, 113.0), p1: (364.0, 68.0), p2: (335.0, 34.5) }) = 7.594643368591447 degrees
* kVsinh: Quad(QuadBez { p0: (117.5, 172.0), p1: (106.0, 201.0), p2: (84.0, 222.0) })/Quad(QuadBez { p0: (84.0, 222.0), p1: (87.0, 218.0), p2: (92.5, 207.5) }) = 9.462322208025613 degrees
* kVIsinh: Quad(QuadBez { p0: (507.0, 469.0), p1: (490.0, 469.0), p2: (472.0, 473.0) })/Quad(QuadBez { p0: (472.0, 473.0), p1: (522.0, 456.0), p2: (559.5, 418.0) }) = 6.249225513294006 degrees
* kVIsinh: Quad(QuadBez { p0: (376.0, 90.0), p1: (370.0, 108.0), p2: (370.0, 113.0) })/Quad(QuadBez { p0: (370.0, 113.0), p1: (364.0, 68.0), p2: (335.0, 34.5) }) = 7.594643368591447 degrees
* kVIsinh: Quad(QuadBez { p0: (117.5, 172.0), p1: (106.0, 201.0), p2: (84.0, 222.0) })/Quad(QuadBez { p0: (84.0, 222.0), p1: (87.0, 218.0), p2: (92.5, 207.5) }) = 9.462322208025613 degrees
* kVIisinh: Quad(QuadBez { p0: (507.0, 469.0), p1: (490.0, 469.0), p2: (472.0, 473.0) })/Quad(QuadBez { p0: (472.0, 473.0), p1: (522.0, 456.0), p2: (559.5, 418.0) }) = 6.249225513294006 degrees
* kVIisinh: Quad(QuadBez { p0: (376.0, 90.0), p1: (370.0, 108.0), p2: (370.0, 113.0) })/Quad(QuadBez { p0: (370.0, 113.0), p1: (364.0, 68.0), p2: (335.0, 34.5) }) = 7.594643368591447 degrees
* kVIisinh: Quad(QuadBez { p0: (117.5, 172.0), p1: (106.0, 201.0), p2: (84.0, 222.0) })/Quad(QuadBez { p0: (84.0, 222.0), p1: (87.0, 218.0), p2: (92.5, 207.5) }) = 9.462322208025613 degrees
* kVUsinh: Quad(QuadBez { p0: (507.0, 469.0), p1: (490.0, 469.0), p2: (472.0, 473.0) })/Quad(QuadBez { p0: (472.0, 473.0), p1: (522.0, 456.0), p2: (559.5, 418.0) }) = 6.249225513294006 degrees
* kVUsinh: Quad(QuadBez { p0: (376.0, 90.0), p1: (370.0, 108.0), p2: (370.0, 113.0) })/Quad(QuadBez { p0: (370.0, 113.0), p1: (364.0, 68.0), p2: (335.0, 34.5) }) = 7.594643368591447 degrees
* kVUsinh: Quad(QuadBez { p0: (117.5, 172.0), p1: (106.0, 201.0), p2: (84.0, 222.0) })/Quad(QuadBez { p0: (84.0, 222.0), p1: (87.0, 218.0), p2: (92.5, 207.5) }) = 9.462322208025613 degrees
* kVUusinh: Quad(QuadBez { p0: (507.0, 469.0), p1: (490.0, 469.0), p2: (472.0, 473.0) })/Quad(QuadBez { p0: (472.0, 473.0), p1: (522.0, 456.0), p2: (559.5, 418.0) }) = 6.249225513294006 degrees
* kVUusinh: Quad(QuadBez { p0: (376.0, 90.0), p1: (370.0, 108.0), p2: (370.0, 113.0) })/Quad(QuadBez { p0: (370.0, 113.0), p1: (364.0, 68.0), p2: (335.0, 34.5) }) = 7.594643368591447 degrees
* kVUusinh: Quad(QuadBez { p0: (117.5, 172.0), p1: (106.0, 201.0), p2: (84.0, 222.0) })/Quad(QuadBez { p0: (84.0, 222.0), p1: (87.0, 218.0), p2: (92.5, 207.5) }) = 9.462322208025613 degrees
* kVasinh: Quad(QuadBez { p0: (507.0, 469.0), p1: (490.0, 469.0), p2: (472.0, 473.0) })/Quad(QuadBez { p0: (472.0, 473.0), p1: (522.0, 456.0), p2: (559.5, 418.0) }) = 6.249225513294006 degrees
* kVasinh: Quad(QuadBez { p0: (376.0, 90.0), p1: (370.0, 108.0), p2: (370.0, 113.0) })/Quad(QuadBez { p0: (370.0, 113.0), p1: (364.0, 68.0), p2: (335.0, 34.5) }) = 7.594643368591447 degrees
* kVasinh: Quad(QuadBez { p0: (117.5, 172.0), p1: (106.0, 201.0), p2: (84.0, 222.0) })/Quad(QuadBez { p0: (84.0, 222.0), p1: (87.0, 218.0), p2: (92.5, 207.5) }) = 9.462322208025613 degrees
* uni0D9A (U+0D9A): Quad(QuadBez { p0: (543.0, 477.5), p1: (490.0, 475.0), p2: (450.0, 473.0) })/Quad(QuadBez { p0: (450.0, 473.0), p1: (507.0, 462.0), p2: (550.0, 424.0) }) = 13.785209945981022 degrees
* uni0D9A (U+0D9A): Quad(QuadBez { p0: (130.0, 166.0), p1: (119.0, 195.0), p2: (97.0, 216.0) })/Quad(QuadBez { p0: (97.0, 216.0), p1: (100.0, 212.0), p2: (106.0, 201.0) }) = 9.462322208025613 degrees
* uni0DF4 (U+0DF4): Quad(QuadBez { p0: (682.0, 455.5), p1: (692.0, 444.0), p2: (693.0, 442.0) })/Quad(QuadBez { p0: (693.0, 442.0), p1: (685.0, 458.0), p2: (677.5, 482.5) }) = 0.0000012074182697257333 degrees
* uni0DF4 (U+0DF4): Quad(QuadBez { p0: (679.0, 597.0), p1: (688.0, 623.0), p2: (695.0, 636.0) })/Quad(QuadBez { p0: (695.0, 636.0), p1: (691.0, 624.0), p2: (686.0, 604.5) }) = 9.865806943084365 degrees
* uni0DF4 (U+0DF4): Quad(QuadBez { p0: (1001.5, 604.5), p1: (997.0, 624.0), p2: (993.0, 636.0) })/Quad(QuadBez { p0: (993.0, 636.0), p1: (999.0, 623.0), p2: (1008.5, 597.0) }) = 6.340191745909966 degrees
* uni0DF4 (U+0DF4): Quad(QuadBez { p0: (1010.5, 482.5), p1: (1003.0, 458.0), p2: (995.0, 442.0) })/Quad(QuadBez { p0: (995.0, 442.0), p1: (996.0, 444.0), p2: (1005.5, 455.5) }) = 0.0000012074182697257333 degrees
* llUsinh: Quad(QuadBez { p0: (36.5, 429.0), p1: (39.0, 415.0), p2: (41.0, 406.0) })/Quad(QuadBez { p0: (41.0, 406.0), p1: (37.0, 419.0), p2: (32.5, 441.5) }) = 4.573921259900898 degrees
* llUusinh: Quad(QuadBez { p0: (36.5, 429.0), p1: (39.0, 415.0), p2: (41.0, 406.0) })/Quad(QuadBez { p0: (41.0, 406.0), p1: (37.0, 419.0), p2: (32.5, 441.5) }) = 4.573921259900898 degrees
* uni0DD8 (U+0DD8): Quad(QuadBez { p0: (117.5, 461.5), p1: (124.0, 450.0), p2: (131.0, 442.0) })/Quad(QuadBez { p0: (131.0, 442.0), p1: (125.0, 447.0), p2: (108.0, 464.0) }) = 9.00850374202515 degrees
* uni0DF2 (U+0DF2): Quad(QuadBez { p0: (517.5, 461.5), p1: (524.0, 450.0), p2: (531.0, 442.0) })/Quad(QuadBez { p0: (531.0, 442.0), p1: (525.0, 447.0), p2: (508.0, 464.0) }) = 9.00850374202515 degrees
* uni0DF2 (U+0DF2): Quad(QuadBez { p0: (117.5, 461.5), p1: (124.0, 450.0), p2: (131.0, 442.0) })/Quad(QuadBez { p0: (131.0, 442.0), p1: (125.0, 447.0), p2: (108.0, 464.0) }) = 9.00850374202515 degrees
* mbsinh: Quad(QuadBez { p0: (446.0, 139.0), p1: (477.0, 139.0), p2: (505.0, 121.0) })/Quad(QuadBez { p0: (505.0, 121.0), p1: (497.0, 127.0), p2: (475.5, 139.0) }) = 4.134671373736451 degrees
* mbsinh: Quad(QuadBez { p0: (217.0, 133.0), p1: (194.0, 119.0), p2: (184.0, 111.0) })/Quad(QuadBez { p0: (184.0, 111.0), p1: (209.0, 127.0), p2: (232.5, 134.5) }) = 6.040565182897221 degrees
* mbIsinh: Quad(QuadBez { p0: (458.0, 135.0), p1: (487.0, 135.0), p2: (519.0, 116.0) })/Quad(QuadBez { p0: (519.0, 116.0), p1: (510.0, 122.0), p2: (488.5, 134.0) }) = 2.990344975165385 degrees
* mbIsinh: Quad(QuadBez { p0: (223.0, 128.0), p1: (199.0, 114.0), p2: (189.0, 106.0) })/Quad(QuadBez { p0: (189.0, 106.0), p1: (214.0, 122.0), p2: (238.5, 129.5) }) = 6.040565182897221 degrees
* mbIisinh: Quad(QuadBez { p0: (444.0, 137.0), p1: (472.0, 137.0), p2: (504.0, 118.0) })/Quad(QuadBez { p0: (504.0, 118.0), p1: (495.0, 124.0), p2: (474.0, 136.0) }) = 2.990344975165385 degrees
* mbIisinh: Quad(QuadBez { p0: (216.0, 130.0), p1: (193.0, 116.0), p2: (183.0, 108.0) })/Quad(QuadBez { p0: (183.0, 108.0), p1: (207.0, 125.0), p2: (231.0, 132.0) }) = 3.3485948144568507 degrees
* mbUsinh: Quad(QuadBez { p0: (447.0, 132.0), p1: (475.0, 132.0), p2: (507.0, 113.0) })/Quad(QuadBez { p0: (507.0, 113.0), p1: (498.0, 119.0), p2: (477.0, 131.0) }) = 2.990344975165385 degrees
* mbUsinh: Quad(QuadBez { p0: (219.0, 125.0), p1: (196.0, 111.0), p2: (186.0, 103.0) })/Quad(QuadBez { p0: (186.0, 103.0), p1: (210.0, 119.0), p2: (234.0, 126.5) }) = 4.969740728110216 degrees
* mbUusinh: Quad(QuadBez { p0: (447.0, 132.0), p1: (475.0, 132.0), p2: (507.0, 113.0) })/Quad(QuadBez { p0: (507.0, 113.0), p1: (498.0, 119.0), p2: (477.0, 131.0) }) = 2.990344975165385 degrees
* mbUusinh: Quad(QuadBez { p0: (219.0, 125.0), p1: (196.0, 111.0), p2: (186.0, 103.0) })/Quad(QuadBez { p0: (186.0, 103.0), p1: (210.0, 119.0), p2: (234.0, 126.5) }) = 4.969740728110216 degrees
* uni0DB9 (U+0DB9): Quad(QuadBez { p0: (447.0, 132.0), p1: (475.0, 132.0), p2: (507.0, 113.0) })/Quad(QuadBez { p0: (507.0, 113.0), p1: (498.0, 119.0), p2: (477.0, 131.0) }) = 2.990344975165385 degrees
* uni0DB9 (U+0DB9): Quad(QuadBez { p0: (219.0, 125.0), p1: (196.0, 111.0), p2: (186.0, 103.0) })/Quad(QuadBez { p0: (186.0, 103.0), p1: (210.0, 119.0), p2: (234.0, 126.5) }) = 4.969740728110216 degrees
* ndsinh: Quad(QuadBez { p0: (32.5, 449.5), p1: (21.0, 401.0), p2: (19.0, 374.0) })/Line(Line { p0: (19.0, 374.0), p1: (19.0, 380.0) }) = 4.236394799058849 degrees
* ndIsinh: Quad(QuadBez { p0: (38.0, 467.0), p1: (22.0, 424.0), p2: (19.0, 374.0) })/Line(Line { p0: (19.0, 374.0), p1: (19.0, 380.0) }) = 3.4336303624506144 degrees
* ndIisinh: Quad(QuadBez { p0: (21.5, 449.5), p1: (10.0, 401.0), p2: (8.0, 374.0) })/Line(Line { p0: (8.0, 374.0), p1: (8.0, 380.0) }) = 4.236394799058849 degrees
* uni0DB3 (U+0DB3): Quad(QuadBez { p0: (32.5, 449.5), p1: (21.0, 401.0), p2: (19.0, 374.0) })/Line(Line { p0: (19.0, 374.0), p1: (19.0, 380.0) }) = 4.236394799058849 degrees
* uni0D9E (U+0D9E): Quad(QuadBez { p0: (350.0, 60.0), p1: (338.0, 87.0), p2: (337.0, 114.0) })/Quad(QuadBez { p0: (337.0, 114.0), p1: (336.0, 108.0), p2: (328.5, 90.0) }) = 11.583418604687026 degrees
* nnsinh: Quad(QuadBez { p0: (618.0, 270.5), p1: (605.0, 286.0), p2: (603.0, 305.0) })/Line(Line { p0: (603.0, 305.0), p1: (603.0, 288.0) }) = 6.009005957494535 degrees
* nnsinh: Quad(QuadBez { p0: (724.5, 566.5), p1: (748.0, 539.0), p2: (749.0, 498.0) })/Quad(QuadBez { p0: (749.0, 498.0), p1: (750.0, 521.0), p2: (761.0, 544.0) }) = 3.886733949295391 degrees
* nnIsinh: Quad(QuadBez { p0: (606.0, 264.0), p1: (593.0, 279.0), p2: (591.0, 298.0) })/Quad(QuadBez { p0: (591.0, 298.0), p1: (591.0, 295.0), p2: (591.5, 291.0) }) = 6.009005957494474 degrees
* nnIsinh: Quad(QuadBez { p0: (711.0, 557.0), p1: (734.0, 530.0), p2: (736.0, 489.0) })/Quad(QuadBez { p0: (736.0, 489.0), p1: (736.0, 512.0), p2: (747.0, 534.5) }) = 2.792702365713218 degrees
* nnIisinh: Quad(QuadBez { p0: (606.0, 264.0), p1: (593.0, 279.0), p2: (591.0, 298.0) })/Quad(QuadBez { p0: (591.0, 298.0), p1: (591.0, 295.0), p2: (591.5, 291.0) }) = 6.009005957494474 degrees
* nnIisinh: Quad(QuadBez { p0: (711.0, 557.0), p1: (734.0, 530.0), p2: (736.0, 489.0) })/Quad(QuadBez { p0: (736.0, 489.0), p1: (736.0, 512.0), p2: (747.0, 534.5) }) = 2.792702365713218 degrees
* nnUsinh: Quad(QuadBez { p0: (618.0, 270.5), p1: (605.0, 286.0), p2: (603.0, 305.0) })/Line(Line { p0: (603.0, 305.0), p1: (603.0, 288.0) }) = 6.009005957494535 degrees
* nnUsinh: Quad(QuadBez { p0: (724.5, 566.5), p1: (748.0, 539.0), p2: (749.0, 498.0) })/Quad(QuadBez { p0: (749.0, 498.0), p1: (750.0, 521.0), p2: (761.0, 544.0) }) = 3.886733949295391 degrees
* nnUusinh: Quad(QuadBez { p0: (618.0, 270.5), p1: (605.0, 286.0), p2: (603.0, 305.0) })/Line(Line { p0: (603.0, 305.0), p1: (603.0, 288.0) }) = 6.009005957494535 degrees
* nnUusinh: Quad(QuadBez { p0: (724.5, 566.5), p1: (748.0, 539.0), p2: (749.0, 498.0) })/Quad(QuadBez { p0: (749.0, 498.0), p1: (750.0, 521.0), p2: (761.0, 544.0) }) = 3.886733949295391 degrees
* uni0DAB (U+0DAB): Quad(QuadBez { p0: (618.0, 270.5), p1: (605.0, 286.0), p2: (603.0, 305.0) })/Line(Line { p0: (603.0, 305.0), p1: (603.0, 288.0) }) = 6.009005957494535 degrees
* uni0DAB (U+0DAB): Quad(QuadBez { p0: (724.5, 566.5), p1: (748.0, 539.0), p2: (749.0, 498.0) })/Quad(QuadBez { p0: (749.0, 498.0), p1: (750.0, 521.0), p2: (761.0, 544.0) }) = 3.886733949295391 degrees
* nnddsinh: Quad(QuadBez { p0: (39.0, 365.0), p1: (39.0, 257.0), p2: (80.0, 125.0) })/Quad(QuadBez { p0: (80.0, 125.0), p1: (15.0, 258.0), p2: (15.0, 378.0) }) = 8.790657298396885 degrees
* nnddIsinh: Quad(QuadBez { p0: (47.0, 250.0), p1: (57.0, 190.0), p2: (78.0, 124.0) })/Quad(QuadBez { p0: (78.0, 124.0), p1: (13.0, 259.0), p2: (13.0, 378.0) }) = 8.059829560881148 degrees
* nnddIisinh: Quad(QuadBez { p0: (35.0, 365.0), p1: (35.0, 257.0), p2: (76.0, 125.0) })/Quad(QuadBez { p0: (76.0, 125.0), p1: (12.0, 256.0), p2: (12.0, 378.0) }) = 8.782693283318721 degrees
* nnddUsinh: Quad(QuadBez { p0: (432.0, 39.0), p1: (402.0, 78.0), p2: (399.0, 115.0) })/Quad(QuadBez { p0: (399.0, 115.0), p1: (393.0, 76.0), p2: (362.0, 39.0) }) = 13.381625689457877 degrees
* nnddUsinh: Quad(QuadBez { p0: (38.0, 365.0), p1: (38.0, 258.0), p2: (79.0, 124.0) })/Quad(QuadBez { p0: (79.0, 124.0), p1: (15.0, 256.0), p2: (15.0, 378.0) }) = 8.853809984850473 degrees
* nnddUusinh: Quad(QuadBez { p0: (432.0, 39.0), p1: (402.0, 78.0), p2: (399.0, 115.0) })/Quad(QuadBez { p0: (399.0, 115.0), p1: (393.0, 76.0), p2: (362.0, 39.0) }) = 13.381625689457877 degrees
* nnddUusinh: Quad(QuadBez { p0: (38.0, 365.0), p1: (38.0, 258.0), p2: (79.0, 124.0) })/Quad(QuadBez { p0: (79.0, 124.0), p1: (15.0, 256.0), p2: (15.0, 378.0) }) = 8.853809984850473 degrees
* uni0DAC (U+0DAC): Quad(QuadBez { p0: (432.0, 39.0), p1: (402.0, 78.0), p2: (399.0, 115.0) })/Quad(QuadBez { p0: (399.0, 115.0), p1: (393.0, 76.0), p2: (362.0, 39.0) }) = 13.381625689457877 degrees
* uni0DAC (U+0DAC): Quad(QuadBez { p0: (38.0, 365.0), p1: (38.0, 258.0), p2: (79.0, 124.0) })/Quad(QuadBez { p0: (79.0, 124.0), p1: (15.0, 256.0), p2: (15.0, 378.0) }) = 8.853809984850473 degrees
* nysinh: Quad(QuadBez { p0: (525.0, 478.0), p1: (512.0, 478.0), p2: (501.0, 481.0) })/Quad(QuadBez { p0: (501.0, 481.0), p1: (576.0, 460.0), p2: (631.0, 389.0) }) = 0.38712775415007933 degrees
* nyIsinh: Quad(QuadBez { p0: (524.0, 478.0), p1: (511.0, 478.0), p2: (500.0, 481.0) })/Quad(QuadBez { p0: (500.0, 481.0), p1: (575.0, 460.0), p2: (630.0, 389.0) }) = 0.38712775415007933 degrees
* nyIisinh: Quad(QuadBez { p0: (525.0, 478.0), p1: (512.0, 478.0), p2: (501.0, 481.0) })/Quad(QuadBez { p0: (501.0, 481.0), p1: (576.0, 460.0), p2: (631.0, 389.0) }) = 0.38712775415007933 degrees
* nyUsinh: Quad(QuadBez { p0: (418.0, 101.5), p1: (416.0, 108.0), p2: (415.0, 112.0) })/Quad(QuadBez { p0: (415.0, 112.0), p1: (415.0, 108.0), p2: (413.0, 102.5) }) = 14.036243467926484 degrees
* nyUusinh: Quad(QuadBez { p0: (520.0, 478.0), p1: (507.0, 478.0), p2: (495.0, 481.0) })/Quad(QuadBez { p0: (495.0, 481.0), p1: (571.0, 460.0), p2: (626.0, 389.0) }) = 1.410072899765912 degrees
* uni0DA4 (U+0DA4): Quad(QuadBez { p0: (525.0, 478.0), p1: (512.0, 478.0), p2: (501.0, 481.0) })/Quad(QuadBez { p0: (501.0, 481.0), p1: (576.0, 460.0), p2: (631.0, 389.0) }) = 0.38712775415007933 degrees
* pIsinh: Quad(QuadBez { p0: (429.5, 677.5), p1: (457.0, 698.0), p2: (493.0, 706.0) })/Quad(QuadBez { p0: (493.0, 706.0), p1: (492.0, 706.0), p2: (491.0, 707.0) }) = 12.528807709151492 degrees
* shUusinh: Line(Line { p0: (626.0, -7.0), p1: (693.0, 10.0) })/Line(Line { p0: (693.0, 10.0), p1: (636.0, 10.0) }) = 14.237280465761097 degrees
* shUusinh: Line(Line { p0: (762.0, 10.0), p1: (695.0, -7.0) })/Line(Line { p0: (695.0, -7.0), p1: (793.0, -7.0) }) = 14.237280465761097 degrees
* tVsinh: Quad(QuadBez { p0: (295.5, 453.0), p1: (307.0, 477.0), p2: (329.0, 494.0) })/Quad(QuadBez { p0: (329.0, 494.0), p1: (302.0, 482.0), p2: (271.5, 454.0) }) = 13.731751492111009 degrees
* yasign_iisignsinh: Quad(QuadBez { p0: (271.0, 627.0), p1: (320.0, 694.0), p2: (381.0, 694.0) })/Quad(QuadBez { p0: (381.0, 694.0), p1: (356.0, 698.0), p2: (335.5, 714.0) }) = 9.090276920822351 degrees
* yasign_iisignsinh: Quad(QuadBez { p0: (448.5, 712.0), p1: (426.0, 693.0), p2: (397.0, 693.0) })/Quad(QuadBez { p0: (397.0, 693.0), p1: (415.0, 690.0), p2: (431.0, 678.0) }) = 9.462322208025613 degrees
* uni0D8E (U+0D8E): Quad(QuadBez { p0: (1145.5, 461.5), p1: (1152.0, 450.0), p2: (1159.0, 442.0) })/Quad(QuadBez { p0: (1159.0, 442.0), p1: (1153.0, 447.0), p2: (1136.0, 464.0) }) = 9.00850374202515 degrees [code: found-jaggy-segments]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Check there are no overlapping path segments (overlapping_path_segments)</summary>
    <div>








- ⚠️ **WARN** The following glyphs have overlapping path segments:

* ddhIisinh: Quad(QuadBez { p0: (346.0, 823.0), p1: (346.0, 823.0), p2: (346.0, 823.0) }) has the same coordinates as a previous segment.
* ddhIisinh: Quad(QuadBez { p0: (346.0, 823.0), p1: (346.0, 823.0), p2: (346.0, 823.0) }) has the same coordinates as a previous segment.
* jIisinh: Line(Line { p0: (481.0, 705.0), p1: (481.0, 705.0) }) has the same coordinates as a previous segment.
* jRIisinh: Line(Line { p0: (481.0, 705.0), p1: (481.0, 705.0) }) has the same coordinates as a previous segment.
* nyjIisinh: Line(Line { p0: (585.0, 705.0), p1: (585.0, 705.0) }) has the same coordinates as a previous segment.
* tThIsinh: Line(Line { p0: (913.0, 556.0), p1: (913.0, 556.0) }) has the same coordinates as a previous segment.
* tThIsinh: Line(Line { p0: (894.0, 802.0), p1: (894.0, 802.0) }) has the same coordinates as a previous segment.
* tThIisinh: Quad(QuadBez { p0: (895.0, 823.0), p1: (895.0, 823.0), p2: (895.0, 823.0) }) has the same coordinates as a previous segment.
* thIisinh: Quad(QuadBez { p0: (320.0, 823.0), p1: (320.0, 823.0), p2: (320.0, 823.0) }) has the same coordinates as a previous segment.
* tthIisinh: Quad(QuadBez { p0: (346.0, 823.0), p1: (346.0, 823.0), p2: (346.0, 823.0) }) has the same coordinates as a previous segment.
* tthIisinh: Quad(QuadBez { p0: (346.0, 823.0), p1: (346.0, 823.0), p2: (346.0, 823.0) }) has the same coordinates as a previous segment.
* yasign_viramasinh: Line(Line { p0: (442.0, 594.0), p1: (442.0, 594.0) }) has the same coordinates as a previous segment.
* yasign_iisignsinh: Quad(QuadBez { p0: (192.0, 715.0), p1: (192.0, 715.0), p2: (192.0, 715.0) }) has the same coordinates as a previous segment. [code: overlapping-path-segments]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Do outlines contain any semi-vertical or semi-horizontal lines? (outline_semi_vertical)</summary>
    <div>








- ⚠️ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

* cIisinh: Line(Line { p0: (16.0, 389.0), p1: (17.0, 562.0) }) (angle: 89.67 degrees, expected: 90.00 degrees)
* cIisinh: Line(Line { p0: (17.0, 562.0), p1: (282.0, 561.0) }) (angle: -0.22 degrees, expected: 0.00 degrees)
* cRIisinh: Line(Line { p0: (16.0, 389.0), p1: (17.0, 562.0) }) (angle: 89.67 degrees, expected: 90.00 degrees)
* cRIisinh: Line(Line { p0: (17.0, 562.0), p1: (282.0, 561.0) }) (angle: -0.22 degrees, expected: 0.00 degrees)
* rAaesinh: Line(Line { p0: (877.0, 788.0), p1: (878.0, 666.0) }) (angle: -89.53 degrees, expected: -90.00 degrees)
* rAaesinh: Line(Line { p0: (607.0, 426.0), p1: (606.0, 571.0) }) (angle: 90.40 degrees, expected: 90.00 degrees) [code: found-semi-vertical]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (googlefonts/meta/script_lang_tags)</summary>
    <div>








- ⚠️ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Description strings in the name table must not exceed 200 characters. (googlefonts/name/description_max_length)</summary>
    <div>








- ⚠️ **WARN** A few name table entries with ID=10 (NameID.DESCRIPTION) are longer than 200 characters. Please check whether those entries are copyright notices mistakenly stored in the description string entries by a bug in an old FontLab version. If that's the case, then such copyright notices must be removed from these entries. [code: too-long]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Checking OS/2 achVendID. (googlefonts/vendor_id)</summary>
    <div>








- ⚠️ **WARN** OS/2 VendorID value 'MNIK' is not yet recognized.
If you registered it recently, then it's safe to ignore this warning message. Otherwise, you should set it to your own unique 4 character code, and register it with Microsoft at https://www.microsoft.com/typography/links/vendorlist.aspx
 [code: unknown]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Check font follows the Google Fonts vertical metric schema (googlefonts/vertical_metrics)</summary>
    <div>








- ⚠️ **WARN** We recommend the absolute sum of the hhea metrics should be between 1.2-1.5x of the font's upm. This font has 1.544x (1544) [code: bad-hhea-range]
  
  

</div>
</details>


</div>
</details>


<details><summary>[3] fonts/ttf</summary>
<div>


<details>
    <summary>🔥 <b>FAIL</b> Check Google Fonts glyph coverage. (googlefonts/glyph_coverage)</summary>
    <div>








- 🔥 **FAIL** fonts/ttf/MottaTypeOneCANARY-Regular.ttf missing required codepoints:

* 0x003A: COLON
* 0x003B: SEMICOLON
* 0x003C: LESS-THAN SIGN
* 0x003D: EQUALS SIGN
* 0x003E: GREATER-THAN SIGN
* 0x003F: QUESTION MARK
* 0x0040: COMMERCIAL AT
* 0x0041: LATIN CAPITAL LETTER A
* 0x0042: LATIN CAPITAL LETTER B
* 0x0043: LATIN CAPITAL LETTER C
* 0x0044: LATIN CAPITAL LETTER D
* 0x0045: LATIN CAPITAL LETTER E
* 0x0046: LATIN CAPITAL LETTER F
* 0x0047: LATIN CAPITAL LETTER G
* 0x0048: LATIN CAPITAL LETTER H
* 0x0049: LATIN CAPITAL LETTER I
* 0x004A: LATIN CAPITAL LETTER J
* 0x004B: LATIN CAPITAL LETTER K
* 0x004C: LATIN CAPITAL LETTER L
* 0x004D: LATIN CAPITAL LETTER M
* 0x004E: LATIN CAPITAL LETTER N
* 0x004F: LATIN CAPITAL LETTER O
* 0x0050: LATIN CAPITAL LETTER P
* 0x0051: LATIN CAPITAL LETTER Q
* 0x0052: LATIN CAPITAL LETTER R
* 0x0053: LATIN CAPITAL LETTER S
* 0x0054: LATIN CAPITAL LETTER T
* 0x0055: LATIN CAPITAL LETTER U
* 0x0056: LATIN CAPITAL LETTER V
* 0x0057: LATIN CAPITAL LETTER W
* 0x0058: LATIN CAPITAL LETTER X
* 0x0059: LATIN CAPITAL LETTER Y
* 0x005A: LATIN CAPITAL LETTER Z
* 0x005B: LEFT SQUARE BRACKET
* 0x005C: REVERSE SOLIDUS
* 0x005D: RIGHT SQUARE BRACKET
* 0x005E: CIRCUMFLEX ACCENT
* 0x005F: LOW LINE
* 0x0060: GRAVE ACCENT
* 0x0061: LATIN SMALL LETTER A
* 0x0062: LATIN SMALL LETTER B
* 0x0063: LATIN SMALL LETTER C
* 0x0064: LATIN SMALL LETTER D
* 0x0065: LATIN SMALL LETTER E
* 0x0066: LATIN SMALL LETTER F
* 0x0067: LATIN SMALL LETTER G
* 0x0068: LATIN SMALL LETTER H
* 0x0069: LATIN SMALL LETTER I
* 0x006A: LATIN SMALL LETTER J
* 0x006B: LATIN SMALL LETTER K
* 0x006C: LATIN SMALL LETTER L
* 0x006D: LATIN SMALL LETTER M
* 0x006E: LATIN SMALL LETTER N
* 0x006F: LATIN SMALL LETTER O
* 0x0070: LATIN SMALL LETTER P
* 0x0071: LATIN SMALL LETTER Q
* 0x0072: LATIN SMALL LETTER R
* 0x0073: LATIN SMALL LETTER S
* 0x0074: LATIN SMALL LETTER T
* 0x0075: LATIN SMALL LETTER U
* 0x0076: LATIN SMALL LETTER V
* 0x0077: LATIN SMALL LETTER W
* 0x0078: LATIN SMALL LETTER X
* 0x0079: LATIN SMALL LETTER Y
* 0x007A: LATIN SMALL LETTER Z
* 0x007B: LEFT CURLY BRACKET
* 0x007C: VERTICAL LINE
* 0x007D: RIGHT CURLY BRACKET
* 0x007E: TILDE
* 0x00A1: INVERTED EXCLAMATION MARK
* 0x00A2: CENT SIGN
* 0x00A3: POUND SIGN
* 0x00A5: YEN SIGN
* 0x00A7: SECTION SIGN
* 0x00A8: DIAERESIS
* 0x00A9: COPYRIGHT SIGN
* 0x00AA: FEMININE ORDINAL INDICATOR
* 0x00AB: LEFT-POINTING DOUBLE ANGLE QUOTATION MARK
* 0x00AE: REGISTERED SIGN
* 0x00AF: MACRON
* 0x00B0: DEGREE SIGN
* 0x00B4: ACUTE ACCENT
* 0x00B6: PILCROW SIGN
* 0x00B7: MIDDLE DOT
* 0x00B8: CEDILLA
* 0x00BA: MASCULINE ORDINAL INDICATOR
* 0x00BB: RIGHT-POINTING DOUBLE ANGLE QUOTATION MARK
* 0x00BF: INVERTED QUESTION MARK
* 0x00C0: LATIN CAPITAL LETTER A WITH GRAVE
* 0x00C1: LATIN CAPITAL LETTER A WITH ACUTE
* 0x00C2: LATIN CAPITAL LETTER A WITH CIRCUMFLEX
* 0x00C3: LATIN CAPITAL LETTER A WITH TILDE
* 0x00C4: LATIN CAPITAL LETTER A WITH DIAERESIS
* 0x00C5: LATIN CAPITAL LETTER A WITH RING ABOVE
* 0x00C6: LATIN CAPITAL LETTER AE
* 0x00C7: LATIN CAPITAL LETTER C WITH CEDILLA
* 0x00C8: LATIN CAPITAL LETTER E WITH GRAVE
* 0x00C9: LATIN CAPITAL LETTER E WITH ACUTE
* 0x00CA: LATIN CAPITAL LETTER E WITH CIRCUMFLEX
* 0x00CB: LATIN CAPITAL LETTER E WITH DIAERESIS
* 0x00CC: LATIN CAPITAL LETTER I WITH GRAVE
* 0x00CD: LATIN CAPITAL LETTER I WITH ACUTE
* 0x00CE: LATIN CAPITAL LETTER I WITH CIRCUMFLEX
* 0x00CF: LATIN CAPITAL LETTER I WITH DIAERESIS
* 0x00D0: LATIN CAPITAL LETTER ETH
* 0x00D1: LATIN CAPITAL LETTER N WITH TILDE
* 0x00D2: LATIN CAPITAL LETTER O WITH GRAVE
* 0x00D3: LATIN CAPITAL LETTER O WITH ACUTE
* 0x00D4: LATIN CAPITAL LETTER O WITH CIRCUMFLEX
* 0x00D5: LATIN CAPITAL LETTER O WITH TILDE
* 0x00D6: LATIN CAPITAL LETTER O WITH DIAERESIS
* 0x00D7: MULTIPLICATION SIGN
* 0x00D8: LATIN CAPITAL LETTER O WITH STROKE
* 0x00D9: LATIN CAPITAL LETTER U WITH GRAVE
* 0x00DA: LATIN CAPITAL LETTER U WITH ACUTE
* 0x00DB: LATIN CAPITAL LETTER U WITH CIRCUMFLEX
* 0x00DC: LATIN CAPITAL LETTER U WITH DIAERESIS
* 0x00DD: LATIN CAPITAL LETTER Y WITH ACUTE
* 0x00DE: LATIN CAPITAL LETTER THORN
* 0x00DF: LATIN SMALL LETTER SHARP S
* 0x00E0: LATIN SMALL LETTER A WITH GRAVE
* 0x00E1: LATIN SMALL LETTER A WITH ACUTE
* 0x00E2: LATIN SMALL LETTER A WITH CIRCUMFLEX
* 0x00E3: LATIN SMALL LETTER A WITH TILDE
* 0x00E4: LATIN SMALL LETTER A WITH DIAERESIS
* 0x00E5: LATIN SMALL LETTER A WITH RING ABOVE
* 0x00E6: LATIN SMALL LETTER AE
* 0x00E7: LATIN SMALL LETTER C WITH CEDILLA
* 0x00E8: LATIN SMALL LETTER E WITH GRAVE
* 0x00E9: LATIN SMALL LETTER E WITH ACUTE
* 0x00EA: LATIN SMALL LETTER E WITH CIRCUMFLEX
* 0x00EB: LATIN SMALL LETTER E WITH DIAERESIS
* 0x00EC: LATIN SMALL LETTER I WITH GRAVE
* 0x00ED: LATIN SMALL LETTER I WITH ACUTE
* 0x00EE: LATIN SMALL LETTER I WITH CIRCUMFLEX
* 0x00EF: LATIN SMALL LETTER I WITH DIAERESIS
* 0x00F0: LATIN SMALL LETTER ETH
* 0x00F1: LATIN SMALL LETTER N WITH TILDE
* 0x00F2: LATIN SMALL LETTER O WITH GRAVE
* 0x00F3: LATIN SMALL LETTER O WITH ACUTE
* 0x00F4: LATIN SMALL LETTER O WITH CIRCUMFLEX
* 0x00F5: LATIN SMALL LETTER O WITH TILDE
* 0x00F6: LATIN SMALL LETTER O WITH DIAERESIS
* 0x00F7: DIVISION SIGN
* 0x00F8: LATIN SMALL LETTER O WITH STROKE
* 0x00F9: LATIN SMALL LETTER U WITH GRAVE
* 0x00FA: LATIN SMALL LETTER U WITH ACUTE
* 0x00FB: LATIN SMALL LETTER U WITH CIRCUMFLEX
* 0x00FC: LATIN SMALL LETTER U WITH DIAERESIS
* 0x00FD: LATIN SMALL LETTER Y WITH ACUTE
* 0x00FE: LATIN SMALL LETTER THORN
* 0x00FF: LATIN SMALL LETTER Y WITH DIAERESIS
* 0x0100: LATIN CAPITAL LETTER A WITH MACRON
* 0x0101: LATIN SMALL LETTER A WITH MACRON
* 0x0102: LATIN CAPITAL LETTER A WITH BREVE
* 0x0103: LATIN SMALL LETTER A WITH BREVE
* 0x0104: LATIN CAPITAL LETTER A WITH OGONEK
* 0x0105: LATIN SMALL LETTER A WITH OGONEK
* 0x0106: LATIN CAPITAL LETTER C WITH ACUTE
* 0x0107: LATIN SMALL LETTER C WITH ACUTE
* 0x010A: LATIN CAPITAL LETTER C WITH DOT ABOVE
* 0x010B: LATIN SMALL LETTER C WITH DOT ABOVE
* 0x010C: LATIN CAPITAL LETTER C WITH CARON
* 0x010D: LATIN SMALL LETTER C WITH CARON
* 0x010E: LATIN CAPITAL LETTER D WITH CARON
* 0x010F: LATIN SMALL LETTER D WITH CARON
* 0x0110: LATIN CAPITAL LETTER D WITH STROKE
* 0x0111: LATIN SMALL LETTER D WITH STROKE
* 0x0112: LATIN CAPITAL LETTER E WITH MACRON
* 0x0113: LATIN SMALL LETTER E WITH MACRON
* 0x0116: LATIN CAPITAL LETTER E WITH DOT ABOVE
* 0x0117: LATIN SMALL LETTER E WITH DOT ABOVE
* 0x0118: LATIN CAPITAL LETTER E WITH OGONEK
* 0x0119: LATIN SMALL LETTER E WITH OGONEK
* 0x011A: LATIN CAPITAL LETTER E WITH CARON
* 0x011B: LATIN SMALL LETTER E WITH CARON
* 0x011E: LATIN CAPITAL LETTER G WITH BREVE
* 0x011F: LATIN SMALL LETTER G WITH BREVE
* 0x0120: LATIN CAPITAL LETTER G WITH DOT ABOVE
* 0x0121: LATIN SMALL LETTER G WITH DOT ABOVE
* 0x0122: LATIN CAPITAL LETTER G WITH CEDILLA
* 0x0123: LATIN SMALL LETTER G WITH CEDILLA
* 0x0126: LATIN CAPITAL LETTER H WITH STROKE
* 0x0127: LATIN SMALL LETTER H WITH STROKE
* 0x012A: LATIN CAPITAL LETTER I WITH MACRON
* 0x012B: LATIN SMALL LETTER I WITH MACRON
* 0x012E: LATIN CAPITAL LETTER I WITH OGONEK
* 0x012F: LATIN SMALL LETTER I WITH OGONEK
* 0x0130: LATIN CAPITAL LETTER I WITH DOT ABOVE
* 0x0131: LATIN SMALL LETTER DOTLESS I
* 0x0136: LATIN CAPITAL LETTER K WITH CEDILLA
* 0x0137: LATIN SMALL LETTER K WITH CEDILLA
* 0x0139: LATIN CAPITAL LETTER L WITH ACUTE
* 0x013A: LATIN SMALL LETTER L WITH ACUTE
* 0x013B: LATIN CAPITAL LETTER L WITH CEDILLA
* 0x013C: LATIN SMALL LETTER L WITH CEDILLA
* 0x013D: LATIN CAPITAL LETTER L WITH CARON
* 0x013E: LATIN SMALL LETTER L WITH CARON
* 0x0141: LATIN CAPITAL LETTER L WITH STROKE
* 0x0142: LATIN SMALL LETTER L WITH STROKE
* 0x0143: LATIN CAPITAL LETTER N WITH ACUTE
* 0x0144: LATIN SMALL LETTER N WITH ACUTE
* 0x0145: LATIN CAPITAL LETTER N WITH CEDILLA
* 0x0146: LATIN SMALL LETTER N WITH CEDILLA
* 0x0147: LATIN CAPITAL LETTER N WITH CARON
* 0x0148: LATIN SMALL LETTER N WITH CARON
* 0x0150: LATIN CAPITAL LETTER O WITH DOUBLE ACUTE
* 0x0151: LATIN SMALL LETTER O WITH DOUBLE ACUTE
* 0x0152: LATIN CAPITAL LIGATURE OE
* 0x0153: LATIN SMALL LIGATURE OE
* 0x0154: LATIN CAPITAL LETTER R WITH ACUTE
* 0x0155: LATIN SMALL LETTER R WITH ACUTE
* 0x0158: LATIN CAPITAL LETTER R WITH CARON
* 0x0159: LATIN SMALL LETTER R WITH CARON
* 0x015A: LATIN CAPITAL LETTER S WITH ACUTE
* 0x015B: LATIN SMALL LETTER S WITH ACUTE
* 0x015E: LATIN CAPITAL LETTER S WITH CEDILLA
* 0x015F: LATIN SMALL LETTER S WITH CEDILLA
* 0x0160: LATIN CAPITAL LETTER S WITH CARON
* 0x0161: LATIN SMALL LETTER S WITH CARON
* 0x0164: LATIN CAPITAL LETTER T WITH CARON
* 0x0165: LATIN SMALL LETTER T WITH CARON
* 0x016A: LATIN CAPITAL LETTER U WITH MACRON
* 0x016B: LATIN SMALL LETTER U WITH MACRON
* 0x016E: LATIN CAPITAL LETTER U WITH RING ABOVE
* 0x016F: LATIN SMALL LETTER U WITH RING ABOVE
* 0x0170: LATIN CAPITAL LETTER U WITH DOUBLE ACUTE
* 0x0171: LATIN SMALL LETTER U WITH DOUBLE ACUTE
* 0x0172: LATIN CAPITAL LETTER U WITH OGONEK
* 0x0173: LATIN SMALL LETTER U WITH OGONEK
* 0x0174: LATIN CAPITAL LETTER W WITH CIRCUMFLEX
* 0x0175: LATIN SMALL LETTER W WITH CIRCUMFLEX
* 0x0176: LATIN CAPITAL LETTER Y WITH CIRCUMFLEX
* 0x0177: LATIN SMALL LETTER Y WITH CIRCUMFLEX
* 0x0178: LATIN CAPITAL LETTER Y WITH DIAERESIS
* 0x0179: LATIN CAPITAL LETTER Z WITH ACUTE
* 0x017A: LATIN SMALL LETTER Z WITH ACUTE
* 0x017B: LATIN CAPITAL LETTER Z WITH DOT ABOVE
* 0x017C: LATIN SMALL LETTER Z WITH DOT ABOVE
* 0x017D: LATIN CAPITAL LETTER Z WITH CARON
* 0x017E: LATIN SMALL LETTER Z WITH CARON
* 0x0218: LATIN CAPITAL LETTER S WITH COMMA BELOW
* 0x0219: LATIN SMALL LETTER S WITH COMMA BELOW
* 0x021A: LATIN CAPITAL LETTER T WITH COMMA BELOW
* 0x021B: LATIN SMALL LETTER T WITH COMMA BELOW
* 0x0237: LATIN SMALL LETTER DOTLESS J
* 0x02C6: MODIFIER LETTER CIRCUMFLEX ACCENT
* 0x02C7: CARON
* 0x02D8: BREVE
* 0x02D9: DOT ABOVE
* 0x02DA: RING ABOVE
* 0x02DB: OGONEK
* 0x02DC: SMALL TILDE
* 0x02DD: DOUBLE ACUTE ACCENT
* 0x0300: COMBINING GRAVE ACCENT
* 0x0301: COMBINING ACUTE ACCENT
* 0x0302: COMBINING CIRCUMFLEX ACCENT
* 0x0303: COMBINING TILDE
* 0x0304: COMBINING MACRON
* 0x0306: COMBINING BREVE
* 0x0307: COMBINING DOT ABOVE
* 0x0308: COMBINING DIAERESIS
* 0x030A: COMBINING RING ABOVE
* 0x030B: COMBINING DOUBLE ACUTE ACCENT
* 0x030C: COMBINING CARON
* 0x0326: COMBINING COMMA BELOW
* 0x0327: COMBINING CEDILLA
* 0x0328: COMBINING OGONEK
* 0x1E80: LATIN CAPITAL LETTER W WITH GRAVE
* 0x1E81: LATIN SMALL LETTER W WITH GRAVE
* 0x1E82: LATIN CAPITAL LETTER W WITH ACUTE
* 0x1E83: LATIN SMALL LETTER W WITH ACUTE
* 0x1E84: LATIN CAPITAL LETTER W WITH DIAERESIS
* 0x1E85: LATIN SMALL LETTER W WITH DIAERESIS
* 0x1E9E: LATIN CAPITAL LETTER SHARP S
* 0x1EF2: LATIN CAPITAL LETTER Y WITH GRAVE
* 0x1EF3: LATIN SMALL LETTER Y WITH GRAVE
* 0x2013: EN DASH
* 0x2014: EM DASH
* 0x2018: LEFT SINGLE QUOTATION MARK
* 0x2019: RIGHT SINGLE QUOTATION MARK
* 0x201A: SINGLE LOW-9 QUOTATION MARK
* 0x201C: LEFT DOUBLE QUOTATION MARK
* 0x201D: RIGHT DOUBLE QUOTATION MARK
* 0x201E: DOUBLE LOW-9 QUOTATION MARK
* 0x2022: BULLET
* 0x2026: HORIZONTAL ELLIPSIS
* 0x2039: SINGLE LEFT-POINTING ANGLE QUOTATION MARK
* 0x203A: SINGLE RIGHT-POINTING ANGLE QUOTATION MARK
* 0x20AC: EURO SIGN
* 0x2122: TRADE MARK SIGN
* 0x2212: MINUS SIGN [code: missing-codepoints]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Ensure Fonts have 'ital' STAT axis. (opentype/STAT/ital_axis)</summary>
    <div>








- ⚠️ **WARN** Static font is missing the 'STAT' table. [code: no-stat-table]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Check for codepoints not covered by METADATA subsets. (googlefonts/metadata/unreachable_subsetting)</summary>
    <div>








- ⚠️ **WARN** fonts/ttf/MottaTypeOneCANARY-Regular.ttf: The following codepoints supported by the font are not covered by any subsets defined in the font's metadata file, and will never be served. You can solve this by either manually adding additional subset declarations to METADATA.pb, or by editing the glyphset definitions.

* U+0021 EXCLAMATION MARK: try adding one of: khmer, latin, adlam, gunjala-gondi, math, syriac, thaana, masaram-gondi, cham, mongolian
* U+0022 QUOTATION MARK: try adding one of: latin, adlam, wancho, mongolian, cham, math, khmer, masaram-gondi
* U+0023 NUMBER SIGN: try adding one of: math, adlam, latin, symbols, khmer
* U+0024 DOLLAR SIGN: try adding one of: latin, khmer, math, adlam
* U+0025 PERCENT SIGN: try adding one of: adlam, masaram-gondi, gunjala-gondi, khmer, latin, math
* U+0026 AMPERSAND: try adding one of: khmer, math, adlam, latin
* U+0027 APOSTROPHE: try adding one of: gunjala-gondi, cham, adlam, math, warang-citi, khmer, latin, masaram-gondi, wancho
* U+0028 LEFT PARENTHESIS: try adding one of: adlam, math, mongolian, gunjala-gondi, thaana, latin, wancho, syriac, masaram-gondi, cham, khmer
* U+0029 RIGHT PARENTHESIS: try adding one of: adlam, latin, khmer, syriac, gunjala-gondi, cham, thaana, masaram-gondi, mongolian, math, wancho
* U+002A ASTERISK: try adding one of: adlam, syriac, math, latin, khmer, masaram-gondi, gunjala-gondi, symbols
* U+002B PLUS SIGN: try adding one of: math, syriac, masaram-gondi, gunjala-gondi, adlam, khmer, latin
* U+002C COMMA: try adding one of: math, thaana, khmer, masaram-gondi, gunjala-gondi, coptic, latin, adlam, cham, nushu, wancho
* U+002D HYPHEN-MINUS: try adding one of: latin, sora-sompeng, math, armenian, cham, sundanese, wancho, lisu, kaithi, kayah-li, syriac, khmer, hebrew, adlam, kharoshthi, mongolian, gunjala-gondi, coptic, masaram-gondi, nushu
* U+002E FULL STOP: try adding one of: khmer, thaana, avestan, syriac, latin, coptic, adlam, math, cham, masaram-gondi, gunjala-gondi, nushu, wancho
* U+002F SOLIDUS: try adding one of: syriac, wancho, cham, khmer, adlam, gunjala-gondi, masaram-gondi, math, latin
* U+0030 DIGIT ZERO: try adding one of: latin, khmer, math, nushu, symbols
* U+0031 DIGIT ONE: try adding one of: latin, math, khmer, nushu, symbols
* U+0032 DIGIT TWO: try adding one of: khmer, latin, math, nushu, symbols
* U+0033 DIGIT THREE: try adding one of: nushu, latin, math, symbols, khmer
* U+0034 DIGIT FOUR: try adding one of: latin, symbols, math, khmer, nushu
* U+0035 DIGIT FIVE: try adding one of: latin, nushu, symbols, khmer, math
* U+0036 DIGIT SIX: try adding one of: latin, nushu, symbols, math, khmer
* U+0037 DIGIT SEVEN: try adding one of: latin, math, symbols, nushu, khmer
* U+0038 DIGIT EIGHT: try adding one of: khmer, symbols, nushu, math, latin
* U+0039 DIGIT NINE: try adding one of: latin, nushu, symbols, math, khmer

Or you can add the above codepoints to one of the subsets supported by the font: sinhala [code: unreachable-subsetting]
  
  

</div>
</details>


</div>
</details>






### Summary

| 🔥 FAIL | ⚠️ WARN | ℹ️ INFO | ✅ PASS | ⏩ SKIP | 
| ---|---|---|---|---|
| 5 | 17 | 20 | 94 | 86 | 
| 2% | 8% | 9% | 42% | 39% | 



