package com.example.myapp

import android.os.Bundle
import androidx.activity.ComponentActivity
import androidx.activity.compose.setContent
import androidx.compose.material3.Text
import androidx.compose.runtime.Composable
import androidx.compose.ui.tooling.preview.Preview
import com.example.myapp.ui.theme.MyAppTheme

class MainActivity : ComponentActivity() {
    override fun onCreate(savedInstanceState: Bundle?) {
        super.onCreate(savedInstanceState)
        setContent {
            MyAppTheme {
                Hello(name = "Дмитрий")
                // Hello(name = null)
            }
        }
    }
}

@Composable
fun Hello(name: String?) {
    Text(text = if (name != null) "Привет, $name!" else "Имя не задано")
}

@Preview(name = "portrait", showSystemUi = true)
@Preview(
    name = "landscape",
    showSystemUi = true,
    device = "spec:parent=pixel_8,orientation=landscape"
)
@Preview(
    name = "round",
    showSystemUi = true,
    showBackground = true,
    backgroundColor = 0xFFFFFF00,
    device = "spec:width=200dp,height=200dp,isRound=true"
)

@Composable
fun HelloPreview() {
    MyAppTheme {
        Hello(name = "Дмитрий")
    }
}
