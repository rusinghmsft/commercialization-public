---
author: joshbax-msft
title: ProjectManager Members
description: ProjectManager Members
MSHAttr:
- 'PreferredSiteName:MSDN'
- 'PreferredLib:/library/windows/hardware'
ms.assetid: 25d8163c-5a05-42da-bf3e-7ac7e5f99544
---

# ProjectManager Members


The following table lists the members exposed by the **ProjectManager** type.

## Public Properties


<table>
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<thead>
<tr class="header">
<th>Name</th>
<th>Description</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>ConnectionType</p></td>
<td><p>This property represents the connection type for this ILogoManager</p></td>
</tr>
<tr class="even">
<td><p>Version</p></td>
<td><p>This property represents the major version of the Windows HCK Controller.</p></td>
</tr>
<tr class="odd">
<td><p>VersionString</p></td>
<td><p>This property represents the version of the Windows HCK Controller and its content.</p></td>
</tr>
</tbody>
</table>

 

## Public Methods


<table>
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<thead>
<tr class="header">
<th>Name</th>
<th>Description</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>CreateDeviceFamily</p></td>
<td><p>This method creates a new device family with the given name.</p></td>
</tr>
<tr class="even">
<td><p>CreateProject</p></td>
<td><p>This method creates a new project.</p></td>
</tr>
<tr class="odd">
<td><p>DeleteDeviceFamily</p></td>
<td><p>This method deletes a device family by name.</p></td>
</tr>
<tr class="even">
<td><p>DeleteProject</p></td>
<td><p>This method deletes a project.</p></td>
</tr>
<tr class="odd">
<td><p>Dispose</p></td>
<td><p>Overloaded.</p></td>
</tr>
<tr class="even">
<td><p><strong>Equals</strong></p></td>
<td><p>(Inherited from <strong>Object</strong>)</p></td>
</tr>
<tr class="odd">
<td><p>GetDeviceFamilies</p></td>
<td><p>This method retrieves the list of available <strong>DeviceFamily</strong> objects.</p></td>
</tr>
<tr class="even">
<td><p>GetFeatures</p></td>
<td><p>This method retrieves the list of feature registered.</p></td>
</tr>
<tr class="odd">
<td><p>GetFilters</p></td>
<td><p>This method retrieves the list of filters that are available.</p></td>
</tr>
<tr class="even">
<td><p>GetHashCode</p></td>
<td><p>(Inherited from <strong>Object</strong>)</p></td>
</tr>
<tr class="odd">
<td><p>GetLocaleList</p></td>
<td><p>This method retrieves the list of possible test locales.</p></td>
</tr>
<tr class="even">
<td><p>GetPlatforms</p></td>
<td><p></p></td>
</tr>
<tr class="odd">
<td><p>GetProductTypes</p></td>
<td><p>This method retrieves the collection of registered product types.</p></td>
</tr>
<tr class="even">
<td><p>GetProject</p></td>
<td><p>This method retrieves a project and returns its object.</p></td>
</tr>
<tr class="odd">
<td><p>GetProjectInfoList</p></td>
<td><p>This method retrieves a list of <strong>ProjectInfo</strong> objects. This does not open each of the projects.</p></td>
</tr>
<tr class="even">
<td><p>GetProjectNames</p></td>
<td><p>This method retrieves a list of names of the projects.</p></td>
</tr>
<tr class="odd">
<td><p>GetProjectSummary</p></td>
<td><p></p></td>
</tr>
<tr class="even">
<td><p>GetRequirements</p></td>
<td><p>This method retrieves a list of requirements registered.</p></td>
</tr>
<tr class="odd">
<td><p>GetRootMachinePool</p></td>
<td><p>This method retrieves the root machine pool.</p></td>
</tr>
<tr class="even">
<td><p><strong>GetType</strong></p></td>
<td><p>(Inherited from <strong>Object</strong>)</p></td>
</tr>
<tr class="odd">
<td><p><strong>ToString</strong></p></td>
<td><p>(Inherited from <strong>Object</strong>)</p></td>
</tr>
</tbody>
</table>

 

## Protected Methods


<table>
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<thead>
<tr class="header">
<th>Name</th>
<th>Description</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Dispose</p></td>
<td><p>Overloaded.</p></td>
</tr>
<tr class="even">
<td><p>Finalize</p></td>
<td><p>Overridden.</p></td>
</tr>
<tr class="odd">
<td><p><strong>MemberwiseClone</strong></p></td>
<td><p>(Inherited from <strong>Object</strong>)</p></td>
</tr>
</tbody>
</table>

 

 

 

[Send comments about this topic to Microsoft](mailto:wsddocfb@microsoft.com?subject=Documentation%20feedback%20%5Bp_hck\p_hck%5D:%20ProjectManager%20Members%20%20RELEASE:%20%284/27/2016%29&body=%0A%0APRIVACY%20STATEMENT%0A%0AWe%20use%20your%20feedback%20to%20improve%20the%20documentation.%20We%20don't%20use%20your%20email%20address%20for%20any%20other%20purpose,%20and%20we'll%20remove%20your%20email%20address%20from%20our%20system%20after%20the%20issue%20that%20you're%20reporting%20is%20fixed.%20While%20we're%20working%20to%20fix%20this%20issue,%20we%20might%20send%20you%20an%20email%20message%20to%20ask%20for%20more%20info.%20Later,%20we%20might%20also%20send%20you%20an%20email%20message%20to%20let%20you%20know%20that%20we've%20addressed%20your%20feedback.%0A%0AFor%20more%20info%20about%20Microsoft's%20privacy%20policy,%20see%20http://privacy.microsoft.com/default.aspx. "Send comments about this topic to Microsoft")



