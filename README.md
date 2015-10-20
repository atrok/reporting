# reporting
processing of logfiles to get performance metrics based on message rates

how to run
=============
from command line:

awk -f count_v2_response_rate ../ServiceRequests/CareFirst/1632345/attachments/unpacked/CSP/sr0001632345/ProxyConfiglogs/1310/CS_Proxy_RR.20151013_1350*

awk -f count_v2_response_rate ../ServiceRequests/CareFirst/1632345/attachments/unpacked/CSP/sr0001632345/ProxyConfiglogs/1310/CS_Proxy_RR.20151013_1350* > result.log
