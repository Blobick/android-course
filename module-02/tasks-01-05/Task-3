package com.example.myapp

import androidx.compose.foundation.background
import androidx.compose.foundation.layout.Column
import androidx.compose.material3.Text
import androidx.compose.runtime.Composable
import androidx.compose.ui.Modifier
import androidx.compose.ui.graphics.Color
import androidx.compose.ui.res.stringResource
import androidx.compose.ui.text.TextStyle
import androidx.compose.ui.text.font.FontStyle
import androidx.compose.ui.text.style.TextAlign
import androidx.compose.ui.text.style.TextDecoration
import androidx.compose.ui.text.style.TextIndent
import androidx.compose.ui.text.style.TextOverflow
import androidx.compose.ui.tooling.preview.Preview
import androidx.compose.ui.unit.sp
import com.example.myapp.ui.theme.MyAppTheme

@Composable
fun TextVariants() {
    val textValue = stringResource(id = R.string.compose_info)
    Column {
        Text(
            text = textValue,
            color = Color.Green,
            fontSize = 16.sp,
            fontStyle = FontStyle.Italic,
            textAlign = TextAlign.Center
        )

        Text(
            text = textValue,
            maxLines = 1,
            overflow = TextOverflow.Ellipsis
        )

        Text(
            text = textValue,
            color = Color.Black,
            fontSize = 24.sp,
            textDecoration = TextDecoration.Underline,
            style = TextStyle(textIndent = TextIndent(firstLine = 48.sp)),
            modifier = Modifier.background(Color.Green)
        )
    }
}

@Preview(name = "portrait", showSystemUi = true)
@Composable
fun Task3Preview() {
    MyAppTheme {
        TextVariants()
    }
}
