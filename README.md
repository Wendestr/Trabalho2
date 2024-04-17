# Trabalho2
**Estimativa de máxima verossimilhança**
 Para os parâmetro do modelo, adaptamos um algoritmo proposto por Anderson(1973). A log-verossimilhança para o modelo espacial linear t-Student é dado por 
 
 $L(\theta)=log(K_{n}(\eta))-\frac{1}{2}log|\Sigma|-\frac{1}{2\eta}(1+{n}\eta)log(1+c(\eta)\delta)$,    (4.4)

 com $log(K{n}(\eta))=\frac{n}{2}log (\frac{c(\eta)}{\pi})+log\Gamma(\frac{1+n\eta}{2\eta}) -log\Gamma(\frac{1}{2\eta}),\delta =(\boldsymbol{Y}-\boldsymbol{X\beta})^{T}\sigma^{-1}(\boldsymbol{Y}-\boldsymbol{X}\beta) e c(\eta)=\eta/(1-2\eta),0<\eta<\frac{1}{2}. Conform observado por Zellner (1976), a função log-verossimilhança. Veja também De Bastiani et al.$
   As funções escores para o modelo espacial linear t-Student são fornecidas por $U\phi(\theta)=(U\beta^T,U\phi^T)^T$, em que 
   

  $U_{\beta}=\partial{L}(\theta)/\partial\beta=w(\delta)\boldsymbol{X}^T \boldsymbol{\Sigma}^{-1}{\epsilon}$  and  $U_\phi=\partial{L}(\theta)/\partial\phi$

  com o j-ésimo elemento de $U_{\phi}$, dado por 

$U_{{\phi}_{j}}$ $=\partial L(\theta)\partial\phi_j=-\frac{1}{2}tr(\Sigma)^-1(\partial \Sigma/\partial\phi_j))+\frac{1}{2}w(\delta)\epsilon^T\Sigma^-1(\partial \Sigma/\partial\phi_j)\Sigma^-1\epsilon,$ para $j=1,2, w(\delta)=(\frac{1+\eta n}{\eta})(\frac{c(\eta)}{1+c(\eta)\delta})$ e $\psi(x)$ é a função Digama. Nesse artigo, $\Sigma=\phi_1I_n+\phi_2R$, então $\partial \Sigma/\partial_1=I_n$ e $\partial \Sigma/\partial\phi_2=R$. Dado $\Sigma$, a função log-verossimilhança (4.4) é maximizada em

$\hat{ \beta} =(\boldsymbol{X}^T{\Sigma}^{-1} {X})^{-1}\boldsymbol{X}^T \boldsymbol{\Sigma}^{-1}\boldsymbol{Y}$

e de$U_{\phi}=0$tem-se que, 

i $\phi$
