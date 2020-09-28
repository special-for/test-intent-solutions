# test-intent-solutions
модуль для версии 3.х
файл install.php может не сработать если нет модуля "Local-copy" или другая сборка,
тогда необходимо виполнить команду по добавлению в БД вручную
ALTER TABLE `oc_product_image` ADD `option_value_ids` VARCHAR(256) NOT NULL AFTER `image`;
