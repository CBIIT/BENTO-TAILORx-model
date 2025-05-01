<link rel='stylesheet' href="assets/style.css">
<link rel='stylesheet' href="https://unpkg.com/leaflet@1.5.1/dist/leaflet.css" integrity="sha512-xwE/Az9zrjBIphAcBb3F6JVqxf46+CDLwfLMHloNu6KEQCAWi6HcDUbeOfBIptF7tcCzusKFjFw2yuvEpDL9wQ==" crossorigin="">
<script type="text/javascript" src="https://code.jquery.com/jquery-3.2.1.min.js"></script>
<script type="text/javascript"  src="https://unpkg.com/leaflet@1.5.1/dist/leaflet.js"></script>
<script type="text/javascript" src="assets/actions.js"></script>

# BENTO-TAILORx Data Model

The Bento Core Data Model supports the Bento software framework that has been developed to stand up data sharing platforms for clinical trials and research programs. Modern clinical trials and research programs generate large volumes of complex biomedical data types. To address this complexity, the Bento Core Data model uses a graph structure to model a clinical trial workflow.  Key trial entities are modelled as node types, while the association between nodes are explicitly modelled as relationship types.

The Bento Core Data Model has been extended to fit the TAILORx clinical data set. The extended model, also called the BENTO_TAILORx data model, comprises of 20 node types and 37 relationship types. Both nodes and relationships store data attributes in the form of properties. These data attributes are listed in the section BENTO_TAILORx Attribute Types. The BENTO_TAILORx graph data model has been implemented in Neo4J, a commercial graph database platform.



Zoom to Node: <select id="node_select">
  <option value="">Zoom to Node</option>
</select>
<div id="model"></div>

<p>
<a href="./model-desc/bento-tailorx-model.svg">SVG file (in view above)</a>
<p>
<a href="./model-desc">Additional model files</a>
<div id='graph' style='display:off;'>
<svg width="4375pt" height="4128pt"
 viewBox="0.00 0.00 4374.74 4128.00" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink">
<g id="graph0" class="graph" transform="scale(1 1) rotate(0) translate(4 4124)">
<title>Perl</title>
<polygon fill="#ffffff" stroke="transparent" points="-4,4 -4,-4124 4370.7355,-4124 4370.7355,4 -4,4"/>
<!-- file -->
<g id="node1" class="node">
<title>file</title>
<path fill="none" stroke="#000000" d="M2233.2355,-3889.5C2233.2355,-3889.5 2418.2355,-3889.5 2418.2355,-3889.5 2424.2355,-3889.5 2430.2355,-3895.5 2430.2355,-3901.5 2430.2355,-3901.5 2430.2355,-4107.5 2430.2355,-4107.5 2430.2355,-4113.5 2424.2355,-4119.5 2418.2355,-4119.5 2418.2355,-4119.5 2233.2355,-4119.5 2233.2355,-4119.5 2227.2355,-4119.5 2221.2355,-4113.5 2221.2355,-4107.5 2221.2355,-4107.5 2221.2355,-3901.5 2221.2355,-3901.5 2221.2355,-3895.5 2227.2355,-3889.5 2233.2355,-3889.5"/>
<text text-anchor="middle" x="2240.7355" y="-4000.8" font-family="Times,serif" font-size="14.00" fill="#000000">file</text>
<polyline fill="none" stroke="#000000" points="2260.2355,-3889.5 2260.2355,-4119.5 "/>
<text text-anchor="middle" x="2270.7355" y="-4000.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="2281.2355,-3889.5 2281.2355,-4119.5 "/>
<text text-anchor="middle" x="2345.2355" y="-4104.3" font-family="Times,serif" font-size="14.00" fill="#000000">acl</text>
<polyline fill="none" stroke="#000000" points="2281.2355,-4096.5 2409.2355,-4096.5 "/>
<text text-anchor="middle" x="2345.2355" y="-4081.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_description</text>
<polyline fill="none" stroke="#000000" points="2281.2355,-4073.5 2409.2355,-4073.5 "/>
<text text-anchor="middle" x="2345.2355" y="-4058.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_format</text>
<polyline fill="none" stroke="#000000" points="2281.2355,-4050.5 2409.2355,-4050.5 "/>
<text text-anchor="middle" x="2345.2355" y="-4035.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_id</text>
<polyline fill="none" stroke="#000000" points="2281.2355,-4027.5 2409.2355,-4027.5 "/>
<text text-anchor="middle" x="2345.2355" y="-4012.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_location</text>
<polyline fill="none" stroke="#000000" points="2281.2355,-4004.5 2409.2355,-4004.5 "/>
<text text-anchor="middle" x="2345.2355" y="-3989.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_name</text>
<polyline fill="none" stroke="#000000" points="2281.2355,-3981.5 2409.2355,-3981.5 "/>
<text text-anchor="middle" x="2345.2355" y="-3966.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_size</text>
<polyline fill="none" stroke="#000000" points="2281.2355,-3958.5 2409.2355,-3958.5 "/>
<text text-anchor="middle" x="2345.2355" y="-3943.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_status</text>
<polyline fill="none" stroke="#000000" points="2281.2355,-3935.5 2409.2355,-3935.5 "/>
<text text-anchor="middle" x="2345.2355" y="-3920.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_type</text>
<polyline fill="none" stroke="#000000" points="2281.2355,-3912.5 2409.2355,-3912.5 "/>
<text text-anchor="middle" x="2345.2355" y="-3897.3" font-family="Times,serif" font-size="14.00" fill="#000000">md5sum</text>
<polyline fill="none" stroke="#000000" points="2409.2355,-3889.5 2409.2355,-4119.5 "/>
<text text-anchor="middle" x="2419.7355" y="-4000.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- study_subject -->
<g id="node2" class="node">
<title>study_subject</title>
<path fill="none" stroke="#000000" d="M1311.2355,-1421.5C1311.2355,-1421.5 1668.2355,-1421.5 1668.2355,-1421.5 1674.2355,-1421.5 1680.2355,-1427.5 1680.2355,-1433.5 1680.2355,-1433.5 1680.2355,-1823.5 1680.2355,-1823.5 1680.2355,-1829.5 1674.2355,-1835.5 1668.2355,-1835.5 1668.2355,-1835.5 1311.2355,-1835.5 1311.2355,-1835.5 1305.2355,-1835.5 1299.2355,-1829.5 1299.2355,-1823.5 1299.2355,-1823.5 1299.2355,-1433.5 1299.2355,-1433.5 1299.2355,-1427.5 1305.2355,-1421.5 1311.2355,-1421.5"/>
<text text-anchor="middle" x="1357.2355" y="-1624.8" font-family="Times,serif" font-size="14.00" fill="#000000">study_subject</text>
<polyline fill="none" stroke="#000000" points="1415.2355,-1421.5 1415.2355,-1835.5 "/>
<text text-anchor="middle" x="1425.7355" y="-1624.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1436.2355,-1421.5 1436.2355,-1835.5 "/>
<text text-anchor="middle" x="1547.7355" y="-1820.3" font-family="Times,serif" font-size="14.00" fill="#000000">case_report_form_submitted</text>
<polyline fill="none" stroke="#000000" points="1436.2355,-1812.5 1659.2355,-1812.5 "/>
<text text-anchor="middle" x="1547.7355" y="-1797.3" font-family="Times,serif" font-size="14.00" fill="#000000">consent_type</text>
<polyline fill="none" stroke="#000000" points="1436.2355,-1789.5 1659.2355,-1789.5 "/>
<text text-anchor="middle" x="1547.7355" y="-1774.3" font-family="Times,serif" font-size="14.00" fill="#000000">consent_withdrawn</text>
<polyline fill="none" stroke="#000000" points="1436.2355,-1766.5 1659.2355,-1766.5 "/>
<text text-anchor="middle" x="1547.7355" y="-1751.3" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_consent</text>
<polyline fill="none" stroke="#000000" points="1436.2355,-1743.5 1659.2355,-1743.5 "/>
<text text-anchor="middle" x="1547.7355" y="-1728.3" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_lost_to_followup</text>
<polyline fill="none" stroke="#000000" points="1436.2355,-1720.5 1659.2355,-1720.5 "/>
<text text-anchor="middle" x="1547.7355" y="-1705.3" font-family="Times,serif" font-size="14.00" fill="#000000">disease_subtype</text>
<polyline fill="none" stroke="#000000" points="1436.2355,-1697.5 1659.2355,-1697.5 "/>
<text text-anchor="middle" x="1547.7355" y="-1682.3" font-family="Times,serif" font-size="14.00" fill="#000000">disease_type</text>
<polyline fill="none" stroke="#000000" points="1436.2355,-1674.5 1659.2355,-1674.5 "/>
<text text-anchor="middle" x="1547.7355" y="-1659.3" font-family="Times,serif" font-size="14.00" fill="#000000">in_analysis</text>
<polyline fill="none" stroke="#000000" points="1436.2355,-1651.5 1659.2355,-1651.5 "/>
<text text-anchor="middle" x="1547.7355" y="-1636.3" font-family="Times,serif" font-size="14.00" fill="#000000">index_date</text>
<polyline fill="none" stroke="#000000" points="1436.2355,-1628.5 1659.2355,-1628.5 "/>
<text text-anchor="middle" x="1547.7355" y="-1613.3" font-family="Times,serif" font-size="14.00" fill="#000000">lost_to_followup</text>
<polyline fill="none" stroke="#000000" points="1436.2355,-1605.5 1659.2355,-1605.5 "/>
<text text-anchor="middle" x="1547.7355" y="-1590.3" font-family="Times,serif" font-size="14.00" fill="#000000">pool</text>
<polyline fill="none" stroke="#000000" points="1436.2355,-1582.5 1659.2355,-1582.5 "/>
<text text-anchor="middle" x="1547.7355" y="-1567.3" font-family="Times,serif" font-size="14.00" fill="#000000">primary_site</text>
<polyline fill="none" stroke="#000000" points="1436.2355,-1559.5 1659.2355,-1559.5 "/>
<text text-anchor="middle" x="1547.7355" y="-1544.3" font-family="Times,serif" font-size="14.00" fill="#000000">status</text>
<polyline fill="none" stroke="#000000" points="1436.2355,-1536.5 1659.2355,-1536.5 "/>
<text text-anchor="middle" x="1547.7355" y="-1521.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_subject_first_name</text>
<polyline fill="none" stroke="#000000" points="1436.2355,-1513.5 1659.2355,-1513.5 "/>
<text text-anchor="middle" x="1547.7355" y="-1498.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_subject_id</text>
<polyline fill="none" stroke="#000000" points="1436.2355,-1490.5 1659.2355,-1490.5 "/>
<text text-anchor="middle" x="1547.7355" y="-1475.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_subject_is_ref</text>
<polyline fill="none" stroke="#000000" points="1436.2355,-1467.5 1659.2355,-1467.5 "/>
<text text-anchor="middle" x="1547.7355" y="-1452.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_subject_source_id</text>
<polyline fill="none" stroke="#000000" points="1436.2355,-1444.5 1659.2355,-1444.5 "/>
<text text-anchor="middle" x="1547.7355" y="-1429.3" font-family="Times,serif" font-size="14.00" fill="#000000">taxon</text>
<polyline fill="none" stroke="#000000" points="1659.2355,-1421.5 1659.2355,-1835.5 "/>
<text text-anchor="middle" x="1669.7355" y="-1624.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- file&#45;&gt;study_subject -->
<g id="edge8" class="edge">
<title>file&#45;&gt;study_subject</title>
<path fill="none" stroke="#000000" d="M2430.3383,-3981.4476C2573.9877,-3942.9147 2814.7355,-3850.6435 2814.7355,-3665 2814.7355,-3665 2814.7355,-3665 2814.7355,-2511.5 2814.7355,-2233.8747 2979.4306,-2099.4709 2800.7355,-1887 2660.7062,-1720.5031 2022.1582,-1659.2178 1690.7282,-1638.3488"/>
<polygon fill="#000000" stroke="#000000" points="1690.7254,-1634.842 1680.527,-1637.7132 1690.2899,-1641.8284 1690.7254,-1634.842"/>
<text text-anchor="middle" x="2890.2355" y="-3157.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_of_study_subject</text>
</g>
<!-- sample -->
<g id="node8" class="node">
<title>sample</title>
<path fill="none" stroke="#000000" d="M3045.2355,-1887.5C3045.2355,-1887.5 3468.2355,-1887.5 3468.2355,-1887.5 3474.2355,-1887.5 3480.2355,-1893.5 3480.2355,-1899.5 3480.2355,-1899.5 3480.2355,-2473.5 3480.2355,-2473.5 3480.2355,-2479.5 3474.2355,-2485.5 3468.2355,-2485.5 3468.2355,-2485.5 3045.2355,-2485.5 3045.2355,-2485.5 3039.2355,-2485.5 3033.2355,-2479.5 3033.2355,-2473.5 3033.2355,-2473.5 3033.2355,-1899.5 3033.2355,-1899.5 3033.2355,-1893.5 3039.2355,-1887.5 3045.2355,-1887.5"/>
<text text-anchor="middle" x="3067.2355" y="-2182.8" font-family="Times,serif" font-size="14.00" fill="#000000">sample</text>
<polyline fill="none" stroke="#000000" points="3101.2355,-1887.5 3101.2355,-2485.5 "/>
<text text-anchor="middle" x="3111.7355" y="-2182.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="3122.2355,-1887.5 3122.2355,-2485.5 "/>
<text text-anchor="middle" x="3290.7355" y="-2470.3" font-family="Times,serif" font-size="14.00" fill="#000000">analysis_area</text>
<polyline fill="none" stroke="#000000" points="3122.2355,-2462.5 3459.2355,-2462.5 "/>
<text text-anchor="middle" x="3290.7355" y="-2447.3" font-family="Times,serif" font-size="14.00" fill="#000000">analysis_area_percentage_glass</text>
<polyline fill="none" stroke="#000000" points="3122.2355,-2439.5 3459.2355,-2439.5 "/>
<text text-anchor="middle" x="3290.7355" y="-2424.3" font-family="Times,serif" font-size="14.00" fill="#000000">analysis_area_percentage_pigmented_tumor</text>
<polyline fill="none" stroke="#000000" points="3122.2355,-2416.5 3459.2355,-2416.5 "/>
<text text-anchor="middle" x="3290.7355" y="-2401.3" font-family="Times,serif" font-size="14.00" fill="#000000">analysis_area_percentage_stroma</text>
<polyline fill="none" stroke="#000000" points="3122.2355,-2393.5 3459.2355,-2393.5 "/>
<text text-anchor="middle" x="3290.7355" y="-2378.3" font-family="Times,serif" font-size="14.00" fill="#000000">analysis_area_percentage_tumor</text>
<polyline fill="none" stroke="#000000" points="3122.2355,-2370.5 3459.2355,-2370.5 "/>
<text text-anchor="middle" x="3290.7355" y="-2355.3" font-family="Times,serif" font-size="14.00" fill="#000000">catalog_reference</text>
<polyline fill="none" stroke="#000000" points="3122.2355,-2347.5 3459.2355,-2347.5 "/>
<text text-anchor="middle" x="3290.7355" y="-2332.3" font-family="Times,serif" font-size="14.00" fill="#000000">comment</text>
<polyline fill="none" stroke="#000000" points="3122.2355,-2324.5 3459.2355,-2324.5 "/>
<text text-anchor="middle" x="3290.7355" y="-2309.3" font-family="Times,serif" font-size="14.00" fill="#000000">composition</text>
<polyline fill="none" stroke="#000000" points="3122.2355,-2301.5 3459.2355,-2301.5 "/>
<text text-anchor="middle" x="3290.7355" y="-2286.3" font-family="Times,serif" font-size="14.00" fill="#000000">current_weight</text>
<polyline fill="none" stroke="#000000" points="3122.2355,-2278.5 3459.2355,-2278.5 "/>
<text text-anchor="middle" x="3290.7355" y="-2263.3" font-family="Times,serif" font-size="14.00" fill="#000000">date_of_sample_collection</text>
<polyline fill="none" stroke="#000000" points="3122.2355,-2255.5 3459.2355,-2255.5 "/>
<text text-anchor="middle" x="3290.7355" y="-2240.3" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_collection</text>
<polyline fill="none" stroke="#000000" points="3122.2355,-2232.5 3459.2355,-2232.5 "/>
<text text-anchor="middle" x="3290.7355" y="-2217.3" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_sample_procurement</text>
<polyline fill="none" stroke="#000000" points="3122.2355,-2209.5 3459.2355,-2209.5 "/>
<text text-anchor="middle" x="3290.7355" y="-2194.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_pathologically_confirmed</text>
<polyline fill="none" stroke="#000000" points="3122.2355,-2186.5 3459.2355,-2186.5 "/>
<text text-anchor="middle" x="3290.7355" y="-2171.3" font-family="Times,serif" font-size="14.00" fill="#000000">distance_normal_to_tumor</text>
<polyline fill="none" stroke="#000000" points="3122.2355,-2163.5 3459.2355,-2163.5 "/>
<text text-anchor="middle" x="3290.7355" y="-2148.3" font-family="Times,serif" font-size="14.00" fill="#000000">distributor_reference</text>
<polyline fill="none" stroke="#000000" points="3122.2355,-2140.5 3459.2355,-2140.5 "/>
<text text-anchor="middle" x="3290.7355" y="-2125.3" font-family="Times,serif" font-size="14.00" fill="#000000">growth_rate</text>
<polyline fill="none" stroke="#000000" points="3122.2355,-2117.5 3459.2355,-2117.5 "/>
<text text-anchor="middle" x="3290.7355" y="-2102.3" font-family="Times,serif" font-size="14.00" fill="#000000">initial_weight</text>
<polyline fill="none" stroke="#000000" points="3122.2355,-2094.5 3459.2355,-2094.5 "/>
<text text-anchor="middle" x="3290.7355" y="-2079.3" font-family="Times,serif" font-size="14.00" fill="#000000">intermediate_dimension</text>
<polyline fill="none" stroke="#000000" points="3122.2355,-2071.5 3459.2355,-2071.5 "/>
<text text-anchor="middle" x="3290.7355" y="-2056.3" font-family="Times,serif" font-size="14.00" fill="#000000">longest_dimension</text>
<polyline fill="none" stroke="#000000" points="3122.2355,-2048.5 3459.2355,-2048.5 "/>
<text text-anchor="middle" x="3290.7355" y="-2033.3" font-family="Times,serif" font-size="14.00" fill="#000000">method_of_sample_procurement</text>
<polyline fill="none" stroke="#000000" points="3122.2355,-2025.5 3459.2355,-2025.5 "/>
<text text-anchor="middle" x="3290.7355" y="-2010.3" font-family="Times,serif" font-size="14.00" fill="#000000">necropsy_sample</text>
<polyline fill="none" stroke="#000000" points="3122.2355,-2002.5 3459.2355,-2002.5 "/>
<text text-anchor="middle" x="3290.7355" y="-1987.3" font-family="Times,serif" font-size="14.00" fill="#000000">non_tumor_tissue_area</text>
<polyline fill="none" stroke="#000000" points="3122.2355,-1979.5 3459.2355,-1979.5 "/>
<text text-anchor="middle" x="3290.7355" y="-1964.3" font-family="Times,serif" font-size="14.00" fill="#000000">passage_count</text>
<polyline fill="none" stroke="#000000" points="3122.2355,-1956.5 3459.2355,-1956.5 "/>
<text text-anchor="middle" x="3290.7355" y="-1941.3" font-family="Times,serif" font-size="14.00" fill="#000000">percentage_stroma</text>
<polyline fill="none" stroke="#000000" points="3122.2355,-1933.5 3459.2355,-1933.5 "/>
<text text-anchor="middle" x="3290.7355" y="-1918.3" font-family="Times,serif" font-size="14.00" fill="#000000">percentage_tumor</text>
<polyline fill="none" stroke="#000000" points="3122.2355,-1910.5 3459.2355,-1910.5 "/>
<text text-anchor="middle" x="3290.7355" y="-1895.3" font-family="Times,serif" font-size="14.00" fill="#000000">+ 18 properties</text>
<polyline fill="none" stroke="#000000" points="3459.2355,-1887.5 3459.2355,-2485.5 "/>
<text text-anchor="middle" x="3469.7355" y="-2182.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- file&#45;&gt;sample -->
<g id="edge33" class="edge">
<title>file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2430.3587,-3998.0119C2600.0923,-3985.2539 2924.4167,-3950.8696 3002.7355,-3871 3218.8831,-3650.5725 2912.8337,-3412.4517 3123.7355,-3187 3146.5638,-3162.5969 3175.3479,-3194.6751 3196.7355,-3169 3241.7617,-3114.9478 3230.421,-2607.2166 3234.7355,-2537 3235.563,-2523.5333 3236.4118,-2509.7758 3237.2721,-2495.8784"/>
<polygon fill="#000000" stroke="#000000" points="3240.7753,-2495.9337 3237.9004,-2485.7364 3233.7887,-2495.5008 3240.7753,-2495.9337"/>
<text text-anchor="middle" x="3175.2355" y="-3310.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_of_sample</text>
</g>
<!-- aliquot -->
<g id="node10" class="node">
<title>aliquot</title>
<path fill="none" stroke="#000000" d="M3299.7355,-3492.5C3299.7355,-3492.5 3703.7355,-3492.5 3703.7355,-3492.5 3709.7355,-3492.5 3715.7355,-3498.5 3715.7355,-3504.5 3715.7355,-3504.5 3715.7355,-3825.5 3715.7355,-3825.5 3715.7355,-3831.5 3709.7355,-3837.5 3703.7355,-3837.5 3703.7355,-3837.5 3299.7355,-3837.5 3299.7355,-3837.5 3293.7355,-3837.5 3287.7355,-3831.5 3287.7355,-3825.5 3287.7355,-3825.5 3287.7355,-3504.5 3287.7355,-3504.5 3287.7355,-3498.5 3293.7355,-3492.5 3299.7355,-3492.5"/>
<text text-anchor="middle" x="3320.7355" y="-3661.3" font-family="Times,serif" font-size="14.00" fill="#000000">aliquot</text>
<polyline fill="none" stroke="#000000" points="3353.7355,-3492.5 3353.7355,-3837.5 "/>
<text text-anchor="middle" x="3364.2355" y="-3661.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="3374.7355,-3492.5 3374.7355,-3837.5 "/>
<text text-anchor="middle" x="3534.7355" y="-3822.3" font-family="Times,serif" font-size="14.00" fill="#000000">aliquot_concentration</text>
<polyline fill="none" stroke="#000000" points="3374.7355,-3814.5 3694.7355,-3814.5 "/>
<text text-anchor="middle" x="3534.7355" y="-3799.3" font-family="Times,serif" font-size="14.00" fill="#000000">aliquot_id</text>
<polyline fill="none" stroke="#000000" points="3374.7355,-3791.5 3694.7355,-3791.5 "/>
<text text-anchor="middle" x="3534.7355" y="-3776.3" font-family="Times,serif" font-size="14.00" fill="#000000">aliquot_is_ref</text>
<polyline fill="none" stroke="#000000" points="3374.7355,-3768.5 3694.7355,-3768.5 "/>
<text text-anchor="middle" x="3534.7355" y="-3753.3" font-family="Times,serif" font-size="14.00" fill="#000000">aliquot_quantity</text>
<polyline fill="none" stroke="#000000" points="3374.7355,-3745.5 3694.7355,-3745.5 "/>
<text text-anchor="middle" x="3534.7355" y="-3730.3" font-family="Times,serif" font-size="14.00" fill="#000000">aliquot_volume</text>
<polyline fill="none" stroke="#000000" points="3374.7355,-3722.5 3694.7355,-3722.5 "/>
<text text-anchor="middle" x="3534.7355" y="-3707.3" font-family="Times,serif" font-size="14.00" fill="#000000">no_matched_normal_low_pass_wgs</text>
<polyline fill="none" stroke="#000000" points="3374.7355,-3699.5 3694.7355,-3699.5 "/>
<text text-anchor="middle" x="3534.7355" y="-3684.3" font-family="Times,serif" font-size="14.00" fill="#000000">no_matched_normal_targeted_sequencing</text>
<polyline fill="none" stroke="#000000" points="3374.7355,-3676.5 3694.7355,-3676.5 "/>
<text text-anchor="middle" x="3534.7355" y="-3661.3" font-family="Times,serif" font-size="14.00" fill="#000000">no_matched_normal_wgs</text>
<polyline fill="none" stroke="#000000" points="3374.7355,-3653.5 3694.7355,-3653.5 "/>
<text text-anchor="middle" x="3534.7355" y="-3638.3" font-family="Times,serif" font-size="14.00" fill="#000000">no_matched_normal_wxs</text>
<polyline fill="none" stroke="#000000" points="3374.7355,-3630.5 3694.7355,-3630.5 "/>
<text text-anchor="middle" x="3534.7355" y="-3615.3" font-family="Times,serif" font-size="14.00" fill="#000000">pool</text>
<polyline fill="none" stroke="#000000" points="3374.7355,-3607.5 3694.7355,-3607.5 "/>
<text text-anchor="middle" x="3534.7355" y="-3592.3" font-family="Times,serif" font-size="14.00" fill="#000000">selected_normal_low_pass_wgs</text>
<polyline fill="none" stroke="#000000" points="3374.7355,-3584.5 3694.7355,-3584.5 "/>
<text text-anchor="middle" x="3534.7355" y="-3569.3" font-family="Times,serif" font-size="14.00" fill="#000000">selected_normal_targeted_sequencing</text>
<polyline fill="none" stroke="#000000" points="3374.7355,-3561.5 3694.7355,-3561.5 "/>
<text text-anchor="middle" x="3534.7355" y="-3546.3" font-family="Times,serif" font-size="14.00" fill="#000000">selected_normal_wgs</text>
<polyline fill="none" stroke="#000000" points="3374.7355,-3538.5 3694.7355,-3538.5 "/>
<text text-anchor="middle" x="3534.7355" y="-3523.3" font-family="Times,serif" font-size="14.00" fill="#000000">selected_normal_wxs</text>
<polyline fill="none" stroke="#000000" points="3374.7355,-3515.5 3694.7355,-3515.5 "/>
<text text-anchor="middle" x="3534.7355" y="-3500.3" font-family="Times,serif" font-size="14.00" fill="#000000">status</text>
<polyline fill="none" stroke="#000000" points="3694.7355,-3492.5 3694.7355,-3837.5 "/>
<text text-anchor="middle" x="3705.2355" y="-3661.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- file&#45;&gt;aliquot -->
<g id="edge22" class="edge">
<title>file&#45;&gt;aliquot</title>
<path fill="none" stroke="#000000" d="M2430.4845,-3998.1004C2585.6555,-3986.1632 2884.0684,-3953.7264 3123.7355,-3871 3175.7193,-3853.0567 3229.0485,-3828.4094 3278.655,-3802.3943"/>
<polygon fill="#000000" stroke="#000000" points="3280.3426,-3805.4613 3287.549,-3797.6948 3277.0722,-3799.2721 3280.3426,-3805.4613"/>
<text text-anchor="middle" x="3206.2355" y="-3859.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_of_aliquot</text>
</g>
<!-- diagnosis -->
<g id="node13" class="node">
<title>diagnosis</title>
<path fill="none" stroke="#000000" d="M1720.2355,-1887.5C1720.2355,-1887.5 2091.2355,-1887.5 2091.2355,-1887.5 2097.2355,-1887.5 2103.2355,-1893.5 2103.2355,-1899.5 2103.2355,-1899.5 2103.2355,-2473.5 2103.2355,-2473.5 2103.2355,-2479.5 2097.2355,-2485.5 2091.2355,-2485.5 2091.2355,-2485.5 1720.2355,-2485.5 1720.2355,-2485.5 1714.2355,-2485.5 1708.2355,-2479.5 1708.2355,-2473.5 1708.2355,-2473.5 1708.2355,-1899.5 1708.2355,-1899.5 1708.2355,-1893.5 1714.2355,-1887.5 1720.2355,-1887.5"/>
<text text-anchor="middle" x="1750.2355" y="-2182.8" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis</text>
<polyline fill="none" stroke="#000000" points="1792.2355,-1887.5 1792.2355,-2485.5 "/>
<text text-anchor="middle" x="1802.7355" y="-2182.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1813.2355,-1887.5 1813.2355,-2485.5 "/>
<text text-anchor="middle" x="1947.7355" y="-2470.3" font-family="Times,serif" font-size="14.00" fill="#000000">age_at_diagnosis</text>
<polyline fill="none" stroke="#000000" points="1813.2355,-2462.5 2082.2355,-2462.5 "/>
<text text-anchor="middle" x="1947.7355" y="-2447.3" font-family="Times,serif" font-size="14.00" fill="#000000">ajcc_clinical_m</text>
<polyline fill="none" stroke="#000000" points="1813.2355,-2439.5 2082.2355,-2439.5 "/>
<text text-anchor="middle" x="1947.7355" y="-2424.3" font-family="Times,serif" font-size="14.00" fill="#000000">ajcc_clinical_n</text>
<polyline fill="none" stroke="#000000" points="1813.2355,-2416.5 2082.2355,-2416.5 "/>
<text text-anchor="middle" x="1947.7355" y="-2401.3" font-family="Times,serif" font-size="14.00" fill="#000000">ajcc_clinical_stage</text>
<polyline fill="none" stroke="#000000" points="1813.2355,-2393.5 2082.2355,-2393.5 "/>
<text text-anchor="middle" x="1947.7355" y="-2378.3" font-family="Times,serif" font-size="14.00" fill="#000000">ajcc_clinical_t</text>
<polyline fill="none" stroke="#000000" points="1813.2355,-2370.5 2082.2355,-2370.5 "/>
<text text-anchor="middle" x="1947.7355" y="-2355.3" font-family="Times,serif" font-size="14.00" fill="#000000">ajcc_pathologic_m</text>
<polyline fill="none" stroke="#000000" points="1813.2355,-2347.5 2082.2355,-2347.5 "/>
<text text-anchor="middle" x="1947.7355" y="-2332.3" font-family="Times,serif" font-size="14.00" fill="#000000">ajcc_pathologic_n</text>
<polyline fill="none" stroke="#000000" points="1813.2355,-2324.5 2082.2355,-2324.5 "/>
<text text-anchor="middle" x="1947.7355" y="-2309.3" font-family="Times,serif" font-size="14.00" fill="#000000">ajcc_pathologic_stage</text>
<polyline fill="none" stroke="#000000" points="1813.2355,-2301.5 2082.2355,-2301.5 "/>
<text text-anchor="middle" x="1947.7355" y="-2286.3" font-family="Times,serif" font-size="14.00" fill="#000000">ajcc_pathologic_t</text>
<polyline fill="none" stroke="#000000" points="1813.2355,-2278.5 2082.2355,-2278.5 "/>
<text text-anchor="middle" x="1947.7355" y="-2263.3" font-family="Times,serif" font-size="14.00" fill="#000000">ajcc_staging_system_edition</text>
<polyline fill="none" stroke="#000000" points="1813.2355,-2255.5 2082.2355,-2255.5 "/>
<text text-anchor="middle" x="1947.7355" y="-2240.3" font-family="Times,serif" font-size="14.00" fill="#000000">anaplasia_present</text>
<polyline fill="none" stroke="#000000" points="1813.2355,-2232.5 2082.2355,-2232.5 "/>
<text text-anchor="middle" x="1947.7355" y="-2217.3" font-family="Times,serif" font-size="14.00" fill="#000000">anaplasia_present_type</text>
<polyline fill="none" stroke="#000000" points="1813.2355,-2209.5 2082.2355,-2209.5 "/>
<text text-anchor="middle" x="1947.7355" y="-2194.3" font-family="Times,serif" font-size="14.00" fill="#000000">ann_arbor_b_symptoms</text>
<polyline fill="none" stroke="#000000" points="1813.2355,-2186.5 2082.2355,-2186.5 "/>
<text text-anchor="middle" x="1947.7355" y="-2171.3" font-family="Times,serif" font-size="14.00" fill="#000000">ann_arbor_clinical_stage</text>
<polyline fill="none" stroke="#000000" points="1813.2355,-2163.5 2082.2355,-2163.5 "/>
<text text-anchor="middle" x="1947.7355" y="-2148.3" font-family="Times,serif" font-size="14.00" fill="#000000">ann_arbor_extranodal_involvement</text>
<polyline fill="none" stroke="#000000" points="1813.2355,-2140.5 2082.2355,-2140.5 "/>
<text text-anchor="middle" x="1947.7355" y="-2125.3" font-family="Times,serif" font-size="14.00" fill="#000000">ann_arbor_pathologic_stage</text>
<polyline fill="none" stroke="#000000" points="1813.2355,-2117.5 2082.2355,-2117.5 "/>
<text text-anchor="middle" x="1947.7355" y="-2102.3" font-family="Times,serif" font-size="14.00" fill="#000000">best_overall_response</text>
<polyline fill="none" stroke="#000000" points="1813.2355,-2094.5 2082.2355,-2094.5 "/>
<text text-anchor="middle" x="1947.7355" y="-2079.3" font-family="Times,serif" font-size="14.00" fill="#000000">breslow_thickness</text>
<polyline fill="none" stroke="#000000" points="1813.2355,-2071.5 2082.2355,-2071.5 "/>
<text text-anchor="middle" x="1947.7355" y="-2056.3" font-family="Times,serif" font-size="14.00" fill="#000000">burkitt_lymphoma_clinical_variant</text>
<polyline fill="none" stroke="#000000" points="1813.2355,-2048.5 2082.2355,-2048.5 "/>
<text text-anchor="middle" x="1947.7355" y="-2033.3" font-family="Times,serif" font-size="14.00" fill="#000000">cause_of_death</text>
<polyline fill="none" stroke="#000000" points="1813.2355,-2025.5 2082.2355,-2025.5 "/>
<text text-anchor="middle" x="1947.7355" y="-2010.3" font-family="Times,serif" font-size="14.00" fill="#000000">child_pugh_classification</text>
<polyline fill="none" stroke="#000000" points="1813.2355,-2002.5 2082.2355,-2002.5 "/>
<text text-anchor="middle" x="1947.7355" y="-1987.3" font-family="Times,serif" font-size="14.00" fill="#000000">circumferential_resection_margin</text>
<polyline fill="none" stroke="#000000" points="1813.2355,-1979.5 2082.2355,-1979.5 "/>
<text text-anchor="middle" x="1947.7355" y="-1964.3" font-family="Times,serif" font-size="14.00" fill="#000000">classification_of_tumor</text>
<polyline fill="none" stroke="#000000" points="1813.2355,-1956.5 2082.2355,-1956.5 "/>
<text text-anchor="middle" x="1947.7355" y="-1941.3" font-family="Times,serif" font-size="14.00" fill="#000000">cog_liver_stage</text>
<polyline fill="none" stroke="#000000" points="1813.2355,-1933.5 2082.2355,-1933.5 "/>
<text text-anchor="middle" x="1947.7355" y="-1918.3" font-family="Times,serif" font-size="14.00" fill="#000000">cog_neuroblastoma_risk_group</text>
<polyline fill="none" stroke="#000000" points="1813.2355,-1910.5 2082.2355,-1910.5 "/>
<text text-anchor="middle" x="1947.7355" y="-1895.3" font-family="Times,serif" font-size="14.00" fill="#000000">+ 104 properties</text>
<polyline fill="none" stroke="#000000" points="2082.2355,-1887.5 2082.2355,-2485.5 "/>
<text text-anchor="middle" x="2092.7355" y="-2182.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- file&#45;&gt;diagnosis -->
<g id="edge10" class="edge">
<title>file&#45;&gt;diagnosis</title>
<path fill="none" stroke="#000000" d="M2221.2193,-3981.5962C2077.3116,-3943.1958 1835.7355,-3851.0291 1835.7355,-3665 1835.7355,-3665 1835.7355,-3665 1835.7355,-2836.5 1835.7355,-2724.9229 1846.0579,-2603.1885 1858.7749,-2495.551"/>
<polygon fill="#000000" stroke="#000000" points="1862.2632,-2495.8564 1859.9726,-2485.5121 1855.3125,-2495.027 1862.2632,-2495.8564"/>
<text text-anchor="middle" x="1895.2355" y="-3310.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_of_diagnosis</text>
</g>
<!-- project -->
<g id="node14" class="node">
<title>project</title>
<path fill="none" stroke="#000000" d="M59.2355,-771.5C59.2355,-771.5 346.2355,-771.5 346.2355,-771.5 352.2355,-771.5 358.2355,-777.5 358.2355,-783.5 358.2355,-783.5 358.2355,-1357.5 358.2355,-1357.5 358.2355,-1363.5 352.2355,-1369.5 346.2355,-1369.5 346.2355,-1369.5 59.2355,-1369.5 59.2355,-1369.5 53.2355,-1369.5 47.2355,-1363.5 47.2355,-1357.5 47.2355,-1357.5 47.2355,-783.5 47.2355,-783.5 47.2355,-777.5 53.2355,-771.5 59.2355,-771.5"/>
<text text-anchor="middle" x="81.2355" y="-1066.8" font-family="Times,serif" font-size="14.00" fill="#000000">project</text>
<polyline fill="none" stroke="#000000" points="115.2355,-771.5 115.2355,-1369.5 "/>
<text text-anchor="middle" x="125.7355" y="-1066.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="136.2355,-771.5 136.2355,-1369.5 "/>
<text text-anchor="middle" x="236.7355" y="-1354.3" font-family="Times,serif" font-size="14.00" fill="#000000">acquisition_type</text>
<polyline fill="none" stroke="#000000" points="136.2355,-1346.5 337.2355,-1346.5 "/>
<text text-anchor="middle" x="236.7355" y="-1331.3" font-family="Times,serif" font-size="14.00" fill="#000000">analytical_fraction</text>
<polyline fill="none" stroke="#000000" points="136.2355,-1323.5 337.2355,-1323.5 "/>
<text text-anchor="middle" x="236.7355" y="-1308.3" font-family="Times,serif" font-size="14.00" fill="#000000">date_of_approval</text>
<polyline fill="none" stroke="#000000" points="136.2355,-1300.5 337.2355,-1300.5 "/>
<text text-anchor="middle" x="236.7355" y="-1285.3" font-family="Times,serif" font-size="14.00" fill="#000000">dbgap_accession_number</text>
<polyline fill="none" stroke="#000000" points="136.2355,-1277.5 337.2355,-1277.5 "/>
<text text-anchor="middle" x="236.7355" y="-1262.3" font-family="Times,serif" font-size="14.00" fill="#000000">embargo_date</text>
<polyline fill="none" stroke="#000000" points="136.2355,-1254.5 337.2355,-1254.5 "/>
<text text-anchor="middle" x="236.7355" y="-1239.3" font-family="Times,serif" font-size="14.00" fill="#000000">end_date</text>
<polyline fill="none" stroke="#000000" points="136.2355,-1231.5 337.2355,-1231.5 "/>
<text text-anchor="middle" x="236.7355" y="-1216.3" font-family="Times,serif" font-size="14.00" fill="#000000">in_review</text>
<polyline fill="none" stroke="#000000" points="136.2355,-1208.5 337.2355,-1208.5 "/>
<text text-anchor="middle" x="236.7355" y="-1193.3" font-family="Times,serif" font-size="14.00" fill="#000000">index_date</text>
<polyline fill="none" stroke="#000000" points="136.2355,-1185.5 337.2355,-1185.5 "/>
<text text-anchor="middle" x="236.7355" y="-1170.3" font-family="Times,serif" font-size="14.00" fill="#000000">intended_release_date</text>
<polyline fill="none" stroke="#000000" points="136.2355,-1162.5 337.2355,-1162.5 "/>
<text text-anchor="middle" x="236.7355" y="-1147.3" font-family="Times,serif" font-size="14.00" fill="#000000">is_legacy</text>
<polyline fill="none" stroke="#000000" points="136.2355,-1139.5 337.2355,-1139.5 "/>
<text text-anchor="middle" x="236.7355" y="-1124.3" font-family="Times,serif" font-size="14.00" fill="#000000">primary_site</text>
<polyline fill="none" stroke="#000000" points="136.2355,-1116.5 337.2355,-1116.5 "/>
<text text-anchor="middle" x="236.7355" y="-1101.3" font-family="Times,serif" font-size="14.00" fill="#000000">project_acronym</text>
<polyline fill="none" stroke="#000000" points="136.2355,-1093.5 337.2355,-1093.5 "/>
<text text-anchor="middle" x="236.7355" y="-1078.3" font-family="Times,serif" font-size="14.00" fill="#000000">project_external_url</text>
<polyline fill="none" stroke="#000000" points="136.2355,-1070.5 337.2355,-1070.5 "/>
<text text-anchor="middle" x="236.7355" y="-1055.3" font-family="Times,serif" font-size="14.00" fill="#000000">project_full_description</text>
<polyline fill="none" stroke="#000000" points="136.2355,-1047.5 337.2355,-1047.5 "/>
<text text-anchor="middle" x="236.7355" y="-1032.3" font-family="Times,serif" font-size="14.00" fill="#000000">project_id</text>
<polyline fill="none" stroke="#000000" points="136.2355,-1024.5 337.2355,-1024.5 "/>
<text text-anchor="middle" x="236.7355" y="-1009.3" font-family="Times,serif" font-size="14.00" fill="#000000">project_manager</text>
<polyline fill="none" stroke="#000000" points="136.2355,-1001.5 337.2355,-1001.5 "/>
<text text-anchor="middle" x="236.7355" y="-986.3" font-family="Times,serif" font-size="14.00" fill="#000000">project_name</text>
<polyline fill="none" stroke="#000000" points="136.2355,-978.5 337.2355,-978.5 "/>
<text text-anchor="middle" x="236.7355" y="-963.3" font-family="Times,serif" font-size="14.00" fill="#000000">project_short_description</text>
<polyline fill="none" stroke="#000000" points="136.2355,-955.5 337.2355,-955.5 "/>
<text text-anchor="middle" x="236.7355" y="-940.3" font-family="Times,serif" font-size="14.00" fill="#000000">project_sort_order</text>
<polyline fill="none" stroke="#000000" points="136.2355,-932.5 337.2355,-932.5 "/>
<text text-anchor="middle" x="236.7355" y="-917.3" font-family="Times,serif" font-size="14.00" fill="#000000">project_type</text>
<polyline fill="none" stroke="#000000" points="136.2355,-909.5 337.2355,-909.5 "/>
<text text-anchor="middle" x="236.7355" y="-894.3" font-family="Times,serif" font-size="14.00" fill="#000000">releasable</text>
<polyline fill="none" stroke="#000000" points="136.2355,-886.5 337.2355,-886.5 "/>
<text text-anchor="middle" x="236.7355" y="-871.3" font-family="Times,serif" font-size="14.00" fill="#000000">release_requested</text>
<polyline fill="none" stroke="#000000" points="136.2355,-863.5 337.2355,-863.5 "/>
<text text-anchor="middle" x="236.7355" y="-848.3" font-family="Times,serif" font-size="14.00" fill="#000000">released</text>
<polyline fill="none" stroke="#000000" points="136.2355,-840.5 337.2355,-840.5 "/>
<text text-anchor="middle" x="236.7355" y="-825.3" font-family="Times,serif" font-size="14.00" fill="#000000">request_submission</text>
<polyline fill="none" stroke="#000000" points="136.2355,-817.5 337.2355,-817.5 "/>
<text text-anchor="middle" x="236.7355" y="-802.3" font-family="Times,serif" font-size="14.00" fill="#000000">start_date</text>
<polyline fill="none" stroke="#000000" points="136.2355,-794.5 337.2355,-794.5 "/>
<text text-anchor="middle" x="236.7355" y="-779.3" font-family="Times,serif" font-size="14.00" fill="#000000">+ 2 properties</text>
<polyline fill="none" stroke="#000000" points="337.2355,-771.5 337.2355,-1369.5 "/>
<text text-anchor="middle" x="347.7355" y="-1066.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- file&#45;&gt;project -->
<g id="edge3" class="edge">
<title>file&#45;&gt;project</title>
<path fill="none" stroke="#000000" d="M2221.0727,-4000.8833C1827.9649,-3986.6337 453.343,-3930.5757 281.7355,-3838 195.9,-3791.695 146.7355,-3762.529 146.7355,-3665 146.7355,-3665 146.7355,-3665 146.7355,-1628.5 146.7355,-1547.7364 152.6154,-1460.7247 160.5645,-1379.9939"/>
<polygon fill="#000000" stroke="#000000" points="164.0843,-1379.9691 161.5955,-1369.6708 157.1189,-1379.2734 164.0843,-1379.9691"/>
<text text-anchor="middle" x="198.2355" y="-2832.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_of_project</text>
</g>
<!-- program -->
<g id="node18" class="node">
<title>program</title>
<path fill="none" stroke="#000000" d="M493.7355,-144.5C493.7355,-144.5 801.7355,-144.5 801.7355,-144.5 807.7355,-144.5 813.7355,-150.5 813.7355,-156.5 813.7355,-156.5 813.7355,-707.5 813.7355,-707.5 813.7355,-713.5 807.7355,-719.5 801.7355,-719.5 801.7355,-719.5 493.7355,-719.5 493.7355,-719.5 487.7355,-719.5 481.7355,-713.5 481.7355,-707.5 481.7355,-707.5 481.7355,-156.5 481.7355,-156.5 481.7355,-150.5 487.7355,-144.5 493.7355,-144.5"/>
<text text-anchor="middle" x="520.7355" y="-428.3" font-family="Times,serif" font-size="14.00" fill="#000000">program</text>
<polyline fill="none" stroke="#000000" points="559.7355,-144.5 559.7355,-719.5 "/>
<text text-anchor="middle" x="570.2355" y="-428.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="580.7355,-144.5 580.7355,-719.5 "/>
<text text-anchor="middle" x="686.7355" y="-704.3" font-family="Times,serif" font-size="14.00" fill="#000000">date_of_approval</text>
<polyline fill="none" stroke="#000000" points="580.7355,-696.5 792.7355,-696.5 "/>
<text text-anchor="middle" x="686.7355" y="-681.3" font-family="Times,serif" font-size="14.00" fill="#000000">dbgap_accession_number</text>
<polyline fill="none" stroke="#000000" points="580.7355,-673.5 792.7355,-673.5 "/>
<text text-anchor="middle" x="686.7355" y="-658.3" font-family="Times,serif" font-size="14.00" fill="#000000">embargo_date</text>
<polyline fill="none" stroke="#000000" points="580.7355,-650.5 792.7355,-650.5 "/>
<text text-anchor="middle" x="686.7355" y="-635.3" font-family="Times,serif" font-size="14.00" fill="#000000">end_date</text>
<polyline fill="none" stroke="#000000" points="580.7355,-627.5 792.7355,-627.5 "/>
<text text-anchor="middle" x="686.7355" y="-612.3" font-family="Times,serif" font-size="14.00" fill="#000000">in_review</text>
<polyline fill="none" stroke="#000000" points="580.7355,-604.5 792.7355,-604.5 "/>
<text text-anchor="middle" x="686.7355" y="-589.3" font-family="Times,serif" font-size="14.00" fill="#000000">index_date</text>
<polyline fill="none" stroke="#000000" points="580.7355,-581.5 792.7355,-581.5 "/>
<text text-anchor="middle" x="686.7355" y="-566.3" font-family="Times,serif" font-size="14.00" fill="#000000">intended_release_date</text>
<polyline fill="none" stroke="#000000" points="580.7355,-558.5 792.7355,-558.5 "/>
<text text-anchor="middle" x="686.7355" y="-543.3" font-family="Times,serif" font-size="14.00" fill="#000000">is_legacy</text>
<polyline fill="none" stroke="#000000" points="580.7355,-535.5 792.7355,-535.5 "/>
<text text-anchor="middle" x="686.7355" y="-520.3" font-family="Times,serif" font-size="14.00" fill="#000000">program_acronym</text>
<polyline fill="none" stroke="#000000" points="580.7355,-512.5 792.7355,-512.5 "/>
<text text-anchor="middle" x="686.7355" y="-497.3" font-family="Times,serif" font-size="14.00" fill="#000000">program_external_url</text>
<polyline fill="none" stroke="#000000" points="580.7355,-489.5 792.7355,-489.5 "/>
<text text-anchor="middle" x="686.7355" y="-474.3" font-family="Times,serif" font-size="14.00" fill="#000000">program_full_description</text>
<polyline fill="none" stroke="#000000" points="580.7355,-466.5 792.7355,-466.5 "/>
<text text-anchor="middle" x="686.7355" y="-451.3" font-family="Times,serif" font-size="14.00" fill="#000000">program_id</text>
<polyline fill="none" stroke="#000000" points="580.7355,-443.5 792.7355,-443.5 "/>
<text text-anchor="middle" x="686.7355" y="-428.3" font-family="Times,serif" font-size="14.00" fill="#000000">program_manager</text>
<polyline fill="none" stroke="#000000" points="580.7355,-420.5 792.7355,-420.5 "/>
<text text-anchor="middle" x="686.7355" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000">program_name</text>
<polyline fill="none" stroke="#000000" points="580.7355,-397.5 792.7355,-397.5 "/>
<text text-anchor="middle" x="686.7355" y="-382.3" font-family="Times,serif" font-size="14.00" fill="#000000">program_short_description</text>
<polyline fill="none" stroke="#000000" points="580.7355,-374.5 792.7355,-374.5 "/>
<text text-anchor="middle" x="686.7355" y="-359.3" font-family="Times,serif" font-size="14.00" fill="#000000">program_sort_order</text>
<polyline fill="none" stroke="#000000" points="580.7355,-351.5 792.7355,-351.5 "/>
<text text-anchor="middle" x="686.7355" y="-336.3" font-family="Times,serif" font-size="14.00" fill="#000000">pubmed_id</text>
<polyline fill="none" stroke="#000000" points="580.7355,-328.5 792.7355,-328.5 "/>
<text text-anchor="middle" x="686.7355" y="-313.3" font-family="Times,serif" font-size="14.00" fill="#000000">releasable</text>
<polyline fill="none" stroke="#000000" points="580.7355,-305.5 792.7355,-305.5 "/>
<text text-anchor="middle" x="686.7355" y="-290.3" font-family="Times,serif" font-size="14.00" fill="#000000">release_requested</text>
<polyline fill="none" stroke="#000000" points="580.7355,-282.5 792.7355,-282.5 "/>
<text text-anchor="middle" x="686.7355" y="-267.3" font-family="Times,serif" font-size="14.00" fill="#000000">released</text>
<polyline fill="none" stroke="#000000" points="580.7355,-259.5 792.7355,-259.5 "/>
<text text-anchor="middle" x="686.7355" y="-244.3" font-family="Times,serif" font-size="14.00" fill="#000000">request_submission</text>
<polyline fill="none" stroke="#000000" points="580.7355,-236.5 792.7355,-236.5 "/>
<text text-anchor="middle" x="686.7355" y="-221.3" font-family="Times,serif" font-size="14.00" fill="#000000">sponsor</text>
<polyline fill="none" stroke="#000000" points="580.7355,-213.5 792.7355,-213.5 "/>
<text text-anchor="middle" x="686.7355" y="-198.3" font-family="Times,serif" font-size="14.00" fill="#000000">start_date</text>
<polyline fill="none" stroke="#000000" points="580.7355,-190.5 792.7355,-190.5 "/>
<text text-anchor="middle" x="686.7355" y="-175.3" font-family="Times,serif" font-size="14.00" fill="#000000">state</text>
<polyline fill="none" stroke="#000000" points="580.7355,-167.5 792.7355,-167.5 "/>
<text text-anchor="middle" x="686.7355" y="-152.3" font-family="Times,serif" font-size="14.00" fill="#000000">submission_enabled</text>
<polyline fill="none" stroke="#000000" points="792.7355,-144.5 792.7355,-719.5 "/>
<text text-anchor="middle" x="803.2355" y="-428.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- file&#45;&gt;program -->
<g id="edge29" class="edge">
<title>file&#45;&gt;program</title>
<path fill="none" stroke="#000000" d="M2221.0486,-4001.403C1924.0811,-3991.7761 1051.2398,-3957.6521 331.7355,-3871 247.0765,-3860.8042 214.9416,-3883.3586 142.7355,-3838 62.6298,-3787.679 18.7355,-3759.5999 18.7355,-3665 18.7355,-3665 18.7355,-3665 18.7355,-1070.5 18.7355,-937.1213 -33.5035,-883.7602 37.7355,-771 135.0742,-616.9283 328.6237,-526.8762 471.7166,-478.8034"/>
<polygon fill="#000000" stroke="#000000" points="473.1106,-482.0286 481.4985,-475.5559 470.905,-475.3851 473.1106,-482.0286"/>
<text text-anchor="middle" x="75.2355" y="-2507.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_of_program</text>
</g>
<!-- study -->
<g id="node19" class="node">
<title>study</title>
<path fill="none" stroke="#000000" d="M510.2355,-771.5C510.2355,-771.5 785.2355,-771.5 785.2355,-771.5 791.2355,-771.5 797.2355,-777.5 797.2355,-783.5 797.2355,-783.5 797.2355,-1357.5 797.2355,-1357.5 797.2355,-1363.5 791.2355,-1369.5 785.2355,-1369.5 785.2355,-1369.5 510.2355,-1369.5 510.2355,-1369.5 504.2355,-1369.5 498.2355,-1363.5 498.2355,-1357.5 498.2355,-1357.5 498.2355,-783.5 498.2355,-783.5 498.2355,-777.5 504.2355,-771.5 510.2355,-771.5"/>
<text text-anchor="middle" x="526.2355" y="-1066.8" font-family="Times,serif" font-size="14.00" fill="#000000">study</text>
<polyline fill="none" stroke="#000000" points="554.2355,-771.5 554.2355,-1369.5 "/>
<text text-anchor="middle" x="564.7355" y="-1066.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="575.2355,-771.5 575.2355,-1369.5 "/>
<text text-anchor="middle" x="675.7355" y="-1354.3" font-family="Times,serif" font-size="14.00" fill="#000000">acquisition_type</text>
<polyline fill="none" stroke="#000000" points="575.2355,-1346.5 776.2355,-1346.5 "/>
<text text-anchor="middle" x="675.7355" y="-1331.3" font-family="Times,serif" font-size="14.00" fill="#000000">analytical_fraction</text>
<polyline fill="none" stroke="#000000" points="575.2355,-1323.5 776.2355,-1323.5 "/>
<text text-anchor="middle" x="675.7355" y="-1308.3" font-family="Times,serif" font-size="14.00" fill="#000000">date_of_approval</text>
<polyline fill="none" stroke="#000000" points="575.2355,-1300.5 776.2355,-1300.5 "/>
<text text-anchor="middle" x="675.7355" y="-1285.3" font-family="Times,serif" font-size="14.00" fill="#000000">dbgap_accession_number</text>
<polyline fill="none" stroke="#000000" points="575.2355,-1277.5 776.2355,-1277.5 "/>
<text text-anchor="middle" x="675.7355" y="-1262.3" font-family="Times,serif" font-size="14.00" fill="#000000">embargo_date</text>
<polyline fill="none" stroke="#000000" points="575.2355,-1254.5 776.2355,-1254.5 "/>
<text text-anchor="middle" x="675.7355" y="-1239.3" font-family="Times,serif" font-size="14.00" fill="#000000">end_date</text>
<polyline fill="none" stroke="#000000" points="575.2355,-1231.5 776.2355,-1231.5 "/>
<text text-anchor="middle" x="675.7355" y="-1216.3" font-family="Times,serif" font-size="14.00" fill="#000000">in_review</text>
<polyline fill="none" stroke="#000000" points="575.2355,-1208.5 776.2355,-1208.5 "/>
<text text-anchor="middle" x="675.7355" y="-1193.3" font-family="Times,serif" font-size="14.00" fill="#000000">index_date</text>
<polyline fill="none" stroke="#000000" points="575.2355,-1185.5 776.2355,-1185.5 "/>
<text text-anchor="middle" x="675.7355" y="-1170.3" font-family="Times,serif" font-size="14.00" fill="#000000">intended_release_date</text>
<polyline fill="none" stroke="#000000" points="575.2355,-1162.5 776.2355,-1162.5 "/>
<text text-anchor="middle" x="675.7355" y="-1147.3" font-family="Times,serif" font-size="14.00" fill="#000000">is_legacy</text>
<polyline fill="none" stroke="#000000" points="575.2355,-1139.5 776.2355,-1139.5 "/>
<text text-anchor="middle" x="675.7355" y="-1124.3" font-family="Times,serif" font-size="14.00" fill="#000000">primary_site</text>
<polyline fill="none" stroke="#000000" points="575.2355,-1116.5 776.2355,-1116.5 "/>
<text text-anchor="middle" x="675.7355" y="-1101.3" font-family="Times,serif" font-size="14.00" fill="#000000">releasable</text>
<polyline fill="none" stroke="#000000" points="575.2355,-1093.5 776.2355,-1093.5 "/>
<text text-anchor="middle" x="675.7355" y="-1078.3" font-family="Times,serif" font-size="14.00" fill="#000000">release_requested</text>
<polyline fill="none" stroke="#000000" points="575.2355,-1070.5 776.2355,-1070.5 "/>
<text text-anchor="middle" x="675.7355" y="-1055.3" font-family="Times,serif" font-size="14.00" fill="#000000">released</text>
<polyline fill="none" stroke="#000000" points="575.2355,-1047.5 776.2355,-1047.5 "/>
<text text-anchor="middle" x="675.7355" y="-1032.3" font-family="Times,serif" font-size="14.00" fill="#000000">request_submission</text>
<polyline fill="none" stroke="#000000" points="575.2355,-1024.5 776.2355,-1024.5 "/>
<text text-anchor="middle" x="675.7355" y="-1009.3" font-family="Times,serif" font-size="14.00" fill="#000000">start_date</text>
<polyline fill="none" stroke="#000000" points="575.2355,-1001.5 776.2355,-1001.5 "/>
<text text-anchor="middle" x="675.7355" y="-986.3" font-family="Times,serif" font-size="14.00" fill="#000000">state</text>
<polyline fill="none" stroke="#000000" points="575.2355,-978.5 776.2355,-978.5 "/>
<text text-anchor="middle" x="675.7355" y="-963.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_acronym</text>
<polyline fill="none" stroke="#000000" points="575.2355,-955.5 776.2355,-955.5 "/>
<text text-anchor="middle" x="675.7355" y="-940.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_external_url</text>
<polyline fill="none" stroke="#000000" points="575.2355,-932.5 776.2355,-932.5 "/>
<text text-anchor="middle" x="675.7355" y="-917.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_full_description</text>
<polyline fill="none" stroke="#000000" points="575.2355,-909.5 776.2355,-909.5 "/>
<text text-anchor="middle" x="675.7355" y="-894.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_id</text>
<polyline fill="none" stroke="#000000" points="575.2355,-886.5 776.2355,-886.5 "/>
<text text-anchor="middle" x="675.7355" y="-871.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_manager</text>
<polyline fill="none" stroke="#000000" points="575.2355,-863.5 776.2355,-863.5 "/>
<text text-anchor="middle" x="675.7355" y="-848.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_name</text>
<polyline fill="none" stroke="#000000" points="575.2355,-840.5 776.2355,-840.5 "/>
<text text-anchor="middle" x="675.7355" y="-825.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_short_description</text>
<polyline fill="none" stroke="#000000" points="575.2355,-817.5 776.2355,-817.5 "/>
<text text-anchor="middle" x="675.7355" y="-802.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_sort_order</text>
<polyline fill="none" stroke="#000000" points="575.2355,-794.5 776.2355,-794.5 "/>
<text text-anchor="middle" x="675.7355" y="-779.3" font-family="Times,serif" font-size="14.00" fill="#000000">+ 2 properties</text>
<polyline fill="none" stroke="#000000" points="776.2355,-771.5 776.2355,-1369.5 "/>
<text text-anchor="middle" x="786.7355" y="-1066.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- file&#45;&gt;study -->
<g id="edge32" class="edge">
<title>file&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2221.0606,-3998.2768C1804.3354,-3972.132 285.7355,-3863.2561 285.7355,-3665 285.7355,-3665 285.7355,-3665 285.7355,-2511.5 285.7355,-2233.8292 244.8267,-2158.35 303.7355,-1887 343.0909,-1705.7187 421.7076,-1514.0368 493.861,-1361.9835"/>
<polygon fill="#000000" stroke="#000000" points="497.026,-1363.4777 498.1649,-1352.9442 490.7058,-1360.4684 497.026,-1363.4777"/>
<text text-anchor="middle" x="331.2355" y="-2832.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_of_study</text>
</g>
<!-- laboratory_procedure -->
<g id="node20" class="node">
<title>laboratory_procedure</title>
<path fill="none" stroke="#000000" d="M3282.2355,-1513.5C3282.2355,-1513.5 3735.2355,-1513.5 3735.2355,-1513.5 3741.2355,-1513.5 3747.2355,-1519.5 3747.2355,-1525.5 3747.2355,-1525.5 3747.2355,-1731.5 3747.2355,-1731.5 3747.2355,-1737.5 3741.2355,-1743.5 3735.2355,-1743.5 3735.2355,-1743.5 3282.2355,-1743.5 3282.2355,-1743.5 3276.2355,-1743.5 3270.2355,-1737.5 3270.2355,-1731.5 3270.2355,-1731.5 3270.2355,-1525.5 3270.2355,-1525.5 3270.2355,-1519.5 3276.2355,-1513.5 3282.2355,-1513.5"/>
<text text-anchor="middle" x="3356.2355" y="-1624.8" font-family="Times,serif" font-size="14.00" fill="#000000">laboratory_procedure</text>
<polyline fill="none" stroke="#000000" points="3442.2355,-1513.5 3442.2355,-1743.5 "/>
<text text-anchor="middle" x="3452.7355" y="-1624.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="3463.2355,-1513.5 3463.2355,-1743.5 "/>
<text text-anchor="middle" x="3594.7355" y="-1728.3" font-family="Times,serif" font-size="14.00" fill="#000000">instrument_model</text>
<polyline fill="none" stroke="#000000" points="3463.2355,-1720.5 3726.2355,-1720.5 "/>
<text text-anchor="middle" x="3594.7355" y="-1705.3" font-family="Times,serif" font-size="14.00" fill="#000000">instrument_name</text>
<polyline fill="none" stroke="#000000" points="3463.2355,-1697.5 3726.2355,-1697.5 "/>
<text text-anchor="middle" x="3594.7355" y="-1682.3" font-family="Times,serif" font-size="14.00" fill="#000000">instrument_version</text>
<polyline fill="none" stroke="#000000" points="3463.2355,-1674.5 3726.2355,-1674.5 "/>
<text text-anchor="middle" x="3594.7355" y="-1659.3" font-family="Times,serif" font-size="14.00" fill="#000000">laboratory_procedure_id</text>
<polyline fill="none" stroke="#000000" points="3463.2355,-1651.5 3726.2355,-1651.5 "/>
<text text-anchor="middle" x="3594.7355" y="-1636.3" font-family="Times,serif" font-size="14.00" fill="#000000">laboratory_procedure_target_type</text>
<polyline fill="none" stroke="#000000" points="3463.2355,-1628.5 3726.2355,-1628.5 "/>
<text text-anchor="middle" x="3594.7355" y="-1613.3" font-family="Times,serif" font-size="14.00" fill="#000000">laboratory_procedure_type</text>
<polyline fill="none" stroke="#000000" points="3463.2355,-1605.5 3726.2355,-1605.5 "/>
<text text-anchor="middle" x="3594.7355" y="-1590.3" font-family="Times,serif" font-size="14.00" fill="#000000">reagent_description</text>
<polyline fill="none" stroke="#000000" points="3463.2355,-1582.5 3726.2355,-1582.5 "/>
<text text-anchor="middle" x="3594.7355" y="-1567.3" font-family="Times,serif" font-size="14.00" fill="#000000">software_name</text>
<polyline fill="none" stroke="#000000" points="3463.2355,-1559.5 3726.2355,-1559.5 "/>
<text text-anchor="middle" x="3594.7355" y="-1544.3" font-family="Times,serif" font-size="14.00" fill="#000000">software_version</text>
<polyline fill="none" stroke="#000000" points="3463.2355,-1536.5 3726.2355,-1536.5 "/>
<text text-anchor="middle" x="3594.7355" y="-1521.3" font-family="Times,serif" font-size="14.00" fill="#000000">test_name</text>
<polyline fill="none" stroke="#000000" points="3726.2355,-1513.5 3726.2355,-1743.5 "/>
<text text-anchor="middle" x="3736.7355" y="-1624.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- file&#45;&gt;laboratory_procedure -->
<g id="edge6" class="edge">
<title>file&#45;&gt;laboratory_procedure</title>
<path fill="none" stroke="#000000" d="M2430.6833,-3995.7196C2536.6474,-3981.0778 2697.2188,-3942.0409 2787.7355,-3838 2989.7614,-3605.7894 2919.7279,-3473.1817 2966.7355,-3169 3053.844,-2605.3305 2720.4497,-2369.412 3024.7355,-1887 3078.6604,-1801.508 3171.0308,-1742.4769 3260.7134,-1702.6587"/>
<polygon fill="#000000" stroke="#000000" points="3262.1817,-1705.8367 3269.9423,-1698.6239 3259.3776,-1699.4229 3262.1817,-1705.8367"/>
<text text-anchor="middle" x="3071.2355" y="-3157.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_of_laboratory_procedure</text>
</g>
<!-- cross_reference_database -->
<g id="node3" class="node">
<title>cross_reference_database</title>
<path fill="none" stroke="#000000" d="M970.2355,-1036C970.2355,-1036 1441.2355,-1036 1441.2355,-1036 1447.2355,-1036 1453.2355,-1042 1453.2355,-1048 1453.2355,-1048 1453.2355,-1093 1453.2355,-1093 1453.2355,-1099 1447.2355,-1105 1441.2355,-1105 1441.2355,-1105 970.2355,-1105 970.2355,-1105 964.2355,-1105 958.2355,-1099 958.2355,-1093 958.2355,-1093 958.2355,-1048 958.2355,-1048 958.2355,-1042 964.2355,-1036 970.2355,-1036"/>
<text text-anchor="middle" x="1059.7355" y="-1066.8" font-family="Times,serif" font-size="14.00" fill="#000000">cross_reference_database</text>
<polyline fill="none" stroke="#000000" points="1161.2355,-1036 1161.2355,-1105 "/>
<text text-anchor="middle" x="1171.7355" y="-1066.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1182.2355,-1036 1182.2355,-1105 "/>
<text text-anchor="middle" x="1307.2355" y="-1089.8" font-family="Times,serif" font-size="14.00" fill="#000000">cross_reference_database_id</text>
<polyline fill="none" stroke="#000000" points="1182.2355,-1082 1432.2355,-1082 "/>
<text text-anchor="middle" x="1307.2355" y="-1066.8" font-family="Times,serif" font-size="14.00" fill="#000000">cross_reference_database_name</text>
<polyline fill="none" stroke="#000000" points="1182.2355,-1059 1432.2355,-1059 "/>
<text text-anchor="middle" x="1307.2355" y="-1043.8" font-family="Times,serif" font-size="14.00" fill="#000000">cross_reference_database_url</text>
<polyline fill="none" stroke="#000000" points="1432.2355,-1036 1432.2355,-1105 "/>
<text text-anchor="middle" x="1442.7355" y="-1066.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- study_subject&#45;&gt;cross_reference_database -->
<g id="edge11" class="edge">
<title>study_subject&#45;&gt;cross_reference_database</title>
<path fill="none" stroke="#000000" d="M1299.2301,-1502.4036C1268.6934,-1473.447 1241.1297,-1440.1007 1222.7355,-1403 1176.3087,-1309.3577 1186.9874,-1182.1089 1197.2623,-1115.451"/>
<polygon fill="#000000" stroke="#000000" points="1200.7645,-1115.7167 1198.8991,-1105.2874 1193.8536,-1114.6037 1200.7645,-1115.7167"/>
<text text-anchor="middle" x="1349.2355" y="-1391.8" font-family="Times,serif" font-size="14.00" fill="#000000">study_subject_cross_referenced_at</text>
</g>
<!-- study_subject&#45;&gt;project -->
<g id="edge2" class="edge">
<title>study_subject&#45;&gt;project</title>
<path fill="none" stroke="#000000" d="M1298.9467,-1610.7816C1088.2427,-1584.3178 744.9437,-1520.3184 488.7355,-1370 444.698,-1344.163 403.0842,-1309.613 365.9383,-1273.1724"/>
<polygon fill="#000000" stroke="#000000" points="368.1333,-1270.4198 358.5693,-1265.8611 363.203,-1275.389 368.1333,-1270.4198"/>
<text text-anchor="middle" x="627.7355" y="-1391.8" font-family="Times,serif" font-size="14.00" fill="#000000">study_subject_of_project</text>
</g>
<!-- study_subject&#45;&gt;program -->
<g id="edge13" class="edge">
<title>study_subject&#45;&gt;program</title>
<path fill="none" stroke="#000000" d="M1541.8414,-1421.2214C1576.1572,-1234.4001 1593.6502,-960.7059 1462.7355,-771 1317.8314,-561.0222 1016.7233,-480.7815 823.8557,-450.3395"/>
<polygon fill="#000000" stroke="#000000" points="824.3131,-446.8687 813.8951,-448.7964 823.2413,-453.7862 824.3131,-446.8687"/>
<text text-anchor="middle" x="1660.7355" y="-1066.8" font-family="Times,serif" font-size="14.00" fill="#000000">study_subject_of_program</text>
</g>
<!-- study_subject&#45;&gt;study -->
<g id="edge4" class="edge">
<title>study_subject&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1298.9938,-1556.0503C1191.2815,-1510.6683 1056.9776,-1446.351 948.7355,-1370 898.3771,-1334.4785 848.8108,-1290.2192 804.8893,-1246.7166"/>
<polygon fill="#000000" stroke="#000000" points="807.1613,-1244.0394 797.6073,-1239.4598 802.2201,-1248.9978 807.1613,-1244.0394"/>
<text text-anchor="middle" x="1074.2355" y="-1391.8" font-family="Times,serif" font-size="14.00" fill="#000000">study_subject_of_study</text>
</g>
<!-- fraction -->
<g id="node4" class="node">
<title>fraction</title>
<path fill="none" stroke="#000000" d="M3686.7355,-2779C3686.7355,-2779 3924.7355,-2779 3924.7355,-2779 3930.7355,-2779 3936.7355,-2785 3936.7355,-2791 3936.7355,-2791 3936.7355,-2882 3936.7355,-2882 3936.7355,-2888 3930.7355,-2894 3924.7355,-2894 3924.7355,-2894 3686.7355,-2894 3686.7355,-2894 3680.7355,-2894 3674.7355,-2888 3674.7355,-2882 3674.7355,-2882 3674.7355,-2791 3674.7355,-2791 3674.7355,-2785 3680.7355,-2779 3686.7355,-2779"/>
<text text-anchor="middle" x="3711.2355" y="-2832.8" font-family="Times,serif" font-size="14.00" fill="#000000">fraction</text>
<polyline fill="none" stroke="#000000" points="3747.7355,-2779 3747.7355,-2894 "/>
<text text-anchor="middle" x="3758.2355" y="-2832.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="3768.7355,-2779 3768.7355,-2894 "/>
<text text-anchor="middle" x="3842.2355" y="-2878.8" font-family="Times,serif" font-size="14.00" fill="#000000">creation_datetime</text>
<polyline fill="none" stroke="#000000" points="3768.7355,-2871 3915.7355,-2871 "/>
<text text-anchor="middle" x="3842.2355" y="-2855.8" font-family="Times,serif" font-size="14.00" fill="#000000">fraction_id</text>
<polyline fill="none" stroke="#000000" points="3768.7355,-2848 3915.7355,-2848 "/>
<text text-anchor="middle" x="3842.2355" y="-2832.8" font-family="Times,serif" font-size="14.00" fill="#000000">fraction_number</text>
<polyline fill="none" stroke="#000000" points="3768.7355,-2825 3915.7355,-2825 "/>
<text text-anchor="middle" x="3842.2355" y="-2809.8" font-family="Times,serif" font-size="14.00" fill="#000000">fraction_type</text>
<polyline fill="none" stroke="#000000" points="3768.7355,-2802 3915.7355,-2802 "/>
<text text-anchor="middle" x="3842.2355" y="-2786.8" font-family="Times,serif" font-size="14.00" fill="#000000">weight</text>
<polyline fill="none" stroke="#000000" points="3915.7355,-2779 3915.7355,-2894 "/>
<text text-anchor="middle" x="3926.2355" y="-2832.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- fraction&#45;&gt;sample -->
<g id="edge20" class="edge">
<title>fraction&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M3795.1254,-2778.9662C3779.04,-2709.4206 3741.3667,-2594.5718 3660.7355,-2537 3606.4496,-2498.239 3569.6756,-2552.0505 3511.7355,-2519 3497.7376,-2511.0152 3484.2527,-2501.9226 3471.2971,-2491.9736"/>
<polygon fill="#000000" stroke="#000000" points="3473.3195,-2489.1112 3463.2989,-2485.6706 3468.9868,-2494.6092 3473.3195,-2489.1112"/>
<text text-anchor="middle" x="3579.7355" y="-2507.8" font-family="Times,serif" font-size="14.00" fill="#000000">fraction_of_sample</text>
</g>
<!-- fraction&#45;&gt;laboratory_procedure -->
<g id="edge17" class="edge">
<title>fraction&#45;&gt;laboratory_procedure</title>
<path fill="none" stroke="#000000" d="M3791.5107,-2778.6426C3745.9524,-2593.3418 3602.9359,-2011.645 3539.528,-1753.7435"/>
<polygon fill="#000000" stroke="#000000" points="3542.9082,-1752.832 3537.1219,-1743.9569 3536.1107,-1754.5033 3542.9082,-1752.832"/>
<text text-anchor="middle" x="3795.7355" y="-2182.8" font-family="Times,serif" font-size="14.00" fill="#000000">fraction_processed_by</text>
</g>
<!-- demographic_data -->
<g id="node5" class="node">
<title>demographic_data</title>
<path fill="none" stroke="#000000" d="M1301.2355,-1922C1301.2355,-1922 1678.2355,-1922 1678.2355,-1922 1684.2355,-1922 1690.2355,-1928 1690.2355,-1934 1690.2355,-1934 1690.2355,-2439 1690.2355,-2439 1690.2355,-2445 1684.2355,-2451 1678.2355,-2451 1678.2355,-2451 1301.2355,-2451 1301.2355,-2451 1295.2355,-2451 1289.2355,-2445 1289.2355,-2439 1289.2355,-2439 1289.2355,-1934 1289.2355,-1934 1289.2355,-1928 1295.2355,-1922 1301.2355,-1922"/>
<text text-anchor="middle" x="1363.7355" y="-2182.8" font-family="Times,serif" font-size="14.00" fill="#000000">demographic_data</text>
<polyline fill="none" stroke="#000000" points="1438.2355,-1922 1438.2355,-2451 "/>
<text text-anchor="middle" x="1448.7355" y="-2182.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1459.2355,-1922 1459.2355,-2451 "/>
<text text-anchor="middle" x="1564.2355" y="-2435.8" font-family="Times,serif" font-size="14.00" fill="#000000">age_at_index</text>
<polyline fill="none" stroke="#000000" points="1459.2355,-2428 1669.2355,-2428 "/>
<text text-anchor="middle" x="1564.2355" y="-2412.8" font-family="Times,serif" font-size="14.00" fill="#000000">age_is_obfuscated</text>
<polyline fill="none" stroke="#000000" points="1459.2355,-2405 1669.2355,-2405 "/>
<text text-anchor="middle" x="1564.2355" y="-2389.8" font-family="Times,serif" font-size="14.00" fill="#000000">breed</text>
<polyline fill="none" stroke="#000000" points="1459.2355,-2382 1669.2355,-2382 "/>
<text text-anchor="middle" x="1564.2355" y="-2366.8" font-family="Times,serif" font-size="14.00" fill="#000000">cause_of_death</text>
<polyline fill="none" stroke="#000000" points="1459.2355,-2359 1669.2355,-2359 "/>
<text text-anchor="middle" x="1564.2355" y="-2343.8" font-family="Times,serif" font-size="14.00" fill="#000000">cause_of_death_source</text>
<polyline fill="none" stroke="#000000" points="1459.2355,-2336 1669.2355,-2336 "/>
<text text-anchor="middle" x="1564.2355" y="-2320.8" font-family="Times,serif" font-size="14.00" fill="#000000">date_of_birth</text>
<polyline fill="none" stroke="#000000" points="1459.2355,-2313 1669.2355,-2313 "/>
<text text-anchor="middle" x="1564.2355" y="-2297.8" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_birth</text>
<polyline fill="none" stroke="#000000" points="1459.2355,-2290 1669.2355,-2290 "/>
<text text-anchor="middle" x="1564.2355" y="-2274.8" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_death</text>
<polyline fill="none" stroke="#000000" points="1459.2355,-2267 1669.2355,-2267 "/>
<text text-anchor="middle" x="1564.2355" y="-2251.8" font-family="Times,serif" font-size="14.00" fill="#000000">demographic_data_id</text>
<polyline fill="none" stroke="#000000" points="1459.2355,-2244 1669.2355,-2244 "/>
<text text-anchor="middle" x="1564.2355" y="-2228.8" font-family="Times,serif" font-size="14.00" fill="#000000">ethnicity</text>
<polyline fill="none" stroke="#000000" points="1459.2355,-2221 1669.2355,-2221 "/>
<text text-anchor="middle" x="1564.2355" y="-2205.8" font-family="Times,serif" font-size="14.00" fill="#000000">gender</text>
<polyline fill="none" stroke="#000000" points="1459.2355,-2198 1669.2355,-2198 "/>
<text text-anchor="middle" x="1564.2355" y="-2182.8" font-family="Times,serif" font-size="14.00" fill="#000000">height</text>
<polyline fill="none" stroke="#000000" points="1459.2355,-2175 1669.2355,-2175 "/>
<text text-anchor="middle" x="1564.2355" y="-2159.8" font-family="Times,serif" font-size="14.00" fill="#000000">menopause_status</text>
<polyline fill="none" stroke="#000000" points="1459.2355,-2152 1669.2355,-2152 "/>
<text text-anchor="middle" x="1564.2355" y="-2136.8" font-family="Times,serif" font-size="14.00" fill="#000000">neutered_indicator</text>
<polyline fill="none" stroke="#000000" points="1459.2355,-2129 1669.2355,-2129 "/>
<text text-anchor="middle" x="1564.2355" y="-2113.8" font-family="Times,serif" font-size="14.00" fill="#000000">occupation_duration_years</text>
<polyline fill="none" stroke="#000000" points="1459.2355,-2106 1669.2355,-2106 "/>
<text text-anchor="middle" x="1564.2355" y="-2090.8" font-family="Times,serif" font-size="14.00" fill="#000000">premature_at_birth</text>
<polyline fill="none" stroke="#000000" points="1459.2355,-2083 1669.2355,-2083 "/>
<text text-anchor="middle" x="1564.2355" y="-2067.8" font-family="Times,serif" font-size="14.00" fill="#000000">race</text>
<polyline fill="none" stroke="#000000" points="1459.2355,-2060 1669.2355,-2060 "/>
<text text-anchor="middle" x="1564.2355" y="-2044.8" font-family="Times,serif" font-size="14.00" fill="#000000">survival_time</text>
<polyline fill="none" stroke="#000000" points="1459.2355,-2037 1669.2355,-2037 "/>
<text text-anchor="middle" x="1564.2355" y="-2021.8" font-family="Times,serif" font-size="14.00" fill="#000000">vital_status</text>
<polyline fill="none" stroke="#000000" points="1459.2355,-2014 1669.2355,-2014 "/>
<text text-anchor="middle" x="1564.2355" y="-1998.8" font-family="Times,serif" font-size="14.00" fill="#000000">weeks_gestation_at_birth</text>
<polyline fill="none" stroke="#000000" points="1459.2355,-1991 1669.2355,-1991 "/>
<text text-anchor="middle" x="1564.2355" y="-1975.8" font-family="Times,serif" font-size="14.00" fill="#000000">weight</text>
<polyline fill="none" stroke="#000000" points="1459.2355,-1968 1669.2355,-1968 "/>
<text text-anchor="middle" x="1564.2355" y="-1952.8" font-family="Times,serif" font-size="14.00" fill="#000000">year_of_birth</text>
<polyline fill="none" stroke="#000000" points="1459.2355,-1945 1669.2355,-1945 "/>
<text text-anchor="middle" x="1564.2355" y="-1929.8" font-family="Times,serif" font-size="14.00" fill="#000000">year_of_death</text>
<polyline fill="none" stroke="#000000" points="1669.2355,-1922 1669.2355,-2451 "/>
<text text-anchor="middle" x="1679.7355" y="-2182.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- demographic_data&#45;&gt;study_subject -->
<g id="edge19" class="edge">
<title>demographic_data&#45;&gt;study_subject</title>
<path fill="none" stroke="#000000" d="M1489.7355,-1921.7986C1489.7355,-1896.4439 1489.7355,-1870.9313 1489.7355,-1846.1013"/>
<polygon fill="#000000" stroke="#000000" points="1493.2356,-1845.8793 1489.7355,-1835.8793 1486.2356,-1845.8794 1493.2356,-1845.8793"/>
<text text-anchor="middle" x="1601.2355" y="-1857.8" font-family="Times,serif" font-size="14.00" fill="#000000">demographic_of_study_subject</text>
</g>
<!-- stratification_factor -->
<g id="node6" class="node">
<title>stratification_factor</title>
<path fill="none" stroke="#000000" d="M2133.7355,-2106C2133.7355,-2106 2595.7355,-2106 2595.7355,-2106 2601.7355,-2106 2607.7355,-2112 2607.7355,-2118 2607.7355,-2118 2607.7355,-2255 2607.7355,-2255 2607.7355,-2261 2601.7355,-2267 2595.7355,-2267 2595.7355,-2267 2133.7355,-2267 2133.7355,-2267 2127.7355,-2267 2121.7355,-2261 2121.7355,-2255 2121.7355,-2255 2121.7355,-2118 2121.7355,-2118 2121.7355,-2112 2127.7355,-2106 2133.7355,-2106"/>
<text text-anchor="middle" x="2201.7355" y="-2182.8" font-family="Times,serif" font-size="14.00" fill="#000000">stratification_factor</text>
<polyline fill="none" stroke="#000000" points="2281.7355,-2106 2281.7355,-2267 "/>
<text text-anchor="middle" x="2292.2355" y="-2182.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="2302.7355,-2106 2302.7355,-2267 "/>
<text text-anchor="middle" x="2444.7355" y="-2251.8" font-family="Times,serif" font-size="14.00" fill="#000000">grouped_recurrence_score</text>
<polyline fill="none" stroke="#000000" points="2302.7355,-2244 2586.7355,-2244 "/>
<text text-anchor="middle" x="2444.7355" y="-2228.8" font-family="Times,serif" font-size="14.00" fill="#000000">menopausal_status_stratification</text>
<polyline fill="none" stroke="#000000" points="2302.7355,-2221 2586.7355,-2221 "/>
<text text-anchor="middle" x="2444.7355" y="-2205.8" font-family="Times,serif" font-size="14.00" fill="#000000">planned_chemotherapy_stratification</text>
<polyline fill="none" stroke="#000000" points="2302.7355,-2198 2586.7355,-2198 "/>
<text text-anchor="middle" x="2444.7355" y="-2182.8" font-family="Times,serif" font-size="14.00" fill="#000000">planned_radiotherapy_stratification</text>
<polyline fill="none" stroke="#000000" points="2302.7355,-2175 2586.7355,-2175 "/>
<text text-anchor="middle" x="2444.7355" y="-2159.8" font-family="Times,serif" font-size="14.00" fill="#000000">stratification_code</text>
<polyline fill="none" stroke="#000000" points="2302.7355,-2152 2586.7355,-2152 "/>
<text text-anchor="middle" x="2444.7355" y="-2136.8" font-family="Times,serif" font-size="14.00" fill="#000000">stratification_factor_id</text>
<polyline fill="none" stroke="#000000" points="2302.7355,-2129 2586.7355,-2129 "/>
<text text-anchor="middle" x="2444.7355" y="-2113.8" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_size_stratification</text>
<polyline fill="none" stroke="#000000" points="2586.7355,-2106 2586.7355,-2267 "/>
<text text-anchor="middle" x="2597.2355" y="-2182.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- stratification_factor&#45;&gt;study_subject -->
<g id="edge9" class="edge">
<title>stratification_factor&#45;&gt;study_subject</title>
<path fill="none" stroke="#000000" d="M2313.1912,-2105.9624C2267.3443,-2039.7131 2194.9592,-1947.2421 2112.7355,-1887 1985.1012,-1793.4872 1818.6439,-1726.6748 1689.9021,-1684.4284"/>
<polygon fill="#000000" stroke="#000000" points="1690.9012,-1681.0729 1680.3089,-1681.3028 1688.7327,-1687.7285 1690.9012,-1681.0729"/>
<text text-anchor="middle" x="2153.7355" y="-1857.8" font-family="Times,serif" font-size="14.00" fill="#000000">sf_of_study_subject</text>
</g>
<!-- analyte -->
<g id="node7" class="node">
<title>analyte</title>
<path fill="none" stroke="#000000" d="M3577.7355,-3187.5C3577.7355,-3187.5 3941.7355,-3187.5 3941.7355,-3187.5 3947.7355,-3187.5 3953.7355,-3193.5 3953.7355,-3199.5 3953.7355,-3199.5 3953.7355,-3428.5 3953.7355,-3428.5 3953.7355,-3434.5 3947.7355,-3440.5 3941.7355,-3440.5 3941.7355,-3440.5 3577.7355,-3440.5 3577.7355,-3440.5 3571.7355,-3440.5 3565.7355,-3434.5 3565.7355,-3428.5 3565.7355,-3428.5 3565.7355,-3199.5 3565.7355,-3199.5 3565.7355,-3193.5 3571.7355,-3187.5 3577.7355,-3187.5"/>
<text text-anchor="middle" x="3600.2355" y="-3310.3" font-family="Times,serif" font-size="14.00" fill="#000000">analyte</text>
<polyline fill="none" stroke="#000000" points="3634.7355,-3187.5 3634.7355,-3440.5 "/>
<text text-anchor="middle" x="3645.2355" y="-3310.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="3655.7355,-3187.5 3655.7355,-3440.5 "/>
<text text-anchor="middle" x="3794.2355" y="-3425.3" font-family="Times,serif" font-size="14.00" fill="#000000">a260_a280_ratio</text>
<polyline fill="none" stroke="#000000" points="3655.7355,-3417.5 3932.7355,-3417.5 "/>
<text text-anchor="middle" x="3794.2355" y="-3402.3" font-family="Times,serif" font-size="14.00" fill="#000000">analyte_concentration</text>
<polyline fill="none" stroke="#000000" points="3655.7355,-3394.5 3932.7355,-3394.5 "/>
<text text-anchor="middle" x="3794.2355" y="-3379.3" font-family="Times,serif" font-size="14.00" fill="#000000">analyte_id</text>
<polyline fill="none" stroke="#000000" points="3655.7355,-3371.5 3932.7355,-3371.5 "/>
<text text-anchor="middle" x="3794.2355" y="-3356.3" font-family="Times,serif" font-size="14.00" fill="#000000">analyte_quantity</text>
<polyline fill="none" stroke="#000000" points="3655.7355,-3348.5 3932.7355,-3348.5 "/>
<text text-anchor="middle" x="3794.2355" y="-3333.3" font-family="Times,serif" font-size="14.00" fill="#000000">analyte_type</text>
<polyline fill="none" stroke="#000000" points="3655.7355,-3325.5 3932.7355,-3325.5 "/>
<text text-anchor="middle" x="3794.2355" y="-3310.3" font-family="Times,serif" font-size="14.00" fill="#000000">analyte_type_id</text>
<polyline fill="none" stroke="#000000" points="3655.7355,-3302.5 3932.7355,-3302.5 "/>
<text text-anchor="middle" x="3794.2355" y="-3287.3" font-family="Times,serif" font-size="14.00" fill="#000000">analyte_volume</text>
<polyline fill="none" stroke="#000000" points="3655.7355,-3279.5 3932.7355,-3279.5 "/>
<text text-anchor="middle" x="3794.2355" y="-3264.3" font-family="Times,serif" font-size="14.00" fill="#000000">normal_tumor_genotype_snp_match</text>
<polyline fill="none" stroke="#000000" points="3655.7355,-3256.5 3932.7355,-3256.5 "/>
<text text-anchor="middle" x="3794.2355" y="-3241.3" font-family="Times,serif" font-size="14.00" fill="#000000">ribosomal_rna_28s_16s_ratio</text>
<polyline fill="none" stroke="#000000" points="3655.7355,-3233.5 3932.7355,-3233.5 "/>
<text text-anchor="middle" x="3794.2355" y="-3218.3" font-family="Times,serif" font-size="14.00" fill="#000000">spectrophotometer_method</text>
<polyline fill="none" stroke="#000000" points="3655.7355,-3210.5 3932.7355,-3210.5 "/>
<text text-anchor="middle" x="3794.2355" y="-3195.3" font-family="Times,serif" font-size="14.00" fill="#000000">well_number</text>
<polyline fill="none" stroke="#000000" points="3932.7355,-3187.5 3932.7355,-3440.5 "/>
<text text-anchor="middle" x="3943.2355" y="-3310.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- analyte&#45;&gt;fraction -->
<g id="edge38" class="edge">
<title>analyte&#45;&gt;fraction</title>
<path fill="none" stroke="#000000" d="M3771.9419,-3187.2924C3780.6995,-3096.3854 3792.157,-2977.4508 3799.2278,-2904.0527"/>
<polygon fill="#000000" stroke="#000000" points="3802.7206,-2904.2954 3800.1957,-2894.0058 3795.7528,-2903.6241 3802.7206,-2904.2954"/>
<text text-anchor="middle" x="3842.7355" y="-3157.8" font-family="Times,serif" font-size="14.00" fill="#000000">analyte_of_fraction</text>
</g>
<!-- analyte&#45;&gt;sample -->
<g id="edge24" class="edge">
<title>analyte&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M3565.5352,-3200.1187C3529.8805,-3182.6091 3492.3432,-3166.2969 3455.7355,-3154 3409.1908,-3138.3651 3379.8397,-3172.2626 3346.7355,-3136 3299.2657,-3084.001 3308.1275,-2574.0189 3300.7355,-2504 3300.4443,-2501.2416 3300.1478,-2498.4703 3299.8462,-2495.6875"/>
<polygon fill="#000000" stroke="#000000" points="3303.3053,-2495.1224 3298.733,-2485.565 3296.3472,-2495.8877 3303.3053,-2495.1224"/>
<text text-anchor="middle" x="3413.2355" y="-2832.8" font-family="Times,serif" font-size="14.00" fill="#000000">analyte_of_sample</text>
</g>
<!-- analyte&#45;&gt;laboratory_procedure -->
<g id="edge12" class="edge">
<title>analyte&#45;&gt;laboratory_procedure</title>
<path fill="none" stroke="#000000" d="M3916.7538,-3187.432C3928.6107,-3171.4425 3938.6843,-3154.2389 3945.7355,-3136 3995.8461,-3006.3838 3951.1775,-2006.7888 3880.7355,-1887 3848.6652,-1832.4634 3800.0161,-1786.6758 3748.3746,-1749.5239"/>
<polygon fill="#000000" stroke="#000000" points="3750.246,-1746.5604 3740.0629,-1743.6354 3746.1994,-1752.2722 3750.246,-1746.5604"/>
<text text-anchor="middle" x="4036.7355" y="-2507.8" font-family="Times,serif" font-size="14.00" fill="#000000">analyte_processed_by</text>
</g>
<!-- sample&#45;&gt;study_subject -->
<g id="edge27" class="edge">
<title>sample&#45;&gt;study_subject</title>
<path fill="none" stroke="#000000" d="M3033.1464,-1991.2624C2963.3833,-1939.3329 2883.4594,-1888.2348 2802.7355,-1854 2605.6518,-1770.4172 2007.0501,-1689.8031 1690.6609,-1651.5681"/>
<polygon fill="#000000" stroke="#000000" points="1690.8019,-1648.0598 1680.4548,-1650.3376 1689.9639,-1655.0095 1690.8019,-1648.0598"/>
<text text-anchor="middle" x="2919.7355" y="-1857.8" font-family="Times,serif" font-size="14.00" fill="#000000">sample_of_study_subject</text>
</g>
<!-- sample&#45;&gt;laboratory_procedure -->
<g id="edge36" class="edge">
<title>sample&#45;&gt;laboratory_procedure</title>
<path fill="none" stroke="#000000" d="M3323.3192,-1887.1311C3327.8325,-1875.8152 3332.6325,-1864.7313 3337.7355,-1854 3354.4897,-1818.7672 3377.3019,-1783.6962 3400.8022,-1752.0763"/>
<polygon fill="#000000" stroke="#000000" points="3403.9004,-1753.7799 3407.1149,-1743.6845 3398.3064,-1749.5718 3403.9004,-1753.7799"/>
<text text-anchor="middle" x="3416.2355" y="-1857.8" font-family="Times,serif" font-size="14.00" fill="#000000">sample_processed_by</text>
</g>
<!-- therapeutic_procedure -->
<g id="node9" class="node">
<title>therapeutic_procedure</title>
<path fill="none" stroke="#000000" d="M1876.2355,-2629.5C1876.2355,-2629.5 2315.2355,-2629.5 2315.2355,-2629.5 2321.2355,-2629.5 2327.2355,-2635.5 2327.2355,-2641.5 2327.2355,-2641.5 2327.2355,-3031.5 2327.2355,-3031.5 2327.2355,-3037.5 2321.2355,-3043.5 2315.2355,-3043.5 2315.2355,-3043.5 1876.2355,-3043.5 1876.2355,-3043.5 1870.2355,-3043.5 1864.2355,-3037.5 1864.2355,-3031.5 1864.2355,-3031.5 1864.2355,-2641.5 1864.2355,-2641.5 1864.2355,-2635.5 1870.2355,-2629.5 1876.2355,-2629.5"/>
<text text-anchor="middle" x="1954.7355" y="-2832.8" font-family="Times,serif" font-size="14.00" fill="#000000">therapeutic_procedure</text>
<polyline fill="none" stroke="#000000" points="2045.2355,-2629.5 2045.2355,-3043.5 "/>
<text text-anchor="middle" x="2055.7355" y="-2832.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="2066.2355,-2629.5 2066.2355,-3043.5 "/>
<text text-anchor="middle" x="2186.2355" y="-3028.3" font-family="Times,serif" font-size="14.00" fill="#000000">all_endocrine_therapy_stopped</text>
<polyline fill="none" stroke="#000000" points="2066.2355,-3020.5 2306.2355,-3020.5 "/>
<text text-anchor="middle" x="2186.2355" y="-3005.3" font-family="Times,serif" font-size="14.00" fill="#000000">chemotherapy_regimen</text>
<polyline fill="none" stroke="#000000" points="2066.2355,-2997.5 2306.2355,-2997.5 "/>
<text text-anchor="middle" x="2186.2355" y="-2982.3" font-family="Times,serif" font-size="14.00" fill="#000000">chemotherapy_regimen_group</text>
<polyline fill="none" stroke="#000000" points="2066.2355,-2974.5 2306.2355,-2974.5 "/>
<text text-anchor="middle" x="2186.2355" y="-2959.3" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_treatment_end</text>
<polyline fill="none" stroke="#000000" points="2066.2355,-2951.5 2306.2355,-2951.5 "/>
<text text-anchor="middle" x="2186.2355" y="-2936.3" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_treatment_start</text>
<polyline fill="none" stroke="#000000" points="2066.2355,-2928.5 2306.2355,-2928.5 "/>
<text text-anchor="middle" x="2186.2355" y="-2913.3" font-family="Times,serif" font-size="14.00" fill="#000000">endocrine_therapy_type</text>
<polyline fill="none" stroke="#000000" points="2066.2355,-2905.5 2306.2355,-2905.5 "/>
<text text-anchor="middle" x="2186.2355" y="-2890.3" font-family="Times,serif" font-size="14.00" fill="#000000">initial_disease_status</text>
<polyline fill="none" stroke="#000000" points="2066.2355,-2882.5 2306.2355,-2882.5 "/>
<text text-anchor="middle" x="2186.2355" y="-2867.3" font-family="Times,serif" font-size="14.00" fill="#000000">primary_surgical_procedure</text>
<polyline fill="none" stroke="#000000" points="2066.2355,-2859.5 2306.2355,-2859.5 "/>
<text text-anchor="middle" x="2186.2355" y="-2844.3" font-family="Times,serif" font-size="14.00" fill="#000000">received_chemotherapy</text>
<polyline fill="none" stroke="#000000" points="2066.2355,-2836.5 2306.2355,-2836.5 "/>
<text text-anchor="middle" x="2186.2355" y="-2821.3" font-family="Times,serif" font-size="14.00" fill="#000000">regimen_or_line_of_therapy</text>
<polyline fill="none" stroke="#000000" points="2066.2355,-2813.5 2306.2355,-2813.5 "/>
<text text-anchor="middle" x="2186.2355" y="-2798.3" font-family="Times,serif" font-size="14.00" fill="#000000">therapeutic_agents</text>
<polyline fill="none" stroke="#000000" points="2066.2355,-2790.5 2306.2355,-2790.5 "/>
<text text-anchor="middle" x="2186.2355" y="-2775.3" font-family="Times,serif" font-size="14.00" fill="#000000">therapeutic_procedure_id</text>
<polyline fill="none" stroke="#000000" points="2066.2355,-2767.5 2306.2355,-2767.5 "/>
<text text-anchor="middle" x="2186.2355" y="-2752.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_anatomic_site</text>
<polyline fill="none" stroke="#000000" points="2066.2355,-2744.5 2306.2355,-2744.5 "/>
<text text-anchor="middle" x="2186.2355" y="-2729.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_effect</text>
<polyline fill="none" stroke="#000000" points="2066.2355,-2721.5 2306.2355,-2721.5 "/>
<text text-anchor="middle" x="2186.2355" y="-2706.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_intent_type</text>
<polyline fill="none" stroke="#000000" points="2066.2355,-2698.5 2306.2355,-2698.5 "/>
<text text-anchor="middle" x="2186.2355" y="-2683.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_or_therapy</text>
<polyline fill="none" stroke="#000000" points="2066.2355,-2675.5 2306.2355,-2675.5 "/>
<text text-anchor="middle" x="2186.2355" y="-2660.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_outcome</text>
<polyline fill="none" stroke="#000000" points="2066.2355,-2652.5 2306.2355,-2652.5 "/>
<text text-anchor="middle" x="2186.2355" y="-2637.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_type</text>
<polyline fill="none" stroke="#000000" points="2306.2355,-2629.5 2306.2355,-3043.5 "/>
<text text-anchor="middle" x="2316.7355" y="-2832.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- therapeutic_procedure&#45;&gt;diagnosis -->
<g id="edge31" class="edge">
<title>therapeutic_procedure&#45;&gt;diagnosis</title>
<path fill="none" stroke="#000000" d="M2035.2267,-2629.4959C2022.7268,-2586.7333 2009.3051,-2540.8171 1996.0073,-2495.3245"/>
<polygon fill="#000000" stroke="#000000" points="1999.3371,-2494.2409 1993.172,-2485.6246 1992.6183,-2496.2049 1999.3371,-2494.2409"/>
<text text-anchor="middle" x="2056.7355" y="-2507.8" font-family="Times,serif" font-size="14.00" fill="#000000">tp_of_diagnosis</text>
</g>
<!-- aliquot&#45;&gt;analyte -->
<g id="edge7" class="edge">
<title>aliquot&#45;&gt;analyte</title>
<path fill="none" stroke="#000000" d="M3591.5443,-3492.3677C3599.0243,-3480.8379 3606.7806,-3469.6052 3614.7355,-3459 3617.319,-3455.5558 3619.982,-3452.1134 3622.7113,-3448.6803"/>
<polygon fill="#000000" stroke="#000000" points="3625.6112,-3450.6611 3629.1934,-3440.6902 3620.1751,-3446.251 3625.6112,-3450.6611"/>
<text text-anchor="middle" x="3680.2355" y="-3462.8" font-family="Times,serif" font-size="14.00" fill="#000000">aliquot_of_analyte</text>
</g>
<!-- aliquot&#45;&gt;sample -->
<g id="edge16" class="edge">
<title>aliquot&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M3487.4555,-3492.4247C3472.3589,-3395.3591 3441.3556,-3276.1513 3377.7355,-3187 3353.8916,-3153.5873 3320.9907,-3171.7025 3300.7355,-3136 3284.87,-3108.0347 3272.0127,-2762.1227 3264.3822,-2495.8077"/>
<polygon fill="#000000" stroke="#000000" points="3267.8741,-2495.4709 3264.0904,-2485.5748 3260.877,-2495.6705 3267.8741,-2495.4709"/>
<text text-anchor="middle" x="3420.7355" y="-3157.8" font-family="Times,serif" font-size="14.00" fill="#000000">aliquot_of_sample</text>
</g>
<!-- aliquot&#45;&gt;laboratory_procedure -->
<g id="edge37" class="edge">
<title>aliquot&#45;&gt;laboratory_procedure</title>
<path fill="none" stroke="#000000" d="M3502.3293,-3492.2477C3503.7084,-3091.032 3507.1019,-2103.774 3508.3045,-1753.915"/>
<polygon fill="#000000" stroke="#000000" points="3511.8049,-1753.7633 3508.3394,-1743.7513 3504.8049,-1753.7392 3511.8049,-1753.7633"/>
<text text-anchor="middle" x="3582.2355" y="-2832.8" font-family="Times,serif" font-size="14.00" fill="#000000">aliquot_processed_by</text>
</g>
<!-- follow_up -->
<g id="node11" class="node">
<title>follow_up</title>
<path fill="none" stroke="#000000" d="M2357.2355,-2537.5C2357.2355,-2537.5 2774.2355,-2537.5 2774.2355,-2537.5 2780.2355,-2537.5 2786.2355,-2543.5 2786.2355,-2549.5 2786.2355,-2549.5 2786.2355,-3123.5 2786.2355,-3123.5 2786.2355,-3129.5 2780.2355,-3135.5 2774.2355,-3135.5 2774.2355,-3135.5 2357.2355,-3135.5 2357.2355,-3135.5 2351.2355,-3135.5 2345.2355,-3129.5 2345.2355,-3123.5 2345.2355,-3123.5 2345.2355,-2549.5 2345.2355,-2549.5 2345.2355,-2543.5 2351.2355,-2537.5 2357.2355,-2537.5"/>
<text text-anchor="middle" x="2387.7355" y="-2832.8" font-family="Times,serif" font-size="14.00" fill="#000000">follow_up</text>
<polyline fill="none" stroke="#000000" points="2430.2355,-2537.5 2430.2355,-3135.5 "/>
<text text-anchor="middle" x="2440.7355" y="-2832.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="2451.2355,-2537.5 2451.2355,-3135.5 "/>
<text text-anchor="middle" x="2608.2355" y="-3120.3" font-family="Times,serif" font-size="14.00" fill="#000000">adverse_event</text>
<polyline fill="none" stroke="#000000" points="2451.2355,-3112.5 2765.2355,-3112.5 "/>
<text text-anchor="middle" x="2608.2355" y="-3097.3" font-family="Times,serif" font-size="14.00" fill="#000000">barretts_esophagus_goblet_cells_present</text>
<polyline fill="none" stroke="#000000" points="2451.2355,-3089.5 2765.2355,-3089.5 "/>
<text text-anchor="middle" x="2608.2355" y="-3074.3" font-family="Times,serif" font-size="14.00" fill="#000000">bmi</text>
<polyline fill="none" stroke="#000000" points="2451.2355,-3066.5 2765.2355,-3066.5 "/>
<text text-anchor="middle" x="2608.2355" y="-3051.3" font-family="Times,serif" font-size="14.00" fill="#000000">cause_of_response</text>
<polyline fill="none" stroke="#000000" points="2451.2355,-3043.5 2765.2355,-3043.5 "/>
<text text-anchor="middle" x="2608.2355" y="-3028.3" font-family="Times,serif" font-size="14.00" fill="#000000">comorbidity</text>
<polyline fill="none" stroke="#000000" points="2451.2355,-3020.5 2765.2355,-3020.5 "/>
<text text-anchor="middle" x="2608.2355" y="-3005.3" font-family="Times,serif" font-size="14.00" fill="#000000">comorbidity_method_of_diagnosis</text>
<polyline fill="none" stroke="#000000" points="2451.2355,-2997.5 2765.2355,-2997.5 "/>
<text text-anchor="middle" x="2608.2355" y="-2982.3" font-family="Times,serif" font-size="14.00" fill="#000000">contact_type</text>
<polyline fill="none" stroke="#000000" points="2451.2355,-2974.5 2765.2355,-2974.5 "/>
<text text-anchor="middle" x="2608.2355" y="-2959.3" font-family="Times,serif" font-size="14.00" fill="#000000">date_of_last_contact</text>
<polyline fill="none" stroke="#000000" points="2451.2355,-2951.5 2765.2355,-2951.5 "/>
<text text-anchor="middle" x="2608.2355" y="-2936.3" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_adverse_event</text>
<polyline fill="none" stroke="#000000" points="2451.2355,-2928.5 2765.2355,-2928.5 "/>
<text text-anchor="middle" x="2608.2355" y="-2913.3" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_comorbidity</text>
<polyline fill="none" stroke="#000000" points="2451.2355,-2905.5 2765.2355,-2905.5 "/>
<text text-anchor="middle" x="2608.2355" y="-2890.3" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_distant_recurrence</text>
<polyline fill="none" stroke="#000000" points="2451.2355,-2882.5 2765.2355,-2882.5 "/>
<text text-anchor="middle" x="2608.2355" y="-2867.3" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_follow_up</text>
<polyline fill="none" stroke="#000000" points="2451.2355,-2859.5 2765.2355,-2859.5 "/>
<text text-anchor="middle" x="2608.2355" y="-2844.3" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_progression</text>
<polyline fill="none" stroke="#000000" points="2451.2355,-2836.5 2765.2355,-2836.5 "/>
<text text-anchor="middle" x="2608.2355" y="-2821.3" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_progression_free</text>
<polyline fill="none" stroke="#000000" points="2451.2355,-2813.5 2765.2355,-2813.5 "/>
<text text-anchor="middle" x="2608.2355" y="-2798.3" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_recurrence</text>
<polyline fill="none" stroke="#000000" points="2451.2355,-2790.5 2765.2355,-2790.5 "/>
<text text-anchor="middle" x="2608.2355" y="-2775.3" font-family="Times,serif" font-size="14.00" fill="#000000">dfs_event_indicator</text>
<polyline fill="none" stroke="#000000" points="2451.2355,-2767.5 2765.2355,-2767.5 "/>
<text text-anchor="middle" x="2608.2355" y="-2752.3" font-family="Times,serif" font-size="14.00" fill="#000000">dfs_event_type</text>
<polyline fill="none" stroke="#000000" points="2451.2355,-2744.5 2765.2355,-2744.5 "/>
<text text-anchor="middle" x="2608.2355" y="-2729.3" font-family="Times,serif" font-size="14.00" fill="#000000">diabetes_treatment_type</text>
<polyline fill="none" stroke="#000000" points="2451.2355,-2721.5 2765.2355,-2721.5 "/>
<text text-anchor="middle" x="2608.2355" y="-2706.3" font-family="Times,serif" font-size="14.00" fill="#000000">disease_response</text>
<polyline fill="none" stroke="#000000" points="2451.2355,-2698.5 2765.2355,-2698.5 "/>
<text text-anchor="middle" x="2608.2355" y="-2683.3" font-family="Times,serif" font-size="14.00" fill="#000000">distant_recurrence_indicator</text>
<polyline fill="none" stroke="#000000" points="2451.2355,-2675.5 2765.2355,-2675.5 "/>
<text text-anchor="middle" x="2608.2355" y="-2660.3" font-family="Times,serif" font-size="14.00" fill="#000000">dlco_ref_predictive_percent</text>
<polyline fill="none" stroke="#000000" points="2451.2355,-2652.5 2765.2355,-2652.5 "/>
<text text-anchor="middle" x="2608.2355" y="-2637.3" font-family="Times,serif" font-size="14.00" fill="#000000">document_number</text>
<polyline fill="none" stroke="#000000" points="2451.2355,-2629.5 2765.2355,-2629.5 "/>
<text text-anchor="middle" x="2608.2355" y="-2614.3" font-family="Times,serif" font-size="14.00" fill="#000000">ecog_performance_status</text>
<polyline fill="none" stroke="#000000" points="2451.2355,-2606.5 2765.2355,-2606.5 "/>
<text text-anchor="middle" x="2608.2355" y="-2591.3" font-family="Times,serif" font-size="14.00" fill="#000000">explain_unknown_status</text>
<polyline fill="none" stroke="#000000" points="2451.2355,-2583.5 2765.2355,-2583.5 "/>
<text text-anchor="middle" x="2608.2355" y="-2568.3" font-family="Times,serif" font-size="14.00" fill="#000000">fev1_fvc_post_bronch_percent</text>
<polyline fill="none" stroke="#000000" points="2451.2355,-2560.5 2765.2355,-2560.5 "/>
<text text-anchor="middle" x="2608.2355" y="-2545.3" font-family="Times,serif" font-size="14.00" fill="#000000">+ 24 properties</text>
<polyline fill="none" stroke="#000000" points="2765.2355,-2537.5 2765.2355,-3135.5 "/>
<text text-anchor="middle" x="2775.7355" y="-2832.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- follow_up&#45;&gt;study_subject -->
<g id="edge30" class="edge">
<title>follow_up&#45;&gt;study_subject</title>
<path fill="none" stroke="#000000" d="M2612.2278,-2537.101C2613.9961,-2519.8388 2615.526,-2502.7127 2616.7355,-2486 2626.344,-2353.2361 2699.6733,-1991.1149 2616.7355,-1887 2503.0916,-1744.3384 1982.9147,-1673.9591 1690.6182,-1645.128"/>
<polygon fill="#000000" stroke="#000000" points="1690.6108,-1641.6106 1680.3174,-1644.1198 1689.9289,-1648.5773 1690.6108,-1641.6106"/>
<text text-anchor="middle" x="2727.2355" y="-2182.8" font-family="Times,serif" font-size="14.00" fill="#000000">fu_of_study_subject</text>
</g>
<!-- follow_up&#45;&gt;diagnosis -->
<g id="edge21" class="edge">
<title>follow_up&#45;&gt;diagnosis</title>
<path fill="none" stroke="#000000" d="M2344.9356,-2542.439C2342.2226,-2540.5824 2339.4892,-2538.7686 2336.7355,-2537 2250.8263,-2481.8213 2197.2952,-2543.2254 2112.7355,-2486 2112.4411,-2485.8007 2112.1469,-2485.6009 2111.8531,-2485.4005"/>
<polygon fill="#000000" stroke="#000000" points="2113.5995,-2482.3488 2103.4138,-2479.433 2109.558,-2488.0643 2113.5995,-2482.3488"/>
<text text-anchor="middle" x="2352.2355" y="-2507.8" font-family="Times,serif" font-size="14.00" fill="#000000">fu_of_diagnosis</text>
</g>
<!-- institution -->
<g id="node12" class="node">
<title>institution</title>
<path fill="none" stroke="#000000" d="M508.2355,-.5C508.2355,-.5 787.2355,-.5 787.2355,-.5 793.2355,-.5 799.2355,-6.5 799.2355,-12.5 799.2355,-12.5 799.2355,-80.5 799.2355,-80.5 799.2355,-86.5 793.2355,-92.5 787.2355,-92.5 787.2355,-92.5 508.2355,-92.5 508.2355,-92.5 502.2355,-92.5 496.2355,-86.5 496.2355,-80.5 496.2355,-80.5 496.2355,-12.5 496.2355,-12.5 496.2355,-6.5 502.2355,-.5 508.2355,-.5"/>
<text text-anchor="middle" x="541.7355" y="-42.8" font-family="Times,serif" font-size="14.00" fill="#000000">institution</text>
<polyline fill="none" stroke="#000000" points="587.2355,-.5 587.2355,-92.5 "/>
<text text-anchor="middle" x="597.7355" y="-42.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="608.2355,-.5 608.2355,-92.5 "/>
<text text-anchor="middle" x="693.2355" y="-77.3" font-family="Times,serif" font-size="14.00" fill="#000000">institution_acronymn</text>
<polyline fill="none" stroke="#000000" points="608.2355,-69.5 778.2355,-69.5 "/>
<text text-anchor="middle" x="693.2355" y="-54.3" font-family="Times,serif" font-size="14.00" fill="#000000">institution_id</text>
<polyline fill="none" stroke="#000000" points="608.2355,-46.5 778.2355,-46.5 "/>
<text text-anchor="middle" x="693.2355" y="-31.3" font-family="Times,serif" font-size="14.00" fill="#000000">institution_name</text>
<polyline fill="none" stroke="#000000" points="608.2355,-23.5 778.2355,-23.5 "/>
<text text-anchor="middle" x="693.2355" y="-8.3" font-family="Times,serif" font-size="14.00" fill="#000000">institution_url</text>
<polyline fill="none" stroke="#000000" points="778.2355,-.5 778.2355,-92.5 "/>
<text text-anchor="middle" x="788.7355" y="-42.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- diagnosis&#45;&gt;study_subject -->
<g id="edge28" class="edge">
<title>diagnosis&#45;&gt;study_subject</title>
<path fill="none" stroke="#000000" d="M1740.8748,-1887.0873C1732.9604,-1875.7533 1724.9027,-1864.6813 1716.7355,-1854 1707.4632,-1841.8733 1697.5658,-1829.7517 1687.2845,-1817.7738"/>
<polygon fill="#000000" stroke="#000000" points="1689.6721,-1815.185 1680.4754,-1809.9247 1684.3845,-1819.772 1689.6721,-1815.185"/>
<text text-anchor="middle" x="1820.7355" y="-1857.8" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_of_study_subject</text>
</g>
<!-- project&#45;&gt;program -->
<g id="edge25" class="edge">
<title>project&#45;&gt;program</title>
<path fill="none" stroke="#000000" d="M358.375,-847.1837C396.2801,-792.7962 437.0392,-734.3137 475.659,-678.9008"/>
<polygon fill="#000000" stroke="#000000" points="478.7427,-680.5975 481.5891,-670.3922 472.9998,-676.595 478.7427,-680.5975"/>
<text text-anchor="middle" x="496.7355" y="-741.8" font-family="Times,serif" font-size="14.00" fill="#000000">project_of_program</text>
</g>
<!-- exposure -->
<g id="node15" class="node">
<title>exposure</title>
<path fill="none" stroke="#000000" d="M325.2355,-1945C325.2355,-1945 736.2355,-1945 736.2355,-1945 742.2355,-1945 748.2355,-1951 748.2355,-1957 748.2355,-1957 748.2355,-2416 748.2355,-2416 748.2355,-2422 742.2355,-2428 736.2355,-2428 736.2355,-2428 325.2355,-2428 325.2355,-2428 319.2355,-2428 313.2355,-2422 313.2355,-2416 313.2355,-2416 313.2355,-1957 313.2355,-1957 313.2355,-1951 319.2355,-1945 325.2355,-1945"/>
<text text-anchor="middle" x="354.2355" y="-2182.8" font-family="Times,serif" font-size="14.00" fill="#000000">exposure</text>
<polyline fill="none" stroke="#000000" points="395.2355,-1945 395.2355,-2428 "/>
<text text-anchor="middle" x="405.7355" y="-2182.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="416.2355,-1945 416.2355,-2428 "/>
<text text-anchor="middle" x="571.7355" y="-2412.8" font-family="Times,serif" font-size="14.00" fill="#000000">alcohol_days_per_week</text>
<polyline fill="none" stroke="#000000" points="416.2355,-2405 727.2355,-2405 "/>
<text text-anchor="middle" x="571.7355" y="-2389.8" font-family="Times,serif" font-size="14.00" fill="#000000">alcohol_drinks_per_day</text>
<polyline fill="none" stroke="#000000" points="416.2355,-2382 727.2355,-2382 "/>
<text text-anchor="middle" x="571.7355" y="-2366.8" font-family="Times,serif" font-size="14.00" fill="#000000">alcohol_history</text>
<polyline fill="none" stroke="#000000" points="416.2355,-2359 727.2355,-2359 "/>
<text text-anchor="middle" x="571.7355" y="-2343.8" font-family="Times,serif" font-size="14.00" fill="#000000">alcohol_intensity</text>
<polyline fill="none" stroke="#000000" points="416.2355,-2336 727.2355,-2336 "/>
<text text-anchor="middle" x="571.7355" y="-2320.8" font-family="Times,serif" font-size="14.00" fill="#000000">asbestos_exposure</text>
<polyline fill="none" stroke="#000000" points="416.2355,-2313 727.2355,-2313 "/>
<text text-anchor="middle" x="571.7355" y="-2297.8" font-family="Times,serif" font-size="14.00" fill="#000000">bmi</text>
<polyline fill="none" stroke="#000000" points="416.2355,-2290 727.2355,-2290 "/>
<text text-anchor="middle" x="571.7355" y="-2274.8" font-family="Times,serif" font-size="14.00" fill="#000000">cigarettes_per_day</text>
<polyline fill="none" stroke="#000000" points="416.2355,-2267 727.2355,-2267 "/>
<text text-anchor="middle" x="571.7355" y="-2251.8" font-family="Times,serif" font-size="14.00" fill="#000000">coal_dust_exposure</text>
<polyline fill="none" stroke="#000000" points="416.2355,-2244 727.2355,-2244 "/>
<text text-anchor="middle" x="571.7355" y="-2228.8" font-family="Times,serif" font-size="14.00" fill="#000000">environmental_tobacco_smoke_exposure</text>
<polyline fill="none" stroke="#000000" points="416.2355,-2221 727.2355,-2221 "/>
<text text-anchor="middle" x="571.7355" y="-2205.8" font-family="Times,serif" font-size="14.00" fill="#000000">exposure_node_id</text>
<polyline fill="none" stroke="#000000" points="416.2355,-2198 727.2355,-2198 "/>
<text text-anchor="middle" x="571.7355" y="-2182.8" font-family="Times,serif" font-size="14.00" fill="#000000">pack_years_smoked</text>
<polyline fill="none" stroke="#000000" points="416.2355,-2175 727.2355,-2175 "/>
<text text-anchor="middle" x="571.7355" y="-2159.8" font-family="Times,serif" font-size="14.00" fill="#000000">radon_exposure</text>
<polyline fill="none" stroke="#000000" points="416.2355,-2152 727.2355,-2152 "/>
<text text-anchor="middle" x="571.7355" y="-2136.8" font-family="Times,serif" font-size="14.00" fill="#000000">respirable_crystalline_silica_exposure</text>
<polyline fill="none" stroke="#000000" points="416.2355,-2129 727.2355,-2129 "/>
<text text-anchor="middle" x="571.7355" y="-2113.8" font-family="Times,serif" font-size="14.00" fill="#000000">smoking_frequency</text>
<polyline fill="none" stroke="#000000" points="416.2355,-2106 727.2355,-2106 "/>
<text text-anchor="middle" x="571.7355" y="-2090.8" font-family="Times,serif" font-size="14.00" fill="#000000">time_between_waking_and_first_smoke</text>
<polyline fill="none" stroke="#000000" points="416.2355,-2083 727.2355,-2083 "/>
<text text-anchor="middle" x="571.7355" y="-2067.8" font-family="Times,serif" font-size="14.00" fill="#000000">tobacco_smoking_onset_year</text>
<polyline fill="none" stroke="#000000" points="416.2355,-2060 727.2355,-2060 "/>
<text text-anchor="middle" x="571.7355" y="-2044.8" font-family="Times,serif" font-size="14.00" fill="#000000">tobacco_smoking_quit_year</text>
<polyline fill="none" stroke="#000000" points="416.2355,-2037 727.2355,-2037 "/>
<text text-anchor="middle" x="571.7355" y="-2021.8" font-family="Times,serif" font-size="14.00" fill="#000000">tobacco_smoking_status</text>
<polyline fill="none" stroke="#000000" points="416.2355,-2014 727.2355,-2014 "/>
<text text-anchor="middle" x="571.7355" y="-1998.8" font-family="Times,serif" font-size="14.00" fill="#000000">type_of_smoke_exposure</text>
<polyline fill="none" stroke="#000000" points="416.2355,-1991 727.2355,-1991 "/>
<text text-anchor="middle" x="571.7355" y="-1975.8" font-family="Times,serif" font-size="14.00" fill="#000000">type_of_tobacco_used</text>
<polyline fill="none" stroke="#000000" points="416.2355,-1968 727.2355,-1968 "/>
<text text-anchor="middle" x="571.7355" y="-1952.8" font-family="Times,serif" font-size="14.00" fill="#000000">years_smoked</text>
<polyline fill="none" stroke="#000000" points="727.2355,-1945 727.2355,-2428 "/>
<text text-anchor="middle" x="737.7355" y="-2182.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- exposure&#45;&gt;study_subject -->
<g id="edge5" class="edge">
<title>exposure&#45;&gt;study_subject</title>
<path fill="none" stroke="#000000" d="M692.5775,-1944.9725C712.884,-1923.6654 734.6854,-1903.8364 757.7355,-1887 916.8133,-1770.8055 1132.8656,-1703.0261 1288.9734,-1666.2544"/>
<polygon fill="#000000" stroke="#000000" points="1290.2243,-1669.5567 1299.1681,-1663.877 1288.6345,-1662.7396 1290.2243,-1669.5567"/>
<text text-anchor="middle" x="889.7355" y="-1857.8" font-family="Times,serif" font-size="14.00" fill="#000000">exposure_of_study_subject</text>
</g>
<!-- family_medical_history -->
<g id="node16" class="node">
<title>family_medical_history</title>
<path fill="none" stroke="#000000" d="M778.7355,-2106C778.7355,-2106 1258.7355,-2106 1258.7355,-2106 1264.7355,-2106 1270.7355,-2112 1270.7355,-2118 1270.7355,-2118 1270.7355,-2255 1270.7355,-2255 1270.7355,-2261 1264.7355,-2267 1258.7355,-2267 1258.7355,-2267 778.7355,-2267 778.7355,-2267 772.7355,-2267 766.7355,-2261 766.7355,-2255 766.7355,-2255 766.7355,-2118 766.7355,-2118 766.7355,-2112 772.7355,-2106 778.7355,-2106"/>
<text text-anchor="middle" x="857.7355" y="-2182.8" font-family="Times,serif" font-size="14.00" fill="#000000">family_medical_history</text>
<polyline fill="none" stroke="#000000" points="948.7355,-2106 948.7355,-2267 "/>
<text text-anchor="middle" x="959.2355" y="-2182.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="969.7355,-2106 969.7355,-2267 "/>
<text text-anchor="middle" x="1109.7355" y="-2251.8" font-family="Times,serif" font-size="14.00" fill="#000000">family_history_id</text>
<polyline fill="none" stroke="#000000" points="969.7355,-2244 1249.7355,-2244 "/>
<text text-anchor="middle" x="1109.7355" y="-2228.8" font-family="Times,serif" font-size="14.00" fill="#000000">relationship_age_at_diagnosis</text>
<polyline fill="none" stroke="#000000" points="969.7355,-2221 1249.7355,-2221 "/>
<text text-anchor="middle" x="1109.7355" y="-2205.8" font-family="Times,serif" font-size="14.00" fill="#000000">relationship_gender</text>
<polyline fill="none" stroke="#000000" points="969.7355,-2198 1249.7355,-2198 "/>
<text text-anchor="middle" x="1109.7355" y="-2182.8" font-family="Times,serif" font-size="14.00" fill="#000000">relationship_primary_diagnosis</text>
<polyline fill="none" stroke="#000000" points="969.7355,-2175 1249.7355,-2175 "/>
<text text-anchor="middle" x="1109.7355" y="-2159.8" font-family="Times,serif" font-size="14.00" fill="#000000">relationship_type</text>
<polyline fill="none" stroke="#000000" points="969.7355,-2152 1249.7355,-2152 "/>
<text text-anchor="middle" x="1109.7355" y="-2136.8" font-family="Times,serif" font-size="14.00" fill="#000000">relative_with_cancer_history</text>
<polyline fill="none" stroke="#000000" points="969.7355,-2129 1249.7355,-2129 "/>
<text text-anchor="middle" x="1109.7355" y="-2113.8" font-family="Times,serif" font-size="14.00" fill="#000000">relatives_with_cancer_history_count</text>
<polyline fill="none" stroke="#000000" points="1249.7355,-2106 1249.7355,-2267 "/>
<text text-anchor="middle" x="1260.2355" y="-2182.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- family_medical_history&#45;&gt;study_subject -->
<g id="edge35" class="edge">
<title>family_medical_history&#45;&gt;study_subject</title>
<path fill="none" stroke="#000000" d="M1086.72,-2105.9579C1144.6406,-2037.3386 1230.5909,-1935.5121 1308.256,-1843.5012"/>
<polygon fill="#000000" stroke="#000000" points="1311.01,-1845.6648 1314.7856,-1835.7655 1305.6608,-1841.1496 1311.01,-1845.6648"/>
<text text-anchor="middle" x="1374.2355" y="-1857.8" font-family="Times,serif" font-size="14.00" fill="#000000">fmh_of_study_subject</text>
</g>
<!-- report -->
<g id="node17" class="node">
<title>report</title>
<path fill="none" stroke="#000000" d="M3644.7355,-3912.5C3644.7355,-3912.5 3874.7355,-3912.5 3874.7355,-3912.5 3880.7355,-3912.5 3886.7355,-3918.5 3886.7355,-3924.5 3886.7355,-3924.5 3886.7355,-4084.5 3886.7355,-4084.5 3886.7355,-4090.5 3880.7355,-4096.5 3874.7355,-4096.5 3874.7355,-4096.5 3644.7355,-4096.5 3644.7355,-4096.5 3638.7355,-4096.5 3632.7355,-4090.5 3632.7355,-4084.5 3632.7355,-4084.5 3632.7355,-3924.5 3632.7355,-3924.5 3632.7355,-3918.5 3638.7355,-3912.5 3644.7355,-3912.5"/>
<text text-anchor="middle" x="3663.7355" y="-4000.8" font-family="Times,serif" font-size="14.00" fill="#000000">report</text>
<polyline fill="none" stroke="#000000" points="3694.7355,-3912.5 3694.7355,-4096.5 "/>
<text text-anchor="middle" x="3705.2355" y="-4000.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="3715.7355,-3912.5 3715.7355,-4096.5 "/>
<text text-anchor="middle" x="3790.7355" y="-4081.3" font-family="Times,serif" font-size="14.00" fill="#000000">md5sum</text>
<polyline fill="none" stroke="#000000" points="3715.7355,-4073.5 3865.7355,-4073.5 "/>
<text text-anchor="middle" x="3790.7355" y="-4058.3" font-family="Times,serif" font-size="14.00" fill="#000000">report_description</text>
<polyline fill="none" stroke="#000000" points="3715.7355,-4050.5 3865.7355,-4050.5 "/>
<text text-anchor="middle" x="3790.7355" y="-4035.3" font-family="Times,serif" font-size="14.00" fill="#000000">report_format</text>
<polyline fill="none" stroke="#000000" points="3715.7355,-4027.5 3865.7355,-4027.5 "/>
<text text-anchor="middle" x="3790.7355" y="-4012.3" font-family="Times,serif" font-size="14.00" fill="#000000">report_id</text>
<polyline fill="none" stroke="#000000" points="3715.7355,-4004.5 3865.7355,-4004.5 "/>
<text text-anchor="middle" x="3790.7355" y="-3989.3" font-family="Times,serif" font-size="14.00" fill="#000000">report_location</text>
<polyline fill="none" stroke="#000000" points="3715.7355,-3981.5 3865.7355,-3981.5 "/>
<text text-anchor="middle" x="3790.7355" y="-3966.3" font-family="Times,serif" font-size="14.00" fill="#000000">report_name</text>
<polyline fill="none" stroke="#000000" points="3715.7355,-3958.5 3865.7355,-3958.5 "/>
<text text-anchor="middle" x="3790.7355" y="-3943.3" font-family="Times,serif" font-size="14.00" fill="#000000">report_size</text>
<polyline fill="none" stroke="#000000" points="3715.7355,-3935.5 3865.7355,-3935.5 "/>
<text text-anchor="middle" x="3790.7355" y="-3920.3" font-family="Times,serif" font-size="14.00" fill="#000000">report_type</text>
<polyline fill="none" stroke="#000000" points="3865.7355,-3912.5 3865.7355,-4096.5 "/>
<text text-anchor="middle" x="3876.2355" y="-4000.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- report&#45;&gt;fraction -->
<g id="edge15" class="edge">
<title>report&#45;&gt;fraction</title>
<path fill="none" stroke="#000000" d="M3844.9195,-3912.45C3862.4111,-3889.5066 3879.0337,-3863.9924 3890.7355,-3838 3950.4858,-3705.2809 3993.1572,-3329.334 3962.7355,-3187 3940.3953,-3082.4766 3884.4728,-2971.422 3845.785,-2902.9998"/>
<polygon fill="#000000" stroke="#000000" points="3848.6747,-2901.0015 3840.6828,-2894.046 3842.5928,-2904.4672 3848.6747,-2901.0015"/>
<text text-anchor="middle" x="4030.7355" y="-3462.8" font-family="Times,serif" font-size="14.00" fill="#000000">report_of_fraction</text>
</g>
<!-- report&#45;&gt;analyte -->
<g id="edge14" class="edge">
<title>report&#45;&gt;analyte</title>
<path fill="none" stroke="#000000" d="M3759.7355,-3912.45C3759.7355,-3794.0619 3759.7355,-3587.4482 3759.7355,-3450.6794"/>
<polygon fill="#000000" stroke="#000000" points="3763.2356,-3450.5451 3759.7355,-3440.5451 3756.2356,-3450.5452 3763.2356,-3450.5451"/>
<text text-anchor="middle" x="3823.2355" y="-3661.3" font-family="Times,serif" font-size="14.00" fill="#000000">report_of_analyte</text>
</g>
<!-- report&#45;&gt;sample -->
<g id="edge39" class="edge">
<title>report&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M3632.5325,-3987.2818C3501.3113,-3966.6996 3309.4047,-3927.7629 3262.7355,-3871 3204.4559,-3800.1154 3248.7355,-3756.7667 3248.7355,-3665 3248.7355,-3665 3248.7355,-3665 3248.7355,-2836.5 3248.7355,-2725.4192 3249.9182,-2603.6685 3251.374,-2495.8733"/>
<polygon fill="#000000" stroke="#000000" points="3254.8743,-2495.8661 3251.5111,-2485.8193 3247.875,-2495.7706 3254.8743,-2495.8661"/>
<text text-anchor="middle" x="3311.2355" y="-3310.3" font-family="Times,serif" font-size="14.00" fill="#000000">report_of_sample</text>
</g>
<!-- report&#45;&gt;aliquot -->
<g id="edge23" class="edge">
<title>report&#45;&gt;aliquot</title>
<path fill="none" stroke="#000000" d="M3657.9471,-3912.4034C3645.166,-3899.0373 3632.7362,-3885.0368 3621.7355,-3871 3615.4476,-3862.9766 3609.2589,-3854.5903 3603.2085,-3845.9853"/>
<polygon fill="#000000" stroke="#000000" points="3606.0223,-3843.9007 3597.4512,-3837.6727 3600.2677,-3847.8864 3606.0223,-3843.9007"/>
<text text-anchor="middle" x="3683.7355" y="-3859.8" font-family="Times,serif" font-size="14.00" fill="#000000">report_of_aliquot</text>
</g>
<!-- report&#45;&gt;laboratory_procedure -->
<g id="edge18" class="edge">
<title>report&#45;&gt;laboratory_procedure</title>
<path fill="none" stroke="#000000" d="M3886.9188,-3952.9398C3996.6942,-3899.034 4137.7355,-3802.9355 4137.7355,-3665 4137.7355,-3665 4137.7355,-3665 4137.7355,-2186.5 4137.7355,-1973.068 3932.5663,-1821.4182 3756.5822,-1730.598"/>
<polygon fill="#000000" stroke="#000000" points="3757.9271,-1727.3546 3747.4304,-1725.9159 3754.7388,-1733.5864 3757.9271,-1727.3546"/>
<text text-anchor="middle" x="4252.2355" y="-3157.8" font-family="Times,serif" font-size="14.00" fill="#000000">report_of_laboratory_procedure</text>
</g>
<!-- program&#45;&gt;institution -->
<g id="edge26" class="edge">
<title>program&#45;&gt;institution</title>
<path fill="none" stroke="#000000" d="M647.7355,-144.2763C647.7355,-129.2309 647.7355,-115.2147 647.7355,-102.7601"/>
<polygon fill="#000000" stroke="#000000" points="651.2356,-102.6771 647.7355,-92.6771 644.2356,-102.6772 651.2356,-102.6771"/>
<text text-anchor="middle" x="730.2355" y="-114.8" font-family="Times,serif" font-size="14.00" fill="#000000">program_of_institution</text>
</g>
<!-- study&#45;&gt;program -->
<g id="edge1" class="edge">
<title>study&#45;&gt;program</title>
<path fill="none" stroke="#000000" d="M647.7355,-771.3472C647.7355,-757.5169 647.7355,-743.6361 647.7355,-729.8091"/>
<polygon fill="#000000" stroke="#000000" points="651.2356,-729.752 647.7355,-719.752 644.2356,-729.752 651.2356,-729.752"/>
<text text-anchor="middle" x="712.7355" y="-741.8" font-family="Times,serif" font-size="14.00" fill="#000000">study_of_program</text>
</g>
<!-- laboratory_procedure&#45;&gt;program -->
<g id="edge34" class="edge">
<title>laboratory_procedure&#45;&gt;program</title>
<path fill="none" stroke="#000000" d="M3301.6344,-1513.4208C2979.134,-1337.3497 2334.2148,-997.7102 1759.7355,-771 1436.7018,-643.5192 1045.5479,-534.2582 823.7823,-476.3163"/>
<polygon fill="#000000" stroke="#000000" points="824.5645,-472.9033 814.0049,-473.7663 822.7979,-479.6767 824.5645,-472.9033"/>
<text text-anchor="middle" x="3145.7355" y="-1066.8" font-family="Times,serif" font-size="14.00" fill="#000000">laboratory_procedure_of_program</text>
</g>
</g>
</svg>
</div>
