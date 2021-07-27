# Swagger-PHP Annotation

## Install

- git clone 
- 将`swagger-php-annotation.xml`复制到`templates`目录
具体`templates`路径参考[文档](https://www.jetbrains.com/help/phpstorm/tuning-the-ide.html#default-dirs)

## Usage

在编辑器中输入 `@Get`

```php
/**
 * @OA\Get(
 *   tags={"Tag"},
 *   path="Path",
 *   summary="Summary",
 *   @OA\Parameter(ref="#/components/parameters/id"),
 *   @OA\Response(response=200, description="OK"),
 *   @OA\Response(response=401, description="Unauthorized"),
 *   @OA\Response(response=404, description="Not Found")
 * )
 */
```