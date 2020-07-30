 id,                        int(11)                  NOT NULL AUTO_INCREMENT,
empresa,                   varchar(60)              NOT NULL,
func_avaliado,             varchar(40)              NOT NULL,
funcao,                    varchar(30)              NOT NULL,
setor,                     varchar(30)              NOT NULL,
fonte_geradora,            varchar(60)              NOT NULL,
data_avaliacao,            date                     NOT NULL,
aparelho_tipo,             varchar(30)              NOT NULL,
aparelho_serie,            varchar(30)              NOT NULL,
aparelho_utilizacao,       varchar(30)              NOT NULL,
inicio_medicao,            time                     NOT NULL,
fim_medicao,               time                     NOT NULL,
epi_tipo,                  enum('P','M','L')        NOT NULL //COMMENT 'Protetor Auricular, Máscara ou Luva',
epi_ca,                    varchar(20)              NOT NULL,
exposicao_tipo,            enum('P','H','E')        NOT NULL COMMENT 'Permanente, Habitual ou Eventual ',
tempo_max_exposicao,       varchar(20)              NOT NULL,
trabalha_no_intervalo,     enum('T'             ,'F') NOT NULL COMMENT 'True or False (''T'' ou ''F'')',
texto_complementar,        varchar(250)             NOT NULL,
cliente_responsavel_avaliacao,  varchar(40)         NOT NULL,
assinatura_virtual,        varchar(300)             NOT NULL,







let data = {
"id" : 00001,
"empresa" : "Grande Empresas de Mineração LTDA",
"func_avaliado" : "Jhon Doe",
"funcao" : "Soldador",
"setor" : "Calderaria",
"fonte_geradora" : "Alguma fonte geradora válida",
"data_avaliacao" : "2020-07-28",
"aparelho_tipo" : "Bloqueador de Luminosidade",
"aparelho_serie" : "sn123456mask",
"aparelho_utilizacao" : "Proteção ocular contra queimaduras",
"inicio_medicao" : "14:30h",
"fim_medicao" : "16:30h",
"epi_tipo" : "M",
"epi_ca" : "999999",
"exposicao_tipo" : "E",
"tempo_max_exposicao" : "30 minutos",
"trabalha_no_intervalo" : "T",
"texto_complementar" : "Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incid",
"cliente_responsavel_avaliacao" : "Joana Doe",
"assinatura_virtual" : ""
}




{{id}}
{{empresa}}
{{func_avaliado}}
{{funcao}}
{{setor}}
{{fonte_geradora}}
{{data_avaliacao}}
{{aparelho_tipo}}
{{aparelho_serie}}
{{aparelho_utilizacao}}
{{inicio_medicao}}
{{fim_medicao}}
{{epi_tipo}}
{{epi_ca}}
{{exposicao_tipo}}
{{tempo_max_exposicao}}
{{trabalha_no_intervalo}}
{{texto_complementar}}
{{cliente_responsavel_avaliacao}}
{{assinatura_virtual}}
