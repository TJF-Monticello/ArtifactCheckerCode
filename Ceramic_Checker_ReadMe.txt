Return artifacts that meet the following criteria:
	Are from a given project and cataloguer (user ID)

1.0 Measurements missing:
	Sherd Weight is blank (Weight cannot be left null. If translating from old data/records, enter "0.01" as placeholder)
	Quantity is greater than one and Max Sherd Measurement is greater than 15mm, but Ware Type is not 'Colonoware', 'Coarse Earthenware, unidentified', 'Refined Earthenware, modern' (Ware types with different batching protocols are excluded from rule that there is no batching sherds over 15mm. )
	Quantity is greater than one and Max Sherd Measurement is greater than 15mm, but Form is not "Flower Pot" (Only modern Flower Pots can be batched regardless of size)
	Quantity is "1" and Max Sherd Measurement is empty (null) but the Notes do not contain the phrase "not found" (Max sherd size required unless sherd is missing from artifact bag/object)
	Quantity is "1" and Completeness contains the word "rim" but Rim Length is blank (null); neither Interior nor Exterior glaze is entered as "Missing"; Use Wear Pattern tab is empty (null); and the Notes do not include the word "able" (All rim sherds not meeting those conditions need to record rim lengths)
	Rim Length is greater than 30mm but Rim Diameter is empty (null); Notes do not include the words "not" or "able"; Form is not "Flower Pot"; and Genre ID is not '23' or '24' (All rim sherds not meeting those conditions and over 30mm in size need to have an estimated diameter recorded)
	Quantity is "1" but Sherd Thickness is blank (null); Notes do not include the words "not,"batch," or "unable"; Use Wear Pattern tab is blank (null); and neither interior nor exterior glaze is recorded as "Missing Surface" (Sherds not meeting those conditions must have sherd thickness recorded)

2.0 Form and Category Mismatches:
	Material is "Coarse EW" and Ware is like "Caribbean" (not sure why this is in there)
	Form is "Saucer" but Category is "Hollow" (should be "Flat")
	Form is "Plate" and Category is "Hollow" (should be "Flat")
	
3.0 Decoration:	
	Quantity is "1" and Decoration Technique is blank (null) but Genre is recorded as something besides "Not Applicable" or "Victorian Majolica" (All other genres require the decoration technique to be recorded)
	Quantity is "1" and Decoration Technique is blank (null) but Decoration Yes/No field is recorded as "Yes" (Decoration tab should be filled out)
	Decoration Technique contains information (not null) but Decoration Yes/No field is recorded as "No" (If Decoration tab contains data, the Decoration Y/N should be "Yes")

4.0 Glaze:
	Exterior Glaze Opacity is something other than "Not Applicable" but Material is not "Coarse EW" (Opacity only used with Coarse EW)
	Interior Glaze Opacity is something other than "Not Applicable" but Material is not "Coarse EW" (Opacity only used with Coarse EW)
	Exterior Glaze Opacity is "Not Applicable" but Material is "Coarse EW" and Exterior Surface does not contain the words "Unglazed," "Missing Surface," or "Wash" (Exterior Glaze Opacity needs to be recorded)
	Interior Glaze Opacity is "Not Applicable" but Material is "Coarse EW" and Interior Surface does not contain the words "Unglazed," "Missing Surface," or "Wash" (Interior Glaze Opacity needs to be recorded)
	
5.0 Mends:
	Mended Yes/No is "Yes" but Mended Form (on Mends tab) is "Not Mended" (If Mended Yes/No indicates a mend, then Mends tab must be completed)
	Mended Yes/No is "Yes, Physically" but Mended Sherd Weight is blank (null) (Mended weight required)
	Notes include word "mended" but not words "not," "fresh," or "after" and Mended Form is "Not Mended" (unless there is a fresh break or other exception noted in the notes, all mended sherds should have mended information filled out in fields on the main tab and Mends tab)
	Mended Form is "Not Mended or "Not Applicable" but Mended Yes/No is "Yes" (Mended Yes/No should be "No")
	Mended Form is something other than "Not Recorded" or "Not Applicable" but Mended Yes/No is "No" (Mended Yes/No should be "Yes")

	Order by Artifact ID