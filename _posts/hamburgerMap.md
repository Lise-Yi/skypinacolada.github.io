---
title: "Dot products and duality"
date: 2020-12-27 19:25:00
categories: 3B1B_LinearAlgebra
---

<!DOCTYPE html>
<html lang="ko">
    <head>
        <title>게살버거는 없습니다</title>
        <meta charset="utf-8"/>
        <link rel="stylesheet" href="https://unpkg.com/leaflet@1.6.0/dist/leaflet.css"
        integrity="sha512-xwE/Az9zrjBIphAcBb3F6JVqxf46+CDLwfLMHloNu6KEQCAWi6HcDUbeOfBIptF7tcCzusKFjFw2yuvEpDL9wQ=="
        crossorigin="" />
        <!-- Make sure you put this AFTER Leaflet's CSS -->
        <script src="https://unpkg.com/leaflet@1.6.0/dist/leaflet.js"
        integrity="sha512-gZwIG9x3wUXg2hdXF6+rVkLF/0Vi9U8D2Ntg4Ga5I5BZpVkVxlJWbSQtXPSiUTtC0TjtGOmxa1AJPuV0CPthew=="
        crossorigin="">
        </script>
        <style type="text/css">
            #map {
                height: 98vh;
                width: 98vw;
            }
        </style>
        <link rel="stylesheet" href="customControl.css">
    </head>
    <body>
        <div id="map"></div>
        <script>
            // Leaflet으로 OSM 지도 추가
            const map = L.map('map').setView([37.5642135, 127.0016985], 11.48);
            L.tileLayer('https://{s}.tile.openstreetmap.org/{z}/{x}/{y}.png', {
                arrtibution: '&copy; <a href="https://www.openstreetmap.org/copyright">OpenStreetMap</a> contributors', 
            }).addTo(map);
        </script>
        <script src="../hamburgerMap/boundary.js"> // 시군구 행정경계 geoJson </script>
        <script src="../hamburgerMap/filterBoundary.js"> // 원하는 지역 행정 경계만 골라 새로운 geoJSon을 추출하는 함수 </script>
        <script src="../hamburgerMap/counting.js">// 구내 가게 카운팅 함수 </script>
        <script src="../hamburgerMap/addCnt.js"> // 추출한 geoJson에 카운트를 프로퍼티로 추가하는 함수</script>
        <script src="../hamburgerMap/popup.js"> // 팝업 함수 </script>
        <script src="../hamburgerMap/burgerKingChoropleth.js"> // 버거킹 프로퍼티 시각화 함수 </script>
        <script src="../hamburgerMap/mcDonaldsChoropleth.js"> // 맥도날드 프로퍼티 시각화 함수 </script>
        <script src="../hamburgerMap/lotteriaChoropleth.js"> // 롯데리아 프로퍼티 시각화 함수 </script>
        <script src="../hamburgerMap/seoulBurgerKing.js">// 서울 내 버거킹 레이어 </script>
        <script src="../hamburgerMap/seoulMcDonalds.js"> //서울 내 맥도날드 레이어</script>
        <script src="../hamburgerMap/seoulLotteria.js">// 서울 내 롯데리아 레이어 </script>
        <script src="../hamburgerMap/layers.js"> // 레이어 그룹 컨트롤</script>
        <script src="../hamburgerMap/interaction.jss"></script>
    </body>
</html>
