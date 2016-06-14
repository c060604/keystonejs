# keystonejs

### 增加自定义ImageUrl Field

* 用处：在列表中显示图片
* 步骤：
	
	1. 在 ./fields/types 目录下创建 imageurl
	2. 在 ./lib/fieldType.js 中引入 imageurl
	3. 在 ./templates/mixins/columns.jade 中处理 imageurl field 的显示逻辑
	4. 在 ./admin/src/fields.js 中引入 imageurl
