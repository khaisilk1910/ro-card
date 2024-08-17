# ro-card
Card hiển thị thông tin máy lọc nước RO.

![image](https://github.com/user-attachments/assets/8f20d532-24ef-4968-abf9-a402a77811fb)

Phần động là mức nước tiêu thụ trong ngày với Min và Max có thể thay đổi trong code mục
```
variables:
  .....
  main_min: 0
  main_max: 20
  .....
```
Tất cả nội dung có thể thay đổi ở trong ```variables:``` hoặc có thể thay đổi trong code tùy ý.

Tải file svg về lưu vào HASS và thay đổi đường dẫn file theo vị trí lưu của bạn tại
```
variables:
  .....
  info_card_entity_picture: /local/images/icon/water filter cartridges.svg
  .....
```

![Untitled video - Made with Clipchamp (1)](https://github.com/user-attachments/assets/acc3eaa1-2bb4-4322-85ad-21db8bffee18)
