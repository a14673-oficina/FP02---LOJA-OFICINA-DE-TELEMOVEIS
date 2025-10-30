# Infinity Mobile - Loja e Oficina

## Português (Portugal)

### Descrição Geral
Este projeto consiste num website de demonstração para a **Infinity Mobile**, uma empresa que combina uma **Loja** de dispositivos móveis e eletrónicos com um serviço de **Oficina/Reparações** (Assistência Técnica). O website utiliza uma estrutura simples e responsiva para apresentar os produtos, os serviços de reparação e os contactos da empresa.

### Funcionalidades Principais
O website é uma aplicação estática com as seguintes páginas principais:
*   **Início/Loja (`index.html`)**: A página principal que funciona como a loja online. Apresenta uma lista de produtos (principalmente telemóveis Samsung Galaxy) com imagens, descrição básica (tamanho do ecrã, RAM, armazenamento) e preço. Inclui um botão "Carrinho" para simular a adição do produto ao carrinho de compras.
*   **Reparações/Oficina (`oficina.html`)**: Dedicada aos serviços de assistência técnica. Apresenta os tipos de dispositivos que a oficina repara (Telemóvel, PC/Laptops, Tablets, SmartWatch, Som). Inclui um botão "Aqui" para agendar uma reparação, simulando um fluxo de agendamento.
*   **Carrinho (`carrinho.html`)**: A página do carrinho de compras. Exibe um exemplo de produto adicionado ("Galaxy S25") e um botão para "Finalizar a compra", simulando o processo de checkout.
*   **Contacto (`conctatos.html`)**: Apresenta a informação de contacto da loja, incluindo a morada ("Infinity Mobile 1º Avenida" no Braga Parque), telefone, email e horário de funcionamento. Inclui um mapa incorporado (iframe) para a localização.

### Estrutura do Código
O website é construído com HTML e CSS.
*   **Design Responsivo Avançado**: O CSS utiliza **Media Queries** (`@media (min-width: 768px)`, `@media (min-width: 1024px)`) para adaptar o layout (principalmente o número de colunas nos *grids*) para dispositivos Móveis, Tablets e PC, garantindo uma boa experiência de utilizador em diferentes ecrãs.
*   **Estrutura Modular**: Todas as páginas seguem um padrão com cabeçalho (`header`), conteúdo principal (`main`) e rodapé (`footer`).
*   **Estilos Incorporados**: O CSS está incorporado na tag `<style>` de cada ficheiro HTML.
*   **Navegação Consistente**: A barra de navegação no cabeçalho permite o acesso rápido a todas as secções principais: "Loja", "Reparações", "Carrinho" e "Contacto".

### Desafios e Soluções (Futuros de Melhoria)
*   **Separação de Estilos**: O CSS deve ser extraído para um ficheiro externo (`style.css`) para melhorar a **manutenibilidade** do código e evitar a repetição de estilos em cada página.
*   **Funcionalidade Dinâmica**: O website é estático. Para ser funcional, necessitaria de um *backend* para:
    *   Gerir o **inventário** e preços dos produtos.
    *   Implementar a lógica de **carrinho de compras** (adição, remoção, cálculo de totais).
    *   Processar o **agendamento de reparações** e o formulário de contacto.
*   **Validação de Dados**: O nome do ficheiro de contactos está incorreto (`conctatos.html`). Deve ser corrigido para `contactos.html` e os links de navegação ajustados para manter a consistência.

### Como Usar
1.  **Clone o repositório** (assumindo que o código está no GitHub).
2.  **Abra o ficheiro `index.html`** no seu navegador para iniciar a navegação.
3.  **Explore** as diferentes secções: "Loja" (por defeito), "Reparações", "Carrinho" e "Contacto" através do menu no cabeçalho.

---

# Infinity Mobile - Store and Workshop

## English

### Overview
This project is a demonstration website for **Infinity Mobile**, a company that combines a **Store** for mobile and electronic devices with a **Workshop/Repair Shop** (Technical Assistance) service. The website uses a simple and responsive structure to present the products, repair services, and company contact information.

### Main Features
The website is a static application with the following main pages:
*   **Home/Store (`index.html`)**: The main page that functions as the online store. It displays a list of products (mainly Samsung Galaxy phones) with images, basic description (screen size, RAM, storage), and price. It includes an "Add to Cart" button to simulate adding the product to the shopping cart.
*   **Repairs/Workshop (`oficina.html`)**: Dedicated to technical assistance services. It presents the types of devices the workshop repairs (Mobile Phone, PC/Laptops, Tablets, SmartWatch, Audio). It includes an "Aqui" (Here) button to schedule a repair, simulating a scheduling flow.
*   **Cart (`carrinho.html`)**: The shopping cart page. It displays an example of an added product ("Galaxy S25") and a "Finalizar a compra" (Finalize Purchase) button, simulating the checkout process.
*   **Contact (`conctatos.html`)**: Presents the store's contact information, including the address ("Infinity Mobile 1º Avenida" at Braga Parque), phone, email, and operating hours. It includes an embedded map (iframe) for the location.

### Code Structure
The website is built with HTML and CSS.
*   **Advanced Responsive Design**: The CSS uses **Media Queries** (`@media (min-width: 768px)`, `@media (min-width: 1024px)`) to adapt the layout (mainly the number of columns in the *grids*) for Mobile, Tablet, and PC devices, ensuring a good user experience on different screens.
*   **Modular Structure**: All pages follow a pattern with a header, main content, and footer.
*   **Embedded Styles**: The CSS is embedded within the `<style>` tag of each HTML file.
*   **Consistent Navigation**: The navigation bar in the header allows quick access to all main sections: "Store", "Repairs", "Cart", and "Contact".

### Challenges and Solutions (Future Improvements)
*   **Style Separation**: The CSS should be extracted to an external file (`style.css`) to improve code **maintainability** and avoid repeating styles on every page.
*   **Dynamic Functionality**: The website is static. To be functional, it would require a *backend* to:
    *   Manage product **inventory** and prices.
    *   Implement the **shopping cart** logic (adding, removing, calculating totals).
    *   Process **repair scheduling** and the contact form.
*   **Data Validation**: The contact file name is misspelled (`conctatos.html`). It should be corrected to `contactos.html` and the navigation links adjusted to maintain consistency.

### How to Use
1.  **Clone the repository** (assuming the code is on GitHub).
2.  **Open the `index.html` file** in your browser to start navigation.
3.  **Explore** the different sections: "Store" (default), "Repairs", "Cart", and "Contact" through the menu in the header.
