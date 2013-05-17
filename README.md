fgl-visualize
=============

FGL To Dot is an automatic translation and labeling of FGL graphs to graphviz Dot format
that can be written out to a file and displayed.

    let dot = showDot (fglToDot graph)
    writeFile "file.dot" dot
    system("dot -Tpng -ofile.png file.dot")
