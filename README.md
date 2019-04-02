# ex2

实验截图：

https://github.com/7419adf/ex2/blob/master/images/%E7%BA%A6%E6%9D%9F%E5%B8%83%E5%B1%80.png
https://github.com/7419adf/ex2/blob/master/images/%E7%BA%BF%E6%80%A7%E5%B8%83%E5%B1%80.png
https://github.com/7419adf/ex2/blob/master/images/%E8%A1%A8%E6%A0%BC%E5%B8%83%E5%B1%80.png

实验代码：

线性布局：
<LinearLayout xmlns:android="http://schemas.android.com/apk/res/android"
    android:layout_width="match_parent"
    android:layout_height="wrap_content"
    android:background="#000000"
    android:orientation="vertical">

    <LinearLayout
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        android:orientation="horizontal">

        <Button
            android:id="@+id/btn_one_one"
            android:layout_width="0dp"
            android:layout_height="wrap_content"
            android:textAllCaps="false"
            android:layout_marginLeft="4dp"
            android:layout_marginTop="2dp"
            android:layout_marginRight="4dp"
            android:layout_marginBottom="2dp"
            android:layout_weight="1"
            android:background="@drawable/button_shape"
            android:text="One，One"
            android:textColor="#FFFFFF"
            android:textSize="14sp" />

        <Button
            android:id="@+id/btn_one_two"
            android:layout_width="0dp"
            android:layout_height="wrap_content"
            android:layout_marginLeft="4dp"
            android:layout_marginTop="2dp"
            android:layout_marginRight="4dp"
            android:layout_marginBottom="2dp"
            android:textAllCaps="false"
            android:layout_weight="2"
            android:background="@drawable/button_shape"
            android:text="One，Two"
            android:textColor="#FFFFFF"
            android:textSize="14sp" />

        <Button
            android:id="@+id/btn_one_three"
            android:layout_width="0dp"
            android:layout_height="wrap_content"
            android:layout_marginLeft="4dp"
            android:layout_marginTop="2dp"
            android:layout_marginRight="4dp"
            android:layout_marginBottom="2dp"
            android:textAllCaps="false"
            android:layout_weight="1"
            android:background="@drawable/button_shape"
            android:text="One，Three"
            android:textColor="#FFFFFF"
            android:textSize="14sp" />

        <Button
            android:id="@+id/btn_one_four"
            android:layout_width="0dp"
            android:layout_height="wrap_content"
            android:layout_marginLeft="4dp"
            android:layout_marginTop="2dp"
            android:layout_marginRight="4dp"
            android:layout_marginBottom="2dp"
            android:textAllCaps="false"
            android:layout_weight="1"
            android:background="@drawable/button_shape"
            android:text="One，Four"
            android:textColor="#FFFFFF"
            android:textSize="14sp" />
    </LinearLayout>

    <LinearLayout
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        android:orientation="horizontal">

        <Button
            android:id="@+id/btn_two_one"
            android:layout_width="0dp"
            android:layout_height="wrap_content"
            android:layout_marginLeft="4dp"
            android:layout_marginTop="2dp"
            android:layout_marginRight="4dp"
            android:layout_marginBottom="2dp"
            android:textAllCaps="false"
            android:layout_weight="1"
            android:background="@drawable/button_shape"
            android:text="Two，One"
            android:textColor="#FFFFFF"
            android:textSize="14sp" />

        <Button
            android:id="@+id/btn_two_two"
            android:layout_width="0dp"
            android:layout_height="wrap_content"
            android:layout_marginLeft="4dp"
            android:layout_marginTop="2dp"
            android:layout_marginRight="4dp"
            android:layout_marginBottom="2dp"
            android:textAllCaps="false"
            android:layout_weight="2"
            android:background="@drawable/button_shape"
            android:text="Two，Two"
            android:textColor="#FFFFFF"
            android:textSize="14sp" />

        <Button
            android:id="@+id/btn_two_three"
            android:layout_width="0dp"
            android:layout_height="wrap_content"
            android:layout_marginLeft="4dp"
            android:layout_marginTop="2dp"
            android:layout_marginRight="4dp"
            android:layout_marginBottom="2dp"
            android:textAllCaps="false"
            android:layout_weight="1"
            android:background="@drawable/button_shape"
            android:text="Two，Three"
            android:textColor="#FFFFFF"
            android:textSize="14sp" />

        <Button
            android:id="@+id/btn_two_four"
            android:layout_width="0dp"
            android:layout_height="wrap_content"
            android:layout_marginLeft="4dp"
            android:layout_marginTop="2dp"
            android:layout_marginRight="4dp"
            android:layout_marginBottom="2dp"
            android:textAllCaps="false"
            android:layout_weight="1"
            android:background="@drawable/button_shape"
            android:text="Two，Four"
            android:textColor="#FFFFFF"
            android:textSize="14sp" />
    </LinearLayout>

    <LinearLayout
        android:layout_width="match_parent"
        android:layout_height="wrap_content">

        <Button
            android:id="@+id/btn_three_one"
            android:layout_width="0dp"
            android:layout_height="wrap_content"
            android:layout_marginLeft="4dp"
            android:layout_marginTop="2dp"
            android:layout_marginRight="4dp"
            android:layout_marginBottom="2dp"
            android:textAllCaps="false"
            android:layout_weight="1"
            android:background="@drawable/button_shape"
            android:text="Three，One"
            android:textColor="#FFFFFF"
            android:textSize="14sp" />

        <Button
            android:id="@+id/btn_three_two"
            android:layout_width="0dp"
            android:layout_height="wrap_content"
            android:layout_marginLeft="4dp"
            android:layout_marginTop="2dp"
            android:layout_marginRight="4dp"
            android:layout_marginBottom="2dp"
            android:textAllCaps="false"
            android:layout_weight="1"
            android:background="@drawable/button_shape"
            android:text="Three，Two"
            android:textColor="#FFFFFF"
            android:textSize="14sp" />

        <Button
            android:id="@+id/btn_three_three"
            android:layout_width="0dp"
            android:layout_height="wrap_content"
            android:layout_marginLeft="4dp"
            android:layout_marginTop="2dp"
            android:layout_marginRight="4dp"
            android:layout_marginBottom="2dp"
            android:textAllCaps="false"
            android:layout_weight="1"
            android:background="@drawable/button_shape"
            android:text="Three，Three"
            android:textColor="#FFFFFF"
            android:textSize="14sp" />

        <Button
            android:id="@+id/btn_three_four"
            android:layout_width="0dp"
            android:layout_height="wrap_content"
            android:layout_marginLeft="4dp"
            android:layout_marginTop="2dp"
            android:layout_marginRight="4dp"
            android:layout_marginBottom="2dp"
            android:textAllCaps="false"
            android:layout_weight="1"
            android:background="@drawable/button_shape"
            android:text="Three，Four"
            android:textColor="#FFFFFF"
            android:textSize="14sp" />
    </LinearLayout>

    <LinearLayout
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        android:orientation="horizontal">

        <Button
            android:id="@+id/btn_four_one"
            android:layout_width="0dp"
            android:layout_height="wrap_content"
            android:layout_marginLeft="4dp"
            android:layout_marginTop="2dp"
            android:layout_marginRight="4dp"
            android:layout_marginBottom="2dp"
            android:textAllCaps="false"
            android:layout_weight="1"
            android:background="@drawable/button_shape"
            android:text="Four，One"
            android:textColor="#FFFFFF"
            android:textSize="14sp" />

        <Button
            android:id="@+id/btn_four_two"
            android:layout_width="0dp"
            android:layout_height="match_parent"
            android:layout_marginLeft="4dp"
            android:layout_marginTop="2dp"
            android:layout_marginRight="4dp"
            android:layout_marginBottom="2dp"
            android:textAllCaps="false"
            android:layout_weight="2"
            android:background="@drawable/button_shape"
            android:text="Four，Two"
            android:textColor="#FFFFFF"
            android:textSize="14sp" />

        <Button
            android:id="@+id/btn_four_three"
            android:layout_width="0dp"
            android:layout_height="wrap_content"
            android:layout_marginLeft="4dp"
            android:layout_marginTop="2dp"
            android:layout_marginRight="4dp"
            android:layout_marginBottom="2dp"
            android:textAllCaps="false"
            android:layout_weight="1"
            android:background="@drawable/button_shape"
            android:text="Four，Three"
            android:textColor="#FFFFFF"
            android:textSize="14sp" />

        <Button
            android:id="@+id/btn_four_four"
            android:layout_width="0dp"
            android:layout_height="wrap_content"
            android:layout_marginLeft="4dp"
            android:layout_marginTop="2dp"
            android:layout_marginRight="4dp"
            android:layout_marginBottom="2dp"
            android:textAllCaps="false"
            android:layout_weight="1"
            android:background="@drawable/button_shape"
            android:text="Four，Four"
            android:textColor="#FFFFFF"
            android:textSize="14sp" />
    </LinearLayout>


</LinearLayout>


约束布局：

<?xml version="1.0" encoding="utf-8"?>
<android.support.constraint.ConstraintLayout xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:app="http://schemas.android.com/apk/res-auto"
    xmlns:tools="http://schemas.android.com/tools"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    android:background="#000000"
    tools:context=".Main2Activity">
    <Button
        android:id="@+id/button"
        android:layout_width="wrap_content"
        android:layout_height="47dp"
        android:layout_marginStart="224dp"
        android:layout_marginLeft="224dp"
        android:layout_marginBottom="8dp"
        android:background="#FFFF00"
        android:text="YELLOW"
        app:layout_constraintBottom_toBottomOf="parent"
        app:layout_constraintEnd_toEndOf="parent"
        app:layout_constraintHorizontal_bias="1.0"
        app:layout_constraintStart_toEndOf="@+id/button3"
        app:layout_constraintTop_toTopOf="parent"
        app:layout_constraintVertical_bias="0.0" />
    <Button
        android:id="@+id/button3"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:layout_marginBottom="8dp"
        android:background="@android:color/holo_red_light"
        android:text="RED"
        app:layout_constraintBottom_toBottomOf="parent"
        app:layout_constraintStart_toStartOf="parent"
        app:layout_constraintTop_toTopOf="parent"
        app:layout_constraintVertical_bias="0.0" />

    <Button
        android:id="@+id/button4"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:layout_marginStart="8dp"
        android:layout_marginLeft="8dp"
        android:layout_marginEnd="8dp"
        android:layout_marginRight="8dp"
        android:background="@android:color/holo_orange_light"
        android:text="ORANGE"
        app:layout_constraintEnd_toStartOf="@+id/button"
        app:layout_constraintStart_toEndOf="@+id/button3"
        app:layout_constraintTop_toTopOf="parent" />
    <Button
        android:id="@+id/button5"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:layout_marginStart="8dp"
        android:layout_marginLeft="8dp"
        android:layout_marginTop="8dp"
        android:layout_marginEnd="8dp"
        android:layout_marginRight="8dp"
        android:layout_marginBottom="8dp"
        android:background="#90EE90"
        android:text="GREEN"
        app:layout_constraintBottom_toBottomOf="parent"
        app:layout_constraintEnd_toStartOf="@+id/button6"
        app:layout_constraintHorizontal_bias="0.538"
        app:layout_constraintStart_toStartOf="parent"
        app:layout_constraintTop_toTopOf="parent"
        app:layout_constraintVertical_bias="0.243" />
    <Button
        android:id="@+id/button6"
        android:layout_width="72dp"
        android:layout_height="54dp"
        android:layout_marginStart="8dp"
        android:layout_marginLeft="8dp"
        android:layout_marginTop="8dp"
        android:layout_marginEnd="8dp"
        android:layout_marginRight="8dp"
        android:layout_marginBottom="8dp"
        android:background="#0000FF"
        android:text="BLUE"
        app:layout_constraintBottom_toBottomOf="parent"
        app:layout_constraintEnd_toEndOf="parent"
        app:layout_constraintHorizontal_bias="0.498"
        app:layout_constraintStart_toStartOf="parent"
        app:layout_constraintTop_toTopOf="parent"
        app:layout_constraintVertical_bias="0.245" />
    <Button
        android:id="@+id/button7"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:layout_marginStart="12dp"
        android:layout_marginLeft="12dp"
        android:layout_marginTop="8dp"
        android:layout_marginEnd="8dp"
        android:layout_marginRight="8dp"
        android:layout_marginBottom="8dp"
        android:background="#4B0082"
        android:text="INDIGO"
        app:layout_constraintBottom_toBottomOf="parent"
        app:layout_constraintEnd_toEndOf="parent"
        app:layout_constraintHorizontal_bias="0.475"
        app:layout_constraintStart_toEndOf="@+id/button6"
        app:layout_constraintTop_toTopOf="parent"
        app:layout_constraintVertical_bias="0.243" />
    <Button
        android:id="@+id/button8"
        android:layout_width="411dp"
        android:layout_height="64dp"
        android:layout_marginTop="8dp"
        android:layout_marginBottom="8dp"
        android:background="#EE82EE"
        android:text="VIOLET"
        app:layout_constraintBottom_toBottomOf="parent"
        app:layout_constraintEnd_toEndOf="parent"
        app:layout_constraintHorizontal_bias="1.0"
        app:layout_constraintStart_toStartOf="parent"
        app:layout_constraintTop_toBottomOf="@+id/button6"
        app:layout_constraintVertical_bias="0.166" />
    
</android.support.constraint.ConstraintLayout>



表格布局：

<?xml version="1.0" encoding="utf-8"?>
<TableLayout xmlns:android="http://schemas.android.com/apk/res/android"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    android:background="@android:color/black"
    android:stretchColumns="1">

    <TableRow>

        <TextView
            android:padding="3dip"
            android:text="   Open..."
            android:textColor="#FFFFFF"/>

        <TextView
            android:gravity="right"
            android:padding="3dip"
            android:text="Ctrl-O"
            android:textColor="#FFFFFF"/>
    </TableRow>

    <TableRow>

        <TextView
            android:padding="3dip"
            android:text="   Save..."
            android:textColor="#FFFFFF"/>

        <TextView
            android:gravity="right"
            android:padding="3dip"
            android:text="Ctrl-S"
            android:textColor="#FFFFFF"/>
    </TableRow>

    <TableRow>

        <TextView
            android:padding="3dip"
            android:text="   Save As..."
            android:textColor="#FFFFFF"/>

        <TextView
            android:gravity="right"
            android:padding="3dip"
            android:text="Ctrl-Shift-S"
            android:textColor="#FFFFFF"/>
    </TableRow>
    <View
        android:layout_alignParentBottom="true"
        android:background="#FFFFFF"
        android:layout_width="fill_parent"
        android:layout_height="2dip"/>
    <TableRow>
        <TextView
            android:padding="3dip"
            android:text="X Import..."
            android:textColor="#FFFFFF"
            />
    </TableRow>
    <TableRow>

        <TextView
            android:padding="3dip"
            android:text="X Export..."
            android:textColor="#FFFFFF"/>

        <TextView
            android:gravity="right"
            android:padding="3dip"
            android:text="Ctrl-E"
            android:textColor="#FFFFFF"/>
    </TableRow>
    <View
        android:layout_alignParentBottom="true"
        android:background="#FFFFFF"
        android:layout_width="fill_parent"
        android:layout_height="2dip"/>
    <TableRow>

        <TextView
            android:padding="3dip"
            android:text="   Quit"
            android:textColor="#FFFFFF"/>
    </TableRow>

</TableLayout>
