# Agradecimentos

Tudo bem?

Venho de antemão agradecer a oportunidade. Não consegui completar o desafio 100% (ainda está bem quebrado 😅). A ideia para o projeto era permitir a consulta do endereço do usuário a partir de um CEP, logradouro, cidade ou bairro. A implementação está apenas com a parte de busca por CEP, faltando a parte de logradouro, cidade ou bairro. Além disso, há um bug no front-end relacionado a cache que não permite que o usuário realize um GET da mesma chamada mais de uma vez. Os próximos passos seriam a resolução e implementação desses problemas, e então o próximo ponto de melhoria no back-end seria acessar a localização através do IP do usuário.

No front-end, foram utilizados o Context e o `useEffect` para as requisições. Por se tratar de uma aplicação pequena, creio que o Context daria conta sem gerar perda de performance. A utilização do `useEffect` foi por uma questão de tempo, já que preferiria utilizar o React Query para tratar questões de cache e otimizar as requisições da aplicação.

No back-end, utilizei o SQLite por ser adequado para um contexto sem muita complexidade e por sua conveniência na criação de um banco de dados.

## Melhorias no Front-End

### Dark/Light Mode

- **Conforto Visual**: O modo escuro pode reduzir o cansaço ocular em ambientes com pouca luz, enquanto o modo claro é mais confortável em ambientes bem iluminados.
- **Economia de Energia**: Em telas OLED e AMOLED, o modo escuro pode ajudar a economizar bateria, já que os pixels pretos consomem menos energia.
- **Personalização**: Permitir que os usuários escolham entre os modos pode melhorar a experiência de uso e a satisfação geral com o site.
- **Acessibilidade**: Oferecer ambos os modos pode tornar o site mais acessível a pessoas com diferentes preferências e necessidades visuais.

## Links

- [Frontend](https://github.com/ConsultCEP/consultation_cep)
- [Backend](https://github.com/ConsultCEP/consultation_cep_back)
