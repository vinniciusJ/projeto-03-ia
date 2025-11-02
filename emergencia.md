````
SE ha_estagio_3 ENTÃO "Emergência";

SE NÃO ha_estagio_3 E dispneia_em_repouso E taquipneia ENTÃO "Emergência";

SE NÃO ha_estagio_3 E
        dispneia_em_repouso E
        NÃO taquipneia E
        hipoxemia_grava ENTÃO "Emergência";

SE NÃO ha_estagio_3 E
        dispneia_em_repouso E
        NÃO taquipneia E
        NÃO hipoxemia_grave E
        hipoxemia_moderada E
        ha_estagio_2 ENTÃO "Emergência";

SE NÃO ha_estagio_3 E
        dispneia_em_repouso E
        NÃO taquipneia E
        NÃO hipoxemia_grave E
        hipoxemia_moderada E
        NÃO ha_estagio_2 E
        taquicardia ENTÃO "Emergência";

SE NÃO ha_estagio_3 E
        dispneia_em_repouso E
        NÃO taquipneia E
        NÃO hipoxemia_grave E
        hipoxemia_moderada E
        NÃO ha_estagio_2 E
        NÃO taquicardia E
        confusao_mental ENTÃO "Emergência";

SE NÃO ha_estagio_3 E
        dispneia_em_repouso E
        NÃO taquipneia E
        NÃO hipoxemia_grave E
        hipoxemia_moderada E
        NÃO ha_estagio_2 E
        NÃO taquicardia E
        NÃO confusao_mental E
        dificuldade_de_falar ENTÃO "Emergência";

SE NÃO ha_estagio_3 E
        dispneia_em_repouso E
        NÃO taquipneia E
        NÃO hipoxemia_grave E
        hipoxemia_moderada E
        NÃO ha_estagio_2 E
        NÃO taquicardia E
        NÃO confusao_mental E
        NÃO dificuldade_de_falar E
        teve_convulsao ENTÃO "Emergência";

SE NÃO ha_estagio_3 E
        dispneia_em_repouso E
        NÃO taquipneia E
        NÃO hipoxemia_grave E
        NÃO hipoxemia_moderada E
        hipoxemia_leve E
        ha_estagio_2 ENTÃO "Emergência";

SE NÃO ha_estagio_3 E
        dispneia_em_repouso E
        NÃO taquipneia E
        NÃO hipoxemia_grave E
        NÃO hipoxemia_moderada E
        hipoxemia_leve E
        NÃO ha_estagio_2
        taquicardia E
        confusao_mental ENTÃO "Emergência";

SE NÃO ha_estagio_3 E
        dispneia_em_repouso E
        NÃO taquipneia E
        NÃO hipoxemia_grave E
        NÃO hipoxemia_moderada E
        hipoxemia_leve E
        NÃO ha_estagio_2
        taquicardia E
        NÃO confusao_mental
        dificuldade_de_falar ENTÃO "Emergência";

SE NÃO ha_estagio_3 E
        dispneia_em_repouso E
        NÃO taquipneia E
        NÃO hipoxemia_grave E
        NÃO hipoxemia_moderada E
        hipoxemia_leve E
        NÃO ha_estagio_2
        NÃO taquicardia E
        confusao_mental E
        dificuldade_de_falar ENTÃO "Emergência";

SE NÃO ha_estagio_3 E
        dispneia_em_repouso E
        NÃO taquipneia E
        NÃO hipoxemia_grave E
        NÃO hipoxemia_moderada E
        NÃO hipoxemia_leve E
        confusao_mental E
        ha_estagio_2 ENTÃO "Emergência";

SE NÃO ha_estagio_3 E
        dispneia_em_repouso E
        NÃO taquipneia E
        NÃO hipoxemia_grave E
        NÃO hipoxemia_moderada E
        NÃO hipoxemia_leve E
        confusao_mental E
        NÃO ha_estagio_2 E 
        taquicardia ENTÃO "Emergência";
 
SE NÃO ha_estagio_3 E
        dispneia_em_repouso E
        NÃO taquipneia E
        NÃO hipoxemia_grave E
        NÃO hipoxemia_moderada E
        NÃO hipoxemia_leve E
        confusao_mental E
        NÃO ha_estagio_2 E 
        NÃO taquicardia
        bradicardia ENTÃO "Emergência";      
         
SE NÃO ha_estagio_3 E
        dispneia_em_repouso E
        NÃO taquipneia E
        NÃO hipoxemia_grave E
        NÃO hipoxemia_moderada E
        NÃO hipoxemia_leve E
        confusao_mental E
        NÃO ha_estagio_2 E 
        NÃO taquicardia
        NÃO bradicardia
        dificuldade_de_falar ENTÃO "Emergência";

SE NÃO ha_estagio_3 E
        dispneia_em_repouso E
        NÃO taquipneia E
        NÃO hipoxemia_grave E
        NÃO hipoxemia_moderada E
        NÃO hipoxemia_leve E
        confusao_mental E
        NÃO ha_estagio_2 E 
        NÃO taquicardia
        NÃO bradicardia
        NÃO dificuldade_de_falar
        teve_convulsao ENTÃO "Emergência";

SE NÃO ha_estagio_3 E
        dispneia_em_repouso E
        NÃO taquipneia E
        NÃO hipoxemia_grave E
        NÃO hipoxemia_moderada E
        NÃO hipoxemia_leve E
        NÃO confusao_mental E
        teve_convulsao E
        ha_estagio_2 E
        taquicardia ENTÃO "Emergência";
```