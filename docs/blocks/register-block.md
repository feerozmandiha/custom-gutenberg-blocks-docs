# 📌 ثبت بلوک جدید

از تابع `registerBlockType()` برای تعریف یک بلوک استفاده می‌شود:

```js
wp.blocks.registerBlockType('my-plugin/example', {
  title: 'بلوک نمونه',
  icon: 'smiley',
  category: 'common',
  edit: function() { ... },
  save: function() { ... },
});
