Code:

var ch = $0.children[0].children
var str = "";
for(var child of ch){
	if(child.hasChildNodes()) 
str += child.firstChild.firstChild.firstChild.firstChild.children[1].firstChild.firstChild.innerText + "\n";
}
