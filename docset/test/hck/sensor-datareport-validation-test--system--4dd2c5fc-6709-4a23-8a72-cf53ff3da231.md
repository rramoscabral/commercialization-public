---
author: joshbax-msft
title: Sensor DataReport Validation Test (System)
description: Sensor DataReport Validation Test (System)
MSHAttr:
- 'PreferredSiteName:MSDN'
- 'PreferredLib:/library/windows/hardware'
ms.assetid: 3882aaf8-7566-43e6-9b69-40589ad07314
---

# Sensor DataReport Validation Test (System)


The data report of each sensor device is expected to have specific data fields and each data field must be a specific vartype. The test prompts the tester to put the sensor device into ready state and the data report is examined to validate the presence of the required data fields and correct vartypes.

This is a system-specific implementation of an existing test. For more information on this test, see [Sensor DataReport Validation Test](sensor-datareport-validation-test-ea6de06c-ec46-48f4-ada1-c80a1ca42b2c.md).

## Test details


<table>
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<tbody>
<tr class="odd">
<td><p><strong>Associated requirements</strong></p></td>
<td><p>System.Client.Sensor.Integrated</p>
<p>[See the system hardware requirements.](http://go.microsoft.com/fwlink/p/?linkid=254482)</p></td>
</tr>
<tr class="even">
<td><p><strong>Platforms</strong></p></td>
<td><p>Windows RT (ARM-based) Windows 8 (x64) Windows 8 (x86)</p></td>
</tr>
<tr class="odd">
<td><p><strong>Expected run time</strong></p></td>
<td><p>~2 minutes</p></td>
</tr>
<tr class="even">
<td><p><strong>Categories</strong></p></td>
<td><p>Certification Functional</p></td>
</tr>
<tr class="odd">
<td><p><strong>Type</strong></p></td>
<td><p>Manual</p></td>
</tr>
</tbody>
</table>

 

## Running the test


Before you run the test, complete the test setup as described in the test requirements: [System Client Testing Prerequisites](system-client-testing-prerequisites.md).

If a GPS sensor exists in the system, perform the following steps:

1.  Confirm that you are running the tests in an environment in which you can receive a GPS signal.

2.  Make sure that you have enabled the **Location Permissions** on the target system and for the system user account under which the WHCK tests are being executed.

## Troubleshooting


For troubleshooting information, see [Troubleshooting System Client Testing](troubleshooting-system-client-testing.md).

 

 





