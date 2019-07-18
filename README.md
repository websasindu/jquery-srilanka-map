# jquery-srilanka-map
Sri Lanka Map Using HTML And Jquery. Free and easy integration sri lanka map into your web site for developing.

-----------------------------------Sri Lanka Map Using SVG And Jquery------------------------------------------

Copy div id #srilankamap to your development page and customize element using css as you want.
This sample made using attribte of element
Insert jquery script inside of any where in page

<code>
  var selected_city='';
  $(document).on("click","#slmap path",function(){
      $("#slmap path").css("fill","#9E9E9E");
      $(this).css("fill","#ee2f5b");
      /** Here Selected city**//
        selected_city=$(this).attr("title");
        alert(selected_city);
     /** Here Selected city**//
  });
 </code>
 
 For more info http://sasindu.com/sri-lanka-jquery-map


