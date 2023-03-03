# 20230303
html 기본

content-box : 지정한 CSS width 및 height를 컨텐츠 영역에만 적용합니다. border, padding, margin은 따로 계산되어 전체 영역이 설정값보다 커질 수 있습니다.
border-box : 지정한 CSS width 및 height를 전체 영역에 적용합니다. border, padding, margin을 모두 합산하기 때문에 컨텐츠 영역이 설정값보다 적어질 수 있습니다.
<div> 태그 등의 영역 크기를 100px으로 설정했을 때

100px 이상으로 <div>가 더 튀어나와서 크기를 100px으로 딱 맞추고 싶다? box-sizing : border-box;
100px 미만으로 <div>가 더 적게 나와서 컨텐츠 영역만 100px으로 맞추고 싶다? box-sizing : content-box;
