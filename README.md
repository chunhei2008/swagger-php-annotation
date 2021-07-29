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

# restart your phpstrom

```

## Usage

### 上下文说明

`swagger-php-annotation`在`phpstrom`中分为两种上下文

1. 注释上下文：注释块中
2. 非注释上下文：注释块之外的空白处

同一个注解分两种上下文使用场景，不同场景使用不同的标识符

如：

`@Get` 和 `@Get_` 都是HTTP `GET` 请求
`@Get_` 为注释上下文使用
`@Get` 为非注释上下文使用

## 参考文档

- [swagger-php Annotations](https://github.com/zircote/swagger-php/tree/master/src/Annotations)
