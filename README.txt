WooCommerce - МойСклад Интеграция
Описание
Плагин "WooCommerce - МойСклад Интеграция" обеспечивает полную синхронизацию между вашим интернет-магазином WooCommerce и системой учета МойСклад. С его помощью вы можете автоматизировать передачу товаров, категорий и заказов, значительно упростив управление вашим бизнесом.

Основные возможности
Двусторонняя синхронизация - данные могут передаваться как из WooCommerce в МойСклад, так и в обратном направлении
Синхронизация товаров - автоматический перенос товаров с фото, описаниями, ценами и характеристиками
Синхронизация категорий - передача структуры категорий между системами
Синхронизация заказов - автоматическое создание заказов в МойСклад при оформлении в WooCommerce
Синхронизация клиентов - создание карточек клиентов в МойСклад с контактными данными
Синхронизация статусов - обновление статусов заказов в обеих системах
Автоматическое создание товаров - если товар в заказе не найден в МойСклад, он будет создан автоматически
Надежная система логирования - подробная информация о всех процессах для легкой отладки
Настройки плагина
Настройки API МойСклад
API URL - URL API МойСклад (обычно https://online.moysklad.ru/api/remap/1.2)
Логин - имя пользователя в МойСклад
Пароль - пароль от учетной записи МойСклад
Токен - альтернативный способ авторизации через токен API
Настройки синхронизации товаров
Активировать синхронизацию товаров - включение/отключение функции
Направление синхронизации - выбор направления (из WooCommerce в МойСклад, из МойСклад в WooCommerce, или двунаправленная)
Интервал синхронизации - как часто проводить автоматическую синхронизацию
Синхронизировать цены - передавать ли информацию о ценах
Синхронизировать остатки - передавать ли информацию о количестве товаров на складе
Настройки синхронизации заказов
Активировать синхронизацию заказов - включение/отключение функции
Префикс заказа - добавление префикса к номеру заказа в МойСклад
Организация - выбор организации в МойСклад для привязки заказов
Склад - выбор склада в МойСклад для резервирования товаров
Группа клиентов - выбор группы для новых клиентов
Маппинг статусов - соответствие между статусами заказов в WooCommerce и МойСклад
Синхронизировать статусы заказов из МойСклад - обновлять ли статусы в WooCommerce при изменении в МойСклад
Настройки веб-хуков
Активировать веб-хуки - включение/отключение обработки событий в реальном времени
URL для веб-хуков - адрес для приема уведомлений от МойСклад
События для веб-хуков - выбор событий, которые должны вызывать синхронизацию (создание, обновление, удаление)
Функциональные кнопки
Синхронизировать все - запуск полной синхронизации товаров, категорий и заказов
Только товары - синхронизация только товаров
Только категории - синхронизация только категорий
Только заказы - синхронизация только заказов
Остановить - экстренная остановка любого процесса синхронизации
Тест соединения - проверка доступности API МойСклад с текущими настройками
Зарегистрировать веб-хуки - регистрация вебхуков в МойСклад для обработки событий
Системные требования
WordPress 5.0 или выше
WooCommerce 3.5 или выше
PHP 7.2 или выше
Доступ к API МойСклад (аккаунт с правами на работу с API)
Поддержка cURL в PHP
Журнал логов
Плагин включает расширенную систему логирования, которая записывает все действия по синхронизации. В интерфейсе администратора доступны следующие функции:

Просмотр всех логов с фильтрацией по типу (info, warning, error)
Очистка логов
Детальная информация о каждой операции с контекстом
Надежность и отказоустойчивость
Автоматические повторные попытки - при сбоях API система автоматически повторяет запросы
Защита от дублирования - система проверяет наличие товаров и заказов перед созданием
Контроль параллельных процессов - предотвращение конфликтов при одновременной синхронизации
Резервное копирование важных данных - сохранение идентификаторов для сопоставления между системами
Дополнительные возможности
Ручное сопоставление - возможность вручную связывать товары между WooCommerce и МойСклад
Импорт существующих данных - загрузка существующих товаров и категорий при первом запуске
Синхронизация атрибутов товаров - передача характеристик товаров между системами
Поддержка вариативных товаров - корректная работа с товарами, имеющими вариации
Преимущества плагина
Значительная экономия времени на ручном вводе данных
Исключение ошибок, связанных с человеческим фактором
Актуальные остатки товаров и цены в вашем магазине
Централизованное управление каталогом и заказами
Улучшение клиентского опыта благодаря актуальной информации
Прозрачность бизнес-процессов и улучшенная аналитика
Плагин разработан с учетом особенностей российского рынка и специфики работы МойСклад, обеспечивая максимальную совместимость и стабильность работы.


=== WooCommerce MoySklad Integration ===
Contributors: yourname
Tags: woocommerce, moysklad, integration, inventory, products, orders, synchronization, мойсклад
Requires at least: 5.0
Tested up to: 6.3
Stable tag: 1.0.0
Requires PHP: 7.2
License: GPLv2 or later
License URI: https://www.gnu.org/licenses/gpl-2.0.html

Comprehensive integration between WooCommerce and MoySklad.ru (МойСклад) for product, inventory, and order synchronization.

== Description ==

WooCommerce MoySklad Integration provides a robust connection between your WooCommerce store and MoySklad (МойСклад) inventory management system. 

**Key Features:**

**Product Synchronization**
* Synchronize products from MoySklad to WooCommerce
* Transfer product names, descriptions, prices, and SKUs
* Import product images
* Support for variable products and modifications
* Support for product sets and bundles
* Synchronize product categories with full nested structure
* Map custom fields to product attributes

**Inventory Management**
* Synchronize stock levels from selected warehouses
* Automatic stock updates on schedule
* Real-time stock updates via webhooks
* Reserve management

**Order Management**
* Send WooCommerce orders to MoySklad automatically
* Synchronize order status changes in both directions
* Map WooCommerce order statuses to MoySklad statuses
* Customer data synchronization

**Customer Management**
* Create and update customers in MoySklad
* Assign customers to groups
* Support for customer-specific pricing

**Additional Features**
* Two synchronization modes: standard and accelerated
* Detailed activity logging
* Webhooks for real-time updates
* Extensive customization options
* Multiple scheduling options
* Comprehensive admin interface

== Installation ==

1. Upload the `woo-moysklad-integration` folder to the `/wp-content/plugins/` directory
2. Activate the plugin through the 'Plugins' menu in WordPress
3. Go to MoySklad menu in WordPress admin
4. Configure your API credentials in the Settings tab
5. Configure synchronization options as needed
6. Start synchronization

== Frequently Asked Questions ==

= Does this plugin require a MoySklad account? =

Yes, you need an active MoySklad (МойСклад) account and API access credentials.

= How often are products and inventory synchronized? =

You can configure the synchronization schedule in the plugin settings. Available options include hourly, twice daily, and daily updates. You can also enable real-time updates using webhooks.

= Can I synchronize existing products? =

Yes, the plugin will attempt to match existing products based on SKU or product name. You can also initiate a full synchronization from the admin interface.

= Does this plugin support variable products? =

Yes, product modifications in MoySklad will be synchronized as variable products in WooCommerce.

= Will my WooCommerce orders be sent to MoySklad? =

Yes, by default all new orders in WooCommerce will be automatically sent to MoySklad. You can configure the delay or disable this feature in the settings.

= Does the plugin support real-time updates? =

Yes, with webhooks enabled, changes in MoySklad (like inventory levels or order status changes) will be reflected in your WooCommerce store almost immediately.

= What languages does the plugin support? =

The plugin supports English and Russian languages.

== Screenshots ==

1. Main dashboard
2. Product synchronization settings
3. Inventory synchronization settings
4. Order synchronization settings
5. Webhooks configuration
6. Logs view

== Changelog ==

= 1.0.0 =
* Initial release

== Upgrade Notice ==

= 1.0.0 =
Initial release

== Configuration Guide ==

### Step 1: API Configuration

1. Log in to your MoySklad account
2. Go to your profile settings and create an API access token
3. In WordPress admin, navigate to MoySklad > Settings > API Settings
4. Enter your API credentials and test the connection

### Step 2: Product Synchronization Settings

1. Go to MoySklad > Settings > Products
2. Enable product synchronization
3. Configure which product data to synchronize (descriptions, images, categories, etc.)
4. Choose the synchronization mode and schedule

### Step 3: Inventory Settings

1. Go to MoySklad > Settings > Inventory
2. Select which warehouse to use for stock levels
3. Configure the synchronization schedule for inventory updates

### Step 4: Order Settings

1. Go to MoySklad > Settings > Orders
2. Enable order synchronization
3. Configure organization and warehouse settings
4. Set up status mapping between WooCommerce and MoySklad order statuses

### Step 5: Webhook Configuration (Optional)

For real-time updates:

1. Go to MoySklad > Settings > Webhooks
2. Enable webhooks
3. Click "Register Webhooks in MoySklad" to automatically set up the required webhooks

### Step 6: Starting Synchronization

1. Go to MoySklad > Products
2. Click "Sync Products Now" to start the initial synchronization
3. Monitor the progress in the Logs section

== MoySklad API Configuration ==

To use this plugin, you need to configure API access in your MoySklad account:

1. Log in to MoySklad (moysklad.ru)
2. Go to Settings > API Access
3. Create a new API account or use your main account credentials
4. Make sure the account has the necessary permissions:
   * Read/write access to Products
   * Read/write access to Orders
   * Read access to Warehouses
   * Read/write access to Customers
   * Read/write access to Organizations

For webhooks to work properly, your account also needs permission to manage webhooks.

== Troubleshooting ==

**Synchronization not working:**
* Check your API credentials
* Verify your server's PHP settings - the plugin requires PHP 7.2 or higher
* Look for error messages in the Logs section

**Products not appearing in WooCommerce:**
* Check that the products are active and visible in MoySklad
* Verify that product synchronization is enabled
* Check the logs for any specific errors related to product synchronization

**Stock levels not updating:**
* Verify that the correct warehouse is selected in settings
* Check that inventory synchronization is enabled
* Try a manual inventory sync

**Orders not appearing in MoySklad:**
* Verify that order synchronization is enabled
* Check the organization and warehouse settings
* Check the logs for any errors related to order creation

**Webhooks not working:**
* Ensure your site is accessible from the internet
* Verify that webhooks are enabled in the plugin settings
* Check that webhooks are properly registered in MoySklad
* Look for webhook-related errors in the logs
