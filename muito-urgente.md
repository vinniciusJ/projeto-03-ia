```
SE NÃO hipoxemia_grave E
    NÃO ha_estagio_3 E
    ha_estagio_2 E
    hipoxemia_moderada E
    NÃO taquicardia E
    NÃO taquipneia E
    NÃO confusao_mental
    NÃO dificuldade_de_falar
    NÃO bradicardia
    NÃO hipotermia 
    NÃO teve_convulsao
    NÃO bradipneia
    NÃO febre_alta
    NÃO hipoxemia_leve 
    NÃO dispneia_em_repouso 
    NÃO cianose ENTÃO "Muito urgente";

SE NÃO hipoxemia_grave E
    NÃO ha_estagio_3 E
    NÃO ha_estagio_2 E
    hipoxemia_moderada E
    NÃO taquicardia E
    NÃO taquipneia E
    NÃO confusao_mental E
    NÃO dificuldade_de_falar E 
    NÃO bradicardia E 
    hipotermia E
    NÃO teve_convulsao E
    NÃO bradipneia E
    NÃO ha_estagio_1 ENTÃO "Muito urgente";

SE NÃO hipoxemia_grave E
    NÃO ha_estagio_3 E
    NÃO ha_estagio_2 E
    hipoxemia_moderada E
    NÃO taquicardia E
    NÃO taquipneia E
    NÃO confusao_mental E
    NÃO dificuldade_de_falar E 
    NÃO bradicardia E 
    NÃO hipotermia E
    teve_convulsao E
    NÃO bradipneia E
    NÃO ha_estagio_1 E
    NÃO febre_alta ENTÃO "Muito urgente";

SE NÃO hipoxemia_grave E
    NÃO ha_estagio_3 E
    NÃO ha_estagio_2 E
    hipoxemia_moderada E
    NÃO taquicardia E
    NÃO taquipneia E
    NÃO confusao_mental E
    NÃO dificuldade_de_falar E 
    NÃO bradicardia E 
    NÃO hipotermia E
    NÃO teve_convulsao ENTÃO "Muito urgente";

SE NÃO hipoxemia_grave E
    NÃO ha_estagio_3 E
    NÃO ha_estagio_2 E
    NÃO hipoxemia_moderada E
    taquicardia E
    NÃO taquipneia E
    NÃO confusao_mental E
    NÃO dificuldade_de_falar E
    NÃO hipotermia E
    NÃO teve_convulsao E 
    bradipneia E
    NÃO ha_estagio_1 E
    cianose
    NÃo sudorese ENTÃO "Muito urgente";

SE NÃO hipoxemia_grave E
    NÃO ha_estagio_3 E
    NÃO ha_estagio_2 E
    NÃO hipoxemia_moderada E
    taquicardia E
    NÃO taquipneia E
    NÃO confusao_mental E
    NÃO dificuldade_de_falar E
    NÃO hipotermia E
    NÃO teve_convulsao E 
    bradipneia E
    NÃO ha_estagio_1 E
    NÃO cianose E
    hipoxemia_leve E
    NÃO dispneia_em_repouso ENTÃO "Muito urgente";  

SE NÃO hipoxemia_grave E
    NÃO ha_estagio_3 E
    NÃO ha_estagio_2 E
    NÃO hipoxemia_moderada E
    taquicardia E
    NÃO taquipneia E
    NÃO confusao_mental E
    NÃO dificuldade_de_falar E
    NÃO hipotermia E
    NÃO teve_convulsao E 
    NÃO bradipneia E
    ha_estagio_1 E
    NÃO hipoxemia_leve E
    NÃO cianose ENTÃO "Muito urgente";

SE NÃO hipoxemia_grave E
    NÃO ha_estagio_3 E
    NÃO ha_estagio_2 E
    NÃO hipoxemia_moderada E
    NÃO taquicardia E
    taquipneia E
    NÃO confusao_mental E
    NÃO dificuldade_de_falar E
    bradicardia E
    NÃO hipotermia
    NÃO teve_convulsao ENTÃO "Muito urgente";

SE NÃO hipoxemia_grave E
    NÃO ha_estagio_3 E
    NÃO ha_estagio_2 E
    NÃO hipoxemia_moderada E
    NÃO taquicardia E
    taquipneia E
    NÃO confusao_mental E
    NÃO dificuldade_de_falar E
    NÃO bradicardia E
    febre_alta E
    ha_estagio_1 E
    NÃO hipoxemia_leve ENTÃO "Muito urgente";

SE NÃO hipoxemia_grave E
    NÃO ha_estagio_3 E
    NÃO ha_estagio_2 E
    NÃO hipoxemia_moderada E
    NÃO taquicardia E
    taquipneia E
    NÃO confusao_mental E
    NÃO dificuldade_de_falar E
    NÃO bradicardia E
    NÃO febre_alta E
    hipoxemia_leve E
    NÃO cianose ENTÃO "Muito urgente";

SE NÃO hipoxemia_grave E
    NÃO ha_estagio_3 E
    NÃO ha_estagio_2 E
    NÃO hipoxemia_moderada E
    NÃO taquicardia E
    taquipneia E
    NÃO confusao_mental E
    NÃO dificuldade_de_falar E
    NÃO bradicardia E
    NÃO febre_alta E
    NÃO hipoxemia_leve ENTÃO "Muito urgente";

SE NÃO hipoxemia_grave E
    NÃO ha_estagio_3 E
    NÃO ha_estagio_2 E
    NÃO hipoxemia_moderada E
    NÃO taquicardia E
    NÃO taquipneia E
    confusao_mental E
    NÃO dificuldade_de_falar E
    NÃO bradicardia E
    NÃO hipotermia E 
    NÃO convulsao E 
    NÃO bradipneia E
    NÃO febre_alta E
    NÃO ha_estagio_1 E
    NÃO hipoxemia_leve E
    dispneia_em_repouso
    NÃO cianose ENTÃO "Muito urgente";

SE NÃO hipoxemia_grave E
    NÃO ha_estagio_3 E
    NÃO ha_estagio_2 E
    NÃO hipoxemia_moderada E
    NÃO taquicardia E
    NÃO taquipneia E
    confusao_mental E
    NÃO dificuldade_de_falar E
    NÃO bradicardia E
    NÃO hipotermia E 
    NÃO convulsao E 
    NÃO bradipneia E
    NÃO febre_alta E
    NÃO ha_estagio_1 E
    NÃO hipoxemia_leve E
    NÃO dispneia_em_repouso ENTÃO "Muito urgente";

SE NÃO hipoxemia_grave E
    NÃO ha_estagio_3 E
    NÃO ha_estagio_2 E
    NÃO hipoxemia_moderada E
    NÃO taquicardia E
    NÃO taquipneia E
    NÃO confusao_mental E
    dificuldade_de_falar E
    NÃO bradicardia E
    hipotermia E
    NÃO convulsao ENTÃO "Muito urgente";

SE NÃO hipoxemia_grave E
    NÃO ha_estagio_3 E
    NÃO ha_estagio_2 E
    NÃO hipoxemia_moderada E
    NÃO taquicardia E
    NÃO taquipneia E
    NÃO confusao_mental E
    dificuldade_de_falar E
    NÃO bradicardia E
    NÃO hipotermia E
    convulsao E
    bradipneia E
    NÃO febre_alta ENTÃO "Muito urgente";

SE NÃO hipoxemia_grave E
    NÃO ha_estagio_3 E
    NÃO ha_estagio_2 E
    NÃO hipoxemia_moderada E
    NÃO taquicardia E
    NÃO taquipneia E
    NÃO confusao_mental E
    dificuldade_de_falar E
    NÃO bradicardia E
    NÃO hipotermia E
    convulsao E
    NÃO bradipneia E
    febre_alta E
    NÃO ha_estagio_1 E
    NÃO hipoxemia_leve ENTÃO "Muito urgente";

SE NÃO hipoxemia_grave E
    NÃO ha_estagio_3 E
    NÃO ha_estagio_2 E
    NÃO hipoxemia_moderada E
    NÃO taquicardia E
    NÃO taquipneia E
    NÃO confusao_mental E
    dificuldade_de_falar E
    NÃO bradicardia E
    NÃO hipotermia E
    convulsao E
    NÃO bradipneia E
    NÃO febre_alta ENTÃO "Muito urgente";

SE NÃO hipoxemia_grave E
    NÃO ha_estagio_3 E
    NÃO ha_estagio_2 E
    NÃO hipoxemia_moderada E
    NÃO taquicardia E
    NÃO taquipneia E
    NÃO confusao_mental E
    dificuldade_de_falar E
    NÃO bradicardia E
    NÃO hipotermia E
    NÃO convulsao E
    bradipneia E
    febre_alta E
    ha_estagio_1 E
    NÃO hipoxemia_leve ENTÃO "Muito urgente";

SE NÃO hipoxemia_grave E
    NÃO ha_estagio_3 E
    NÃO ha_estagio_2 E
    NÃO hipoxemia_moderada E
    NÃO taquicardia E
    NÃO taquipneia E
    NÃO confusao_mental E
    dificuldade_de_falar E
    NÃO bradicardia E
    NÃO hipotermia E
    NÃO convulsao E
    bradipneia E
    febre_alta E
    NÃO ha_estagio_1 ENTÃO "Muito urgente";

SE NÃO hipoxemia_grave E
    NÃO ha_estagio_3 E
    NÃO ha_estagio_2 E
    NÃO hipoxemia_moderada E
    NÃO taquicardia E
    NÃO taquipneia E
    NÃO confusao_mental E
    dificuldade_de_falar E
    NÃO bradicardia E
    NÃO hipotermia E
    NÃO convulsao E
    bradipneia E
    NÃO febre_alta ENTÃO "Muito urgente";

SE NÃO hipoxemia_grave E
    NÃO ha_estagio_3 E
    NÃO ha_estagio_2 E
    NÃO hipoxemia_moderada E
    NÃO taquicardia E
    NÃO taquipneia E
    NÃO confusao_mental E
    dificuldade_de_falar E
    NÃO bradicardia E
    NÃO hipotermia E
    NÃO convulsao E
    NÃO bradipneia ENTÃO "Muito urgente";

SE NÃO hipoxemia_grave E
    NÃO ha_estagio_3 E
    NÃO ha_estagio_2 E
    NÃO hipoxemia_moderada E
    NÃO taquicardia E
    NÃO taquipneia E
    NÃO confusao_mental E
    NÃO dificuldade_de_falar E
    bradicardia E
    hipotermia E
    convulsao E
    bradipneia E
    NÃO ha_estagio_1 E
    NÃO hipoxemia_leve E
    NÃO dispneia_em_repouso E
    NÃO cianose ENTÃO "Muito urgente";

SE NÃO hipoxemia_grave E
    NÃO ha_estagio_3 E
    NÃO ha_estagio_2 E
    NÃO hipoxemia_moderada E
    NÃO taquicardia E
    NÃO taquipneia E
    NÃO confusao_mental E
    NÃO dificuldade_de_falar E
    bradicardia E
    hipotermia E
    convulsao E
    NÃO bradipneia E
    NÃO febre_alta ENTÃO "Muito urgente";

SE NÃO hipoxemia_grave E
    NÃO ha_estagio_3 E
    NÃO ha_estagio_2 E
    NÃO hipoxemia_moderada E
    NÃO taquicardia E
    NÃO taquipneia E
    NÃO confusao_mental E
    NÃO dificuldade_de_falar E
    bradicardia E
    hipotermia E
    NÃO convulsao ENTÃO "Muito urgente";

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
    convulsao ENTÃO "Muito urgente";

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
    cianose ENTÃO "Muito urgente";

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
    sudorese ENTÃO "Muito urgente";

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
    cianose E
    bradipneia E
    NÃO hipoxemia_leve ENTÃO "Muito urgente";

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
    cianose E
    NÃO bradipneia ENTÃO "Muito urgente";

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
    hipoxemia_leve ENTÃO "Muito urgente";

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
    hipoxemia_leve ENTÃO "Muito urgente";

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
    febre_alta ENTÃO "Muito urgente";

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
    hipoxemia_leve ENTÃO "Muito urgente";

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
    cianose ENTÃO "Muito urgente";

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
    cianose ENTÃO "Muito urgente";
```