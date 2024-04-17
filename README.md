# Trabalho2
**Estimativa de máxima verossimilhança**
 Para os parâmetro do modelo, adaptamos um algoritmo proposto por Anderson(1973). A log-verossimilhança para o modelo espacial linear t-Student é dado por 
 
 $L(\theta)=log(K_{n}(\eta))-\frac{1}{2}log|\Sigma|-\frac{1}{2\eta}(1+{n}\eta)log(1+c(\eta)\delta)$,    (4.4)

 com $log(K{n}(\eta))=\frac{n}{2}log (\frac{c(\eta)}{\pi})+log\Gamma(\frac{1+n\eta}{2\eta}) -log\Gamma(\frac{1}{2\eta}),\delta =(\boldsymbol{Y}-\boldsymbol{X\beta})$
