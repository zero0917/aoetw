<template>
  <div class="container">
    <div class="row padtop">
      <div class="col-md-12">
        <h1>完美的烈士</h1>
        <div class="hrn1"></div>
      </div>
      <div class="col-md-8">
        <div class="n1">
          <p>
            <strong>完美的烈士</strong>為<nuxt-link to="/batt/Joan_of_Arc"
              >聖女貞德戰役</nuxt-link
            >的第六關劇情關卡，此關法軍與英軍於卡斯提農決戰，是英法百年戰爭的最後一場戰役，發生在加斯科涅的多爾多尼河畔卡斯提農（今卡斯提農拉巴泰爾），法軍取得了決定性的勝利，自此英格蘭王國失去除加萊和海峽群島外的全部法國領土。
          </p>
        </div>
        <h2>遊戲者</h2>
        <div class="hrn1"></div>
        <div class="n1">
          <!--<span class="glyphicon glyphicon-star" aria-hidden="true" style="color: #ff911d; margin-left: 5px;"></span>:中立</p>!-->
          <table class="table-bordered" width="100%">
            <tr>
              <td class="tc4" colspan="4" style="background: #2980b9;">
                玩家本身
              </td>
            </tr>
            <tr>
              <td class="tc6"><div class="p1">玩家1</div></td>
              <td class="tc6" colspan="3">
                <nuxt-link to="/civs/Franks">法蘭克人</nuxt-link>（藍色）
              </td>
            </tr>
            <tr>
              <td class="tc4" colspan="4" style="background:#ea6153;">敵對</td>
            </tr>
            <tr>
              <td class="tc6" width="12%"><div class="p6">玩家2</div></td>
              <td class="tc6" width="38%">勃根地（紫色）法蘭克</td>
              <td class="tc6" width="12%"><div class="p2">玩家3</div></td>
              <td class="tc6" width="38%">
                英國（紅色）<nuxt-link to="/civs/Britons">不列顛</nuxt-link>
              </td>
            </tr>
            <tr>
              <td class="tc6"><div class="p8">玩家4</div></td>
              <td class="tc6">舒茲伯利（橘色）不列顛</td>
            </tr>
            <tr></tr>
          </table>
        </div>
      </div>
      <div class="col-md-4">
        <table class="table-bordered" width="100%">
          <tr>
            <td class="unit" colspan="2" style="background-color:#375d96;">
              <div class="unititle2">
                完美的烈士
              </div>
            </td>
          </tr>
          <tr>
            <td colspan="2">
              <div class="unititle">
                <img src="~assets/Joan6map.png" alt="" />
              </div>
            </td>
          </tr>
          <tr>
            <td class="unit" colspan="2" style="background-color:#375d96;">
              <div class="unititle2">情景信息</div>
            </td>
          </tr>
          <tr>
            <td class="unit3">版本</td>
            <td class="unit4">
              <nuxt-link to="/games/aok">帝王世紀</nuxt-link>
            </td>
          </tr>
          <tr>
            <td class="unit3">戰役</td>
            <td class="unit4">
              <nuxt-link to="/batt/Joan_of_Arc">聖女貞德</nuxt-link>
            </td>
          </tr>
          <tr>
            <td class="unit3"><nuxt-link to="/civs">文明</nuxt-link></td>
            <td class="unit4">
              <nuxt-link to="/civs/Franks">法蘭克</nuxt-link>
            </td>
          </tr>
          <tr>
            <td class="unit" colspan="2" style="background-color:#375d96;">
              <div class="unititle2">
                戰役關卡編號
              </div>
            </td>
          </tr>
          <tr>
            <td class="unit3">章節</td>
            <td class="unit4">
              <nuxt-link to="/games/aok">帝王世紀</nuxt-link>第二章之六
            </td>
          </tr>
          <tr>
            <td class="unit3">上一關</td>
            <td class="unit4">
              <nuxt-link to="/batt/The_Siege_of_Paris">巴黎攻城戰</nuxt-link>
            </td>
          </tr>
          <tr>
            <td class="unit3">下一關</td>
            <td class="unit4">N/A</td>
          </tr>
        </table>

        <div class="thanks">感謝！此頁面由裕暉、亞諭協助編輯。</div>
        <p></p>
        <div class="wiki" style="margin-top: 5px;">
          <div style="float: left;">
            <img src="~assets/Wikipedia-logo.png" width="50" height="46" />
          </div>
          <div style="margin-left: 60px;">
            維基百科上的完美的烈士
            <div style="margin-left: 10px;">
              <i
                ><strong
                  ><a href="http://tinyurl.com/ybatc4lg"
                    >卡斯蒂隆戰役</a
                  ></strong
                ></i
              >
            </div>
          </div>
        </div>
      </div>
    </div>
    <h2>戰役說明</h2>
    <div class="hrn1"></div>
    <div class="row">
      <div class="col-md-4">
        <h3>開場設定</h3>
        <ul>
          <li>
            <strong>起始時代：</strong>
            <img
              class="gg"
              src="~assets/Castle-age-reseach.jpg"
              alt=""
            /><nuxt-link to="/techs/age/Castle_Age">城堡時代</nuxt-link>
          </li>
          <li><strong>起始資源：</strong>無</li>
          <li><strong>人口上限：</strong>75</li>
        </ul>
      </div>
      <div class="col-md-4">
        <h3>起始單位</h3>
        <ul>
          <li>
            <img
              class="gg"
              src="~assets/Guyjosselyneicon.png"
              alt=""
            /><nuxt-link to="/units/hero/Guy_Josselyne">蓋佐斯爾立</nuxt-link>
          </li>
          <li>
            <img class="gg" src="~assets/TradeCartIcon.jpg" alt="" /><nuxt-link
              to="/units/Trade_Cart"
              >貿易車隊</nuxt-link
            >*1
          </li>
        </ul>
      </div>
      <div class="col-md-4">
        <h3>大地之母</h3>
        <ul>
          <li>
            <img class="gg" src="~assets/Lahire.png" alt="" /><nuxt-link
              to="/units/hero/La_Hire"
              >拉海爾</nuxt-link
            >
          </li>
          <li>
            <img
              class="gg"
              src="~assets/Constablerichemonticon.png"
              alt=""
            /><nuxt-link to="/units/hero/Constable_Richemont"
              >康斯塔伯理察蒙</nuxt-link
            >
          </li>
          <li>
            <img class="gg" src="~assets/Jeanbureauicon.png" alt="" /><nuxt-link
              to="/units/hero/Jean_Bureau"
              >約翰布荷</nuxt-link
            >
          </li>
          <li>
            <img class="gg" src="~assets/ArbalestIcon.jpg" alt="" /><nuxt-link
              to="/units/Arbalest"
              >強弩兵</nuxt-link
            >*16
          </li>
          <li>
            <img class="gg" src="~assets/ChampionIcon.jpg" alt="" /><nuxt-link
              to="/units/Champion"
              >劍兵勇士</nuxt-link
            >*8
          </li>
          <li>
            <img class="gg" src="~assets/HussarIcon.jpg" alt="" /><nuxt-link
              to="/units/Hussar"
              >匈牙利輕騎兵</nuxt-link
            >*8
          </li>
          <li>
            <img
              class="gg"
              src="~assets/HandCannoneerIcon.jpg"
              alt=""
            /><nuxt-link to="/units/Hand_Cannoneer">火槍兵</nuxt-link>*8
          </li>
          <li>
            <img
              class="gg"
              src="~assets/VillagerMaleIcon.jpg"
              alt=""
            /><nuxt-link to="/units/Villager">村民</nuxt-link>*6
          </li>
          <li>
            <img class="gg" src="~assets/PaladinIcon.jpg" alt="" /><nuxt-link
              to="/units/Paladin"
              >遊俠</nuxt-link
            >*6
          </li>
          <li>
            <img
              class="gg"
              src="~assets/BombardCannonIcon.jpg"
              alt=""
            /><nuxt-link to="/units/Bombard_Cannon">火砲</nuxt-link>*6
          </li>
          <li>
            <img
              class="gg"
              src="~assets/TrebuchetPackedIcon.jpg"
              alt=""
            /><nuxt-link to="/units/Trebuchet">巨型投石機</nuxt-link>*2
          </li>
          <dd>
            <strong
              >*困難模式為1台<img
                class="gg"
                src="~assets/TrebuchetPackedIcon.jpg"
                alt=""
              /><nuxt-link to="/units/Trebuchet">巨型投石機</nuxt-link>和3台<img
                class="gg"
                src="~assets/BombardCannonIcon.jpg"
                alt=""
              /><nuxt-link to="/units/Bombard_Cannon">火砲</nuxt-link>。</strong
            >
          </dd>
        </ul>
      </div>
    </div>
    <h3>主要任務</h3>
    <div class="hrn1"></div>
    <div class="n1">
      <ol>
        <li>
          跟法國軍隊會合，由<nuxt-link to="/units/hero/Constable_Richemont"
            >康斯塔伯理察蒙</nuxt-link
          >來指揮。
        </li>
        <li>
          跟法國的大砲部隊會合，由<nuxt-link to="/units/hero/Jean_Bureau"
            >約翰布荷</nuxt-link
          >來指揮。
        </li>
        <li>
          把法國國旗（由<nuxt-link to="/units/Trade_Cart">貿易車隊</nuxt-link
          >裝載）插在卡斯提農的山上（以旗子來覆滿它）。
        </li>
      </ol>
    </div>
    <h3>任務提示</h3>
    <div class="hrn1"></div>
    <div class="n1">
      <ul>
        <li>
          這邊大部分的土地都被佔領了。你將必須驅離勃艮地人以重建城鎮。不需要將勃艮地所有的<nuxt-link
            to="/building/Stone_Wall"
            >城牆</nuxt-link
          >都給擊垮，因為它們可以發揮防禦的功能。
        </li>
        <li>
          <nuxt-link to="/units/Longbowman">長弓兵</nuxt-link
          >固然實力堅強，但<nuxt-link to="/units/Bombard_Cannon">火砲</nuxt-link
          >的威力更是驚人。你可以將火砲和<nuxt-link to="/units/Siege_Weapons"
            >攻城武器</nuxt-link
          >設為「不還擊」狀態，以免誤傷你自己的軍隊。
        </li>
      </ul>
      <h3>芝麻小事</h3>
      <div class="hrn1"></div>
      <ul>
        <li>
          此關是整場戰役的故事旁白—<nuxt-link to="/units/hero/Guy_Josselyne"
            >蓋佐斯爾立</nuxt-link
          >所出現的唯一場景，也是玩家唯一無法使用貞德的關卡。
        </li>
        <li>
          有方法甚至不需要建立基地或生產軍事單位就可以贏得戰役。首先帶領你的起始軍隊過河，摧毀任何威脅的<nuxt-link
            to="/building/Watch_Tower"
            >箭塔</nuxt-link
          >或單位，並從西北方<nuxt-link to="/building/Gate">城門</nuxt-link
          >闖入卡斯提農。然而，此方法在困難模式的難度較大，因為玩家的攻城武器較少。
        </li>
        <li>
          英軍在此場卡斯提農戰役中的指揮官是舒茲伯利，原名約翰•塔爾波特KG，第一代舒茲伯利及沃特福德伯爵（John
          Talbot, 1st Earl of Shrewsbury and 1st Earl of
          Waterford，1384年/1387年－1453年7月17日），又被稱為老塔爾波特，出生於施洛普郡，是英法百年戰爭中一名重要的英國軍事將領，也是唯一由蘭開斯特人擔任的法國<nuxt-link
            to="/units/Knight"
            >騎士</nuxt-link
          >統帥。
        </li>
        <li>
          在史實中，<nuxt-link to="/units/hero/La_Hire">拉海爾</nuxt-link
          >在卡斯提農戰役前於1443年1月，他因為不明的疾病於蒙托邦過世。
        </li>
      </ul>
    </div>
    <h2>概述</h2>
    <div class="hrn1"></div>
    <div class="n1">
      <ul>
        <li>
          場景開始時你只有國王蓋佐斯爾立和裝著法國旗子的貿易車隊。往東南邊穿過淺灘處後會有玩家的大軍等著你，再往西一點還有你的火砲，一開始你沒有任何資源跟<nuxt-link
            to="/building"
            >建築</nuxt-link
          >，你需要進攻勃根地來建立你的基地。你可以攻擊勃根地的北邊基地，不過你可能會經歷一場硬戰而且損失非常慘重，選擇進攻勃根地的南邊基地可能會簡單些。
        </li>
        <li>
          將你的火砲設定為不還擊狀態，之後帶軍隊沿著地圖邊緣往南走到一群巨石區，這裡是可以通行的，從這裡到達河流穿越處後，把你的<nuxt-link
            to="/units/Villager"
            >村民</nuxt-link
          >跟貿易車隊安置好，用火砲跟<nuxt-link to="/units/Trebuchet"
            >巨型投石機</nuxt-link
          >摧毀所有建築，用<nuxt-link to="/units/Hand_Cannoneer"
            >火槍兵</nuxt-link
          >跟<nuxt-link to="/units/Arbalest">強弩兵</nuxt-link
          >對付勃根地的<nuxt-link to="/units/Pikeman">重裝長槍兵</nuxt-link
          >跟<nuxt-link to="/units/Champion">劍兵勇士</nuxt-link>，用<nuxt-link
            to="/units/Hussar"
            >匈牙利輕騎兵</nuxt-link
          >和<nuxt-link to="/units/Paladin">遊俠</nuxt-link
          >屠殺你看到的任何村民。
        </li>
        <li>
          這時勃根地北方的軍隊（<nuxt-link to="/units/Crossbowman"
            >弩兵</nuxt-link
          >、<nuxt-link to="/units/Long_Swordsman">長劍兵</nuxt-link
          >和<nuxt-link to="/units/Throwing_Axeman">擲斧兵</nuxt-link
          >）會過來增援，迅速解決他們，用匈牙利輕騎兵殺對面<nuxt-link
            to="/units/Monk"
            >僧侶</nuxt-link
          >跟<nuxt-link to="/units/Mangonel">投石車</nuxt-link
          >。等到勃根地投降後，你會收到400肉、50金、50<nuxt-link
            to="/resource/Stone"
            >石頭</nuxt-link
          >和不等的<nuxt-link to="/resource/Wood">木材</nuxt-link
          >（木材量是根據他們留下多少決定）。在這裡建立你的基地並用城門和城牆封住河流穿越處。
        </li>
        <li>
          現在趕快發展你的經濟體，優先建造<nuxt-link to="/building/House"
            >居住房舍</nuxt-link
          >舒緩人口，趕快派兩個村民採集<nuxt-link to="/resource/Stone"
            >石礦</nuxt-link
          >準備建造<nuxt-link to="/building/Castle">城堡</nuxt-link
          >防禦基地，當人口達到50以上時帶著你的重騎兵、攻城武器、強弩兵和僧侶北上殲滅舒茲伯利，把匈牙利輕騎兵、火槍兵和<nuxt-link
            to="/units/Infantry_Units"
            >步兵</nuxt-link
          >留在基地內就可以應付<nuxt-link to="/civs/Britons">不列顛人</nuxt-link
          >的攻擊了。
        </li>
        <li>
          河的北邊有兩艘<nuxt-link to="/units/Galleon">重型弩砲戰船</nuxt-link
          >和一艘<nuxt-link to="/units/Cannon_Galleon">火砲戰船</nuxt-link
          >會攻擊玩家的基地，可以用僧侶<nuxt-link to="/elements/Conversion"
            >招降</nuxt-link
          >或是箭矢擊沉他們，摧毀他們後不列顛人也不會繼續訓練任何<nuxt-link
            to="/units/Naval_Vessels"
            >海軍</nuxt-link
          >了。在勃根地北方基地的左邊有條山路可以直接到舒茲伯利的基地，不過順便清掉勃根地的北邊基地好挖取他們的<nuxt-link
            to="/resource/Gold"
            >黃金</nuxt-link
          >跟石頭，只需要火砲或巨型投石機就可以摧毀所有的<nuxt-link
            to="/building/Keep"
            >大型箭塔</nuxt-link
          >了。另外記得毀掉城門建造新的，不然敵方單位是可以通過原本城門的。
        </li>
      </ul>
      <div class="row">
        <div class="col-md-6">
          <gallery
            ><img
              position="centered"
              class="imgn hg"
              width="500"
              src="~assets/Joanofarc6rock.jpg"
              alt=""
          /></gallery>
          <p>
            <em>讓軍隊沿著地圖邊緣走到這邊準備攻擊勃根地人。</em>
          </p>
        </div>
        <div class="col-md-6">
          <gallery
            ><img
              position="centered"
              class="imgn hg"
              width="500"
              src="~assets/Joanofarc6Burgundy.jpg"
              alt=""
          /></gallery>
          <p><em>破壞勃根地城鎮。</em></p>
        </div>
      </div>
      <ul>
        <li>
          在舒茲伯利左邊的城門附近建造城堡跟<nuxt-link to="/building/Stable"
            >馬廄</nuxt-link
          >還有<nuxt-link to="/units/Siege_Weapons">攻城器製造所</nuxt-link
          >，他們只要注意到你馬上就會派<nuxt-link to="/units/Cavalier"
            >騎兵</nuxt-link
          >、巨型投石機跟<nuxt-link to="/units/Capped_Ram">裝甲衝撞車</nuxt-link
          >襲來。用強弩兵盡量射殺敵人，用騎兵摧毀攻城武器，打敗舒茲伯利後你可以開採他們領地內的黃金和石頭，可把<nuxt-link
            to="/building/Market"
            >市集</nuxt-link
          >留著並在南邊的基地建造市集生產貿易車隊增加黃金存量，不過開採的黃金應該足夠使用了。在進攻舒茲伯利時不列顛會來援助他，記得不斷訓練單位擊退他們。
        </li>
        <li>
          現在你要專心對付不列顛人，升級到遊俠，升級所有相關<nuxt-link
            to="/techs"
            >科技</nuxt-link
          >，搭配裝甲衝撞車、巨型投石機跟火砲，摧毀沿路阻擋你的箭塔跟城堡，在不列顛人的城門前你會遭遇一場硬戰，記得帶上村民在前線插城堡跟蓋馬廄、攻城器製造所等軍事建築。讓遊俠不斷出擊，用攻城武器摧毀城牆城堡和<nuxt-link
            to="/building/Bombard_Tower"
            >火砲塔</nuxt-link
          >，插旗的地方會有火砲塔，記得先摧毀他們再目送貿易車隊插上旗子取得最後勝利。
        </li>
      </ul>
      <div class="row">
        <div class="col-md-6">
          <gallery
            ><img class="imgn hg" src="~assets/Joanofarc6Shrewsbury.jpg" alt=""
          /></gallery>
          <p>
            <em>舒茲伯利有大量的黃金跟石頭可以開採。</em>
          </p>
        </div>
        <div class="col-md-6">
          <gallery
            ><img class="imgn hg" src="~assets/Joanofarc6Northwest.jpg" alt=""
          /></gallery>
          <p>
            <em
              >看到<nuxt-link to="/building/Guard_Tower">防禦箭塔</nuxt-link
              >就在附近蓋城堡跟軍事建築。</em
            >
          </p>
        </div>
      </div>
      <ul>
        <li>
          你也可以選擇進攻地圖西北邊，這裡相對離目標更近。過了地圖中間的河流穿越處沿著河流往北走，遇到懸崖後往西走一些這裡有兩座防禦箭塔跟一座城堡，你可以相當容易地摧毀他們，記得先讓村民在這邊插城堡跟一些軍事建築後再打，讓<nuxt-link
            to="/units/Siege_Weapons"
            >攻城單位</nuxt-link
          >攻破城牆和火砲塔後就可以護送馬車贏得勝利了。
        </li>
        <li>
          在這個戰役玩家也可用<nuxt-link to="/building/Wonder"
            >世界奇觀</nuxt-link
          >獲得勝利。在市場交易所需資源後讓村民開始蓋世界奇觀並守護200年，記得還是要發展經濟跟<nuxt-link
            to="/batt/Training_the_Troops"
            >訓練軍隊</nuxt-link
          >保護基地。你也可以直接擊敗不列顛人獲得勝利。
        </li>
      </ul>
      <div class="row">
        <div class="col-md-6">
          <gallery
            ><img
              position="centered"
              class="imgn hg"
              width="500"
              src="~assets/Joanofarc6lastmile.jpg"
              alt=""
          /></gallery>
          <p><em>在城門前蓋城堡往目標繼續挺進。</em></p>
        </div>
        <div class="col-md-6">
          <gallery
            ><img
              position="centered"
              class="imgn hg"
              width="500"
              src="~assets/Joanofarc6victory.jpg"
              alt=""
          /></gallery>
          <p><em>玩家可以直接擊敗不列顛人獲得勝利。</em></p>
        </div>
      </div>
    </div>
  </div>
</template>
<script>
export default {
  layout: 'allbatt',
  components: {}
}
</script>
<style></style>
