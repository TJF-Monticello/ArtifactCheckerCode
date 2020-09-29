Return artifacts that meet the following criteria:
	Are from a given project and cataloguer (user name)

1.0 Measurements Missing:
	Weight is null and Notes field does not contain the word "weight" (Weight cannot be blank. If translating from old data/records, then put in 0.01 as a placeholder)

2.0 Nail Mismatches:
	Form is "Nail" and Completeness is "Incomplete" (Terms that should be used are "Shank," "Complete," "Head and Shank", etc)
	Form is "Nail" but Nail Head Type is "Flaw, Anvil" or "Flaw, Hardy" (Form should be "Nail, waster")
	Form is "Nail" and ManuTech is "Wrought/Forged" but "Nail Head Type" is "Unidentifiable" (Nail Head Type should be "Wrought, unid")
	Form is "Nail" and Completeness is "Complete" and ManuTech is not "Drawn/Wire" but Nail Length is Null or 0; All complete non-drawn/wire nails should have lengths
	Form is "Nail" and Completeness is "Complete" and ManuTech is not "Drawn/Wire" but Head and End Types are entered as "Not Recorded" (All non-drawn/wire nails should have identified/specific Head and Tip Types recorded)
	Form is "Nail" and ManuTech is "Indeterminate" ("Unidentifiable" or "Not a Wire Nail" should be used)
	Form is "Nail" and ManuTech is "Cut" ("Machine Cut" should be used)

3.0 Form, Manutech, Material Mismatches or Use of Terms that have been phased out:
	Material is "Mortar" but the Form begins with "Axe" (Form should be "Mortar")
	Material is "Ferricrete/Bog Iron" but the Form is not "Pebble"; Material is likely incorrect ("Iron" should probably be selected)
	Material is "Plaster/Mortar" or Form is "Plaster/Mortar" (Both should be plaster or mortar)
	Form is "Brick/Daub" and Material is not "Brick/Daub" (Either form should be something other than 'Brick/Daub' or material should be 'Brick, [appropriate color]')
	Form is "Stone, unidentified" (Stone-related forms most likely should be "Pebble," "Cobble," "Boulder," or in some cases "Architecture, unid," "Flake," etc)