# log-parser
Above dataset is access log of NASA Kennedy Space Center WWW server in Florida.

The logs are an ASCII file with one line per request, with the following columns:

   - host - making the request. A hostname when possible, otherwise the Internet address if the name could not be looked up.
   - timestamp - in the format "DAY MON DD HH:MM:SS YYYY", where DAY is the day of the week, MON is the name of the month, DD is the day of the month, HH:MM:SS is the time of day using a 24-hour clock, and YYYY is the year. The timezone is -0400.
   - request URL - given in quotes.
   - HTTP reply code.
   - Bytes returned by the server.
