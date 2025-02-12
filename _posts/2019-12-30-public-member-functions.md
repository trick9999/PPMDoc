---
title: 'Public Member Functions'

layout: nil
---

### Public Member Functions 

<style>
    table {
        width: 100%;
    }
    tr {
        border-top: 1px solid black;
        border-bottom: 1px solid black;
    }
    table tr td:nth-child(1) {
        width: 20%;
        vertical-align: top;
    }
    table tr td:nth-child(2) {
        width: 80%;
        vertical-align: top;
    }
</style>

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
