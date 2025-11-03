Vue2 기반 코드를 Vue3 스타일로 전환

1. E01
   Vue 3에서 export default 구조로 유지
   ![E01](./src/assets/E-01.png)

3. E02
   Vue 2 data -> Vue 3 ref,computed 기반으로 반응형 데이터 구조
   ![E02](./src/assets/E-02.png)

5. E03
   data()대신 ref()사용하도록 변경
   ![E03](./src/assets/E-03.png)

7. E04
   v-if, v-show,v-for등 디렉티브는 동일하나, 데이터 정의를 ref()로 리팩터링
   ![E04](./src/assets/E-04.png)

9. E05
   propos/&emit 구조를 Vue 3 Composition API(defineProps,defineEmits)로 변환
   ![E05](./src/assets/E-05.png)

6.E06
   Vue 2의 provide/inject를 Composition API(provide,inject)함수로 변경
   ![E06](./src/assets/E-06.png)

7. E07
   E08과 E09를 Vue 3문법임

8. E10 ~ 12
   이미 Vue3 문법
