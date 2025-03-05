# HTML-E-CSS-CABE-ALHO
1) Adicionando um subtítulo à página
 
 <div class="aprensentacao_links">
    <h2>Acesse minhas redes:</h2><a class="apresentacao__links__link" href="https://www.instagram.com/eleazarlima._/">Instagram</a>
    <a class="apresentacao__links__link" href="https://github.com/Ele703">Github</a>
    <a class="apresentacao__links__link" href="https://www.linkedin.com/in/eleazar-de-moraes-lima-6aa613318/"
	   
2) Alterando a disposição dos elementos com Flexbox
	   
.apresentacao__links {
    display: flex;
    flex-direction: column;
    justify-content: space-between;
}
	
3) Ajustando o alinhamento e o espaçamento dos elementos

	.apresentacao__links {
    display: flex;
    flex-direction: column;
    justify-content: space-between;
    align-items: center;
    gap: 32px;
}
	 
4) 
	

<h2 class="apresentacao__links__subtitulo">Acesse minhas redes:</h2>

5) Estilizando o subtítulo

.apresentacao__links__subtitulo {
    font-family: 'Krona One', sans-serif;
    font-weight: 400;
    font-size: 24px;
}

6) Modificando o estilo dos botões

.apresentacao__links__link {
    /* background-color: #22D4FD; */ /* Código comentado */
    border: 2px solid #22D4FD;
    color: #F6F6F6;
    width: 378px;
    border-radius: 8px;
    /* Outras propriedades existentes permanecem inalteradas */
}


