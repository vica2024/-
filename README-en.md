[中文](./README.md) | English

# Diamond POS
<p align="center">
    <img src="https://s1.imagehub.cc/images/2024/04/29/9e531fec82c60fefbaceaafc8fbf7229.png" width="150" />
</p>
<p align="center">
    <a href="" target="_blank">Home</a> |
    <a href="" target="_blank">Document</a> | 
    <a href="" target="_blank">Demo</a> |
    <a href="https://arco.design" target="_blank">Arco Design</a>
</p>

This is a POS system specifically tailored for offline brand chain stores, adaptable for both PC and iPad devices. Picture this: when distinguished customers visit your brand store and express purchase intentions after being introduced to your products by professional salespeople, your sales staff seamlessly utilize the professional iPad POS to provide a high-quality, efficient shopping experience. Undoubtedly, this enhances your brand image. Beyond offering mainstream POS functionalities and a user-friendly interface, this system can also be customized to match your brand's color scheme. It serves as the cornerstone of your enterprise digitization, empowering you to achieve objectives like <a href="" target="_blank">⭐Marketing Online</a> <a href="" target="_blank">⭐Sales Online</a> <a href="" target="_blank">⭐Service Online</a> and <a href="" target="_blank">⭐Production Online</a>."

Open-source projects thrive on community support. If you find this project helpful, please consider giving it a star ⭐️ on GitHub. Your support and encouragement mean the world to me!

## Project List
├── .gitignore
├── .prettierignore
├── DIRECTORY_STRUCTURE.txt
├── LICENSE
├── README-en.md
├── README.md
├── __tests__
│   └── .js
├── babel.config.js
├── commitlint.config.cjs
├── generate-tree.js
├── index.html
├── jest.config.js
├── listFolders.js
├── package-lock.json
├── package.json
├── plugin
│   ├── arcoResolver.js
│   ├── arcoStyleImport.js
│   ├── compress.js
│   ├── imagemin.js
│   └── visualizer.js
├── postcss.config.js
├── public
│   └── vite.svg
├── src
│   ├── .DS_Store
│   ├── App.vue
│   ├── api
│   │   ├── common.js
│   │   ├── customer.js
│   │   ├── dashboard.js
│   │   ├── form.js
│   │   ├── interceptor.js
│   │   ├── list.js
│   │   ├── message.js
│   │   ├── order.js
│   │   ├── product.js
│   │   ├── profile.js
│   │   ├── store.js
│   │   ├── user-center.js
│   │   ├── user.js
│   │   └── visualization.js
│   ├── assets
│   │   ├── .DS_Store
│   │   ├── images
│   │   │   ├── bg.png
│   │   │   ├── clear.png
│   │   │   ├── dpg.png
│   │   │   ├── expressi.jpg
│   │   │   ├── give_coupon.png
│   │   │   ├── give_integral.png
│   │   │   ├── gold.png
│   │   │   ├── goods_default.png
│   │   │   ├── goods_vip.png
│   │   │   ├── label01.png
│   │   │   ├── label02.png
│   │   │   ├── line.jpg
│   │   │   ├── login-banner.png
│   │   │   ├── mjhd.png
│   │   │   ├── mjmz.png
│   │   │   ├── moren.jpg
│   │   │   ├── mshd.png
│   │   │   ├── njnz.png
│   │   │   ├── no-active.png
│   │   │   ├── no-cart.png
│   │   │   ├── no-cup.png
│   │   │   ├── no-goods.png
│   │   │   ├── no-order.png
│   │   │   ├── no-record.png
│   │   │   ├── no-staff.png
│   │   │   ├── no-thing.png
│   │   │   ├── no-user.png
│   │   │   ├── no.png
│   │   │   ├── process1.png
│   │   │   ├── process2.png
│   │   │   ├── ren.png
│   │   │   ├── svip-user.png
│   │   │   ├── tourist.png
│   │   │   ├── upload.png
│   │   │   ├── vip-bg.png
│   │   │   ├── work-chat-login.png
│   │   │   ├── wutu.png
│   │   │   ├── wx-login.png
│   │   │   ├── wx_zfb_pay.png
│   │   │   ├── xpay.png
│   │   │   ├── xszk.png
│   │   │   ├── yonghu.png
│   │   │   └── yue.png
│   │   ├── logo.svg
│   │   ├── logo2.png
│   │   ├── style
│   │   │   ├── breakpoint.less
│   │   │   ├── common.less
│   │   │   ├── global.less
│   │   │   └── index.css
│   │   ├── svg
│   │   │   ├── body.svg
│   │   │   ├── header-theme-dark.svg
│   │   │   ├── header-theme-primary.svg
│   │   │   ├── header-top.svg
│   │   │   ├── icon-happy.svg
│   │   │   ├── icon-sad.svg
│   │   │   ├── icon-social-bilibili.svg
│   │   │   ├── icon-social-dingding.svg
│   │   │   ├── icon-social-facebook.svg
│   │   │   ├── icon-social-juejin.svg
│   │   │   ├── icon-social-qq.svg
│   │   │   ├── icon-social-twitter.svg
│   │   │   ├── icon-social-wechat.svg
│   │   │   ├── icon-social-weibo.svg
│   │   │   ├── icon-social-zhihu.svg
│   │   │   ├── nav-theme-dark.svg
│   │   │   └── nav-theme-light.svg
│   │   └── world.json
│   ├── components
│   │   ├── TemplateAddRowModal
│   │   │   └── TemplateAddRowModal.vue
│   │   ├── TemplateDialog
│   │   │   └── TemplateDialog.vue
│   │   ├── breadcrumb
│   │   │   └── index.vue
│   │   ├── chart
│   │   │   └── index.vue
│   │   ├── custom
│   │   │   ├── DynamicIcon.vue
│   │   │   └── DynamicInput.vue
│   │   ├── footer
│   │   │   └── index.vue
│   │   ├── global-setting
│   │   │   ├── block.vue
│   │   │   ├── form-wrapper.vue
│   │   │   └── index.vue
│   │   ├── index.js
│   │   ├── menu
│   │   │   ├── index.vue
│   │   │   └── use-menu-tree.js
│   │   ├── message-box
│   │   │   ├── details-left.vue
│   │   │   ├── details-right.vue
│   │   │   ├── details.vue
│   │   │   ├── index.vue
│   │   │   ├── list.vue
│   │   │   └── locale
│   │   │       ├── en-US.js
│   │   │       └── zh-CN.js
│   │   ├── navbar
│   │   │   └── index.vue
│   │   └── tab-bar
│   │       ├── index.vue
│   │       └── tab-item.vue
│   ├── config
│   │   ├── globlaEnum.js
│   │   └── settings.json
│   ├── directive
│   │   ├── index.js
│   │   ├── permission
│   │   │   └── index.js
│   │   └── resizeDirective.js
│   ├── hooks
│   │   ├── chart-option.js
│   │   ├── loading.js
│   │   ├── locale.js
│   │   ├── permission.js
│   │   ├── request.js
│   │   ├── responsive.js
│   │   ├── themes.js
│   │   ├── useAddTableRow.js
│   │   ├── useAddTableRowForm.js
│   │   ├── useDeleteConfim.js
│   │   ├── useMessage.js
│   │   ├── useTableHook.js
│   │   ├── user.js
│   │   └── visible.js
│   ├── layout
│   │   ├── cashier-layout.vue
│   │   ├── default-layout.vue
│   │   └── page-layout.vue
│   ├── locale
│   │   ├── en-US
│   │   │   └── settings.js
│   │   ├── en-US.js
│   │   ├── index.js
│   │   ├── zh-CN
│   │   │   └── settings.js
│   │   └── zh-CN.js
│   ├── main.js
│   ├── mock
│   │   ├── index.js
│   │   ├── message.js
│   │   └── user.js
│   ├── router
│   │   ├── app-menus
│   │   │   └── index.js
│   │   ├── constants.js
│   │   ├── guard
│   │   │   ├── index.js
│   │   │   ├── permission.js
│   │   │   └── userLoginInfo.js
│   │   ├── index.js
│   │   ├── routes
│   │   │   ├── base.js
│   │   │   ├── index.js
│   │   │   ├── modules
│   │   │   │   └── pos.js
│   │   │   └── types.ts
│   │   └── typings.d.ts
│   ├── store
│   │   ├── index.js
│   │   └── modules
│   │       ├── app
│   │       │   └── index.js
│   │       ├── cashier
│   │       │   └── index.ts
│   │       ├── customer
│   │       │   └── index.ts
│   │       ├── tab-bar
│   │       │   └── index.js
│   │       └── user
│   │           └── index.js
│   ├── style.css
│   ├── utils
│   │   ├── auth.js
│   │   ├── computes.js
│   │   ├── customFunc.js
│   │   ├── env.js
│   │   ├── event.js
│   │   ├── index.js
│   │   ├── is.js
│   │   ├── monitor.js
│   │   ├── notification-service.js
│   │   ├── route-listener.js
│   │   └── setup-mock.js
│   └── views
│       ├── cashier
│       │   ├── components
│       │   │   ├── counter
│       │   │   │   ├── cart-item-amount.vue
│       │   │   │   ├── cart-item-product.vue
│       │   │   │   ├── cart-item-total.vue
│       │   │   │   ├── cart-list.vue
│       │   │   │   ├── cart.vue
│       │   │   │   ├── customer.vue
│       │   │   │   ├── index.vue
│       │   │   │   ├── serving-v2.vue
│       │   │   │   ├── serving.vue
│       │   │   │   ├── staff.vue
│       │   │   │   └── tools.vue
│       │   │   ├── drawers
│       │   │   │   ├── cart-details-list.vue
│       │   │   │   ├── cart-details.vue
│       │   │   │   ├── customer
│       │   │   │   │   ├── columns.js
│       │   │   │   │   ├── create.vue
│       │   │   │   │   ├── descriptions-item-value.vue
│       │   │   │   │   ├── descriptions.vue
│       │   │   │   │   ├── record.vue
│       │   │   │   │   └── search-form.vue
│       │   │   │   ├── customer-info-details.vue
│       │   │   │   ├── payment-type
│       │   │   │   │   ├── alipay.vue
│       │   │   │   │   ├── balance-pay.vue
│       │   │   │   │   ├── cash-pay.vue
│       │   │   │   │   ├── credit-card.vue
│       │   │   │   │   ├── crypto-cion.vue
│       │   │   │   │   └── wepay.vue
│       │   │   │   └── payment.vue
│       │   │   ├── modals
│       │   │   │   ├── cashier-list.vue
│       │   │   │   ├── order-marks.vue
│       │   │   │   ├── product-sku.vue
│       │   │   │   └── recharge.vue
│       │   │   └── product
│       │   │       ├── card
│       │   │       │   └── index.vue
│       │   │       ├── index.vue
│       │   │       ├── item-card.vue
│       │   │       ├── search-skeleton.vue
│       │   │       └── search.vue
│       │   ├── index.vue
│       │   ├── locale
│       │   │   ├── en-US.js
│       │   │   └── zh-CN.js
│       │   └── mock.js
│       ├── exception
│       │   ├── 403
│       │   │   ├── index.vue
│       │   │   └── locale
│       │   │       ├── en-US.js
│       │   │       └── zh-CN.js
│       │   ├── 404
│       │   │   ├── index.vue
│       │   │   └── locale
│       │   │       ├── en-US.js
│       │   │       └── zh-CN.js
│       │   └── 500
│       │       ├── index.vue
│       │       └── locale
│       │           ├── en-US.js
│       │           └── zh-CN.js
│       ├── login
│       │   ├── components
│       │   │   ├── banner.vue
│       │   │   └── login-form.vue
│       │   ├── index.vue
│       │   └── locale
│       │       ├── en-US.js
│       │       └── zh-CN.js
│       ├── not-found
│       │   └── index.vue
│       ├── order
│       │   ├── components
│       │   │   ├── customer-card.vue
│       │   │   ├── order-details.vue
│       │   │   ├── order-info-list.vue
│       │   │   ├── order-info.vue
│       │   │   ├── order-list-card.vue
│       │   │   ├── order-record.vue
│       │   │   ├── order-select.vue
│       │   │   └── tabs.vue
│       │   ├── index.vue
│       │   ├── locale
│       │   │   ├── en-US.js
│       │   │   └── zh-CN.js
│       │   └── mock.js
│       ├── pending
│       │   ├── components
│       │   │   ├── customer-card.vue
│       │   │   ├── handOrder-list.vue
│       │   │   ├── order-items-card.vue
│       │   │   └── order-items.vue
│       │   ├── index.vue
│       │   ├── locale
│       │   │   ├── en-US.js
│       │   │   └── zh-CN.js
│       │   └── mock.js
│       ├── refund
│       │   ├── components
│       │   │   ├── customer-card.vue
│       │   │   ├── order-details.vue
│       │   │   ├── order-info-list.vue
│       │   │   ├── order-info.vue
│       │   │   ├── order-list-card.vue
│       │   │   ├── order-record.vue
│       │   │   ├── order-select.vue
│       │   │   └── tabs.vue
│       │   ├── index.vue
│       │   └── mock.js
│       └── write-off
│           ├── components
│           │   ├── customer-card.vue
│           │   ├── order-details.vue
│           │   ├── order-info-list.vue
│           │   ├── order-info.vue
│           │   ├── order-list-card.vue
│           │   ├── order-record.vue
│           │   ├── order-select.vue
│           │   └── tabs.vue
│           ├── index.vue
│           └── order.vue
├── tailwind.config.js
├── tsconfig.json
├── vite.config.js
└── yarn.lock

## Install Guide

- pull the code
```
git clone https://github.com/vica2024/vica-retail-cashier.git
```
- Install Dependencies
```
cd vica-retail-cashier && yarn install 
```
or
```
cd vica-retail-cashier && npm install
```
- run project
```
yarn dev
```
or
```
nup run dev
```
- build the project to launch
```
yarn build
```

## Support

Feel free to contact me by email if you have any questions about the project. 

**zhuovica@gmail.com**

## Screenshots

<img src="https://s21.ax1x.com/2024/06/11/pkUYRgO.png" alt="diamond POS" />

<img src="https://s21.ax1x.com/2024/06/11/pkUY5bd.png" alt="diamond POS" />

<img src="https://s21.ax1x.com/2024/06/11/pkUYTUI.png" alt="diamond POS" />

<img src="https://s21.ax1x.com/2024/06/11/pkUY75t.png" alt="diamond POS" />

<img src="https://s21.ax1x.com/2024/06/11/pkUYbPP.png" alt="diamond POS" />
