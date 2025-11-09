```
102 - SE NÃO hipoxemia_grave E
    NÃO ha_estagio_3 E
    NÃO ha_estagio_2 E
    NÃO hipoxemia_moderada E
    NÃO taquicardia E
    NÃO taquipneia E
    NÃO confusao_mental E
    NÃO dificuldade_de_falar E
    bradicardia E
    NÃO hipotermia E
    NÃO convulsao E
    NÃO cianose E
    palidez E
    NÃO sudorese ENTÃO "Urgente";

103 - SE NÃO hipoxemia_grave E
    NÃO ha_estagio_3 E
    NÃO ha_estagio_2 E
    NÃO hipoxemia_moderada E
    NÃO taquicardia E
    NÃO taquipneia E
    NÃO confusao_mental E
    NÃO dificuldade_de_falar E
    bradicardia E
    NÃO hipotermia E
    NÃO convulsao E
    NÃO cianose E
    NÃO palidez ENTÃO "Urgente";

104 - SE NÃO hipoxemia_grave E
    NÃO ha_estagio_3 E
    NÃO ha_estagio_2 E
    NÃO hipoxemia_moderada E
    NÃO taquicardia E
    NÃO taquipneia E
    NÃO confusao_mental E
    NÃO dificuldade_de_falar E
    NÃO bradicardia E
    hipotermia E
    NÃO cianose E
    convulsao E
    NÃO hipoxemia_leve ENTÃO "Urgente";

105 - SE NÃO hipoxemia_grave E
    NÃO ha_estagio_3 E
    NÃO ha_estagio_2 E
    NÃO hipoxemia_moderada E
    NÃO taquicardia E
    NÃO taquipneia E
    NÃO confusao_mental E
    NÃO dificuldade_de_falar E
    NÃO bradicardia E
    hipotermia E
    NÃO cianose E
    NÃO convulsao E
    bradipneia E
    NÃO hipoxemia_leve ENTÃO "Urgente";

106 - SE NÃO hipoxemia_grave E
    NÃO ha_estagio_3 E
    NÃO ha_estagio_2 E
    NÃO hipoxemia_moderada E
    NÃO taquicardia E
    NÃO taquipneia E
    NÃO confusao_mental E
    NÃO dificuldade_de_falar E
    NÃO bradicardia E
    hipotermia E
    NÃO cianose E
    NÃO convulsao E
    NÃO bradipneia ENTÃO "Urgente";

107 - SE NÃO hipoxemia_grave E
    NÃO ha_estagio_3 E
    NÃO ha_estagio_2 E
    NÃO hipoxemia_moderada E
    NÃO taquicardia E
    NÃO taquipneia E
    NÃO confusao_mental E
    NÃO dificuldade_de_falar E
    NÃO bradicardia E
    NÃO hipotermia E
    convulsao E
    NÃO febre_alta E
    NÃO hipoxemia_leve E
    bradipneia E
    NÃO cianose ENTÃO "Urgente";

108 - SE NÃO hipoxemia_grave E
    NÃO ha_estagio_3 E
    NÃO ha_estagio_2 E
    NÃO hipoxemia_moderada E
    NÃO taquicardia E
    NÃO taquipneia E
    NÃO confusao_mental E
    NÃO dificuldade_de_falar E
    NÃO bradicardia E
    NÃO hipotermia E
    convulsao E
    NÃO febre_alta E
    NÃO hipoxemia_leve E
    NÃO bradipneia ENTÃO "Urgente";

109 - SE NÃO hipoxemia_grave E
    NÃO ha_estagio_3 E
    NÃO ha_estagio_2 E
    NÃO hipoxemia_moderada E
    NÃO taquicardia E
    NÃO taquipneia E
    NÃO confusao_mental E
    NÃO dificuldade_de_falar E
    NÃO bradicardia E
    NÃO hipotermia E
    NÃO convulsao E
    bradipneia E
    NÃO cianose ENTÃO "Urgente";

110 - SE NÃO hipoxemia_grave E
    NÃO ha_estagio_3 E
    NÃO ha_estagio_2 E
    NÃO hipoxemia_moderada E
    NÃO taquicardia E
    NÃO taquipneia E
    NÃO confusao_mental E
    NÃO dificuldade_de_falar E
    NÃO bradicardia E
    NÃO hipotermia E
    NÃO convulsao E
    NÃO bradipneia E
    febre_alta ENTÃO "Urgente";

111 - SE NÃO hipoxemia_grave E
    NÃO ha_estagio_3 E
    NÃO ha_estagio_2 E
    NÃO hipoxemia_moderada E
    NÃO taquicardia E
    NÃO taquipneia E
    NÃO confusao_mental E
    NÃO dificuldade_de_falar E
    NÃO bradicardia E
    NÃO hipotermia E
    NÃO convulsao E
    NÃO bradipneia E
    NÃO febre_alta E
    ha_estagio_1 ENTÃO "Urgente";

112 - SE NÃO hipoxemia_grave E
    NÃO ha_estagio_3 E
    NÃO ha_estagio_2 E
    NÃO hipoxemia_moderada E
    NÃO taquicardia E
    NÃO taquipneia E
    NÃO confusao_mental E
    NÃO dificuldade_de_falar E
    NÃO bradicardia E
    NÃO hipotermia E
    NÃO convulsao E
    NÃO bradipneia E
    NÃO febre_alta E
    NÃO ha_estagio_1 E 
    hipoxemia_leve ENTÃO "Urgente";

113 - SE NÃO hipoxemia_grave E
    NÃO ha_estagio_3 E
    NÃO ha_estagio_2 E
    NÃO hipoxemia_moderada E
    NÃO taquicardia E
    NÃO taquipneia E
    NÃO confusao_mental E
    NÃO dificuldade_de_falar E
    NÃO bradicardia E
    NÃO hipotermia E
    NÃO convulsao E
    NÃO bradipneia E
    NÃO febre_alta E
    NÃO ha_estagio_1 E 
    NÃO hipoxemia_leve E 
    cianose ENTÃO "Urgente";
```