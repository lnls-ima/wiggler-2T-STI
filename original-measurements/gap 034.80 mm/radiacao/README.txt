by Ximenes Resende @ LNLS - 21/02/05

C�lculo do perfil de pot�ncia irradiada desprezando-se
a emit�ncia finita do feixe no anel. Al�m desta aproxima-
��o, o c�lculo considera toda a radia��o concentrada no
plano da �rbita e usa uma distribui��o gaussiana com abertura
angular 1/gama para o cone de radia��o instant�nea. 

Para efeito de c�lculo de acelera��o instant�nea, a �rbita
do feixe � integrada a partir do curva de campo magn�tico. N�o
h� aproxima��es nas equa��es de movimento al�m da aproxima��o de
campo uniforme (sem roll-off) e dos erros de integra��o num�rica, cujo
passo de integra��o � o mesmo da curva de campo dispon�vel.  

AL�m da pot�ncia total irradiada, o programa levanta perfis de 
densidade linear de pot�ncia para v�rias dist�ncias de observa��o.


PAR�METROS DO PROGRAMA:

1. energia do feixe [GeV]
2. posx_init [cm]  : posi��o horizontal inicial do feixe
3. posxl_init [cm] : �ngulo horizontal inicial do feixe
4. corrente [mA] fo feixe
5. nr_points : n�mero de perfis a serem calculados em diversas dist�ncias
6. lista com par�metros do perfis, seguindo a sintaxe (4 colunas):
	DIST�NCIA AO FIM DO WIGGLER[m]	
	POSI��O HORIZ. INICIAL DA JANELA DE OBSERVA��O [mm]
	POSI��O HORIZ. FINAL   "  "      "  "          "
	N�MERO DE PLONTOS PARA A CURVA DO PERFIL