
@Library('sharedLibrary')_
//import com.aexp.func 
 //
node("master"){
 println "Seconf Node"
//def te = new func()
 def te = new com.aexp.func()
def val = te.func1()
 println val
 stage("Build"){
    testPipeline{
      item = "girish"
      name="Reddy"      
    }
 }
}
