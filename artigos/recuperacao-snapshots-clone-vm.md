# Recuperação de Snapshots e Clonação de VMs

> **Alerta de Segurança:** Todas as alterações, arquivos e atualizações realizadas serão permanentemente perdidos antes da snapshot.

## 1. Quando Aplicar (Sintoma)
Deve se aplicar um snapshot imediatamente quando uma alteração, atualização, configuração incorreta em homologação/produção, Teste de software, driver com erro ou teste crítico não seja concluída sucetivamente e o caminho mais rápido para estabilizar o sistema for pelo meio da caminho das snapshots, `Exemplo: Quando alguma atualização ou patch travar`.

## 2. Ferramentas/Componentes Necessários
* **Hardware / Físico:** Disco NVMe ou SSD, Capacidade de armazenamento extra CPU, Memória RAM, Placa de Rede
* **Software:** Clonezilla, Mozilla Firefox, VMware ou Virtual Oracle box

## 3. Passo a Passo Rápido
1. Verificação breve Com a snapshot pronta para ser instalada, avise os clientes que a máquina ficará indisponível temporariamente assim dando tempo para salvarem arquivos ou criarem backups;
2. Localizar a máquina virtual desejada na lista de Snapshots;
3. Identifique o snapshot correto verificando a data, hora e descrição da captura, Certificando-se de que não há alertas de corrupção na cadeia de discos ou falta de espaço antes de iniciar;
1. Selecione de uma forma que a máquina faça com que o download seja permitido para a quantidade de máquinas para baixar seja exatamente o número digitado no Multicast, assim criando uma forma de formatação cuja todas as máquinas-clientes terão um download seguro e prático;
1. Execução Clique na snapshot desejada e selecione a opção Revert to Snapshot, confirmando o aviso de segurança exibido na tela e aguardando a VM iniciar ou restaurar o estado de memória;
1. Depois disso faça o iniciamento das máquinas clientes realizando o download das snapshots virtuais assim realizando o download;
1. Testar o Sistema: Acesse a VM e verifique se as aplicações voltaram a funcionar corretamente, logo após deletando o snapshot utilizado para consolidar os discos e evitar perda de performance futura;
1. Por último se certifique de criar um backup depois da snapshot, protegendo seus dados e informações, evitando riscos futuros.