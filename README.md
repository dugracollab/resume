Using Latex to create my personal resume. 

### Motivation

Based off of sb2nov/resume

https://github.com/jakegut/resume/tree/master
I created this template as managing a resume on Google Docs was hard and changing any formatting was too difficult since it had to be applied in multiple places.

Most currently available templates either focus on two columns, or are multiple pages long that didn't work well for career fairs or online applications.

### Inspiration
Based on 
 [sb2nov/resume](https://github.com/sb2nov/resume)
and 
 [jakegut/resume](https://github.com/jakegut/resume.git).

### Build using Docker
using windows cmd
```sh
docker build -t mi-latex-image 
set currentDir=%cd%
docker run --rm -v %currentDir%:/data -w /data mi-latex-image pdflatex nicolas_cejas_resume.tex
```

### Preview

![Resume Screenshot](/resume_preview.png)

### License

Format is MIT but all the data is owned by Sourabh Bajaj.
