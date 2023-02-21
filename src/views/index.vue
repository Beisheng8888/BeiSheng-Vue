<template>
 <div>
    <div class="app-container home">
      <el-row :gutter="20">
        <el-col :sm="24" :lg="24" style="padding-left: 20px">
          <div style="text-align: center;">
            <b>
              <h2>技能比武显身手，竞技竞智争上游—2022年浙江省省级职工职业技能竞赛慢性病监测赛项圆满落幕</h2>
            </b>
          </div>
          <div v-highlight v-html="msg" class="styleClass"></div>
        </el-col>
      </el-row>
    </div>
  </div>
</template>
<script>
export default {
  name: "Index",
  data() {
    return {
      // 版本号
      version: "3.8.5",
      msg: "<p>null# 抑郁-焦虑-压力量表简体中文版</p>\n<h1><a href=\"#depression-anxiety-and-stress-scale-dass-21-\" name=\"depression-anxiety-and-stress-scale-dass-21-\"></a>（Depression Anxiety and Stress Scale，DASS-21）</h1>\n<p>​ DASS的内部结构以Clark和Watson提出的三维度模型（tripartite model）为基础，该模型认为抑郁和焦虑既有各自独特的、又有彼此共通的症状特征。抑郁的典型特征是快感缺失和消极情感，焦虑的典型特征是生理上的过度唤起，而广泛性的压抑体验（general distress）则是两者共有的特征。DASS的编制者有保留地借鉴了三维度模型的观点，将该量表界定为三维结构，即抑郁、焦虑和压力既相互关联又彼此独立，且尤其强调这三者之间的差异，以达到区分症状的目的。经过数十年的实证检验，DASS的三维结构获得了广泛认同，同时也得到了部分修正和完善。</p>\n<p>21条目抑郁焦虑和应激量表（DASS-21）<br/> 指导语：仔细阅读下面每个句子，“过去一周”您是否出现过这些情况，请选择适合您的选项。<br/> 0不符合&mdash;-1有时符合&mdash;2常常符合&mdash;3总是符合</p>\n<ol>\n  <li>我觉得很难让自己安静下来。</li>\n  <li>我感到口干舌燥。</li>\n  <li>我好像不再有任何愉快、舒畅的感觉。</li>\n  <li>我感到呼吸困难（例如：不做运动时也感到气促或透不过气来）。</li>\n  <li>我感到很难主动去开始工作。</li>\n  <li>我对事情往往做出过敏反应。</li>\n  <li>我感到颤抖（例如手震）。</li>\n  <li>我觉得自己消耗很多精神。</li>\n  <li>我担心一些令自己恐慌或出丑的场合。</li>\n  <li>我觉得自己对将来没有什么可盼望。</li>\n  <li>我感到忐忑不安。</li>\n  <li>我感到很难放松自己。</li>\n  <li>我感到忧郁沮丧</li>\n  <li>我无法容忍任何阻碍我继续工作的事情。</li>\n  <li>我感到快要恐慌了。</li>\n  <li>我对任何事也不热衷。</li>\n  <li>我觉得自己不怎么配做人。</li>\n  <li>我发觉自己很容易被触怒。</li>\n  <li>我察觉自己在没有明显的体力劳动时，也感到心律不正常。</li>\n  <li>我无缘无故地感到害怕。</li>\n  <li>我感到生命毫无意义。</li>\n</ol>\n<p>计分标准：</p>\n<p>压力：1、6、8、11、12、14、18<br/> 焦虑：2、4、7、9、15、19、20<br/> 抑郁：3、5、10、13、16、17、21</p>\n<p><strong>注意：将各分量表（压力、焦虑、抑郁）得分乘以 2，即为该分量表的分值。</strong></p>\n<p>抑郁得分≤9分为正常，10～l3分为轻度，14—20分为中度，21～27分为重度，≥28分为非常严重；<br/> 焦虑得分≤7分为正常，8～9分为轻度，10～14分为中度，15～l9分为重度，≥20分为非常严重；<br/> 压力得分≤14分为正常，15～l8分为轻度，l9～25分为中度，26～33分为重度，≥34分为非常严重。</p>\n<p>抑郁-焦虑-应激自评量表简版（Depression Anxiety and Stress Scale，DASS-21）DASS 最初由 Lovibond 等人于 1995 年编制，本研究采用的是袭栩等人(2010) 修订的 DASS-21 简体中文版，全量表包含 21 个条目，抑郁、焦虑和压力三个分量表各含 7 个条目，均采用从“0”（不符）到“3”（总是符合）的 4 级计分，将各分量表得分乘以 2，即为该分量表的分值，分值越高代表越具有这种情绪。在抑郁分量表中，10、14 及 21 分别是轻微、中度及重度抑郁的临界值；在焦虑分量表中，8、10 及 15 分别为轻微、中度及重度焦虑的临界值；在压力分量表中，15、19 及 26 分别为轻微、中度及重度压力的临界值。对 543 份有效前期调查问卷进行分析，该量表的 Cronbach α 系数为 0.891，KMO 值为 0.925，抑郁、焦虑和压力三个分量表的 Cronbach α 系数分别为 0.774、0.743、0.752，该量表的信效度良好。</p>\n<p>到很难主动去开始工作。<br/>6. 我对事情往往做出过敏反应。<br/>7. 我感到颤抖（例如手震）。<br/>8. 我觉得自己消耗很多精神。<br/>9. 我担心一些令自己恐慌或出丑的场合。<br/>10. 我觉得自己对将来没有什么可盼望。<br/>11. 我感到忐忑不安。<br/>12. 我感到很难放松自己。<br/>13. 我感到忧郁沮丧<br/>14. 我无法容忍任何阻碍我继续工作的事情。<br/>15. 我感到快要恐慌了。<br/>16. 我对任何事也不热衷。<br/>17. 我觉得自己不怎么配做人。<br/>18. 我发觉自己很容易被触怒。<br/>19. 我察觉自己在没有明显的体力劳动时，也感到心律不正常。<br/>20. 我无缘无故地感到害怕。<br/>21. 我感到生命毫无意义。</p>\n<p>计分标准：</p>\n<p>压力：1、6、8、11、12、14、18<br/> 焦虑：2、4、7、9、15、19、20<br/> 抑郁：3、5、10、13、16、17、21</p>\n<p><strong>注意：将各分量表（压力、焦虑、抑郁）得分乘以 2，即为该分量表的分值。</strong></p>\n<p>抑郁得分≤9分为正常，10～l3分为轻度，14—20分为中度，21～27分为重度，≥28分为非常严重；<br/> 焦虑得分≤7分为正常，8～9分为轻度，</p>",
    };
  },
  methods: {
    goTarget(href) {
      window.open(href, "_blank");
    },
  }

};
</script>


<style lang="scss" scoped>
.home {
  blockquote {
    padding: 10px 20px;
    margin: 0 0 20px;
    font-size: 17.5px;
    border-left: 5px solid #eee;
  }

  hr {
    margin-top: 20px;
    margin-bottom: 20px;
    border: 0;
    border-top: 1px solid #eee;
  }

  .col-item {
    margin-bottom: 20px;
  }

  ul {
    padding: 0;
    margin: 0;
  }

  font-family: "open sans", "Helvetica Neue", Helvetica, Arial, sans-serif;
  font-size: 13px;
  color: #676a6c;
  overflow-x: hidden;

  ul {
    list-style-type: none;
  }

  h4 {
    margin-top: 0px;
  }

  h2 {
    margin-top: 10px;
    font-size: 26px;
    font-weight: 100;
  }

  p {
    margin-top: 10px;

    b {
      font-weight: 700;
    }
  }

  .styleClass {
    margin-top: 10px;
    font-size: 18px;
    font-weight: 100;
  }

  .update-log {
    ol {
      display: block;
      list-style-type: decimal;
      margin-block-start: 1em;
      margin-block-end: 1em;
      margin-inline-start: 0;
      margin-inline-end: 0;
      padding-inline-start: 40px;
    }
  }
}

</style>

