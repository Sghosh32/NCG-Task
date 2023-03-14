# NCG-Task
### Ideation:- 
1. Extract the sentences from "**research_problem.json**" and "**Stanza-out.txt**" files.
2. Create sentences embeddings of the sentences in "**research_problem.json**" and "**Stanza-out.txt**" through a custom dataloader.
3. Pass these sentence embeddings through a transformer model, which will process these sentence embeddings.
4. Pass these sentence encodings to a DNN layer, which will identify which of the sentences are research problems and which are not.
5. After identifying the research problem sentences, finding the sentence numbers in the "**Stanza-out.txt**" file which correspond to the respective research problem statements.
6. Using a dependency parser to extract the research problem form the identified research problem statements in step 4.
7. Creating a triplet of the form <contribution | has research problem | "research problem" > from the extracted research problem phrases.
