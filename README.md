# Swagger-PHP Annotation

## Install


安装插件：
phpstrom: PHP Annotation


具体`templates`路径参考[文档](https://www.jetbrains.com/help/phpstorm/tuning-the-ide.html#default-dirs)

```sh

git clone https://github.com/chunhei2008/swagger-php-annotation.git

cd swagger-php-annotation

# 将`swagger-php-annotation.xml`复制到`templates`目录
cp swagger-php-annotation.xml [phpstrom/templates/path]

```

## Usage



使用规则：

- `@Get` 与 `@Get_` 为HTTP `GET` 请求
- `@Post` 与 `@Post_` 为HTTP `POST` 请求

带`_` 表示在注释中使用

注解字段参考 [swagger-php Annotations](https://github.com/zircote/swagger-php/tree/master/src/Annotations)
