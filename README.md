**Python Developer Internship - ERP Analysis Task** 🚀
======================================================

**Objective**
-------------

This task evaluates your ability to process EEG data, extract event-related potentials (ERPs), and visualize the results using Python and MNE-Python.

**Dataset**
-----------

You are provided with an **EDF file** named John\_Brain\_Data.edf, which contains EEG recordings with event markers for two stimulus types:

*   **Common Stimuli**
    
*   **Uncommon Stimuli**
    

**Your Task**
-------------

1.  **Load the EEG Data**
    
    *   Use MNE-Python to read John\_Brain\_Data.edf.
        
2.  **Preprocess the EEG Data**
    
    *   Apply a **bandpass filter** (e.g., 1–40 Hz).
        
    *   Remove artifacts if necessary (e.g., using **ICA or epoch rejection**).
        
3.  **Extract Event-Related Potentials (ERPs)**
    
    *   Identify event markers for **Common** and **Uncommon** stimuli.
        
    *   Segment the data into epochs around stimulus onset.
        
    *   Compute and plot **ERP waveforms** (averaged over trials) for at least **3 electrodes of your choice**.
        
4.  **Bonus Task (Optional)**
    
    *   Compute the **grand average ERP** across all trials for each condition.
        
    *   Highlight key ERP components like **P300** or **N200**, if visible.
        
    *   Perform a **statistical comparison** between Common and Uncommon ERPs (e.g., using a t-test).
        

**Submission Instructions**
---------------------------

*   Complete the task using **Google Colab**.
    
*   Share the **Colab Notebook link** with **mubin@algosoftbd.com**.
    
*   Use the **email subject**:**"Python Developer Internship - ERP Analysis Submission - \[Your Name\]"**
    

**Hints & Resources**
---------------------

*   MNE-Python documentation: https://mne.tools/stable/index.html
    
