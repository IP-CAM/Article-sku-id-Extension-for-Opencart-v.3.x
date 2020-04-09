Модуль выводит id товара в качестве артикула, что позволяет автоматически присваивать артикул новому товару.  
Архив для установки через установщик модулей article_sku_id-oc3.ocmod.zip  
Или можно создать новый модификатор и вставить код из article_sku_id-oc3.xml  
После установки необходимо обновить кэш модификатора  
!!!
Если не появились данные в шаблоне, проверьте вывод в файлах модуля
<file path="catalog/view/theme/default/template/product/product.twig">
<file path="catalog/view/theme/default/template/product/category.twig">
<file path="catalog/view/theme/default/template/extension/module/latest.twig">
<file path="catalog/view/theme/default/template/extension/module/featured.twig">