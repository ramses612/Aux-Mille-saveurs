<!DOCTYPE html>
<html lang="fr">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>Aux Mille saveurs — Commander</title></b>
  <style>
    :root{--accent:#e76f51;--dark:#1f2733;--muted:#6b7280;--card:#ffffff;font-family:Inter, system-ui, -apple-system,"Segoe UI",Roboto,Arial}{box-sizing:border-box}html,body{height:75%}body{margin:0;background:linear-gradient(180deg,#fbfbfc,#f1f5f9);color:var(--dark);line-height:1.6;font-size:16px;padding:0 8px}p{margin:0 0 1.1em 0}header{position:relative;height:56vh;min-height:420px;display:flex;align-items:center;justify-content:center;background:linear-gradient(180deg, rgba(31,39,51,0.45), rgba(31,39,51,0.12)), url('https://images.unsplash.com/photo-1600891964599-f61ba0e24092?q=80&w=1600&auto=format&fit=crop') center/cover no-repeat;color:white;padding:28px} .hero{width:95%;max-width:1200px;display:flex;gap:34px;align-items:center} .brand{flex:1;backdrop-filter:blur(6px);background:linear-gradient(180deg, rgba(255,255,255,0.06), rgba(255,255,255,0.03));padding:34px;border-radius:14px;box-shadow:0 12px 36px rgba(15,23,42,0.22)} .brand h1{margin:0 0 8px 0;font-size:36px;letter-spacing:0.2px} .cta{display:flex;gap:14px;align-items:center} .cta button{background:var(--accent);color:white;border:0;padding:12px 18px;border-radius:12px;cursor:pointer;font-weight:700} main{width:95%;max-width:1200px;margin:-56px auto 72px;display:grid;grid-template-columns:1fr 380px;gap:28px;align-items:start} .menu{background:var(--card);padding:26px;border-radius:14px;box-shadow:0 12px 28px rgba(15,23,42,0.06)} .grid{display:grid;grid-template-columns:repeat(auto-fill,minmax(240px,1fr));gap:18px} .dish{background:linear-gradient(180deg,#fff,#fbfbfd);border-radius:12px;overflow:hidden;display:flex;flex-direction:column;border:1px solid rgba(15,23,42,0.04)} .dish img{width:100%;height:160px;object-fit:cover} .dish-body{padding:16px;display:flex;flex-direction:column;gap:10px} .dish h4{margin:0;font-size:17px} .dish p{margin:0;color:var(--muted);font-size:14px} .dish .meta{display:flex;justify-content:space-between;align-items:center;margin-top:8px} .dish button{background:var(--dark);color:white;border:0;padding:9px 12px;border-radius:10px;cursor:pointer} .cart{position:sticky;top:22px;background:linear-gradient(180deg,var(--card),#fff);padding:22px;border-radius:14px;border:1px solid rgba(15,23,42,0.04);box-shadow:0 12px 36px rgba(15,23,42,0.05)} .cart h3{margin:0 0 12px 0} .cart-list{display:flex;flex-direction:column;gap:12px;max-height:360px;overflow:auto;padding-right:6px} .item{display:flex;gap:14px;align-items:center} .qty{display:flex;gap:8px;align-items:center} .qty button{width:34px;height:34px;border-radius:8px;border:1px solid rgba(15,23,42,0.06);background:white;cursor:pointer} .total{display:flex;justify-content:space-between;margin-top:14px;font-weight:700;font-size:17px} .checkout{margin-top:14px;display:flex;gap:12px;flex-direction:column} .checkout button{background:var(--accent);color:white;border:0;padding:12px 14px;border-radius:10px;cursor:pointer;font-weight:800} .note{font-size:14px;color:var(--muted);margin-top:10px} footer{text-align:center;color:var(--muted);margin:48px 0 96px} #order-modal,#receipt-modal{display:none;position:fixed;inset:0;background:rgba(8,11,15,0.45);align-items:center;justify-content:center;padding:20px} .modal-card{background:white;border-radius:14px;max-width:780px;width:100%;padding:20px;box-shadow:0 24px 70px rgba(15,23,42,0.35)} .receipt{background:#fafafa;border-radius:10px;padding:14px;border:1px solid #eee;font-family:monospace;font-size:14px;white-space:pre-wrap} @media (max-width:980px){main{grid-template-columns:1fr;margin-top:20px;padding:0 8px}header{height:50vh;padding:20px} .hero{flex-direction:column;gap:18px} .brand{width:100%} .cart{position:relative;top:auto;margin-top:8px} .grid{grid-template-columns:repeat(auto-fill,minmax(200px,1fr));gap:16px} .dish img{height:150px}body{font-size:17px}} @media (max-width:560px){:root{font-size:16px}body{padding:0 12px}header{min-height:340px;height:44vh} .brand h1{font-size:24px} .dish img{height:140px} .dish-body{padding:14px} .menu{padding:18px} main{margin:-40px auto 60px} .cart{padding:16px} .qty button{width:30px;height:30px}}
  </style>
</head>
<body>
  <header>
    <div class="hero">
      <div class="brand" role="region" aria-label="Présentation">
        <h1><b>꧁𝓐𝓾𝔁 𝓜𝓲𝓵𝓵𝓮 𝓢𝓪𝓿𝓮𝓾𝓻꧂</h1></b>
        <p>ミ★ Saveurs locales, produits frais et des plats au tant délicieux que votre imagination. Commandez en ligne. ★彡</p>
        <div class="cta">
          <button id="view-menu">Voir le menu</button>
          <a href="#cart" style="color:white;text-decoration:underline">Panier</a>
        </div>
      </div>
      <div style="flex:1;display:flex;align-items:center;justify-content:center">
        <img src="C:\Users\pc\Documents\aa\WhatsApp Image 2026-03-23 at 11.50.21.png" alt="Assiette" style="width:240px;height:240px;object-fit:cover;border-radius:14px;box-shadow:0 12px 30px rgba(31,39,51,0.18)">
      </div>
    </div>
  </header>

  <main>
    <section class="menu" id="menu">
      <div style="display:flex;justify-content:space-between;align-items:center;margin-bottom:14px">
        <h2 style="margin:0">Notre menu</h2>
        <div style="color:var(--muted);font-size:14px">Livraison & retrait</div>
      </div>
      <div class="grid" id="dishes"></div>
    </section>

    <aside class="cart" id="cart" aria-label="Panier">
      <h3>Panier</h3>
      <div class="cart-list" id="cart-list"><div style="color:var(--muted)">Aucun article en vue l'instant.</div></div>
      <div class="total"><span>Total</span><span id="total">€0.00</span></div>
      <div class="checkout">
        <button id="open-order">Passer la commande</button>
        <button id="clear-cart" style="background:#f3f4f6;border:1px solid rgba(15,23,42,0.04);font-weight:600;color:var(--dark)">Vider</button>
      </div>
      <div class="note">Paiement à la livraison ou simulation via le formulaire.</div>
    </aside>
  </main>

  <!-- Order modal -->
  <div id="order-modal">
    <div class="modal-card">
      <h3 style="margin-top:0">Finaliser la commande</h3>
      <div id="order-summary" style="margin-bottom:12px;color:var(--muted)"></div>
      <form id="order-form">
        <div style="display:flex;gap:8px;flex-wrap:wrap">
          <input name="name" placeholder="nom (Entrez votre nom)" required style="flex:1;padding:10px;border-radius:8px;border:1px solid #e6e7eb">
          <input name="phone" placeholder="Téléphone (ex: 6-00-00-00-00)" required style="flex:1;padding:10px;border-radius:8px;border:1px solid #e6e7eb">
        </div>
        <input name="address" placeholder="Adresse (pour livraison)" style="width:100%;margin-top:8px;padding:10px;border-radius:8px;border:1px solid #e6e7eb">
        <div style="display:flex;gap:8px;margin-top:8px;align-items:center">
          <label for="total-dishes" style="color:var(--muted);min-width:160px">Nombre total de plats</label>
          <input id="total-dishes" name="total_dishes" type="number" min="0" value="0" style="flex:1;padding:10px;border-radius:8px;border:1px solid #e6e7eb">
        </div>
        <div style="display:flex;gap:8px;margin-top:12px;justify-content:flex-end">
          <button type="button" id="cancel-order" style="background:#f3f4f6;border:0;padding:10px 12px;border-radius:8px;cursor:pointer">Annuler</button>
          <button type="submit" id="confirm-order" style="background:var(--accent);color:white;border:0;padding:10px 12px;border-radius:8px;cursor:pointer">Commander</button>
        </div>
      </form>
    </div>
  </div>

  <!-- Receipt modal -->
  <div id="receipt-modal">
    <div class="modal-card">
      <h3 style="margin-top:0"><i><u>Reçu de commande</h3></i></u>
      <div id="receipt-container" class="receipt"></div>
      <div style="display:flex;gap:8px;justify-content:flex-end;margin-top:12px">
        <button id="close-receipt" style="background:#f3f4f6;border:0;padding:8px 10px;border-radius:8px;cursor:pointer">Fermer</button>
        <button id="send-whatsapp" style="background:#25D366;color:white;border:0;padding:8px 10px;border-radius:8px;cursor:pointer">Envoyer sur WhatsApp</button>
      </div>
    </div>
  </div>

  <footer>© site créé par råmz¥ éÐï† en 2026 </footer>

  <script>
    // Données plats
    const DISHES = [
      {id:1,name:'HamBurger',desc:'Boeuf haché, cheddar, sauce secrète',price:2000,img:'https://images.unsplash.com/photo-1550547660-d9450f859349?q=80&w=900&auto=format&fit=crop'},
      {id:2,name:'Boeufs braiser',desc:'Légumes frais, vinaigrette citronnée',price:3500,img:'https://images.unsplash.com/photo-1544025162-d76694265947?q=80&w=900&auto=format&fit=crop'},
      {id:3,name:'Pâtes au boulets',desc:'Pâtes fraîches, pesto maison, pignons',price:2500,img:'https://images.unsplash.com/photo-1529042410759-befb1204b468?q=80&w=900&auto=format&fit=crop'},
      {id:4,name:'Aille de Poulet',desc:'Poulet épicé, salsa maison',price:1500,img:'https://images.unsplash.com/photo-1600891964599-f61ba0e24092?q=80&w=900&auto=format&fit=crop'},
      {id:5,name:'Pizza Margherita',desc:'Tomate San Marzano, mozzarella',price:13000,img:'https://tse3.mm.bing.net/th/id/OIP.1nDpsMRtcNDJ-jjoq24aSQHaEJ?rs=1&pid=ImgDetMain&o=7&rm=3'},
      {id:6,name:'Dessert spécial Mille Saveur',desc:"Douceur selon l'inspiration du jour",price:6500,img:'https://images.unsplash.com/photo-1499636136210-6f4ee915583e?q=80&w=900&auto=format&fit=crop'}
    ];

    const cart = new Map();
    function formatPrice(n){ return 'FCFA' + n.toFixed(0); }

    function renderDishes(){
      const container = document.getElementById('dishes');
      container.innerHTML = '';
      DISHES.forEach(d=>{
        const el = document.createElement('article'); el.className='dish';
        el.innerHTML = `
          <img src="${d.img}" alt="${d.name}">
          <div class="dish-body">
            <h4>${d.name}</h4>
            <p>${d.desc}</p>
            <div class="meta">
              <strong>${formatPrice(d.price)}</strong>
              <div style="display:flex;gap:8px;align-items:center">
                <input data-id="${d.id}" class="add-qty" type="number" min="1" value="1" style="width:60px;padding:6px;border-radius:6px;border:1px solid rgba(15,23,42,0.06)">
                <button data-id="${d.id}">Ajouter</button>
              </div>
            </div>
          </div>`;
        container.appendChild(el);
      });
      container.querySelectorAll('button[data-id]').forEach(btn=>{
        btn.addEventListener('click', ()=> {
          const id = Number(btn.dataset.id);
          const input = container.querySelector(`input.add-qty[data-id="${id}"]`);
          const qty = Math.max(1, Number(input.value) || 1);
          addToCart(id, qty);
        });
      });
    }

    function addToCart(id, qty=1){
      const dish = DISHES.find(d=>d.id===id); if(!dish) return;
      const existing = cart.get(id) || {...dish, qty:0};
      existing.qty += qty; cart.set(id, existing); renderCart();
    }

    function changeQty(id, delta){
      const item = cart.get(id); if(!item) return;
      item.qty += delta; if(item.qty<=0) cart.delete(id); else cart.set(id,item); renderCart();
    }

    function clearCart(){ cart.clear(); renderCart(); }

    function renderCart(){
      const list = document.getElementById('cart-list'); list.innerHTML='';
      if(cart.size===0){
        list.innerHTML = "<div style=\"color:var(--muted)\">Aucun article pour l'instant.</div>";
        document.getElementById('total').textContent = formatPrice(0);
        const totalDishesInput = document.getElementById('total-dishes'); if(totalDishesInput) totalDishesInput.value = 0;
        return;
      }
      let sum=0; let totalDishes=0;
      cart.forEach(item=>{
        const lineTotal = item.price * item.qty; sum += lineTotal; totalDishes += item.qty;
        const row = document.createElement('div'); row.className='item';
        row.innerHTML = `
          <div style="width:50px;height:50px;border-radius:8px;overflow:hidden"><img src="${item.img}" alt="${item.name}" style="width:100%;height:100%;object-fit:cover"></div>
          <div class="info"><div style="font-weight:700">${item.name}</div>
            <div style="font-size:13px;color:var(--muted)">${formatPrice(item.price)} x ${item.qty} = <strong>${formatPrice(lineTotal)}</strong></div></div>
          <div class="qty"><button data-action="dec" data-id="${item.id}">−</button>
            <div style="min-width:26px;text-align:center">${item.qty}</div>
            <button data-action="inc" data-id="${item.id}">+</button></div>`;
        list.appendChild(row);
      });
      document.getElementById('total').textContent = formatPrice(sum);
      const totalDishesInput = document.getElementById('total-dishes'); if(totalDishesInput) totalDishesInput.value = totalDishes;
      list.querySelectorAll('button[data-action]').forEach(b=>b.addEventListener('click', ()=> changeQty(Number(b.dataset.id), b.dataset.action==='inc'?1:-1)));
    }

    // Modals & receipt
    const orderModal = document.getElementById('order-modal');
    const receiptModal = document.getElementById('receipt-modal');
    const orderSummary = document.getElementById('order-summary');
    const receiptContainer = document.getElementById('receipt-container');

    function openOrder(){
      if(cart.size===0){ alert('Votre panier est vide.'); return; }
      let txt = ''; let total=0; let totalPlats=0;
      cart.forEach(item=>{ const line = item.qty * item.price; txt += `${item.qty} × ${item.name} — ${formatPrice(line)}\n`; total += line; totalPlats += item.qty; });
      txt += `\nTotal: ${formatPrice(total)}\nNombre total de plats: ${totalPlats}`;
      orderSummary.innerHTML = `<div style="color:var(--muted)">${txt.replace(/\n/g,'<br>')}</div>`;
      const totalDishesInput = document.getElementById('total-dishes'); if(totalDishesInput) totalDishesInput.value = totalPlats;
      orderModal.style.display = 'flex';
    }
    function closeOrder(){ orderModal.style.display = 'none'; }

    document.getElementById('open-order').addEventListener('click', openOrder);
    document.getElementById('cancel-order').addEventListener('click', closeOrder);

    document.getElementById('order-form').addEventListener('submit', function(e){
      e.preventDefault();
      const f = new FormData(e.target);
      const name = f.get('name') || '';
      const phone = f.get('phone') || '';
      const address = f.get('address') || '';
      const total_dishes = Number(f.get('total_dishes') || 0);

      let total = 0;
      let lines = [];
      cart.forEach(item=>{
        const line = item.qty * item.price;
        lines.push({name: item.name, qty: item.qty, price:item.price, line});
        total += line;
      });

      const now = new Date();
      const dateStr = now.toLocaleString();

      let receiptText = `Aux Mille Saveurs\nReçu de commande\nDate: ${dateStr}\n\nClient: ${name}\nTéléphone: ${phone}\nAdresse: ${address}\n\n--- Commande ---\n`;
      lines.forEach(l => { receiptText += `${l.qty} x ${l.name} @ ${formatPrice(l.price)} = ${formatPrice(l.line)}\n`; });
      receiptText += `\nTotal plats: ${total_dishes}\nMontant total: ${formatPrice(total)}\n\nMerci pour votre commande !`;

      receiptContainer.textContent = receiptText;
      closeOrder();
      receiptModal.style.display = 'flex';
    });

    document.getElementById('close-receipt').addEventListener('click', ()=>{ receiptModal.style.display='none'; });

    // WhatsApp send button
    document.getElementById('send-whatsapp').addEventListener('click', ()=>{
      const DEST_NUMBER = '676843813'; // <-- remplacez par le numéro destinataire sans '+'
      const text = encodeURIComponent(receiptContainer.textContent || '');
      const waUrl = `https://wa.me/${DEST_NUMBER}?text=${text}`;
      window.open(waUrl, '_blank');
    });

    document.getElementById('clear-cart').addEventListener('click', ()=>{ if(confirm('Vider le panier ?')) clearCart(); });
    document.getElementById('view-menu').addEventListener('click', ()=>{ const m = document.getElementById('menu'); if(m) m.scrollIntoView({behavior:'smooth'}); });

    // Initialisation après DOM ready
    document.addEventListener('DOMContentLoaded', ()=>{
      renderDishes();
      renderCart();
    });
  </script>
</body>
</html>
