---
weight: 60
title: Application enablement
layout: bundle
---

{{< c8y-admon-info >}}
These release notes contain all changes until build version 10.18.0.59.
{{< /c8y-admon-info >}}

### Improvements

<table>
<colgroup>
<col style="width: 15%;">
<col style="width:50%;">
<col style="width: 10%;">
<col style="width: 12%;">
<col style="width: 13%;">
</colgroup>
<thead><tr>
<th>
Product area</th>
<th>
Description</th>
<th>
Issue</th>
<th>
Build version</th>
<th>Build comp.</th>
</tr>
</thead><tbody>


<tr>
<td>Cockpit</td>
<td>The "Rotation" widget has been migrated to Angular.</td>
<td>MTM-50847</td>
<td>10.17.68.0</td>
<td>UI</td>
</tr>

<tr>
<td>Cockpit</td>
<td>Widgets that use the global date context are now marked with an icon and a corresponding tooltip.</td>
<td>MTM-51225</td>
<td>10.17.68.0</td>
<td>UI</td>
</tr>

<tr>
<td>Cockpit</td>
<td>It is now possible to use a global time range in "Data point table" widgets so that you can align all data point graphs on a dashboard to the same time range without setting each time range individually.</td>
<td>MTM-50924</td>
<td>10.17.68.0</td>
<td>UI</td>
</tr>

<tr>
<td>Cockpit</td>
<td>It is now possible to a the global time range in "Event list" widgets so that you can align all data point graphs on a dashboard to the same time range without setting each time range individually.</td>
<td>MTM-50925</td>
<td>10.17.67.0</td>
<td>UI</td>
</tr>

<tr>
<td>Cockpit</td>
<td>It is now possible to use a global time range in "Data point graph" widgets so that you can align all data point graphs on a dashboard to the same time range without setting each time range individually.</td>
<td>MTM-48198</td>
<td>10.17.11.0</td>
<td>UI</td>
</tr>

<tr>
<td>Microservices</td>
<td>The Smartrule agent now uses the Microservice API 2.</td>
<td>MTM-48740</td>
<td>10.17.178.0</td>
<td>Core</td>
</tr>

<tr>
<td>Microservices</td>
<td>The Report agent now uses the Microservice API 2.</td>
<td>MTM-48736</td>
<td>10.17.178.0</td>
<td>Core</td>
</tr>

<tr>
<td>Microservices</td>
<td>The Echo agent now uses the Microservice API 2.</td>
<td>MTM-48729</td>
<td>10.17.178.0</td>
<td>Core</td>
</tr>

<tr>
<td>Microservices</td>
<td>The Java SDK and the Microservice SDK are now compatible with Java 17.</td>
<td>MTM-44319</td>
<td>10.17.114.0</td>
<td>Core</td>
</tr>

<tr>
<td>UI</td>
<td>Context help has been added to various tabs such as <b>Dashboard</b> and <b>Subassets</b>.</td>
<td>MTM-51868</td>
<td>10.17.171.0</td>
<td>UI</td>
</tr>

<tr>
<td>Web SDK</td>
<td>When updating blueprints via the UI users now get a notification instead of Cumulocity IoT silently updating in the background.</td>

<td>MTM-50636</td>
<td>10.17.257.0</td>
<td>UI</td>
</tr>


<tr>
<td>Web SDK</td>
<td>It is now possible to remove a file when updating its file property within a complex property of an asset.</td>
<td>MTM-51514</td>
<td>10.18.0.25</td>
<td>UI</td>
</tr>

<tr>
<td>Web SDK</td>
<td>The application switcher is now updated whenever changes to applications have been made within the same browser tab. This covers, for example, the creation of new applications, updates of existing applications or the deletion of applications. Other browser tabs still require a reload to refresh the applications.</td>
<td>MTM-52060</td>
<td>10.17.233.0</td>
<td>UI</td>
</tr>

<tr>
<td>Web SDK</td>
<td>The <code>@ngx-formly/core</code> dependency of <code>@c8y/ngx-components</code> has been upgraded to version 6.1.3.</td>
<td>DM-1996</td>
<td>10.17.223.0</td>
<td>UI</td>
</tr>

<tr>
<td>Web SDK</td>
<td>The <b>Files repository</b> page has been migrated from AngularJS to Angular. It now uses the new data grid with configurable columns which can be filtered or sorted. Moreover, you can now select multiple files for upload. The file search via the search input field is performed on the server side and searches through the entire available data set.</td>
<td>MTM-51333</td>
<td>10.17.216.0</td>
<td>UI</td>
</tr>

<tr>
<td>Web SDK</td>
<td>The <code>DatapointSelectorModule</code> can now be used in a module federation plugin.</td>
<td>MTM-52251</td>
<td>10.17.215.0</td>
<td>UI</td>
</tr>

<tr>
<td>Web SDK</td>
<td>Added examples for developers on how to bundle images correctly into a plugin. These examples are shown when you scaffold a new widget-plugin application with the c8ycli tool.</td>
<td>MTM-50721</td>
<td>10.17.205.0</td>
<td>UI</td>
</tr>

<tr>
<td>Web SDK</td>
<td>A real-time indicator has been added to the "Data point table" widget.</td>
<td>MTM-51537</td>
<td>10.17.190.0</td>
<td>UI</td>
</tr>

<tr>
<td>Web SDK</td>
<td>The Web SDK is now versioned independently from the backend.</td>
<td>MTM-50809</td>
<td>10.17.106.0</td>
<td>UI</td>
</tr>

<tr>
<td>Web SDK</td>
<td>It is now possible to open a blueprint directly after the installation has finished.</td>
<td>MTM-50637</td>
<td>10.17.47.0</td>
<td>UI</td>
</tr>

<tr>
<td>Web SDK</td>
<td>The <code>HOOK_COMPONENTS</code> now allows to lazily load the components used, for example, within widgets by utilizing the <code>loadComponent</code> and <code>loadConfigComponent</code> attributes of the <code>DynamicComponentDefinition</code> type (see <a href="https://resources.cumulocity.com/documentation/websdk/1016.0.110/ngx-components/interfaces/LazyDynamicComponents.html" class="no-ajaxy">https://resources.cumulocity.com/documentation/websdk/1016.0.110/ngx-components/interfaces/LazyDynamicComponents.html</a>).</td>
<td>MTM-51161</td>
<td>10.17.27.0</td>
<td>UI</td>
</tr>


</tbody></table>


### Fixes

<table>
<colgroup>
<col style="width: 15%;">
<col style="width:50%;">
<col style="width: 10%;">
<col style="width: 12%;">
<col style="width: 13%;">
</colgroup>
<thead><tr>
<th>
Product area</th>
<th>
Description</th>
<th>
Issue</th>
<th>
Build version</th>
<th>Build comp.</th>
</tr>
</thead><tbody>

<tr>
<td>Cockpit</td>
<td>The latest events are now correctly displayed in the data point graph, even if a custom interval has been selected.</td>
<td>MTM-52175</td>
<td>10.18.0.40</td>
<td>UI</td>
</tr>

<tr>
<td>Cockpit</td>
<td>The table used for the SCADA widget configuration has been replaced by a list group, allowing better visualization of data and actions.</td>
<td>MTM-51932</td>
<td>10.18.0.31</td>
<td>UI</td>
</tr>

<tr>
<td>Cockpit</td>
<td>In the datapoint library, it is now possible to pick fragment and series from an existing datapoint.</td>
<td>MTM-52704</td>
<td>10.18.0.30</td>
<td>UI</td>
</tr>

<tr>
<td>Cockpit</td>
<td>The asset property of type Boolean now shows "false" instead of "Undefined" when it's value is "false".</td>
<td>MTM-51513</td>
<td>10.18.0.24</td>
<td>UI</td>
</tr>

<tr>
<td>Cockpit</td>
<td>Improved the localization of the dialog window titles for adding and editing dashboards and reports.</td>
<td>MTM-51106</td>
<td>10.18.0.22</td>
<td>UI</td>
</tr>

<tr>
<td>Cockpit</td>
<td>The <b>Properties</b> tab is no longer shown when the associated asset model has no properties.</td>
<td>MTM-52015</td>
<td>10.17.270.0</td>
<td>UI</td>
</tr>

<tr>
<td>Cockpit</td>
<td>Fixed a localization issue in the tooltip of the <b>Load More</b> button in the custom Cockpit application configuration.</td>
<td>MTM-52177</td>
<td>10.17.262.0</td>
<td>UI</td>
</tr>

<tr>
<td>Cockpit</td>
<td>The <b>Properties</b> section is now displayed correctly for newly created assets.</td>
<td>MTM-50725</td>
<td>10.17.247.0</td>
<td>UI</td>
</tr>

<tr>
<td>Cockpit</td>
<td>The datapoint library now correctly parses older datapoint library entries, which stored numeric values as strings instead of numbers in the JSON object.</td>
<td>MTM-51785</td>
<td>10.17.121.0</td>
</tr>

<tr>
<td>Cockpit</td>
<td>An issue has been fixed that caused AngularJS widgets to not show up in the "Add widget" dialog.</td>
<td>MTM-51482</td>
<td>10.17.67.0</td>
<td>UI</td>
</tr>

<tr>
<td>DTM</td>
<td>If the DTM asset custom property is declared as required and complex, all of its subproperties are required too.</td>
<td>MTM-50101</td>
<td>10.17.12.0</td>
<td>UI</td>
</tr>

<tr>
<td>Java SDK</td>
<td>The dependency on <code>com.jayway.jsonpath:json-path</code> has been removed from the Java SDK.</td>

<td>MTM-53341</td>
<td>10.18.0.59</td>
<td>Core</td>
</tr>

<tr>
<td>Java SDK</td>
<td>The dependency on <code>org.json:json</code> has been removed from the Java SDK.</td>

<td>MTM-53340</td>
<td>10.18.0.55</td>
<td>Core</td>
</tr>

<tr>
<td>Microservice SDK</td>
<td>The Spring Boot dependency has been updated to version 2.7.11.</td>
<td>MTM-53342</td>
<td>10.18.0.54</td>
<td>Core</td>
</tr>

<tr>
<td>Microservice SDK</td>
<td>Dependencies on <code>org.eclipse.jetty:jetty-*</code> were updated to version 9.4.51.v20230217.</td>
<td>MTM-53359</td>
<td>10.18.0.55</td>
<td>Core</td>
</tr>

<tr>
<td>Web SDK</td>
<td>The optional links of a package shown in the packages details now point to the right location.</td>
<td>MTM-52691</td>
<td>10.18.0.7</td>
<td>UI</td>
</tr>

<tr>
<td>Web SDK</td>
<td>An issue with the "Copy dashboard" functionality has been addressed. The device context of a configured widget is now again replaced by the context it has been pasted to. This applies, for example, to the selected asset or to datapoints.</td>
<td>MTM-52374</td>
<td>10.17.259.0</td>
<td>UI</td>
</tr>

<tr>
<td>Web SDK</td>
<td>Datapoints no longer contain irrelevant data from the template after the link to the template has been removed. The datapoint now only contains the data from the template which is relevant for the current context.</td>
<td>MTM-51682</td>
<td>10.17.257.0</td>
<td>UI</td>
</tr>

<tr>
<td>Web SDK</td>
<td>The <code>HOOK_</code> prefixed injection tokens have been marked as deprecated. Details on their replacement are provided in their deprecation notice.</td>
<td>MTM-52376</td>
<td>10.17.259.0</td>
<td>UI</td>
</tr>

<tr>
<td>Web SDK</td>
<td>The HOOK_WIZARD can now be used in a module federation plugin.</td>
<td>MTM-51776</td>
<td>10.17.154.0</td>
<td>UI</td>
</tr>

<tr>
<td>Web SDK</td>
<td>Opening the widget configuration for a micro frontend plugin multiple times does no longer cause performance issues in the UI.</td>
<td>MTM-50306</td>
<td>10.17.53.0</td>
<td>UI</td>
</tr>

<tr>
<td>Web SDK</td>
<td>A toggle has been added to the plugin installation dialog, which allows to filter the plugin versions for only the latest versions or all versions.</td>
<td>MTM-50901</td>
<td>10.17.3.0</td>
<td>UI</td>
</tr>

<tr>
<td>UI</td>
<td>Corrected Japanese localizations in the <b>App configuration</b> page and in the <b>Add smart rules</b> dialog.</td>
<td>MTM-52050</td>
<td>10.17.272.0</td>
<td>UI</td>
</tr>

<tr>
<td>UI</td>
<td>The German localization in the "Connect smartphone" wizard has been corrected.</td>
<td>MTM-51935</td>
<td>10.17.207.0</td>
<td>UI</td>
</tr>

<tr>
<td>UI</td>
<td>Fixed a branding issue where the background color and the primary label were not using the brand color.</td>
<td>MTM-50807</td>
<td>10.17.86.0</td>
<td>UI</td>
</tr>

</tbody></table>
