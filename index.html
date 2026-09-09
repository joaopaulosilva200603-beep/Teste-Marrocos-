<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Delivery - Cardápio Digital</title>
    <style>
        :root {
            --primary: #e63946;
            --primary-dark: #c1121f;
            --bg: #f8f9fa;
            --text: #212529;
            --gray: #6c757d;
            --light-gray: #e9ecef;
            --success: #2a9d8f;
        }

        * {
            box-sizing: border-box;
            margin: 0;
            padding: 0;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
        }

        body {
            background-color: var(--bg);
            color: var(--text);
            padding-bottom: 90px;
        }

        header {
            background-color: var(--primary);
            color: white;
            padding: 20px;
            text-align: center;
            box-shadow: 0 4px 6px rgba(0,0,0,0.1);
        }

        header h1 {
            font-size: 1.5rem;
            margin-bottom: 5px;
        }

        header p {
            font-size: 0.9rem;
            opacity: 0.9;
        }

        .categories {
            display: flex;
            gap: 10px;
            padding: 15px;
            overflow-x: auto;
            background: white;
            box-shadow: 0 2px 4px rgba(0,0,0,0.05);
            position: sticky;
            top: 0;
            z-index: 10;
        }

        .category-btn {
            background: var(--light-gray);
            border: none;
            padding: 8px 16px;
            border-radius: 20px;
            font-size: 0.9rem;
            font-weight: 600;
            color: var(--gray);
            cursor: pointer;
            white-space: nowrap;
            transition: all 0.3s;
        }

        .category-btn.active {
            background: var(--primary);
            color: white;
        }

        .container {
            max-width: 800px;
            margin: 0 auto;
            padding: 15px;
        }

        .section-title {
            font-size: 1.2rem;
            margin: 20px 0 10px 0;
            color: var(--text);
            border-left: 4px solid var(--primary);
            padding-left: 8px;
        }

        .product-grid {
            display: grid;
            grid-template-columns: 1fr;
            gap: 15px;
        }

        @media(min-width: 600px) {
            .product-grid {
                grid-template-columns: repeat(2, 1fr);
            }
        }

        .product-card {
            background: white;
            border-radius: 12px;
            overflow: hidden;
            box-shadow: 0 2px 8px rgba(0,0,0,0.05);
            display: flex;
            flex-direction: column;
            cursor: pointer;
            transition: transform 0.2s;
        }

        .product-card:hover {
            transform: translateY(-3px);
        }

        .product-img {
            width: 100%;
            height: 140px;
            object-fit: cover;
            background-color: var(--light-gray);
        }

        .product-info {
            padding: 12px;
            display: flex;
            flex-direction: column;
            flex-grow: 1;
            justify-content: space-between;
        }

        .product-title {
            font-size: 1rem;
            font-weight: bold;
            margin-bottom: 4px;
        }

        .product-desc {
            font-size: 0.8rem;
            color: var(--gray);
            margin-bottom: 8px;
            display: -webkit-box;
            -webkit-line-clamp: 2;
            -webkit-box-orient: vertical;
            overflow: hidden;
        }

        .product-footer {
            display: flex;
            justify-content: space-between;
            align-items: center;
            margin-top: 8px;
        }

        .product-price {
            font-weight: bold;
            color: var(--primary-dark);
            font-size: 1rem;
        }

        .btn-add-mini {
            background: var(--primary);
            color: white;
            border: none;
            padding: 6px 12px;
            border-radius: 6px;
            font-size: 0.8rem;
            font-weight: bold;
        }

        /* Modal de Personalização (Estilo Mc Donald's) */
        .modal-overlay {
            position: fixed;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            background: rgba(0,0,0,0.6);
            display: none;
            justify-content: center;
            align-items: flex-end;
            z-index: 100;
        }

        .modal-overlay.active {
            display: flex;
        }

        .modal-content {
            background: white;
            width: 100%;
            max-width: 600px;
            max-height: 90vh;
            border-radius: 20px 20px 0 0;
            padding: 20px;
            overflow-y: auto;
            animation: slideUp 0.3s ease;
        }

        @keyframes slideUp {
            from { transform: translateY(100%); }
            to { transform: translateY(0); }
        }

        .modal-header {
            display: flex;
            justify-content: space-between;
            align-items: center;
            margin-bottom: 15px;
        }

        .modal-close {
            background: var(--light-gray);
            border: none;
            width: 30px;
            height: 30px;
            border-radius: 50%;
            font-weight: bold;
            cursor: pointer;
        }

        .modal-img {
            width: 100%;
            height: 180px;
            object-fit: cover;
            border-radius: 10px;
            margin-bottom: 15px;
        }

        .customization-group {
            margin-bottom: 15px;
        }

        .customization-title {
            font-weight: bold;
            font-size: 0.95rem;
            margin-bottom: 8px;
            color: var(--text);
        }

        .checkbox-label {
            display: flex;
            align-items: center;
            gap: 10px;
            padding: 8px 0;
            font-size: 0.9rem;
            border-bottom: 1px solid var(--light-gray);
            cursor: pointer;
        }

        .checkbox-label input {
            width: 18px;
            height: 18px;
            accent-color: var(--primary);
        }

        .modal-footer {
            margin-top: 20px;
            display: flex;
            gap: 10px;
            align-items: center;
        }

        .quantity-control {
            display: flex;
            align-items: center;
            border: 1px solid var(--light-gray);
            border-radius: 8px;
            overflow: hidden;
        }

        .quantity-control button {
            background: var(--light-gray);
            border: none;
            padding: 10px 15px;
            font-weight: bold;
            cursor: pointer;
        }

        .quantity-control span {
            padding: 0 15px;
            font-weight: bold;
        }

        .btn-confirm-add {
            flex-grow: 1;
            background: var(--primary);
            color: white;
            border: none;
            padding: 12px;
            border-radius: 8px;
            font-weight: bold;
            font-size: 1rem;
            cursor: pointer;
        }

        /* Barra Inferior do Carrinho */
        .cart-bar {
            position: fixed;
            bottom: 0;
            left: 0;
            width: 100%;
            background: white;
            box-shadow: 0 -4px 10px rgba(0,0,0,0.1);
            padding: 15px 20px;
            display: flex;
            justify-content: space-between;
            align-items: center;
            z-index: 50;
            display: none;
        }

        .cart-bar.active {
            display: flex;
        }

        .cart-info span {
            display: block;
            font-size: 0.8rem;
            color: var(--gray);
        }

        .cart-info strong {
            font-size: 1.1rem;
            color: var(--text);
        }

        .btn-checkout {
            background: var(--success);
            color: white;
            border: none;
            padding: 10px 20px;
            border-radius: 8px;
            font-weight: bold;
            font-size: 0.95rem;
            cursor: pointer;
        }
    </style>
</head>
<body>

    <header>
        <h1>🍔 Delivery Express</h1>
        <p>Escolha seus pratos e monte do seu jeito!</p>
    </header>

    <div class="categories" id="categoriesContainer">
        <button class="category-btn active" onclick="filterCategory('todos', this)">Todos</button>
        <button class="category-btn" onclick="filterCategory('xis', this)">Xis & Lanches</button>
        <button class="category-btn" onclick="filterCategory('porcoes', this)">Porções</button>
        <button class="category-btn" onclick="filterCategory('bebidas', this)">Bebidas</button>
    </div>

    <div class="container">
        <div id="productContainer" class="product-grid">
            <!-- Os produtos entram aqui via JavaScript -->
        </div>
    </div>

    <!-- Modal de Customização -->
    <div class="modal-overlay" id="productModal">
        <div class="modal-content">
            <div class="modal-header">
                <h3 id="modalProductName">Nome do Produto</h3>
                <button class="modal-close" onclick="closeModal()">✕</button>
            </div>
            <img id="modalProductImg" class="modal-img" src="" alt="Produto">
            <p id="modalProductDesc" style="color: var(--gray); font-size: 0.9rem; margin-bottom: 15px;"></p>

            <div id="customizationSection">
                <div class="customization-group">
                    <div class="customization-title">O que deseja retirar? (Sem custo)</div>
                    <div id="removableItemsList">
                        <!-- Itens removíveis injetados aqui -->
                    </div>
                </div>
            </div>

            <div class="modal-footer">
                <div class="quantity-control">
                    <button onclick="changeModalQty(-1)">-</button>
                    <span id="modalQty">1</span>
                    <button onclick="changeModalQty(1)">+</button>
                </div>
                <button class="btn-confirm-add" onclick="confirmAddToCart()">Adicionar R$ <span id="modalTotalPrice">0,00</span></button>
            </div>
        </div>
    </div>

    <!-- Barra do Carrinho -->
    <div class="cart-bar" id="cartBar">
        <div class="cart-info">
            <span id="cartItemCount">0 itens no carrinho</span>
            <strong id="cartTotalPrice">R$ 0,00</strong>
        </div>
        <button class="btn-checkout" onclick="openCheckout()">Ver Carrinho / Pedir</button>
    </div>

    <script>
        // Banco de Dados de Produtos com Fotos e Ingredientes Removíveis
        const products = [
            {
                id: 1,
                category: 'xis',
                name: 'Xis Bacon Especial',
                price: 32.00,
                desc: 'Pão, bife de carne artesanal, queijo cheddar cremoso, bacon crocante, alface e tomate.',
                img: 'https://images.unsplash.com/photo-1568901346375-23c9450c58cd?auto=format&fit=crop&w=500&q=80',
                removables: ['Alface', 'Tomate', 'Maionese da casa']
            },
            {
                id: 2,
                category: 'xis',
                name: 'Xis Salada Completo',
                price: 28.00,
                desc: 'Pão macio, bife, queijo prato derretido, presunto, ovo, milho, ervilha, alface e tomate.',
                img: 'https://images.unsplash.com/photo-1550547660-d9450f859349?auto=format&fit=crop&w=500&q=80',
                removables: ['Milho', 'Ervilha', 'Alface', 'Tomate', 'Ovo']
            },
            {
                id: 3,
                category: 'porcoes',
                name: 'Porção de Fritas com Bacon e Cheddar',
                price: 35.00,
                desc: 'Batatas fritas sequinhas cobertas com muito cheddar cremoso e cubos de bacon.',
                img: 'https://images.unsplash.com/photo-1573080496219-bb080dd4f877?auto=format&fit=crop&w=500&q=80',
                removables: []
            },
            {
                id: 4,
                category: 'bebidas',
                name: 'Coca-Cola 2 Litros',
                price: 12.00,
                desc: 'Garrafa 2L gelada.',
                img: 'https://images.unsplash.com/photo-1622483767028-3f66f32aef97?auto=format&fit=crop&w=500&q=80',
                removables: []
            }
        ];

        let cart = [];
        let currentProduct = null;
        let currentQty = 1;

        function renderProducts(filter = 'todos') {
            const container = document.getElementById('productContainer');
            container.innerHTML = '';

            const filtered = filter === 'todos' ? products : products.filter(p => p.category === filter);

            filtered.forEach(product => {
                container.innerHTML += `
                    <div class="product-card" onclick="openProductModal(${product.id})">
                        <img class="product-img" src="${product.img}" alt="${product.name}">
                        <div class="product-info">
                            <div>
                                <div class="product-title">${product.name}</div>
                                <div class="product-desc">${product.desc}</div>
                            </div>
                            <div class="product-footer">
                                <span class="product-price">R$ ${product.price.toFixed(2).replace('.', ',')}</span>
                                <button class="btn-add-mini">Pedir</button>
                            </div>
                        </div>
                    </div>
                `;
            });
        }

        function filterCategory(category, btn) {
            document.querySelectorAll('.category-btn').forEach(b => b.classList.remove('active'));
            btn.classList.add('active');
            renderProducts(category);
        }

        function openProductModal(id) {
            currentProduct = products.find(p => p.id === id);
            currentQty = 1;

            document.getElementById('modalProductName').innerText = currentProduct.name;
            document.getElementById('modalProductImg').src = currentProduct.img;
            document.getElementById('modalProductDesc').innerText = currentProduct.desc;
            document.getElementById('modalQty').innerText = currentQty;

            // Renderizar itens removíveis (estilo McDonald's)
            const removableContainer = document.getElementById('removableItemsList');
            const section = document.getElementById('customizationSection');
            removableContainer.innerHTML = '';

            if (currentProduct.removables && currentProduct.removables.length > 0) {
                section.style.display = 'block';
                currentProduct.removables.forEach((item, index) => {
                    removableContainer.innerHTML += `
                        <label class="checkbox-label">
                            <input type="checkbox" value="${item}" id="removable_${index}">
                            Sem ${item}
                        </label>
                    `;
                });
            } else {
                section.style.display = 'none';
            }

            updateModalTotal();
            document.getElementById('productModal').classList.add('active');
        }

        function closeModal() {
            document.getElementById('productModal').classList.remove('active');
        }

        function changeModalQty(change) {
            if (currentQty + change >= 1) {
                currentQty += change;
                document.getElementById('modalQty').innerText = currentQty;
                updateModalTotal();
            }
        }

        function updateModalTotal() {
            const total = currentProduct.price * currentQty;
            document.getElementById('modalTotalPrice').innerText = total.toFixed(2).replace('.', ',');
        }

        function confirmAddToCart() {
            // Capturar o que o cliente marcou para tirar
            let removedItems = [];
            if (currentProduct.removables) {
                currentProduct.removables.forEach((item, index) => {
                    const checkbox = document.getElementById(`removable_${index}`);
                    if (checkbox && checkbox.checked) {
                        removedItems.push(`Sem ${item}`);
                    }
                });
            }

            cart.push({
                name: currentProduct.name,
                price: currentProduct.price,
                qty: currentQty,
                removals: removedItems
            });

            closeModal();
            updateCartBar();
        }

        function updateCartBar() {
            const cartBar = document.getElementById('cartBar');
            if (cart.length > 0) {
                cartBar.classList.add('active');
                const totalItems = cart.reduce((sum, item) => sum + item.qty, 0);
                const totalPrice = cart.reduce((sum, item) => sum + (item.price * item.qty), 0);

                document.getElementById('cartItemCount').innerText = `${totalItems} ${totalItems === 1 ? 'item' : 'itens'} no carrinho`;
                document.getElementById('cartTotalPrice').innerText = `R$ ${totalPrice.toFixed(2).replace('.', ',')}`;
            } else {
                cartBar.classList.remove('active');
            }
        }

        function openCheckout() {
            let message = "Olá! Gostaria de fazer o seguinte pedido:%0A%0A";
            let total = 0;

            cart.forEach((item, index) => {
                let subtotal = item.price * item.qty;
                total += subtotal;
                message += `*${item.qty}x ${item.name}* - R$ ${subtotal.toFixed(2).replace('.', ',')}%0A`;
                
                if (item.removals && item.removals.length > 0) {
                    message += `   _Obs: ${item.removals.join(', ')}_%0A`;
                }
            });

            message += `%0A*Total dos Produtos: R$ ${total.toFixed(2).replace('.', ',')}*`;
            message += `%0A%0A*Endereço de Entrega:* [Digite seu endereço aqui]`;

            // Substitua pelo seu número de WhatsApp
            const phone = "5554999999999"; 
            window.open(`https://wa.me/${phone}?text=${message}`, '_blank');
        }

        // Inicializar a página
        renderProducts();
    </script>
</body>
</html>
