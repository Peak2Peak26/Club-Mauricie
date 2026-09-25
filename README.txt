CLUB MOTONEIGE MAURICIE — Boutique (même format que FCMQ, paiement Square)

1) Netlify > Environment variables :
   SQUARE_ACCESS_TOKEN = (même token que FCMQ)
   SQUARE_LOCATION_ID  = LKBN9910T1M36

2) EmailJS (merci.html) : même clé publique que FCMQ.
   Remplacer service_XXXXXXX (service Gmail clubmotoneigep2p@gmail.com)
   et template_XXXXXXX (dupliquer le template FCMQ, mêmes variables).

3) Prix/produits : 3 endroits identiques
   index.html, merci.html, netlify/functions/create-checkout-session.js
