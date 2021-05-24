

<script language="javascript" src="/js/jquery-3.6.0.min.js"></script>
<script type="text/javascript">

    $(document).ready(function() {
        var mall_arr = ['mall0025^^11번가','mall0010^^지마켓','mall0003^^(주)옥션','mall0148^^스마트스토어','mall0184^^쿠팡','mall0012^^(주)인터파크','mall0287^^위메프 파트너2.0','mall0182^^티몬','mall0247^^고도몰5','mall0021^^GS홈쇼핑','mall0020^^CJ온스타일','mall0022^^(주)롯데닷컴','mall0177^^위메프','mall0037^^롯데아이몰','mall0015^^(주)현대홈쇼핑','mall0170^^신세계닷컴2.0','mall0321^^롯데온','mall0286^^카카오톡 스토어','mall0033^^AK몰','mall0284^^카페24','mall0063^^이마트','mall0036^^하프클럽','mall0038^^NS홈쇼핑','mall0060^^1300K','mall0164^^홈앤쇼핑','mall0206^^멸치쇼핑','mall0194^^고도몰','mall0044^^패션플러스','mall0046^^이지웰','mall0094^^바보사랑','mall0054^^아이스타일24(주)','mall0297^^도매꾹','mall0023^^(주)위즈위드','mall0211^^다이소몰','mall0264^^네이버페이','mall0056^^홈플러스','mall0238^^오너클랜(왕도매)','mall0147^^한화갤러리아','mall0305^^10X10','mall0079^^YES24','mall0110^^NH마켓','mall0153^^교보핫트랙스','mall0168^^아트박스','mall0187^^롯데백화점몰','mall0245^^이랜드리테일','mall0181^^하이마트','mall0048^^LF','mall0159^^롯데마트','mall0192^^무신사스토어','mall0113^^오셀러','mall0242^^공영홈쇼핑','mall0258^^머스트잇','mall0212^^K쇼핑','mall0337^^SSG오픈마켓','mall0229^^인터파크 비즈마켓','mall0216^^신세계백화점','mall0266^^SK스토아','mall0276^^베네피아','mall0068^^PLAYER','mall0104^^세상N','mall0202^^WCONCEPT','mall0180^^웰스토리몰2.0','mall0132^^위핑(구:이룬마켓)','mall0219^^후추통','mall0251^^신세계TV쇼핑','mall0291^^펀앤쇼핑','mall0207^^스킨알엑스','mall0220^^AK백화점','mall0201^^(주)현대백화점','mall0289^^쇼핑엔티','mall0160^^가방팝','mall0176^^파미웰','mall0241^^우먼스톡','mall0339^^보리보리','mall0230^^(주)더현대몰','mall0051^^여인닷컴','mall0231^^삼성카드','mall0163^^레이틀리','mall0308^^컴퓨존','mall0156^^GS리테일 복지몰','mall0152^^엔조이뉴욕(레더스)','mall0283^^서울스토어','mall0196^^제로투세븐','mall0222^^한국뱅크앤컴퍼니','mall0227^^리본즈코리아','mall0090^^2001아울렛','mall0288^^크런치 프라이스','mall0226^^농협a마켓','mall0296^^힙합퍼','mall0252^^케이그룹','mall0265^^위메프 셀러마켓','mall0235^^(주)현대리바트','mall0078^^인터파크도서','mall0172^^지트리트','mall0327^^W쇼핑','mall0145^^SBS골프숍','mall0290^^롯데슈퍼','mall0307^^도매의신','mall0333^^몽땅뚝딱몰','mall0300^^하우스미디어','mall0135^^알라딘(SCM)','mall0280^^SSF SHOP','mall0317^^샵바이','mall0186^^아이몰7','mall0208^^골핑','mall0139^^키드키즈','mall0175^^아이스탁몰','mall0119^^홀리스퀘어','mall0173^^와이티몰(놀부닷컴)','mall0237^^ETAH','mall0282^^NCP','mall0085^^웰베이','mall0239^^에듀팡','mall0234^^무궁화 꽃이 피었습니다','mall0311^^우리샵','mall0205^^오테이스트몰','mall0223^^판다코리아','mall0257^^에이랜드','mall0323^^스페셜오퍼','mall0255^^마리오아울렛','mall0329^^셀렉온','mall0200^^엔샵','mall0275^^티빙몰','mall0279^^홈데이몰','mall0281^^놀다가게','mall0330^^까사미아','mall0295^^스마트스코어','mall0301^^투비즈온','mall0136^^알라딘(오픈마켓)','mall0221^^원더플레이스','mall0298^^설성푸드주식회사','mall0302^^LF스퀘어','mall0309^^코즈몰','mall0224^^엘샵','mall0233^^먼슬러','mall0254^^바이폴','mall0268^^스메그코리아','mall0250^^루이스클럽','mall0174^^스타일아이디','mall0269^^슈나이더','mall0324^^T셀파몰','mall0325^^씨스토어','mall0267^^엔터식스','mall0299^^jtbcgolf','mall0316^^어라운드더코너','mall0340^^코오롱몰','mall0341^^알렛츠샵','mall0204^^YIC컴퍼니','mall0179^^스토리웨이몰','mall0195^^티어제로','mall0246^^쇼핑파이','mall0262^^우마켓','mall0274^^멍도리','mall0292^^모게요','mall0338^^골디닷컴','mall0188^^베이스존','mall0213^^알람몰','mall0232^^에이지몰','mall0243^^FINDEN','mall0244^^허그몰','mall0306^^푸딩','mall0322^^패디코리아','mall0332^^LG하우시스 지인몰','mall0215^^하이웨이마트','mall0342^^스타일크루','mall0263^^마카롱팩토리','mall0303^^지니프렌즈'];
        var mall_status = ['Y^^Y^^Y^^Y^^Y^^Y','Y^^Y^^Y^^Y^^Y^^Y','Y^^Y^^Y^^Y^^Y^^Y','Y^^Y^^Y^^Y^^Y^^Y','Y^^Y^^Y^^Y^^Y^^Y','Y^^Y^^Y^^Y^^Y^^Y','Y^^Y^^Y^^Y^^Y^^Y','Y^^Y^^Y^^Y^^Y^^Y','Y^^Y^^Y^^Y^^A^^Y','Y^^Y^^Y^^Y^^Y^^Y','Y^^Y^^Y^^Y^^Y^^Y','Y^^Y^^Y^^Y^^Y^^Y','Y^^Y^^Y^^Y^^Y^^N','Y^^Y^^Y^^Y^^Y^^Y','Y^^Y^^Y^^Y^^Y^^Y','Y^^Y^^Y^^Y^^Y^^Y','Y^^Y^^Y^^Y^^Y^^Y','Y^^Y^^Y^^Y^^Y^^Y','Y^^Y^^Y^^Y^^Y^^Y','Y^^Y^^Y^^Y^^A^^Y','Y^^Y^^Y^^Y^^Y^^Y','Y^^Y^^Y^^Y^^Y^^Y','Y^^Y^^Y^^Y^^Y^^A','Y^^Y^^Y^^Y^^A^^Y','Y^^Y^^Y^^Y^^Y^^N','Y^^Y^^Y^^Y^^Y^^N','Y^^Y^^Y^^Y^^N^^Y','Y^^Y^^Y^^Y^^Y^^Y','Y^^Y^^Y^^Y^^Y^^Y','Y^^Y^^Y^^Y^^N^^Y','Y^^Y^^Y^^Y^^Y^^Y','Y^^Y^^Y^^Y^^Y^^Y','Y^^Y^^Y^^Y^^N^^Y','Y^^Y^^Y^^Y^^Y^^Y','N^^N^^Y^^Y^^N^^N','Y^^Y^^Y^^Y^^Y^^Y','Y^^Y^^Y^^Y^^A^^Y','Y^^Y^^Y^^Y^^Y^^Y','Y^^Y^^Y^^Y^^Y^^Y','Y^^Y^^Y^^Y^^Y^^N','Y^^Y^^N^^N^^N^^N','Y^^Y^^Y^^Y^^A^^Y','Y^^Y^^Y^^Y^^Y^^Y','Y^^Y^^Y^^Y^^Y^^Y','Y^^Y^^Y^^Y^^N^^Y','Y^^Y^^Y^^Y^^Y^^Y','Y^^Y^^Y^^Y^^A^^N','Y^^Y^^Y^^Y^^N^^N','Y^^Y^^Y^^Y^^N^^Y','N^^N^^Y^^Y^^N^^N','Y^^Y^^Y^^Y^^Y^^Y','Y^^Y^^Y^^Y^^Y^^Y','Y^^Y^^Y^^Y^^N^^Y','Y^^Y^^N^^N^^N^^N','Y^^Y^^Y^^Y^^N^^N','Y^^Y^^N^^N^^N^^N','Y^^Y^^Y^^Y^^Y^^Y','Y^^Y^^Y^^Y^^Y^^Y','Y^^Y^^Y^^Y^^N^^Y','Y^^Y^^Y^^Y^^N^^Y','Y^^Y^^Y^^Y^^Y^^Y','Y^^Y^^Y^^Y^^N^^Y','Y^^Y^^Y^^Y^^N^^Y','Y^^Y^^Y^^Y^^N^^Y','Y^^Y^^Y^^Y^^N^^Y','Y^^Y^^Y^^Y^^Y^^Y','Y^^Y^^Y^^Y^^Y^^Y','Y^^Y^^Y^^Y^^Y^^Y','Y^^Y^^Y^^N^^Y^^Y','Y^^Y^^Y^^Y^^Y^^Y','Y^^Y^^Y^^Y^^N^^N','Y^^Y^^Y^^Y^^N^^Y','Y^^Y^^Y^^Y^^Y^^Y','Y^^Y^^Y^^Y^^Y^^Y','Y^^Y^^A^^A^^Y^^A','Y^^Y^^Y^^Y^^N^^N','Y^^Y^^Y^^Y^^Y^^A','Y^^Y^^Y^^Y^^N^^Y','Y^^Y^^Y^^Y^^Y^^Y','Y^^Y^^Y^^Y^^N^^Y','Y^^Y^^Y^^Y^^N^^Y','Y^^Y^^Y^^Y^^Y^^Y','Y^^Y^^Y^^Y^^N^^Y','Y^^Y^^Y^^Y^^N^^N','Y^^Y^^Y^^Y^^N^^Y','Y^^Y^^Y^^Y^^N^^Y','Y^^Y^^Y^^Y^^N^^Y','Y^^Y^^Y^^Y^^Y^^Y','Y^^Y^^Y^^Y^^Y^^Y','Y^^Y^^Y^^Y^^Y^^Y','Y^^Y^^N^^N^^N^^N','Y^^Y^^Y^^Y^^Y^^Y','Y^^Y^^Y^^Y^^N^^N','Y^^Y^^Y^^Y^^N^^Y','Y^^Y^^Y^^Y^^Y^^Y','Y^^Y^^Y^^Y^^N^^N','Y^^Y^^Y^^Y^^N^^A','Y^^Y^^Y^^Y^^Y^^Y','Y^^Y^^Y^^Y^^Y^^Y','Y^^Y^^Y^^Y^^Y^^Y','Y^^Y^^Y^^Y^^N^^Y','Y^^Y^^Y^^Y^^Y^^Y','Y^^Y^^Y^^Y^^A^^Y','Y^^Y^^Y^^Y^^N^^Y','Y^^Y^^Y^^Y^^N^^Y','Y^^N^^N^^N^^N^^N','Y^^Y^^Y^^Y^^N^^Y','Y^^Y^^Y^^Y^^N^^N','Y^^Y^^Y^^Y^^N^^Y','Y^^Y^^Y^^Y^^Y^^Y','Y^^Y^^Y^^Y^^Y^^Y','Y^^Y^^Y^^Y^^N^^N','Y^^Y^^Y^^Y^^Y^^Y','Y^^Y^^Y^^Y^^A^^A','Y^^Y^^Y^^Y^^Y^^Y','Y^^Y^^Y^^Y^^N^^Y','Y^^Y^^Y^^Y^^N^^N','Y^^Y^^Y^^Y^^Y^^Y','Y^^Y^^Y^^Y^^Y^^Y','Y^^Y^^Y^^Y^^N^^Y','Y^^Y^^Y^^Y^^Y^^Y','Y^^Y^^Y^^Y^^N^^N','Y^^Y^^Y^^Y^^Y^^N','Y^^Y^^Y^^Y^^Y^^Y','Y^^Y^^Y^^Y^^A^^Y','Y^^Y^^Y^^Y^^Y^^Y','Y^^Y^^Y^^Y^^Y^^Y','Y^^Y^^Y^^Y^^Y^^Y','Y^^Y^^Y^^Y^^N^^Y','Y^^Y^^Y^^Y^^Y^^Y','Y^^Y^^Y^^Y^^N^^Y','Y^^Y^^Y^^Y^^N^^Y','Y^^Y^^Y^^Y^^Y^^Y','Y^^Y^^A^^A^^A^^A','Y^^Y^^Y^^Y^^Y^^Y','Y^^Y^^Y^^Y^^N^^Y','Y^^Y^^Y^^Y^^A^^Y','Y^^Y^^Y^^Y^^A^^Y','Y^^Y^^Y^^Y^^N^^N','Y^^Y^^Y^^Y^^A^^Y','Y^^Y^^Y^^Y^^Y^^Y','Y^^Y^^Y^^Y^^Y^^Y','Y^^Y^^Y^^Y^^N^^Y','Y^^Y^^Y^^Y^^Y^^Y','Y^^Y^^Y^^Y^^N^^Y','Y^^Y^^Y^^Y^^N^^Y','Y^^Y^^Y^^Y^^Y^^Y','Y^^Y^^Y^^Y^^N^^N','Y^^Y^^Y^^Y^^Y^^Y','Y^^Y^^Y^^Y^^N^^Y','Y^^Y^^Y^^Y^^Y^^A','Y^^Y^^Y^^Y^^Y^^Y','Y^^Y^^Y^^Y^^A^^A','Y^^Y^^Y^^Y^^Y^^Y','Y^^Y^^Y^^Y^^Y^^Y','Y^^Y^^Y^^N^^N^^N','Y^^Y^^Y^^Y^^N^^Y','Y^^Y^^Y^^Y^^A^^A','Y^^Y^^Y^^Y^^Y^^Y','Y^^Y^^Y^^Y^^Y^^Y','Y^^Y^^Y^^Y^^Y^^Y','Y^^Y^^Y^^Y^^Y^^Y','Y^^Y^^Y^^Y^^Y^^Y','Y^^Y^^Y^^Y^^N^^Y','Y^^Y^^Y^^Y^^Y^^N','N^^N^^Y^^Y^^Y^^Y','Y^^Y^^Y^^Y^^Y^^Y'];

        var table_txt = "";
        for(var i = 0; i < mall_arr.length; i++){
            var mall_info = mall_arr[i].split("^^");
            var mall_info2 = mall_status[i].split("^^");
            table_txt += "<tr>";
            table_txt += "<td><img src='https://www.shoplinker.co.kr/images/mall/apply/ico_"+mall_info[0]+".png' /></td>";
            table_txt += "<td><a href='/mall/"+mall_info[0]+"/'>"+mall_info[1]+"</a></td>";
            for(var ii = 0; ii < 6; ii++){
                var use_txt = "X";
                if(mall_info2[ii] == "Y"){use_txt = "O";}
                table_txt += "<td>"+use_txt+"</td>";
            }
            table_txt += "</tr>";
        }
        $("#all_body").html(table_txt);
    });

</script>

# 쇼핑몰 안내

--- 

<html>

<p id="aaa"></p>
<div class="content-wrap">
    <div class="mall-wrap">
        <div class="mall-search-wrap">
            <div class="mall-search-box">
                <div class="mall-search-word">
                    <input type="text" title="쇼핑몰 검색" />
                    <button type="button">검색</button>
                </div>
                <span class="all-view"><button type="button">전체보기</button></span>
            </div>
            <ul class="mall-search-btn">
            </ul>
        </div>
    </div>
    <table class="new-support-mall">
        <thead>
            <tr>
                <th scope="col">쇼핑몰</th>
                <th scope="col">쇼핑몰명</th>
                <th scope="col">상품<br>등록</th>
                <th scope="col">상품<br>수정</th>
                <th scope="col">주문<br>수집</th>
                <th scope="col">송장<br>전송</th>
                <th scope="col">문의<br>후기</th>
                <th scope="col">클레임</th>
            </tr>
        </thead>
        <tbody id = "all_body">
        </tbody>
    </table>
</div>

</html>


<script type="text/javascript">
    $(".mall-search-word button").on("click",function(){
        var schTxt = $(this).prev().val();
        if(!schTxt){
            alert("검색하실 쇼핑몰명을 입력해주세요");
        }else{
            sortKeyword(schTxt);
        };
        return false;
    });

    // 키워드 검색
    function sortKeyword(txt){
        var sortMallEl = $('.new-support-mall tbody tr');
        var resultItem = sortMallEl.filter(function(idx,value){
            return $(value).find('td').eq(1).text().indexOf(txt) >= 0
        });
        if(resultItem.length){
             sortMallEl.show().not(resultItem).hide();
        }else{
            var el = '<tr><td colspan="8" class="no-data"><img src="/images/bg/bg_no_data.png" alt="" /> <strong>'+txt+'</strong> 에 대한 검색 결과가 없습니다</td></tr>';
            sortMallEl.hide();
            sortMallEl.parent().append(el);
            $(".no-data").show();
        };
        $(window).scrollTop(schBoxPos);
    };
</script>