# Sổ tay dịch tễ học với R

# Về cuốn số tay này
**Sổ tay dịch tễ học với R là một tài liệu hướng dẫn về dịch tễ học ứng dụng và y tế công cộng.**  

***Hãy ghé thăm website www.epiRhandbook.com/vn để xem phiên bản trực tuyến mới nhất.***

![Project logo](https://github.com/appliedepi/epiRhandbook_eng/blob/master/images/Epi%20R%20Handbook%20Banner%20Beige%201500x500.png)

**Sổ tay này hướng tới:**

-   Là một tài liệu tham khảo R một cách nhanh chóng
-   Cung cấp các ví dụ tập trung vào nhiệm vụ giải quyết các vấn đề dịch tễ học phổ biến
-   Hỗ trợ các nhà dịch tễ học chuyển sang sử dụng R
-   Có thể sử dụng trong các tình huống có kết nối internet thấp thông qua **[phiên bản ngoại tuyến](https://epirhandbook.com/vn/data-used.html#data-used)**
  

<img src="https://github.com/appliedepi/epiRhandbook_eng/blob/master/images/epiRhandbook_HexSticker_500x500.png" width="200" height="200">

<span style="color: black;">**Được viết bởi các nhà dịch tễ học, dành cho các nhà dịch tễ học**</span>
Applied Epi là một tổ chức phi lợi nhuận và phong trào cơ sở của các nhà dịch tễ học từ khắp mọi nơi trên thế giới. Chúng tôi dành thời gian rảnh rỗi của mình để viết và cung cấp tài nguyên này cho cộng đồng. Mọi lời động viên khuyến khích và phản hồi của bạn đều được chúng tôi chào đón:  

* Gửi **[biểu mẫu phản hồi](https://forms.gle/A5SnRVws7tPD15Js9)**  
* Email tới **epiRhandbook@gmail.com** hoặc tweet **[\@epiRhandbook](https://twitter.com/epirhandbook)**  
* Gửi các vấn đề cho chúng tôi tại **[Github repository](https://github.com/epirhandbook/Epi_R_handbook)**  


## Sổ tay này được sử dụng như thế nào  


-   Truy cập các trang trong phần Mục lục, hoặc sử dụng ô tìm kiếm
-   Nhấn biểu tượng "copy" để sao chép code
-   Kết hợp theo dõi cùng với các bộ [dữ liệu minh họa](https://epirhandbook.com/vn/data-used.html#data-used)
-   Xem phần "Tài nguyên" trong từng chương để tìm thêm tài liệu

**Phiên bản ngoại tuyến**

Xem hướng dẫn tại trang [Tải sách và dữ liệu](https://epirhandbook.com/vn/data-used.html#data-used). 




<!-- ======================================================= -->
## Lời cảm ơn

Sổ tay này được tạo ra bởi sự hợp tác của các nhà dịch tễ học từ khắp nơi trên thế giới, đúc kết kinh nghiệm cùng với các tổ chức khác bao gồm các cơ quan y tế địa phương, tiểu bang, tỉnh và quốc gia, Tổ chức Y tế Thế giới (WHO), Tổ chức Bác sỹ không biên giới (MSF), hệ thống các bệnh viện, và các đơn vị nghiên cứu.

Sổ tay này **không phải** là sản phẩm đã được phê duyệt của bất kỳ tổ chức cụ thể nào. Mặc dù chúng tôi cố gắng đảm bảo tính chính xác, nhưng chúng tôi không chịu trách nhiệm về nội dung trong cuốn sách này.

### Những người đóng góp

**Chủ biên:** [Neale Batra](https://www.linkedin.com/in/neale-batra/)

**Nhóm tác giả**: [Neale Batra](https://www.linkedin.com/in/neale-batra/), [Alex Spina](https://github.com/aspina7), [Paula Blomquist](https://www.linkedin.com/in/paula-bianca-blomquist-53188186/), [Finlay Campbell](https://github.com/finlaycampbell), [Henry Laurenson-Schafer](https://github.com/henryls1), [Isaac Florence](www.Twitter.com/isaacatflorence), [Natalie Fischer](https://www.linkedin.com/in/nataliefischer211/), [Aminata Ndiaye](https://twitter.com/aminata_fadl), [Liza Coyer]( https://www.linkedin.com/in/liza-coyer-86022040/), [Jonathan Polonsky](https://twitter.com/jonny_polonsky), [Yurie Izawa](https://ch.linkedin.com/in/yurie-izawa-a1590319), [Chris Bailey](https://twitter.com/cbailey_58?lang=en), [Daniel Molling](https://www.linkedin.com/in/daniel-molling-4005716a/), [Isha Berry](https://twitter.com/ishaberry2), [Emma Buajitti](https://twitter.com/buajitti), [Mathilde Mousset](https://mathildemousset.wordpress.com/research/), [Sara Hollis](https://www.linkedin.com/in/saramhollis/), Wen Lin  

**Nhóm dịch giả**: [Nguyễn Thanh Lương](https://www.linkedin.com/in/ntluong95/), [Nguyễn Thị Khánh Huyền](https://www.linkedin.com/in/huyen-nguyen-thi-khanh-3920b51a6/), Võ Hữu Thuận, Nguyễn Trung Thành, Vũ Thu Hà, [Hồ Hoàng Dung](https://www.linkedin.com/in/dzunggg/)

**Nhóm phản biện**: Pat Keating,  [Amrish Baidjoe](https://twitter.com/Ammer_B), Annick Lenglet, Margot Charette, Danielly Xavier, Marie-Amélie Degail Chabrat, Esther Kukielka, Michelle Sloan, Aybüke Koyuncu, Rachel Burke, Kate Kelsey, [Berhe Etsay](https://www.linkedin.com/in/berhe-etsay-5752b1154/), John Rossow, Mackenzie Zendt, James Wright, Laura Haskins, [Flavio Finger](ffinger.github.io), Tim Taylor, [Jae Hyoung Tim Lee](https://www.linkedin.com/in/jaehyoungtlee/), [Brianna Bradley](https://www.linkedin.com/in/brianna-bradley-bb8658155), [Wayne Enanoria](https://www.linkedin.com/in/wenanoria), Manual Albela Miranda, [Molly Mantus](https://www.linkedin.com/in/molly-mantus-174550150/), Pattama Ulrich, Joseph Timothy, Adam Vaughan, Olivia Varsaneux, Lionel Monteiro, Joao Muianga  

**Hình minh họa**: Calder Fong 


<!-- **Editor-in-Chief:** Neale Batra  -->

<!-- **Project core team:** Neale Batra, Alex Spina, Amrish Baidjoe, Pat Keating, Henry Laurenson-Schafer, Finlay Campbell   -->

<!-- **Authors**: Neale Batra, Alex Spina, Paula Blomquist, Finlay Campbell, Henry Laurenson-Schafer, [Isaac Florence](www.Twitter.com/isaacatflorence), Natalie Fischer, Aminata Ndiaye, Liza Coyer, Jonathan Polonsky, Yurie Izawa, Chris Bailey, Daniel Molling, Isha Berry, Emma Buajitti, Mathilde Mousset, Sara Hollis, Wen Lin   -->

<!-- **Reviewers**: Pat Keating, Mathilde Mousset, Annick Lenglet, Margot Charette, Isha Berry, Paula Blomquist, Natalie Fischer, Daniely Xavier, Esther Kukielka, Michelle Sloan, Aybüke Koyuncu, Rachel Burke, Daniel Molling, Kate Kelsey, Berhe Etsay, John Rossow, Mackenzie Zendt, James Wright, Wayne Enanoria, Laura Haskins, Flavio Finger, Tim Taylor, Jae Hyoung Tim Lee, Brianna Bradley, Manual Albela Miranda, Molly Mantus, Priscilla Spencer, Pattama Ulrich, Joseph Timothy, Adam Vaughan, Olivia Varsaneux, Lionel Monteiro, Joao Muianga   -->


### Tài trợ và hỗ trợ

Sổ tay này nhận được tài trợ thông qua kinh phí hỗ trợ trợ xây dựng năng lực khẩn cấp COVID-19 từ [TEPHINET](https://www.tephinet.org/), mạng lưới toàn cầu của các Chương trình Đào tạo Dịch tễ học Thực địa (FETPs).

Các hỗ trợ hành chính được cung cấp bởi mạng lưới cựu sinh EPIET ([EAN](https://epietalumni.net/)), với lời cảm ơn đặc biệt tới Annika Wendland. EPIET là Chương trình đào tạo Dịch tễ học can thiệp tại Châu Âu.

Đặc biệt gửi lời cảm ơn tới Trung tâm Điều hành Amsterdam (OCA) của Tổ chức Bác sỹ không biên giới (MSF) cho những sự hỗ trợ của họ trong quá trình phát triển cuốn sổ tay này.

*Ấn phẩm này được hỗ trợ bởi Hợp đồng Hợp tác số NU2GGH001873, được tài trợ bởi Trung tâm Kiểm soát và Phòng ngừa Dịch bệnh thông qua TEPHINET, một chương trình của Lực lượng đặc nhiệm về sức khỏe toàn cầu. Nội dung của sổ tay hoàn toàn do tác giả chịu trách nhiệm và đại diện cho quan điểm chính thức của Trung tâm Kiểm soát và Phòng ngừa Dịch bệnh, Bộ Y tế và Dịch vụ Nhân sinh, Lực lượng Đặc nhiệm về Sức khỏe Toàn cầu, hoặc TEPHINET*

### Cảm hứng

Rất nhiều các hướng dẫn và tóm tắt cung cấp kiến thức sử dụng để phát triển nội dung sổ tay này được tham khảo trong các trang nội dung tương ứng.

Một cách tổng quát hơn, các nguồn sau đây đã truyền nguồn cảm hứng cho cuốn sổ tay này:\
[The "R4Epis" project](https://r4epis.netlify.app/) (một sự hợp tác giữa MSF và RECON)\
[R Epidemics Consortium (RECON)](https://www.repidemicsconsortium.org/)\
[R for Data Science book (R4DS)](https://r4ds.had.co.nz/)\
[bookdown: Authoring Books and Technical Documents with R Markdown](https://bookdown.org/yihui/bookdown/)\
[Netlify](https://www.netlify.com) để lưu trữ trang web này


<!-- ### Image credits {-}   -->

<!-- Images in logo from US CDC Public Health Image Library) include [2013 Yemen looking for mosquito breeding sites](https://phil.cdc.gov/Details.aspx?pid=19623), [Ebola virus](https://phil.cdc.gov/Details.aspx?pid=23186), and [Survey in Rajasthan](https://phil.cdc.gov/Details.aspx?pid=19838).   -->


## Điều khoản sử dụng và đóng góp

### Giấy phép

<a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/"><img src="https://i.creativecommons.org/l/by-nc-sa/4.0/88x31.png" alt="Creative Commons License" style="border-width:0"/></a><br />Sổ tay này được cấp phép theo <a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/">Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License</a>.

Chúng tôi khuyến khích các khóa học và các chương trình đào tạo dịch tễ sử dụng cuốn sổ tay này cho sinh viên của mình. Nếu bạn có thắc mắc về mục đích sử dụng của mình, hãy gửi email tới [**epiRhandbook\@gmail.com**](mailto:epiRhandbook@gmail.com).

### Trích dẫn

Neale Batra và cộng sự, Cẩm nang Dịch tễ học với R. <a rel="license" href="https://zenodo.org/badge/231610102.svg"><img src="https://zenodo.org/badge/231610102.svg" alt="DOI" style="border-width:0"/></a><br />

### Đóng góp

Nếu bạn muốn đóng góp nội dung, vui lòng liên hệ với chúng tôi thông qua Github hoặc email. Chúng tôi đang triển khai lịch trình cập nhật cho cuốn sách cũng như xây dựng hướng dẫn dành cho cộng tác viên.

Xin lưu ý rằng dự án epiRhandbook được phát hành cùng với bộ [Quy tắc ứng xử của cộng tác viên](https://contributor-covenant.org/version/2/0/CODE_OF_CONDUCT.html). Bằng cách đóng góp cho dự án này, bạn đồng ý tuân theo các điều khoản của nó.