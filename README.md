# mstr-metricDrilldown
MicroStrategy snippet to enable linking from metrics to e.g. drilldown documents of 


HTML Output metric:
<a abv=[ConcatAggMetric] href=URL onmouseover=JavaScript builidng the link dynamically> [KPI value Metric] </a>
Concat => get all parts together
    
Structure:
a => link tag
abv => arbirtary attribute name to store ConcatAGG values
href => stores the link that will be updaten on mouse over
KPI is metric we want to display
target => where should link open _self, _blank
    
Event triggering the link creation:
