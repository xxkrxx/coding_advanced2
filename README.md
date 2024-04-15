# coding_advanced2

<script>
  $(document).ready(function(){ // ドキュメントの準備ができたときに以下の処理を実行する
    $(".title").click(function(){ // タイトル要素がクリックされたときに以下の処理を実行する
      $(this).next('.list').slideToggle(); // クリックされたタイトル要素の次の兄弟要素で、クラスが 'list' の要素をスライドトグルする
    });
  });
</script>

thisは、「クリックされた要素」を示す。
.next('.list')  クリックされた.title要素の次の兄弟要素で、クラスが list に一致する要素を取得
.slideToggle(): 要素をスライドで表示または非表示に切り替え 
                要素が表示されている場合は非表示にし、非表示の場合は表示する