Módulo de Gestão Documental
===========================

O módulo de Gestão documental do SUPER.GOV.BR traz consigo uma série de funcionalidades que visam contribuir para a gestão arquivística dos processos possibilitando o arquivamento, o desarquivamento, o controle dos prazos de guarda, a avaliação, a devolução para correção de metadados e a geração de listagens de eliminação e recolhimento.

Essa seção tem por objetivo demonstrar as funcionalidades que serão disponibilizadas pelo módulo de Gestão Documental e também as configurações necessárias para o seu correto funcionamento.

O módulo de Gestão Documental traz incrementos ao Sistema SUPER.GOV.BR que podem ser acessados via entidades:

* **Botão Arquivar Processo** – Possibilita o arquivamento de processos.
* **Botão Desarquivar Processo** – possibilita que um processo arquivado seja desarquivado e retorne para a tela de controle de processos.
* **Menu Arquivo da Unidade** – concentra todos os processos da unidade que foram arquivados e se encontram em fase corrente.
* **Menu Pendências de Arquivamento** – concentra todos os processos cuja unidade foi a última a concluir e ainda não os arquivou.
* **Menu Gestão Documental** – possibilita a avaliação dos processos, a devolução para correção e a geração de listagens de eliminação e de recolhimento, conforme a destinação final associada a cada processo.

Abaixo são detalhadas cada uma dessas funcionalidades.

Arquivar Processo
-----------------

O botão “**Arquivar Processo**” será utilizado para indicar que o último ato processual foi realizado, ou seja, tal processo não terá mais movimentações e estará pronto para iniciar a contagem dos prazos de guarda.

Após o clique nesse botão indicado, será necessário preencher o formulário de arquivamento, incluindo a justificativa de arquivamento e inserindo a senha para autenticação da ação.

O botão “**Arquivar Processo**” está disponível na tela de Controle de Processos e na tela de Visualização de Processos, como pode ser visto abaixo:

Tela de Controle de processos
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
 
.. figure:: _static/images/conculsao_arquivament_tela_de_controle_processos.gif

Para arquivamento de processos, o usuário deverá selecionar o processo, via marcação de checkbox, e clicar no botão “**Arquivar Processo**”.


.. admonition:: Nota

   Será possível a seleção de mais de um processo para a realização do procedimento de arquivamento, contudo, todos os processos deverão ter a mesma justificativa de arquivamento.


Tela de Visualização do Processo
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

.. figure:: _static/images/conculsao_arquivament_tela_de_visualizacao_processos.gif

Após todas as tratativas do processo, o usuário poderá direcioná-lo para arquivamento por meio de click no botão “**Arquivar Processo**”.

Preenchimento do Formulário de Arquivamento de Processo
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

.. figure:: _static/images/conculsao_arquivament_fomulario_de_preenchimento.png

O formulário deverá ser preenchido conforme os campos indicados abaixo:

1. **Processo(s)**: campo preenchido automaticamente. Utilizado para indicar um ou mais processos que serão arquivados;
2. **Justificativa**: campo obrigatório. Utilizado para indicar a justificativa do arquivamento. Poderá ser selecionada apenas uma justificativa para arquivamento.
3. **Arquivamento Legado?**: Campo opcional. Funcionalidade utilizada para indicar uma data retroativa de arquivamento do processo. Tal funcionalidade pode ser utilizada para arquivamento de processos concluídos antes da implantação do módulo.

.. admonition:: Nota

  No arquivamento legado não é possível selecionar uma data de arquivamento anterior à data do último andamento do processo.

4. **Órgão do Assinante**: Campo obrigatório. Utilizado para indicação do órgão ao qual o usuário responsável pela ação está vinculado.
5. **Assinante**: Campo obrigatório. Utilizado para o registro do nome do usuário responsável pelo arquivamento.
6. **Cargo/Função**: Campo obrigatório. Utilizado para o registro do cargo/função do assinante.
7. **Senha**: Campo obrigatório. Utilizado para a inclusão da senha de autenticação da ação.

.. figure:: _static/images/conculsao_arquivament_fomulario_de_preenchimento.gif

Ao clicar em Assinar, o processo receberá uma sinalização indicando que está Arquivado. Além disso, o sistema irá gerar automaticamente um documento de arquivamento assinado eletronicamente pelo responsável pela ação e o incorporará ao processo.

.. figure:: _static/images/conculsao_arquivamento_tela_apos_procedimento_arquivamento.gif

A realização do arquivamento impede que novos documentos ou andamentos sejam associados ao processo, sendo possível apenas as seguintes ações:

- Iniciar Processo Relacionado
- Consultar Processo
- Acompanhamento Especial
- Adicionar aos Favoritos
- Anotações
- Gerar Arquivo PDF do Processo
- Gerar Arquivo ZIP do Processo
- Comentários
- Controle de Prazos
- Controle de Processos
- Pesquisar no Processo
- Consultar Histórico de Arquivamento do Processo
- Desarquivar Processo

Após o procedimento de arquivamento, o processo ficará disponível no menu “**Arquivo da Unidade**” até o cumprimento do prazo corrente. Depois passará a ser apresentado na tela de Avaliação de Processos da Unidade de Avaliação associada.

Desarquivar Processo
--------------------

O botão “Desarquivar Processo” será utilizado para o desarquivamento, retornando o processo para a tela de controle de processos.

Após o clique no botão indicado, será necessário preencher o formulário de desarquivamento do processo, incluindo a justificativa de desarquivamento e inserindo a senha para autenticação da ação.

Caso seja necessário, o desarquivamento de um processo poderá ser realizado por meio da tela de visualização do processo ou pelo menu “**Arquivo da Unidade**”.

Desarquivar via Visão do Processo
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

.. figure:: _static/images/desarquivamento_visao_processo.gif

Desarquivar via Menu Arquivo da Unidade
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

.. figure:: _static/images/desarquivamento_visao_menu_arquivo_unidade_individual.gif

Será possível a seleção de mais de um processo para desarquivamento, para tanto, o usuário deverá selecionar todos os processos desejados, via marcação de checkbox, e em seguida clicar no botão Desarquivar, existente na parte superior direita da tela. Poderá ser selecionada apenas uma justificativa para desarquivamento.

.. admonition:: Nota

   Para o desarquivamento em lote, todos os processos a serem desarquivados deverão ter a mesma justificativa de desarquivamento.


.. figure:: _static/images/desarquivamento_visao_menu_arquivo_unidade_lote.gif


Preenchimento do Formulário de Desarquivamento de Processo
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

.. figure:: _static/images/desarquivamento_formulario_preenchimento.png

O formulário deverá ser preenchido conforme os campos indicados abaixo:

1) **Processo(s)**: campo preenchido automaticamente. Utilizado para indicar um ou mais processos que serão desarquivados.
2) **Justificativa**: campo obrigatório. Utilizado para indicar a justificativa do desarquivamento. Poderá ser selecionada apenas uma justificativa para desarquivamento.
3) **Órgão do Assinante**: Campo obrigatório. Utilizado para indicação do órgão ao qual o usuário responsável pela ação está vinculado.
4) **Assinante**: Campo obrigatório. Utilizado para o registro do nome do usuário responsável pelo desarquivamento.
5) **Cargo/Função**: Campo obrigatório. Utilizado para o registro do cargo/função do responsável pelo desarquivamento.
6) **Senha**: Campo obrigatório. Utilizado para a inclusão da senha de autenticação da ação.

.. figure:: _static/images/desarquivamento_formulario_preenchimento.gif

Ao clicar em Assinar, o sistema irá gerar automaticamente um documento de desarquivamento assinado eletronicamente pelo responsável pela ação e o incorporará ao processo.

Menu Arquivo da Unidade
-----------------------

Tal menu concentra a lista de todos os processos que foram arquivados pela unidade e se encontram em fase corrente.

Pesquisar Processos Arquivados
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

A pesquisa de processos poderá ser realizada por meio do preenchimento dos campos de filtragem disponíveis em tela e, em seguida, clique no botão "**Pesquisar**".


Imprimir Relação de Processos
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

Será possível imprimir uma relação de processos conforme os filtros de pesquisa aplicados. 

Para realizar a Impressão (seja física ou em PDF), o usuário deverá selecionar os processos, via marcação de checkbox, e clicar em "**Imprimir**".
 
Desarquivar um ou mais processos
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

Os passos para o desarquivamento de processos poderão ser acessados por meio da seção Desarquivar de Processo, existente nesse documento.

Menu Pendências de Arquivamento
--------------------------------

No menu pendências de arquivamento ficam concentrados todos os processos cuja unidade foi a última a concluir e ainda não os arquivou.

Pesquisar Processos Concluídos
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

A pesquisa de processos poderá ser realizada por meio do preenchimento dos campos de filtragem disponíveis em tela e, em seguida, clique no botão "**Pesquisar**".

Reabrir Processo
~~~~~~~~~~~~~~~~

A reabertura consiste em retornar um processo ao status de aberto. Nesta visão, o usuário terá a possibilidade de reabrir um ou mais processos.

.. admonition:: Nota

   Só é possível reabrir processos que estejam apenas concluídos. Processos arquivados precisam ser desarquivados para voltarem a tramitar.


Para reabrir um único processo, o usuário deverá clicar no botão "**Reabrir Processo**", presente na grid do processo que deseja reabrir.

.. figure:: _static/images/pendencias_arquivamento_reabir_um_processo.gif

Após o clique no botão, o sistema apresentará uma mensagem de confirmação da reabertura. Para concluir a ação, o usuário deverá clicar em “**Ok**”.
 
Para reabrir mais de um processo, o usuário deverá selecionar todos os processos desejados, via marcação de checkbox, e em seguida clicar no botão "**Reabrir**", existente na parte superior direita da tela.

.. figure:: _static/images/pendencias_arquivamento_reabir_varios_processos.gif

Após o clique no botão, o sistema apresentará uma mensagem de confirmação da reabertura. Para concluir a ação, o usuário deverá clicar em “**Ok**”.


Arquivar Processo
~~~~~~~~~~~~~~~~~~


Nesta visão, o usuário terá a possibilidade de arquivar um ou mais processos.

Para arquivar um único processo, o usuário deverá clicar no botão "**Arquivar Processo**", presente na grid do processo que deseja arquivar.

.. figure:: _static/images/arquivo_unidade_arquivar_um_documento.gif

Após o clique no botão, o sistema abrirá o formulário de arquivamento para preenchimento e autenticação. Os passos para o preenchimento deste formulário poderão ser acessados na seção [Preenchimento do Formulário de Desarquivamento de Processo](#preenchimento-do-formulário-de-desarquivamento-de-processo).

Para arquivar mais de um processo, o usuário deverá selecionar todos os processos desejados, via marcação de checkbox, e em seguida clicar no botão "**Arquivar**", existente na parte superior direita da tela.

.. admonition:: Nota

   Para o arquivamento em lote, todos os processos a serem arquivados deverão ter a mesma justificativa de arquivamento.

.. figure:: _static/images/arquivo_unidade_arquivar_lote_documento.gif


Gestão Documental
-----------------

O menu Gestão documental poderá ser utilizado pelo usuário lotado na Unidade configurada como de Avaliação que possua o perfil equivalente.

Nesse menu ficarão disponíveis as seguintes opções:

* Avaliação de Processos
* Listagens de Eliminação
* Listagens de Recolhimento
* Relatórios
 
Avaliação de Processos
~~~~~~~~~~~~~~~~~~~~~~

Na opção Avaliação de Processos ficam concentrados todos os processos arquivados pelas respectivas unidades de arquivamento e que cumpriram o prazo de guarda corrente. Nesta visão, o usuário poderá avaliar se as informações relativas aos processos estão adequadas, poderá devolver para a unidade responsável pelo arquivamento realizar correções e poderá enviar para a etapa de preparação da listagem. 

Pesquisar Processos para Avaliação
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^


A pesquisa de processos poderá ser realizada por meio do preenchimento dos campos de filtragem disponíveis em tela e, em seguida, clique no botão "**Pesquisar**".
 
Preparação da Listagem de Eliminação
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

Para indicar que um único processo deve ser enviado para preparação da listagem de eliminação, o usuário deverá clicar no botão "**Preparar Listagem de Eliminação**", presente na grid do processo.

.. figure:: _static/images/avaliacao_de_processos_enviar_destinacao_um_registro.gif

Após o clique no botão, o sistema apresentará uma mensagem de confirmação. Para concluir a ação, o usuário deverá clicar em “**Ok**”.

Para indicar que mais de um processo deve ser enviado para preparação da listagem de eliminação, o usuário deverá selecionar todos os processos desejados, via marcação de checkbox, e em seguida clicar no botão “**Preparar Listagem de Eliminação**” existente na parte superior direita da tela.

.. admonition:: Nota
 
   Caso tenha sido selecionado algum processo cuja destinação final não seja Eliminação o módulo irá desconsiderá-lo.

.. figure:: _static/images/avaliacao_de_processos_enviar_destinacao_lote_registros.gif

Após o clique no botão, o sistema apresentará uma mensagem de confirmação. Para concluir a ação, o usuário deverá clicar em “**Ok**”.

Os processos enviados para preparação da listagem de eliminação passarão a ser listados no menu “Gestão Documental > Listagens de Eliminação > Preparação da Listagem”.

Preparação da Listagem de Recolhimento
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

Para indicar que um único processo deve ser enviado para preparação da listagem de recolhimento, o usuário deverá clicar no botão Preparar Listagem de Recolhimento, presente na grid do processo.

.. figure:: _static/images/avaliacao_de_processos_enviar_destinacao_um_registro.gif

Após o clique no botão, o sistema apresentará uma mensagem de confirmação. Para concluir a ação, o usuário deverá clicar em “**Ok**”.

Para indicar que mais de um processo deve ser enviado para preparação da listagem de recolhimento, o usuário deverá selecionar todos os processos desejados, via marcação de checkbox, e em seguida clicar no botão “**Preparar Listagem de Recolhimento**” existente na parte superior direita da tela.

.. admonition:: Nota

   Caso tenha sido selecionado algum processo cuja destinação final não seja Recolhimento o módulo irá desconsiderá-lo.

.. figure:: _static/images/avaliacao_de_processos_enviar_destinacao_lote_registros.gif

Após o clique no botão, o sistema apresentará uma mensagem de confirmação. Para concluir a ação, o usuário deverá clicar em “**Ok**”.

Os processos enviados para preparação da listagem de recolhimento passarão a ser listados no menu “Gestão Documental > Listagens de Recolhimento > Preparação da Listagem”.

Imprimir
^^^^^^^^^

Nessa visão será possível imprimir uma relação de processos conforme os filtros de pesquisa aplicados. 

Para realizar a Impressão (seja física ou em PDF), o usuário deverá selecionar os processos, via marcação de checkbox, e clicar em "**Imprimir**".

Devolver para Correção
^^^^^^^^^^^^^^^^^^^^^^

Caso o usuário identifique que alguma informação necessita ser corrigida, deverá clicar no botão "**Devolver para Correção**", presente na grid do processo.

.. figure:: _static/images/avaliacao_de_processos_enviar_correcao_um_registro.gif

Ao clicar nesse botão, será aberta uma janela para inserção da mensagem de devolução do processo. Após o término do texto, clicar em "**Devolver**".

.. figure:: _static/images/avaliacao_de_processos_enviar_correcao_justificativa.gif
 
O processo devolvido para correção ficará disponível no Arquivo da Unidade que realizou o arquivamento. Tal processo terá a indicação de que foi devolvido para correção, acompanhado do motivo.

.. figure:: _static/images/tela_arquivo_da_unidade_icone_correcao2.gif

.. figure:: _static/images/icone_motivo_correção_detalhado.png

Para realizar a correção o usuário deverá clicar no ícone "**Consultar/Alterar Processo**" (1), disponível na grid do processo. Após a correção, o usuário deverá clicar no ícone "**Concluir Edição**" (2), disponível na grid do processo.

.. figure:: _static/images/avaliacao_de_processos_icone_correcao.gif

.. admonition:: Nota

   Ao confirmar a conclusão da Edição os prazos de guarda serão recalculados. Caso ainda esteja pendente o cumprimento de prazo corrente, o processo continuará no Arquivo da Unidade. Caso o processo já tenha cumprido o prazo de guarda corrente, será retornado para a tela de Avaliação de Processos da unidade responsável pela avaliação.

Listagem de Eliminação
~~~~~~~~~~~~~~~~~~~~~~

Nesta opção, o usuário irá criar as listagens de processos elegíveis para eliminação para posterior submissão à CPAD (Comissão Permanente de Avalição de Documentos)

.. admonition:: Nota
 
   A submissão à CPAD não é um procedimento controlado pelo Módulo.

Preparar Listagem de Eliminação
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

Pesquisar Processos para Eliminação
"""""""""""""""""""""""""""""""""""""""""""

A pesquisa poderá ser realizada por meio do preenchimento dos campos de filtragem disponíveis em tela e, em seguida, clique no botão "**Pesquisar**".

Gerar Listagem de Eliminação
"""""""""""""""""""""""""""""

Para gerar uma listagem de eliminação, o usuário deverá selecionar os processos que deseja que componham a listagem e clicar em "**Gerar Listagem de Eliminação**".

.. figure:: _static/images/listagem_eliminacao_gerar_listagem.gif

Ao gerar uma listagem, o sistema criará um processo na tela de controle de processos para guardar a listagem criada, que ficará disponível na visão “**Gestão das Listagens**”, ligada à Listagens de Eliminação, existente no menu Gestão Documental.

Excluir da Preparação para Eliminação
""""""""""""""""""""""""""""""""""""""

Nessa visão, o usuário terá a possibilidade de excluir um ou mais processos da preparação da Listagem de Eliminação.

Para excluir um único processo, o usuário deverá clicar no botão Excluir, presente na grid do processo.

.. figure:: _static/images/listagem_eliminacao_exclusao_uma_lista.png

Para excluir mais de um processo, o usuário deverá selecionar todos os processos desejados, via marcação de checkbox, e em seguida clicar no botão "**Excluir**", existente na parte superior direita da tela.

.. figure:: _static/images/listagem_eliminacao_exclusao_varias_listas.gif

Após a confirmação da exclusão, os processos ficarão disponíveis na tela de Avaliação de Processos, do menu "**Gestão Documental**".

Imprimir
"""""""""

Nesta visão será possível imprimir uma relação de processos conforme os filtros de pesquisa aplicados. 

Para realizar a Impressão (seja física ou em PDF), o usuário deverá selecionar os processos, via marcação de checkbox, e clicar em "**Imprimir**".

Adicionar observação e/ou justificativa
""""""""""""""""""""""""""""""""""""""""""""""

Para registrar uma observação e/ou justificativa, o usuário deverá clicar no botão "**Adicionar observação e/ou justificativa**", presente na grid do processo que deseja.

.. figure:: _static/images/listagem_eliminacao_observacao_justificativa.png
 
Preencher o campo com a informação desejada e clicar em Salvar.

.. figure:: _static/images/listagem_eliminacao_inclusao_observacao_justificativa.png
 
Após esta ação, a informação salva ficará disponível em tela no campo Observações e/ou Justificativas da Grid do processo.


Gestão das Listagens de Eliminação
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

A visão de Gestão das Listagens concentra a relação dos processos de  eliminação, criados na fase “**Preparação de Listagem**”.

Pesquisar
""""""""""

A pesquisa de processos poderá ser realizada por meio do preenchimento dos campos de filtragem disponíveis em tela e, em seguida, clique no botão "**Pesquisar**".
 
Imprimir
""""""""

Nesta visão será possível imprimir uma relação de processos conforme os filtros de pesquisa aplicados. Para realizar a Impressão (seja física ou em PDF), o usuário deverá selecionar os processos, via marcação de checkbox, e clicar em "**Imprimir**".

Visualizar Listagem de Eliminação
"""""""""""""""""""""""""""""""""

Para visualizar a listagem de eliminação o usuário deverá clicar no botão "**Visualizar Listagem de Eliminação**" disponível na grid do processo que deseja.

.. admonition:: Nota

   O documento Listagem de Eliminação conforme modelo definido pelo Conarq é criado no processo de eliminação gerado na tela de controle de processos da unidade responsável pela Avaliação.

.. figure:: _static/images/gestao_das_listagens_visualizao_listagem.gif

Ao acessar a listagem de eliminação, o usuário poderá imprimi-la, via clique no botão imprimir; poderá gerar um PDF, via clique no botão Gerar PDF; ou retornar à tela de gestão de listagens, via clique no botão "**Cancelar**".

.. figure:: _static/images/gestao_das_listagens_visualizao_listagem_opcoes.gif

Editar a Listagem de Eliminação
"""""""""""""""""""""""""""""""

Conforme a necessidade e/ou deliberações internas, o usuário poderá editar a listagem de eliminação clicando no botão "**Editar Listagem de Eliminação**".

.. figure:: _static/images/gestao_das_listagens_editar_listagem.gif

Ao realizar esta ação, o sistema irá apresentar na grid do processo botões para adicionar ou remover processos.

.. figure:: _static/images/gestao_das_listagens_editar_listagem_inclusao_exclusao.gif

Adicionar Processos à Listagem de Eliminação
"""""""""""""""""""""""""""""""""""""""""""""

Ao clicar em adicionar, o sistema disponibiliza a lista de todos os processos presentes na tela de Preparação da Listagem de Eliminação. 

Para incluir um ou mais processos, o usuário deverá selecionar, via marcação de checkbox, os processos que deseja incluir na listagem e clicar no botão "**Adicionar na Listagem de Eliminação**"".

.. figure:: _static/images/gestao_das_listagens_editar_listagem_opcao_inclusao.gif

Remover Processos da Listagem de Eliminação
"""""""""""""""""""""""""""""""""""""""""""

Ao clicar em remover, o sistema disponibiliza a lista de todos os processos presentes na listagem de eliminação.

Para excluir um ou mais processos, o usuário deverá selecionar, via marcação de checkbox, os processos que deseja excluir da listagem e clicar no botão "**Excluir da Listagem de Eliminação**".

.. figure:: _static/images/gestao_das_listagens_editar_listagem_opcao_exclusao.gif

Após realizar as inclusões e/ou exclusões de processos na listagem desejada, o usuário deverá clicar no botão "**Concluir Edição da Listagem**" para atualizar a lista com as edições efetuadas. Nesse momento será criada uma nova Listagem de Eliminação no processo de eliminação gerado na tela de controle de processos da unidade de avaliação.

.. figure:: _static/images/gestao_das_listagens_editar_listagem_inclusao_exclusao_atualizar.gif

Acessar o Processo
""""""""""""""""""

Para acessar o processo contendo a listagem de eliminação, o usuário deverá clicar sobre o número do processo em questão.

.. figure:: _static/images/gestao_das_listagens_acessar_listagem.gif


Listagem de Recolhimento
~~~~~~~~~~~~~~~~~~~~~~~~

Nesta opção, o usuário irá criar as listagens de processos elegíveis para recolhimento.

Preparar Listagem de Recolhimento
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

Pesquisar
"""""""""

A pesquisa poderá ser realizada por meio do preenchimento dos campos de filtragem disponíveis em tela e, em seguida, clique no botão "**Pesquisar**".

Gerar Listagem de Recolhimento
""""""""""""""""""""""""""""""

Para gerar uma listagem de recolhimento, o usuário deverá selecionar os processos que deseja que componham a listagem e clicar em "**Gerar Listagem de Recolhimento**".

.. figure:: _static/images/listagem_recolhimento_gerar_listagem.gif

Ao gerar uma listagem, o sistema criará um número de processo para guardar a listagem criada, que ficará disponível na visão “**Gestão das Listagens**”, ligada à Listagens de Recolhimento, existente no menu Gestão Documental.

Excluir da Preparação para Recolhimento
"""""""""""""""""""""""""""""""""""""""

Nesta visão, o usuário terá a possibilidade de excluir um ou mais processos da preparação da Listagem de Recolhimento.

Para excluir um único processo, o usuário deverá clicar no botão Excluir da Preparação para Recolhimento, presente na grid do processo.

.. figure:: _static/images/listagem_recolhimento_exclusao_uma_lista.png
 
Para excluir mais de um processo, o usuário deverá selecionar todos os processos desejados, via marcação de checkbox, e em seguida clicar no botão "**Excluir**", existente na parte superior direita da tela.

.. figure:: _static/images/listagem_recolhimento_exclusao_varias_listas.gif

Após a confirmação da exclusão, os processos ficarão disponíveis na visão de Avaliação de Processos, do menu "**Gestão Documental**"

Imprimir
""""""""

Nesta visão será possível imprimir uma relação de processos conforme os filtros de pesquisa aplicados. 

Para realizar a Impressão (seja física ou em PDF), o usuário deverá selecionar os processos, via marcação de checkbox, e clicar em "**Imprimir**".


Adicionar observação e/ou justificativa
"""""""""""""""""""""""""""""""""""""""

Para registrar uma observação e/ou justificativa, o usuário deverá clicar no botão "**Adicionar observação e/ou justificativa**", presente na grid do processo que deseja.

.. figure:: _static/images/listagem_recolhimento_observacao_justificativa.gif

Preencher o campo com a informação desejada e clicar em Salvar.

.. figure:: _static/images/listagem_recolhimento_inclusao_observacao_justificativa.gif
 
Após esta ação, a informação salva ficará disponível em tela no campo Observações e/ou Justificativas da Grid do processo.


Gestão das Listagens de Recolhimento
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

A visão de Gestão das Listagens concentra a relação dos processos de Recolhimento, criados na fase “Preparação de Listagem”.

Pesquisar
"""""""""

A pesquisa de processos poderá ser realizada por meio do preenchimento dos campos de filtragem disponíveis em tela e, em seguida, clique no botão "**Pesquisar**".

Imprimir
"""""""""

Nesta visão será possível imprimir uma relação de processos conforme os filtros de pesquisa aplicados. 

Para realizar a Impressão (seja física ou em PDF), o usuário deverá selecionar os processos, via marcação de checkbox, e clicar em "**Imprimir**".

Visualizar Listagem de Recolhimento
"""""""""""""""""""""""""""""""""""

Para visualizar a listagem de recolhimento o usuário deverá clicar no botão "**Visualizar Listagem**", disponível na grid do processo que deseja.

.. figure:: _static/images/recolhimento_gestao_das_listagens_visualizao_listagem.gif
 
Ao acessar a listagem de recolhimento, o usuário poderá imprimi-la, via clique no botão imprimir; poderá gerar um PDF, via clique no botão Gerar PDF; ou retornar a tela de gestão de listagens, via clique no botão Cancelar.

.. figure:: _static/images/recolhimento_gestao_das_listagens_visualizacao_listagem_opcoes.gif


Editar Listagem de Recolhimento
"""""""""""""""""""""""""""""""

Conforme a necessidade e/ou deliberações internas, o usuário poderá editar a listagem de recolhimento clicando no botão "**Editar Listagem de Recolhimento**".
 
.. figure:: _static/images/recolhimento_gestao_das_listagens_editar_listagem.gif

Ao realizar esta ação, o sistema irá deixar disponível na grid do processo um botão para adicionar processos e outro para remover processos.

.. figure:: _static/images/recolhimento_gestao_das_listagens_editar_listagem_inclusao_exclusao.gif

Adicionar Processos à Listagem de Recolhimento
""""""""""""""""""""""""""""""""""""""""""""""

Ao clicar em adicionar, o sistema disponibiliza a lista de todos os processos presentes na tela de Preparação da Listagem de Recolhimento.

Para incluir um ou mais processos, o usuário deverá selecionar, via marcação de *checkbox*, os processos que deseja incluir na listagem e clicar no botão "**Adicionar na Listagem de Recolhimento**".

.. figure:: _static/images/recolhimento_gestao_das_listagens_editar_listagem_opcao_inclusao.gif
 
Remover Processos da Listagem de Recolhimento
"""""""""""""""""""""""""""""""""""""""""""""

Ao clicar em remover, o sistema disponibiliza a lista de todos os processos presentes na listagem de recolhimento.

Para excluir um ou mais processos, o usuário deverá selecionar, via marcação de *checkbox*, os processos que deseja excluir da listagem e clicar no botão "**Excluir da Listagem de Recolhimento**".
 
.. figure:: _static/images/recolhimento_gestao_das_listagens_editar_listagem_opcao_exclusao.gif

Após realizar as inclusões e/ou exclusões de processos na listagem desejada, o usuário deverá clicar no botão Concluir Edição da Listagem para atualizar a lista com as edições efetuadas. Nesse momento será criada uma nova Listagem de Recolhimento no processo de recolhimento gerado na tela de controle de processos da unidade de avaliação.

.. figure:: _static/images/recolhimento_gestao_das_listagens_editar_listagem_inclusao_exclusao_atualizar.gif

Acessar o Processo
""""""""""""""""""

Para acessar o processo contendo a listagem de recolhimento, o usuário deverá clicar sobre o número do processo em questão.

.. figure:: _static/images/recolhimento_gestao_das_listagens_acessar_listagem.gif


Relatórios
~~~~~~~~~~

Nessa visão o usuário terá um panorama geral dos processos arquivados pelo Módulo.

Na parte inferior da tela existem contadores que auxiliam o usuário.

.. figure:: _static/images/relatorios_contadores.png


Pesquisar
^^^^^^^^^

A pesquisa de processos poderá ser realizada por meio do preenchimento dos campos de filtragem disponíveis em tela e, em seguida, clique no botão "**Pesquisar**".
 

Imprimir
^^^^^^^^

Nessa visão será possível imprimir uma relação de processos conforme os filtros de pesquisa aplicados.

Para realizar a Impressão (seja física ou em PDF), o usuário deverá selecionar os processos, via marcação de checkbox, e clicar em "**Imprimir**".

