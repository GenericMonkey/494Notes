# 494Notes
How to contribute:

1. If you are familiar with git, make sure to pull before editing. If you are not, make sure to download the latest zip before you begin working. 
2. Writing the notes:
    * The notes are structured in modular blocks. For any day you are writing notes for, make a new .tex file in which you start with   \section{Date}, and type as if this is just an excerpt of the main file.
    * Title these .tex files as Date_with_underscores.tex. Example: 1_4_17.tex
    * In the main 494notes.tex, add a line of the form \input{1_4_17.tex}
    * Every time you create a new Proposition, Corollary, Theorem, or Fact (or anything that can be cited later in the course), make sure to add a label for the result in the format \label{Type #, Mon Day} (Example: \label{Cor 5, Jan 30})
    * Every time you reference a result from class, in the same format from above, reference the result (\ref{Type #, Mon Day}). Provided this is done correctly, the document will automatically hyperlink all results.
    * That's it! You've successfully added the excerpt you typed into the master tex file
3. Adding the Notes back to Github:
    * If you are familiar with git, add just the new tex file, as well as the master and the pdf and push.
    * Otherwise, the directions are as follows:
        1. On the Github page, click "Upload Files"
        2. Select the newest section .tex, the 494notes.tex, and the 494notes.pdf that you just updated. 
        3. Under the "Commit Changes" section, make sure to add a message saying what date you just added notes for

The Schedule (This repeats until semester ends)
- Pranav (Wednesdays)
- Nick (Fridays)
- Ben (Mondays)
