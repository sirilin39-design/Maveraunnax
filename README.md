# Maveraunnax
"Интернет-магазин женской одежды Maveraunnax — минимализм, мультиязычный, с оплатой UZ и международными картами
Maveraunnax/
├─ public/           # изображения, баннеры, фото товаров
├─ pages/
│   ├─ index.js      # Главная
│   ├─ shop.js       # Каталог
│   ├─ product/[id].js # Страница товара
│   ├─ cart.js       # Корзина
│   ├─ checkout.js   # Оплата
│   ├─ about.js      # О бренде
│   ├─ delivery.js   # Доставка
│   └─ admin.js      # Админка
├─ components/       # Кнопки, карточки товара, меню
├─ lib/
│   ├─ supabase.js   # подключение базы данных
│   └─ payment.js    # API оплаты
├─ locales/
│   ├─ uz.json
│   ├─ en.json
│   └─ tr.json
├─ styles/
│   └─ globals.css   # TailwindCSS стили
├─ package.json
└─ next.config.js
