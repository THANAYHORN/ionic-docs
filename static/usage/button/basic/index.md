import Playground from '../../../../src/components/global/Playground';
import PlaygroundCode from '../../../../src/components/global/PlaygroundCode';
import JavaScriptCode from './javascript.md'
import ReactCode from './react.md'
import VueCode from './vue.md'
import AngularCode from './angular.md'

<Playground>
  <PlaygroundCode name="javascript">
    <JavaScriptCode />
  </PlaygroundCode>
  
  <PlaygroundCode name="react">
    <ReactCode />
  </PlaygroundCode>
  
  <PlaygroundCode name="vue">
    <VueCode />
  </PlaygroundCode>
  
  <PlaygroundCode name="angular">
    <AngularCode />
  </PlaygroundCode>
</Playground>