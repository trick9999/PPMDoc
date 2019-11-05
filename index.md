<style>
    td {
        vertical-align: top
    }
</style>

## PPM_Synth Class Reference
----
Synthesizer class for time-frequency modification and communication with GUI.

### Classes
----

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
