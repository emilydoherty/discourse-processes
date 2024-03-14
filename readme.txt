Readme 2/1/24

Clean_Transcripts.ipynb = cleans the transcripts, removes [inaudible], etc. Combines adjoining utterances by the same speaker and adjusts timestamps accordingly. Computes utterance counts per speaker. 

Embed.ipnyb = embeds the transcripts using USE and SBERT. Computes inter utterance and 3-window coherence and add these values to the round excel sheet. 

Survey_Clean.ipynb = cleans the long survey xlsx file. Drops info from other rounds. Computes averages per SessionID and individual. Performs t-tests to see effect of group size and task on other subjective measures. 

