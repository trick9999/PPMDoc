---
title: 'Public Member Functions'

layout: nil
---

### Public Member Functions 
---
<style>
    table {
        width: 100%;
    }
    tr {
        border-bottom: 1px solid black;
    }
    .type td {
        width: 20%;
        text-align: right
        vertical-align: top
    }
    .func td {
        width: 80%;
        text-align: left
        vertical-align: top
    }
</style>

<table>
    <tr> 
        <td class="type"> virtual </td>
        <td class="func"> 
            ~PPM_Synthesizer() 
            <br> Destructor 
        </td>
    </tr>
    <tr> 
        <td class="type"> void </td>
        <td class="func"> 
            init()
            <br> Initialize or reset sounds 
        </td>
    </tr>
    <tr> 
        <td class="type"> void </td>
        <td class="func"> 
            loadInstruments()
            <br> Load specific instruments
        </td>
    </tr>
    <tr> 
        <td class="type"> void </td>
        <td class="func"> 
            loadInstruments()
            <br> Modify current pattern based on initSegmentPos, segmentPos and pitches
        </td>
    </tr>
    <tr> 
        <td class="type"> void </td>
        <td class="func"> 
            threadModify()
            <br> Wrapper for function modify() running in back-thread
        </td>
    </tr>
    <tr> 
        <td class="type"> StringArray </td>
        <td class="func"> 
            getSampleFileName()
            <br> Return currently selected sample file names
        </td>
    </tr>
    <tr> 
        <td class="type"> XmlElement* </td>
        <td class="func"> 
            getMetaData()
            <br> Return metadata of current pattern
        </td>
    </tr>
    <tr> 
        <td class="type"> int* </td>
        <td class="func"> 
            getSelectedFiles()
            <br> Return selected pattern files in GUI
        </td>
    </tr>
    <tr> 
        <td class="type"> int </td>
        <td class="func"> 
            getCurrentNote()
            <br> Return currently or recently played note
        </td>
    </tr>
    <tr> 
        <td class="type"> int </td>
        <td class="func"> 
            getCurrentNote()
            <br> Return currently or recently played note
        </td>
    </tr>
</table>
