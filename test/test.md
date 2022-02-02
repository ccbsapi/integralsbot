&&&thm
&&&math
\begin {aligned}
\int _{0}^{1}\cos (\pi x)\ln \frac {\Gamma \left (\frac {x}2\right )}{\Gamma \left (\frac {x+1}2\right )}dx
&=\frac{1}2
\end{aligned}
&&&
&&&

&&&prf
&&&math
\begin {aligned}
\int _{0}^{1}\cos (\pi x)\ln \frac {\Gamma \left (\frac {x}2\right )}{\Gamma \left (\frac {x+1}2\right )}dx
&=\int _{0}^{1}\cos (\pi x)\ln \frac {\Gamma \left (1-\frac {x}2\right )}{\Gamma \left (\frac {1-x}2\right )}dx\\
&=\frac {1}2\int _{0}^{1}\cos (\pi x)\ln \frac {\Gamma \left (\frac {x}2\right )\Gamma \left (1-\frac {x}2\right )}{\Gamma \left (\frac {1+x}2\right )\Gamma \left (\frac {1-x}2\right )}dx\\
&=\frac {1}2\int _{0}^{1}\cos (\pi x)\ln \frac {\sin \frac {\pi x}2}{\sin \frac {\pi -\pi x}2}dx\\
&=-\frac {1}2\int _{0}^{1}\cos (\pi x)\ln \tan \frac {\pi x}2dx\\
&=-\frac {1}\pi \int _{0}^{\frac {\pi }2}\cos (2x)\ln \tan xdx\\
&=-\frac {1}\pi \int _{0}^{\frac {\pi }2}\left (2\cos ^{2}x-1\right )\ln \tan xdx\\
&=-\frac {2}\pi \int _{0}^{\frac {\pi }2}\cos ^{2}x\ln \tan xdx\\
&=-\frac {2}\pi \int _{0}^{\infty }\frac {\ln x}{(1+x^{2})^{2}}dx\\
&=-\frac {1}\pi \Re \int _{-\infty }^{\infty }\frac {\log x}{(1+x^{2})^{2}}dx\\
&=-\frac {1}\pi \Re \left (2\pi i\underset{z=i}{\mathrm {Res}}\frac {\log z}{(1+z^{2})^2}\right )\\
&=2\Im \left (\left .\frac {d}{dz}\frac {\log z}{(z+i)^{2}}\right |_{z=i}\right )\\
&=2\Im\left (\frac {\pi }8+\frac {i}4\right )\\
&=\textcolor {blue}{\frac {1}2}.
\end {aligned}
&&&
&&&

<div class="dotted" title="別解">
&&&math
\begin {aligned}
\int _{0}^{1}\cos (\pi x)\ln \frac {\Gamma \left (\frac {x}2\right )}{\Gamma \left (\frac {x+1}2\right )}dx
&=\left [\frac {\sin \pi x}\pi \ln \frac {\Gamma \left (\frac {x}2\right )}{\Gamma \left (\frac {x+1}2\right )}\right ]-\frac {1}\pi \int _{0}^{1}\sin (\pi x)\cdot \frac {1}2\left (\psi ^{(0)}\left (\frac {x}2\right )-\psi ^{(0)}\left (\frac {1+x}2\right )\right )\\
&=-\frac {1}{2\pi}\int _{0}^{1} \sin (\pi x)\left (\lim _{n\to \infty }\left (\log n-\sum _{k=0}^{n}\frac {1}{\frac {x}2+k}-\log n+\sum _{k=0}^{n}\frac {1}{\frac {x+1}2+k}\right )\right )dx\\
&=\frac {1}\pi \int _{0}^{1}\sin (\pi x)\sum _{k=0}^{\infty }\left (\frac {1}{x+2k}-\frac {1}{x+2k+1}\right )dx\\
&=\frac {1}\pi \int _{0}^{1}\sin (\pi x)\sum _{k=0}^{\infty }\frac {(-1)^k}{x+k}dx\\
&=\frac {1}\pi \sum _{k=0}^{\infty }\int _{0}^{1}\frac {\sin (\pi x+\pi k)}{x+k}dx\\
&=\frac {1}\pi \sum _{k=0}^{\infty }\int _{k}^{k+1}\frac {\sin \pi x}xdx\\
&=\frac {1}\pi \int _{0}^{\infty }\frac {\sin \pi x}xdx\\
&=\frac {1}\pi \cdot \frac {\pi }2\\
&=\textcolor {blue}{\frac {1}2}.
\end {aligned}
&&&
</div>
