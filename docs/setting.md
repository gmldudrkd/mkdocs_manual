<script language="javascript" src="https://gmldudrkd.github.io/mkdocs_manual/js/jquery-3.6.0.min.js "></script>
<script type="text/javascript">

    $(document).ready(function() {
        /*쇼핑몰 DB셀렉 기준 : SELECT a.mall_id,a.mall_name,a.step01,a.step02,a.step03,a.step04,a.step05,a.step06 FROM mall_info a LEFT JOIN customer_mall_info b ON a.mall_id=b.mall_id WHERE a.charge_status='y' AND a.type!='자사몰' AND a.type!='해외쇼핑몰' AND !(a.step01 != 'Y' AND a.step02 != 'Y' AND a.step03 != 'Y' AND a.step04 != 'Y' AND a.step05 != 'Y' AND a.step06 != 'Y') GROUP BY a.mall_id ORDER BY a.mall_id asc;*/

        /*menu_yn : 쇼핑몰 메뉴얼 존재여부*/
        var menu_yn = [];
        menu_yn["mall0003"] = "Y";
        menu_yn["mall0010"] = "N";
        menu_yn["mall0012"] = "N";
        menu_yn["mall0015"] = "N";
        menu_yn["mall0020"] = "N";
        menu_yn["mall0021"] = "N";
        menu_yn["mall0022"] = "N";
        menu_yn["mall0023"] = "N";
        menu_yn["mall0025"] = "Y";
        menu_yn["mall0033"] = "N";
        menu_yn["mall0036"] = "N";
        menu_yn["mall0037"] = "N";
        menu_yn["mall0038"] = "N";
        menu_yn["mall0044"] = "N";
        menu_yn["mall0046"] = "N";
        menu_yn["mall0048"] = "N";
        menu_yn["mall0051"] = "N";
        menu_yn["mall0054"] = "N";
        menu_yn["mall0056"] = "N";
        menu_yn["mall0060"] = "N";
        menu_yn["mall0063"] = "N";
        menu_yn["mall0068"] = "N";
        menu_yn["mall0078"] = "N";
        menu_yn["mall0079"] = "N";
        menu_yn["mall0085"] = "N";
        menu_yn["mall0090"] = "N";
        menu_yn["mall0094"] = "N";
        menu_yn["mall0104"] = "N";
        menu_yn["mall0110"] = "N";
        menu_yn["mall0113"] = "N";
        menu_yn["mall0119"] = "N";
        menu_yn["mall0132"] = "N";
        menu_yn["mall0135"] = "N";
        menu_yn["mall0136"] = "N";
        menu_yn["mall0139"] = "N";
        menu_yn["mall0145"] = "N";
        menu_yn["mall0147"] = "N";
        menu_yn["mall0148"] = "Y";
        menu_yn["mall0152"] = "N";
        menu_yn["mall0153"] = "N";
        menu_yn["mall0156"] = "N";
        menu_yn["mall0159"] = "N";
        menu_yn["mall0160"] = "N";
        menu_yn["mall0163"] = "N";
        menu_yn["mall0164"] = "N";
        menu_yn["mall0168"] = "N";
        menu_yn["mall0170"] = "N";
        menu_yn["mall0172"] = "N";
        menu_yn["mall0173"] = "N";
        menu_yn["mall0174"] = "N";
        menu_yn["mall0175"] = "N";
        menu_yn["mall0176"] = "N";
        menu_yn["mall0177"] = "N";
        menu_yn["mall0179"] = "N";
        menu_yn["mall0180"] = "N";
        menu_yn["mall0181"] = "N";
        menu_yn["mall0182"] = "N";
        menu_yn["mall0184"] = "N";
        menu_yn["mall0186"] = "N";
        menu_yn["mall0187"] = "N";
        menu_yn["mall0188"] = "N";
        menu_yn["mall0192"] = "N";
        menu_yn["mall0194"] = "N";
        menu_yn["mall0195"] = "N";
        menu_yn["mall0196"] = "N";
        menu_yn["mall0200"] = "N";
        menu_yn["mall0201"] = "N";
        menu_yn["mall0202"] = "N";
        menu_yn["mall0204"] = "N";
        menu_yn["mall0205"] = "N";
        menu_yn["mall0206"] = "N";
        menu_yn["mall0207"] = "N";
        menu_yn["mall0208"] = "N";
        menu_yn["mall0211"] = "N";
        menu_yn["mall0212"] = "N";
        menu_yn["mall0213"] = "N";
        menu_yn["mall0215"] = "N";
        menu_yn["mall0216"] = "N";
        menu_yn["mall0219"] = "N";
        menu_yn["mall0220"] = "N";
        menu_yn["mall0221"] = "N";
        menu_yn["mall0222"] = "N";
        menu_yn["mall0223"] = "N";
        menu_yn["mall0224"] = "N";
        menu_yn["mall0226"] = "N";
        menu_yn["mall0227"] = "N";
        menu_yn["mall0229"] = "N";
        menu_yn["mall0230"] = "N";
        menu_yn["mall0231"] = "N";
        menu_yn["mall0232"] = "N";
        menu_yn["mall0233"] = "N";
        menu_yn["mall0234"] = "N";
        menu_yn["mall0235"] = "N";
        menu_yn["mall0237"] = "N";
        menu_yn["mall0238"] = "N";
        menu_yn["mall0239"] = "N";
        menu_yn["mall0241"] = "N";
        menu_yn["mall0242"] = "N";
        menu_yn["mall0243"] = "N";
        menu_yn["mall0244"] = "N";
        menu_yn["mall0245"] = "N";
        menu_yn["mall0246"] = "N";
        menu_yn["mall0247"] = "N";
        menu_yn["mall0250"] = "N";
        menu_yn["mall0251"] = "N";
        menu_yn["mall0252"] = "N";
        menu_yn["mall0254"] = "N";
        menu_yn["mall0255"] = "N";
        menu_yn["mall0257"] = "N";
        menu_yn["mall0258"] = "N";
        menu_yn["mall0262"] = "N";
        menu_yn["mall0263"] = "N";
        menu_yn["mall0264"] = "N";
        menu_yn["mall0265"] = "N";
        menu_yn["mall0266"] = "N";
        menu_yn["mall0267"] = "N";
        menu_yn["mall0268"] = "N";
        menu_yn["mall0269"] = "N";
        menu_yn["mall0274"] = "N";
        menu_yn["mall0275"] = "N";
        menu_yn["mall0276"] = "N";
        menu_yn["mall0279"] = "N";
        menu_yn["mall0280"] = "N";
        menu_yn["mall0281"] = "N";
        menu_yn["mall0282"] = "N";
        menu_yn["mall0283"] = "N";
        menu_yn["mall0284"] = "Y";
        menu_yn["mall0286"] = "N";
        menu_yn["mall0287"] = "N";
        menu_yn["mall0288"] = "N";
        menu_yn["mall0289"] = "N";
        menu_yn["mall0290"] = "N";
        menu_yn["mall0291"] = "N";
        menu_yn["mall0292"] = "N";
        menu_yn["mall0295"] = "N";
        menu_yn["mall0296"] = "N";
        menu_yn["mall0297"] = "N";
        menu_yn["mall0298"] = "N";
        menu_yn["mall0299"] = "N";
        menu_yn["mall0300"] = "N";
        menu_yn["mall0301"] = "N";
        menu_yn["mall0302"] = "N";
        menu_yn["mall0303"] = "N";
        menu_yn["mall0305"] = "N";
        menu_yn["mall0306"] = "N";
        menu_yn["mall0307"] = "N";
        menu_yn["mall0308"] = "N";
        menu_yn["mall0309"] = "N";
        menu_yn["mall0311"] = "N";
        menu_yn["mall0316"] = "N";
        menu_yn["mall0317"] = "N";
        menu_yn["mall0321"] = "N";
        menu_yn["mall0322"] = "N";
        menu_yn["mall0323"] = "N";
        menu_yn["mall0324"] = "N";
        menu_yn["mall0325"] = "N";
        menu_yn["mall0327"] = "N";
        menu_yn["mall0329"] = "N";
        menu_yn["mall0330"] = "N";
        menu_yn["mall0332"] = "N";
        menu_yn["mall0333"] = "N";
        menu_yn["mall0337"] = "N";
        menu_yn["mall0338"] = "N";
        menu_yn["mall0339"] = "N";
        menu_yn["mall0340"] = "N";
        menu_yn["mall0341"] = "N";
        menu_yn["mall0342"] = "N";

        /*mall_arr : 노출쇼핑몰 및 기능지원여부*/
        var mall_arr = [];
        mall_arr.push("mall0003^^(주)옥션^^Y^^Y^^Y^^Y^^Y^^Y");
        mall_arr.push("mall0010^^지마켓^^Y^^Y^^Y^^Y^^Y^^Y");
        mall_arr.push("mall0012^^(주)인터파크^^Y^^Y^^Y^^Y^^Y^^Y");
        mall_arr.push("mall0015^^(주)현대홈쇼핑^^Y^^Y^^Y^^Y^^Y^^Y");
        mall_arr.push("mall0020^^CJ온스타일^^Y^^Y^^Y^^Y^^Y^^Y");
        mall_arr.push("mall0021^^GS홈쇼핑^^Y^^Y^^Y^^Y^^Y^^Y");
        mall_arr.push("mall0022^^(주)롯데닷컴^^Y^^Y^^Y^^Y^^Y^^Y");
        mall_arr.push("mall0023^^(주)위즈위드^^Y^^Y^^Y^^Y^^N^^Y");
        mall_arr.push("mall0025^^11번가^^Y^^Y^^Y^^Y^^Y^^Y");
        mall_arr.push("mall0033^^AK몰^^Y^^Y^^Y^^Y^^Y^^Y");
        mall_arr.push("mall0036^^하프클럽^^Y^^Y^^Y^^Y^^Y^^Y");
        mall_arr.push("mall0037^^롯데아이몰^^Y^^Y^^Y^^Y^^Y^^Y");
        mall_arr.push("mall0038^^NS홈쇼핑^^Y^^Y^^Y^^Y^^Y^^A");
        mall_arr.push("mall0044^^패션플러스^^Y^^Y^^Y^^Y^^Y^^Y");
        mall_arr.push("mall0046^^이지웰^^Y^^Y^^Y^^Y^^Y^^Y");
        mall_arr.push("mall0048^^LF^^Y^^Y^^Y^^Y^^A^^N");
        mall_arr.push("mall0051^^여인닷컴^^Y^^Y^^Y^^Y^^N^^N");
        mall_arr.push("mall0054^^아이스타일24(주)^^Y^^Y^^Y^^Y^^Y^^Y");
        mall_arr.push("mall0056^^홈플러스^^Y^^Y^^Y^^Y^^Y^^Y");
        mall_arr.push("mall0060^^1300K^^Y^^Y^^Y^^Y^^A^^Y");
        mall_arr.push("mall0063^^이마트^^Y^^Y^^Y^^Y^^Y^^Y");
        mall_arr.push("mall0068^^PLAYER^^Y^^Y^^Y^^Y^^N^^Y");
        mall_arr.push("mall0078^^인터파크도서^^Y^^Y^^Y^^Y^^N^^N");
        mall_arr.push("mall0079^^YES24^^Y^^Y^^Y^^Y^^Y^^N");
        mall_arr.push("mall0085^^웰베이^^Y^^Y^^Y^^Y^^N^^N");
        mall_arr.push("mall0090^^2001아울렛^^Y^^Y^^Y^^Y^^N^^Y");
        mall_arr.push("mall0094^^바보사랑^^Y^^Y^^Y^^Y^^N^^Y");
        mall_arr.push("mall0104^^세상N^^Y^^Y^^Y^^Y^^N^^Y");
        mall_arr.push("mall0110^^NH마켓^^Y^^Y^^N^^N^^N^^N");
        mall_arr.push("mall0113^^오셀러^^N^^N^^Y^^Y^^N^^N");
        mall_arr.push("mall0119^^홀리스퀘어^^Y^^Y^^Y^^Y^^N^^N");
        mall_arr.push("mall0132^^위핑(구:이룬마켓)^^Y^^Y^^Y^^Y^^N^^Y");
        mall_arr.push("mall0135^^알라딘(SCM)^^Y^^Y^^Y^^Y^^N^^Y");
        mall_arr.push("mall0136^^알라딘(오픈마켓)^^Y^^Y^^Y^^Y^^N^^Y");
        mall_arr.push("mall0139^^키드키즈^^Y^^N^^N^^N^^N^^N");
        mall_arr.push("mall0145^^SBS골프숍^^Y^^Y^^Y^^Y^^N^^N");
        mall_arr.push("mall0147^^한화갤러리아^^Y^^Y^^Y^^Y^^Y^^Y");
        mall_arr.push("mall0148^^스마트스토어^^Y^^Y^^Y^^Y^^Y^^Y");
        mall_arr.push("mall0152^^엔조이뉴욕(레더스)^^Y^^Y^^Y^^Y^^N^^Y");
        mall_arr.push("mall0153^^교보핫트랙스^^Y^^Y^^Y^^Y^^A^^Y");
        mall_arr.push("mall0156^^GS리테일 복지몰^^Y^^Y^^Y^^Y^^N^^Y");
        mall_arr.push("mall0159^^롯데마트^^Y^^Y^^Y^^Y^^N^^N");
        mall_arr.push("mall0160^^가방팝^^Y^^Y^^Y^^Y^^N^^N");
        mall_arr.push("mall0163^^레이틀리^^Y^^Y^^Y^^Y^^N^^Y");
        mall_arr.push("mall0164^^홈앤쇼핑^^Y^^Y^^Y^^Y^^Y^^N");
        mall_arr.push("mall0168^^아트박스^^Y^^Y^^Y^^Y^^Y^^Y");
        mall_arr.push("mall0170^^신세계닷컴2.0^^Y^^Y^^Y^^Y^^Y^^Y");
        mall_arr.push("mall0172^^지트리트^^Y^^Y^^Y^^Y^^N^^Y");
        mall_arr.push("mall0173^^와이티몰(놀부닷컴)^^Y^^Y^^Y^^Y^^N^^Y");
        mall_arr.push("mall0174^^스타일아이디^^Y^^Y^^Y^^Y^^N^^N");
        mall_arr.push("mall0175^^아이스탁몰^^Y^^Y^^Y^^Y^^N^^Y");
        mall_arr.push("mall0176^^파미웰^^Y^^Y^^Y^^Y^^N^^Y");
        mall_arr.push("mall0177^^위메프^^Y^^Y^^Y^^Y^^Y^^N");
        mall_arr.push("mall0179^^스토리웨이몰^^Y^^Y^^Y^^Y^^Y^^Y");
        mall_arr.push("mall0180^^웰스토리몰2.0^^Y^^Y^^Y^^Y^^N^^Y");
        mall_arr.push("mall0181^^하이마트^^Y^^Y^^Y^^Y^^Y^^Y");
        mall_arr.push("mall0182^^티몬^^Y^^Y^^Y^^Y^^Y^^Y");
        mall_arr.push("mall0184^^쿠팡^^Y^^Y^^Y^^Y^^Y^^Y");
        mall_arr.push("mall0186^^아이몰7^^Y^^Y^^Y^^Y^^N^^Y");
        mall_arr.push("mall0187^^롯데백화점몰^^Y^^Y^^Y^^Y^^Y^^Y");
        mall_arr.push("mall0188^^베이스존^^Y^^Y^^Y^^N^^N^^N");
        mall_arr.push("mall0192^^무신사스토어^^Y^^Y^^Y^^Y^^N^^Y");
        mall_arr.push("mall0194^^고도몰^^Y^^Y^^Y^^Y^^N^^Y");
        mall_arr.push("mall0195^^티어제로^^Y^^Y^^Y^^Y^^N^^Y");
        mall_arr.push("mall0196^^제로투세븐^^Y^^Y^^Y^^Y^^N^^Y");
        mall_arr.push("mall0200^^엔샵^^Y^^Y^^Y^^Y^^N^^N");
        mall_arr.push("mall0201^^(주)현대백화점^^Y^^Y^^Y^^N^^Y^^Y");
        mall_arr.push("mall0202^^WCONCEPT^^Y^^Y^^Y^^Y^^Y^^Y");
        mall_arr.push("mall0204^^YIC컴퍼니^^Y^^Y^^Y^^Y^^N^^N");
        mall_arr.push("mall0205^^오테이스트몰^^Y^^Y^^Y^^Y^^N^^Y");
        mall_arr.push("mall0206^^멸치쇼핑^^Y^^Y^^Y^^Y^^Y^^N");
        mall_arr.push("mall0207^^스킨알엑스^^Y^^Y^^Y^^Y^^Y^^Y");
        mall_arr.push("mall0208^^골핑^^Y^^Y^^Y^^Y^^N^^Y");
        mall_arr.push("mall0211^^다이소몰^^Y^^Y^^Y^^Y^^Y^^Y");
        mall_arr.push("mall0212^^K쇼핑^^Y^^Y^^Y^^Y^^N^^Y");
        mall_arr.push("mall0213^^알람몰^^Y^^Y^^Y^^Y^^N^^Y");
        mall_arr.push("mall0215^^하이웨이마트^^Y^^Y^^Y^^Y^^N^^Y");
        mall_arr.push("mall0216^^신세계백화점^^Y^^Y^^N^^N^^N^^N");
        mall_arr.push("mall0219^^후추통^^Y^^Y^^Y^^Y^^N^^Y");
        mall_arr.push("mall0220^^AK백화점^^Y^^Y^^Y^^Y^^Y^^Y");
        mall_arr.push("mall0221^^원더플레이스^^Y^^Y^^Y^^Y^^Y^^Y");
        mall_arr.push("mall0222^^한국뱅크앤컴퍼니^^Y^^Y^^Y^^Y^^N^^N");
        mall_arr.push("mall0223^^판다코리아^^Y^^Y^^Y^^Y^^N^^N");
        mall_arr.push("mall0224^^엘샵^^Y^^Y^^A^^A^^A^^A");
        mall_arr.push("mall0226^^농협a마켓^^Y^^Y^^Y^^Y^^Y^^Y");
        mall_arr.push("mall0227^^리본즈코리아^^Y^^Y^^Y^^Y^^N^^Y");
        mall_arr.push("mall0229^^인터파크 비즈마켓^^Y^^Y^^Y^^Y^^N^^N");
        mall_arr.push("mall0230^^(주)더현대몰^^Y^^Y^^A^^A^^Y^^A");
        mall_arr.push("mall0231^^삼성카드^^Y^^Y^^Y^^Y^^Y^^A");
        mall_arr.push("mall0232^^에이지몰^^Y^^Y^^Y^^Y^^A^^A");
        mall_arr.push("mall0233^^먼슬러^^Y^^Y^^Y^^Y^^Y^^Y");
        mall_arr.push("mall0234^^무궁화 꽃이 피었습니다^^Y^^Y^^Y^^Y^^A^^A");
        mall_arr.push("mall0235^^(주)현대리바트^^Y^^Y^^Y^^Y^^Y^^Y");
        mall_arr.push("mall0237^^ETAH^^Y^^Y^^Y^^Y^^Y^^Y");
        mall_arr.push("mall0238^^오너클랜(왕도매)^^Y^^Y^^Y^^Y^^A^^Y");
        mall_arr.push("mall0239^^에듀팡^^Y^^Y^^Y^^Y^^Y^^Y");
        mall_arr.push("mall0241^^우먼스톡^^Y^^Y^^Y^^Y^^Y^^Y");
        mall_arr.push("mall0242^^공영홈쇼핑^^Y^^Y^^Y^^Y^^Y^^Y");
        mall_arr.push("mall0243^^FINDEN^^Y^^Y^^Y^^Y^^Y^^Y");
        mall_arr.push("mall0244^^허그몰^^Y^^Y^^Y^^Y^^Y^^Y");
        mall_arr.push("mall0245^^이랜드리테일^^Y^^Y^^Y^^Y^^N^^Y");
        mall_arr.push("mall0246^^쇼핑파이^^Y^^Y^^Y^^Y^^Y^^A");
        mall_arr.push("mall0247^^고도몰5^^Y^^Y^^Y^^Y^^A^^Y");
        mall_arr.push("mall0250^^루이스클럽^^Y^^Y^^Y^^Y^^A^^Y");
        mall_arr.push("mall0251^^신세계TV쇼핑^^Y^^Y^^Y^^Y^^N^^Y");
        mall_arr.push("mall0252^^케이그룹^^Y^^Y^^Y^^Y^^Y^^Y");
        mall_arr.push("mall0254^^바이폴^^Y^^Y^^Y^^Y^^N^^Y");
        mall_arr.push("mall0255^^마리오아울렛^^Y^^Y^^Y^^Y^^N^^Y");
        mall_arr.push("mall0257^^에이랜드^^Y^^Y^^Y^^Y^^Y^^Y");
        mall_arr.push("mall0258^^머스트잇^^Y^^Y^^Y^^Y^^Y^^Y");
        mall_arr.push("mall0262^^우마켓^^Y^^Y^^Y^^Y^^Y^^Y");
        mall_arr.push("mall0263^^마카롱팩토리^^N^^N^^Y^^Y^^Y^^Y");
        mall_arr.push("mall0264^^네이버페이^^N^^N^^Y^^Y^^N^^N");
        mall_arr.push("mall0265^^위메프 셀러마켓^^Y^^Y^^N^^N^^N^^N");
        mall_arr.push("mall0266^^SK스토아^^Y^^Y^^Y^^Y^^Y^^Y");
        mall_arr.push("mall0267^^엔터식스^^Y^^Y^^Y^^Y^^N^^Y");
        mall_arr.push("mall0268^^스메그코리아^^Y^^Y^^Y^^Y^^A^^Y");
        mall_arr.push("mall0269^^슈나이더^^Y^^Y^^Y^^Y^^A^^Y");
        mall_arr.push("mall0274^^멍도리^^Y^^Y^^Y^^Y^^A^^A");
        mall_arr.push("mall0275^^티빙몰^^Y^^Y^^Y^^Y^^Y^^N");
        mall_arr.push("mall0276^^베네피아^^Y^^Y^^Y^^Y^^Y^^Y");
        mall_arr.push("mall0279^^홈데이몰^^Y^^Y^^Y^^Y^^Y^^Y");
        mall_arr.push("mall0280^^SSF SHOP^^Y^^Y^^Y^^Y^^Y^^Y");
        mall_arr.push("mall0281^^놀다가게^^Y^^Y^^Y^^Y^^A^^Y");
        mall_arr.push("mall0282^^NCP^^Y^^Y^^Y^^Y^^Y^^Y");
        mall_arr.push("mall0283^^서울스토어^^Y^^Y^^Y^^Y^^Y^^Y");
        mall_arr.push("mall0284^^카페24^^Y^^Y^^Y^^Y^^A^^Y");
        mall_arr.push("mall0286^^카카오톡 스토어^^Y^^Y^^Y^^Y^^Y^^Y");
        mall_arr.push("mall0287^^위메프 파트너2.0^^Y^^Y^^Y^^Y^^Y^^Y");
        mall_arr.push("mall0288^^크런치 프라이스^^Y^^Y^^Y^^Y^^N^^Y");
        mall_arr.push("mall0289^^쇼핑엔티^^Y^^Y^^Y^^Y^^Y^^Y");
        mall_arr.push("mall0290^^롯데슈퍼^^Y^^Y^^Y^^Y^^N^^A");
        mall_arr.push("mall0291^^펀앤쇼핑^^Y^^Y^^Y^^Y^^Y^^Y");
        mall_arr.push("mall0292^^모게요^^Y^^Y^^Y^^Y^^Y^^Y");
        mall_arr.push("mall0295^^스마트스코어^^Y^^Y^^Y^^Y^^Y^^Y");
        mall_arr.push("mall0296^^힙합퍼^^Y^^Y^^Y^^Y^^Y^^Y");
        mall_arr.push("mall0297^^도매꾹^^Y^^Y^^Y^^Y^^Y^^Y");
        mall_arr.push("mall0298^^설성푸드주식회사^^Y^^Y^^Y^^Y^^N^^Y");
        mall_arr.push("mall0299^^jtbcgolf^^Y^^Y^^Y^^Y^^Y^^Y");
        mall_arr.push("mall0300^^하우스미디어^^Y^^Y^^Y^^Y^^Y^^Y");
        mall_arr.push("mall0301^^투비즈온^^Y^^Y^^Y^^Y^^Y^^Y");
        mall_arr.push("mall0302^^LF스퀘어^^Y^^Y^^Y^^Y^^N^^Y");
        mall_arr.push("mall0303^^지니프렌즈^^Y^^Y^^Y^^Y^^Y^^Y");
        mall_arr.push("mall0305^^10X10^^Y^^Y^^Y^^Y^^Y^^Y");
        mall_arr.push("mall0306^^푸딩^^Y^^Y^^Y^^Y^^Y^^Y");
        mall_arr.push("mall0307^^도매의신^^Y^^Y^^Y^^Y^^Y^^Y");
        mall_arr.push("mall0308^^컴퓨존^^Y^^Y^^Y^^Y^^Y^^Y");
        mall_arr.push("mall0309^^코즈몰^^Y^^Y^^Y^^Y^^Y^^Y");
        mall_arr.push("mall0311^^우리샵^^Y^^Y^^Y^^Y^^Y^^Y");
        mall_arr.push("mall0316^^어라운드더코너^^Y^^Y^^Y^^Y^^N^^Y");
        mall_arr.push("mall0317^^샵바이^^Y^^Y^^Y^^Y^^A^^Y");
        mall_arr.push("mall0321^^롯데온^^Y^^Y^^Y^^Y^^Y^^Y");
        mall_arr.push("mall0322^^패디코리아^^Y^^Y^^Y^^Y^^Y^^Y");
        mall_arr.push("mall0323^^스페셜오퍼^^Y^^Y^^Y^^Y^^Y^^Y");
        mall_arr.push("mall0324^^T셀파몰^^Y^^Y^^Y^^Y^^Y^^Y");
        mall_arr.push("mall0325^^씨스토어^^Y^^Y^^Y^^Y^^Y^^Y");
        mall_arr.push("mall0327^^W쇼핑^^Y^^Y^^Y^^Y^^Y^^Y");
        mall_arr.push("mall0329^^셀렉온^^Y^^Y^^Y^^Y^^Y^^Y");
        mall_arr.push("mall0330^^까사미아^^Y^^Y^^Y^^Y^^Y^^Y");
        mall_arr.push("mall0332^^LG하우시스 지인몰^^Y^^Y^^Y^^Y^^Y^^Y");
        mall_arr.push("mall0333^^몽땅뚝딱몰^^Y^^Y^^Y^^Y^^Y^^Y");
        mall_arr.push("mall0337^^SSG오픈마켓^^Y^^Y^^N^^N^^N^^N");
        mall_arr.push("mall0338^^골디닷컴^^Y^^Y^^Y^^Y^^Y^^Y");
        mall_arr.push("mall0339^^보리보리^^Y^^Y^^Y^^Y^^Y^^Y");
        mall_arr.push("mall0340^^코오롱몰^^Y^^Y^^Y^^Y^^N^^Y");
        mall_arr.push("mall0341^^알렛츠샵^^Y^^Y^^Y^^Y^^Y^^Y");
        mall_arr.push("mall0342^^스타일크루^^Y^^Y^^Y^^Y^^Y^^N");

        var table_txt = "";
        for(var i = 0; i < mall_arr.length; i++){
            var mall_info = mall_arr[i].split("^^");
            var menu_yn_t = menu_yn[mall_info[0]];
            table_txt += "<tr>";
            table_txt += "<td><img src='https://www.shoplinker.co.kr/images/mall/apply/ico_"+mall_info[0]+".png' /></td>";
            if(menu_yn_t == "Y"){
                table_txt += "<td><a href='../mall/"+mall_info[0]+"/'>"+mall_info[1]+"</a></td>";
            }else{
                table_txt += "<td>"+mall_info[1]+"</td>";
            }
            for(var ii = 2; ii < 8; ii++){
                var use_txt = "X";
                if(mall_info[ii] == "Y"){use_txt = "O";}
                table_txt += "<td>"+use_txt+"</td>";
            }
            table_txt += "</tr>";
        }
        $("#all_body").html(table_txt);
    });

</script>

# 지원 쇼핑몰 안내
* <font size="2px">쇼핑몰 명 클릭 시 해당 쇼핑몰 사용안내 페이지로 이동합니다.</font>
* <font size="2px">별도 안내가 없는 쇼핑몰의 경우 이동하지 않습니다.</font>

--- 
## 쇼핑몰 검색

<html>
<div class="content-wrap">
    <div class="mall-wrap">
        <div class="mall-search-wrap">
            <div class="mall-search-box">
                <div class="mall-search-word">
                    <input type="text" title="쇼핑몰 검색" id = "search_text" onKeypress="javascript:if(event.keyCode==13) enter_key()"/>
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
                <th scope="col">상품등록</th>
                <th scope="col">상품수정</th>
                <th scope="col">주문수집</th>
                <th scope="col">송장전송</th>
                <th scope="col">문의후기</th>
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
        sortKeyword(schTxt);
        return false;
    });

    function enter_key(){
        var schTxt = $("#search_text").val();
        sortKeyword(schTxt);
        return false;
    }

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