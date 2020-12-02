# Decode-Query-String
Decode the query string sent by an anti-adfraud provider to its server to reveal the fingerprint, behavioral biometrics, and other attributes it collects through javascript.

For Example,

decrypt("ZBmFdp7fYNrVNHMa$dXJsJDAkaHR0cDovL3ByaXZzZWN0b2RheS5jb20vIiwicmVmZXJyZXIkMCQiLCJhbmNlc3Rvck9yaWdpbnMkMCQiLCJ2aWRlbyQwJDE5MjB4MTIwMHgyNCIsImZyYW1lJDAkMCIsImhpZGRlbiQwJDAiLCJ2aXNpYmlsaXR5U3RhdGUkMCR2aXNpYmxlIiwiaGFzRm9jdXMkMCQxIiwid2luZG93JDEkMTM1eDEwNjAiLCJpbm5lciQxJDE1MHgxMDc1Iiwib3V0ZXIkMSQxMzU0eDExNDciLCJsb2NhbFN0b3JhZ2UkMSQxIiwic2Vzc2lvblN0b3JhZ2UkMSQxIiwiYXBwQ29kZU5hbWUkMSRNb3ppbGxhIiwiYXBwTmFtZSQxJE5ldHNjYXBlIiwiYXBwVmVyc2lvbiQx");

will return:

["url", http://privsectoday.com/", 0"]
["referrer", ", 0"]
["ancestorOrigins", ", 0"]
["video", 1920x1200x24", 0"]
["frame", 0", 0"]
["hidden", 0", 0"]
["visibilityState", visible", 0"]
["hasFocus", 1", 0"]
["window", 135x1060", 1"]
["inner", 150x1075", 1"]
["outer", 1354x1147", 1"]
["localStorage", 1", 1"]
["sessionStorage", 1", 1"]
["appCodeName", Mozilla", 1"]
["appName", Netscape", 1"]
