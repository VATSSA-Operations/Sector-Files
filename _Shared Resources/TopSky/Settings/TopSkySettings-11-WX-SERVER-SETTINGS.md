// ##################################################################
//                 #11 WX SERVER SETTINGS v0.1
// ##################################################################

// MET Settings (METAR, TAF & SIGMET)
HTTP_METAR_Server=https://aviationweather.gov/
HTTP_METAR_Page_Prefix=adds/dataserver_current/httpparam?dataSource=metars&requestType=retrieve&format=xml&stationString=
HTTP_METAR_Page_Suffix=&hoursBeforeNow=1&mostRecentForEachStation=true&fields=raw_text
HTTP_METAR_Data_Prefix=<raw_text>
HTTP_METAR_Data_Suffix=</raw_text>

HTTP_TAF_Server=https://aviationweather.gov/
HTTP_TAF_Page_Prefix=adds/dataserver_current/httpparam?dataSource=tafs&requestType=retrieve&format=xml&stationString=
HTTP_TAF_Page_Suffix=&hoursBeforeNow=1&mostRecentForEachStation=true&fields=raw_text
HTTP_TAF_Data_Prefix=<raw_text>
HTTP_TAF_Data_Suffix=</raw_text>

HTTP_SIGMET_Server=https://aviationweather.gov/
HTTP_SIGMET_Page_Prefix=data/iffdp/
HTTP_SIGMET_Pages=6448
HTTP_SIGMET_Page_Suffix=.txt