# android-databind_lecture

1. build.gradle(Module)
 add dataBinding { 
  enabled true 
 }
 
2. layout 감싸기
3. private lateinit var binding : ActivityMainBinding
4. binding = DataBindingUtil.setContentView(this, R.layout.activity_main)
5. binding.btn.setOnClickListener {
        Toast.makeText(this, "click", Toast.LENGTH_LONG).show()
    }
