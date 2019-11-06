---
category: Stuff
path: '/stuff'
title: 'Post a thing'
type: 'POST'

layout: nil
---

This method allows users to create a new thing.

### Request

* The headers must include a **valid authentication token**.
* **The body can't be empty** and must include at least the name attribute, a `string` that will be used as the name of the thing.

### Response

**If succeeds**, returns the created thing.

For errors responses, see the [response status codes documentation](#response-status-codes).

### Public Member Functions 
----
<table>
    <tr> 
        <td> virtual </td>
        <td> 
            ~PPM_Synthesizer() <br> 
            Destructor 
        </td>
    </tr>
    <tr> 
        <td> void </td>
        <td> 
            init()
            <br> Initialize or reset sounds 
        </td>
    </tr>
    <tr> 
        <td> void </td>
        <td> 
            loadInstruments()
            <br> Load specific instruments
        </td>
    </tr>
    <tr> 
        <td> void </td>
        <td> 
            loadInstruments()
            <br> Modify current pattern based on initSegmentPos, segmentPos and pitches
        </td>
    </tr>
    <tr> 
        <td> void </td>
        <td> 
            threadModify()
            <br> Wrapper for function modify() running in back-thread
        </td>
    </tr>
    <tr> 
        <td> StringArray </td>
        <td> 
            getSampleFileName()
            <br> Return currently selected sample file names
        </td>
    </tr>
    <tr> 
        <td> XmlElement* </td>
        <td> 
            getMetaData()
            <br> Return metadata of current pattern
        </td>
    </tr>
    <tr> 
        <td> int* </td>
        <td> 
            getSelectedFiles()
            <br> Return selected pattern files in GUI
        </td>
    </tr>
    <tr> 
        <td> int </td>
        <td> 
            getCurrentNote()
            <br> Return currently or recently played note
        </td>
    </tr>
    <tr> 
        <td> int </td>
        <td> 
            getCurrentNote()
            <br> Return currently or recently played note
        </td>
    </tr>
</table>
