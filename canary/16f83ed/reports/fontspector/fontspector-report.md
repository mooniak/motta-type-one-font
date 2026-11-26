## FontSpector report

fontspector version: 1.9.0






## Check results




<details><summary>[1] fonts/ttf</summary>
<div>


<details>
    <summary>⚠️ <b>WARN</b> Ensure Fonts have 'ital' STAT axis. (opentype/STAT/ital_axis)</summary>
    <div>








- ⚠️ **WARN** Static font is missing the 'STAT' table. [code: no-stat-table]
  
  

</div>
</details>


</div>
</details>


<details><summary>[11] fonts/ttf/MottaTypeOneCANARY-Regular.ttf</summary>
<div>


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
* uni0D89 (U+0D89): found 1, expected one of: [2, 3, 4]
* uni0D94 (U+0D94): found 4, expected one of: [1, 2, 3]
* uni0D96 (U+0D96): found 5, expected one of: [2, 3, 4]
* uni0D9E (U+0D9E): found 1, expected one of: [2, 3, 4]
* uni0D9F (U+0D9F): found 2, expected one of: [1, 3, 5]
* uni0DA4 (U+0DA4): found 2, expected one of: [3, 4, 6] [code: contour-count]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Ensure indic fonts have the Indian Rupee Sign glyph. (rupee)</summary>
    <div>








- ⚠️ **WARN** Font is missing the Indian Rupee Sign glyph. Please add a glyph for Indian Rupee Sign (₹) at codepoint U+20B9. (Overriden: Sinhala fonts: U+20B9 is optional (Sri Lanka writes රු / Rs)) [code: missing-rupee]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Ensure font has overlaps bit set correctly. (overlaps_bit)</summary>
    <div>








- ⚠️ **WARN** The following glyphs have overlaps but the overlaps bit is not set:
* ssIisinh
* fsinh
* shsinh
* cRasinh
* fRIsinh
* jhRIisinh
* ndsinh
* tIisinh
* ghsinh
* uni0D92 (U+0D92)
* mbUsinh
* tUusinh
* ghRIisinh
* khUusinh
* ysinh
* ddhUusinh
* bhRasinh
* shIisinh
* kSsUusinh
* dhRsinh
* vUsinh
* jUsinh
* tthsinh
* shRIisinh
* kSsIsinh
* jhUusinh
* nIisinh
* nUusinh
* phUsinh
* sIisinh
* ssRasinh
* jRIsinh
* pRIisinh
* ssRIisinh
* sRIisinh
* phsinh
* tRasinh
* mbUusinh
* phUusinh
* gRIsinh
* tsinh
* thsinh
* dsinh
* ttRasinh
* ssRsinh
* jRasinh
* nngsinh
* gIsinh
* kIsinh
* gRIisinh
* ksinh
* sRIsinh
* nysinh
* ttUsinh
* ddRIisinh
* gRsinh
* ttRIisinh
* jnysinh
* cUusinh
* khRasinh
* hIsinh
* ghRasinh
* bRasinh
* vRIsinh
* uni0DDD (U+0DDD)
* thUusinh
* hRIsinh
* tUsinh
* kRasinh
* hRsinh
* fRasinh
* jRsinh
* shRsinh
* khRIsinh
* bRIsinh
* gUusinh
* shIsinh
* hUsinh
* shUsinh
* khUsinh
* hUusinh
* ddUusinh
* kSsIisinh
* vUusinh
* hRIisinh
* dhUusinh
* ssUsinh
* vRasinh
* nIsinh
* bhRIisinh
* bhRsinh
* mUusinh
* dRsinh
* chUsinh
* thUsinh
* nsinh
* ssUusinh
* sRsinh
* psinh
* jhRasinh
* jUusinh
* shRasinh
* hsinh
* ssRIsinh
* mRasinh
* dhRIisinh
* khRIisinh
* dhRIsinh
* llsinh
* kSssinh
* hRasinh
* bRsinh
* tRIsinh
* gRasinh
* jRIisinh
* bUsinh
* bUusinh
* sIsinh
* yUsinh
* jhRIsinh
* tRIisinh
* kSsUsinh
* bhIsinh
* nngUusinh
* jhUsinh
* bhIisinh
* kIisinh
* fUsinh
* fUusinh
* shRIsinh
* cUsinh
* dhUsinh
* pRasinh
* tthUsinh
* ddRasinh
* dhRasinh
* bhRIsinh
* bhsinh
* kUusinh
* cRIisinh
* gUsinh
* nDsinh
* fRsinh
* khRsinh
* lsinh
* chUusinh
* ttRsinh
* ssIsinh
* ssinh
* kRIsinh
* tRsinh
* gsinh
* ttUusinh
* kRIisinh
* ghIisinh
* ghRIsinh
* sRasinh
* pRsinh
* ddRIsinh
* cRIsinh
* sUusinh
* nnUusinh
* ghIsinh
* vRsinh
* ddhsinh
* tthUusinh
* pRIsinh
* pUusinh
* sssinh
* nUsinh
* cRsinh
* ddRsinh
* tIsinh
* ttRIsinh
* bRIisinh
* vRIisinh [code: no-overlaps-bit]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Check font follows the Google Fonts vertical metric schema (googlefonts/vertical_metrics)</summary>
    <div>








- ⚠️ **WARN** We recommend the absolute sum of the hhea metrics should be between 1.2-1.5x of the font's upm. This font has 1.544x (1544) (Overriden: line height is a design choice for Mooniak display faces) [code: bad-hhea-range]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (googlefonts/meta/script_lang_tags)</summary>
    <div>








- ⚠️ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Do any segments have colinear vectors? (outline_colinear_vectors)</summary>
    <div>








- ⚠️ **WARN** The following glyphs have colinear vectors:

* tThIsinh: from (913.0, 556.0) to (913.0, 556.0) is colinear with segment from (913.0, 556.0) to (913.0, 556.0)
* tThIsinh: from (894.0, 802.0) to (894.0, 802.0) is colinear with segment from (894.0, 802.0) to (894.0, 802.0)
* jIisinh: from (481.0, 705.0) to (481.0, 705.0) is colinear with segment from (481.0, 705.0) to (481.0, 705.0)
* jIisinh: from (481.0, 705.0) to (481.0, 705.0) is colinear with segment from (481.0, 705.0) to (481.0, 705.0)
* nyjIisinh: from (585.0, 705.0) to (585.0, 705.0) is colinear with segment from (585.0, 705.0) to (585.0, 705.0)
* nyjIisinh: from (585.0, 705.0) to (585.0, 705.0) is colinear with segment from (585.0, 705.0) to (585.0, 705.0)
* jRIisinh: from (481.0, 705.0) to (481.0, 705.0) is colinear with segment from (481.0, 705.0) to (481.0, 705.0)
* jRIisinh: from (481.0, 705.0) to (481.0, 705.0) is colinear with segment from (481.0, 705.0) to (481.0, 705.0)
* yasign_viramasinh: from (442.0, 594.0) to (442.0, 594.0) is colinear with segment from (442.0, 594.0) to (442.0, 594.0) [code: found-colinear-vectors]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Check the direction of the outermost contour in each glyph (outline_direction)</summary>
    <div>








- ⚠️ **WARN** The following glyphs have a counter-clockwise outer contour:

* jIisinh has a path with no bounds (probably a single point)
* nyjIisinh has a path with no bounds (probably a single point)
* tthIisinh has a path with no bounds (probably a single point)
* ddhIisinh has a path with no bounds (probably a single point)
* thIisinh has a path with no bounds (probably a single point)
* tThIisinh has a path with no bounds (probably a single point)
* jRIisinh has a path with no bounds (probably a single point) [code: ccw-outer-contour]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Do outlines contain any jaggy segments? (outline_jaggy_segments)</summary>
    <div>








- ⚠️ **WARN** The following glyphs have jaggy segments:

* uni0D85 (U+0D85): Quad(QuadBez { p0: (485.0, 406.0), p1: (477.0, 426.0), p2: (476.0, 433.0) })/Quad(QuadBez { p0: (476.0, 433.0), p1: (477.0, 382.0), p2: (477.0, 331.5) }) = 7.006799640080604 degrees
* uni0D86 (U+0D86): Quad(QuadBez { p0: (485.0, 406.0), p1: (477.0, 426.0), p2: (476.0, 433.0) })/Quad(QuadBez { p0: (476.0, 433.0), p1: (477.0, 382.0), p2: (477.0, 331.5) }) = 7.006799640080604 degrees
* uni0D87 (U+0D87): Quad(QuadBez { p0: (485.0, 406.0), p1: (477.0, 426.0), p2: (476.0, 433.0) })/Quad(QuadBez { p0: (476.0, 433.0), p1: (477.0, 382.0), p2: (477.0, 331.5) }) = 7.006799640080604 degrees
* uni0D88 (U+0D88): Quad(QuadBez { p0: (485.0, 406.0), p1: (477.0, 426.0), p2: (476.0, 433.0) })/Quad(QuadBez { p0: (476.0, 433.0), p1: (477.0, 382.0), p2: (477.0, 331.5) }) = 7.006799640080604 degrees
* uni0D8E (U+0D8E): Quad(QuadBez { p0: (1145.5, 461.5), p1: (1152.0, 450.0), p2: (1159.0, 442.0) })/Quad(QuadBez { p0: (1159.0, 442.0), p1: (1153.0, 447.0), p2: (1136.0, 464.0) }) = 9.00850374202515 degrees
* uni0D91 (U+0D91): Quad(QuadBez { p0: (401.5, 598.0), p1: (370.0, 610.0), p2: (341.0, 634.0) })/Quad(QuadBez { p0: (341.0, 634.0), p1: (363.0, 605.0), p2: (369.5, 574.0) }) = 13.204605306740262 degrees
* uni0D92 (U+0D92): Quad(QuadBez { p0: (418.5, 598.0), p1: (387.0, 610.0), p2: (358.0, 634.0) })/Quad(QuadBez { p0: (358.0, 634.0), p1: (380.0, 605.0), p2: (386.5, 574.0) }) = 13.204605306740262 degrees
* uni0D93 (U+0D93): Quad(QuadBez { p0: (895.5, 598.0), p1: (864.0, 610.0), p2: (835.0, 634.0) })/Quad(QuadBez { p0: (835.0, 634.0), p1: (857.0, 605.0), p2: (863.5, 574.0) }) = 13.204605306740262 degrees
* uni0D9A (U+0D9A): Quad(QuadBez { p0: (543.0, 477.5), p1: (490.0, 475.0), p2: (450.0, 473.0) })/Quad(QuadBez { p0: (450.0, 473.0), p1: (507.0, 462.0), p2: (550.0, 424.0) }) = 13.785209945981022 degrees
* uni0D9A (U+0D9A): Quad(QuadBez { p0: (130.0, 166.0), p1: (119.0, 195.0), p2: (97.0, 216.0) })/Quad(QuadBez { p0: (97.0, 216.0), p1: (100.0, 212.0), p2: (106.0, 201.0) }) = 9.462322208025613 degrees
* uni0DF4 (U+0DF4): Quad(QuadBez { p0: (682.0, 455.5), p1: (692.0, 444.0), p2: (693.0, 442.0) })/Quad(QuadBez { p0: (693.0, 442.0), p1: (685.0, 458.0), p2: (677.5, 482.5) }) = 0.0000012074182697257333 degrees
* uni0DF4 (U+0DF4): Quad(QuadBez { p0: (679.0, 597.0), p1: (688.0, 623.0), p2: (695.0, 636.0) })/Quad(QuadBez { p0: (695.0, 636.0), p1: (691.0, 624.0), p2: (686.0, 604.5) }) = 9.865806943084365 degrees
* uni0DF4 (U+0DF4): Quad(QuadBez { p0: (1001.5, 604.5), p1: (997.0, 624.0), p2: (993.0, 636.0) })/Quad(QuadBez { p0: (993.0, 636.0), p1: (999.0, 623.0), p2: (1008.5, 597.0) }) = 6.340191745909966 degrees
* uni0DF4 (U+0DF4): Quad(QuadBez { p0: (1010.5, 482.5), p1: (1003.0, 458.0), p2: (995.0, 442.0) })/Quad(QuadBez { p0: (995.0, 442.0), p1: (996.0, 444.0), p2: (1005.5, 455.5) }) = 0.0000012074182697257333 degrees
* uni0D9E (U+0D9E): Quad(QuadBez { p0: (350.0, 60.0), p1: (338.0, 87.0), p2: (337.0, 114.0) })/Quad(QuadBez { p0: (337.0, 114.0), p1: (336.0, 108.0), p2: (328.5, 90.0) }) = 11.583418604687026 degrees
* uni0DA3 (U+0DA3): Quad(QuadBez { p0: (135.0, 152.0), p1: (121.0, 192.0), p2: (97.0, 216.0) })/Quad(QuadBez { p0: (97.0, 216.0), p1: (112.0, 197.0), p2: (112.0, 174.0) }) = 6.709836807756896 degrees
* uni0DA3 (U+0DA3): Quad(QuadBez { p0: (456.5, 472.5), p1: (451.0, 473.0), p2: (450.0, 473.0) })/Quad(QuadBez { p0: (450.0, 473.0), p1: (535.0, 456.0), p2: (587.0, 382.0) }) = 11.309932474020227 degrees
* uni0DA4 (U+0DA4): Quad(QuadBez { p0: (525.0, 478.0), p1: (512.0, 478.0), p2: (501.0, 481.0) })/Quad(QuadBez { p0: (501.0, 481.0), p1: (576.0, 460.0), p2: (631.0, 389.0) }) = 0.38712775415007933 degrees
* uni0DAA (U+0DAA): Quad(QuadBez { p0: (361.5, 27.0), p1: (329.0, 54.0), p2: (328.0, 102.0) })/Quad(QuadBez { p0: (328.0, 102.0), p1: (327.0, 96.0), p2: (318.5, 80.0) }) = 10.655811632007621 degrees
* uni0DAB (U+0DAB): Quad(QuadBez { p0: (618.0, 270.5), p1: (605.0, 286.0), p2: (603.0, 305.0) })/Line(Line { p0: (603.0, 305.0), p1: (603.0, 288.0) }) = 6.009005957494535 degrees
* uni0DAB (U+0DAB): Quad(QuadBez { p0: (724.5, 566.5), p1: (748.0, 539.0), p2: (749.0, 498.0) })/Quad(QuadBez { p0: (749.0, 498.0), p1: (750.0, 521.0), p2: (761.0, 544.0) }) = 3.886733949295391 degrees
* uni0DAC (U+0DAC): Quad(QuadBez { p0: (432.0, 39.0), p1: (402.0, 78.0), p2: (399.0, 115.0) })/Quad(QuadBez { p0: (399.0, 115.0), p1: (393.0, 76.0), p2: (362.0, 39.0) }) = 13.381625689457877 degrees
* uni0DAC (U+0DAC): Quad(QuadBez { p0: (38.0, 365.0), p1: (38.0, 258.0), p2: (79.0, 124.0) })/Quad(QuadBez { p0: (79.0, 124.0), p1: (15.0, 256.0), p2: (15.0, 378.0) }) = 8.853809984850473 degrees
* uni0DB3 (U+0DB3): Quad(QuadBez { p0: (32.5, 449.5), p1: (21.0, 401.0), p2: (19.0, 374.0) })/Line(Line { p0: (19.0, 374.0), p1: (19.0, 380.0) }) = 4.236394799058849 degrees
* uni0DB9 (U+0DB9): Quad(QuadBez { p0: (447.0, 132.0), p1: (475.0, 132.0), p2: (507.0, 113.0) })/Quad(QuadBez { p0: (507.0, 113.0), p1: (498.0, 119.0), p2: (477.0, 131.0) }) = 2.990344975165385 degrees
* uni0DB9 (U+0DB9): Quad(QuadBez { p0: (219.0, 125.0), p1: (196.0, 111.0), p2: (186.0, 103.0) })/Quad(QuadBez { p0: (186.0, 103.0), p1: (210.0, 119.0), p2: (234.0, 126.5) }) = 4.969740728110216 degrees
* kSsasinh: Quad(QuadBez { p0: (507.0, 469.0), p1: (490.0, 469.0), p2: (472.0, 473.0) })/Quad(QuadBez { p0: (472.0, 473.0), p1: (522.0, 456.0), p2: (559.5, 418.0) }) = 6.249225513294006 degrees
* kSsasinh: Quad(QuadBez { p0: (376.0, 90.0), p1: (370.0, 108.0), p2: (370.0, 113.0) })/Quad(QuadBez { p0: (370.0, 113.0), p1: (364.0, 68.0), p2: (335.0, 34.5) }) = 7.594643368591447 degrees
* kSsasinh: Quad(QuadBez { p0: (117.5, 172.0), p1: (106.0, 201.0), p2: (84.0, 222.0) })/Quad(QuadBez { p0: (84.0, 222.0), p1: (87.0, 218.0), p2: (92.5, 207.5) }) = 9.462322208025613 degrees
* kVasinh: Quad(QuadBez { p0: (507.0, 469.0), p1: (490.0, 469.0), p2: (472.0, 473.0) })/Quad(QuadBez { p0: (472.0, 473.0), p1: (522.0, 456.0), p2: (559.5, 418.0) }) = 6.249225513294006 degrees
* kVasinh: Quad(QuadBez { p0: (376.0, 90.0), p1: (370.0, 108.0), p2: (370.0, 113.0) })/Quad(QuadBez { p0: (370.0, 113.0), p1: (364.0, 68.0), p2: (335.0, 34.5) }) = 7.594643368591447 degrees
* kVasinh: Quad(QuadBez { p0: (117.5, 172.0), p1: (106.0, 201.0), p2: (84.0, 222.0) })/Quad(QuadBez { p0: (84.0, 222.0), p1: (87.0, 218.0), p2: (92.5, 207.5) }) = 9.462322208025613 degrees
* uni0DD8 (U+0DD8): Quad(QuadBez { p0: (117.5, 461.5), p1: (124.0, 450.0), p2: (131.0, 442.0) })/Quad(QuadBez { p0: (131.0, 442.0), p1: (125.0, 447.0), p2: (108.0, 464.0) }) = 9.00850374202515 degrees
* uni0DF2 (U+0DF2): Quad(QuadBez { p0: (517.5, 461.5), p1: (524.0, 450.0), p2: (531.0, 442.0) })/Quad(QuadBez { p0: (531.0, 442.0), p1: (525.0, 447.0), p2: (508.0, 464.0) }) = 9.00850374202515 degrees
* uni0DF2 (U+0DF2): Quad(QuadBez { p0: (117.5, 461.5), p1: (124.0, 450.0), p2: (131.0, 442.0) })/Quad(QuadBez { p0: (131.0, 442.0), p1: (125.0, 447.0), p2: (108.0, 464.0) }) = 9.00850374202515 degrees
* ksinh: Quad(QuadBez { p0: (543.0, 477.5), p1: (490.0, 475.0), p2: (450.0, 473.0) })/Quad(QuadBez { p0: (450.0, 473.0), p1: (507.0, 462.0), p2: (550.0, 424.0) }) = 13.785209945981022 degrees
* ksinh: Quad(QuadBez { p0: (130.0, 166.0), p1: (119.0, 195.0), p2: (97.0, 216.0) })/Quad(QuadBez { p0: (97.0, 216.0), p1: (100.0, 212.0), p2: (106.0, 201.0) }) = 9.462322208025613 degrees
* chsinh: Quad(QuadBez { p0: (586.0, 298.0), p1: (608.0, 326.0), p2: (614.0, 375.0) })/Quad(QuadBez { p0: (614.0, 375.0), p1: (611.0, 367.0), p2: (602.0, 349.5) }) = 13.574987812753653 degrees
* nysinh: Quad(QuadBez { p0: (525.0, 478.0), p1: (512.0, 478.0), p2: (501.0, 481.0) })/Quad(QuadBez { p0: (501.0, 481.0), p1: (576.0, 460.0), p2: (631.0, 389.0) }) = 0.38712775415007933 degrees
* ddhsinh: Quad(QuadBez { p0: (361.5, 27.0), p1: (329.0, 54.0), p2: (328.0, 102.0) })/Quad(QuadBez { p0: (328.0, 102.0), p1: (327.0, 96.0), p2: (318.5, 80.0) }) = 10.655811632007621 degrees
* nnsinh: Quad(QuadBez { p0: (618.0, 270.5), p1: (605.0, 286.0), p2: (603.0, 305.0) })/Line(Line { p0: (603.0, 305.0), p1: (603.0, 288.0) }) = 6.009005957494535 degrees
* nnsinh: Quad(QuadBez { p0: (724.5, 566.5), p1: (748.0, 539.0), p2: (749.0, 498.0) })/Quad(QuadBez { p0: (749.0, 498.0), p1: (750.0, 521.0), p2: (761.0, 544.0) }) = 3.886733949295391 degrees
* nnddsinh: Quad(QuadBez { p0: (39.0, 365.0), p1: (39.0, 257.0), p2: (80.0, 125.0) })/Quad(QuadBez { p0: (80.0, 125.0), p1: (15.0, 258.0), p2: (15.0, 378.0) }) = 8.790657298396885 degrees
* ndsinh: Quad(QuadBez { p0: (32.5, 449.5), p1: (21.0, 401.0), p2: (19.0, 374.0) })/Line(Line { p0: (19.0, 374.0), p1: (19.0, 380.0) }) = 4.236394799058849 degrees
* mbsinh: Quad(QuadBez { p0: (446.0, 139.0), p1: (477.0, 139.0), p2: (505.0, 121.0) })/Quad(QuadBez { p0: (505.0, 121.0), p1: (497.0, 127.0), p2: (475.5, 139.0) }) = 4.134671373736451 degrees
* mbsinh: Quad(QuadBez { p0: (217.0, 133.0), p1: (194.0, 119.0), p2: (184.0, 111.0) })/Quad(QuadBez { p0: (184.0, 111.0), p1: (209.0, 127.0), p2: (232.5, 134.5) }) = 6.040565182897221 degrees
* kSssinh: Quad(QuadBez { p0: (488.0, 469.0), p1: (471.0, 469.0), p2: (453.0, 473.0) })/Quad(QuadBez { p0: (453.0, 473.0), p1: (503.0, 456.0), p2: (540.5, 418.0) }) = 6.249225513294006 degrees
* kSssinh: Quad(QuadBez { p0: (357.0, 90.0), p1: (351.0, 108.0), p2: (351.0, 113.0) })/Quad(QuadBez { p0: (351.0, 113.0), p1: (345.0, 68.0), p2: (316.0, 34.5) }) = 7.594643368591447 degrees
* kSssinh: Quad(QuadBez { p0: (98.5, 172.0), p1: (87.0, 201.0), p2: (65.0, 222.0) })/Quad(QuadBez { p0: (65.0, 222.0), p1: (68.0, 218.0), p2: (73.5, 207.5) }) = 9.462322208025613 degrees
* kVsinh: Quad(QuadBez { p0: (507.0, 469.0), p1: (490.0, 469.0), p2: (472.0, 473.0) })/Quad(QuadBez { p0: (472.0, 473.0), p1: (522.0, 456.0), p2: (559.5, 418.0) }) = 6.249225513294006 degrees
* kVsinh: Quad(QuadBez { p0: (376.0, 90.0), p1: (370.0, 108.0), p2: (370.0, 113.0) })/Quad(QuadBez { p0: (370.0, 113.0), p1: (364.0, 68.0), p2: (335.0, 34.5) }) = 7.594643368591447 degrees
* kVsinh: Quad(QuadBez { p0: (117.5, 172.0), p1: (106.0, 201.0), p2: (84.0, 222.0) })/Quad(QuadBez { p0: (84.0, 222.0), p1: (87.0, 218.0), p2: (92.5, 207.5) }) = 9.462322208025613 degrees
* tVsinh: Quad(QuadBez { p0: (295.5, 453.0), p1: (307.0, 477.0), p2: (329.0, 494.0) })/Quad(QuadBez { p0: (329.0, 494.0), p1: (302.0, 482.0), p2: (271.5, 454.0) }) = 13.731751492111009 degrees
* dDhsinh: Quad(QuadBez { p0: (401.0, 538.0), p1: (344.0, 554.0), p2: (293.0, 556.0) })/Quad(QuadBez { p0: (293.0, 556.0), p1: (310.0, 559.0), p2: (329.0, 559.0) }) = 12.25372236733639 degrees
* dDhsinh: Quad(QuadBez { p0: (162.5, 529.5), p1: (216.0, 558.0), p2: (293.0, 556.0) })/Quad(QuadBez { p0: (293.0, 556.0), p1: (259.0, 550.0), p2: (233.0, 532.5) }) = 11.495847330269116 degrees
* kIsinh: Quad(QuadBez { p0: (543.0, 477.5), p1: (490.0, 475.0), p2: (450.0, 473.0) })/Quad(QuadBez { p0: (450.0, 473.0), p1: (507.0, 462.0), p2: (550.0, 424.0) }) = 13.785209945981022 degrees
* kIsinh: Quad(QuadBez { p0: (130.0, 166.0), p1: (119.0, 195.0), p2: (97.0, 216.0) })/Quad(QuadBez { p0: (97.0, 216.0), p1: (100.0, 212.0), p2: (106.0, 201.0) }) = 9.462322208025613 degrees
* chIsinh: Quad(QuadBez { p0: (175.0, 711.0), p1: (228.0, 711.0), p2: (275.0, 679.0) })/Quad(QuadBez { p0: (275.0, 679.0), p1: (261.0, 693.0), p2: (255.5, 713.5) }) = 10.750966993188074 degrees
* chIsinh: Line(Line { p0: (293.0, 665.0), p1: (291.0, 666.0) })/Quad(QuadBez { p0: (291.0, 666.0), p1: (318.0, 644.0), p2: (334.5, 612.0) }) = 12.60860679336625 degrees
* jhIsinh: Quad(QuadBez { p0: (520.0, 469.0), p1: (503.0, 469.0), p2: (487.0, 472.0) })/Quad(QuadBez { p0: (487.0, 472.0), p1: (552.0, 450.0), p2: (597.0, 389.0) }) = 8.079327528025978 degrees
* jhIsinh: Quad(QuadBez { p0: (135.0, 158.0), p1: (121.0, 198.0), p2: (97.0, 222.0) })/Quad(QuadBez { p0: (97.0, 222.0), p1: (111.0, 202.0), p2: (111.0, 181.0) }) = 10.007979801441312 degrees
* jhIsinh: Quad(QuadBez { p0: (350.0, 463.0), p1: (353.0, 466.0), p2: (356.0, 467.0) })/Quad(QuadBez { p0: (356.0, 467.0), p1: (289.0, 461.0), p2: (222.0, 402.0) }) = 13.317633972949405 degrees
* nyIsinh: Quad(QuadBez { p0: (524.0, 478.0), p1: (511.0, 478.0), p2: (500.0, 481.0) })/Quad(QuadBez { p0: (500.0, 481.0), p1: (575.0, 460.0), p2: (630.0, 389.0) }) = 0.38712775415007933 degrees
* nnIsinh: Quad(QuadBez { p0: (606.0, 264.0), p1: (593.0, 279.0), p2: (591.0, 298.0) })/Quad(QuadBez { p0: (591.0, 298.0), p1: (591.0, 295.0), p2: (591.5, 291.0) }) = 6.009005957494474 degrees
* nnIsinh: Quad(QuadBez { p0: (711.0, 557.0), p1: (734.0, 530.0), p2: (736.0, 489.0) })/Quad(QuadBez { p0: (736.0, 489.0), p1: (736.0, 512.0), p2: (747.0, 534.5) }) = 2.792702365713218 degrees
* nnddIsinh: Quad(QuadBez { p0: (47.0, 250.0), p1: (57.0, 190.0), p2: (78.0, 124.0) })/Quad(QuadBez { p0: (78.0, 124.0), p1: (13.0, 259.0), p2: (13.0, 378.0) }) = 8.059829560881148 degrees
* ndIsinh: Quad(QuadBez { p0: (38.0, 467.0), p1: (22.0, 424.0), p2: (19.0, 374.0) })/Line(Line { p0: (19.0, 374.0), p1: (19.0, 380.0) }) = 3.4336303624506144 degrees
* pIsinh: Quad(QuadBez { p0: (429.5, 677.5), p1: (457.0, 698.0), p2: (493.0, 706.0) })/Quad(QuadBez { p0: (493.0, 706.0), p1: (492.0, 706.0), p2: (491.0, 707.0) }) = 12.528807709151492 degrees
* mbIsinh: Quad(QuadBez { p0: (458.0, 135.0), p1: (487.0, 135.0), p2: (519.0, 116.0) })/Quad(QuadBez { p0: (519.0, 116.0), p1: (510.0, 122.0), p2: (488.5, 134.0) }) = 2.990344975165385 degrees
* mbIsinh: Quad(QuadBez { p0: (223.0, 128.0), p1: (199.0, 114.0), p2: (189.0, 106.0) })/Quad(QuadBez { p0: (189.0, 106.0), p1: (214.0, 122.0), p2: (238.5, 129.5) }) = 6.040565182897221 degrees
* kSsIsinh: Quad(QuadBez { p0: (515.0, 469.0), p1: (498.0, 469.0), p2: (480.0, 473.0) })/Quad(QuadBez { p0: (480.0, 473.0), p1: (530.0, 456.0), p2: (567.5, 418.0) }) = 6.249225513294006 degrees
* kSsIsinh: Quad(QuadBez { p0: (384.0, 90.0), p1: (378.0, 108.0), p2: (378.0, 113.0) })/Quad(QuadBez { p0: (378.0, 113.0), p1: (372.0, 68.0), p2: (343.0, 34.5) }) = 7.594643368591447 degrees
* kSsIsinh: Quad(QuadBez { p0: (125.5, 172.0), p1: (114.0, 201.0), p2: (92.0, 222.0) })/Quad(QuadBez { p0: (92.0, 222.0), p1: (95.0, 218.0), p2: (100.5, 207.5) }) = 9.462322208025613 degrees
* kVIsinh: Quad(QuadBez { p0: (507.0, 469.0), p1: (490.0, 469.0), p2: (472.0, 473.0) })/Quad(QuadBez { p0: (472.0, 473.0), p1: (522.0, 456.0), p2: (559.5, 418.0) }) = 6.249225513294006 degrees
* kVIsinh: Quad(QuadBez { p0: (376.0, 90.0), p1: (370.0, 108.0), p2: (370.0, 113.0) })/Quad(QuadBez { p0: (370.0, 113.0), p1: (364.0, 68.0), p2: (335.0, 34.5) }) = 7.594643368591447 degrees
* kVIsinh: Quad(QuadBez { p0: (117.5, 172.0), p1: (106.0, 201.0), p2: (84.0, 222.0) })/Quad(QuadBez { p0: (84.0, 222.0), p1: (87.0, 218.0), p2: (92.5, 207.5) }) = 9.462322208025613 degrees
* kIisinh: Quad(QuadBez { p0: (543.0, 477.5), p1: (490.0, 475.0), p2: (450.0, 473.0) })/Quad(QuadBez { p0: (450.0, 473.0), p1: (507.0, 462.0), p2: (550.0, 424.0) }) = 13.785209945981022 degrees
* kIisinh: Quad(QuadBez { p0: (130.0, 166.0), p1: (119.0, 195.0), p2: (97.0, 216.0) })/Quad(QuadBez { p0: (97.0, 216.0), p1: (100.0, 212.0), p2: (106.0, 201.0) }) = 9.462322208025613 degrees
* jhIisinh: Quad(QuadBez { p0: (504.0, 469.0), p1: (487.0, 469.0), p2: (471.0, 472.0) })/Quad(QuadBez { p0: (471.0, 472.0), p1: (538.0, 449.0), p2: (582.0, 389.0) }) = 8.326849413353978 degrees
* jhIisinh: Quad(QuadBez { p0: (120.0, 158.0), p1: (104.0, 199.0), p2: (81.0, 222.0) })/Quad(QuadBez { p0: (81.0, 222.0), p1: (96.0, 203.0), p2: (96.0, 181.0) }) = 6.70983680775695 degrees
* jhIisinh: Quad(QuadBez { p0: (335.0, 463.0), p1: (338.0, 466.0), p2: (341.0, 467.0) })/Quad(QuadBez { p0: (341.0, 467.0), p1: (274.0, 461.0), p2: (206.0, 402.0) }) = 13.317633972949405 degrees
* nyIisinh: Quad(QuadBez { p0: (525.0, 478.0), p1: (512.0, 478.0), p2: (501.0, 481.0) })/Quad(QuadBez { p0: (501.0, 481.0), p1: (576.0, 460.0), p2: (631.0, 389.0) }) = 0.38712775415007933 degrees
* ddhIisinh: Quad(QuadBez { p0: (361.5, 27.0), p1: (329.0, 54.0), p2: (328.0, 102.0) })/Quad(QuadBez { p0: (328.0, 102.0), p1: (327.0, 96.0), p2: (318.5, 80.0) }) = 10.655811632007621 degrees
* nnIisinh: Quad(QuadBez { p0: (606.0, 264.0), p1: (593.0, 279.0), p2: (591.0, 298.0) })/Quad(QuadBez { p0: (591.0, 298.0), p1: (591.0, 295.0), p2: (591.5, 291.0) }) = 6.009005957494474 degrees
* nnIisinh: Quad(QuadBez { p0: (711.0, 557.0), p1: (734.0, 530.0), p2: (736.0, 489.0) })/Quad(QuadBez { p0: (736.0, 489.0), p1: (736.0, 512.0), p2: (747.0, 534.5) }) = 2.792702365713218 degrees
* nnddIisinh: Quad(QuadBez { p0: (35.0, 365.0), p1: (35.0, 257.0), p2: (76.0, 125.0) })/Quad(QuadBez { p0: (76.0, 125.0), p1: (12.0, 256.0), p2: (12.0, 378.0) }) = 8.782693283318721 degrees
* ndIisinh: Quad(QuadBez { p0: (21.5, 449.5), p1: (10.0, 401.0), p2: (8.0, 374.0) })/Line(Line { p0: (8.0, 374.0), p1: (8.0, 380.0) }) = 4.236394799058849 degrees
* mbIisinh: Quad(QuadBez { p0: (444.0, 137.0), p1: (472.0, 137.0), p2: (504.0, 118.0) })/Quad(QuadBez { p0: (504.0, 118.0), p1: (495.0, 124.0), p2: (474.0, 136.0) }) = 2.990344975165385 degrees
* mbIisinh: Quad(QuadBez { p0: (216.0, 130.0), p1: (193.0, 116.0), p2: (183.0, 108.0) })/Quad(QuadBez { p0: (183.0, 108.0), p1: (207.0, 125.0), p2: (231.0, 132.0) }) = 3.3485948144568507 degrees
* kSsIisinh: Quad(QuadBez { p0: (507.0, 469.0), p1: (490.0, 469.0), p2: (472.0, 473.0) })/Quad(QuadBez { p0: (472.0, 473.0), p1: (522.0, 456.0), p2: (559.5, 418.0) }) = 6.249225513294006 degrees
* kSsIisinh: Quad(QuadBez { p0: (376.0, 90.0), p1: (370.0, 108.0), p2: (370.0, 113.0) })/Quad(QuadBez { p0: (370.0, 113.0), p1: (364.0, 68.0), p2: (335.0, 34.5) }) = 7.594643368591447 degrees
* kSsIisinh: Quad(QuadBez { p0: (117.5, 172.0), p1: (106.0, 201.0), p2: (84.0, 222.0) })/Quad(QuadBez { p0: (84.0, 222.0), p1: (87.0, 218.0), p2: (92.5, 207.5) }) = 9.462322208025613 degrees
* kVIisinh: Quad(QuadBez { p0: (507.0, 469.0), p1: (490.0, 469.0), p2: (472.0, 473.0) })/Quad(QuadBez { p0: (472.0, 473.0), p1: (522.0, 456.0), p2: (559.5, 418.0) }) = 6.249225513294006 degrees
* kVIisinh: Quad(QuadBez { p0: (376.0, 90.0), p1: (370.0, 108.0), p2: (370.0, 113.0) })/Quad(QuadBez { p0: (370.0, 113.0), p1: (364.0, 68.0), p2: (335.0, 34.5) }) = 7.594643368591447 degrees
* kVIisinh: Quad(QuadBez { p0: (117.5, 172.0), p1: (106.0, 201.0), p2: (84.0, 222.0) })/Quad(QuadBez { p0: (84.0, 222.0), p1: (87.0, 218.0), p2: (92.5, 207.5) }) = 9.462322208025613 degrees
* dDhIisinh: Quad(QuadBez { p0: (424.0, 536.0), p1: (373.0, 550.0), p2: (327.0, 553.0) })/Quad(QuadBez { p0: (327.0, 553.0), p1: (335.0, 554.0), p2: (343.0, 554.0) }) = 10.856413348062235 degrees
* dDhIisinh: Quad(QuadBez { p0: (186.5, 531.5), p1: (245.0, 559.0), p2: (327.0, 553.0) })/Quad(QuadBez { p0: (327.0, 553.0), p1: (288.0, 550.0), p2: (258.5, 534.0) }) = 8.583621480113925 degrees
* kUsinh: Quad(QuadBez { p0: (543.0, 477.5), p1: (490.0, 475.0), p2: (450.0, 473.0) })/Quad(QuadBez { p0: (450.0, 473.0), p1: (507.0, 462.0), p2: (550.0, 424.0) }) = 13.785209945981022 degrees
* kUsinh: Quad(QuadBez { p0: (130.0, 166.0), p1: (119.0, 195.0), p2: (97.0, 216.0) })/Quad(QuadBez { p0: (97.0, 216.0), p1: (100.0, 212.0), p2: (106.0, 201.0) }) = 9.462322208025613 degrees
* jhUsinh: Quad(QuadBez { p0: (135.0, 152.0), p1: (121.0, 192.0), p2: (97.0, 216.0) })/Quad(QuadBez { p0: (97.0, 216.0), p1: (112.0, 197.0), p2: (112.0, 174.0) }) = 6.709836807756896 degrees
* jhUsinh: Quad(QuadBez { p0: (456.5, 472.5), p1: (451.0, 473.0), p2: (450.0, 473.0) })/Quad(QuadBez { p0: (450.0, 473.0), p1: (535.0, 456.0), p2: (587.0, 382.0) }) = 11.309932474020227 degrees
* nyUsinh: Quad(QuadBez { p0: (418.0, 101.5), p1: (416.0, 108.0), p2: (415.0, 112.0) })/Quad(QuadBez { p0: (415.0, 112.0), p1: (415.0, 108.0), p2: (413.0, 102.5) }) = 14.036243467926484 degrees
* nnUsinh: Quad(QuadBez { p0: (618.0, 270.5), p1: (605.0, 286.0), p2: (603.0, 305.0) })/Line(Line { p0: (603.0, 305.0), p1: (603.0, 288.0) }) = 6.009005957494535 degrees
* nnUsinh: Quad(QuadBez { p0: (724.5, 566.5), p1: (748.0, 539.0), p2: (749.0, 498.0) })/Quad(QuadBez { p0: (749.0, 498.0), p1: (750.0, 521.0), p2: (761.0, 544.0) }) = 3.886733949295391 degrees
* nnddUsinh: Quad(QuadBez { p0: (432.0, 39.0), p1: (402.0, 78.0), p2: (399.0, 115.0) })/Quad(QuadBez { p0: (399.0, 115.0), p1: (393.0, 76.0), p2: (362.0, 39.0) }) = 13.381625689457877 degrees
* nnddUsinh: Quad(QuadBez { p0: (38.0, 365.0), p1: (38.0, 258.0), p2: (79.0, 124.0) })/Quad(QuadBez { p0: (79.0, 124.0), p1: (15.0, 256.0), p2: (15.0, 378.0) }) = 8.853809984850473 degrees
* mbUsinh: Quad(QuadBez { p0: (447.0, 132.0), p1: (475.0, 132.0), p2: (507.0, 113.0) })/Quad(QuadBez { p0: (507.0, 113.0), p1: (498.0, 119.0), p2: (477.0, 131.0) }) = 2.990344975165385 degrees
* mbUsinh: Quad(QuadBez { p0: (219.0, 125.0), p1: (196.0, 111.0), p2: (186.0, 103.0) })/Quad(QuadBez { p0: (186.0, 103.0), p1: (210.0, 119.0), p2: (234.0, 126.5) }) = 4.969740728110216 degrees
* llUsinh: Quad(QuadBez { p0: (36.5, 429.0), p1: (39.0, 415.0), p2: (41.0, 406.0) })/Quad(QuadBez { p0: (41.0, 406.0), p1: (37.0, 419.0), p2: (32.5, 441.5) }) = 4.573921259900898 degrees
* kSsUsinh: Quad(QuadBez { p0: (507.0, 469.0), p1: (490.0, 469.0), p2: (472.0, 473.0) })/Quad(QuadBez { p0: (472.0, 473.0), p1: (522.0, 456.0), p2: (559.5, 418.0) }) = 6.249225513294006 degrees
* kSsUsinh: Quad(QuadBez { p0: (376.0, 90.0), p1: (370.0, 108.0), p2: (370.0, 113.0) })/Quad(QuadBez { p0: (370.0, 113.0), p1: (364.0, 68.0), p2: (335.0, 34.5) }) = 7.594643368591447 degrees
* kSsUsinh: Quad(QuadBez { p0: (117.5, 172.0), p1: (106.0, 201.0), p2: (84.0, 222.0) })/Quad(QuadBez { p0: (84.0, 222.0), p1: (87.0, 218.0), p2: (92.5, 207.5) }) = 9.462322208025613 degrees
* kVUsinh: Quad(QuadBez { p0: (507.0, 469.0), p1: (490.0, 469.0), p2: (472.0, 473.0) })/Quad(QuadBez { p0: (472.0, 473.0), p1: (522.0, 456.0), p2: (559.5, 418.0) }) = 6.249225513294006 degrees
* kVUsinh: Quad(QuadBez { p0: (376.0, 90.0), p1: (370.0, 108.0), p2: (370.0, 113.0) })/Quad(QuadBez { p0: (370.0, 113.0), p1: (364.0, 68.0), p2: (335.0, 34.5) }) = 7.594643368591447 degrees
* kVUsinh: Quad(QuadBez { p0: (117.5, 172.0), p1: (106.0, 201.0), p2: (84.0, 222.0) })/Quad(QuadBez { p0: (84.0, 222.0), p1: (87.0, 218.0), p2: (92.5, 207.5) }) = 9.462322208025613 degrees
* kUusinh: Quad(QuadBez { p0: (543.0, 477.5), p1: (490.0, 475.0), p2: (450.0, 473.0) })/Quad(QuadBez { p0: (450.0, 473.0), p1: (507.0, 462.0), p2: (550.0, 424.0) }) = 13.785209945981022 degrees
* kUusinh: Quad(QuadBez { p0: (130.0, 166.0), p1: (119.0, 195.0), p2: (97.0, 216.0) })/Quad(QuadBez { p0: (97.0, 216.0), p1: (100.0, 212.0), p2: (106.0, 201.0) }) = 9.462322208025613 degrees
* jhUusinh: Quad(QuadBez { p0: (135.0, 152.0), p1: (121.0, 192.0), p2: (97.0, 216.0) })/Quad(QuadBez { p0: (97.0, 216.0), p1: (112.0, 197.0), p2: (112.0, 174.0) }) = 6.709836807756896 degrees
* jhUusinh: Quad(QuadBez { p0: (456.5, 472.5), p1: (451.0, 473.0), p2: (450.0, 473.0) })/Quad(QuadBez { p0: (450.0, 473.0), p1: (535.0, 456.0), p2: (587.0, 382.0) }) = 11.309932474020227 degrees
* nyUusinh: Quad(QuadBez { p0: (520.0, 478.0), p1: (507.0, 478.0), p2: (495.0, 481.0) })/Quad(QuadBez { p0: (495.0, 481.0), p1: (571.0, 460.0), p2: (626.0, 389.0) }) = 1.410072899765912 degrees
* nnUusinh: Quad(QuadBez { p0: (618.0, 270.5), p1: (605.0, 286.0), p2: (603.0, 305.0) })/Line(Line { p0: (603.0, 305.0), p1: (603.0, 288.0) }) = 6.009005957494535 degrees
* nnUusinh: Quad(QuadBez { p0: (724.5, 566.5), p1: (748.0, 539.0), p2: (749.0, 498.0) })/Quad(QuadBez { p0: (749.0, 498.0), p1: (750.0, 521.0), p2: (761.0, 544.0) }) = 3.886733949295391 degrees
* nnddUusinh: Quad(QuadBez { p0: (432.0, 39.0), p1: (402.0, 78.0), p2: (399.0, 115.0) })/Quad(QuadBez { p0: (399.0, 115.0), p1: (393.0, 76.0), p2: (362.0, 39.0) }) = 13.381625689457877 degrees
* nnddUusinh: Quad(QuadBez { p0: (38.0, 365.0), p1: (38.0, 258.0), p2: (79.0, 124.0) })/Quad(QuadBez { p0: (79.0, 124.0), p1: (15.0, 256.0), p2: (15.0, 378.0) }) = 8.853809984850473 degrees
* bhUusinh: Line(Line { p0: (696.0, 10.0), p1: (629.0, -7.0) })/Line(Line { p0: (629.0, -7.0), p1: (727.0, -7.0) }) = 14.237280465761097 degrees
* mbUusinh: Quad(QuadBez { p0: (447.0, 132.0), p1: (475.0, 132.0), p2: (507.0, 113.0) })/Quad(QuadBez { p0: (507.0, 113.0), p1: (498.0, 119.0), p2: (477.0, 131.0) }) = 2.990344975165385 degrees
* mbUusinh: Quad(QuadBez { p0: (219.0, 125.0), p1: (196.0, 111.0), p2: (186.0, 103.0) })/Quad(QuadBez { p0: (186.0, 103.0), p1: (210.0, 119.0), p2: (234.0, 126.5) }) = 4.969740728110216 degrees
* shUusinh: Line(Line { p0: (626.0, -7.0), p1: (693.0, 10.0) })/Line(Line { p0: (693.0, 10.0), p1: (636.0, 10.0) }) = 14.237280465761097 degrees
* shUusinh: Line(Line { p0: (762.0, 10.0), p1: (695.0, -7.0) })/Line(Line { p0: (695.0, -7.0), p1: (793.0, -7.0) }) = 14.237280465761097 degrees
* llUusinh: Quad(QuadBez { p0: (36.5, 429.0), p1: (39.0, 415.0), p2: (41.0, 406.0) })/Quad(QuadBez { p0: (41.0, 406.0), p1: (37.0, 419.0), p2: (32.5, 441.5) }) = 4.573921259900898 degrees
* kSsUusinh: Quad(QuadBez { p0: (507.0, 469.0), p1: (490.0, 469.0), p2: (472.0, 473.0) })/Quad(QuadBez { p0: (472.0, 473.0), p1: (522.0, 456.0), p2: (559.5, 418.0) }) = 6.249225513294006 degrees
* kSsUusinh: Quad(QuadBez { p0: (376.0, 90.0), p1: (370.0, 108.0), p2: (370.0, 113.0) })/Quad(QuadBez { p0: (370.0, 113.0), p1: (364.0, 68.0), p2: (335.0, 34.5) }) = 7.594643368591447 degrees
* kSsUusinh: Quad(QuadBez { p0: (117.5, 172.0), p1: (106.0, 201.0), p2: (84.0, 222.0) })/Quad(QuadBez { p0: (84.0, 222.0), p1: (87.0, 218.0), p2: (92.5, 207.5) }) = 9.462322208025613 degrees
* kVUusinh: Quad(QuadBez { p0: (507.0, 469.0), p1: (490.0, 469.0), p2: (472.0, 473.0) })/Quad(QuadBez { p0: (472.0, 473.0), p1: (522.0, 456.0), p2: (559.5, 418.0) }) = 6.249225513294006 degrees
* kVUusinh: Quad(QuadBez { p0: (376.0, 90.0), p1: (370.0, 108.0), p2: (370.0, 113.0) })/Quad(QuadBez { p0: (370.0, 113.0), p1: (364.0, 68.0), p2: (335.0, 34.5) }) = 7.594643368591447 degrees
* kVUusinh: Quad(QuadBez { p0: (117.5, 172.0), p1: (106.0, 201.0), p2: (84.0, 222.0) })/Quad(QuadBez { p0: (84.0, 222.0), p1: (87.0, 218.0), p2: (92.5, 207.5) }) = 9.462322208025613 degrees
* kRasinh: Quad(QuadBez { p0: (543.0, 477.5), p1: (490.0, 475.0), p2: (450.0, 473.0) })/Quad(QuadBez { p0: (450.0, 473.0), p1: (507.0, 462.0), p2: (550.0, 424.0) }) = 13.785209945981022 degrees
* kRasinh: Quad(QuadBez { p0: (130.0, 166.0), p1: (119.0, 195.0), p2: (97.0, 216.0) })/Quad(QuadBez { p0: (97.0, 216.0), p1: (100.0, 212.0), p2: (106.0, 201.0) }) = 9.462322208025613 degrees
* jhRasinh: Quad(QuadBez { p0: (135.0, 152.0), p1: (121.0, 192.0), p2: (97.0, 216.0) })/Quad(QuadBez { p0: (97.0, 216.0), p1: (112.0, 197.0), p2: (112.0, 174.0) }) = 6.709836807756896 degrees
* jhRasinh: Quad(QuadBez { p0: (456.5, 472.5), p1: (451.0, 473.0), p2: (450.0, 473.0) })/Quad(QuadBez { p0: (450.0, 473.0), p1: (535.0, 456.0), p2: (587.0, 382.0) }) = 11.309932474020227 degrees
* kRIsinh: Quad(QuadBez { p0: (542.0, 477.5), p1: (489.0, 475.0), p2: (449.0, 473.0) })/Quad(QuadBez { p0: (449.0, 473.0), p1: (506.0, 462.0), p2: (549.0, 424.0) }) = 13.785209945981022 degrees
* kRIsinh: Quad(QuadBez { p0: (129.0, 166.0), p1: (118.0, 195.0), p2: (96.0, 216.0) })/Quad(QuadBez { p0: (96.0, 216.0), p1: (99.0, 212.0), p2: (105.0, 201.0) }) = 9.462322208025613 degrees
* jhRIsinh: Quad(QuadBez { p0: (520.0, 469.0), p1: (503.0, 469.0), p2: (487.0, 472.0) })/Quad(QuadBez { p0: (487.0, 472.0), p1: (552.0, 450.0), p2: (597.0, 389.0) }) = 8.079327528025978 degrees
* jhRIsinh: Quad(QuadBez { p0: (135.0, 158.0), p1: (121.0, 198.0), p2: (97.0, 222.0) })/Quad(QuadBez { p0: (97.0, 222.0), p1: (111.0, 202.0), p2: (111.0, 181.0) }) = 10.007979801441312 degrees
* jhRIsinh: Quad(QuadBez { p0: (350.0, 463.0), p1: (353.0, 466.0), p2: (356.0, 467.0) })/Quad(QuadBez { p0: (356.0, 467.0), p1: (289.0, 461.0), p2: (222.0, 402.0) }) = 13.317633972949405 degrees
* kRIisinh: Quad(QuadBez { p0: (537.0, 477.5), p1: (484.0, 475.0), p2: (444.0, 473.0) })/Quad(QuadBez { p0: (444.0, 473.0), p1: (501.0, 462.0), p2: (544.0, 424.0) }) = 13.785209945981022 degrees
* kRIisinh: Quad(QuadBez { p0: (124.0, 166.0), p1: (113.0, 195.0), p2: (91.0, 216.0) })/Quad(QuadBez { p0: (91.0, 216.0), p1: (94.0, 212.0), p2: (100.0, 201.0) }) = 9.462322208025613 degrees
* jhRIisinh: Quad(QuadBez { p0: (504.0, 469.0), p1: (487.0, 469.0), p2: (471.0, 472.0) })/Quad(QuadBez { p0: (471.0, 472.0), p1: (538.0, 449.0), p2: (582.0, 389.0) }) = 8.326849413353978 degrees
* jhRIisinh: Quad(QuadBez { p0: (120.0, 158.0), p1: (104.0, 199.0), p2: (81.0, 222.0) })/Quad(QuadBez { p0: (81.0, 222.0), p1: (96.0, 203.0), p2: (96.0, 181.0) }) = 6.70983680775695 degrees
* jhRIisinh: Quad(QuadBez { p0: (335.0, 463.0), p1: (338.0, 466.0), p2: (341.0, 467.0) })/Quad(QuadBez { p0: (341.0, 467.0), p1: (274.0, 461.0), p2: (206.0, 402.0) }) = 13.317633972949405 degrees
* yasign_iisignsinh: Quad(QuadBez { p0: (271.0, 627.0), p1: (320.0, 694.0), p2: (381.0, 694.0) })/Quad(QuadBez { p0: (381.0, 694.0), p1: (356.0, 698.0), p2: (335.5, 714.0) }) = 9.090276920822351 degrees
* yasign_iisignsinh: Quad(QuadBez { p0: (448.5, 712.0), p1: (426.0, 693.0), p2: (397.0, 693.0) })/Quad(QuadBez { p0: (397.0, 693.0), p1: (415.0, 690.0), p2: (431.0, 678.0) }) = 9.462322208025613 degrees
* dvocalicr._csinh: Quad(QuadBez { p0: (706.5, 461.5), p1: (713.0, 450.0), p2: (720.0, 442.0) })/Quad(QuadBez { p0: (720.0, 442.0), p1: (714.0, 447.0), p2: (697.0, 464.0) }) = 9.00850374202515 degrees
* dvocalicrr._csinh: Quad(QuadBez { p0: (1102.5, 461.5), p1: (1109.0, 450.0), p2: (1116.0, 442.0) })/Quad(QuadBez { p0: (1116.0, 442.0), p1: (1110.0, 447.0), p2: (1093.0, 464.0) }) = 9.00850374202515 degrees
* dvocalicrr._csinh: Quad(QuadBez { p0: (702.5, 461.5), p1: (709.0, 450.0), p2: (716.0, 442.0) })/Quad(QuadBez { p0: (716.0, 442.0), p1: (710.0, 447.0), p2: (693.0, 464.0) }) = 9.00850374202515 degrees [code: found-jaggy-segments]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Do outlines contain any semi-vertical or semi-horizontal lines? (outline_semi_vertical)</summary>
    <div>








- ⚠️ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

* cIisinh: Line(Line { p0: (16.0, 389.0), p1: (17.0, 562.0) }) (angle: 89.67 degrees, expected: 90.00 degrees)
* cIisinh: Line(Line { p0: (17.0, 562.0), p1: (282.0, 561.0) }) (angle: -0.22 degrees, expected: 0.00 degrees)
* rAaesinh: Line(Line { p0: (877.0, 788.0), p1: (878.0, 666.0) }) (angle: -89.53 degrees, expected: -90.00 degrees)
* rAaesinh: Line(Line { p0: (607.0, 426.0), p1: (606.0, 571.0) }) (angle: 90.40 degrees, expected: 90.00 degrees)
* cRIisinh: Line(Line { p0: (16.0, 389.0), p1: (17.0, 562.0) }) (angle: 89.67 degrees, expected: 90.00 degrees)
* cRIisinh: Line(Line { p0: (17.0, 562.0), p1: (282.0, 561.0) }) (angle: -0.22 degrees, expected: 0.00 degrees) [code: found-semi-vertical]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Check there are no overlapping path segments (overlapping_path_segments)</summary>
    <div>








- ⚠️ **WARN** The following glyphs have overlapping path segments:

* tThIsinh: Line(Line { p0: (913.0, 556.0), p1: (913.0, 556.0) }) has the same coordinates as a previous segment.
* tThIsinh: Line(Line { p0: (894.0, 802.0), p1: (894.0, 802.0) }) has the same coordinates as a previous segment.
* jIisinh: Line(Line { p0: (481.0, 705.0), p1: (481.0, 705.0) }) has the same coordinates as a previous segment.
* nyjIisinh: Line(Line { p0: (585.0, 705.0), p1: (585.0, 705.0) }) has the same coordinates as a previous segment.
* tthIisinh: Quad(QuadBez { p0: (346.0, 823.0), p1: (346.0, 823.0), p2: (346.0, 823.0) }) has the same coordinates as a previous segment.
* tthIisinh: Quad(QuadBez { p0: (346.0, 823.0), p1: (346.0, 823.0), p2: (346.0, 823.0) }) has the same coordinates as a previous segment.
* ddhIisinh: Quad(QuadBez { p0: (346.0, 823.0), p1: (346.0, 823.0), p2: (346.0, 823.0) }) has the same coordinates as a previous segment.
* ddhIisinh: Quad(QuadBez { p0: (346.0, 823.0), p1: (346.0, 823.0), p2: (346.0, 823.0) }) has the same coordinates as a previous segment.
* thIisinh: Quad(QuadBez { p0: (320.0, 823.0), p1: (320.0, 823.0), p2: (320.0, 823.0) }) has the same coordinates as a previous segment.
* tThIisinh: Quad(QuadBez { p0: (895.0, 823.0), p1: (895.0, 823.0), p2: (895.0, 823.0) }) has the same coordinates as a previous segment.
* jRIisinh: Line(Line { p0: (481.0, 705.0), p1: (481.0, 705.0) }) has the same coordinates as a previous segment.
* yasign_iisignsinh: Quad(QuadBez { p0: (192.0, 715.0), p1: (192.0, 715.0), p2: (192.0, 715.0) }) has the same coordinates as a previous segment.
* yasign_viramasinh: Line(Line { p0: (442.0, 594.0), p1: (442.0, 594.0) }) has the same coordinates as a previous segment. [code: overlapping-path-segments]
  
  

</div>
</details>


</div>
</details>






### Summary

| ⚠️ WARN | ℹ️ INFO | ✅ PASS | ⏩ SKIP | 
| ---|---|---|---|
| 12 | 12 | 82 | 51 | 
| 8% | 8% | 52% | 32% | 



