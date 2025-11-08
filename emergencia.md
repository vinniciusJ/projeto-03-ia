```
SE hipoxemia_grave ENTÃO "Emergência";

SE NÃO hipoxemia_grave E
    ha_estagio_3 ENTÃO "Emergência";

SE NÃO hipoxemia_grave E
    NÃO ha_estagio_3 E
    ha_estagio_2 E
    hipoxemia_moderada ENTÃO "Emergência";

SE NÃO hipoxemia_grave E
    NÃO ha_estagio_3 E
    ha_estagio_2 E
    NÃO hipoxemia_moderada E
    taquicardia ENTÃO "Emergência";

SE NÃO hipoxemia_grave E
    NÃO ha_estagio_3 E
    ha_estagio_2 E
    NÃO hipoxemia_moderada E
    NÃO taquicardia E
    taquipneia ENTÃO "Emergência";

SE NÃO hipoxemia_grave E
    NÃO ha_estagio_3 E
    ha_estagio_2 E
    NÃO hipoxemia_moderada E
    NÃO taquicardia E
    NÃO taquipneia E
    confusao_mental ENTÃO "Emergência";

SE NÃO hipoxemia_grave E
    NÃO ha_estagio_3 E
    ha_estagio_2 E
    NÃO hipoxemia_moderada E
    NÃO taquicardia E
    NÃO taquipneia E
    NÃO confusao_mental
    dificuldade_de_falar ENTÃO "Emergência";

SE NÃO hipoxemia_grave E
    NÃO ha_estagio_3 E
    ha_estagio_2 E
    NÃO hipoxemia_moderada E
    NÃO taquicardia E
    NÃO taquipneia E
    NÃO confusao_mental
    NÃO dificuldade_de_falar
    bradicardia ENTÃO "Emergência";

SE NÃO hipoxemia_grave E
    NÃO ha_estagio_3 E
    ha_estagio_2 E
    NÃO hipoxemia_moderada E
    NÃO taquicardia E
    NÃO taquipneia E
    NÃO confusao_mental E
    NÃO dificuldade_de_falar E
    NÃO bradicardia E
    hipotermia ENTÃO "Emergência";

SE NÃO hipoxemia_grave E
    NÃO ha_estagio_3 E
    ha_estagio_2 E
    NÃO hipoxemia_moderada E
    NÃO taquicardia E
    NÃO taquipneia E
    NÃO confusao_mental E
    NÃO dificuldade_de_falar E
    NÃO bradicardia E
    NÃO hipotermia E 
    teve_convulsao ENTÃO "Emergência";

SE NÃO hipoxemia_grave E
    NÃO ha_estagio_3 E
    ha_estagio_2 E
    NÃO hipoxemia_moderada E
    NÃO taquicardia E
    NÃO taquipneia E
    NÃO confusao_mental E
    NÃO dificuldade_de_falar E
    NÃO bradicardia E
    NÃO hipotermia E 
    NÃO teve_convulsao E
    bradipneia ENTÃO "Emergência";

SE NÃO hipoxemia_grave E
    NÃO ha_estagio_3 E
    ha_estagio_2 E
    NÃO hipoxemia_moderada E
    NÃO taquicardia E
    NÃO taquipneia E
    NÃO confusao_mental E
    NÃO dificuldade_de_falar E
    NÃO bradicardia E
    NÃO hipotermia  E
    NÃO teve_convulsao E
    NÃO bradipneia E
    febre_alta ENTÃO "Emergência";

SE NÃO hipoxemia_grave E
    NÃO ha_estagio_3 E
    ha_estagio_2 E
    NÃO hipoxemia_moderada E
    NÃO taquicardia E
    NÃO taquipneia E
    NÃO confusao_mental E
    NÃO dificuldade_de_falar E
    NÃO bradicardia E
    NÃO hipotermia E
    NÃO teve_convulsao E
    NÃO bradipneia E
    NÃO febre_alta E
    hipoxemia_leve ENTÃO "Emergência";

SE NÃO hipoxemia_grave E
    NÃO ha_estagio_3 E
    ha_estagio_2 E
    NÃO hipoxemia_moderada E
    NÃO taquicardia E
    NÃO taquipneia E
    NÃO confusao_mental E
    NÃO dificuldade_de_falar E
    NÃO bradicardia E
    NÃO hipotermia E
    NÃO teve_convulsao E
    NÃO bradipneia E
    NÃO febre_alta E
    NÃO hipoxemia_leve E
    dispneia_em_repouso ENTÃO "Emergência";

SE NÃO hipoxemia_grave E
    NÃO ha_estagio_3 E
    ha_estagio_2 E
    NÃO hipoxemia_moderada E
    NÃO taquicardia E
    NÃO taquipneia E
    NÃO confusao_mental
    NÃO dificuldade_de_falar E
    NÃO bradicardia E
    NÃO hipotermia E
    NÃO teve_convulsao E
    NÃO bradipneia E
    NÃO febre_alta E
    NÃO hipoxemia_leve E
    NÃO dispneia_em_repouso E
    cianose ENTÃO "Emergência";

SE NÃO hipoxemia_grave E
    NÃO ha_estagio_3 E
    NÃO ha_estagio_2 E
    hipoxemia_moderada E
    taquicardia ENTÃO "Emergência";

SE NÃO hipoxemia_grave E
    NÃO ha_estagio_3 E
    NÃO ha_estagio_2 E
    hipoxemia_moderada E
    NÃO taquicardia E
    taquipneia ENTÃO "Emergência";

SE NÃO hipoxemia_grave E
    NÃO ha_estagio_3 E
    NÃO ha_estagio_2 E
    hipoxemia_moderada E
    NÃO taquicardia E
    NÃO taquipneia E
    confusao_mental ENTÃO "Emergência";

SE NÃO hipoxemia_grave E
    NÃO ha_estagio_3 E
    NÃO ha_estagio_2 E
    hipoxemia_moderada E
    NÃO taquicardia E
    NÃO taquipneia E
    NÃO confusao_mental E
    dificuldade_de_falar ENTÃO "Emergência";

SE NÃO hipoxemia_grave E
    NÃO ha_estagio_3 E
    NÃO ha_estagio_2 E
    hipoxemia_moderada E
    NÃO taquicardia E
    NÃO taquipneia E
    NÃO confusao_mental E
    NÃO dificuldade_de_falar E 
    bradicardia ENTÃO "Emergência";

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
    teve_convulsao ENTÃO "Emergência";

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
    bradipneia ENTÃO "Emergência";

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
    ha_estagio_1 ENTÃO "Emergência";

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
    bradipneia ENTÃO "Emergência";

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
    ha_estagio_1 ENTÃO "Emergência";

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
    febre_alta ENTÃO "Emergência";

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
    febre_alta ENTÃO "Emergência";

SE NÃO hipoxemia_grave E
    NÃO ha_estagio_3 E
    NÃO ha_estagio_2 E
    NÃO hipoxemia_moderada E
    taquicardia E
    taquipneia ENTÃO "Emergência";

SE NÃO hipoxemia_grave E
    NÃO ha_estagio_3 E
    NÃO ha_estagio_2 E
    NÃO hipoxemia_moderada E
    taquicardia E
    NÃO taquipneia E
    confusao_mental ENTÃO "Emergência";

SE NÃO hipoxemia_grave E
    NÃO ha_estagio_3 E
    NÃO ha_estagio_2 E
    NÃO hipoxemia_moderada E
    taquicardia E
    NÃO taquipneia E
    NÃO confusao_mental E
    dificuldade_de_falar ENTÃO "Emergência";

SE NÃO hipoxemia_grave E
    NÃO ha_estagio_3 E
    NÃO ha_estagio_2 E
    NÃO hipoxemia_moderada E
    taquicardia E
    NÃO taquipneia E
    NÃO confusao_mental E
    NÃO dificuldade_de_falar E
    hipotermia ENTÃO "Emergência";

SE NÃO hipoxemia_grave E
    NÃO ha_estagio_3 E
    NÃO ha_estagio_2 E
    NÃO hipoxemia_moderada E
    taquicardia E
    NÃO taquipneia E
    NÃO confusao_mental E
    NÃO dificuldade_de_falar E
    NÃO hipotermia E
    teve_convulsao ENTÃO "Emergência";

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
    ha_estagio_1 ENTÃO "Emergência";

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
    sudorese ENTÃO "Emergência";

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
    dispneia_em_repouso ENTÃO "Emergência";

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
    hipoxemia_leve ENTÃO "Emergência";

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
    cianose ENTÃO "Emergência";

    
SE NÃO hipoxemia_grave E
    NÃO ha_estagio_3 E
    NÃO ha_estagio_2 E
    NÃO hipoxemia_moderada E
    NÃO taquicardia E
    taquipneia E
    confusao_mental ENTÃO "Emergência";

SE NÃO hipoxemia_grave E
    NÃO ha_estagio_3 E
    NÃO ha_estagio_2 E
    NÃO hipoxemia_moderada E
    NÃO taquicardia E
    taquipneia E
    NÃO confusao_mental E
    dificuldade_de_falar E
    bradicardia ENTÃO "Emergência";

SE NÃO hipoxemia_grave E
    NÃO ha_estagio_3 E
    NÃO ha_estagio_2 E
    NÃO hipoxemia_moderada E
    NÃO taquicardia E
    taquipneia E
    NÃO confusao_mental E
    dificuldade_de_falar E
    NÃO bradicardia E
    teve_convulsao ENTÃO "Emergência";


SE NÃO hipoxemia_grave E
    NÃO ha_estagio_3 E
    NÃO ha_estagio_2 E
    NÃO hipoxemia_moderada E
    NÃO taquicardia E
    taquipneia E
    NÃO confusao_mental E
    NÃO dificuldade_de_falar E
    bradicardia E
    hipotermia ENTÃO "Emergência";

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
    teve_convulsao ENTÃO "Emergência";

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
    hipoxemia_leve ENTÃO "Emergência";

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
    cianose ENTÃO "Emergência";

SE NÃO hipoxemia_grave E
    NÃO ha_estagio_3 E
    NÃO ha_estagio_2 E
    NÃO hipoxemia_moderada E
    NÃO taquicardia E
    NÃO taquipneia E
    confusao_mental E
    dificuldade_de_falar ENTÃO "Emergência";

SE NÃO hipoxemia_grave E
    NÃO ha_estagio_3 E
    NÃO ha_estagio_2 E
    NÃO hipoxemia_moderada E
    NÃO taquicardia E
    NÃO taquipneia E
    confusao_mental E
    NÃO dificuldade_de_falar E
    bradicardia ENTÃO "Emergência";

SE NÃO hipoxemia_grave E
    NÃO ha_estagio_3 E
    NÃO ha_estagio_2 E
    NÃO hipoxemia_moderada E
    NÃO taquicardia E
    NÃO taquipneia E
    confusao_mental E
    NÃO dificuldade_de_falar E
    NÃO bradicardia E
    hipotermia ENTÃO "Emergência";

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
    convulsao ENTÃO "Emergência";

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
    bradipneia ENTÃO "Emergência";

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
    febre_alta ENTÃO "Emergência";

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
    ha_estagio_1 ENTÃO "Emergência";

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
    hipoxemia_leve ENTÃO "Emergência";

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
    cianose ENTÃO "Emergência";

SE NÃO hipoxemia_grave E
    NÃO ha_estagio_3 E
    NÃO ha_estagio_2 E
    NÃO hipoxemia_moderada E
    NÃO taquicardia E
    NÃO taquipneia E
    NÃO confusao_mental E
    dificuldade_de_falar E
    bradicardia ENTÃO "Emergência";

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
    convulsao ENTÃO "Emergência";

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
    febre_alta ENTÃO "Emergência";

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
    ha_estagio_1 ENTÃO "Emergência";

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
    hipoxemia_leve ENTÃO "Emergência";

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
    hipoxemia_leve ENTÃO "Emergência";

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
    ha_estagio_1 ENTÃO "Emergência";

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
    hipoxemia_leve ENTÃO "Emergência";

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
    dispneia_em_repouso ENTÃO "Emergência";

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
    cianose ENTÃO "Emergência";

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
    febre_alta ENTÃO "Emergência";

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
    hipoxemia_leve ENTÃO "Emergência";
```
