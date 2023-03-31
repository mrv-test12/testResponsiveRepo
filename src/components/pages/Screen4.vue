<template>
  <DropZone ncBgType="bgImage"
    backgroundImage="https://steamuserimages-a.akamaihd.net/ugc/940586530515504757/CDDE77CB810474E1C07B945E40AE4713141AFD76/?imw=5000&amp;imh=5000&amp;ima=fit&amp;impolicy=Letterbox&amp;imcolor=%23000000&amp;letterbox=false"
    id="ed67e462-956f-4036-8a00-3ee714292ebf" v-bind:style="{'width':'100%','height':'auto'}">
    <WPillSuccessButton tag="button" href="" v-bind:pill="true" size="md" text="Success" type="button"
      v-bind:block="false" color="#FFFF00FF" v-bind:snapX="false" v-bind:snapY="false" theme="theme--light01"
      v-bind:squared="false" variant="success" position="relative" v-bind:isEnabled="true" background="#28a745"
      linkTarget="_top" ncLinkType="router_link" borderColor="#28A745" ncTypography="body1" v-bind:resetTrigger="false"
      ncTooltipText="" verticalWidth="60px"
      v-bind:nucalDataModel="{'type':'NSW','isList':false,'dynamic':false,'structure':[{'type':'string','propName':'text','displayName':'Value'}]}"
      verticalHeight="60px" horizontalWidth="72.4479px" toForRouterLink="Screen+1" horizontalHeight="37.5347px"
      ncClickFontColor="#FFFFFF" ncFocusFontColor="#FFFFFF" ncHoverFontColor="#FFFFFF" ncClickBorderColor="#28A745"
      ncDisableFontColor="#FFFFFF" ncFocusBorderColor="#28A745" ncHoverBorderColor="#28A745"
      ncDisableBorderColor="transparent" ncClickBackgroundColor="#28A745" ncFocusBackgroundColor="#28A745"
      ncHoverBackgroundColor="#28A745" ncDisableBackgroundColor="#969696" id="b07c66d9-bef5-4674-9d43-23ca543be087"
      v-bind:style="{'width':'100%','height':'100%','zIndex':2,'tabIndex':'0px','boxShadow':'','fontStyle':'normal','marginTop':'0px','textAlign':'center','fontFamily':'OpenSans-Bold,Open Sans','fontWeight':'bold','lineHeight':'1.4','marginLeft':'0px','paddingTop':'','textShadow':'','visibility':'visible','borderStyle':'solid','marginRight':'0px','paddingLeft':'','marginBottom':'0px','paddingRight':'','paddingBottom':'','borderTopWidth':'1px','textDecoration':'none','borderLeftWidth':'1px','borderRightWidth':'1px','horizontalHeight':'37.5347px','borderBottomWidth':'1px','borderTopLeftRadius':'4px','borderTopRightRadius':'4px','borderBottomLeftRadius':'4px','borderBottomRightRadius':'4px'}"/>
    <WParagraph
      text="Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident."
      v-bind:snapX="false" v-bind:snapY="false" theme="theme--light01" position="relative" v-bind:isClipping="false"
      ncTypography="custom" ncTooltipText=""
      v-bind:nucalDataModel="{'type':'NSW','isList':false,'dynamic':false,'structure':[{'type':'string','propName':'text','displayName':'Value'}]}"
      id="986662af-ae19-4a26-9dfd-cab627854ea2"
      v-bind:style="{'wrap':'md','color':'#FFFFFFFF','width':'100%','height':'100%','zIndex':3,'fontStyle':'normal','marginTop':'0px','textAlign':'center','background':'transparent','fontFamily':'Roboto-Regular,Roboto','fontWeight':'normal','lineHeight':'1.4','marginLeft':'0px','paddingTop':'0px','textIndent':'0px','visibility':'visible','whiteSpace':'pre-wrap','marginRight':'0px','paddingLeft':'0px','wordSpacing':'0px','marginBottom':'0px','paddingRight':'0px','letterSpacing':'0px','paddingBottom':'0px','textTransform':'none','textDecoration':'none'}"/>
  </DropZone>
</template>
<script>
export default {
  name: 'Screen4',
  data() {
    return {};
  },
  props: {},
  created() {},
  mounted() {},
  computed: {},
  methods: {},
  watch: {},
};
</script>

<style lang="scss" scoped>
@media (min-width: 1024.05px){[id='ed67e462-956f-4036-8a00-3ee714292ebf'] {
             display: grid; 
             grid-template-columns: 13.75rem 21.015625rem 29.375rem 18.359375rem 17.5rem;
             grid-template-rows: minmax(2.8125rem, max-content) minmax(12.5rem, max-content) minmax(3.90625rem, max-content) minmax(18.515625rem, max-content) minmax(9.140625rem, max-content);
          }
[id='b07c66d9-bef5-4674-9d43-23ca543be087']{
          grid-area: 2/3/3/4;
          font-size: Max(Min(12rem, 12px),0.9375rem);
          
          }
[id='986662af-ae19-4a26-9dfd-cab627854ea2']{
          grid-area: 4/2/5/5;
          font-size: Max(Min(26rem, 12px),2.03125rem);
          
          }}

@media (min-width: 768.05px) and (max-width: 1024px){[id='ed67e462-956f-4036-8a00-3ee714292ebf'] {
             display: grid; 
             grid-template-columns: 3.125rem 28.515625rem 36.71875rem 28.515625rem 3.125rem;
             grid-template-rows: minmax(3.515625rem, max-content) minmax(15.625rem, max-content) minmax(4.8828125rem, max-content) minmax(25.248579545454543rem, max-content) minmax(3.125rem, max-content);
          }
[id='b07c66d9-bef5-4674-9d43-23ca543be087']{
          grid-area: 2/3/3/4;
          font-size: Max(Min(12rem, 12px),1.171875rem);
          
          }
[id='986662af-ae19-4a26-9dfd-cab627854ea2']{
          grid-area: 4/2/5/5;
          font-size: Max(Min(26rem, 12px),2.7698863636363633rem);
          
          }}

@media (min-width: 480.05px) and (max-width: 768px){[id='ed67e462-956f-4036-8a00-3ee714292ebf'] {
             display: grid; 
             grid-template-columns: 4.166666667000001rem 21.35416666633333rem 48.958333333333336rem 21.354166666333334rem 4.166666667000001rem;
             grid-template-rows: minmax(4.6875rem, max-content) minmax(20.833333333333332rem, max-content) minmax(6.510416666666667rem, max-content) minmax(24.687499999820453rem, max-content) minmax(4.166666667rem, max-content);
          }
[id='b07c66d9-bef5-4674-9d43-23ca543be087']{
          grid-area: 2/3/3/4;
          font-size: Max(Min(12rem, 12px),1.5625rem);
          
          }
[id='986662af-ae19-4a26-9dfd-cab627854ea2']{
          grid-area: 4/2/5/5;
          font-size: Max(Min(26rem, 12px),2.7083333333136363rem);
          
          }}

@media (min-width: 375.05px) and (max-width: 480px){[id='ed67e462-956f-4036-8a00-3ee714292ebf'] {
             display: grid; 
             grid-template-columns: 5rem 0 90rem 0 5rem;
             grid-template-rows: minmax(7.5rem, max-content) minmax(38.297872340425535rem, max-content) minmax(10.416666666666666rem, max-content) minmax(24.238636363636363rem, max-content) minmax(5rem, max-content);
          }
[id='b07c66d9-bef5-4674-9d43-23ca543be087']{
          grid-area: 2/2/3/5;
          font-size: Max(Min(12rem, 12px),2.872340425531915rem);
          
          }
[id='986662af-ae19-4a26-9dfd-cab627854ea2']{
          grid-area: 4/3/5/4;
          font-size: Max(Min(26rem, 12px),2.659090909090909rem);
          
          }}

@media (min-width: 0px) and (max-width: 375px){[id='ed67e462-956f-4036-8a00-3ee714292ebf'] {
             display: grid; 
             grid-template-columns: 6.4rem 0 87.2rem 0 6.4rem;
             grid-template-rows: minmax(9.6rem, max-content) minmax(37.1063829787234rem, max-content) minmax(13.333333333333334rem, max-content) minmax(23.484545454545458rem, max-content) minmax(6.4rem, max-content);
          }
[id='b07c66d9-bef5-4674-9d43-23ca543be087']{
          grid-area: 2/2/3/5;
          font-size: Max(Min(12rem, 12px),2.7829787234042556rem);
          
          }
[id='986662af-ae19-4a26-9dfd-cab627854ea2']{
          grid-area: 4/3/5/4;
          font-size: Max(Min(26rem, 12px),2.5763636363636366rem);
          
          }}
</style>