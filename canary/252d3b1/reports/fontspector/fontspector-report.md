## FontSpector report

fontspector version: 1.9.0






## Check results




<details><summary>[17] fonts/ttf/MottaTypeOneCANARY-Regular.ttf</summary>
<div>


<details>
    <summary>🔥 <b>FAIL</b> Shapes languages in all GF glyphsets. (googlefonts/glyphsets/shape_languages)</summary>
    <div>








- 🔥 **FAIL** No GF glyphset was found to be supported >80%, so language shaping support couldn't get checked. [code: no-glyphset-supported]
  
  

</div>
</details>





<details>
    <summary>🔥 <b>FAIL</b> Directory name in GFonts repo structure must
    match NameID 1 of the regular. (googlefonts/repo/dirname_matches_nameid_1)</summary>
    <div>








- 🔥 **FAIL** Family name on the name table ('Motta Type One CANARY') does not match directory name in the repo structure ('ttf'). Expected 'mottatypeonecanary'. [code: mismatch]
  
  

</div>
</details>





<details>
    <summary>🔥 <b>FAIL</b> Ensure font can render its own name. (googlefonts/render_own_name)</summary>
    <div>








- 🔥 **FAIL** .notdef glyphs were found when attempting to render Motta Type One CANARY [code: render-own-name]
  
  

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
    <summary>⚠️ <b>WARN</b> Check font contains no unreachable glyphs (unreachable_glyphs)</summary>
    <div>








- ⚠️ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

* isignsinh.alt3 [code: unreachable-glyphs]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Ensure font has overlaps bit set correctly. (overlaps_bit)</summary>
    <div>








- ⚠️ **WARN** The following glyphs have overlaps but the overlaps bit is not set:
* cUusinh
* nsinh
* phsinh
* chUsinh
* kSsUusinh
* kIisinh
* fRasinh
* vUusinh
* hRIisinh
* jnysinh
* bUsinh
* tthUusinh
* phUusinh
* fsinh
* gIsinh
* mUusinh
* nngUusinh
* yUsinh
* jRIsinh
* hRsinh
* kSssinh
* bRsinh
* shUsinh
* tRIisinh
* kSsUsinh
* nIsinh
* ssinh
* ddRasinh
* bRasinh
* sRIsinh
* tthsinh
* cRIisinh
* bhIsinh
* bhIisinh
* sRasinh
* tsinh
* ttRIisinh
* phUsinh
* bhRasinh
* pRasinh
* kIsinh
* dhRIisinh
* jhUusinh
* nUsinh
* ssRIisinh
* jUusinh
* ghsinh
* ssUusinh
* ghIsinh
* ghRIsinh
* ttRasinh
* bhRIsinh
* ghRasinh
* jhRasinh
* tRIsinh
* ddRsinh
* bhRsinh
* mRasinh
* uni0DDD (U+0DDD)
* ndsinh
* shRIisinh
* nIisinh
* tIisinh
* ttUsinh
* nnUusinh
* vRIisinh
* vRasinh
* llsinh
* vUsinh
* jRsinh
* khRIsinh
* jhUsinh
* fUusinh
* bhRIisinh
* chUusinh
* ysinh
* pRIsinh
* shsinh
* thUsinh
* ghRIisinh
* bhsinh
* kSsIsinh
* kRasinh
* mbUusinh
* cRIsinh
* gUsinh
* dhUsinh
* jUsinh
* dhRsinh
* sIsinh
* nysinh
* ttUusinh
* fRIsinh
* ssUsinh
* tIsinh
* khRIisinh
* jhRIsinh
* ssRsinh
* tRasinh
* cRsinh
* dsinh
* ddhUusinh
* hRIsinh
* khUusinh
* kRIsinh
* sIisinh
* nDsinh
* vRIsinh
* cUsinh
* ddRIisinh
* ssIisinh
* lsinh
* ssRasinh
* jhRIisinh
* tUusinh
* ghIisinh
* bRIisinh
* bRIsinh
* khUsinh
* pRIisinh
* tRsinh
* hsinh
* kRIisinh
* hUusinh
* uni0D92 (U+0D92)
* sUusinh
* dhRIsinh
* bUusinh
* dhRasinh
* pRsinh
* sRIisinh
* ssIsinh
* ddRIsinh
* khRsinh
* thUusinh
* tthUsinh
* ttRIsinh
* psinh
* fRsinh
* pUusinh
* shIisinh
* dRsinh
* sRsinh
* ssRIsinh
* hUsinh
* vRsinh
* shRasinh
* uni0DF4 (U+0DF4)
* dhUusinh
* gRIsinh
* ddhsinh
* ksinh
* shRIsinh
* gsinh
* kUusinh
* mbUsinh
* khRasinh
* jRIisinh
* hRasinh
* cRasinh
* kSsIisinh
* fUsinh
* jRasinh
* gRIisinh
* shRsinh
* sssinh
* ddUusinh
* gRasinh
* tUsinh
* ttRsinh
* gRsinh
* shIsinh
* thsinh
* gUusinh
* hIsinh
* nUusinh [code: no-overlaps-bit]
  
  

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

* dDhUusinh: from (335.0, -55.0) to (327.0, -68.0) is colinear with segment from (327.0, -68.0) to (320.0, -78.0)
* ghUusinh: from (253.0, -55.0) to (245.0, -68.0) is colinear with segment from (245.0, -68.0) to (238.0, -78.0)
* jhIisinh: from (731.0, 216.0) to (758.0, 217.0) is colinear with segment from (758.0, 217.0) to (785.0, 217.0)
* jhRIisinh: from (731.0, 216.0) to (758.0, 217.0) is colinear with segment from (758.0, 217.0) to (785.0, 217.0)
* kVUusinh: from (734.0, -55.0) to (726.0, -68.0) is colinear with segment from (726.0, -68.0) to (719.0, -78.0)
* nDhsinh: from (708.0, 220.0) to (735.0, 221.0) is colinear with segment from (735.0, 221.0) to (762.0, 222.0)
* nDhIisinh: from (717.0, 216.0) to (744.0, 217.0) is colinear with segment from (744.0, 217.0) to (771.0, 217.0)
* nyjUusinh: from (356.0, -57.0) to (348.0, -70.0) is colinear with segment from (348.0, -70.0) to (341.0, -80.0)
* rIisinh: from (126.0, 403.0) to (126.0, 403.0) is colinear with segment from (126.0, 403.0) to (126.0, 403.0)
* tThUusinh: from (689.0, -46.0) to (681.0, -59.0) is colinear with segment from (681.0, -59.0) to (674.0, -69.0)
* tVUusinh: from (677.0, -56.0) to (669.0, -69.0) is colinear with segment from (669.0, -69.0) to (662.0, -79.0)
* uni0D8F (U+0D8F): from (446.0, 538.0) to (446.0, 538.0) is colinear with segment from (446.0, 538.0) to (446.0, 538.0)
* uni0D90 (U+0D90): from (446.0, 538.0) to (446.0, 538.0) is colinear with segment from (446.0, 538.0) to (446.0, 538.0) [code: found-colinear-vectors]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Check the direction of the outermost contour in each glyph (outline_direction)</summary>
    <div>








- ⚠️ **WARN** The following glyphs have a counter-clockwise outer contour:

* ddhIisinh has a path with no bounds (probably a single point)
* phIisinh has a path with no bounds (probably a single point)
* tThIisinh has a path with no bounds (probably a single point)
* thIisinh has a path with no bounds (probably a single point)
* tthIisinh has a path with no bounds (probably a single point) [code: ccw-outer-contour]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Do outlines contain any jaggy segments? (outline_jaggy_segments)</summary>
    <div>








- ⚠️ **WARN** The following glyphs have jaggy segments:

* uni0D85 (U+0D85): Quad(QuadBez { p0: (377.0, 315.5), p1: (371.0, 331.0), p2: (370.0, 337.0) })/Quad(QuadBez { p0: (370.0, 337.0), p1: (370.0, 297.0), p2: (370.5, 257.5) }) = 9.462322208025574 degrees
* uni0D86 (U+0D86): Quad(QuadBez { p0: (377.0, 315.5), p1: (371.0, 331.0), p2: (370.0, 337.0) })/Quad(QuadBez { p0: (370.0, 337.0), p1: (370.0, 297.0), p2: (370.5, 257.5) }) = 9.462322208025574 degrees
* uni0D88 (U+0D88): Quad(QuadBez { p0: (377.0, 315.5), p1: (371.0, 331.0), p2: (370.0, 337.0) })/Quad(QuadBez { p0: (370.0, 337.0), p1: (370.0, 297.0), p2: (370.5, 257.5) }) = 9.462322208025574 degrees
* uni0D87 (U+0D87): Quad(QuadBez { p0: (377.0, 315.5), p1: (371.0, 331.0), p2: (370.0, 337.0) })/Quad(QuadBez { p0: (370.0, 337.0), p1: (370.0, 297.0), p2: (370.5, 257.5) }) = 9.462322208025574 degrees
* uni0D93 (U+0D93): Quad(QuadBez { p0: (696.0, 464.5), p1: (672.0, 474.0), p2: (649.0, 493.0) })/Quad(QuadBez { p0: (649.0, 493.0), p1: (666.0, 470.0), p2: (671.0, 446.0) }) = 13.97109764095363 degrees
* bhUusinh: Line(Line { p0: (541.0, 8.0), p1: (489.0, -5.0) })/Line(Line { p0: (489.0, -5.0), p1: (565.0, -5.0) }) = 14.036243467926457 degrees
* cRasinh: Quad(QuadBez { p0: (73.5, 517.0), p1: (87.0, 527.0), p2: (108.0, 530.0) })/Line(Line { p0: (108.0, 530.0), p1: (107.0, 530.0) }) = 8.130102354156005 degrees
* cUsinh: Quad(QuadBez { p0: (73.5, 517.0), p1: (87.0, 527.0), p2: (108.0, 530.0) })/Line(Line { p0: (108.0, 530.0), p1: (107.0, 530.0) }) = 8.130102354156005 degrees
* cUusinh: Quad(QuadBez { p0: (73.5, 517.0), p1: (87.0, 527.0), p2: (108.0, 530.0) })/Line(Line { p0: (108.0, 530.0), p1: (107.0, 530.0) }) = 8.130102354156005 degrees
* uni0DA0 (U+0DA0): Quad(QuadBez { p0: (73.5, 517.0), p1: (87.0, 527.0), p2: (108.0, 530.0) })/Line(Line { p0: (108.0, 530.0), p1: (107.0, 530.0) }) = 8.130102354156005 degrees
* chsinh: Quad(QuadBez { p0: (443.0, 217.5), p1: (471.0, 240.0), p2: (477.0, 292.0) })/Quad(QuadBez { p0: (477.0, 292.0), p1: (475.0, 283.0), p2: (462.5, 263.0) }) = 5.946863053973514 degrees
* chIsinh: Quad(QuadBez { p0: (136.0, 553.0), p1: (179.0, 553.0), p2: (216.0, 526.0) })/Quad(QuadBez { p0: (216.0, 526.0), p1: (204.0, 538.0), p2: (199.0, 554.5) }) = 8.880659150520193 degrees
* chIsinh: Line(Line { p0: (227.0, 518.0), p1: (225.0, 519.0) })/Quad(QuadBez { p0: (225.0, 519.0), p1: (246.0, 502.0), p2: (259.5, 476.5) }) = 12.425942865427485 degrees
* chUsinh: Quad(QuadBez { p0: (460.5, 234.0), p1: (483.0, 258.0), p2: (482.0, 294.0) })/Quad(QuadBez { p0: (482.0, 294.0), p1: (480.0, 285.0), p2: (467.5, 265.0) }) = 14.119947980346076 degrees
* chUusinh: Quad(QuadBez { p0: (460.5, 234.0), p1: (483.0, 258.0), p2: (482.0, 294.0) })/Quad(QuadBez { p0: (482.0, 294.0), p1: (480.0, 285.0), p2: (467.5, 265.0) }) = 14.119947980346076 degrees
* uni0DA1 (U+0DA1): Quad(QuadBez { p0: (460.5, 234.0), p1: (483.0, 258.0), p2: (482.0, 294.0) })/Quad(QuadBez { p0: (482.0, 294.0), p1: (480.0, 285.0), p2: (467.5, 265.0) }) = 14.119947980346076 degrees
* dDhsinh: Quad(QuadBez { p0: (312.0, 418.0), p1: (266.0, 431.0), p2: (226.0, 432.0) })/Quad(QuadBez { p0: (226.0, 432.0), p1: (240.0, 435.0), p2: (256.0, 435.0) }) = 13.526853261176734 degrees
* dDhsinh: Quad(QuadBez { p0: (125.0, 410.5), p1: (166.0, 433.0), p2: (226.0, 432.0) })/Quad(QuadBez { p0: (226.0, 432.0), p1: (199.0, 427.0), p2: (179.0, 413.5) }) = 11.446318266203786 degrees
* dDhIisinh: Quad(QuadBez { p0: (330.0, 417.0), p1: (292.0, 428.0), p2: (258.0, 430.0) })/Quad(QuadBez { p0: (258.0, 430.0), p1: (262.0, 430.0), p2: (267.0, 430.0) }) = 3.36646066342994 degrees
* dDhIisinh: Quad(QuadBez { p0: (147.0, 414.0), p1: (193.0, 435.0), p2: (258.0, 430.0) })/Quad(QuadBez { p0: (258.0, 430.0), p1: (226.0, 429.0), p2: (202.5, 416.0) }) = 6.1886159632415545 degrees
* ddhsinh: Quad(QuadBez { p0: (281.0, 21.0), p1: (255.0, 42.0), p2: (255.0, 79.0) })/Quad(QuadBez { p0: (255.0, 79.0), p1: (254.0, 73.0), p2: (243.0, 53.5) }) = 9.462322208025613 degrees
* ddhIisinh: Quad(QuadBez { p0: (281.0, 21.0), p1: (255.0, 42.0), p2: (255.0, 79.0) })/Quad(QuadBez { p0: (255.0, 79.0), p1: (254.0, 73.0), p2: (243.0, 53.5) }) = 9.462322208025613 degrees
* uni0DAA (U+0DAA): Quad(QuadBez { p0: (281.0, 21.0), p1: (255.0, 42.0), p2: (255.0, 79.0) })/Quad(QuadBez { p0: (255.0, 79.0), p1: (254.0, 73.0), p2: (243.0, 53.5) }) = 9.462322208025613 degrees
* uni0D91 (U+0D91): Quad(QuadBez { p0: (312.0, 464.5), p1: (288.0, 474.0), p2: (265.0, 493.0) })/Quad(QuadBez { p0: (265.0, 493.0), p1: (282.0, 470.0), p2: (287.0, 446.0) }) = 13.97109764095363 degrees
* uni0D92 (U+0D92): Quad(QuadBez { p0: (325.0, 464.5), p1: (301.0, 474.0), p2: (278.0, 493.0) })/Quad(QuadBez { p0: (278.0, 493.0), p1: (295.0, 470.0), p2: (300.0, 446.0) }) = 13.97109764095363 degrees
* gUusinh: Line(Line { p0: (492.0, -6.0), p1: (544.0, 7.0) })/Line(Line { p0: (544.0, 7.0), p1: (465.0, 7.0) }) = 14.036243467926484 degrees
* gUusinh: Line(Line { p0: (598.0, 8.0), p1: (546.0, -5.0) })/Line(Line { p0: (546.0, -5.0), p1: (622.0, -5.0) }) = 14.036243467926457 degrees
* jsinh: Quad(QuadBez { p0: (364.5, 458.5), p1: (379.0, 457.0), p2: (397.0, 453.0) })/Quad(QuadBez { p0: (397.0, 453.0), p1: (387.0, 458.0), p2: (379.0, 473.0) }) = 14.036243467926484 degrees
* jIsinh: Quad(QuadBez { p0: (364.5, 458.5), p1: (379.0, 457.0), p2: (397.0, 453.0) })/Quad(QuadBez { p0: (397.0, 453.0), p1: (387.0, 458.0), p2: (379.0, 473.0) }) = 14.036243467926484 degrees
* jIisinh: Quad(QuadBez { p0: (305.0, 502.5), p1: (326.0, 523.0), p2: (346.0, 535.0) })/Quad(QuadBez { p0: (346.0, 535.0), p1: (340.0, 533.0), p2: (333.0, 533.0) }) = 12.52880770915155 degrees
* jIisinh: Quad(QuadBez { p0: (364.5, 458.5), p1: (379.0, 457.0), p2: (397.0, 453.0) })/Quad(QuadBez { p0: (397.0, 453.0), p1: (387.0, 458.0), p2: (379.0, 473.0) }) = 14.036243467926484 degrees
* jRsinh: Quad(QuadBez { p0: (365.5, 464.5), p1: (380.0, 463.0), p2: (398.0, 459.0) })/Quad(QuadBez { p0: (398.0, 459.0), p1: (388.0, 464.0), p2: (380.0, 479.0) }) = 14.036243467926484 degrees
* jRIsinh: Quad(QuadBez { p0: (364.5, 458.5), p1: (379.0, 457.0), p2: (397.0, 453.0) })/Quad(QuadBez { p0: (397.0, 453.0), p1: (387.0, 458.0), p2: (379.0, 473.0) }) = 14.036243467926484 degrees
* jRIisinh: Quad(QuadBez { p0: (305.0, 502.5), p1: (326.0, 523.0), p2: (346.0, 535.0) })/Quad(QuadBez { p0: (346.0, 535.0), p1: (340.0, 533.0), p2: (333.0, 533.0) }) = 12.52880770915155 degrees
* jRIisinh: Quad(QuadBez { p0: (364.5, 458.5), p1: (379.0, 457.0), p2: (397.0, 453.0) })/Quad(QuadBez { p0: (397.0, 453.0), p1: (387.0, 458.0), p2: (379.0, 473.0) }) = 14.036243467926484 degrees
* jRasinh: Quad(QuadBez { p0: (364.5, 458.5), p1: (379.0, 457.0), p2: (397.0, 453.0) })/Quad(QuadBez { p0: (397.0, 453.0), p1: (387.0, 458.0), p2: (379.0, 473.0) }) = 14.036243467926484 degrees
* jUsinh: Quad(QuadBez { p0: (364.5, 458.5), p1: (379.0, 457.0), p2: (397.0, 453.0) })/Quad(QuadBez { p0: (397.0, 453.0), p1: (387.0, 458.0), p2: (379.0, 473.0) }) = 14.036243467926484 degrees
* jUusinh: Quad(QuadBez { p0: (364.5, 458.5), p1: (379.0, 457.0), p2: (397.0, 453.0) })/Quad(QuadBez { p0: (397.0, 453.0), p1: (387.0, 458.0), p2: (379.0, 473.0) }) = 14.036243467926484 degrees
* uni0DA2 (U+0DA2): Quad(QuadBez { p0: (364.5, 458.5), p1: (379.0, 457.0), p2: (397.0, 453.0) })/Quad(QuadBez { p0: (397.0, 453.0), p1: (387.0, 458.0), p2: (379.0, 473.0) }) = 14.036243467926484 degrees
* jhIsinh: Quad(QuadBez { p0: (404.0, 364.0), p1: (392.0, 364.0), p2: (378.0, 367.0) })/Quad(QuadBez { p0: (378.0, 367.0), p1: (430.0, 350.0), p2: (464.0, 302.0) }) = 6.009005957494535 degrees
* jhIsinh: Quad(QuadBez { p0: (303.0, 69.0), p1: (298.0, 81.0), p2: (297.0, 88.0) })/Quad(QuadBez { p0: (297.0, 88.0), p1: (293.0, 51.0), p2: (270.0, 26.0) }) = 14.300277449185575 degrees
* jhIsinh: Quad(QuadBez { p0: (105.0, 123.0), p1: (93.0, 156.0), p2: (75.0, 173.0) })/Quad(QuadBez { p0: (75.0, 173.0), p1: (87.0, 157.0), p2: (87.0, 141.0) }) = 9.76667939577274 degrees
* jhIisinh: Quad(QuadBez { p0: (392.0, 364.0), p1: (380.0, 364.0), p2: (366.0, 367.0) })/Quad(QuadBez { p0: (366.0, 367.0), p1: (418.0, 350.0), p2: (452.0, 302.0) }) = 6.009005957494535 degrees
* jhIisinh: Quad(QuadBez { p0: (291.0, 69.0), p1: (286.0, 81.0), p2: (285.0, 88.0) })/Quad(QuadBez { p0: (285.0, 88.0), p1: (281.0, 51.0), p2: (258.0, 26.0) }) = 14.300277449185575 degrees
* jhIisinh: Quad(QuadBez { p0: (93.0, 123.0), p1: (81.0, 156.0), p2: (63.0, 173.0) })/Quad(QuadBez { p0: (63.0, 173.0), p1: (75.0, 157.0), p2: (75.0, 141.0) }) = 9.76667939577274 degrees
* jhRIsinh: Quad(QuadBez { p0: (404.0, 364.0), p1: (392.0, 364.0), p2: (378.0, 367.0) })/Quad(QuadBez { p0: (378.0, 367.0), p1: (430.0, 350.0), p2: (464.0, 302.0) }) = 6.009005957494535 degrees
* jhRIsinh: Quad(QuadBez { p0: (303.0, 69.0), p1: (298.0, 81.0), p2: (297.0, 88.0) })/Quad(QuadBez { p0: (297.0, 88.0), p1: (293.0, 51.0), p2: (270.0, 26.0) }) = 14.300277449185575 degrees
* jhRIsinh: Quad(QuadBez { p0: (105.0, 123.0), p1: (93.0, 156.0), p2: (75.0, 173.0) })/Quad(QuadBez { p0: (75.0, 173.0), p1: (87.0, 157.0), p2: (87.0, 141.0) }) = 9.76667939577274 degrees
* jhRIisinh: Quad(QuadBez { p0: (392.0, 364.0), p1: (380.0, 364.0), p2: (366.0, 367.0) })/Quad(QuadBez { p0: (366.0, 367.0), p1: (418.0, 350.0), p2: (452.0, 302.0) }) = 6.009005957494535 degrees
* jhRIisinh: Quad(QuadBez { p0: (291.0, 69.0), p1: (286.0, 81.0), p2: (285.0, 88.0) })/Quad(QuadBez { p0: (285.0, 88.0), p1: (281.0, 51.0), p2: (258.0, 26.0) }) = 14.300277449185575 degrees
* jhRIisinh: Quad(QuadBez { p0: (93.0, 123.0), p1: (81.0, 156.0), p2: (63.0, 173.0) })/Quad(QuadBez { p0: (63.0, 173.0), p1: (75.0, 157.0), p2: (75.0, 141.0) }) = 9.76667939577274 degrees
* jhRasinh: Quad(QuadBez { p0: (105.0, 118.0), p1: (93.0, 150.0), p2: (76.0, 168.0) })/Quad(QuadBez { p0: (76.0, 168.0), p1: (87.0, 153.0), p2: (87.0, 135.0) }) = 7.109585220938496 degrees
* jhUsinh: Quad(QuadBez { p0: (105.0, 118.0), p1: (93.0, 150.0), p2: (76.0, 168.0) })/Quad(QuadBez { p0: (76.0, 168.0), p1: (87.0, 153.0), p2: (87.0, 135.0) }) = 7.109585220938496 degrees
* jhUusinh: Quad(QuadBez { p0: (105.0, 118.0), p1: (93.0, 150.0), p2: (76.0, 168.0) })/Quad(QuadBez { p0: (76.0, 168.0), p1: (87.0, 153.0), p2: (87.0, 135.0) }) = 7.109585220938496 degrees
* uni0DA3 (U+0DA3): Quad(QuadBez { p0: (105.0, 118.0), p1: (93.0, 150.0), p2: (76.0, 168.0) })/Quad(QuadBez { p0: (76.0, 168.0), p1: (87.0, 153.0), p2: (87.0, 135.0) }) = 7.109585220938496 degrees
* ksinh: Quad(QuadBez { p0: (422.5, 371.0), p1: (381.0, 369.0), p2: (350.0, 367.0) })/Quad(QuadBez { p0: (350.0, 367.0), p1: (394.0, 359.0), p2: (427.5, 329.5) }) = 13.996232455217315 degrees
* ksinh: Quad(QuadBez { p0: (101.0, 129.0), p1: (92.0, 151.0), p2: (76.0, 168.0) })/Quad(QuadBez { p0: (76.0, 168.0), p1: (78.0, 165.0), p2: (82.5, 156.5) }) = 9.574227885091789 degrees
* kIsinh: Quad(QuadBez { p0: (422.5, 371.0), p1: (381.0, 369.0), p2: (350.0, 367.0) })/Quad(QuadBez { p0: (350.0, 367.0), p1: (394.0, 359.0), p2: (427.5, 329.5) }) = 13.996232455217315 degrees
* kIsinh: Quad(QuadBez { p0: (101.0, 129.0), p1: (92.0, 151.0), p2: (76.0, 168.0) })/Quad(QuadBez { p0: (76.0, 168.0), p1: (78.0, 165.0), p2: (82.5, 156.5) }) = 9.574227885091789 degrees
* kIisinh: Quad(QuadBez { p0: (422.5, 371.0), p1: (381.0, 369.0), p2: (350.0, 367.0) })/Quad(QuadBez { p0: (350.0, 367.0), p1: (394.0, 359.0), p2: (427.5, 329.5) }) = 13.996232455217315 degrees
* kIisinh: Quad(QuadBez { p0: (101.0, 129.0), p1: (92.0, 151.0), p2: (76.0, 168.0) })/Quad(QuadBez { p0: (76.0, 168.0), p1: (78.0, 165.0), p2: (82.5, 156.5) }) = 9.574227885091789 degrees
* kRIsinh: Quad(QuadBez { p0: (421.5, 371.0), p1: (380.0, 369.0), p2: (349.0, 367.0) })/Quad(QuadBez { p0: (349.0, 367.0), p1: (393.0, 359.0), p2: (426.5, 329.5) }) = 13.996232455217315 degrees
* kRIsinh: Quad(QuadBez { p0: (100.0, 129.0), p1: (91.0, 151.0), p2: (75.0, 168.0) })/Quad(QuadBez { p0: (75.0, 168.0), p1: (77.0, 165.0), p2: (81.5, 156.5) }) = 9.574227885091789 degrees
* kRIisinh: Quad(QuadBez { p0: (417.5, 371.0), p1: (376.0, 369.0), p2: (345.0, 367.0) })/Quad(QuadBez { p0: (345.0, 367.0), p1: (389.0, 359.0), p2: (422.5, 329.5) }) = 13.996232455217315 degrees
* kRIisinh: Quad(QuadBez { p0: (96.0, 129.0), p1: (87.0, 151.0), p2: (71.0, 168.0) })/Quad(QuadBez { p0: (71.0, 168.0), p1: (73.0, 165.0), p2: (77.5, 156.5) }) = 9.574227885091789 degrees
* kRasinh: Quad(QuadBez { p0: (422.5, 371.0), p1: (381.0, 369.0), p2: (350.0, 367.0) })/Quad(QuadBez { p0: (350.0, 367.0), p1: (394.0, 359.0), p2: (427.5, 329.5) }) = 13.996232455217315 degrees
* kRasinh: Quad(QuadBez { p0: (101.0, 129.0), p1: (92.0, 151.0), p2: (76.0, 168.0) })/Quad(QuadBez { p0: (76.0, 168.0), p1: (78.0, 165.0), p2: (82.5, 156.5) }) = 9.574227885091789 degrees
* kSssinh: Quad(QuadBez { p0: (379.0, 364.0), p1: (366.0, 364.0), p2: (352.0, 367.0) })/Quad(QuadBez { p0: (352.0, 367.0), p1: (410.0, 347.0), p2: (446.0, 292.5) }) = 6.930848960556587 degrees
* kSssinh: Quad(QuadBez { p0: (76.0, 134.0), p1: (67.0, 156.0), p2: (50.0, 173.0) })/Quad(QuadBez { p0: (50.0, 173.0), p1: (52.0, 170.0), p2: (57.0, 161.5) }) = 11.309932474020162 degrees
* kSsIsinh: Quad(QuadBez { p0: (400.0, 364.0), p1: (387.0, 364.0), p2: (373.0, 367.0) })/Quad(QuadBez { p0: (373.0, 367.0), p1: (431.0, 347.0), p2: (467.0, 292.5) }) = 6.930848960556587 degrees
* kSsIsinh: Quad(QuadBez { p0: (97.0, 134.0), p1: (88.0, 156.0), p2: (71.0, 173.0) })/Quad(QuadBez { p0: (71.0, 173.0), p1: (73.0, 170.0), p2: (78.0, 161.5) }) = 11.309932474020162 degrees
* kSsIisinh: Quad(QuadBez { p0: (394.0, 364.0), p1: (381.0, 364.0), p2: (367.0, 367.0) })/Quad(QuadBez { p0: (367.0, 367.0), p1: (425.0, 347.0), p2: (461.0, 292.5) }) = 6.930848960556587 degrees
* kSsIisinh: Quad(QuadBez { p0: (91.0, 134.0), p1: (82.0, 156.0), p2: (65.0, 173.0) })/Quad(QuadBez { p0: (65.0, 173.0), p1: (67.0, 170.0), p2: (72.0, 161.5) }) = 11.309932474020162 degrees
* kSsUsinh: Quad(QuadBez { p0: (394.0, 364.0), p1: (381.0, 364.0), p2: (367.0, 367.0) })/Quad(QuadBez { p0: (367.0, 367.0), p1: (425.0, 347.0), p2: (461.0, 292.5) }) = 6.930848960556587 degrees
* kSsUsinh: Quad(QuadBez { p0: (91.0, 134.0), p1: (82.0, 156.0), p2: (65.0, 173.0) })/Quad(QuadBez { p0: (65.0, 173.0), p1: (67.0, 170.0), p2: (72.0, 161.5) }) = 11.309932474020162 degrees
* kSsUusinh: Quad(QuadBez { p0: (394.0, 364.0), p1: (381.0, 364.0), p2: (367.0, 367.0) })/Quad(QuadBez { p0: (367.0, 367.0), p1: (425.0, 347.0), p2: (461.0, 292.5) }) = 6.930848960556587 degrees
* kSsUusinh: Quad(QuadBez { p0: (91.0, 134.0), p1: (82.0, 156.0), p2: (65.0, 173.0) })/Quad(QuadBez { p0: (65.0, 173.0), p1: (67.0, 170.0), p2: (72.0, 161.5) }) = 11.309932474020162 degrees
* kSsasinh: Quad(QuadBez { p0: (394.0, 364.0), p1: (381.0, 364.0), p2: (367.0, 367.0) })/Quad(QuadBez { p0: (367.0, 367.0), p1: (425.0, 347.0), p2: (461.0, 292.5) }) = 6.930848960556587 degrees
* kSsasinh: Quad(QuadBez { p0: (91.0, 134.0), p1: (82.0, 156.0), p2: (65.0, 173.0) })/Quad(QuadBez { p0: (65.0, 173.0), p1: (67.0, 170.0), p2: (72.0, 161.5) }) = 11.309932474020162 degrees
* kUsinh: Quad(QuadBez { p0: (422.5, 371.0), p1: (381.0, 369.0), p2: (350.0, 367.0) })/Quad(QuadBez { p0: (350.0, 367.0), p1: (394.0, 359.0), p2: (427.5, 329.5) }) = 13.996232455217315 degrees
* kUsinh: Quad(QuadBez { p0: (101.0, 129.0), p1: (92.0, 151.0), p2: (76.0, 168.0) })/Quad(QuadBez { p0: (76.0, 168.0), p1: (78.0, 165.0), p2: (82.5, 156.5) }) = 9.574227885091789 degrees
* kUusinh: Quad(QuadBez { p0: (422.5, 371.0), p1: (381.0, 369.0), p2: (350.0, 367.0) })/Quad(QuadBez { p0: (350.0, 367.0), p1: (394.0, 359.0), p2: (427.5, 329.5) }) = 13.996232455217315 degrees
* kUusinh: Quad(QuadBez { p0: (101.0, 129.0), p1: (92.0, 151.0), p2: (76.0, 168.0) })/Quad(QuadBez { p0: (76.0, 168.0), p1: (78.0, 165.0), p2: (82.5, 156.5) }) = 9.574227885091789 degrees
* kUusinh: Line(Line { p0: (556.0, -6.0), p1: (608.0, 7.0) })/Line(Line { p0: (608.0, 7.0), p1: (529.0, 7.0) }) = 14.036243467926484 degrees
* kUusinh: Line(Line { p0: (662.0, 8.0), p1: (610.0, -5.0) })/Line(Line { p0: (610.0, -5.0), p1: (686.0, -5.0) }) = 14.036243467926457 degrees
* kVsinh: Quad(QuadBez { p0: (394.0, 364.0), p1: (381.0, 364.0), p2: (367.0, 367.0) })/Quad(QuadBez { p0: (367.0, 367.0), p1: (425.0, 347.0), p2: (461.0, 292.5) }) = 6.930848960556587 degrees
* kVsinh: Quad(QuadBez { p0: (91.0, 134.0), p1: (82.0, 156.0), p2: (65.0, 173.0) })/Quad(QuadBez { p0: (65.0, 173.0), p1: (67.0, 170.0), p2: (72.0, 161.5) }) = 11.309932474020162 degrees
* kVIsinh: Quad(QuadBez { p0: (394.0, 364.0), p1: (381.0, 364.0), p2: (367.0, 367.0) })/Quad(QuadBez { p0: (367.0, 367.0), p1: (425.0, 347.0), p2: (461.0, 292.5) }) = 6.930848960556587 degrees
* kVIsinh: Quad(QuadBez { p0: (91.0, 134.0), p1: (82.0, 156.0), p2: (65.0, 173.0) })/Quad(QuadBez { p0: (65.0, 173.0), p1: (67.0, 170.0), p2: (72.0, 161.5) }) = 11.309932474020162 degrees
* kVIisinh: Quad(QuadBez { p0: (394.0, 364.0), p1: (381.0, 364.0), p2: (367.0, 367.0) })/Quad(QuadBez { p0: (367.0, 367.0), p1: (425.0, 347.0), p2: (461.0, 292.5) }) = 6.930848960556587 degrees
* kVIisinh: Quad(QuadBez { p0: (91.0, 134.0), p1: (82.0, 156.0), p2: (65.0, 173.0) })/Quad(QuadBez { p0: (65.0, 173.0), p1: (67.0, 170.0), p2: (72.0, 161.5) }) = 11.309932474020162 degrees
* kVUsinh: Quad(QuadBez { p0: (394.0, 364.0), p1: (381.0, 364.0), p2: (367.0, 367.0) })/Quad(QuadBez { p0: (367.0, 367.0), p1: (425.0, 347.0), p2: (461.0, 292.5) }) = 6.930848960556587 degrees
* kVUsinh: Quad(QuadBez { p0: (91.0, 134.0), p1: (82.0, 156.0), p2: (65.0, 173.0) })/Quad(QuadBez { p0: (65.0, 173.0), p1: (67.0, 170.0), p2: (72.0, 161.5) }) = 11.309932474020162 degrees
* kVUusinh: Quad(QuadBez { p0: (394.0, 364.0), p1: (381.0, 364.0), p2: (367.0, 367.0) })/Quad(QuadBez { p0: (367.0, 367.0), p1: (425.0, 347.0), p2: (461.0, 292.5) }) = 6.930848960556587 degrees
* kVUusinh: Quad(QuadBez { p0: (91.0, 134.0), p1: (82.0, 156.0), p2: (65.0, 173.0) })/Quad(QuadBez { p0: (65.0, 173.0), p1: (67.0, 170.0), p2: (72.0, 161.5) }) = 11.309932474020162 degrees
* kVasinh: Quad(QuadBez { p0: (394.0, 364.0), p1: (381.0, 364.0), p2: (367.0, 367.0) })/Quad(QuadBez { p0: (367.0, 367.0), p1: (425.0, 347.0), p2: (461.0, 292.5) }) = 6.930848960556587 degrees
* kVasinh: Quad(QuadBez { p0: (91.0, 134.0), p1: (82.0, 156.0), p2: (65.0, 173.0) })/Quad(QuadBez { p0: (65.0, 173.0), p1: (67.0, 170.0), p2: (72.0, 161.5) }) = 11.309932474020162 degrees
* uni0D9A (U+0D9A): Quad(QuadBez { p0: (422.5, 371.0), p1: (381.0, 369.0), p2: (350.0, 367.0) })/Quad(QuadBez { p0: (350.0, 367.0), p1: (394.0, 359.0), p2: (427.5, 329.5) }) = 13.996232455217315 degrees
* uni0D9A (U+0D9A): Quad(QuadBez { p0: (101.0, 129.0), p1: (92.0, 151.0), p2: (76.0, 168.0) })/Quad(QuadBez { p0: (76.0, 168.0), p1: (78.0, 165.0), p2: (82.5, 156.5) }) = 9.574227885091789 degrees
* uni0DF4 (U+0DF4): Quad(QuadBez { p0: (530.5, 354.0), p1: (538.0, 345.0), p2: (539.0, 343.0) })/Quad(QuadBez { p0: (539.0, 343.0), p1: (532.0, 356.0), p2: (526.5, 375.0) }) = 1.735704588928346 degrees
* uni0DF4 (U+0DF4): Quad(QuadBez { p0: (528.0, 464.0), p1: (535.0, 484.0), p2: (540.0, 494.0) })/Quad(QuadBez { p0: (540.0, 494.0), p1: (537.0, 485.0), p2: (533.5, 470.0) }) = 8.130102354156005 degrees
* uni0DF4 (U+0DF4): Quad(QuadBez { p0: (778.5, 470.0), p1: (775.0, 485.0), p2: (772.0, 494.0) })/Quad(QuadBez { p0: (772.0, 494.0), p1: (777.0, 485.0), p2: (784.0, 464.5) }) = 10.619655276155175 degrees
* uni0DF4 (U+0DF4): Quad(QuadBez { p0: (785.5, 375.5), p1: (780.0, 356.0), p2: (773.0, 343.0) })/Quad(QuadBez { p0: (773.0, 343.0), p1: (774.0, 345.0), p2: (781.5, 354.0) }) = 1.735704588928346 degrees
* llUsinh: Quad(QuadBez { p0: (28.5, 333.5), p1: (30.0, 323.0), p2: (32.0, 315.0) })/Quad(QuadBez { p0: (32.0, 315.0), p1: (29.0, 326.0), p2: (25.5, 343.5) }) = 1.2188752351310335 degrees
* llUusinh: Quad(QuadBez { p0: (28.5, 333.5), p1: (30.0, 323.0), p2: (32.0, 315.0) })/Quad(QuadBez { p0: (32.0, 315.0), p1: (29.0, 326.0), p2: (25.5, 343.5) }) = 1.2188752351310335 degrees
* uusignsinh.alt1: Line(Line { p0: (-177.0, -6.0), p1: (-125.0, 7.0) })/Line(Line { p0: (-125.0, 7.0), p1: (-204.0, 7.0) }) = 14.036243467926484 degrees
* uusignsinh.alt1: Line(Line { p0: (-71.0, 8.0), p1: (-123.0, -5.0) })/Line(Line { p0: (-123.0, -5.0), p1: (-47.0, -5.0) }) = 14.036243467926457 degrees
* mbsinh: Quad(QuadBez { p0: (346.0, 108.0), p1: (370.0, 108.0), p2: (393.0, 94.0) })/Quad(QuadBez { p0: (393.0, 94.0), p1: (383.0, 101.0), p2: (351.5, 116.5) }) = 3.6633273307544822 degrees
* mbsinh: Quad(QuadBez { p0: (169.0, 103.0), p1: (151.0, 92.0), p2: (143.0, 86.0) })/Quad(QuadBez { p0: (143.0, 86.0), p1: (162.0, 99.0), p2: (180.5, 104.5) }) = 2.489552921998982 degrees
* mbIsinh: Quad(QuadBez { p0: (356.0, 105.0), p1: (380.0, 105.0), p2: (403.0, 90.0) })/Quad(QuadBez { p0: (403.0, 90.0), p1: (393.0, 97.0), p2: (360.5, 112.5) }) = 1.8806782381866813 degrees
* mbIsinh: Quad(QuadBez { p0: (173.5, 99.0), p1: (155.0, 88.0), p2: (147.0, 82.0) })/Quad(QuadBez { p0: (147.0, 82.0), p1: (166.0, 95.0), p2: (185.0, 100.5) }) = 2.489552921998982 degrees
* mbIisinh: Quad(QuadBez { p0: (345.0, 106.0), p1: (369.0, 106.0), p2: (392.0, 92.0) })/Quad(QuadBez { p0: (392.0, 92.0), p1: (382.0, 99.0), p2: (350.5, 114.5) }) = 3.6633273307544822 degrees
* mbIisinh: Quad(QuadBez { p0: (168.0, 101.0), p1: (150.0, 90.0), p2: (142.0, 84.0) })/Quad(QuadBez { p0: (142.0, 84.0), p1: (161.0, 97.0), p2: (179.5, 102.5) }) = 2.489552921998982 degrees
* mbUsinh: Quad(QuadBez { p0: (348.0, 102.0), p1: (372.0, 102.0), p2: (394.0, 88.0) })/Quad(QuadBez { p0: (394.0, 88.0), p1: (384.0, 95.0), p2: (352.5, 110.5) }) = 2.5208279077102165 degrees
* mbUsinh: Quad(QuadBez { p0: (170.0, 97.0), p1: (152.0, 86.0), p2: (144.0, 80.0) })/Quad(QuadBez { p0: (144.0, 80.0), p1: (163.0, 93.0), p2: (181.5, 98.5) }) = 2.489552921998982 degrees
* mbUusinh: Quad(QuadBez { p0: (348.0, 102.0), p1: (372.0, 102.0), p2: (394.0, 88.0) })/Quad(QuadBez { p0: (394.0, 88.0), p1: (384.0, 95.0), p2: (352.5, 110.5) }) = 2.5208279077102165 degrees
* mbUusinh: Quad(QuadBez { p0: (170.0, 97.0), p1: (152.0, 86.0), p2: (144.0, 80.0) })/Quad(QuadBez { p0: (144.0, 80.0), p1: (163.0, 93.0), p2: (181.5, 98.5) }) = 2.489552921998982 degrees
* uni0DB9 (U+0DB9): Quad(QuadBez { p0: (348.0, 102.0), p1: (372.0, 102.0), p2: (394.0, 88.0) })/Quad(QuadBez { p0: (394.0, 88.0), p1: (384.0, 95.0), p2: (352.5, 110.5) }) = 2.5208279077102165 degrees
* uni0DB9 (U+0DB9): Quad(QuadBez { p0: (170.0, 97.0), p1: (152.0, 86.0), p2: (144.0, 80.0) })/Quad(QuadBez { p0: (144.0, 80.0), p1: (163.0, 93.0), p2: (181.5, 98.5) }) = 2.489552921998982 degrees
* ndsinh: Quad(QuadBez { p0: (25.0, 349.5), p1: (16.0, 312.0), p2: (15.0, 291.0) })/Quad(QuadBez { p0: (15.0, 291.0), p1: (15.0, 293.0), p2: (15.0, 296.0) }) = 2.7263109939063455 degrees
* ndIsinh: Quad(QuadBez { p0: (64.0, 425.0), p1: (20.0, 368.0), p2: (15.0, 291.0) })/Quad(QuadBez { p0: (15.0, 291.0), p1: (15.0, 293.0), p2: (15.0, 296.0) }) = 3.7152891054287163 degrees
* ndIisinh: Quad(QuadBez { p0: (16.0, 349.5), p1: (7.0, 312.0), p2: (6.0, 291.0) })/Quad(QuadBez { p0: (6.0, 291.0), p1: (6.0, 293.0), p2: (6.0, 296.0) }) = 2.7263109939063455 degrees
* uni0DB3 (U+0DB3): Quad(QuadBez { p0: (25.0, 349.5), p1: (16.0, 312.0), p2: (15.0, 291.0) })/Quad(QuadBez { p0: (15.0, 291.0), p1: (15.0, 293.0), p2: (15.0, 296.0) }) = 2.7263109939063455 degrees
* nyjIsinh: Quad(QuadBez { p0: (458.5, 458.5), p1: (473.0, 457.0), p2: (491.0, 453.0) })/Quad(QuadBez { p0: (491.0, 453.0), p1: (481.0, 458.0), p2: (473.0, 473.0) }) = 14.036243467926484 degrees
* nyjIisinh: Quad(QuadBez { p0: (386.0, 502.5), p1: (407.0, 523.0), p2: (427.0, 535.0) })/Quad(QuadBez { p0: (427.0, 535.0), p1: (421.0, 533.0), p2: (414.0, 533.0) }) = 12.52880770915155 degrees
* nyjIisinh: Quad(QuadBez { p0: (445.5, 458.5), p1: (460.0, 457.0), p2: (478.0, 453.0) })/Quad(QuadBez { p0: (478.0, 453.0), p1: (468.0, 458.0), p2: (460.0, 473.0) }) = 14.036243467926484 degrees
* nyjRsinh: Quad(QuadBez { p0: (435.5, 464.5), p1: (450.0, 463.0), p2: (468.0, 459.0) })/Quad(QuadBez { p0: (468.0, 459.0), p1: (458.0, 464.0), p2: (450.0, 479.0) }) = 14.036243467926484 degrees
* nyjRasinh: Quad(QuadBez { p0: (444.5, 464.5), p1: (459.0, 463.0), p2: (477.0, 459.0) })/Quad(QuadBez { p0: (477.0, 459.0), p1: (467.0, 464.0), p2: (459.0, 479.0) }) = 14.036243467926484 degrees
* nyjUsinh: Quad(QuadBez { p0: (452.5, 458.5), p1: (467.0, 457.0), p2: (485.0, 453.0) })/Quad(QuadBez { p0: (485.0, 453.0), p1: (475.0, 458.0), p2: (467.0, 473.0) }) = 14.036243467926484 degrees
* nyjUusinh: Quad(QuadBez { p0: (458.5, 458.5), p1: (473.0, 457.0), p2: (491.0, 453.0) })/Quad(QuadBez { p0: (491.0, 453.0), p1: (481.0, 458.0), p2: (473.0, 473.0) }) = 14.036243467926484 degrees
* uni0DA6 (U+0DA6): Line(Line { p0: (257.0, 504.0), p1: (252.0, 505.0) })/Quad(QuadBez { p0: (252.0, 505.0), p1: (266.0, 505.0), p2: (281.0, 505.5) }) = 11.309932474020195 degrees
* uni0DA6 (U+0DA6): Quad(QuadBez { p0: (450.5, 458.5), p1: (465.0, 457.0), p2: (483.0, 453.0) })/Quad(QuadBez { p0: (483.0, 453.0), p1: (473.0, 458.0), p2: (465.0, 473.0) }) = 14.036243467926484 degrees
* nnsinh: Quad(QuadBez { p0: (480.0, 210.5), p1: (470.0, 222.0), p2: (469.0, 237.0) })/Quad(QuadBez { p0: (469.0, 237.0), p1: (469.0, 235.0), p2: (469.0, 231.5) }) = 3.8140748342903783 degrees
* nnsinh: Quad(QuadBez { p0: (563.0, 440.5), p1: (581.0, 419.0), p2: (583.0, 387.0) })/Quad(QuadBez { p0: (583.0, 387.0), p1: (583.0, 414.0), p2: (602.0, 439.0) }) = 3.5763343749973706 degrees
* nnIsinh: Quad(QuadBez { p0: (471.0, 205.5), p1: (461.0, 217.0), p2: (460.0, 232.0) })/Quad(QuadBez { p0: (460.0, 232.0), p1: (460.0, 230.0), p2: (460.0, 226.5) }) = 3.8140748342903783 degrees
* nnIsinh: Quad(QuadBez { p0: (553.0, 432.5), p1: (571.0, 411.0), p2: (572.0, 380.0) })/Quad(QuadBez { p0: (572.0, 380.0), p1: (572.0, 406.0), p2: (591.0, 431.0) }) = 1.8476102659947131 degrees
* nnIisinh: Quad(QuadBez { p0: (471.0, 205.5), p1: (461.0, 217.0), p2: (460.0, 232.0) })/Quad(QuadBez { p0: (460.0, 232.0), p1: (460.0, 230.0), p2: (460.0, 226.5) }) = 3.8140748342903783 degrees
* nnIisinh: Quad(QuadBez { p0: (553.0, 432.5), p1: (571.0, 411.0), p2: (572.0, 380.0) })/Quad(QuadBez { p0: (572.0, 380.0), p1: (572.0, 406.0), p2: (591.0, 431.0) }) = 1.8476102659947131 degrees
* nnUsinh: Quad(QuadBez { p0: (480.0, 210.5), p1: (470.0, 222.0), p2: (469.0, 237.0) })/Quad(QuadBez { p0: (469.0, 237.0), p1: (469.0, 235.0), p2: (469.0, 231.5) }) = 3.8140748342903783 degrees
* nnUsinh: Quad(QuadBez { p0: (563.0, 440.5), p1: (581.0, 419.0), p2: (583.0, 387.0) })/Quad(QuadBez { p0: (583.0, 387.0), p1: (583.0, 414.0), p2: (602.0, 439.0) }) = 3.5763343749973706 degrees
* nnUusinh: Quad(QuadBez { p0: (480.0, 210.5), p1: (470.0, 222.0), p2: (469.0, 237.0) })/Quad(QuadBez { p0: (469.0, 237.0), p1: (469.0, 235.0), p2: (469.0, 231.5) }) = 3.8140748342903783 degrees
* nnUusinh: Quad(QuadBez { p0: (563.0, 440.5), p1: (581.0, 419.0), p2: (583.0, 387.0) })/Quad(QuadBez { p0: (583.0, 387.0), p1: (583.0, 414.0), p2: (602.0, 439.0) }) = 3.5763343749973706 degrees
* uni0DAB (U+0DAB): Quad(QuadBez { p0: (480.0, 210.5), p1: (470.0, 222.0), p2: (469.0, 237.0) })/Quad(QuadBez { p0: (469.0, 237.0), p1: (469.0, 235.0), p2: (469.0, 231.5) }) = 3.8140748342903783 degrees
* uni0DAB (U+0DAB): Quad(QuadBez { p0: (563.0, 440.5), p1: (581.0, 419.0), p2: (583.0, 387.0) })/Quad(QuadBez { p0: (583.0, 387.0), p1: (583.0, 414.0), p2: (602.0, 439.0) }) = 3.5763343749973706 degrees
* nnddsinh: Quad(QuadBez { p0: (30.0, 284.0), p1: (30.0, 199.0), p2: (62.0, 97.0) })/Quad(QuadBez { p0: (62.0, 97.0), p1: (12.0, 200.0), p2: (12.0, 294.0) }) = 8.47567620202511 degrees
* nnddIsinh: Quad(QuadBez { p0: (29.0, 284.0), p1: (29.0, 198.0), p2: (60.0, 97.0) })/Quad(QuadBez { p0: (60.0, 97.0), p1: (10.0, 200.0), p2: (10.0, 294.0) }) = 8.830789820766595 degrees
* nnddIisinh: Quad(QuadBez { p0: (27.0, 284.0), p1: (27.0, 199.0), p2: (59.0, 97.0) })/Quad(QuadBez { p0: (59.0, 97.0), p1: (9.0, 200.0), p2: (9.0, 294.0) }) = 8.47567620202511 degrees
* nnddUsinh: Quad(QuadBez { p0: (336.0, 30.0), p1: (313.0, 60.0), p2: (310.0, 90.0) })/Quad(QuadBez { p0: (310.0, 90.0), p1: (306.0, 60.0), p2: (281.0, 30.0) }) = 13.305236506091065 degrees
* nnddUsinh: Quad(QuadBez { p0: (30.0, 284.0), p1: (30.0, 198.0), p2: (62.0, 97.0) })/Quad(QuadBez { p0: (62.0, 97.0), p1: (11.0, 200.0), p2: (11.0, 294.0) }) = 8.76226009922519 degrees
* nnddUusinh: Quad(QuadBez { p0: (336.0, 30.0), p1: (313.0, 60.0), p2: (310.0, 90.0) })/Quad(QuadBez { p0: (310.0, 90.0), p1: (306.0, 60.0), p2: (281.0, 30.0) }) = 13.305236506091065 degrees
* nnddUusinh: Quad(QuadBez { p0: (30.0, 284.0), p1: (30.0, 198.0), p2: (62.0, 97.0) })/Quad(QuadBez { p0: (62.0, 97.0), p1: (11.0, 200.0), p2: (11.0, 294.0) }) = 8.76226009922519 degrees
* uni0DAC (U+0DAC): Quad(QuadBez { p0: (336.0, 30.0), p1: (313.0, 60.0), p2: (310.0, 90.0) })/Quad(QuadBez { p0: (310.0, 90.0), p1: (306.0, 60.0), p2: (281.0, 30.0) }) = 13.305236506091065 degrees
* uni0DAC (U+0DAC): Quad(QuadBez { p0: (30.0, 284.0), p1: (30.0, 198.0), p2: (62.0, 97.0) })/Quad(QuadBez { p0: (62.0, 97.0), p1: (11.0, 200.0), p2: (11.0, 294.0) }) = 8.76226009922519 degrees
* nngUusinh: Line(Line { p0: (471.0, -6.0), p1: (523.0, 7.0) })/Line(Line { p0: (523.0, 7.0), p1: (444.0, 7.0) }) = 14.036243467926484 degrees
* nngUusinh: Line(Line { p0: (577.0, 8.0), p1: (525.0, -5.0) })/Line(Line { p0: (525.0, -5.0), p1: (601.0, -5.0) }) = 14.036243467926457 degrees
* nysinh: Quad(QuadBez { p0: (408.0, 372.0), p1: (398.0, 372.0), p2: (389.0, 374.0) })/Quad(QuadBez { p0: (389.0, 374.0), p1: (449.0, 358.0), p2: (491.0, 303.0) }) = 2.402609468986064 degrees
* nyIsinh: Quad(QuadBez { p0: (407.0, 372.0), p1: (397.0, 372.0), p2: (388.0, 374.0) })/Quad(QuadBez { p0: (388.0, 374.0), p1: (448.0, 358.0), p2: (490.0, 303.0) }) = 2.402609468986064 degrees
* nyIisinh: Quad(QuadBez { p0: (408.0, 372.0), p1: (398.0, 372.0), p2: (389.0, 374.0) })/Quad(QuadBez { p0: (389.0, 374.0), p1: (449.0, 358.0), p2: (491.0, 303.0) }) = 2.402609468986064 degrees
* nyUsinh: Quad(QuadBez { p0: (409.0, 372.0), p1: (399.0, 372.0), p2: (390.0, 374.0) })/Quad(QuadBez { p0: (390.0, 374.0), p1: (450.0, 358.0), p2: (492.0, 303.0) }) = 2.402609468986064 degrees
* nyUusinh: Quad(QuadBez { p0: (404.0, 372.0), p1: (394.0, 372.0), p2: (385.0, 374.0) })/Quad(QuadBez { p0: (385.0, 374.0), p1: (445.0, 358.0), p2: (487.0, 303.0) }) = 2.402609468986064 degrees
* uni0DA4 (U+0DA4): Quad(QuadBez { p0: (408.0, 372.0), p1: (398.0, 372.0), p2: (389.0, 374.0) })/Quad(QuadBez { p0: (389.0, 374.0), p1: (449.0, 358.0), p2: (491.0, 303.0) }) = 2.402609468986064 degrees
* shUusinh: Line(Line { p0: (487.0, -6.0), p1: (538.0, 7.0) })/Line(Line { p0: (538.0, 7.0), p1: (494.0, 7.0) }) = 14.300277449185575 degrees
* shUusinh: Line(Line { p0: (592.0, 8.0), p1: (540.0, -5.0) })/Line(Line { p0: (540.0, -5.0), p1: (616.0, -5.0) }) = 14.036243467926457 degrees
* tUusinh: Line(Line { p0: (470.0, -6.0), p1: (522.0, 7.0) })/Line(Line { p0: (522.0, 7.0), p1: (443.0, 7.0) }) = 14.036243467926484 degrees
* tUusinh: Line(Line { p0: (576.0, 8.0), p1: (524.0, -5.0) })/Line(Line { p0: (524.0, -5.0), p1: (600.0, -5.0) }) = 14.036243467926457 degrees
* yasign_iisignsinh: Quad(QuadBez { p0: (210.0, 487.0), p1: (248.0, 538.0), p2: (297.0, 540.0) })/Quad(QuadBez { p0: (297.0, 540.0), p1: (276.0, 543.0), p2: (260.5, 555.5) }) = 10.467408213279857 degrees
* yasign_iisignsinh: Quad(QuadBez { p0: (348.5, 553.5), p1: (331.0, 539.0), p2: (309.0, 539.0) })/Quad(QuadBez { p0: (309.0, 539.0), p1: (322.0, 536.0), p2: (335.0, 527.0) }) = 12.994616791916483 degrees [code: found-jaggy-segments]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Check there are no overlapping path segments (overlapping_path_segments)</summary>
    <div>








- ⚠️ **WARN** The following glyphs have overlapping path segments:

* ddhIisinh: Quad(QuadBez { p0: (269.0, 640.0), p1: (269.0, 640.0), p2: (269.0, 640.0) }) has the same coordinates as a previous segment.
* ddhIisinh: Quad(QuadBez { p0: (269.0, 640.0), p1: (269.0, 640.0), p2: (269.0, 640.0) }) has the same coordinates as a previous segment.
* phIisinh: Quad(QuadBez { p0: (243.0, 640.0), p1: (243.0, 640.0), p2: (243.0, 640.0) }) has the same coordinates as a previous segment.
* phIisinh: Quad(QuadBez { p0: (243.0, 640.0), p1: (243.0, 640.0), p2: (243.0, 640.0) }) has the same coordinates as a previous segment.
* rIisinh: Line(Line { p0: (126.0, 403.0), p1: (126.0, 403.0) }) has the same coordinates as a previous segment.
* tThIisinh: Quad(QuadBez { p0: (696.0, 640.0), p1: (696.0, 640.0), p2: (696.0, 640.0) }) has the same coordinates as a previous segment.
* thIisinh: Quad(QuadBez { p0: (249.0, 640.0), p1: (249.0, 640.0), p2: (249.0, 640.0) }) has the same coordinates as a previous segment.
* tthIisinh: Quad(QuadBez { p0: (269.0, 640.0), p1: (269.0, 640.0), p2: (269.0, 640.0) }) has the same coordinates as a previous segment.
* tthIisinh: Quad(QuadBez { p0: (269.0, 640.0), p1: (269.0, 640.0), p2: (269.0, 640.0) }) has the same coordinates as a previous segment.
* uni0D8F (U+0D8F): Line(Line { p0: (446.0, 538.0), p1: (446.0, 538.0) }) has the same coordinates as a previous segment.
* uni0D90 (U+0D90): Line(Line { p0: (446.0, 538.0), p1: (446.0, 538.0) }) has the same coordinates as a previous segment.
* yasign_iisignsinh: Quad(QuadBez { p0: (149.0, 556.0), p1: (149.0, 556.0), p2: (149.0, 556.0) }) has the same coordinates as a previous segment.
* yasign_iisignsinh: Quad(QuadBez { p0: (149.0, 556.0), p1: (149.0, 556.0), p2: (149.0, 556.0) }) has the same coordinates as a previous segment. [code: overlapping-path-segments]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Do outlines contain any semi-vertical or semi-horizontal lines? (outline_semi_vertical)</summary>
    <div>








- ⚠️ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

* cIisinh: Line(Line { p0: (12.0, 302.0), p1: (13.0, 437.0) }) (angle: 89.58 degrees, expected: 90.00 degrees)
* cIisinh: Line(Line { p0: (13.0, 437.0), p1: (219.0, 436.0) }) (angle: -0.28 degrees, expected: 0.00 degrees)
* cRIisinh: Line(Line { p0: (12.0, 302.0), p1: (13.0, 437.0) }) (angle: 89.58 degrees, expected: 90.00 degrees)
* cRIisinh: Line(Line { p0: (13.0, 437.0), p1: (219.0, 436.0) }) (angle: -0.28 degrees, expected: 0.00 degrees)
* ghsinh: Line(Line { p0: (24.0, 302.0), p1: (23.0, 444.0) }) (angle: 90.40 degrees, expected: 90.00 degrees)
* ghIsinh: Line(Line { p0: (24.0, 302.0), p1: (23.0, 444.0) }) (angle: 90.40 degrees, expected: 90.00 degrees)
* ghIisinh: Line(Line { p0: (24.0, 302.0), p1: (23.0, 444.0) }) (angle: 90.40 degrees, expected: 90.00 degrees)
* ghRIsinh: Line(Line { p0: (28.0, 302.0), p1: (27.0, 444.0) }) (angle: 90.40 degrees, expected: 90.00 degrees)
* ghRIisinh: Line(Line { p0: (24.0, 302.0), p1: (23.0, 444.0) }) (angle: 90.40 degrees, expected: 90.00 degrees)
* ghRasinh: Line(Line { p0: (24.0, 302.0), p1: (23.0, 444.0) }) (angle: 90.40 degrees, expected: 90.00 degrees)
* ghUsinh: Line(Line { p0: (24.0, 302.0), p1: (23.0, 444.0) }) (angle: 90.40 degrees, expected: 90.00 degrees)
* ghUusinh: Line(Line { p0: (24.0, 302.0), p1: (23.0, 444.0) }) (angle: 90.40 degrees, expected: 90.00 degrees)
* uni0D9D (U+0D9D): Line(Line { p0: (24.0, 302.0), p1: (23.0, 444.0) }) (angle: 90.40 degrees, expected: 90.00 degrees)
* lUusinh: Line(Line { p0: (437.0, -158.0), p1: (436.0, 38.0) }) (angle: 90.29 degrees, expected: 90.00 degrees)
* rAaesinh: Line(Line { p0: (607.0, 330.0), p1: (472.0, 331.0) }) (angle: 179.58 degrees, expected: 180.00 degrees) [code: found-semi-vertical]
  
  

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

* U+0021 EXCLAMATION MARK: try adding one of: khmer, latin, gunjala-gondi, math, cham, thaana, syriac, adlam, mongolian, masaram-gondi
* U+0022 QUOTATION MARK: try adding one of: latin, adlam, masaram-gondi, mongolian, wancho, math, cham, khmer
* U+0023 NUMBER SIGN: try adding one of: khmer, symbols, math, latin, adlam
* U+0024 DOLLAR SIGN: try adding one of: math, khmer, latin, adlam
* U+0025 PERCENT SIGN: try adding one of: masaram-gondi, khmer, latin, gunjala-gondi, math, adlam
* U+0026 AMPERSAND: try adding one of: khmer, latin, math, adlam
* U+0027 APOSTROPHE: try adding one of: adlam, gunjala-gondi, cham, warang-citi, math, khmer, latin, wancho, masaram-gondi
* U+0028 LEFT PARENTHESIS: try adding one of: mongolian, syriac, math, masaram-gondi, khmer, adlam, latin, cham, thaana, wancho, gunjala-gondi
* U+0029 RIGHT PARENTHESIS: try adding one of: cham, latin, math, thaana, gunjala-gondi, wancho, masaram-gondi, syriac, adlam, mongolian, khmer
* U+002A ASTERISK: try adding one of: khmer, gunjala-gondi, latin, masaram-gondi, math, symbols, adlam, syriac
* U+002B PLUS SIGN: try adding one of: latin, masaram-gondi, syriac, adlam, gunjala-gondi, khmer, math
* U+002C COMMA: try adding one of: khmer, adlam, latin, coptic, cham, thaana, math, nushu, gunjala-gondi, wancho, masaram-gondi
* U+002D HYPHEN-MINUS: try adding one of: coptic, wancho, sora-sompeng, mongolian, kaithi, kharoshthi, lisu, nushu, latin, khmer, adlam, kayah-li, masaram-gondi, armenian, hebrew, math, sundanese, syriac, cham, gunjala-gondi
* U+002E FULL STOP: try adding one of: nushu, syriac, thaana, wancho, khmer, cham, math, avestan, adlam, coptic, gunjala-gondi, latin, masaram-gondi
* U+002F SOLIDUS: try adding one of: khmer, adlam, gunjala-gondi, latin, syriac, wancho, math, cham, masaram-gondi
* U+0030 DIGIT ZERO: try adding one of: symbols, latin, khmer, nushu, math
* U+0031 DIGIT ONE: try adding one of: khmer, math, latin, nushu, symbols
* U+0032 DIGIT TWO: try adding one of: nushu, latin, symbols, khmer, math
* U+0033 DIGIT THREE: try adding one of: math, latin, nushu, symbols, khmer
* U+0034 DIGIT FOUR: try adding one of: symbols, math, latin, khmer, nushu
* U+0035 DIGIT FIVE: try adding one of: nushu, latin, symbols, khmer, math
* U+0036 DIGIT SIX: try adding one of: math, symbols, latin, khmer, nushu
* U+0037 DIGIT SEVEN: try adding one of: symbols, latin, khmer, math, nushu
* U+0038 DIGIT EIGHT: try adding one of: math, nushu, khmer, symbols, latin
* U+0039 DIGIT NINE: try adding one of: latin, khmer, nushu, symbols, math

Or you can add the above codepoints to one of the subsets supported by the font: sinhala [code: unreachable-subsetting]
  
  

</div>
</details>


</div>
</details>






### Summary

| 🔥 FAIL | ⚠️ WARN | ℹ️ INFO | ✅ PASS | ⏩ SKIP | 
| ---|---|---|---|---|
| 4 | 17 | 19 | 96 | 86 | 
| 2% | 8% | 9% | 43% | 39% | 



