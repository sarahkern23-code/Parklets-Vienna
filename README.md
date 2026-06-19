# Project Title: Vienna's Grätzloasen Dataset

## Description
This dataset contains information regarding the location and characteristics of Grätzloasen in Vienna (1 - 9th district). It serves as a comprehensive overview of urban micro-spaces and their amenities for public use.

## Data Structure (Attributes)
	⁃	fid: Unique identifier for each Grätzloase
	⁃	District: Administrative district of the Grätzloase (1-9)
	⁃	Name: Name of the parklet installation
	⁃	Address: Physical location/street address
	⁃	Type: Type of Grätzloase (Grüne Parklets, Grätzleben or Junge Grätzl)
	⁃	State: Current status (Planned, Existing, Non existing)
	⁃	Operator: Entity responsible for the Grätzloase
	⁃	Opening: When it has been opened
	⁃	Seating YN: Indicates if seating is available (false/true)
	⁃	Seating: Type of seating (Bench, Chair, Picnic table)
	⁃	Num_seat: Total count of available seats (<=4, 4 to <=10, >10)
	⁃	Covered: Presence of a roof (Not Covered, Partly Covered, Fully Covered)
	⁃	Art: Presence of artistic elements (false/true)
	⁃	Plants: Presence of vegetation (false/true)
	⁃	Plant type: Specific types of vegetation used (Flowers, Eatable, Large plants, Small plants)
	⁃	Access: Accessibility information (false/true)
	⁃	Condition: Current maintenance state of the parklet (good, medium, bad)
	⁃	Extras: Additional amenities (Books, Garbage can, Bike stands)
	⁃	Image: Path to the corresponding photo
	⁃	Other: Other additional information and other extras


## Methodology
The dataset was created by merging multiple sources using QGIS. Data cleaning and attribute standardization were performed to ensure consistency across the entries.

## License
This work is licensed under the CC0-1.0.

## Dataset
The images for this project can be downloaded here:
[Click here to download the dataset] (https://drive.google.com/drive/folders/16Pg_Z7sDweAtR_P6FGIpPbpZnaFqpLpY?usp=share_link)
