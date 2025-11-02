```
SE NÃO ha_estagio_3 E
        dispneia_em_repouso E
        NÃO taquipneia E
        NÃO hipoxemia_grave E
        hipoxemia_moderada E
        NÃO ha_estagio_2 E
        NÃO taquicardia E
        NÃO confusao_mental E
        NÃO dificuldade_de_falar E
        NÃO teve_convulsao ENTÃO "Muito urgente";

SE NÃO ha_estagio_3 E
        dispneia_em_repouso E
        NÃO taquipneia E
        NÃO hipoxemia_grave E
        NÃO hipoxemia_moderada E
        hipoxemia_leve E
        NÃO ha_estagio_2
        taquicardia E
        NÃO confusao_mental
        NÃO dificuldade_de_falar ENTÃO "Muito urgente";

SE NÃO ha_estagio_3 E
        dispneia_em_repouso E
        NÃO taquipneia E
        NÃO hipoxemia_grave E
        NÃO hipoxemia_moderada E
        hipoxemia_leve E
        NÃO ha_estagio_2
        NÃO taquicardia E
        confusao_mental E
        NÃO dificuldade_de_falar ENTÃO "Muito urgente";

SE NÃO ha_estagio_3 E
        dispneia_em_repouso E
        NÃO taquipneia E
        NÃO hipoxemia_grave E
        NÃO hipoxemia_moderada E
        hipoxemia_leve E
        NÃO ha_estagio_2
        NÃO taquicardia E
        NÃO confusao_mental E
        dificuldade_de_falar ENTÃO "Muito urgente";

SE NÃO ha_estagio_3 E
        dispneia_em_repouso E
        NÃO taquipneia E
        NÃO hipoxemia_grave E
        NÃO hipoxemia_moderada E
        hipoxemia_leve E
        NÃO ha_estagio_2
        NÃO taquicardia E
        NÃO confusao_mental E
        NÃO dificuldade_de_falar E
        cianose E
        teve_convulsao ENTÃO "Muito urgente";

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
        NÃO teve_convulsao ENTÃO "Muito urgente";

SE NÃO ha_estagio_3 E
        dispneia_em_repouso E
        NÃO taquipneia E
        NÃO hipoxemia_grave E
        NÃO hipoxemia_moderada E
        NÃO hipoxemia_leve E
        NÃO confusao_mental E
        teve_convulsao E
        ha_estagio_2 E
        NÃO taquicardia ENTÃO "Muito urgente";

SE NÃO ha_estagio_3 E
        dispneia_em_repouso E
        NÃO taquipneia E
        NÃO hipoxemia_grave E
        NÃO hipoxemia_moderada E
        NÃO hipoxemia_leve E
        NÃO confusao_mental E
        teve_convulsao E
        NÃO ha_estagio_2 E
        taquicardia ENTÃO "Muito urgente";

SE NÃO ha_estagio_3 E
        dispneia_em_repouso E
        NÃO taquipneia E
        NÃO hipoxemia_grave E
        NÃO hipoxemia_moderada E
        NÃO hipoxemia_leve E
        NÃO confusao_mental E
        NÃO teve_convulsao E
        taquicardia E
        ha_estagio_2 ENTÃO "Muito urgente";
```