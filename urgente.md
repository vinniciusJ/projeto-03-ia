```
SE NÃO hipoxemia_grave E
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

SE NÃO hipoxemia_grave E
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

SE NÃO hipoxemia_grave E
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

SE NÃO hipoxemia_grave E
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

SE NÃO hipoxemia_grave E
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

SE NÃO hipoxemia_grave E
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

SE NÃO hipoxemia_grave E
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

SE NÃO hipoxemia_grave E
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

SE NÃO hipoxemia_grave E
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

SE NÃO hipoxemia_grave E
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

SE NÃO hipoxemia_grave E
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

SE NÃO hipoxemia_grave E
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