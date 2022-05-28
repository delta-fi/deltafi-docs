# Oracle Failures

Various oracle failure detections have been implemented. For example, prices in two consecutive slots should not be too different. Too big a price deviation in two consecutive slots are therefore detected as an oracle failure. Trades are disabled in such cases.
