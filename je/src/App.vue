<template>
  <div id="app">
    <h1>{{ msg }}</h1>
    <section>
      <b-card no-body>
        <b-tabs pills card vertical>
          <b-tab title="git" active>
            <b-card-text>
              <ul>
                <li>
                  <h5>git clone</h5>
                  <p>서버의 모든 파일을 로컬로 다운로드</p>
                </li>
                <li>
                  <h5>git branch</h5>
                  <p>서버 내에서의 작업공간 리스트 확인(동일한 프로젝트를 여러 버전으로 관리 가능)</p>
                </li>
                <li>
                  <h5>git stash</h5>
                  <p>로컬의 수정 중인 파일을 임시 보관하고 가장 최근의 commit 상태로 만듦.</p>
                </li>
                <li>
                  <h5>버전 관리 시스템은 왜 필요한가요?</h5>
                  <p>서버의 모든 파일을 로컬로 다운로드</p>
                </li>
                <li>
                  <h5>git 외의 버전관리 시스템에는 무엇이 있나요? </h5>
                  <p>SVN, mercurial 등이 있음.</p>
                  <h5>git은 그 시스템과 어떤 점이 다르며, 어떤 장점을 가지고 있나요?</h5>
                  <p>중앙 서버에서 원하는 파일만 로컬에 받아 수정하는 SVN과는 달리, Git은 프로젝트 전체를 로컬에 다운 받은 뒤 수정하므로 중앙 서버에 문제가 생기더라도 어려움없이 복구나 작업이 가능.</p>
                </li>
              </ul>
              
            </b-card-text>
          </b-tab>
          <b-tab title="HTML,CSS">
            <b-card-text>
              <ul>
                <li>
                  <h5>"section"과 "div", "header", "footer", "article" 엘리먼트의 차이점은 무엇인가요?</h5>
                  <p>기본적인 스타일 속성은 같지만 내용이나 용도에 따라 구분하여 사용. 대체적으로 section은 내용의 구조를 만들 때, article은 페이지의 내용과 관련이 없는 독립적인 경우일 때 사용함.</p>
                  <dl>
                    <dt>Section </dt>
                    <dd>내부 콘텐츠가 그룹화되어 페이지 개요에 항목으로 표시되어야 하는 요소</dd>
                    <dt>Header </dt>
                    <dd>도입부에 해당하는 콘텐츠를 가지고 있는 부분</dd>
                    <dt>Footer</dt>
                    <dd>사이트의 작성자나 저작권정보, 연락처 등의 정보를 담고 있는 부분</dd>
                    <dt>Article</dt>
                    <dd>html 문서에서 독립적인 하나의 기사로, 아티클 요소의 내용 자체만으로도 내용이 이해가 되어야 함</dd>
                    <dt>div</dt>
                    <dd>별다른 의미 전달을 하지 않음</dd>                    
                  </dl>
                  <p>div외 나머지 요소들은 레이아웃만을 위한 시맨틱 태그로, 태그 스스로 브라우저와 개발자 모두에게 자신이 사용된 의미를 명확히 전달해 줌</p>
                </li>
                <li>
                  <h5>블럭 레벨 엘리먼트와 인라인 엘리먼트의 차이는 무엇일까요?</h5>
                  <p>블럭은 기본적으로 가로 폭을 모두 사용하고 width, height 사이즈 조절이나 padding 등의 여백 속성이 적용 가능하며 블럭 엘리먼트 안에 다른 블럭이나 인라인 엘리먼트 포함 가능.</p>
                  <p>인라인은 내용이 차지하는 영역만 사용하고 사이즈 조절이나 여백 속성은 적용할 수 없으며 안에 인라인 엘리먼트만 포함 가능.</p>
                  <dl>
                    <dt>블럭요소</dt>
                    <dd>줄바꿈이 일어나는 요소 (h1,p,div 등), 블럭, 인라인 요소 포함 가능</dd>
                    <dt>인라인 요소</dt>
                    <dd>줄바꿈이 없는 요소 (span, em, strong, a 등), 블럭요소 포함 불가능</dd>
                  </dl>
                </li>
                <li>
                  <h5></h5>
                  <p></p>
                </li>
                <li>
                  <h5></h5>
                  <p></p>
                </li>
                <li>
                  <h5></h5>
                  <p></p>
                </li>
                <li>
                  <h5></h5>
                  <p></p>
                </li>
                <li>
                  <h5></h5>
                  <p></p>
                </li>
                <li>
                  <h5></h5>
                  <p></p>
                </li>
                <li>
                  <h5></h5>
                  <p></p>
                </li>
                <li>
                  <h5></h5>
                  <p></p>
                </li>
              </ul>
            </b-card-text>
          </b-tab>
          <b-tab title="Tab 3"><b-card-text>Tab contents 3</b-card-text></b-tab>
        </b-tabs>
      </b-card>
    </section>
  </div>
</template>

<script>
export default {
  name: 'app',
  data () {
    return {
      msg: 'JE vue'
    }
  }
}
</script>

<style lang="scss">

</style>
