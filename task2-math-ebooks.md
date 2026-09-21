# Task 2: Math ebooks in PDF format

W2-PM2, Google Hacking Database. The goal was to find 10 open directory listings that have downloadable mathematics PDFs, using Google dorks only.

The base dork I started with is the one from the guide:

```
intitle:index.of "parent directory" mathematics pdf
```

Then I swapped the last words (`calculus`, `algebra`, `lecture notes`, etc.) to get different results. All of these opened straight away without any login.

| No. | Link | Relevant Dork | Username / Password (if any) |
|-----|------|---------------|------------------------------|
| 1 | https://www.skylineuniversity.ac.ae/pdf/math/ | `intitle:index.of "parent directory" mathematics pdf` | --- |
| 2 | https://www.netlib.org/math/docpdf/ | `intitle:index.of "parent directory" mathematics pdf` | --- |
| 3 | https://carma.newcastle.edu.au/brailey/Lecture_Notes/ | `intitle:index.of "parent directory" mathematics pdf` | --- |
| 4 | https://education.giakonda.org.uk/Maths/ | `intitle:index.of "parent directory" mathematics pdf` | --- |
| 5 | https://www.jsoftware.com/books/pdf/ | `intitle:index.of "parent directory" calculus pdf` | --- |
| 6 | https://www.math.uci.edu/~remote_teaching/Lecture_Notes_of_Hamed/Math%202A%20Lecture%20Notes/ | `intitle:index.of "parent directory" algebra pdf lecture notes` | --- |
| 7 | https://www.math.ucla.edu/~popa/Books/ | `intitle:index.of "parent directory" algebra pdf lecture notes` | --- |
| 8 | https://www.hairer.org/notes/ | `intitle:index.of "parent directory" algebra pdf lecture notes` | --- |
| 9 | https://math.mit.edu/~fgotti/docs/Courses/ | `intitle:index.of "parent directory" algebra pdf` | --- |
| 10 | https://www.cs.cmu.edu/~hn1/documents/algebraic-geometry | `intitle:index.of "parent directory" algebra pdf` | --- |

## Notes on each one

1. **Skyline University College**: This is the example from the guide. It's a big folder, and Google's snippet alone showed more than 80 files.
2. **Netlib**: The PDFs are split up chapter by chapter (`ch01.pdf`, `ch02-01.pdf`, and so on), plus a few appendices.
3. **Newcastle (CARMA)**: Lecture notes on linear algebra, metric spaces, Hilbert spaces and probability, plus a sub-folder with topology notes.
4. **giakonda.org.uk /Maths/**: School-level material, including Additional Mathematics (Pure and Applied) and Mathematics 10-12. A few of the files are really big (`math7.pdf` is about 479 MB), so I didn't download anything from here.
5. **jsoftware.com**: `algebra.pdf`, `calculus.pdf` and `arithmetic.pdf`, along with some other books in the same folder.
6. **UC Irvine**: Math 2A lecture notes, one PDF per chapter section.
7. **UCLA (Popa)**: A short list of PDFs, including an analysis course and an algebra manual.
8. **Hairer's notes**: Lecture notes on stochastic analysis, rough paths and SPDEs.
9. **MIT (Gotti)**: Folders of course notes for Algebra 1, Ideal Theory, Math 1a/1b/53 and Combinatorial Analysis.
10. **CMU (hn1)**: The algebraic geometry notes as `geometry.pdf`, with the LaTeX source in the same folder.

I skipped a few directories that showed up in the results but looked like dumps of pirated textbooks. They'd match the dork, but they aren't something I want to link to.
