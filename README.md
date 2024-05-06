# Portfolio LaTeX
Bienvenido sea lector a mi portfolio de LaTeX. A continuación, encontrará un breve recorrido través de mi experiencia produciendo documentos formateados utilizando LaTeX.

## Plantilla para notas y apuntes de clase
En esta sección encontrará mi propuesta a una plantilla, sencilla pero de utilidad, para la redacción de notas de clase en asignaturas con volúmen de carga físico-matemática. 

En primer lugar,  elección de una fuente. Aunque a decir verdad esta es una decisión estríctamente personal, y que el usuario debiera conciliar con su <i>yo</i> más interior, arrojaré un par de comentarios sobre mi propia elección, que en este caso se trata de una configuración para la gran <a href="https://www.ibm.com/plex/"><i>IBM plex sans</i></a>, inspirada en la <a href="https://tex.stackexchange.com/questions/458588/looking-for-math-font-to-match-ibm-plex-serif-sans">contribución de <i>tecosaur</i> en <i>StackOverflow</i></a>.

```TeX
% FONT CONFIGURATION
%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%
\usepackage{fourier}
\usepackage{plex-serif}
\usepackage[basic,italic,symbolgreek]{mathastext}
\usepackage[sfdefault]{plex-sans}

\makeatletter
\@for\@tempa:=a,b,c,d,e,h,i,k,l,m,n,o,q,r,s,t,u,v,w,x\do{%
\MTsetmathskips{\@tempa}{0.5mu}{0.5mu}}%
\makeatother

\MTsetmathskips{f}{2.5mu}{0.5mu}
\MTsetmathskips{g}{1.5mu}{0.5mu}
\MTsetmathskips{j}{2.5mu}{0.5mu}
\MTsetmathskips{p}{1.5mu}{0mu}
\MTsetmathskips{y}{1.5mu}{0.5mu}
\MTsetmathskips{z}{1mu}{0.5mu}
```

## Formato de documentos ajedrecísticos
