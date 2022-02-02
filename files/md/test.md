&&&thm
補題
&&&math
\int _{0}^{\infty }\frac {\ln (1+x^{2})}{a^2+x^{2}}dx
=\frac {\pi \ln (1+a)}a\quad\quad a>0
&&&
&&&

&&&prf
&&&math
\begin {aligned}
\int _{0}^{\infty }\frac {\ln (1+x^{2})}{a^2+x^{2}}dx
&=\int _{0}^{\infty }\int _{0}^{1}\frac {2tx^2}{(a^{2}+x^{2})(1+t^{2}x^{2})}dtdx\\
&=\int _{0}^{1}\frac {2t}{a^{2}t^{2}-1}\int _{0}^{\infty }\left (\frac {a^2}{a^{2}+x^{2}}-\frac {1}{1+t^{2}x^{2}}\right )dxdt\\
&=\int _{0}^{1}\frac {2t}{a^{2}t^{2}-1}\cdot \frac {\pi }2\left (a-\frac {1}t\right )dt\\
&=\pi \int _{0}^{1}\frac {1}{1+at}dt\\
&=\frac {\pi \ln (1+a)}a
\end {aligned}
&&&
&&&
