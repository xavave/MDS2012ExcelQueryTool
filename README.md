# MDS2012ExcelQueryTool
Master Data Services Excel Add-in Query updater - This small tool allows you to Load, Edit, and save MDS queries with operators that are not available in current mds add-in
<a href="http://legacy.averbouch.biz/master-data-services-excel-add-in-query-updater/" target="_blank">http://legacy.averbouch.biz/master-data-services-excel-add-in-query-updater/</a>

Load your already generated query

then choose a new Operator and edit the criteria

and then save the updated query

you can use all these operators:
[Description(“”)] NotSpecified,
[Description(“=”)] IsEqual,
[Description(“<>”)] IsNotEqual,
[Description(“LIKE”)] Like,
[Description(“NOT LIKE”)] NotLike,
[Description(“>”)] GreaterThan,
[Description(“< “)] LessThan, [Description(“>=”)] GreaterThanOrEqual,
[Description(“< =”)] LessThanOrEqual,
[Description(“MATCH”)] Matches,
[Description(“NOT MATCH”)] NotMatches,
[Description(“REGEX”)] ContainsPattern,
[Description(“NOT REGEX”)] NotContainsPattern,
[Description(“IS NULL”)] IsNull,
[Description(“IS NOT NULL”)] IsNotNull,
[Description(“IN”)] In,
[Description(“NOT IN”)] NotIn,
[Description(“DIRECT DECENDANTS”)] DirectDecendants,
[Description(“ALL DECENDANTS”)] AllDecendants,

More info on <a href="http://social.msdn.microsoft.com/Forums/en-US/sqlmds/thread/fdb64488-a459-43c0-be96-08344c70fbc9" target="_blank">sql mds 2012 MSDN blog</a>
