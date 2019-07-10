## intent:greet
- hey
- hello
- hi
- good morning
- good evening
- hey there

## intent:goodbye
- bye
- goodbye
- see you around
- see you later

## intent:affirm
- yes
- indeed
- of course
- that sounds good
- correct

## intent:deny
- no
- never
- I don't think so
- don't like that
- no way
- not really

## intent:mood_great
- perfect
- very good
- great
- amazing
- wonderful
- I am feeling very good
- I am great
- I'm good

## intent:mood_unhappy
- sad
- very sad
- unhappy
- bad
- very bad
- awful
- terrible
- not very good
- extremely sad
- so sad

## intent: de_xuat_mua_laptop_chi_tiet
- Tôi muốn mua laptop [rams](ram_config) RAM 
- Tôi muốn mua laptop [ram values](ram_config:ram) RAM
- Tôi cần mua laptop [ram](ram_config) RAM
- Tôi muốn mua laptop [ram values](ram_config:ram) RAM
- shop có bán laptop [rams](ram_config) RAM không?
- shop có bán laptop [ram values](ram_config:ram) RAM không?


## intent:de_xuat_nhu_cau
- Mình muốn mua laptop.
- Tôi đang cần mua laptop.
- Muốn mua laptop còn hàng không?

## intent:hoi_mat_hang
- Còn sản phẩm không bạn?
- Mình muốn mua sản phẩm, còn không bạn?
- Cho hỏi thông tin sản phẩm?
- sản phẩm còn hàng không?
- sản phẩm giá bao nhiêu?

## intent:hoi_cau_hinh
- Cấu hình sản phẩm thế nào?
- Ram bao nhiêu GB?
- Ổ cứng bao nhiêu GB?
- Tốc độ xử lý thế nào?
- Thông số kĩ thuật thế nào?

## intent:hoi_bao_hanh
- Chế độ bảo hành như thế nào?
- Bảo hành bao nhiêu tháng?
- Có bảo hành không?

## intent:hoi_khuyen_mai
- Khuyến mãi cho sản phẩm là gì?
- Có khuyến mãi gì cho sản phẩm không?
- Được tặng gì kèm theo không?

## intent:hoi_nha_san_xuat
- Thương hiệu của sản phẩm là gì?
- Sản phẩm của thương hiệu nào?
- Sản phẩm được sản xuất ở đâu thế bạn?

## synonym: rams
- 4GB
- 8GB
- 16GB
- 32GB

## synonym: mems
- 256GB
- 512GB
- 1000GB


## lookup: rams
- 4GB
- 8GB
- 16GB
- 32GB

## lookup: cores
- dual core
- i3
- i5
- i7

## lookup: mems
- 128GB
- 256GB
- 512GB

## regex: year
- 20[0-9]{2}

## regex: mems
- [0-9]{3}GB

## regex: rams
- [0-9]{2}GB
- [0-9]{1}GB
