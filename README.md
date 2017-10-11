# MS430056-RomRaider-ECU-Definition

### TODO

* See list of issues
* Assign correct log parameters to units for proper live tracing
* Rename maps to include meaningful name
* Add meaningful descriptions

### Q&A

#### What is this?
This is MS430056 ecu definitions xml file for RomRaider.

#### Where did it come from?
It was automatically converted from DAMOS (A2L) file from [this thread](http://www.romraider.com/forum/viewtopic.php?f=43&t=14111&sid=2396e879abbbaa71987613262ac2d56a).

#### Why is it better than already existing ecu definitions file?
It is not. It simply includes all (except a few) maps that were described in DAMOS (A2L) file. JUst like with XDF file for TunerPro, this ecu definitions file will need work done to it. That includes, mapping correct live tracing params, renaming standard map names, adding meaningful descriptions, and so on.

#### It takes a while for RomRaider to load a flash with this ecu definitions file. Why is that?
Since this ecu definitions files includes so many maps, loading data for all of them takes a while.
