```
1 - SE hipoxemia_grave ENTÃO "Emergência";

2 - SE NÃO hipoxemia_grave E
    ha_estagio_3 ENTÃO "Emergência";

3 - SE NÃO hipoxemia_grave E
    NÃO ha_estagio_3 E
    ha_estagio_2 E
    hipoxemia_moderada ENTÃO "Emergência";

4 - SE NÃO hipoxemia_grave E
    NÃO ha_estagio_3 E
    ha_estagio_2 E
    NÃO hipoxemia_moderada E
    taquicardia ENTÃO "Emergência";

5 - SE NÃO hipoxemia_grave E
    NÃO ha_estagio_3 E
    ha_estagio_2 E
    NÃO hipoxemia_moderada E
    NÃO taquicardia E
    taquipneia ENTÃO "Emergência";

6 - SE NÃO hipoxemia_grave E
    NÃO ha_estagio_3 E
    ha_estagio_2 E
    NÃO hipoxemia_moderada E
    NÃO taquicardia E
    NÃO taquipneia E
    confusao_mental ENTÃO "Emergência";

7 - SE NÃO hipoxemia_grave E
    NÃO ha_estagio_3 E
    ha_estagio_2 E
    NÃO hipoxemia_moderada E
    NÃO taquicardia E
    NÃO taquipneia E
    NÃO confusao_mental
    dificuldade_de_falar ENTÃO "Emergência";

8 - SE NÃO hipoxemia_grave E
    NÃO ha_estagio_3 E
    ha_estagio_2 E
    NÃO hipoxemia_moderada E
    NÃO taquicardia E
    NÃO taquipneia E
    NÃO confusao_mental
    NÃO dificuldade_de_falar
    bradicardia ENTÃO "Emergência";

9 - SE NÃO hipoxemia_grave E
    NÃO ha_estagio_3 E
    ha_estagio_2 E
    NÃO hipoxemia_moderada E
    NÃO taquicardia E
    NÃO taquipneia E
    NÃO confusao_mental E
    NÃO dificuldade_de_falar E
    NÃO bradicardia E
    hipotermia ENTÃO "Emergência";

10 - SE NÃO hipoxemia_grave E
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

11 - SE NÃO hipoxemia_grave E
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

12 - SE NÃO hipoxemia_grave E
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

13 - SE NÃO hipoxemia_grave E
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

14 - SE NÃO hipoxemia_grave E
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

15 - SE NÃO hipoxemia_grave E
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

16 - SE NÃO hipoxemia_grave E
    NÃO ha_estagio_3 E
    NÃO ha_estagio_2 E
    hipoxemia_moderada E
    taquicardia ENTÃO "Emergência";

17 - SE NÃO hipoxemia_grave E
    NÃO ha_estagio_3 E
    NÃO ha_estagio_2 E
    hipoxemia_moderada E
    NÃO taquicardia E
    taquipneia ENTÃO "Emergência";

18 - SE NÃO hipoxemia_grave E
    NÃO ha_estagio_3 E
    NÃO ha_estagio_2 E
    hipoxemia_moderada E
    NÃO taquicardia E
    NÃO taquipneia E
    confusao_mental ENTÃO "Emergência";

19 - SE NÃO hipoxemia_grave E
    NÃO ha_estagio_3 E
    NÃO ha_estagio_2 E
    hipoxemia_moderada E
    NÃO taquicardia E
    NÃO taquipneia E
    NÃO confusao_mental E
    dificuldade_de_falar ENTÃO "Emergência";

20 - SE NÃO hipoxemia_grave E
    NÃO ha_estagio_3 E
    NÃO ha_estagio_2 E
    hipoxemia_moderada E
    NÃO taquicardia E
    NÃO taquipneia E
    NÃO confusao_mental E
    NÃO dificuldade_de_falar E 
    bradicardia ENTÃO "Emergência";

21 - SE NÃO hipoxemia_grave E
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

22 - SE NÃO hipoxemia_grave E
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

23 - SE NÃO hipoxemia_grave E
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

24 - SE NÃO hipoxemia_grave E
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

25 - SE NÃO hipoxemia_grave E
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

26 - SE NÃO hipoxemia_grave E
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

<!-- 27 - SE NÃO hipoxemia_grave E
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
    febre_alta ENTÃO "Emergência"; -->

27 - SE NÃO hipoxemia_grave E
    NÃO ha_estagio_3 E
    NÃO ha_estagio_2 E
    NÃO hipoxemia_moderada E
    taquicardia E
    taquipneia ENTÃO "Emergência";

28 - SE NÃO hipoxemia_grave E
    NÃO ha_estagio_3 E
    NÃO ha_estagio_2 E
    NÃO hipoxemia_moderada E
    taquicardia E
    NÃO taquipneia E
    confusao_mental ENTÃO "Emergência";

29 - SE NÃO hipoxemia_grave E
    NÃO ha_estagio_3 E
    NÃO ha_estagio_2 E
    NÃO hipoxemia_moderada E
    taquicardia E
    NÃO taquipneia E
    NÃO confusao_mental E
    dificuldade_de_falar ENTÃO "Emergência";

30 - SE NÃO hipoxemia_grave E
    NÃO ha_estagio_3 E
    NÃO ha_estagio_2 E
    NÃO hipoxemia_moderada E
    taquicardia E
    NÃO taquipneia E
    NÃO confusao_mental E
    NÃO dificuldade_de_falar E
    hipotermia ENTÃO "Emergência";

31 - SE NÃO hipoxemia_grave E
    NÃO ha_estagio_3 E
    NÃO ha_estagio_2 E
    NÃO hipoxemia_moderada E
    taquicardia E
    NÃO taquipneia E
    NÃO confusao_mental E
    NÃO dificuldade_de_falar E
    NÃO hipotermia E
    teve_convulsao ENTÃO "Emergência";

32 - SE NÃO hipoxemia_grave E
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

33 - SE NÃO hipoxemia_grave E
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

34 - SE NÃO hipoxemia_grave E
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

35 - SE NÃO hipoxemia_grave E
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

36 - SE NÃO hipoxemia_grave E
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

    
37 - SE NÃO hipoxemia_grave E
    NÃO ha_estagio_3 E
    NÃO ha_estagio_2 E
    NÃO hipoxemia_moderada E
    NÃO taquicardia E
    taquipneia E
    confusao_mental ENTÃO "Emergência";

38 - SE NÃO hipoxemia_grave E
    NÃO ha_estagio_3 E
    NÃO ha_estagio_2 E
    NÃO hipoxemia_moderada E
    NÃO taquicardia E
    taquipneia E
    NÃO confusao_mental E
    dificuldade_de_falar E
    bradicardia ENTÃO "Emergência";

39 - SE NÃO hipoxemia_grave E
    NÃO ha_estagio_3 E
    NÃO ha_estagio_2 E
    NÃO hipoxemia_moderada E
    NÃO taquicardia E
    taquipneia E
    NÃO confusao_mental E
    dificuldade_de_falar E
    NÃO bradicardia E
    teve_convulsao ENTÃO "Emergência";


40 - SE NÃO hipoxemia_grave E
    NÃO ha_estagio_3 E
    NÃO ha_estagio_2 E
    NÃO hipoxemia_moderada E
    NÃO taquicardia E
    taquipneia E
    NÃO confusao_mental E
    NÃO dificuldade_de_falar E
    bradicardia E
    hipotermia ENTÃO "Emergência";

41 - SE NÃO hipoxemia_grave E
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

42 - SE NÃO hipoxemia_grave E
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

43 - SE NÃO hipoxemia_grave E
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

44 - SE NÃO hipoxemia_grave E
    NÃO ha_estagio_3 E
    NÃO ha_estagio_2 E
    NÃO hipoxemia_moderada E
    NÃO taquicardia E
    NÃO taquipneia E
    confusao_mental E
    dificuldade_de_falar ENTÃO "Emergência";

45 - SE NÃO hipoxemia_grave E
    NÃO ha_estagio_3 E
    NÃO ha_estagio_2 E
    NÃO hipoxemia_moderada E
    NÃO taquicardia E
    NÃO taquipneia E
    confusao_mental E
    NÃO dificuldade_de_falar E
    bradicardia ENTÃO "Emergência";

46 - SE NÃO hipoxemia_grave E
    NÃO ha_estagio_3 E
    NÃO ha_estagio_2 E
    NÃO hipoxemia_moderada E
    NÃO taquicardia E
    NÃO taquipneia E
    confusao_mental E
    NÃO dificuldade_de_falar E
    NÃO bradicardia E
    hipotermia ENTÃO "Emergência";

47 - SE NÃO hipoxemia_grave E
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

48 - SE NÃO hipoxemia_grave E
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

49 - SE NÃO hipoxemia_grave E
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

50 - SE NÃO hipoxemia_grave E
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

51 - SE NÃO hipoxemia_grave E
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

52 - SE NÃO hipoxemia_grave E
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

53 - SE NÃO hipoxemia_grave E
    NÃO ha_estagio_3 E
    NÃO ha_estagio_2 E
    NÃO hipoxemia_moderada E
    NÃO taquicardia E
    NÃO taquipneia E
    NÃO confusao_mental E
    dificuldade_de_falar E
    bradicardia ENTÃO "Emergência";

54 - SE NÃO hipoxemia_grave E
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

55 - SE NÃO hipoxemia_grave E
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

56 - SE NÃO hipoxemia_grave E
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

57 - SE NÃO hipoxemia_grave E
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

58 - SE NÃO hipoxemia_grave E
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

59 - SE NÃO hipoxemia_grave E
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

60 - SE NÃO hipoxemia_grave E
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

61 - SE NÃO hipoxemia_grave E
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

62 - SE NÃO hipoxemia_grave E
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

63 - SE NÃO hipoxemia_grave E
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

64 - SE NÃO hipoxemia_grave E
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
