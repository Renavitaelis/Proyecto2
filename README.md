# Proyecto2
//Ascende os leds em sequência:
    /*
    Vleds = (Vleds == 0)? 
      (1 << 3) : ((Vleds << 1) & (0x1F << 3));
    
    HAL_GPIO_WritePin(GPIOA, 0x1F<<3, 0);
    HAL_GPIO_WritePin(GPIOA, Vleds, 1);*/
    

//Contador Binário de Leds:
    /*HAL_GPIO_WritePin(GPIOA, Vleds<<3, 1);
    HAL_GPIO_WritePin(GPIOA, ~(Vleds)<<3, 0); 
    Vleds++;*/