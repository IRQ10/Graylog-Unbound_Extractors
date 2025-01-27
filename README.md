# Graylog-Unbound_Extractors
#
#Extractors for Graylog to parse Unbound DNS query messages from OPNsense firewall
#
#
# These GROK extractors are designed for OPNsense Unbound DNS messages.
# OPNsense -> Services -> Unbound DNS -> Advanced
# Check "Log Queries", "Log Replies", and "Tag Queries and Replies" - Be sure to click 'Apply'
#
# Optional
# Add a Graylog input for Unbound messages. OPNsense makes it easy to send specific messages to different inputs.
# When adding the target input in Graylog ensure you enable "Store full message"
#
# OPNsense -> System -> Settings -> Logging 
# Remote Tab -> "+" Add a new entry
# Applications -- Select "resolver (unbound)"
# rfc5424 - check to enable
# Click "Save" and "Apply"
#
12/2/21 - Initial commit.
1/27/25 - Update
