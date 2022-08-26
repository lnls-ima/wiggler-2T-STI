by Ximenes Resende @ LNLS - 21/02/05

Cálculo do perfil de potência irradiada desprezando-se
a emitância finita do feixe no anel. Além desta aproxima-
ção, o cálculo considera toda a radiação concentrada no
plano da órbita e usa uma distribuição gaussiana com abertura
angular 1/gama para o cone de radiação instantânea. 

Para efeito de cálculo de aceleração instantânea, a órbita
do feixe é integrada a partir do curva de campo magnético. Não
há aproximações nas equações de movimento além da aproximação de
campo uniforme (sem roll-off) e dos erros de integração numérica, cujo
passo de integração é o mesmo da curva de campo disponível.  

ALém da potência total irradiada, o programa levanta perfis de 
densidade linear de potência para várias distâncias de observação.


PARÂMETROS DO PROGRAMA:

1. energia do feixe [GeV]
2. posx_init [cm]  : posição horizontal inicial do feixe
3. posxl_init [cm] : ângulo horizontal inicial do feixe
4. corrente [mA] fo feixe
5. nr_points : número de perfis a serem calculados em diversas distâncias
6. lista com parâmetros do perfis, seguindo a sintaxe (4 colunas):
	DISTÂNCIA AO FIM DO WIGGLER[m]	
	POSIÇÃO HORIZ. INICIAL DA JANELA DE OBSERVAÇÃO [mm]
	POSIÇÃO HORIZ. FINAL   "  "      "  "          "
	NÚMERO DE PLONTOS PARA A CURVA DO PERFIL