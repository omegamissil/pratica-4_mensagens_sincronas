Troca de Mensagens Síncronas com MPI

Este repositório contém uma implementação em Python utilizando a biblioteca mpi4py e NumPy para demonstrar o funcionamento da comunicação síncrona bloqueante (Ssend() e Recv()) entre dois processos MPI. O script evidencia o handshake temporal exigido pelo envio síncrono, no qual o processo remetente (rank 0) permanece bloqueado até que o receptor (rank 1) conclua um atraso configurável e inicie a recepção correspondente, processando o dado recebido e devolvendo a resposta calculada.
