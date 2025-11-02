```
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
        NÃO teve_convulsao ENTÃO "Urgente";

SE NÃO ha_estagio_3 E
        dispneia_em_repouso E
        NÃO taquipneia E
        NÃO hipoxemia_grave E
        NÃO hipoxemia_moderada E
        NÃO hipoxemia_leve E
        NÃO confusao_mental E
        teve_convulsao E
        NÃO ha_estagio_2 E
        NÃO taquicardia ENTÃO "Urgente";

SE NÃO ha_estagio_3 E
        dispneia_em_repouso E
        NÃO taquipneia E
        NÃO hipoxemia_grave E
        NÃO hipoxemia_moderada E
        NÃO hipoxemia_leve E
        NÃO confusao_mental E
        NÃO teve_convulsao E
        taquicardia E
        NÃO ha_estagio_2 ENTÃO "Urgente";

SE NÃO ha_estagio_3 E
        dispneia_em_repouso E
        NÃO taquipneia E
        NÃO hipoxemia_grave E
        NÃO hipoxemia_moderada E
        NÃO hipoxemia_leve E
        NÃO confusao_mental E
        NÃO teve_convulsao E
        NÃO taquicardia E
        ha_estagio_2 ENTÃO "Urgente";
```