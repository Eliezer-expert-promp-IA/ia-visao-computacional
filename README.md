# ia-visao-computacional
Criação de proejto teste da DIO.me, para treinamento da Azure IA900



#Inputs
- Extraia tags comuns de imagens
   ![image](https://github.com/user-attachments/assets/a685e021-69d6-40cc-87dd-4f37d907604d)
   ![image](https://github.com/user-attachments/assets/a95fe66a-1973-4a48-9de1-f0bc9f6ace51)

Ideiais de uso:
 * Utilização em energia solar: Criação de sistema que faz validação remota de instalações de usinas solares.

  # Código JSON #
#Extraia tags comuns de imagens (Json)
   {
  "apim-request-id": "9becc8a2-1c1f-467f-9b9c-ee0555586bf6",
  "comprimento-do-conteúdo": "571",
  "tipo de conteúdo": "aplicativo/json; conjunto de caracteres=utf-8",
  "modelVersion": "2023-10-01",
  "metadados": {
    "largura": 600,
    "altura": 359
  },
  "tagsResult": {
    "valores": [
      {
        "nome": "esboço",
        "confiança": 0,9740208387374878
      },
      {
        "nome": "arte linear",
        "confiança": 0,9635458588600159
      },
      {
        "nome": "clip art",
        "confiança": 0,9443122744560242
      },
      {
        "nome": "desenho",
        "confiança": 0,9373296499252319
      },
      {
        "nome": "ilustração",
        "confiança": 0,9252294898033142
      },
      {
        "nome": "livro de colorir",
        "confiança": 0,9178551435470581
      },
      {
        "nome": "traçado",
        "confiança": 0,8724575042724609
      },
      {
        "nome": "mamífero",
        "confiança": 0,8535805344581604
      },
      {
        "nome": "arte",
        "confiança": 0,7022183537483215
      }
    ]
  }
}



  
- Detector de Rostos
-   ![image](https://github.com/user-attachments/assets/8b8e5c94-017b-4120-bde2-6fd99c1a1564)
-   ![image](https://github.com/user-attachments/assets/22c0d194-368f-484a-a301-5bf740afad5c)

Ideiais de uso:
* Poderia substituri acessos via cartões aos condimínios e trazer mais segurança.
* Meios de Pagamentos: Substituir o uso da senha pela validação facial. 

 # Código JSON #
 [
  {
    "recognitionModel": "reconhecimento_01",
    "faceRectangle": {
      "largura": 119,
      "altura": 159,
      "esquerda": 564,
      "topo": 154
    },
    "faceMarcos": {
      "pupilaEsquerda": {
        "x": 592,
        "e": 228
      },
      "pupilaRight": {
        "x": 643,7,
        "e": 219,3
      },
      "ponta do nariz": {
        "x": 618,4,
        "e": 256,8
      },
      "bocaEsquerda": {
        "x": 601,9,
        "e": 278,2
      },
      "bocaDireita": {
        "x": 649,4,
        "e": 271
      },
      "sobrancelhaEsquerdaExterna": {
        "x": 574,
        "e": 216,5
      },
      "sobrancelhaEsquerdaInterna": {
        "x": 600,
        "e": 213,6
      },
      "olhoEsquerdoExterno": {
        "x": 582,7,
        "e": 229,1
      },
      "olhoEsquerdoTopo": {
        "x": 592,4,
        "e": 224
      },
      "olhoEsquerdoInferior": {
        "x": 591,1,
        "e": 231,4
      },
      "olhoEsquerdoInterno": {
        "x": 601,8,
        "e": 227,5
      },
      "sobrancelhaDireitaInterior": {
        "x": 626,9,
        "e": 209,9
      },
      "sobrancelhadireitaexterna": {
        "x": 660,1,
        "e": 204,6
      },
      "olhoDireitoInterior": {
        "x": 634,2,
        "e": 222,4
      },
      "olhoDireitoTopo": {
        "x": 641,5,
        "e": 215,3
      },
      "olhoDireitoInferior": {
        "x": 644,9,
        "e": 222,6
      },
      "olhoDireitoExterno": {
        "x": 654,1,
        "e": 216,9
      },
      "narizRaizEsquerda": {
        "x": 609,2,
        "e": 230,1
      },
      "narizRaizDireita": {
        "x": 623,6,
        "e": 227,7
      },
      "noseLeftAlarTop": {
        "x": 607,5,
        "e": 249,3
      },
      "noseRightAlarTop": {
        "x": 630,6,
        "e": 245,5
      },
      "noseLeftAlarOutTip": {
        "x": 604,7,
        "e": 259,1
      },
      "noseRightAlarOutTip": {
        "x": 637,2,
        "e": 254,7
      },
      "topo do lábio superior": {
        "x": 624,2,
        "e": 273,8
      },
      "lábiosuperiorinferior": {
        "x": 623,7,
        "e": 277,2
      },
      "underLipTop": {
        "x": 624,7,
        "e": 283,5
      },
      "underLipBottom": {
        "x": 625,9,
        "e": 289,6
      }
    },
    "Atributos de rosto": {
      "máscara": {
        "tipo": "noMask",
        "narizEBocaCoberto": falso
      }
    }
  },
  {
    "recognitionModel": "reconhecimento_01",
    "faceRectangle": {
      "largura": 96,
      "altura": 125,
      "esquerda": 362,
      "topo": 160
    },
    "faceMarcos": {
      "pupilaEsquerda": {
        "x": 399,4,
        "e": 209,7
      },
      "pupilaRight": {
        "x": 439,9,
        "e": 225,3
      },
      "ponta do nariz": {
        "x": 415,4,
        "e": 239,4
      },
      "bocaEsquerda": {
        "x": 388,3,
        "e": 251,2
      },
      "bocaDireita": {
        "x": 420,2,
        "e": 263,6
      },
      "sobrancelhaEsquerdaExterna": {
        "x": 388,3,
        "e": 191,8
      },
      "sobrancelhaEsquerdaInterna": {
        "x": 416,1,
        "e": 202,2
      },
      "olhoEsquerdoExterno": {
        "x": 392,1,
        "e": 206,9
      },
      "olhoEsquerdoTopo": {
        "x": 400,7,
        "e": 208
      },
      "olhoEsquerdoInferior": {
        "x": 398,5,
        "e": 211,4
      },
      "olhoEsquerdoInterno": {
        "x": 406,4,
        "e": 212,5
      },
      "sobrancelhaDireitaInterior": {
        "x": 435,8,
        "e": 210,4
      },
      "sobrancelhadireitaexterna": {
        "x": 458,1,
        "e": 218,6
      },
      "olhoDireitoInterior": {
        "x": 433,3,
        "e": 223,2
      },
      "olhoDireitoTopo": {
        "x": 440,6,
        "e": 223,1
      },
      "olhoDireitoInferior": {
        "x": 439,3,
        "e": 227
      },
      "olhoDireitoExterno": {
        "x": 446,4,
        "e": 228
      },
      "narizRaizEsquerda": {
        "x": 414,9,
        "e": 216,6
      },
      "narizRaizDireita": {
        "x": 426,5,
        "e": 221,2
      },
      "noseLeftAlarTop": {
        "x": 407,4,
        "e": 229,5
      },
      "noseRightAlarTop": {
        "x": 424,8,
        "e": 236
      },
      "noseLeftAlarOutTip": {
        "x": 400,
        "e": 235,5
      },
      "noseRightAlarOutTip": {
        "x": 425,3,
        "e": 245,5
      },
      "topo do lábio superior": {
        "x": 408,5,
        "e": 254,8
      },
      "lábiosuperiorinferior": {
        "x": 406,5,
        "e": 257,9
      },
      "underLipTop": {
        "x": 405,4,
        "e": 260,4
      },
      "underLipBottom": {
        "x": 403,2,
        "e": 265,7
      }
    },
    "Atributos de rosto": {
      "máscara": {
        "tipo": "noMask",
        "narizEBocaCoberto": falso
      }
    }
  }
]


#Códigos JASON dos exemplos utilizados!

- Extrair texto de imagens
  ![image](https://github.com/user-attachments/assets/3def4774-b7ce-4264-b995-d6f0c0281291)
  ![image](https://github.com/user-attachments/assets/771b5623-b4e6-43de-9288-a9416080cbde)

Ideiais de uso:
* Solar: Automatizar uma aplicação de fazer o dimensionamento de projeto de usina solar pela foto das contas de luz.
  

 # Código JSON #
----
[
  {
    "linhas": [
      {
        "texto": "Informações Nutricionais",
        "polígonolimitador": [
          {
            "x": 142,
            "e": 0
          },
          {
            "x": 709,
            "e": 96
          },
          {
            "x": 697,
            "e": 164
          },
          {
            "x": 129,
            "e": 59
          }
        ],
        "palavras": [
          {
            "texto": "Nutrição",
            "polígonolimitador": [
              {
                "x": 144,
                "e": 0
              },
              {
                "x": 447,
                "e": 48
              },
              {
                "x": 432,
                "e": 114
              },
              {
                "x": 130,
                "e": 59
              }
            ],
            "confiança": 0,994
          },
          {
            "texto": "Fatos",
            "polígonolimitador": [
              {
                "x": 486,
                "e": 55
              },
              {
                "x": 684,
                "e": 97
              },
              {
                "x": 669,
                "e": 160
              },
              {
                "x": 471,
                "e": 122
              }
            ],
            "confiança": 0,996
          }
        ]
      },
      {
        "text": "Quantidade por porção",
        "polígonolimitador": [
          {
            "x": 720,
            "e": 115
          },
          {
            "x": 1238,
            "e": 225
          },
          {
            "x": 1227,
            "e": 273
          },
          {
            "x": 709,
            "e": 161
          }
        ],
        "palavras": [
          {
            "texto": "Quantidade",
            "polígonolimitador": [
              {
                "x": 732,
                "e": 117
              },
              {
                "x": 925,
                "e": 157
              },
              {
                "x": 915,
                "e": 201
              },
              {
                "x": 722,
                "e": 163
              }
            ],
            "confiança": 0,991
          },
          {
            "texto": "Por",
            "polígonolimitador": [
              {
                "x": 938,
                "e": 160
              },
              {
                "x": 1021,
                "e": 178
              },
              {
                "x": 1010,
                "e": 222
              },
              {
                "x": 927,
                "e": 204
              }
            ],
            "confiança": 0,999
          },
          {
            "texto": "Servindo",
            "polígonolimitador": [
              {
                "x": 1039,
                "e": 182
              },
              {
                "x": 1223,
                "e": 223
              },
              {
                "x": 1212,
                "e": 271
              },
              {
                "x": 1029,
                "e": 227
              }
            ],
            "confiança": 0,994
          }
        ]
      },
      {
        "texto": "Tamanho da porção: 1 barra (40g)",
        "polígonolimitador": [
          {
            "x": 107,
            "e": 58
          },
          {
            "x": 598,
            "e": 154
          },
          {
            "x": 587,
            "e": 207
          },
          {
            "x": 97,
            "e": 109
          }
        ],
        "palavras": [
          {
            "texto": "Servindo",
            "polígonolimitador": [
              {
                "x": 111,
                "e": 60
              },
              {
                "x": 258,
                "e": 87
              },
              {
                "x": 247,
                "e": 139
              },
              {
                "x": 101,
                "e": 110
              }
            ],
            "confiança": 0,993
          },
          {
            "texto": "tamanho:",
            "polígonolimitador": [
              {
                "x": 269,
                "e": 89
              },
              {
                "x": 365,
                "e": 108
              },
              {
                "x": 354,
                "e": 160
              },
              {
                "x": 258,
                "e": 141
              }
            ],
            "confiança": 0,993
          },
          {
            "texto 1",
            "polígonolimitador": [
              {
                "x": 375,
                "e": 110
              },
              {
                "x": 399,
                "e": 114
              },
              {
                "x": 388,
                "e": 167
              },
              {
                "x": 364,
                "e": 163
              }
            ],
            "confiança": 0,994
          },
          {
            "texto": "barra",
            "polígonolimitador": [
              {
                "x": 409,
                "e": 116
              },
              {
                "x": 478,
                "e": 131
              },
              {
                "x": 467,
                "e": 183
              },
              {
                "x": 398,
                "e": 169
              }
            ],
            "confiança": 0,995
          },
          {
            "texto": "(40g)",
            "polígonolimitador": [
              {
                "x": 488,
                "e": 133
              },
              {
                "x": 597,
                "e": 156
              },
              {
                "x": 586,
                "e": 208
              },
              {
                "x": 477,
                "e": 185
              }
            ],
            "confiança": 0,994
          }
        ]
      },
      {
        "text": "Porções por pacote: 4",
        "polígonolimitador": [
          {
            "x": 79,
            "e": 109
          },
          {
            "x": 553,
            "e": 203
          },
          {
            "x": 542,
            "e": 255
          },
          {
            "x": 68,
            "e": 161
          }
        ],
        "palavras": [
          {
            "texto": "Servindo",
            "polígonolimitador": [
              {
                "x": 85,
                "e": 110
              },
              {
                "x": 230,
                "e": 138
              },
              {
                "x": 218,
                "e": 192
              },
              {
                "x": 72,
                "e": 163
              }
            ],
            "confiança": 0,995
          },
          {
            "texto": "Por",
            "polígonolimitador": [
              {
                "x": 241,
                "e": 140
              },
              {
                "x": 308,
                "e": 154
              },
              {
                "x": 298,
                "e": 207
              },
              {
                "x": 229,
                "e": 194
              }
            ],
            "confiança": 0,994
          },
          {
            "texto": "Pacote:",
            "polígonolimitador": [
              {
                "x": 319,
                "e": 156
              },
              {
                "x": 514,
                "e": 199
              },
              {
                "x": 505,
                "e": 248
              },
              {
                "x": 308,
                "e": 209
              }
            ],
            "confiança": 0,993
          },
          {
            "texto": "4",
            "polígonolimitador": [
              {
                "x": 525,
                "e": 202
              },
              {
                "x": 551,
                "e": 208
              },
              {
                "x": 542,
                "e": 255
              },
              {
                "x": 516,
                "e": 250
              }
            ],
            "confiança": 0,996
          }
        ]
      },
      {
        "texto": "Gordura total 13g",
        "polígonolimitador": [
          {
            "x": 682,
            "e": 214
          },
          {
            "x": 1001,
            "e": 285
          },
          {
            "x": 990,
            "e": 333
          },
          {
            "x": 672,
            "e": 260
          }
        ],
        "palavras": [
          {
            "texto": "Total",
            "polígonolimitador": [
              {
                "x": 686,
                "e": 215
              },
              {
                "x": 810,
                "e": 242
              },
              {
                "x": 798,
                "e": 287
              },
              {
                "x": 675,
                "e": 260
              }
            ],
            "confiança": 0,993
          },
          {
            "texto": "Gordo",
            "polígonolimitador": [
              {
                "x": 819,
                "e": 244
              },
              {
                "x": 903,
                "e": 263
              },
              {
                "x": 890,
                "e": 309
              },
              {
                "x": 807,
                "e": 289
              }
            ],
            "confiança": 0,993
          },
          {
            "texto": "13g",
            "polígonolimitador": [
              {
                "x": 919,
                "e": 267
              },
              {
                "x": 996,
                "e": 286
              },
              {
                "x": 982,
                "e": 333
              },
              {
                "x": 905,
                "e": 313
              }
            ],
            "confiança": 0,999
          }
        ]
      },
      {
        "texto": "Gordura Saturada 1,5g",
        "polígonolimitador": [
          {
            "x": 693,
            "e": 297
          },
          {
            "x": 1119,
            "e": 394
          },
          {
            "x": 1106,
            "e": 449
          },
          {
            "x": 684,
            "e": 347
          }
        ],
        "palavras": [
          {
            "texto": "Saturado",
            "polígonolimitador": [
              {
                "x": 696,
                "e": 298
              },
              {
                "x": 908,
                "e": 345
              },
              {
                "x": 897,
                "e": 395
              },
              {
                "x": 687,
                "e": 346
              }
            ],
            "confiança": 0,995
          },
          {
            "texto": "Gordo",
            "polígonolimitador": [
              {
                "x": 925,
                "e": 349
              },
              {
                "x": 1007,
                "e": 368
              },
              {
                "x": 995,
                "e": 420
              },
              {
                "x": 914,
                "e": 399
              }
            ],
            "confiança": 0,999
          },
          {
            "texto": "1,5g",
            "polígonolimitador": [
              {
                "x": 1018,
                "e": 370
              },
              {
                "x": 1113,
                "e": 394
              },
              {
                "x": 1100,
                "e": 448
              },
              {
                "x": 1006,
                "e": 423
              }
            ],
            "confiança": 0,992
          }
        ]
      },
      {
        "text": "Quantidade por porção",
        "polígonolimitador": [
          {
            "x": 25,
            "e": 213
          },
          {
            "x": 489,
            "e": 310
          },
          {
            "x": 477,
            "e": 366
          },
          {
            "x": 14,
            "e": 264
          }
        ],
        "palavras": [
          {
            "texto": "Quantidade",
            "polígonolimitador": [
              {
                "x": 28,
                "e": 215
              },
              {
                "x": 206,
                "e": 249
              },
              {
                "x": 195,
                "e": 296
              },
              {
                "x": 18,
                "e": 262
              }
            ],
            "confiança": 0,996
          },
          {
            "texto": "Por",
            "polígonolimitador": [
              {
                "x": 216,
                "e": 251
              },
              {
                "x": 299,
                "e": 268
              },
              {
                "x": 287,
                "e": 317
              },
              {
                "x": 204,
                "e": 298
              }
            ],
            "confiança": 0,993
          },
          {
            "texto": "Servindo",
            "polígonolimitador": [
              {
                "x": 313,
                "e": 271
              },
              {
                "x": 486,
                "e": 312
              },
              {
                "x": 472,
                "e": 366
              },
              {
                "x": 300,
                "e": 320
              }
            ],
            "confiança": 0,993
          }
        ]
      },
      {
        "texto": "Gordura Trans 0g",
        "polígonolimitador": [
          {
            "x": 667,
            "e": 368
          },
          {
            "x": 953,
            "e": 438
          },
          {
            "x": 941,
            "e": 487
          },
          {
            "x": 655,
            "e": 415
          }
        ],
        "palavras": [
          {
            "texto": "Tradução",
            "polígonolimitador": [
              {
                "x": 670,
                "e": 368
              },
              {
                "x": 795,
                "e": 399
              },
              {
                "x": 780,
                "e": 443
              },
              {
                "x": 656,
                "e": 415
              }
            ],
            "confiança": 0,993
          },
          {
            "texto": "Gordo",
            "polígonolimitador": [
              {
                "x": 808,
                "e": 402
              },
              {
                "x": 887,
                "e": 422
              },
              {
                "x": 873,
                "e": 468
              },
              {
                "x": 793,
                "e": 446
              }
            ],
            "confiança": 0,993
          },
          {
            "texto": "0g",
            "polígonolimitador": [
              {
                "x": 896,
                "e": 424
              },
              {
                "x": 950,
                "e": 438
              },
              {
                "x": 936,
                "e": 487
              },
              {
                "x": 882,
                "e": 470
              }
            ],
            "confiança": 0,902
          }
        ]
      },
      {
        "texto": "alorias 190",
        "polígonolimitador": [
          {
            "x": 7,
            "e": 294
          },
          {
            "x": 268,
            "e": 351
          },
          {
            "x": 258,
            "e": 396
          },
          {
            "x": 0,
            "e": 338
          }
        ],
        "palavras": [
          {
            "texto": "alórias",
            "polígonolimitador": [
              {
                "x": 13,
                "e": 295
              },
              {
                "x": 170,
                "e": 330
              },
              {
                "x": 158,
                "e": 375
              },
              {
                "x": 6,
                "e": 341
              }
            ],
            "confiança": 0,176
          },
          {
            "texto": "190",
            "polígonolimitador": [
              {
                "x": 188,
                "e": 334
              },
              {
                "x": 262,
                "e": 350
              },
              {
                "x": 248,
                "e": 395
              },
              {
                "x": 176,
                "e": 379
              }
            ],
            "confiança": 0,989
          }
        ]
      },
      {
        "texto": "Colesterol 0mg",
        "polígonolimitador": [
          {
            "x": 594,
            "e": 428
          },
          {
            "x": 1009,
            "e": 527
          },
          {
            "x": 994,
            "e": 585
          },
          {
            "x": 581,
            "e": 479
          }
        ],
        "palavras": [
          {
            "texto": "Colesterol",
            "polígonolimitador": [
              {
                "x": 593,
                "e": 429
              },
              {
                "x": 886,
                "e": 496
              },
              {
                "x": 871,
                "e": 551
              },
              {
                "x": 581,
                "e": 476
              }
            ],
            "confiança": 0,994
          },
          {
            "texto": "0mg",
            "polígonolimitador": [
              {
                "x": 896,
                "e": 499
              },
              {
                "x": 1002,
                "e": 528
              },
              {
                "x": 987,
                "e": 584
              },
              {
                "x": 882,
                "e": 554
              }
            ],
            "confiança": 0,839
          }
        ]
      },
      {
        "texto": "teorias do Fat 110",
        "polígonolimitador": [
          {
            "x": 4,
            "e": 371
          },
          {
            "x": 399,
            "e": 463
          },
          {
            "x": 387,
            "e": 513
          },
          {
            "x": 0,
            "e": 420
          }
        ],
        "palavras": [
          {
            "texto": "orias",
            "polígonolimitador": [
              {
                "x": 7,
                "e": 372
              },
              {
                "x": 107,
                "e": 396
              },
              {
                "x": 101,
                "e": 447
              },
              {
                "x": 3,
                "e": 424
              }
            ],
            "confiança": 0,989
          },
          {
            "texto": "de",
            "polígonolimitador": [
              {
                "x": 118,
                "e": 399
              },
              {
                "x": 199,
                "e": 418
              },
              {
                "x": 190,
                "e": 468
              },
              {
                "x": 111,
                "e": 449
              }
            ],
            "confiança": 0,99
          },
          {
            "texto": "Gordo",
            "polígonolimitador": [
              {
                "x": 229,
                "e": 425
              },
              {
                "x": 306,
                "e": 442
              },
              {
                "x": 296,
                "e": 492
              },
              {
                "x": 220,
                "e": 474
              }
            ],
            "confiança": 0,998
          },
          {
            "texto": "110",
            "polígonolimitador": [
              {
                "x": 317,
                "e": 445
              },
              {
                "x": 395,
                "e": 462
              },
              {
                "x": 382,
                "e": 512
              },
              {
                "x": 306,
                "e": 494
              }
            ],
            "confiança": 0,999
          }
        ]
      },
      {
        "texto": "Sódio 20mg",
        "polígonolimitador": [
          {
            "x": 556,
            "e": 499
          },
          {
            "x": 915,
            "e": 587
          },
          {
            "x": 900,
            "e": 643
          },
          {
            "x": 542,
            "e": 551
          }
        ],
        "palavras": [
          {
            "texto": "Sódio",
            "polígonolimitador": [
              {
                "x": 566,
                "e": 501
              },
              {
                "x": 735,
                "e": 541
              },
              {
                "x": 719,
                "e": 595
              },
              {
                "x": 550,
                "e": 551
              }
            ],
            "confiança": 0,994
          },
          {
            "texto": "20mg",
            "polígonolimitador": [
              {
                "x": 778,
                "e": 552
              },
              {
                "x": 910,
                "e": 587
              },
              {
                "x": 895,
                "e": 643
              },
              {
                "x": 762,
                "e": 606
              }
            ],
            "confiança": 0,987
          }
        ]
      },
      {
        "text": "Os valores diários são baseados em",
        "polígonolimitador": [
          {
            "x": 4,
            "e": 472
          },
          {
            "x": 465,
            "e": 586
          },
          {
            "x": 454,
            "e": 628
          },
          {
            "x": 0,
            "e": 516
          }
        ],
        "palavras": [
          {
            "texto": "nt",
            "polígonolimitador": [
              {
                "x": 5,
                "e": 472
              },
              {
                "x": 33,
                "e": 480
              },
              {
                "x": 28,
                "e": 525
              },
              {
                "x": 0,
                "e": 518
              }
            ],
            "confiança": 0,995
          },
          {
            "texto": "Diariamente",
            "polígonolimitador": [
              {
                "x": 41,
                "e": 482
              },
              {
                "x": 120,
                "e": 502
              },
              {
                "x": 114,
                "e": 547
              },
              {
                "x": 36,
                "e": 528
              }
            ],
            "confiança": 0,993
          },
          {
            "texto": "Valores",
            "polígonolimitador": [
              {
                "x": 129,
                "e": 504
              },
              {
                "x": 236,
                "e": 531
              },
              {
                "x": 228,
                "e": 576
              },
              {
                "x": 122,
                "e": 550
              }
            ],
            "confiança": 0,994
          },
          {
            "texto": "são",
            "polígonolimitador": [
              {
                "x": 245,
                "e": 534
              },
              {
                "x": 298,
                "e": 547
              },
              {
                "x": 289,
                "e": 590
              },
              {
                "x": 236,
                "e": 578
              }
            ],
            "confiança": 0,998
          },
          {
            "texto": "baseado",
            "polígonolimitador": [
              {
                "x": 307,
                "e": 549
              },
              {
                "x": 408,
                "e": 574
              },
              {
                "x": 397,
                "e": 615
              },
              {
                "x": 297,
                "e": 592
              }
            ],
            "confiança": 0,997
          },
          {
            "texto": "em",
            "polígonolimitador": [
              {
                "x": 417,
                "e": 577
              },
              {
                "x": 461,
                "e": 588
              },
              {
                "x": 450,
                "e": 627
              },
              {
                "x": 406,
                "e": 617
              }
            ],
            "confiança": 0,998
          }
        ]
      },
      {
        "texto": "Vitamina A 50% . VN",
        "polígonolimitador": [
          {
            "x": 523,
            "e": 598
          },
          {
            "x": 876,
            "e": 674
          },
          {
            "x": 867,
            "e": 703
          },
          {
            "x": 514,
            "e": 648
          }
        ],
        "palavras": [
          {
            "texto": "Vitamina",
            "polígonolimitador": [
              {
                "x": 529,
                "e": 600
              },
              {
                "x": 651,
                "e": 630
              },
              {
                "x": 640,
                "e": 677
              },
              {
                "x": 516,
                "e": 643
              }
            ],
            "confiança": 0,936
          },
          {
            "texto": "A",
            "polígonolimitador": [
              {
                "x": 662,
                "e": 632
              },
              {
                "x": 681,
                "e": 637
              },
              {
                "x": 671,
                "e": 683
              },
              {
                "x": 651,
                "e": 679
              }
            ],
            "confiança": 0,959
          },
          {
            "texto": "50%",
            "polígonolimitador": [
              {
                "x": 694,
                "e": 641
              },
              {
                "x": 781,
                "e": 663
              },
              {
                "x": 772,
                "e": 698
              },
              {
                "x": 684,
                "e": 686
              }
            ],
            "confiança": 0,826
          },
          {
            "texto": ".",
            "polígonolimitador": [
              {
                "x": 791,
                "e": 666
              },
              {
                "x": 811,
                "e": 671
              },
              {
                "x": 803,
                "e": 701
              },
              {
                "x": 783,
                "e": 699
              }
            ],
            "confiança": 0,222
          },
          {
            "texto": "VN",
            "polígonolimitador": [
              {
                "x": 819,
                "e": 674
              },
              {
                "x": 870,
                "e": 688
              },
              {
                "x": 863,
                "e": 703
              },
              {
                "x": 811,
                "e": 702
              }
            ],
            "confiança": 0,121
          }
        ]
      },
      {
        "texto": "dieta calórica.",
        "polígonolimitador": [
          {
            "x": 4,
            "e": 526
          },
          {
            "x": 198,
            "e": 578
          },
          {
            "x": 186,
            "e": 618
          },
          {
            "x": 0,
            "e": 568
          }
        ],
        "palavras": [
          {
            "texto": "caloria",
            "polígonolimitador": [
              {
                "x": 10,
                "e": 528
              },
              {
                "x": 121,
                "e": 558
              },
              {
                "x": 113,
                "e": 600
              },
              {
                "x": 5,
                "e": 572
              }
            ],
            "confiança": 0,994
          },
          {
            "texto": "dieta.",
            "polígonolimitador": [
              {
                "x": 129,
                "e": 561
              },
              {
                "x": 197,
                "e": 578
              },
              {
                "x": 188,
                "e": 618
              },
              {
                "x": 121,
                "e": 602
              }
            ],
            "confiança": 0,947
          }
        ]
      }
    ]
  }
]
