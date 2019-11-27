# quill-ee-source-button
    show source button for quill editor, working with quill-vue-editor
    support quill-2.0.0-dev 3|4|5 + quill-1.*

# usage 
    import { eeSourceBtn } from '@/components/quill/quill.eeSourceBtn.js';
    Quill.register('modules/eeSourceBtn', eeSourceBtn);
  
  
    ...
    modules: {
    ...
      eeSourceBtn: {},
    
    
# working as
will show a ">_" button in the end of the toolbar, click will switch to source editor, click again will switch back, and update the quill editor



# idea from  
    https://codepen.io/anon/pen/ZyEjrQ
    just wrapper it as a js file for vue use, and did very small style change.

    right now it's free for use.
