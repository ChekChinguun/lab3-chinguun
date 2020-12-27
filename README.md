<!DOCTYPE html>
<html>
<head>
	<title>Lab 2 Chinguun</title>
	<style>
		#bigTable{  
		  width: 40%;
		  display: flex;
		  font-size: 12px;
		}
		.firstRow{
		  text-align: center;
		}
		.secondRow{
		  text-align: center;
		  background-color: orange;
		}
		.firstColumn{
		  background-color: yellow;
		}
		.rowCol{
		  text-align: center;
		  background-color: green;
		}
		.lastCol{
		  background-color: yellow;
		}
		.lastRow{
		  background-color: orange;
		}
		.firstImage{
		  height: 50px;
		  width: 50px;
		  display: block;
		  margin-left: auto;
		  margin-right: auto;
		}
	</style>
</head>
<body>
	<table border="1" id="bigTable">
		<tr>
			<td><img src="https://news.num.edu.mn/wp-content/uploads/2016/09/muis-logo.png" alt="МУИС logo" class="firstImage"></td>
			<td colspan="3" class="firstRow"><h1>МОНГОЛ УЛСЫН ИХ СУРГУУЛЬ</h1></td>
		</tr>
		<tr class="secondRow">
			<td colspan="4"><h2>Эрдмийн хэт цахиваас Хөгжлийн гал бадармой</h2></td>
		</tr>
		<tr>	
			<td rowspan="2" class="firstColumn">
				<h4>Цэс</h4>
				<ul class="firstList">
					<a href="https://www.num.edu.mn/"><li class="calibre12">Нүүр хуудас</li></a>
					<a href="https://elselt.num.edu.mn/"><li class="calibre12">Элсэлт</li></a>
					<a href="https://news.num.edu.mn/"><li class="calibre12">Мэдээ</li></a>
					<a href="https://www.num.edu.mn/researchmon"><li class="calibre12">Судалгаа</li></a>
				</ul>
			</td>
			<td rowspan="2"><img src="https://news.num.edu.mn/wp-content/uploads/2020/09/119916424_3461051250622645_6235753213183607063_n.jpg" alt="МУИС, Монгол банк" style="height: 100px; width: 125px;"></td>
			<td class="rowCol" class="shrinkCol"><h4>Мэдээлэл</h4></td>
			<td rowspan="2" class="lastCol">
				<h4 class="calibre10">Архив</h4>
				<ol type="I" start="3" class="secondList">
					<a href="https://elselt.num.edu.mn/?page_id=12"><li class="calibre12">Элсэлт эхэллээ</li></a>
  					<a href="https://elselt.num.edu.mn/?page_id=193"><li class="calibre12">Сургалтын бүртгэл явагдаж байна</li></a>
  					<a href="https://student.num.edu.mn/?p=7718"><li class="calibre12">Оюутны хурал болно</li></a>
				</ol>
			</td>
		</tr>
		<tr class="shrinkCol">
			<td><h4>Монгол Улсын Их Сургууль Монголбанктай хамтын ажиллагааны гэрээ байгууллаа</h4>
			Монгол Улсын Их Сургууль Монголбанкны эдийн засаг, санхүүгийн чиглэлийн судалгаа, сургалтыг дэмжих “Тинк банк” хөтөлбөрийн хүрээнд хамтын ажиллагааны гэрээ байгууллаа. Энэхүү хөтөлбөр нь эдийн засаг, санхүүгийн чиглэлээр судалгааны магистрын түвшинд суралцаж буй оюутнуудын судалгааны чанарыг сайжруулах, Монголбанкны болон хөндлөнгийн судлаачдын хамтын ажиллагааг ахиулах, судлаачдын бүтээлийг олон нийтэд түгээх, бодлого боловсруулахад оролцох оролцоог нь нэмэгдүүлэх зорилготой юм.</td>
		</tr>
		<tr>
			<td colspan="4" class="lastRow">Бүх эрх хуулиар хамгаалагдсан</td>
		</tr>
	</table>
</body>
</html>
