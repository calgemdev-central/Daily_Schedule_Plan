ABDWLOC Inspection Map - README
==============================

WHAT IT IS
A single HTML page that plots ABDWLOC re-inspections, original inspections and
Daily Schedule events on a map for field planning. Nothing to install.

HOW TO USE
1. Double-click ABDWLOC_Map.html (Chrome or Edge). An internet connection is
   needed for the map background.
2. Drag a spreadsheet (.xlsx) into the box at the top left, or click the box to
   browse. You can load an ABDWLOC export, a Daily Schedule, or both. The page
   detects which is which.
3. Use the Layers, Field, Operator and Well Status checkboxes, or the search box,
   to filter. Hover a marker for details. Click a marker for Directions.
4. Loaded files reopen automatically next time. Use "remove" to drop a file.

MARKERS
  Magenta diamond "R"  ABDWLOC re-inspection (AW Eval = Fail, or Ready for RI = Y)
  Teal square "O"      ABDWLOC original inspection (no AW result yet), or an
                       ABDWLOC event on the schedule
  Amber triangle "S"   Schedule surface plug event
  Blue dot             Other schedule events
  Wells with AW Eval = Pass are not shown.
  A marker notes when a well is on both the ABDWLOC list and the schedule.

SPREADSHEET REQUIREMENTS
  ABDWLOC export: Latitude, Longitude and AWEval columns (standard export headers).
  Daily Schedule: Lat, Long and Event Type columns ("FEU 2" tab preferred).
