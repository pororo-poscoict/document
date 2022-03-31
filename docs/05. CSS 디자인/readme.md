# CSS 사용 예시

### Button

```html
<button id="scm_button">조회</button>
```

### Input

```html
<div id="scm-input-parent-div">
	<div id="scm-input-div">
		<input id="scm-input" autocomplete="off" type="text" required/>
		<label id="scm-input-label" for="scm-input"><span id="scm-input-label-span">법인</span></label>
	</div>
	<div id="scm-input-div">
		<input id="scm-input" autocomplete="off" type="text" required/>
		<label id="scm-input-label" for="scm-input"><span id="scm-input-label-span">OrderNo</span></label>
	</div>
</div>
```

### label

```html
<label id="scm-label">법인</label>
```

### select

```html
<select id="scm-select" name="GCS_COMP_CODE">
   <option value="POSCO" selected>POSCO</option>
   <option value="SAMSUNG">SAMSUNG</option>
   <option value="KAKAO">KAKAO</option>
</select>
```

### table

```html
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/twitter-bootstrap/5.0.1/css/bootstrap.min.css" />
<link rel="stylesheet" href="https://cdn.datatables.net/1.11.5/css/dataTables.bootstrap5.min.css" />
```

head 앞에 해당 link 태그를 넣는다.

<br/>
<br/>

```html
<script src="./assets/js/app.js"></script>
<script src="https://code.jquery.com/jquery-3.5.1.js"></script>
<script src="https://cdn.datatables.net/1.11.5/js/jquery.dataTables.min.js"></script>
<script src="https://cdn.datatables.net/1.11.5/js/dataTables.bootstrap5.min.js"></script>
```

![KakaoTalk_Photo_2022-03-31-17-03-14](https://user-images.githubusercontent.com/66767038/161011030-56afdbf3-c4d4-476f-8a0a-ac656208c96a.png)

body태그 앞에 script 태그를 넣는다.

<br/>
<br/>

```jsx
$(document).ready(function() {
    $('#example').DataTable();
} );
```

![KakaoTalk_Photo_2022-03-31-16-59-19](https://user-images.githubusercontent.com/66767038/161011021-51c08070-b57b-4b09-8804-0f94934921c3.png)

js에 app.js를 넣는다.

<br/>
<br/>

```html
<!-- Tables -->
      <div class = "table-container container">
        <div class = "row">
        <table id="example" class="content-table table table-striped" style="width:100%">
          <thead>
              <tr>
                  <th class = "col-1">SEQ</th>
                  <th class = "col-1">상태</th>
                  <th class = "col-1">OrderNo</th>
                  <th class = "col-1">수주</th>
                  <th class = "col-1">품명</th>
                  <th class = "col-5">확정통과공정</th>
                  <th class = "col-3">생산기한</th>
                  <th class = "col-1">용도</th>
                  <th class = "col-3">주문 SIZE</th>
                  <th class = "col-1">단중</th>
                  <th class = "col-3">출강목표</th>
                  <th class = "col-1">EDGE</th>
                  <th class = "col-1">고객사명</th>
                  <th class = "col-1">주문량</th>
              </tr>
          </thead>
          <tbody>
              <tr>
                  <td>System Architect</td>
                  <td>Edinburgh</td>
                  <td>61</td>
                  <td>2011/04/25</td>
                  <td>$320,800</td>
                  <td>Tiger Nixon</td>
                  <td>System Architect</td>
                  <td>Edinburgh</td>
                  <td>61</td>
                  <td>2011/04/25</td>
                  <td>$320,800</td>
                  <td>Tiger Nixon</td>
                  <td>System Architect</td>
                  <td>Edinburgh</td>
              </tr>
          </tbody>
        </table>
      </div>
    </div>
```

샘플코드