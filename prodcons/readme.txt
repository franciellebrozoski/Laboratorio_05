Acredito que a implementação contém erro, pois procurei na documentação do RTOS 
em: https://www.keil.com/pack/doc/cmsis/RTOS2/html/structosRtxConfig__t.html
mas não encontrei como implementar uma IRQ sem utilizar thread como já estava implementada no 
exercício.

Usei como base o exemplo simple_io_main_sp.c porém não consegui implementar a rotina de 
interrupção como está no exemplo com SysTick_Handler.

Além desses adendos, a rotina para considerar apenas os 4 bits menos significativos
do número acumulado count, supondo que altere-se o buffersize para 32 bits não foi implementada
pois os testes não foram assertivos.
Tentei implementar uma operação lógica para zerar os bits mais significativos e deixar
apenas os 4 menos, porém não consegui, o resultado gerou um count sempre igual a 1.

Sem mais.

Francielle 22/07/21  23:46.