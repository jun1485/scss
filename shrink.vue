// flexbox 또는 grid 아이템의 축소 가능성을 제어.
// 기본적으로, 위 레이아웃들에서는 자식 요소들이 부모 컨테이너의 크기에 맞춰 자신의 크기를 조절 가능.
// 이때, 아이템들은 기본적으로 공간이 부족할 경우 축소될 수 있음.
// shrink-0 클래스는 이러한 아이템의 축소 가능성을 비활성화, 부모 요소의 크기와 관계없이 원래 크기를 유지.
<div class="flex">
  <div class="shrink-0 bg-blue-500 text-white p-4">
    축소되지 않음
  </div>
  <div class="bg-red-500 text-white p-4 flex-auto">
    나머지 공간 차지
  </div>
</div>
