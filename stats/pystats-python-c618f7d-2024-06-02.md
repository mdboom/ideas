## Execution counts

<details>
<summary> Execution counts for Tier 1 instructions. </summary>


The "miss ratio" column shows the percentage of times the instruction
executed that it deoptimized. When this happens, the base unspecialized
instruction is not counted.

<table>
<thead>
<tr>
<th align="left">Name</th>
<th align="right">Count</th>
<th align="right">Self</th>
<th align="right">Cumulative</th>
<th align="right">Miss ratio</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">21,913,890,923</td>
<td align="right">18.9%</td>
<td align="right">18.9%</td>
<td align="right"></td>
</tr>
<tr>
<td align="left">STORE_FAST</td>
<td align="right">6,931,225,501</td>
<td align="right">6.0%</td>
<td align="right">24.9%</td>
<td align="right"></td>
</tr>
<tr>
<td align="left">LOAD_CONST</td>
<td align="right">6,288,469,980</td>
<td align="right">5.4%</td>
<td align="right">30.3%</td>
<td align="right"></td>
</tr>
<tr>
<td align="left">POP_JUMP_IF_FALSE</td>
<td align="right">5,350,932,934</td>
<td align="right">4.6%</td>
<td align="right">34.9%</td>
<td align="right"></td>
</tr>
<tr>
<td align="left">LOAD_FAST_LOAD_FAST</td>
<td align="right">5,104,228,577</td>
<td align="right">4.4%</td>
<td align="right">39.3%</td>
<td align="right"></td>
</tr>
<tr>
<td align="left">RESUME_CHECK</td>
<td align="right">4,391,695,835</td>
<td align="right">3.8%</td>
<td align="right">43.1%</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_INSTANCE_VALUE</td>
<td align="right">3,670,445,782</td>
<td align="right">3.2%</td>
<td align="right">46.3%</td>
<td align="right">4.7%</td>
</tr>
<tr>
<td align="left">LOAD_GLOBAL_BUILTIN</td>
<td align="right">3,357,587,013</td>
<td align="right">2.9%</td>
<td align="right">49.2%</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">TO_BOOL_BOOL</td>
<td align="right">2,797,975,259</td>
<td align="right">2.4%</td>
<td align="right">51.6%</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">STORE_FAST_STORE_FAST</td>
<td align="right">2,488,798,924</td>
<td align="right">2.1%</td>
<td align="right">53.8%</td>
<td align="right"></td>
</tr>
<tr>
<td align="left">RETURN_VALUE</td>
<td align="right">2,462,421,213</td>
<td align="right">2.1%</td>
<td align="right">55.9%</td>
<td align="right"></td>
</tr>
<tr>
<td align="left">POP_TOP</td>
<td align="right">2,278,595,325</td>
<td align="right">2.0%</td>
<td align="right">57.9%</td>
<td align="right"></td>
</tr>
<tr>
<td align="left">JUMP_BACKWARD</td>
<td align="right">2,172,096,118</td>
<td align="right">1.9%</td>
<td align="right">59.7%</td>
<td align="right"></td>
</tr>
<tr>
<td align="left">CALL_PY_EXACT_ARGS</td>
<td align="right">2,169,482,813</td>
<td align="right">1.9%</td>
<td align="right">61.6%</td>
<td align="right">2.0%</td>
</tr>
<tr>
<td align="left">LOAD_GLOBAL_MODULE</td>
<td align="right">2,097,449,648</td>
<td align="right">1.8%</td>
<td align="right">63.4%</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_METHOD_WITH_VALUES</td>
<td align="right">1,714,563,576</td>
<td align="right">1.5%</td>
<td align="right">64.9%</td>
<td align="right">9.9%</td>
</tr>
<tr>
<td align="left">COMPARE_OP_INT</td>
<td align="right">1,321,554,679</td>
<td align="right">1.1%</td>
<td align="right">66.0%</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">BINARY_OP_ADD_INT</td>
<td align="right">1,266,230,259</td>
<td align="right">1.1%</td>
<td align="right">67.1%</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">INTERPRETER_EXIT</td>
<td align="right">1,236,283,106</td>
<td align="right">1.1%</td>
<td align="right">68.2%</td>
<td align="right"></td>
</tr>
<tr>
<td align="left">POP_JUMP_IF_TRUE</td>
<td align="right">1,210,056,788</td>
<td align="right">1.0%</td>
<td align="right">69.2%</td>
<td align="right"></td>
</tr>
<tr>
<td align="left">LOAD_ATTR_SLOT</td>
<td align="right">1,083,673,910</td>
<td align="right">0.9%</td>
<td align="right">70.2%</td>
<td align="right">7.0%</td>
</tr>
<tr>
<td align="left">RETURN_CONST</td>
<td align="right">1,082,615,239</td>
<td align="right">0.9%</td>
<td align="right">71.1%</td>
<td align="right"></td>
</tr>
<tr>
<td align="left">PUSH_NULL</td>
<td align="right">1,072,058,665</td>
<td align="right">0.9%</td>
<td align="right">72.0%</td>
<td align="right"></td>
</tr>
<tr>
<td align="left">FOR_ITER_LIST</td>
<td align="right">1,069,334,610</td>
<td align="right">0.9%</td>
<td align="right">73.0%</td>
<td align="right">6.1%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR</td>
<td align="right">1,037,158,162</td>
<td align="right">0.9%</td>
<td align="right">73.9%</td>
<td align="right"></td>
</tr>
<tr>
<td align="left">BINARY_SUBSCR</td>
<td align="right">1,034,886,592</td>
<td align="right">0.9%</td>
<td align="right">74.7%</td>
<td align="right"></td>
</tr>
<tr>
<td align="left">LOAD_ATTR_METHOD_NO_DICT</td>
<td align="right">1,001,325,278</td>
<td align="right">0.9%</td>
<td align="right">75.6%</td>
<td align="right">0.9%</td>
</tr>
<tr>
<td align="left">BINARY_OP</td>
<td align="right">964,183,706</td>
<td align="right">0.8%</td>
<td align="right">76.4%</td>
<td align="right"></td>
</tr>
<tr>
<td align="left">COPY</td>
<td align="right">957,199,430</td>
<td align="right">0.8%</td>
<td align="right">77.3%</td>
<td align="right"></td>
</tr>
<tr>
<td align="left">YIELD_VALUE</td>
<td align="right">957,087,042</td>
<td align="right">0.8%</td>
<td align="right">78.1%</td>
<td align="right"></td>
</tr>
<tr>
<td align="left">CALL_BUILTIN_FAST</td>
<td align="right">942,489,658</td>
<td align="right">0.8%</td>
<td align="right">78.9%</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">BINARY_OP_MULTIPLY_FLOAT</td>
<td align="right">874,732,236</td>
<td align="right">0.8%</td>
<td align="right">79.7%</td>
<td align="right">0.8%</td>
</tr>
<tr>
<td align="left">BINARY_SUBSCR_LIST_INT</td>
<td align="right">860,107,753</td>
<td align="right">0.7%</td>
<td align="right">80.4%</td>
<td align="right">0.4%</td>
</tr>
<tr>
<td align="left">SWAP</td>
<td align="right">849,030,343</td>
<td align="right">0.7%</td>
<td align="right">81.1%</td>
<td align="right"></td>
</tr>
<tr>
<td align="left">CALL_BUILTIN_O</td>
<td align="right">807,673,081</td>
<td align="right">0.7%</td>
<td align="right">81.8%</td>
<td align="right">0.2%</td>
</tr>
<tr>
<td align="left">STORE_ATTR_INSTANCE_VALUE</td>
<td align="right">687,740,617</td>
<td align="right">0.6%</td>
<td align="right">82.4%</td>
<td align="right">9.1%</td>
</tr>
<tr>
<td align="left">LOAD_DEREF</td>
<td align="right">675,513,256</td>
<td align="right">0.6%</td>
<td align="right">83.0%</td>
<td align="right"></td>
</tr>
<tr>
<td align="left">BUILD_TUPLE</td>
<td align="right">577,229,854</td>
<td align="right">0.5%</td>
<td align="right">83.5%</td>
<td align="right"></td>
</tr>
<tr>
<td align="left">UNPACK_SEQUENCE_TWO_TUPLE</td>
<td align="right">560,944,836</td>
<td align="right">0.5%</td>
<td align="right">84.0%</td>
<td align="right"></td>
</tr>
<tr>
<td align="left">STORE_ATTR_SLOT</td>
<td align="right">546,366,165</td>
<td align="right">0.5%</td>
<td align="right">84.5%</td>
<td align="right">2.6%</td>
</tr>
<tr>
<td align="left">UNPACK_SEQUENCE_TUPLE</td>
<td align="right">538,418,178</td>
<td align="right">0.5%</td>
<td align="right">84.9%</td>
<td align="right">0.2%</td>
</tr>
<tr>
<td align="left">IS_OP</td>
<td align="right">515,697,814</td>
<td align="right">0.4%</td>
<td align="right">85.4%</td>
<td align="right"></td>
</tr>
<tr>
<td align="left">BINARY_OP_SUBTRACT_INT</td>
<td align="right">494,996,615</td>
<td align="right">0.4%</td>
<td align="right">85.8%</td>
<td align="right">0.1%</td>
</tr>
<tr>
<td align="left">SEND_GEN</td>
<td align="right">488,011,628</td>
<td align="right">0.4%</td>
<td align="right">86.2%</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">CALL_ISINSTANCE</td>
<td align="right">451,467,397</td>
<td align="right">0.4%</td>
<td align="right">86.6%</td>
<td align="right"></td>
</tr>
<tr>
<td align="left">FOR_ITER_RANGE</td>
<td align="right">449,947,120</td>
<td align="right">0.4%</td>
<td align="right">87.0%</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">GET_ITER</td>
<td align="right">445,072,507</td>
<td align="right">0.4%</td>
<td align="right">87.4%</td>
<td align="right"></td>
</tr>
<tr>
<td align="left">NOP</td>
<td align="right">432,259,375</td>
<td align="right">0.4%</td>
<td align="right">87.8%</td>
<td align="right"></td>
</tr>
<tr>
<td align="left">BINARY_OP_ADD_FLOAT</td>
<td align="right">410,236,797</td>
<td align="right">0.4%</td>
<td align="right">88.1%</td>
<td align="right">1.5%</td>
</tr>
<tr>
<td align="left">JUMP_BACKWARD_NO_INTERRUPT</td>
<td align="right">393,113,735</td>
<td align="right">0.3%</td>
<td align="right">88.5%</td>
<td align="right"></td>
</tr>
<tr>
<td align="left">JUMP_FORWARD</td>
<td align="right">356,692,419</td>
<td align="right">0.3%</td>
<td align="right">88.8%</td>
<td align="right"></td>
</tr>
<tr>
<td align="left">CALL_NON_PY_GENERAL</td>
<td align="right">355,367,769</td>
<td align="right">0.3%</td>
<td align="right">89.1%</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">POP_JUMP_IF_NOT_NONE</td>
<td align="right">352,506,862</td>
<td align="right">0.3%</td>
<td align="right">89.4%</td>
<td align="right"></td>
</tr>
<tr>
<td align="left">FOR_ITER</td>
<td align="right">346,843,975</td>
<td align="right">0.3%</td>
<td align="right">89.7%</td>
<td align="right"></td>
</tr>
<tr>
<td align="left">TO_BOOL_NONE</td>
<td align="right">343,696,946</td>
<td align="right">0.3%</td>
<td align="right">90.0%</td>
<td align="right">7.3%</td>
</tr>
<tr>
<td align="left">CALL_TYPE_1</td>
<td align="right">331,257,561</td>
<td align="right">0.3%</td>
<td align="right">90.3%</td>
<td align="right"></td>
</tr>
<tr>
<td align="left">LOAD_ATTR_MODULE</td>
<td align="right">326,916,945</td>
<td align="right">0.3%</td>
<td align="right">90.5%</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">EXTENDED_ARG</td>
<td align="right">306,282,698</td>
<td align="right">0.3%</td>
<td align="right">90.8%</td>
<td align="right"></td>
</tr>
<tr>
<td align="left">CONTAINS_OP_SET</td>
<td align="right">302,330,097</td>
<td align="right">0.3%</td>
<td align="right">91.1%</td>
<td align="right">0.2%</td>
</tr>
<tr>
<td align="left">STORE_SUBSCR</td>
<td align="right">300,610,948</td>
<td align="right">0.3%</td>
<td align="right">91.3%</td>
<td align="right"></td>
</tr>
<tr>
<td align="left">BINARY_OP_SUBTRACT_FLOAT</td>
<td align="right">282,026,572</td>
<td align="right">0.2%</td>
<td align="right">91.6%</td>
<td align="right">5.4%</td>
</tr>
<tr>
<td align="left">CALL_LEN</td>
<td align="right">274,120,704</td>
<td align="right">0.2%</td>
<td align="right">91.8%</td>
<td align="right"></td>
</tr>
<tr>
<td align="left">STORE_SUBSCR_LIST_INT</td>
<td align="right">270,387,910</td>
<td align="right">0.2%</td>
<td align="right">92.0%</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">CALL_PY_GENERAL</td>
<td align="right">270,114,854</td>
<td align="right">0.2%</td>
<td align="right">92.3%</td>
<td align="right">1.8%</td>
</tr>
<tr>
<td align="left">FOR_ITER_TUPLE</td>
<td align="right">268,342,262</td>
<td align="right">0.2%</td>
<td align="right">92.5%</td>
<td align="right">24.1%</td>
</tr>
<tr>
<td align="left">BINARY_OP_MULTIPLY_INT</td>
<td align="right">267,678,054</td>
<td align="right">0.2%</td>
<td align="right">92.7%</td>
<td align="right">3.2%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_WITH_HINT</td>
<td align="right">261,730,872</td>
<td align="right">0.2%</td>
<td align="right">93.0%</td>
<td align="right">0.5%</td>
</tr>
<tr>
<td align="left">CALL_METHOD_DESCRIPTOR_FAST</td>
<td align="right">247,623,113</td>
<td align="right">0.2%</td>
<td align="right">93.2%</td>
<td align="right">5.3%</td>
</tr>
<tr>
<td align="left">CALL_METHOD_DESCRIPTOR_NOARGS</td>
<td align="right">247,310,737</td>
<td align="right">0.2%</td>
<td align="right">93.4%</td>
<td align="right">8.8%</td>
</tr>
<tr>
<td align="left">BINARY_SUBSCR_DICT</td>
<td align="right">237,808,507</td>
<td align="right">0.2%</td>
<td align="right">93.6%</td>
<td align="right"></td>
</tr>
<tr>
<td align="left">CALL_METHOD_DESCRIPTOR_O</td>
<td align="right">233,886,599</td>
<td align="right">0.2%</td>
<td align="right">93.8%</td>
<td align="right">0.1%</td>
</tr>
<tr>
<td align="left">RETURN_GENERATOR</td>
<td align="right">230,565,832</td>
<td align="right">0.2%</td>
<td align="right">94.0%</td>
<td align="right"></td>
</tr>
<tr>
<td align="left">BUILD_LIST</td>
<td align="right">229,895,911</td>
<td align="right">0.2%</td>
<td align="right">94.2%</td>
<td align="right"></td>
</tr>
<tr>
<td align="left">BINARY_SUBSCR_TUPLE_INT</td>
<td align="right">228,520,347</td>
<td align="right">0.2%</td>
<td align="right">94.4%</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">POP_JUMP_IF_NONE</td>
<td align="right">228,222,743</td>
<td align="right">0.2%</td>
<td align="right">94.6%</td>
<td align="right"></td>
</tr>
<tr>
<td align="left">UNPACK_SEQUENCE_LIST</td>
<td align="right">227,311,720</td>
<td align="right">0.2%</td>
<td align="right">94.8%</td>
<td align="right">0.6%</td>
</tr>
<tr>
<td align="left">TO_BOOL_INT</td>
<td align="right">204,800,764</td>
<td align="right">0.2%</td>
<td align="right">95.0%</td>
<td align="right">0.4%</td>
</tr>
<tr>
<td align="left">END_SEND</td>
<td align="right">204,674,000</td>
<td align="right">0.2%</td>
<td align="right">95.1%</td>
<td align="right"></td>
</tr>
<tr>
<td align="left">CONTAINS_OP_DICT</td>
<td align="right">202,227,364</td>
<td align="right">0.2%</td>
<td align="right">95.3%</td>
<td align="right">0.3%</td>
</tr>
<tr>
<td align="left">TO_BOOL</td>
<td align="right">195,934,034</td>
<td align="right">0.2%</td>
<td align="right">95.5%</td>
<td align="right"></td>
</tr>
<tr>
<td align="left">COMPARE_OP_STR</td>
<td align="right">192,723,084</td>
<td align="right">0.2%</td>
<td align="right">95.6%</td>
<td align="right">0.2%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_METHOD_LAZY_DICT</td>
<td align="right">177,215,948</td>
<td align="right">0.2%</td>
<td align="right">95.8%</td>
<td align="right">2.1%</td>
</tr>
<tr>
<td align="left">CALL_LIST_APPEND</td>
<td align="right">176,135,045</td>
<td align="right">0.2%</td>
<td align="right">95.9%</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">COPY_FREE_VARS</td>
<td align="right">174,369,044</td>
<td align="right">0.2%</td>
<td align="right">96.1%</td>
<td align="right"></td>
</tr>
<tr>
<td align="left">STORE_SUBSCR_DICT</td>
<td align="right">174,153,662</td>
<td align="right">0.2%</td>
<td align="right">96.2%</td>
<td align="right"></td>
</tr>
<tr>
<td align="left">CONTAINS_OP</td>
<td align="right">172,165,802</td>
<td align="right">0.1%</td>
<td align="right">96.4%</td>
<td align="right"></td>
</tr>
<tr>
<td align="left">LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES</td>
<td align="right">165,577,265</td>
<td align="right">0.1%</td>
<td align="right">96.5%</td>
<td align="right">24.5%</td>
</tr>
<tr>
<td align="left">FOR_ITER_GEN</td>
<td align="right">143,396,152</td>
<td align="right">0.1%</td>
<td align="right">96.7%</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">COMPARE_OP</td>
<td align="right">142,594,527</td>
<td align="right">0.1%</td>
<td align="right">96.8%</td>
<td align="right"></td>
</tr>
<tr>
<td align="left">CALL_INTRINSIC_1</td>
<td align="right">140,671,847</td>
<td align="right">0.1%</td>
<td align="right">96.9%</td>
<td align="right"></td>
</tr>
<tr>
<td align="left">BINARY_SLICE</td>
<td align="right">133,105,581</td>
<td align="right">0.1%</td>
<td align="right">97.0%</td>
<td align="right"></td>
</tr>
<tr>
<td align="left">STORE_SLICE</td>
<td align="right">117,634,680</td>
<td align="right">0.1%</td>
<td align="right">97.1%</td>
<td align="right"></td>
</tr>
<tr>
<td align="left">COMPARE_OP_FLOAT</td>
<td align="right">117,197,491</td>
<td align="right">0.1%</td>
<td align="right">97.2%</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">CALL_BOUND_METHOD_EXACT_ARGS</td>
<td align="right">114,364,375</td>
<td align="right">0.1%</td>
<td align="right">97.3%</td>
<td align="right">7.5%</td>
</tr>
<tr>
<td align="left">TO_BOOL_ALWAYS_TRUE</td>
<td align="right">114,240,057</td>
<td align="right">0.1%</td>
<td align="right">97.4%</td>
<td align="right">21.2%</td>
</tr>
<tr>
<td align="left">SEND</td>
<td align="right">111,602,640</td>
<td align="right">0.1%</td>
<td align="right">97.5%</td>
<td align="right"></td>
</tr>
<tr>
<td align="left">FORMAT_SIMPLE</td>
<td align="right">109,714,440</td>
<td align="right">0.1%</td>
<td align="right">97.6%</td>
<td align="right"></td>
</tr>
<tr>
<td align="left">BINARY_SUBSCR_GETITEM</td>
<td align="right">108,148,170</td>
<td align="right">0.1%</td>
<td align="right">97.7%</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">BUILD_SLICE</td>
<td align="right">105,903,300</td>
<td align="right">0.1%</td>
<td align="right">97.8%</td>
<td align="right"></td>
</tr>
<tr>
<td align="left">CONVERT_VALUE</td>
<td align="right">105,666,300</td>
<td align="right">0.1%</td>
<td align="right">97.9%</td>
<td align="right"></td>
</tr>
<tr>
<td align="left">CALL_BUILTIN_CLASS</td>
<td align="right">103,365,427</td>
<td align="right">0.1%</td>
<td align="right">98.0%</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">CALL_BUILTIN_FAST_WITH_KEYWORDS</td>
<td align="right">100,244,503</td>
<td align="right">0.1%</td>
<td align="right">98.1%</td>
<td align="right"></td>
</tr>
<tr>
<td align="left">GET_ANEXT</td>
<td align="right">100,136,760</td>
<td align="right">0.1%</td>
<td align="right">98.1%</td>
<td align="right"></td>
</tr>
<tr>
<td align="left">CALL_KW</td>
<td align="right">96,355,148</td>
<td align="right">0.1%</td>
<td align="right">98.2%</td>
<td align="right"></td>
</tr>
<tr>
<td align="left">LIST_APPEND</td>
<td align="right">94,406,021</td>
<td align="right">0.1%</td>
<td align="right">98.3%</td>
<td align="right"></td>
</tr>
<tr>
<td align="left">LOAD_ATTR_CLASS</td>
<td align="right">91,836,250</td>
<td align="right">0.1%</td>
<td align="right">98.4%</td>
<td align="right">0.8%</td>
</tr>
<tr>
<td align="left">CALL_FUNCTION_EX</td>
<td align="right">87,307,205</td>
<td align="right">0.1%</td>
<td align="right">98.5%</td>
<td align="right"></td>
</tr>
<tr>
<td align="left">TO_BOOL_LIST</td>
<td align="right">85,511,996</td>
<td align="right">0.1%</td>
<td align="right">98.5%</td>
<td align="right">1.3%</td>
</tr>
<tr>
<td align="left">GET_AWAITABLE</td>
<td align="right">83,096,840</td>
<td align="right">0.1%</td>
<td align="right">98.6%</td>
<td align="right"></td>
</tr>
<tr>
<td align="left">DELETE_SUBSCR</td>
<td align="right">74,045,957</td>
<td align="right">0.1%</td>
<td align="right">98.7%</td>
<td align="right"></td>
</tr>
<tr>
<td align="left">MAKE_FUNCTION</td>
<td align="right">73,814,675</td>
<td align="right">0.1%</td>
<td align="right">98.7%</td>
<td align="right"></td>
</tr>
<tr>
<td align="left">CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS</td>
<td align="right">73,222,021</td>
<td align="right">0.1%</td>
<td align="right">98.8%</td>
<td align="right">2.4%</td>
</tr>
<tr>
<td align="left">BUILD_MAP</td>
<td align="right">68,780,201</td>
<td align="right">0.1%</td>
<td align="right">98.9%</td>
<td align="right"></td>
</tr>
<tr>
<td align="left">SET_FUNCTION_ATTRIBUTE</td>
<td align="right">66,986,907</td>
<td align="right">0.1%</td>
<td align="right">98.9%</td>
<td align="right"></td>
</tr>
<tr>
<td align="left">LOAD_ATTR_NONDESCRIPTOR_NO_DICT</td>
<td align="right">64,093,421</td>
<td align="right">0.1%</td>
<td align="right">99.0%</td>
<td align="right">19.7%</td>
</tr>
<tr>
<td align="left">STORE_FAST_LOAD_FAST</td>
<td align="right">63,425,059</td>
<td align="right">0.1%</td>
<td align="right">99.0%</td>
<td align="right"></td>
</tr>
<tr>
<td align="left">CALL_ALLOC_AND_ENTER_INIT</td>
<td align="right">58,973,454</td>
<td align="right">0.1%</td>
<td align="right">99.1%</td>
<td align="right">2.9%</td>
</tr>
<tr>
<td align="left">TO_BOOL_STR</td>
<td align="right">58,323,834</td>
<td align="right">0.1%</td>
<td align="right">99.1%</td>
<td align="right">4.1%</td>
</tr>
<tr>
<td align="left">RESUME</td>
<td align="right">58,275,813</td>
<td align="right">0.1%</td>
<td align="right">99.2%</td>
<td align="right">0.2%</td>
</tr>
<tr>
<td align="left">EXIT_INIT_CHECK</td>
<td align="right">57,267,754</td>
<td align="right">0.0%</td>
<td align="right">99.2%</td>
<td align="right"></td>
</tr>
<tr>
<td align="left">BUILD_STRING</td>
<td align="right">55,233,180</td>
<td align="right">0.0%</td>
<td align="right">99.3%</td>
<td align="right"></td>
</tr>
<tr>
<td align="left">BINARY_OP_ADD_UNICODE</td>
<td align="right">54,361,480</td>
<td align="right">0.0%</td>
<td align="right">99.3%</td>
<td align="right"></td>
</tr>
<tr>
<td align="left">STORE_DEREF</td>
<td align="right">48,904,059</td>
<td align="right">0.0%</td>
<td align="right">99.4%</td>
<td align="right"></td>
</tr>
<tr>
<td align="left">STORE_ATTR</td>
<td align="right">48,766,071</td>
<td align="right">0.0%</td>
<td align="right">99.4%</td>
<td align="right"></td>
</tr>
<tr>
<td align="left">LIST_EXTEND</td>
<td align="right">47,472,395</td>
<td align="right">0.0%</td>
<td align="right">99.5%</td>
<td align="right"></td>
</tr>
<tr>
<td align="left">CALL_STR_1</td>
<td align="right">44,886,597</td>
<td align="right">0.0%</td>
<td align="right">99.5%</td>
<td align="right"></td>
</tr>
<tr>
<td align="left">LOAD_ATTR_PROPERTY</td>
<td align="right">44,153,239</td>
<td align="right">0.0%</td>
<td align="right">99.5%</td>
<td align="right">16.1%</td>
</tr>
<tr>
<td align="left">LOAD_SUPER_ATTR_METHOD</td>
<td align="right">43,540,781</td>
<td align="right">0.0%</td>
<td align="right">99.6%</td>
<td align="right"></td>
</tr>
<tr>
<td align="left">BINARY_SUBSCR_STR_INT</td>
<td align="right">40,752,600</td>
<td align="right">0.0%</td>
<td align="right">99.6%</td>
<td align="right">0.4%</td>
</tr>
<tr>
<td align="left">STORE_ATTR_WITH_HINT</td>
<td align="right">40,116,164</td>
<td align="right">0.0%</td>
<td align="right">99.6%</td>
<td align="right">0.1%</td>
</tr>
<tr>
<td align="left">END_FOR</td>
<td align="right">37,964,583</td>
<td align="right">0.0%</td>
<td align="right">99.7%</td>
<td align="right"></td>
</tr>
<tr>
<td align="left">LOAD_FAST_AND_CLEAR</td>
<td align="right">35,388,286</td>
<td align="right">0.0%</td>
<td align="right">99.7%</td>
<td align="right"></td>
</tr>
<tr>
<td align="left">CALL</td>
<td align="right">33,491,186</td>
<td align="right">0.0%</td>
<td align="right">99.7%</td>
<td align="right"></td>
</tr>
<tr>
<td align="left">UNARY_NEGATIVE</td>
<td align="right">29,540,730</td>
<td align="right">0.0%</td>
<td align="right">99.8%</td>
<td align="right"></td>
</tr>
<tr>
<td align="left">GET_YIELD_FROM_ITER</td>
<td align="right">27,465,648</td>
<td align="right">0.0%</td>
<td align="right">99.8%</td>
<td align="right"></td>
</tr>
<tr>
<td align="left">UNARY_NOT</td>
<td align="right">26,551,549</td>
<td align="right">0.0%</td>
<td align="right">99.8%</td>
<td align="right"></td>
</tr>
<tr>
<td align="left">DICT_MERGE</td>
<td align="right">25,189,669</td>
<td align="right">0.0%</td>
<td align="right">99.8%</td>
<td align="right"></td>
</tr>
<tr>
<td align="left">MAKE_CELL</td>
<td align="right">24,076,336</td>
<td align="right">0.0%</td>
<td align="right">99.8%</td>
<td align="right"></td>
</tr>
<tr>
<td align="left">MAP_ADD</td>
<td align="right">14,621,786</td>
<td align="right">0.0%</td>
<td align="right">99.9%</td>
<td align="right"></td>
</tr>
<tr>
<td align="left">INSTRUMENTED_RESUME</td>
<td align="right">14,567,820</td>
<td align="right">0.0%</td>
<td align="right">99.9%</td>
<td align="right"></td>
</tr>
<tr>
<td align="left">INSTRUMENTED_RETURN_VALUE</td>
<td align="right">14,567,220</td>
<td align="right">0.0%</td>
<td align="right">99.9%</td>
<td align="right"></td>
</tr>
<tr>
<td align="left">PUSH_EXC_INFO</td>
<td align="right">11,969,897</td>
<td align="right">0.0%</td>
<td align="right">99.9%</td>
<td align="right"></td>
</tr>
<tr>
<td align="left">POP_EXCEPT</td>
<td align="right">11,969,880</td>
<td align="right">0.0%</td>
<td align="right">99.9%</td>
<td align="right"></td>
</tr>
<tr>
<td align="left">CHECK_EXC_MATCH</td>
<td align="right">11,602,443</td>
<td align="right">0.0%</td>
<td align="right">99.9%</td>
<td align="right"></td>
</tr>
<tr>
<td align="left">CALL_TUPLE_1</td>
<td align="right">10,827,693</td>
<td align="right">0.0%</td>
<td align="right">99.9%</td>
<td align="right"></td>
</tr>
<tr>
<td align="left">UNARY_INVERT</td>
<td align="right">10,395,065</td>
<td align="right">0.0%</td>
<td align="right">99.9%</td>
<td align="right"></td>
</tr>
<tr>
<td align="left">LOAD_NAME</td>
<td align="right">9,003,000</td>
<td align="right">0.0%</td>
<td align="right">99.9%</td>
<td align="right"></td>
</tr>
<tr>
<td align="left">CALL_BOUND_METHOD_GENERAL</td>
<td align="right">8,855,225</td>
<td align="right">0.0%</td>
<td align="right">99.9%</td>
<td align="right">16.0%</td>
</tr>
<tr>
<td align="left">LOAD_GLOBAL</td>
<td align="right">7,328,345</td>
<td align="right">0.0%</td>
<td align="right">100.0%</td>
<td align="right"></td>
</tr>
<tr>
<td align="left">BUILD_CONST_KEY_MAP</td>
<td align="right">7,138,166</td>
<td align="right">0.0%</td>
<td align="right">100.0%</td>
<td align="right"></td>
</tr>
<tr>
<td align="left">BEFORE_WITH</td>
<td align="right">6,463,551</td>
<td align="right">0.0%</td>
<td align="right">100.0%</td>
<td align="right"></td>
</tr>
<tr>
<td align="left">IMPORT_FROM</td>
<td align="right">6,173,911</td>
<td align="right">0.0%</td>
<td align="right">100.0%</td>
<td align="right"></td>
</tr>
<tr>
<td align="left">STORE_GLOBAL</td>
<td align="right">6,151,680</td>
<td align="right">0.0%</td>
<td align="right">100.0%</td>
<td align="right"></td>
</tr>
<tr>
<td align="left">END_ASYNC_FOR</td>
<td align="right">6,000,000</td>
<td align="right">0.0%</td>
<td align="right">100.0%</td>
<td align="right"></td>
</tr>
<tr>
<td align="left">GET_AITER</td>
<td align="right">6,000,000</td>
<td align="right">0.0%</td>
<td align="right">100.0%</td>
<td align="right"></td>
</tr>
<tr>
<td align="left">IMPORT_NAME</td>
<td align="right">5,694,437</td>
<td align="right">0.0%</td>
<td align="right">100.0%</td>
<td align="right"></td>
</tr>
<tr>
<td align="left">LOAD_FAST_CHECK</td>
<td align="right">3,326,909</td>
<td align="right">0.0%</td>
<td align="right">100.0%</td>
<td align="right"></td>
</tr>
<tr>
<td align="left">BINARY_OP_INPLACE_ADD_UNICODE</td>
<td align="right">2,236,600</td>
<td align="right">0.0%</td>
<td align="right">100.0%</td>
<td align="right"></td>
</tr>
<tr>
<td align="left">RERAISE</td>
<td align="right">1,484,821</td>
<td align="right">0.0%</td>
<td align="right">100.0%</td>
<td align="right"></td>
</tr>
<tr>
<td align="left">RAISE_VARARGS</td>
<td align="right">1,333,284</td>
<td align="right">0.0%</td>
<td align="right">100.0%</td>
<td align="right"></td>
</tr>
<tr>
<td align="left">DELETE_FAST</td>
<td align="right">1,190,907</td>
<td align="right">0.0%</td>
<td align="right">100.0%</td>
<td align="right"></td>
</tr>
<tr>
<td align="left">LOAD_SUPER_ATTR_ATTR</td>
<td align="right">1,093,698</td>
<td align="right">0.0%</td>
<td align="right">100.0%</td>
<td align="right"></td>
</tr>
<tr>
<td align="left">UNPACK_EX</td>
<td align="right">500,280</td>
<td align="right">0.0%</td>
<td align="right">100.0%</td>
<td align="right"></td>
</tr>
<tr>
<td align="left">UNPACK_SEQUENCE</td>
<td align="right">114,488</td>
<td align="right">0.0%</td>
<td align="right">100.0%</td>
<td align="right"></td>
</tr>
<tr>
<td align="left">BUILD_SET</td>
<td align="right">88,989</td>
<td align="right">0.0%</td>
<td align="right">100.0%</td>
<td align="right"></td>
</tr>
<tr>
<td align="left">DELETE_ATTR</td>
<td align="right">83,220</td>
<td align="right">0.0%</td>
<td align="right">100.0%</td>
<td align="right"></td>
</tr>
<tr>
<td align="left">SET_ADD</td>
<td align="right">26,940</td>
<td align="right">0.0%</td>
<td align="right">100.0%</td>
<td align="right"></td>
</tr>
<tr>
<td align="left">DICT_UPDATE</td>
<td align="right">13,140</td>
<td align="right">0.0%</td>
<td align="right">100.0%</td>
<td align="right"></td>
</tr>
<tr>
<td align="left">STORE_NAME</td>
<td align="right">9,900</td>
<td align="right">0.0%</td>
<td align="right">100.0%</td>
<td align="right"></td>
</tr>
<tr>
<td align="left">WITH_EXCEPT_START</td>
<td align="right">4,800</td>
<td align="right">0.0%</td>
<td align="right">100.0%</td>
<td align="right"></td>
</tr>
<tr>
<td align="left">LOAD_LOCALS</td>
<td align="right">1,380</td>
<td align="right">0.0%</td>
<td align="right">100.0%</td>
<td align="right"></td>
</tr>
<tr>
<td align="left">LOAD_FROM_DICT_OR_DEREF</td>
<td align="right">1,380</td>
<td align="right">0.0%</td>
<td align="right">100.0%</td>
<td align="right"></td>
</tr>
<tr>
<td align="left">LOAD_BUILD_CLASS</td>
<td align="right">1,320</td>
<td align="right">0.0%</td>
<td align="right">100.0%</td>
<td align="right"></td>
</tr>
<tr>
<td align="left">LOAD_SUPER_ATTR</td>
<td align="right">860</td>
<td align="right">0.0%</td>
<td align="right">100.0%</td>
<td align="right"></td>
</tr>
<tr>
<td align="left">CLEANUP_THROW</td>
<td align="right">480</td>
<td align="right">0.0%</td>
<td align="right">100.0%</td>
<td align="right"></td>
</tr>
<tr>
<td align="left">INSTRUMENTED_RETURN_CONST</td>
<td align="right">180</td>
<td align="right">0.0%</td>
<td align="right">100.0%</td>
<td align="right"></td>
</tr>
<tr>
<td align="left">SET_UPDATE</td>
<td align="right">120</td>
<td align="right">0.0%</td>
<td align="right">100.0%</td>
<td align="right"></td>
</tr>
<tr>
<td align="left">INSTRUMENTED_JUMP_BACKWARD</td>
<td align="right">60</td>
<td align="right">0.0%</td>
<td align="right">100.0%</td>
<td align="right"></td>
</tr>
</tbody>
</table>


</details>

## Pair counts

<details>
<summary> Pair counts for top 100 opcode pairs </summary>


Pairs of specialized operations that deoptimize and are then followed by
the corresponding unspecialized instruction are not counted as pairs.

<table>
<thead>
<tr>
<th align="left">Pair</th>
<th align="right">Count</th>
<th align="right">Self</th>
<th align="right">Cumulative</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">STORE_FAST LOAD_FAST</td>
<td align="right">3,478,601,698</td>
<td align="right">3.0%</td>
<td align="right">3.0%</td>
</tr>
<tr>
<td align="left">LOAD_FAST LOAD_ATTR_INSTANCE_VALUE</td>
<td align="right">3,216,101,202</td>
<td align="right">2.8%</td>
<td align="right">5.8%</td>
</tr>
<tr>
<td align="left">POP_JUMP_IF_FALSE LOAD_FAST</td>
<td align="right">2,762,695,211</td>
<td align="right">2.4%</td>
<td align="right">8.2%</td>
</tr>
<tr>
<td align="left">LOAD_GLOBAL_BUILTIN LOAD_FAST</td>
<td align="right">2,265,411,514</td>
<td align="right">2.0%</td>
<td align="right">10.1%</td>
</tr>
<tr>
<td align="left">LOAD_FAST LOAD_CONST</td>
<td align="right">2,226,268,451</td>
<td align="right">1.9%</td>
<td align="right">12.0%</td>
</tr>
<tr>
<td align="left">TO_BOOL_BOOL POP_JUMP_IF_FALSE</td>
<td align="right">2,061,270,943</td>
<td align="right">1.8%</td>
<td align="right">13.8%</td>
</tr>
<tr>
<td align="left">CALL_PY_EXACT_ARGS RESUME_CHECK</td>
<td align="right">1,948,094,871</td>
<td align="right">1.7%</td>
<td align="right">15.5%</td>
</tr>
<tr>
<td align="left">RESUME_CHECK LOAD_FAST</td>
<td align="right">1,806,183,265</td>
<td align="right">1.6%</td>
<td align="right">17.1%</td>
</tr>
<tr>
<td align="left">STORE_FAST_STORE_FAST STORE_FAST_STORE_FAST</td>
<td align="right">1,603,189,202</td>
<td align="right">1.4%</td>
<td align="right">18.4%</td>
</tr>
<tr>
<td align="left">LOAD_FAST LOAD_ATTR_METHOD_WITH_VALUES</td>
<td align="right">1,539,020,905</td>
<td align="right">1.3%</td>
<td align="right">19.8%</td>
</tr>
<tr>
<td align="left">COMPARE_OP_INT POP_JUMP_IF_FALSE</td>
<td align="right">1,118,944,465</td>
<td align="right">1.0%</td>
<td align="right">20.7%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_INSTANCE_VALUE LOAD_FAST</td>
<td align="right">1,052,827,067</td>
<td align="right">0.9%</td>
<td align="right">21.6%</td>
</tr>
<tr>
<td align="left">CACHE RESUME_CHECK</td>
<td align="right">999,657,217</td>
<td align="right">0.9%</td>
<td align="right">22.5%</td>
</tr>
<tr>
<td align="left">LOAD_FAST LOAD_ATTR_SLOT</td>
<td align="right">935,069,227</td>
<td align="right">0.8%</td>
<td align="right">23.3%</td>
</tr>
<tr>
<td align="left">STORE_FAST LOAD_FAST_LOAD_FAST</td>
<td align="right">926,099,743</td>
<td align="right">0.8%</td>
<td align="right">24.1%</td>
</tr>
<tr>
<td align="left">LOAD_FAST LOAD_GLOBAL_BUILTIN</td>
<td align="right">891,306,946</td>
<td align="right">0.8%</td>
<td align="right">24.9%</td>
</tr>
<tr>
<td align="left">JUMP_BACKWARD FOR_ITER_LIST</td>
<td align="right">829,644,464</td>
<td align="right">0.7%</td>
<td align="right">25.6%</td>
</tr>
<tr>
<td align="left">POP_TOP LOAD_FAST</td>
<td align="right">819,587,077</td>
<td align="right">0.7%</td>
<td align="right">26.3%</td>
</tr>
<tr>
<td align="left">POP_JUMP_IF_FALSE LOAD_GLOBAL_BUILTIN</td>
<td align="right">804,789,313</td>
<td align="right">0.7%</td>
<td align="right">27.0%</td>
</tr>
<tr>
<td align="left">LOAD_CONST BINARY_OP_ADD_INT</td>
<td align="right">804,349,772</td>
<td align="right">0.7%</td>
<td align="right">27.7%</td>
</tr>
<tr>
<td align="left">LOAD_CONST LOAD_FAST</td>
<td align="right">778,526,102</td>
<td align="right">0.7%</td>
<td align="right">28.4%</td>
</tr>
<tr>
<td align="left">POP_TOP JUMP_BACKWARD</td>
<td align="right">747,539,312</td>
<td align="right">0.6%</td>
<td align="right">29.0%</td>
</tr>
<tr>
<td align="left">LOAD_FAST CALL_PY_EXACT_ARGS</td>
<td align="right">736,250,840</td>
<td align="right">0.6%</td>
<td align="right">29.6%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_METHOD_WITH_VALUES LOAD_FAST</td>
<td align="right">721,114,180</td>
<td align="right">0.6%</td>
<td align="right">30.3%</td>
</tr>
<tr>
<td align="left">RESUME_CHECK LOAD_GLOBAL_BUILTIN</td>
<td align="right">711,437,670</td>
<td align="right">0.6%</td>
<td align="right">30.9%</td>
</tr>
<tr>
<td align="left">STORE_FAST STORE_FAST</td>
<td align="right">711,356,581</td>
<td align="right">0.6%</td>
<td align="right">31.5%</td>
</tr>
<tr>
<td align="left">LOAD_FAST LOAD_GLOBAL_MODULE</td>
<td align="right">696,099,725</td>
<td align="right">0.6%</td>
<td align="right">32.1%</td>
</tr>
<tr>
<td align="left">LOAD_CONST LOAD_CONST</td>
<td align="right">691,063,233</td>
<td align="right">0.6%</td>
<td align="right">32.7%</td>
</tr>
<tr>
<td align="left">LOAD_FAST TO_BOOL_BOOL</td>
<td align="right">647,340,855</td>
<td align="right">0.6%</td>
<td align="right">33.3%</td>
</tr>
<tr>
<td align="left">TO_BOOL_BOOL POP_JUMP_IF_TRUE</td>
<td align="right">636,796,062</td>
<td align="right">0.5%</td>
<td align="right">33.8%</td>
</tr>
<tr>
<td align="left">LOAD_FAST PUSH_NULL</td>
<td align="right">616,884,139</td>
<td align="right">0.5%</td>
<td align="right">34.3%</td>
</tr>
<tr>
<td align="left">STORE_FAST_STORE_FAST LOAD_FAST</td>
<td align="right">612,979,446</td>
<td align="right">0.5%</td>
<td align="right">34.9%</td>
</tr>
<tr>
<td align="left">LOAD_FAST CALL_BUILTIN_O</td>
<td align="right">575,632,517</td>
<td align="right">0.5%</td>
<td align="right">35.4%</td>
</tr>
<tr>
<td align="left">RESUME_CHECK POP_TOP</td>
<td align="right">562,987,632</td>
<td align="right">0.5%</td>
<td align="right">35.8%</td>
</tr>
<tr>
<td align="left">LOAD_FAST BINARY_OP_MULTIPLY_FLOAT</td>
<td align="right">560,637,880</td>
<td align="right">0.5%</td>
<td align="right">36.3%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_INSTANCE_VALUE TO_BOOL_BOOL</td>
<td align="right">554,867,282</td>
<td align="right">0.5%</td>
<td align="right">36.8%</td>
</tr>
<tr>
<td align="left">LOAD_FAST RETURN_VALUE</td>
<td align="right">546,471,415</td>
<td align="right">0.5%</td>
<td align="right">37.3%</td>
</tr>
<tr>
<td align="left">LOAD_CONST COMPARE_OP_INT</td>
<td align="right">544,496,145</td>
<td align="right">0.5%</td>
<td align="right">37.8%</td>
</tr>
<tr>
<td align="left">FOR_ITER_LIST STORE_FAST</td>
<td align="right">544,064,954</td>
<td align="right">0.5%</td>
<td align="right">38.2%</td>
</tr>
<tr>
<td align="left">LOAD_FAST_LOAD_FAST LOAD_FAST</td>
<td align="right">529,854,396</td>
<td align="right">0.5%</td>
<td align="right">38.7%</td>
</tr>
<tr>
<td align="left">LOAD_FAST LOAD_ATTR_METHOD_NO_DICT</td>
<td align="right">522,572,937</td>
<td align="right">0.5%</td>
<td align="right">39.1%</td>
</tr>
<tr>
<td align="left">LOAD_FAST LOAD_ATTR</td>
<td align="right">520,872,836</td>
<td align="right">0.4%</td>
<td align="right">39.6%</td>
</tr>
<tr>
<td align="left">PUSH_NULL LOAD_FAST</td>
<td align="right">517,063,875</td>
<td align="right">0.4%</td>
<td align="right">40.0%</td>
</tr>
<tr>
<td align="left">LOAD_FAST_LOAD_FAST CALL_PY_EXACT_ARGS</td>
<td align="right">510,383,502</td>
<td align="right">0.4%</td>
<td align="right">40.5%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_METHOD_NO_DICT LOAD_FAST</td>
<td align="right">496,448,974</td>
<td align="right">0.4%</td>
<td align="right">40.9%</td>
</tr>
<tr>
<td align="left">BINARY_SUBSCR LOAD_FAST</td>
<td align="right">492,966,749</td>
<td align="right">0.4%</td>
<td align="right">41.3%</td>
</tr>
<tr>
<td align="left">CALL_BUILTIN_FAST TO_BOOL_BOOL</td>
<td align="right">486,880,685</td>
<td align="right">0.4%</td>
<td align="right">41.7%</td>
</tr>
<tr>
<td align="left">STORE_FAST LOAD_GLOBAL_BUILTIN</td>
<td align="right">472,311,722</td>
<td align="right">0.4%</td>
<td align="right">42.1%</td>
</tr>
<tr>
<td align="left">RETURN_CONST POP_TOP</td>
<td align="right">471,159,197</td>
<td align="right">0.4%</td>
<td align="right">42.6%</td>
</tr>
<tr>
<td align="left">YIELD_VALUE INTERPRETER_EXIT</td>
<td align="right">468,395,685</td>
<td align="right">0.4%</td>
<td align="right">43.0%</td>
</tr>
<tr>
<td align="left">POP_JUMP_IF_TRUE LOAD_FAST</td>
<td align="right">454,164,709</td>
<td align="right">0.4%</td>
<td align="right">43.4%</td>
</tr>
<tr>
<td align="left">LOAD_FAST_LOAD_FAST LOAD_FAST_LOAD_FAST</td>
<td align="right">452,668,596</td>
<td align="right">0.4%</td>
<td align="right">43.7%</td>
</tr>
<tr>
<td align="left">IS_OP POP_JUMP_IF_FALSE</td>
<td align="right">448,130,871</td>
<td align="right">0.4%</td>
<td align="right">44.1%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_METHOD_WITH_VALUES LOAD_FAST_LOAD_FAST</td>
<td align="right">446,212,081</td>
<td align="right">0.4%</td>
<td align="right">44.5%</td>
</tr>
<tr>
<td align="left">CALL_ISINSTANCE TO_BOOL_BOOL</td>
<td align="right">440,159,402</td>
<td align="right">0.4%</td>
<td align="right">44.9%</td>
</tr>
<tr>
<td align="left">POP_JUMP_IF_TRUE JUMP_BACKWARD</td>
<td align="right">436,536,876</td>
<td align="right">0.4%</td>
<td align="right">45.3%</td>
</tr>
<tr>
<td align="left">LOAD_GLOBAL_BUILTIN CALL_BUILTIN_FAST</td>
<td align="right">434,497,240</td>
<td align="right">0.4%</td>
<td align="right">45.6%</td>
</tr>
<tr>
<td align="left">LOAD_DEREF LOAD_FAST</td>
<td align="right">431,645,993</td>
<td align="right">0.4%</td>
<td align="right">46.0%</td>
</tr>
<tr>
<td align="left">LOAD_GLOBAL_MODULE LOAD_FAST</td>
<td align="right">419,478,423</td>
<td align="right">0.4%</td>
<td align="right">46.4%</td>
</tr>
<tr>
<td align="left">RETURN_VALUE RETURN_VALUE</td>
<td align="right">417,508,356</td>
<td align="right">0.4%</td>
<td align="right">46.7%</td>
</tr>
<tr>
<td align="left">LOAD_FAST LOAD_FAST</td>
<td align="right">416,842,026</td>
<td align="right">0.4%</td>
<td align="right">47.1%</td>
</tr>
<tr>
<td align="left">JUMP_BACKWARD FOR_ITER_RANGE</td>
<td align="right">415,861,117</td>
<td align="right">0.4%</td>
<td align="right">47.5%</td>
</tr>
<tr>
<td align="left">RETURN_VALUE STORE_FAST</td>
<td align="right">400,819,618</td>
<td align="right">0.3%</td>
<td align="right">47.8%</td>
</tr>
<tr>
<td align="left">LOAD_CONST STORE_FAST</td>
<td align="right">396,107,800</td>
<td align="right">0.3%</td>
<td align="right">48.1%</td>
</tr>
<tr>
<td align="left">RESUME_CHECK JUMP_BACKWARD_NO_INTERRUPT</td>
<td align="right">388,886,240</td>
<td align="right">0.3%</td>
<td align="right">48.5%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_METHOD_WITH_VALUES CALL_PY_EXACT_ARGS</td>
<td align="right">388,761,137</td>
<td align="right">0.3%</td>
<td align="right">48.8%</td>
</tr>
<tr>
<td align="left">LOAD_FAST_LOAD_FAST LOAD_CONST</td>
<td align="right">386,899,839</td>
<td align="right">0.3%</td>
<td align="right">49.2%</td>
</tr>
<tr>
<td align="left">RETURN_VALUE INTERPRETER_EXIT</td>
<td align="right">386,773,253</td>
<td align="right">0.3%</td>
<td align="right">49.5%</td>
</tr>
<tr>
<td align="left">FOR_ITER_RANGE STORE_FAST</td>
<td align="right">386,713,789</td>
<td align="right">0.3%</td>
<td align="right">49.8%</td>
</tr>
<tr>
<td align="left">YIELD_VALUE YIELD_VALUE</td>
<td align="right">383,262,128</td>
<td align="right">0.3%</td>
<td align="right">50.2%</td>
</tr>
<tr>
<td align="left">JUMP_BACKWARD_NO_INTERRUPT SEND_GEN</td>
<td align="right">383,247,580</td>
<td align="right">0.3%</td>
<td align="right">50.5%</td>
</tr>
<tr>
<td align="left">SEND_GEN RESUME_CHECK</td>
<td align="right">383,241,200</td>
<td align="right">0.3%</td>
<td align="right">50.8%</td>
</tr>
<tr>
<td align="left">POP_JUMP_IF_FALSE LOAD_FAST_LOAD_FAST</td>
<td align="right">366,534,168</td>
<td align="right">0.3%</td>
<td align="right">51.1%</td>
</tr>
<tr>
<td align="left">LOAD_CONST BINARY_OP_SUBTRACT_INT</td>
<td align="right">360,967,114</td>
<td align="right">0.3%</td>
<td align="right">51.4%</td>
</tr>
<tr>
<td align="left">CALL_BUILTIN_O POP_TOP</td>
<td align="right">355,295,220</td>
<td align="right">0.3%</td>
<td align="right">51.7%</td>
</tr>
<tr>
<td align="left">RETURN_CONST INTERPRETER_EXIT</td>
<td align="right">350,733,168</td>
<td align="right">0.3%</td>
<td align="right">52.0%</td>
</tr>
<tr>
<td align="left">LOAD_FAST BINARY_SUBSCR</td>
<td align="right">348,647,859</td>
<td align="right">0.3%</td>
<td align="right">52.3%</td>
</tr>
<tr>
<td align="left">LOAD_CONST CALL_BUILTIN_FAST</td>
<td align="right">333,675,973</td>
<td align="right">0.3%</td>
<td align="right">52.6%</td>
</tr>
<tr>
<td align="left">BUILD_TUPLE RETURN_VALUE</td>
<td align="right">332,984,913</td>
<td align="right">0.3%</td>
<td align="right">52.9%</td>
</tr>
<tr>
<td align="left">UNPACK_SEQUENCE_TWO_TUPLE STORE_FAST_STORE_FAST</td>
<td align="right">329,513,940</td>
<td align="right">0.3%</td>
<td align="right">53.2%</td>
</tr>
<tr>
<td align="left">NOP LOAD_FAST</td>
<td align="right">327,642,363</td>
<td align="right">0.3%</td>
<td align="right">53.5%</td>
</tr>
<tr>
<td align="left">LOAD_FAST CALL_TYPE_1</td>
<td align="right">327,580,757</td>
<td align="right">0.3%</td>
<td align="right">53.8%</td>
</tr>
<tr>
<td align="left">STORE_ATTR_INSTANCE_VALUE LOAD_FAST</td>
<td align="right">322,762,067</td>
<td align="right">0.3%</td>
<td align="right">54.1%</td>
</tr>
<tr>
<td align="left">CALL_BUILTIN_FAST STORE_FAST</td>
<td align="right">322,314,124</td>
<td align="right">0.3%</td>
<td align="right">54.3%</td>
</tr>
<tr>
<td align="left">STORE_FAST LOAD_DEREF</td>
<td align="right">318,968,447</td>
<td align="right">0.3%</td>
<td align="right">54.6%</td>
</tr>
<tr>
<td align="left">LOAD_FAST_LOAD_FAST STORE_ATTR_INSTANCE_VALUE</td>
<td align="right">314,248,145</td>
<td align="right">0.3%</td>
<td align="right">54.9%</td>
</tr>
<tr>
<td align="left">TO_BOOL_NONE POP_JUMP_IF_FALSE</td>
<td align="right">313,878,458</td>
<td align="right">0.3%</td>
<td align="right">55.1%</td>
</tr>
<tr>
<td align="left">LOAD_GLOBAL_MODULE LOAD_ATTR_MODULE</td>
<td align="right">312,298,509</td>
<td align="right">0.3%</td>
<td align="right">55.4%</td>
</tr>
<tr>
<td align="left">POP_JUMP_IF_FALSE RETURN_CONST</td>
<td align="right">309,024,697</td>
<td align="right">0.3%</td>
<td align="right">55.7%</td>
</tr>
<tr>
<td align="left">LOAD_CONST BINARY_OP</td>
<td align="right">307,946,148</td>
<td align="right">0.3%</td>
<td align="right">56.0%</td>
</tr>
<tr>
<td align="left">BINARY_OP_MULTIPLY_FLOAT BINARY_OP_ADD_FLOAT</td>
<td align="right">301,743,300</td>
<td align="right">0.3%</td>
<td align="right">56.2%</td>
</tr>
<tr>
<td align="left">LOAD_FAST POP_JUMP_IF_NOT_NONE</td>
<td align="right">296,966,028</td>
<td align="right">0.3%</td>
<td align="right">56.5%</td>
</tr>
<tr>
<td align="left">LOAD_FAST_LOAD_FAST LOAD_ATTR_INSTANCE_VALUE</td>
<td align="right">296,748,789</td>
<td align="right">0.3%</td>
<td align="right">56.7%</td>
</tr>
<tr>
<td align="left">CONTAINS_OP_SET POP_JUMP_IF_FALSE</td>
<td align="right">294,730,837</td>
<td align="right">0.3%</td>
<td align="right">57.0%</td>
</tr>
<tr>
<td align="left">FOR_ITER_LIST UNPACK_SEQUENCE_TWO_TUPLE</td>
<td align="right">287,912,670</td>
<td align="right">0.2%</td>
<td align="right">57.2%</td>
</tr>
<tr>
<td align="left">PUSH_NULL LOAD_FAST_LOAD_FAST</td>
<td align="right">287,219,986</td>
<td align="right">0.2%</td>
<td align="right">57.5%</td>
</tr>
<tr>
<td align="left">LOAD_FAST_LOAD_FAST STORE_ATTR_SLOT</td>
<td align="right">285,584,104</td>
<td align="right">0.2%</td>
<td align="right">57.7%</td>
</tr>
<tr>
<td align="left">CALL_TYPE_1 STORE_FAST</td>
<td align="right">284,162,256</td>
<td align="right">0.2%</td>
<td align="right">58.0%</td>
</tr>
<tr>
<td align="left">BINARY_OP_ADD_INT STORE_FAST</td>
<td align="right">283,331,931</td>
<td align="right">0.2%</td>
<td align="right">58.2%</td>
</tr>
<tr>
<td align="left">LOAD_FAST STORE_ATTR_INSTANCE_VALUE</td>
<td align="right">278,768,917</td>
<td align="right">0.2%</td>
<td align="right">58.5%</td>
</tr>
</tbody>
</table>


</details>

## Predecessor/Successor Pairs

<details>
<summary> Top 5 predecessors and successors of each Tier 1 opcode. </summary>


This does not include the unspecialized instructions that occur after a
specialized instruction deoptimizes.

### BINARY_SLICE

<details>
<summary> Successors and predecessors for BINARY_SLICE </summary>

<table>
<thead>
<tr>
<th align="left">Predecessors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">LOAD_CONST</td>
<td align="right">65,987,821</td>
<td align="right">49.6%</td>
</tr>
<tr>
<td align="left">BINARY_OP_ADD_INT</td>
<td align="right">35,580,420</td>
<td align="right">26.7%</td>
</tr>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">25,780,400</td>
<td align="right">19.4%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_SLOT</td>
<td align="right">4,782,720</td>
<td align="right">3.6%</td>
</tr>
<tr>
<td align="left">CALL_METHOD_DESCRIPTOR_FAST</td>
<td align="right">544,920</td>
<td align="right">0.4%</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Successors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">CALL_PY_EXACT_ARGS</td>
<td align="right">25,443,000</td>
<td align="right">19.1%</td>
</tr>
<tr>
<td align="left">STORE_FAST</td>
<td align="right">24,280,400</td>
<td align="right">18.2%</td>
</tr>
<tr>
<td align="left">CALL_LIST_APPEND</td>
<td align="right">19,300,980</td>
<td align="right">14.5%</td>
</tr>
<tr>
<td align="left">BINARY_OP</td>
<td align="right">15,327,540</td>
<td align="right">11.5%</td>
</tr>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">10,969,600</td>
<td align="right">8.2%</td>
</tr>
</tbody>
</table>


</details>

### STORE_SLICE

<details>
<summary> Successors and predecessors for STORE_SLICE </summary>

<table>
<thead>
<tr>
<th align="left">Predecessors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">BINARY_OP_ADD_INT</td>
<td align="right">103,909,800</td>
<td align="right">88.3%</td>
</tr>
<tr>
<td align="left">LOAD_CONST</td>
<td align="right">13,458,480</td>
<td align="right">11.4%</td>
</tr>
<tr>
<td align="left">LOAD_FAST_LOAD_FAST</td>
<td align="right">258,360</td>
<td align="right">0.2%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_SLOT</td>
<td align="right">8,040</td>
<td align="right">0.0%</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Successors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">107,577,720</td>
<td align="right">91.5%</td>
</tr>
<tr>
<td align="left">RETURN_CONST</td>
<td align="right">5,855,760</td>
<td align="right">5.0%</td>
</tr>
<tr>
<td align="left">LOAD_FAST_LOAD_FAST</td>
<td align="right">4,157,040</td>
<td align="right">3.5%</td>
</tr>
<tr>
<td align="left">JUMP_BACKWARD</td>
<td align="right">40,380</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">LOAD_GLOBAL_BUILTIN</td>
<td align="right">2,700</td>
<td align="right">0.0%</td>
</tr>
</tbody>
</table>


</details>

### CACHE

<details>
<summary> Successors and predecessors for CACHE </summary>

<table>
<thead>
<tr>
<th align="left">Successors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">RESUME_CHECK</td>
<td align="right">999,657,217</td>
<td align="right">80.7%</td>
</tr>
<tr>
<td align="left">POP_TOP</td>
<td align="right">87,759,138</td>
<td align="right">7.1%</td>
</tr>
<tr>
<td align="left">COPY_FREE_VARS</td>
<td align="right">61,233,628</td>
<td align="right">4.9%</td>
</tr>
<tr>
<td align="left">RESUME</td>
<td align="right">58,273,022</td>
<td align="right">4.7%</td>
</tr>
<tr>
<td align="left">RETURN_GENERATOR</td>
<td align="right">30,371,700</td>
<td align="right">2.5%</td>
</tr>
</tbody>
</table>


</details>

### BINARY_SUBSCR

<details>
<summary> Successors and predecessors for BINARY_SUBSCR </summary>

<table>
<thead>
<tr>
<th align="left">Predecessors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">348,647,859</td>
<td align="right">33.7%</td>
</tr>
<tr>
<td align="left">LOAD_FAST_LOAD_FAST</td>
<td align="right">257,252,970</td>
<td align="right">24.9%</td>
</tr>
<tr>
<td align="left">COPY</td>
<td align="right">109,352,700</td>
<td align="right">10.6%</td>
</tr>
<tr>
<td align="left">BUILD_SLICE</td>
<td align="right">105,404,640</td>
<td align="right">10.2%</td>
</tr>
<tr>
<td align="left">BINARY_OP_ADD_INT</td>
<td align="right">102,644,000</td>
<td align="right">9.9%</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Successors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">492,966,749</td>
<td align="right">47.6%</td>
</tr>
<tr>
<td align="left">LOAD_FAST_LOAD_FAST</td>
<td align="right">122,125,380</td>
<td align="right">11.8%</td>
</tr>
<tr>
<td align="left">STORE_FAST</td>
<td align="right">88,251,620</td>
<td align="right">8.5%</td>
</tr>
<tr>
<td align="left">BINARY_OP_MULTIPLY_FLOAT</td>
<td align="right">67,701,000</td>
<td align="right">6.5%</td>
</tr>
<tr>
<td align="left">BINARY_SUBSCR</td>
<td align="right">48,260,332</td>
<td align="right">4.7%</td>
</tr>
</tbody>
</table>


</details>

### GET_ITER

<details>
<summary> Successors and predecessors for GET_ITER </summary>

<table>
<thead>
<tr>
<th align="left">Predecessors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">158,332,919</td>
<td align="right">35.6%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_INSTANCE_VALUE</td>
<td align="right">68,302,380</td>
<td align="right">15.3%</td>
</tr>
<tr>
<td align="left">RETURN_VALUE</td>
<td align="right">55,159,755</td>
<td align="right">12.4%</td>
</tr>
<tr>
<td align="left">CALL_METHOD_DESCRIPTOR_NOARGS</td>
<td align="right">43,266,601</td>
<td align="right">9.7%</td>
</tr>
<tr>
<td align="left">RETURN_GENERATOR</td>
<td align="right">37,574,400</td>
<td align="right">8.4%</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Successors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">FOR_ITER_LIST</td>
<td align="right">163,805,977</td>
<td align="right">36.8%</td>
</tr>
<tr>
<td align="left">FOR_ITER_TUPLE</td>
<td align="right">69,515,694</td>
<td align="right">15.6%</td>
</tr>
<tr>
<td align="left">CALL_PY_EXACT_ARGS</td>
<td align="right">66,895,472</td>
<td align="right">15.0%</td>
</tr>
<tr>
<td align="left">FOR_ITER</td>
<td align="right">54,720,102</td>
<td align="right">12.3%</td>
</tr>
<tr>
<td align="left">FOR_ITER_GEN</td>
<td align="right">37,634,066</td>
<td align="right">8.5%</td>
</tr>
</tbody>
</table>


</details>

### INTERPRETER_EXIT

<details>
<summary> Successors and predecessors for INTERPRETER_EXIT </summary>

<table>
<thead>
<tr>
<th align="left">Predecessors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">YIELD_VALUE</td>
<td align="right">468,395,685</td>
<td align="right">37.9%</td>
</tr>
<tr>
<td align="left">RETURN_VALUE</td>
<td align="right">386,773,253</td>
<td align="right">31.3%</td>
</tr>
<tr>
<td align="left">RETURN_CONST</td>
<td align="right">350,733,168</td>
<td align="right">28.4%</td>
</tr>
<tr>
<td align="left">RETURN_GENERATOR</td>
<td align="right">30,381,000</td>
<td align="right">2.5%</td>
</tr>
</tbody>
</table>


</details>

### MAKE_FUNCTION

<details>
<summary> Successors and predecessors for MAKE_FUNCTION </summary>

<table>
<thead>
<tr>
<th align="left">Predecessors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">LOAD_CONST</td>
<td align="right">73,814,675</td>
<td align="right">100.0%</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Successors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">SET_FUNCTION_ATTRIBUTE</td>
<td align="right">66,942,786</td>
<td align="right">90.7%</td>
</tr>
<tr>
<td align="left">LOAD_GLOBAL_MODULE</td>
<td align="right">2,498,700</td>
<td align="right">3.4%</td>
</tr>
<tr>
<td align="left">LOAD_GLOBAL_BUILTIN</td>
<td align="right">1,949,518</td>
<td align="right">2.6%</td>
</tr>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">1,560,941</td>
<td align="right">2.1%</td>
</tr>
<tr>
<td align="left">STORE_FAST</td>
<td align="right">513,156</td>
<td align="right">0.7%</td>
</tr>
</tbody>
</table>


</details>

### NOP

<details>
<summary> Successors and predecessors for NOP </summary>

<table>
<thead>
<tr>
<th align="left">Predecessors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">RESUME_CHECK</td>
<td align="right">167,730,114</td>
<td align="right">38.8%</td>
</tr>
<tr>
<td align="left">POP_JUMP_IF_FALSE</td>
<td align="right">93,221,066</td>
<td align="right">21.6%</td>
</tr>
<tr>
<td align="left">STORE_FAST</td>
<td align="right">57,643,833</td>
<td align="right">13.3%</td>
</tr>
<tr>
<td align="left">STORE_ATTR_INSTANCE_VALUE</td>
<td align="right">25,256,481</td>
<td align="right">5.8%</td>
</tr>
<tr>
<td align="left">POP_JUMP_IF_TRUE</td>
<td align="right">23,861,875</td>
<td align="right">5.5%</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Successors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">327,642,363</td>
<td align="right">75.8%</td>
</tr>
<tr>
<td align="left">LOAD_GLOBAL_BUILTIN</td>
<td align="right">29,106,556</td>
<td align="right">6.7%</td>
</tr>
<tr>
<td align="left">LOAD_GLOBAL_MODULE</td>
<td align="right">15,706,699</td>
<td align="right">3.6%</td>
</tr>
<tr>
<td align="left">LOAD_CONST</td>
<td align="right">15,616,412</td>
<td align="right">3.6%</td>
</tr>
<tr>
<td align="left">NOP</td>
<td align="right">15,130,520</td>
<td align="right">3.5%</td>
</tr>
</tbody>
</table>


</details>

### POP_TOP

<details>
<summary> Successors and predecessors for POP_TOP </summary>

<table>
<thead>
<tr>
<th align="left">Predecessors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">RESUME_CHECK</td>
<td align="right">562,987,632</td>
<td align="right">24.7%</td>
</tr>
<tr>
<td align="left">RETURN_CONST</td>
<td align="right">471,159,197</td>
<td align="right">20.7%</td>
</tr>
<tr>
<td align="left">CALL_BUILTIN_O</td>
<td align="right">355,295,220</td>
<td align="right">15.6%</td>
</tr>
<tr>
<td align="left">POP_JUMP_IF_FALSE</td>
<td align="right">132,849,033</td>
<td align="right">5.8%</td>
</tr>
<tr>
<td align="left">CALL_METHOD_DESCRIPTOR_O</td>
<td align="right">127,882,933</td>
<td align="right">5.6%</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Successors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">819,587,077</td>
<td align="right">36.0%</td>
</tr>
<tr>
<td align="left">JUMP_BACKWARD</td>
<td align="right">747,539,312</td>
<td align="right">32.8%</td>
</tr>
<tr>
<td align="left">RESUME_CHECK</td>
<td align="right">230,564,512</td>
<td align="right">10.1%</td>
</tr>
<tr>
<td align="left">RETURN_CONST</td>
<td align="right">153,973,770</td>
<td align="right">6.8%</td>
</tr>
<tr>
<td align="left">LOAD_FAST_LOAD_FAST</td>
<td align="right">81,403,727</td>
<td align="right">3.6%</td>
</tr>
</tbody>
</table>


</details>

### PUSH_NULL

<details>
<summary> Successors and predecessors for PUSH_NULL </summary>

<table>
<thead>
<tr>
<th align="left">Predecessors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">616,884,139</td>
<td align="right">57.5%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_MODULE</td>
<td align="right">261,559,477</td>
<td align="right">24.4%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR</td>
<td align="right">66,182,674</td>
<td align="right">6.2%</td>
</tr>
<tr>
<td align="left">LOAD_FAST_LOAD_FAST</td>
<td align="right">46,717,817</td>
<td align="right">4.4%</td>
</tr>
<tr>
<td align="left">LOAD_DEREF</td>
<td align="right">45,864,475</td>
<td align="right">4.3%</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Successors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">517,063,875</td>
<td align="right">48.2%</td>
</tr>
<tr>
<td align="left">LOAD_FAST_LOAD_FAST</td>
<td align="right">287,219,986</td>
<td align="right">26.8%</td>
</tr>
<tr>
<td align="left">LOAD_CONST</td>
<td align="right">141,777,514</td>
<td align="right">13.2%</td>
</tr>
<tr>
<td align="left">CALL_NON_PY_GENERAL</td>
<td align="right">50,695,024</td>
<td align="right">4.7%</td>
</tr>
<tr>
<td align="left">LOAD_GLOBAL_MODULE</td>
<td align="right">34,347,803</td>
<td align="right">3.2%</td>
</tr>
</tbody>
</table>


</details>

### RETURN_VALUE

<details>
<summary> Successors and predecessors for RETURN_VALUE </summary>

<table>
<thead>
<tr>
<th align="left">Predecessors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">546,471,415</td>
<td align="right">22.2%</td>
</tr>
<tr>
<td align="left">RETURN_VALUE</td>
<td align="right">417,508,356</td>
<td align="right">17.0%</td>
</tr>
<tr>
<td align="left">BUILD_TUPLE</td>
<td align="right">332,984,913</td>
<td align="right">13.5%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_INSTANCE_VALUE</td>
<td align="right">187,363,724</td>
<td align="right">7.6%</td>
</tr>
<tr>
<td align="left">BINARY_SUBSCR_DICT</td>
<td align="right">140,276,589</td>
<td align="right">5.7%</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Successors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">RETURN_VALUE</td>
<td align="right">417,508,356</td>
<td align="right">17.0%</td>
</tr>
<tr>
<td align="left">STORE_FAST</td>
<td align="right">400,819,618</td>
<td align="right">16.3%</td>
</tr>
<tr>
<td align="left">INTERPRETER_EXIT</td>
<td align="right">386,773,253</td>
<td align="right">15.7%</td>
</tr>
<tr>
<td align="left">UNPACK_SEQUENCE_TUPLE</td>
<td align="right">240,521,160</td>
<td align="right">9.8%</td>
</tr>
<tr>
<td align="left">TO_BOOL_BOOL</td>
<td align="right">234,731,401</td>
<td align="right">9.5%</td>
</tr>
</tbody>
</table>


</details>

### STORE_SUBSCR

<details>
<summary> Successors and predecessors for STORE_SUBSCR </summary>

<table>
<thead>
<tr>
<th align="left">Predecessors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">SWAP</td>
<td align="right">109,360,580</td>
<td align="right">36.4%</td>
</tr>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">78,840,948</td>
<td align="right">26.2%</td>
</tr>
<tr>
<td align="left">LOAD_FAST_LOAD_FAST</td>
<td align="right">54,484,700</td>
<td align="right">18.1%</td>
</tr>
<tr>
<td align="left">BINARY_OP_ADD_INT</td>
<td align="right">41,532,300</td>
<td align="right">13.8%</td>
</tr>
<tr>
<td align="left">BUILD_TUPLE</td>
<td align="right">6,375,840</td>
<td align="right">2.1%</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Successors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">JUMP_BACKWARD</td>
<td align="right">109,811,820</td>
<td align="right">36.5%</td>
</tr>
<tr>
<td align="left">LOAD_FAST_LOAD_FAST</td>
<td align="right">104,112,780</td>
<td align="right">34.6%</td>
</tr>
<tr>
<td align="left">LOAD_GLOBAL_BUILTIN</td>
<td align="right">27,003,100</td>
<td align="right">9.0%</td>
</tr>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">25,331,260</td>
<td align="right">8.4%</td>
</tr>
<tr>
<td align="left">LOAD_DEREF</td>
<td align="right">15,741,060</td>
<td align="right">5.2%</td>
</tr>
</tbody>
</table>


</details>

### TO_BOOL

<details>
<summary> Successors and predecessors for TO_BOOL </summary>

<table>
<thead>
<tr>
<th align="left">Predecessors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">140,320,588</td>
<td align="right">71.6%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_INSTANCE_VALUE</td>
<td align="right">44,256,535</td>
<td align="right">22.6%</td>
</tr>
<tr>
<td align="left">CALL_BUILTIN_FAST</td>
<td align="right">7,714,960</td>
<td align="right">3.9%</td>
</tr>
<tr>
<td align="left">BINARY_SUBSCR_TUPLE_INT</td>
<td align="right">1,320,120</td>
<td align="right">0.7%</td>
</tr>
<tr>
<td align="left">COPY</td>
<td align="right">1,061,720</td>
<td align="right">0.5%</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Successors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">POP_JUMP_IF_TRUE</td>
<td align="right">114,102,003</td>
<td align="right">58.2%</td>
</tr>
<tr>
<td align="left">POP_JUMP_IF_FALSE</td>
<td align="right">81,462,158</td>
<td align="right">41.6%</td>
</tr>
<tr>
<td align="left">TO_BOOL</td>
<td align="right">206,069</td>
<td align="right">0.1%</td>
</tr>
<tr>
<td align="left">UNARY_NOT</td>
<td align="right">61,586</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">TO_BOOL_NONE</td>
<td align="right">57,726</td>
<td align="right">0.0%</td>
</tr>
</tbody>
</table>


</details>

### BINARY_OP

<details>
<summary> Successors and predecessors for BINARY_OP </summary>

<table>
<thead>
<tr>
<th align="left">Predecessors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">LOAD_CONST</td>
<td align="right">307,946,148</td>
<td align="right">31.9%</td>
</tr>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">170,198,674</td>
<td align="right">17.7%</td>
</tr>
<tr>
<td align="left">CALL_METHOD_DESCRIPTOR_O</td>
<td align="right">72,001,440</td>
<td align="right">7.5%</td>
</tr>
<tr>
<td align="left">LOAD_FAST_LOAD_FAST</td>
<td align="right">66,385,884</td>
<td align="right">6.9%</td>
</tr>
<tr>
<td align="left">BINARY_SUBSCR_LIST_INT</td>
<td align="right">65,379,191</td>
<td align="right">6.8%</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Successors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">STORE_FAST</td>
<td align="right">173,355,991</td>
<td align="right">18.0%</td>
</tr>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">167,635,780</td>
<td align="right">17.4%</td>
</tr>
<tr>
<td align="left">LOAD_FAST_LOAD_FAST</td>
<td align="right">120,315,500</td>
<td align="right">12.5%</td>
</tr>
<tr>
<td align="left">BINARY_SUBSCR_LIST_INT</td>
<td align="right">96,694,080</td>
<td align="right">10.0%</td>
</tr>
<tr>
<td align="left">LOAD_CONST</td>
<td align="right">93,802,469</td>
<td align="right">9.7%</td>
</tr>
</tbody>
</table>


</details>

### BUILD_LIST

<details>
<summary> Successors and predecessors for BUILD_LIST </summary>

<table>
<thead>
<tr>
<th align="left">Predecessors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">STORE_FAST</td>
<td align="right">104,033,203</td>
<td align="right">45.3%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_SLOT</td>
<td align="right">36,520,699</td>
<td align="right">15.9%</td>
</tr>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">23,435,366</td>
<td align="right">10.2%</td>
</tr>
<tr>
<td align="left">SWAP</td>
<td align="right">11,846,243</td>
<td align="right">5.2%</td>
</tr>
<tr>
<td align="left">LOAD_CONST</td>
<td align="right">11,189,640</td>
<td align="right">4.9%</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Successors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">STORE_FAST</td>
<td align="right">110,395,804</td>
<td align="right">48.0%</td>
</tr>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">74,550,847</td>
<td align="right">32.4%</td>
</tr>
<tr>
<td align="left">SWAP</td>
<td align="right">11,846,303</td>
<td align="right">5.2%</td>
</tr>
<tr>
<td align="left">RETURN_VALUE</td>
<td align="right">8,195,112</td>
<td align="right">3.6%</td>
</tr>
<tr>
<td align="left">CALL_METHOD_DESCRIPTOR_FAST</td>
<td align="right">8,086,320</td>
<td align="right">3.5%</td>
</tr>
</tbody>
</table>


</details>

### BUILD_MAP

<details>
<summary> Successors and predecessors for BUILD_MAP </summary>

<table>
<thead>
<tr>
<th align="left">Predecessors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">17,281,259</td>
<td align="right">25.1%</td>
</tr>
<tr>
<td align="left">BUILD_TUPLE</td>
<td align="right">12,202,571</td>
<td align="right">17.7%</td>
</tr>
<tr>
<td align="left">STORE_FAST</td>
<td align="right">8,730,060</td>
<td align="right">12.7%</td>
</tr>
<tr>
<td align="left">SWAP</td>
<td align="right">7,992,866</td>
<td align="right">11.6%</td>
</tr>
<tr>
<td align="left">RESUME_CHECK</td>
<td align="right">5,019,900</td>
<td align="right">7.3%</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Successors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">30,212,029</td>
<td align="right">43.9%</td>
</tr>
<tr>
<td align="left">STORE_FAST</td>
<td align="right">20,036,372</td>
<td align="right">29.1%</td>
</tr>
<tr>
<td align="left">SWAP</td>
<td align="right">7,992,866</td>
<td align="right">11.6%</td>
</tr>
<tr>
<td align="left">CALL_BUILTIN_FAST_WITH_KEYWORDS</td>
<td align="right">3,960,360</td>
<td align="right">5.8%</td>
</tr>
<tr>
<td align="left">CALL_FUNCTION_EX</td>
<td align="right">3,904,980</td>
<td align="right">5.7%</td>
</tr>
</tbody>
</table>


</details>

### BUILD_TUPLE

<details>
<summary> Successors and predecessors for BUILD_TUPLE </summary>

<table>
<thead>
<tr>
<th align="left">Predecessors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">177,632,843</td>
<td align="right">30.8%</td>
</tr>
<tr>
<td align="left">LOAD_CONST</td>
<td align="right">165,296,007</td>
<td align="right">28.6%</td>
</tr>
<tr>
<td align="left">LOAD_FAST_LOAD_FAST</td>
<td align="right">125,038,680</td>
<td align="right">21.7%</td>
</tr>
<tr>
<td align="left">CALL_NON_PY_GENERAL</td>
<td align="right">36,531,830</td>
<td align="right">6.3%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR</td>
<td align="right">16,453,917</td>
<td align="right">2.9%</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Successors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">RETURN_VALUE</td>
<td align="right">332,984,913</td>
<td align="right">57.7%</td>
</tr>
<tr>
<td align="left">LOAD_CONST</td>
<td align="right">67,168,873</td>
<td align="right">11.6%</td>
</tr>
<tr>
<td align="left">YIELD_VALUE</td>
<td align="right">31,496,880</td>
<td align="right">5.5%</td>
</tr>
<tr>
<td align="left">BINARY_SUBSCR_GETITEM</td>
<td align="right">28,812,000</td>
<td align="right">5.0%</td>
</tr>
<tr>
<td align="left">LIST_APPEND</td>
<td align="right">23,077,057</td>
<td align="right">4.0%</td>
</tr>
</tbody>
</table>


</details>

### CALL

<details>
<summary> Successors and predecessors for CALL </summary>

<table>
<thead>
<tr>
<th align="left">Predecessors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">LOAD_ATTR_INSTANCE_VALUE</td>
<td align="right">19,764,554</td>
<td align="right">59.0%</td>
</tr>
<tr>
<td align="left">LOAD_FAST_LOAD_FAST</td>
<td align="right">7,041,002</td>
<td align="right">21.0%</td>
</tr>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">2,169,983</td>
<td align="right">6.5%</td>
</tr>
<tr>
<td align="left">LOAD_GLOBAL_MODULE</td>
<td align="right">1,284,035</td>
<td align="right">3.8%</td>
</tr>
<tr>
<td align="left">LOAD_GLOBAL_BUILTIN</td>
<td align="right">1,197,720</td>
<td align="right">3.6%</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Successors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">CALL_METHOD_DESCRIPTOR_O</td>
<td align="right">19,489,737</td>
<td align="right">58.2%</td>
</tr>
<tr>
<td align="left">GET_ITER</td>
<td align="right">7,127,389</td>
<td align="right">21.3%</td>
</tr>
<tr>
<td align="left">STORE_FAST</td>
<td align="right">3,988,500</td>
<td align="right">11.9%</td>
</tr>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">1,269,491</td>
<td align="right">3.8%</td>
</tr>
<tr>
<td align="left">CALL_TUPLE_1</td>
<td align="right">484,980</td>
<td align="right">1.4%</td>
</tr>
</tbody>
</table>


</details>

### CALL_FUNCTION_EX

<details>
<summary> Successors and predecessors for CALL_FUNCTION_EX </summary>

<table>
<thead>
<tr>
<th align="left">Predecessors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">CALL_INTRINSIC_1</td>
<td align="right">41,060,393</td>
<td align="right">47.0%</td>
</tr>
<tr>
<td align="left">DICT_MERGE</td>
<td align="right">25,189,669</td>
<td align="right">28.9%</td>
</tr>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">14,606,307</td>
<td align="right">16.7%</td>
</tr>
<tr>
<td align="left">BUILD_MAP</td>
<td align="right">3,904,980</td>
<td align="right">4.5%</td>
</tr>
<tr>
<td align="left">STORE_FAST</td>
<td align="right">2,309,666</td>
<td align="right">2.6%</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Successors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">POP_TOP</td>
<td align="right">42,598,079</td>
<td align="right">48.8%</td>
</tr>
<tr>
<td align="left">STORE_FAST</td>
<td align="right">17,450,547</td>
<td align="right">20.0%</td>
</tr>
<tr>
<td align="left">RESUME_CHECK</td>
<td align="right">11,547,312</td>
<td align="right">13.2%</td>
</tr>
<tr>
<td align="left">LOAD_FAST_LOAD_FAST</td>
<td align="right">4,981,620</td>
<td align="right">5.7%</td>
</tr>
<tr>
<td align="left">MAKE_CELL</td>
<td align="right">4,668,977</td>
<td align="right">5.3%</td>
</tr>
</tbody>
</table>


</details>

### CALL_INTRINSIC_1

<details>
<summary> Successors and predecessors for CALL_INTRINSIC_1 </summary>

<table>
<thead>
<tr>
<th align="left">Predecessors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">88,136,760</td>
<td align="right">62.7%</td>
</tr>
<tr>
<td align="left">LIST_EXTEND</td>
<td align="right">46,514,087</td>
<td align="right">33.1%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_INSTANCE_VALUE</td>
<td align="right">6,000,000</td>
<td align="right">4.3%</td>
</tr>
<tr>
<td align="left">LIST_APPEND</td>
<td align="right">11,520</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">RERAISE</td>
<td align="right">9,000</td>
<td align="right">0.0%</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Successors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">YIELD_VALUE</td>
<td align="right">94,136,760</td>
<td align="right">66.9%</td>
</tr>
<tr>
<td align="left">CALL_FUNCTION_EX</td>
<td align="right">41,060,393</td>
<td align="right">29.2%</td>
</tr>
<tr>
<td align="left">LOAD_CONST</td>
<td align="right">3,370,440</td>
<td align="right">2.4%</td>
</tr>
<tr>
<td align="left">BUILD_MAP</td>
<td align="right">2,070,114</td>
<td align="right">1.5%</td>
</tr>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">20,760</td>
<td align="right">0.0%</td>
</tr>
</tbody>
</table>


</details>

### CALL_KW

<details>
<summary> Successors and predecessors for CALL_KW </summary>

<table>
<thead>
<tr>
<th align="left">Predecessors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">LOAD_CONST</td>
<td align="right">96,355,148</td>
<td align="right">100.0%</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Successors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">RESUME_CHECK</td>
<td align="right">41,922,978</td>
<td align="right">43.5%</td>
</tr>
<tr>
<td align="left">STORE_FAST</td>
<td align="right">32,272,447</td>
<td align="right">33.5%</td>
</tr>
<tr>
<td align="left">POP_TOP</td>
<td align="right">7,930,372</td>
<td align="right">8.2%</td>
</tr>
<tr>
<td align="left">RETURN_VALUE</td>
<td align="right">6,119,934</td>
<td align="right">6.4%</td>
</tr>
<tr>
<td align="left">COPY_FREE_VARS</td>
<td align="right">3,419,040</td>
<td align="right">3.5%</td>
</tr>
</tbody>
</table>


</details>

### COMPARE_OP

<details>
<summary> Successors and predecessors for COMPARE_OP </summary>

<table>
<thead>
<tr>
<th align="left">Predecessors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">LOAD_CONST</td>
<td align="right">51,005,273</td>
<td align="right">35.8%</td>
</tr>
<tr>
<td align="left">LOAD_FAST_LOAD_FAST</td>
<td align="right">46,732,768</td>
<td align="right">32.8%</td>
</tr>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">16,814,374</td>
<td align="right">11.8%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR</td>
<td align="right">8,859,610</td>
<td align="right">6.2%</td>
</tr>
<tr>
<td align="left">BINARY_SUBSCR_TUPLE_INT</td>
<td align="right">4,881,300</td>
<td align="right">3.4%</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Successors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">POP_JUMP_IF_FALSE</td>
<td align="right">88,053,548</td>
<td align="right">61.8%</td>
</tr>
<tr>
<td align="left">POP_JUMP_IF_TRUE</td>
<td align="right">41,467,715</td>
<td align="right">29.1%</td>
</tr>
<tr>
<td align="left">BINARY_OP</td>
<td align="right">4,684,940</td>
<td align="right">3.3%</td>
</tr>
<tr>
<td align="left">LOAD_FAST_LOAD_FAST</td>
<td align="right">4,684,940</td>
<td align="right">3.3%</td>
</tr>
<tr>
<td align="left">UNARY_NOT</td>
<td align="right">2,531,411</td>
<td align="right">1.8%</td>
</tr>
</tbody>
</table>


</details>

### CONTAINS_OP

<details>
<summary> Successors and predecessors for CONTAINS_OP </summary>

<table>
<thead>
<tr>
<th align="left">Predecessors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">75,214,680</td>
<td align="right">43.7%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_SLOT</td>
<td align="right">58,268,820</td>
<td align="right">33.8%</td>
</tr>
<tr>
<td align="left">LOAD_FAST_LOAD_FAST</td>
<td align="right">19,573,352</td>
<td align="right">11.4%</td>
</tr>
<tr>
<td align="left">LOAD_CONST</td>
<td align="right">7,483,457</td>
<td align="right">4.3%</td>
</tr>
<tr>
<td align="left">LOAD_GLOBAL_MODULE</td>
<td align="right">2,880,420</td>
<td align="right">1.7%</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Successors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">POP_JUMP_IF_FALSE</td>
<td align="right">153,995,629</td>
<td align="right">89.4%</td>
</tr>
<tr>
<td align="left">POP_JUMP_IF_TRUE</td>
<td align="right">14,854,560</td>
<td align="right">8.6%</td>
</tr>
<tr>
<td align="left">COPY</td>
<td align="right">2,826,900</td>
<td align="right">1.6%</td>
</tr>
<tr>
<td align="left">EXTENDED_ARG</td>
<td align="right">331,440</td>
<td align="right">0.2%</td>
</tr>
<tr>
<td align="left">RETURN_VALUE</td>
<td align="right">70,020</td>
<td align="right">0.0%</td>
</tr>
</tbody>
</table>


</details>

### COPY

<details>
<summary> Successors and predecessors for COPY </summary>

<table>
<thead>
<tr>
<th align="left">Predecessors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">COPY</td>
<td align="right">269,772,840</td>
<td align="right">28.2%</td>
</tr>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">222,834,185</td>
<td align="right">23.3%</td>
</tr>
<tr>
<td align="left">LOAD_FAST_LOAD_FAST</td>
<td align="right">121,554,000</td>
<td align="right">12.7%</td>
</tr>
<tr>
<td align="left">SWAP</td>
<td align="right">103,030,020</td>
<td align="right">10.8%</td>
</tr>
<tr>
<td align="left">LOAD_CONST</td>
<td align="right">95,950,223</td>
<td align="right">10.0%</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Successors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">COPY</td>
<td align="right">269,772,840</td>
<td align="right">28.2%</td>
</tr>
<tr>
<td align="left">BINARY_SUBSCR_LIST_INT</td>
<td align="right">159,175,780</td>
<td align="right">16.6%</td>
</tr>
<tr>
<td align="left">TO_BOOL_BOOL</td>
<td align="right">146,037,123</td>
<td align="right">15.3%</td>
</tr>
<tr>
<td align="left">BINARY_SUBSCR</td>
<td align="right">109,352,700</td>
<td align="right">11.4%</td>
</tr>
<tr>
<td align="left">COMPARE_OP_INT</td>
<td align="right">100,083,960</td>
<td align="right">10.5%</td>
</tr>
</tbody>
</table>


</details>

### COPY_FREE_VARS

<details>
<summary> Successors and predecessors for COPY_FREE_VARS </summary>

<table>
<thead>
<tr>
<th align="left">Predecessors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">CALL_PY_EXACT_ARGS</td>
<td align="right">68,970,510</td>
<td align="right">39.6%</td>
</tr>
<tr>
<td align="left">CACHE</td>
<td align="right">61,233,628</td>
<td align="right">35.1%</td>
</tr>
<tr>
<td align="left">CALL_BOUND_METHOD_EXACT_ARGS</td>
<td align="right">27,104,627</td>
<td align="right">15.5%</td>
</tr>
<tr>
<td align="left">CALL_PY_GENERAL</td>
<td align="right">8,342,424</td>
<td align="right">4.8%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_PROPERTY</td>
<td align="right">3,871,095</td>
<td align="right">2.2%</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Successors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">RESUME_CHECK</td>
<td align="right">113,367,281</td>
<td align="right">65.0%</td>
</tr>
<tr>
<td align="left">RETURN_GENERATOR</td>
<td align="right">60,925,203</td>
<td align="right">34.9%</td>
</tr>
<tr>
<td align="left">MAKE_CELL</td>
<td align="right">76,500</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">RESUME</td>
<td align="right">60</td>
<td align="right">0.0%</td>
</tr>
</tbody>
</table>


</details>

### DICT_MERGE

<details>
<summary> Successors and predecessors for DICT_MERGE </summary>

<table>
<thead>
<tr>
<th align="left">Predecessors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">24,769,382</td>
<td align="right">98.3%</td>
</tr>
<tr>
<td align="left">LOAD_DEREF</td>
<td align="right">172,650</td>
<td align="right">0.7%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_INSTANCE_VALUE</td>
<td align="right">154,937</td>
<td align="right">0.6%</td>
</tr>
<tr>
<td align="left">RETURN_VALUE</td>
<td align="right">50,880</td>
<td align="right">0.2%</td>
</tr>
<tr>
<td align="left">BUILD_CONST_KEY_MAP</td>
<td align="right">16,320</td>
<td align="right">0.1%</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Successors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">CALL_FUNCTION_EX</td>
<td align="right">25,189,669</td>
<td align="right">100.0%</td>
</tr>
</tbody>
</table>


</details>

### FOR_ITER

<details>
<summary> Successors and predecessors for FOR_ITER </summary>

<table>
<thead>
<tr>
<th align="left">Predecessors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">JUMP_BACKWARD</td>
<td align="right">255,012,693</td>
<td align="right">73.5%</td>
</tr>
<tr>
<td align="left">GET_ITER</td>
<td align="right">54,720,102</td>
<td align="right">15.8%</td>
</tr>
<tr>
<td align="left">EXTENDED_ARG</td>
<td align="right">17,546,138</td>
<td align="right">5.1%</td>
</tr>
<tr>
<td align="left">SWAP</td>
<td align="right">10,909,406</td>
<td align="right">3.1%</td>
</tr>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">8,518,184</td>
<td align="right">2.5%</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Successors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">UNPACK_SEQUENCE_TWO_TUPLE</td>
<td align="right">193,134,633</td>
<td align="right">55.7%</td>
</tr>
<tr>
<td align="left">STORE_FAST</td>
<td align="right">85,614,652</td>
<td align="right">24.7%</td>
</tr>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">26,140,133</td>
<td align="right">7.5%</td>
</tr>
<tr>
<td align="left">RETURN_CONST</td>
<td align="right">12,951,961</td>
<td align="right">3.7%</td>
</tr>
<tr>
<td align="left">SWAP</td>
<td align="right">10,524,206</td>
<td align="right">3.0%</td>
</tr>
</tbody>
</table>


</details>

### IMPORT_FROM

<details>
<summary> Successors and predecessors for IMPORT_FROM </summary>

<table>
<thead>
<tr>
<th align="left">Predecessors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">IMPORT_NAME</td>
<td align="right">5,398,217</td>
<td align="right">87.4%</td>
</tr>
<tr>
<td align="left">STORE_FAST</td>
<td align="right">639,507</td>
<td align="right">10.4%</td>
</tr>
<tr>
<td align="left">STORE_DEREF</td>
<td align="right">136,187</td>
<td align="right">2.2%</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Successors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">STORE_FAST</td>
<td align="right">4,617,377</td>
<td align="right">74.8%</td>
</tr>
<tr>
<td align="left">STORE_DEREF</td>
<td align="right">1,556,534</td>
<td align="right">25.2%</td>
</tr>
</tbody>
</table>


</details>

### IMPORT_NAME

<details>
<summary> Successors and predecessors for IMPORT_NAME </summary>

<table>
<thead>
<tr>
<th align="left">Predecessors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">LOAD_CONST</td>
<td align="right">5,694,437</td>
<td align="right">100.0%</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Successors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">IMPORT_FROM</td>
<td align="right">5,398,217</td>
<td align="right">94.8%</td>
</tr>
<tr>
<td align="left">STORE_FAST</td>
<td align="right">296,220</td>
<td align="right">5.2%</td>
</tr>
</tbody>
</table>


</details>

### JUMP_BACKWARD

<details>
<summary> Successors and predecessors for JUMP_BACKWARD </summary>

<table>
<thead>
<tr>
<th align="left">Predecessors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">POP_TOP</td>
<td align="right">747,539,312</td>
<td align="right">34.4%</td>
</tr>
<tr>
<td align="left">POP_JUMP_IF_TRUE</td>
<td align="right">436,536,876</td>
<td align="right">20.1%</td>
</tr>
<tr>
<td align="left">POP_JUMP_IF_FALSE</td>
<td align="right">208,817,589</td>
<td align="right">9.6%</td>
</tr>
<tr>
<td align="left">STORE_FAST</td>
<td align="right">180,826,781</td>
<td align="right">8.3%</td>
</tr>
<tr>
<td align="left">STORE_SUBSCR</td>
<td align="right">109,811,820</td>
<td align="right">5.1%</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Successors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">FOR_ITER_LIST</td>
<td align="right">829,644,464</td>
<td align="right">38.2%</td>
</tr>
<tr>
<td align="left">FOR_ITER_RANGE</td>
<td align="right">415,861,117</td>
<td align="right">19.1%</td>
</tr>
<tr>
<td align="left">FOR_ITER</td>
<td align="right">255,012,693</td>
<td align="right">11.7%</td>
</tr>
<tr>
<td align="left">FOR_ITER_TUPLE</td>
<td align="right">193,692,691</td>
<td align="right">8.9%</td>
</tr>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">128,689,128</td>
<td align="right">5.9%</td>
</tr>
</tbody>
</table>


</details>

### JUMP_FORWARD

<details>
<summary> Successors and predecessors for JUMP_FORWARD </summary>

<table>
<thead>
<tr>
<th align="left">Predecessors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">STORE_FAST</td>
<td align="right">123,693,702</td>
<td align="right">34.7%</td>
</tr>
<tr>
<td align="left">POP_JUMP_IF_FALSE</td>
<td align="right">119,076,711</td>
<td align="right">33.4%</td>
</tr>
<tr>
<td align="left">POP_TOP</td>
<td align="right">55,695,274</td>
<td align="right">15.6%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_SLOT</td>
<td align="right">11,995,080</td>
<td align="right">3.4%</td>
</tr>
<tr>
<td align="left">STORE_ATTR_INSTANCE_VALUE</td>
<td align="right">8,968,200</td>
<td align="right">2.5%</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Successors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">141,932,200</td>
<td align="right">39.8%</td>
</tr>
<tr>
<td align="left">LOAD_FAST_LOAD_FAST</td>
<td align="right">78,079,383</td>
<td align="right">21.9%</td>
</tr>
<tr>
<td align="left">LOAD_CONST</td>
<td align="right">38,631,210</td>
<td align="right">10.8%</td>
</tr>
<tr>
<td align="left">LOAD_GLOBAL_BUILTIN</td>
<td align="right">27,880,500</td>
<td align="right">7.8%</td>
</tr>
<tr>
<td align="left">JUMP_BACKWARD</td>
<td align="right">24,968,520</td>
<td align="right">7.0%</td>
</tr>
</tbody>
</table>


</details>

### LIST_EXTEND

<details>
<summary> Successors and predecessors for LIST_EXTEND </summary>

<table>
<thead>
<tr>
<th align="left">Predecessors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">LOAD_ATTR_SLOT</td>
<td align="right">35,834,359</td>
<td align="right">75.5%</td>
</tr>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">10,689,592</td>
<td align="right">22.5%</td>
</tr>
<tr>
<td align="left">LOAD_CONST</td>
<td align="right">712,020</td>
<td align="right">1.5%</td>
</tr>
<tr>
<td align="left">RETURN_VALUE</td>
<td align="right">124,764</td>
<td align="right">0.3%</td>
</tr>
<tr>
<td align="left">LOAD_DEREF</td>
<td align="right">77,460</td>
<td align="right">0.2%</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Successors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">CALL_INTRINSIC_1</td>
<td align="right">46,514,087</td>
<td align="right">98.0%</td>
</tr>
<tr>
<td align="left">STORE_FAST</td>
<td align="right">457,824</td>
<td align="right">1.0%</td>
</tr>
<tr>
<td align="left">UNPACK_SEQUENCE_LIST</td>
<td align="right">345,120</td>
<td align="right">0.7%</td>
</tr>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">150,744</td>
<td align="right">0.3%</td>
</tr>
<tr>
<td align="left">BUILD_TUPLE</td>
<td align="right">2,940</td>
<td align="right">0.0%</td>
</tr>
</tbody>
</table>


</details>

### LOAD_ATTR

<details>
<summary> Successors and predecessors for LOAD_ATTR </summary>

<table>
<thead>
<tr>
<th align="left">Predecessors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">520,872,836</td>
<td align="right">50.2%</td>
</tr>
<tr>
<td align="left">LOAD_GLOBAL_BUILTIN</td>
<td align="right">220,580,892</td>
<td align="right">21.3%</td>
</tr>
<tr>
<td align="left">LOAD_GLOBAL_MODULE</td>
<td align="right">101,494,357</td>
<td align="right">9.8%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_SLOT</td>
<td align="right">83,426,225</td>
<td align="right">8.0%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR</td>
<td align="right">38,735,854</td>
<td align="right">3.7%</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Successors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">IS_OP</td>
<td align="right">228,852,189</td>
<td align="right">22.1%</td>
</tr>
<tr>
<td align="left">STORE_FAST</td>
<td align="right">227,152,408</td>
<td align="right">21.9%</td>
</tr>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">101,777,069</td>
<td align="right">9.8%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_SLOT</td>
<td align="right">80,213,757</td>
<td align="right">7.7%</td>
</tr>
<tr>
<td align="left">PUSH_NULL</td>
<td align="right">66,182,674</td>
<td align="right">6.4%</td>
</tr>
</tbody>
</table>


</details>

### LOAD_CONST

<details>
<summary> Successors and predecessors for LOAD_CONST </summary>

<table>
<thead>
<tr>
<th align="left">Predecessors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">2,226,268,451</td>
<td align="right">35.4%</td>
</tr>
<tr>
<td align="left">LOAD_CONST</td>
<td align="right">691,063,233</td>
<td align="right">11.0%</td>
</tr>
<tr>
<td align="left">LOAD_FAST_LOAD_FAST</td>
<td align="right">386,899,839</td>
<td align="right">6.2%</td>
</tr>
<tr>
<td align="left">POP_JUMP_IF_FALSE</td>
<td align="right">260,563,261</td>
<td align="right">4.1%</td>
</tr>
<tr>
<td align="left">STORE_FAST</td>
<td align="right">254,565,178</td>
<td align="right">4.0%</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Successors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">BINARY_OP_ADD_INT</td>
<td align="right">804,349,772</td>
<td align="right">12.8%</td>
</tr>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">778,526,102</td>
<td align="right">12.4%</td>
</tr>
<tr>
<td align="left">LOAD_CONST</td>
<td align="right">691,063,233</td>
<td align="right">11.0%</td>
</tr>
<tr>
<td align="left">COMPARE_OP_INT</td>
<td align="right">544,496,145</td>
<td align="right">8.7%</td>
</tr>
<tr>
<td align="left">STORE_FAST</td>
<td align="right">396,107,800</td>
<td align="right">6.3%</td>
</tr>
</tbody>
</table>


</details>

### LOAD_DEREF

<details>
<summary> Successors and predecessors for LOAD_DEREF </summary>

<table>
<thead>
<tr>
<th align="left">Predecessors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">STORE_FAST</td>
<td align="right">318,968,447</td>
<td align="right">47.2%</td>
</tr>
<tr>
<td align="left">POP_JUMP_IF_FALSE</td>
<td align="right">53,605,470</td>
<td align="right">7.9%</td>
</tr>
<tr>
<td align="left">CALL_BUILTIN_FAST_WITH_KEYWORDS</td>
<td align="right">46,765,320</td>
<td align="right">6.9%</td>
</tr>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">30,055,761</td>
<td align="right">4.4%</td>
</tr>
<tr>
<td align="left">POP_JUMP_IF_NONE</td>
<td align="right">27,877,560</td>
<td align="right">4.1%</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Successors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">431,645,993</td>
<td align="right">63.9%</td>
</tr>
<tr>
<td align="left">PUSH_NULL</td>
<td align="right">45,864,475</td>
<td align="right">6.8%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR</td>
<td align="right">35,313,906</td>
<td align="right">5.2%</td>
</tr>
<tr>
<td align="left">LOAD_CONST</td>
<td align="right">31,481,352</td>
<td align="right">4.7%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_METHOD_NO_DICT</td>
<td align="right">17,411,286</td>
<td align="right">2.6%</td>
</tr>
</tbody>
</table>


</details>

### LOAD_FAST

<details>
<summary> Successors and predecessors for LOAD_FAST </summary>

<table>
<thead>
<tr>
<th align="left">Predecessors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">STORE_FAST</td>
<td align="right">3,478,601,698</td>
<td align="right">15.9%</td>
</tr>
<tr>
<td align="left">POP_JUMP_IF_FALSE</td>
<td align="right">2,762,695,211</td>
<td align="right">12.6%</td>
</tr>
<tr>
<td align="left">LOAD_GLOBAL_BUILTIN</td>
<td align="right">2,265,411,514</td>
<td align="right">10.3%</td>
</tr>
<tr>
<td align="left">RESUME_CHECK</td>
<td align="right">1,806,183,265</td>
<td align="right">8.2%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_INSTANCE_VALUE</td>
<td align="right">1,052,827,067</td>
<td align="right">4.8%</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Successors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">LOAD_ATTR_INSTANCE_VALUE</td>
<td align="right">3,216,101,202</td>
<td align="right">14.7%</td>
</tr>
<tr>
<td align="left">LOAD_CONST</td>
<td align="right">2,226,268,451</td>
<td align="right">10.2%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_METHOD_WITH_VALUES</td>
<td align="right">1,539,020,905</td>
<td align="right">7.0%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_SLOT</td>
<td align="right">935,069,227</td>
<td align="right">4.3%</td>
</tr>
<tr>
<td align="left">LOAD_GLOBAL_BUILTIN</td>
<td align="right">891,306,946</td>
<td align="right">4.1%</td>
</tr>
</tbody>
</table>


</details>

### LOAD_FAST_LOAD_FAST

<details>
<summary> Successors and predecessors for LOAD_FAST_LOAD_FAST </summary>

<table>
<thead>
<tr>
<th align="left">Predecessors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">STORE_FAST</td>
<td align="right">926,099,743</td>
<td align="right">18.1%</td>
</tr>
<tr>
<td align="left">LOAD_FAST_LOAD_FAST</td>
<td align="right">452,668,596</td>
<td align="right">8.9%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_METHOD_WITH_VALUES</td>
<td align="right">446,212,081</td>
<td align="right">8.7%</td>
</tr>
<tr>
<td align="left">POP_JUMP_IF_FALSE</td>
<td align="right">366,534,168</td>
<td align="right">7.2%</td>
</tr>
<tr>
<td align="left">PUSH_NULL</td>
<td align="right">287,219,986</td>
<td align="right">5.6%</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Successors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">529,854,396</td>
<td align="right">10.4%</td>
</tr>
<tr>
<td align="left">CALL_PY_EXACT_ARGS</td>
<td align="right">510,383,502</td>
<td align="right">10.0%</td>
</tr>
<tr>
<td align="left">LOAD_FAST_LOAD_FAST</td>
<td align="right">452,668,596</td>
<td align="right">8.9%</td>
</tr>
<tr>
<td align="left">LOAD_CONST</td>
<td align="right">386,899,839</td>
<td align="right">7.6%</td>
</tr>
<tr>
<td align="left">STORE_ATTR_INSTANCE_VALUE</td>
<td align="right">314,248,145</td>
<td align="right">6.2%</td>
</tr>
</tbody>
</table>


</details>

### LOAD_GLOBAL

<details>
<summary> Successors and predecessors for LOAD_GLOBAL </summary>

<table>
<thead>
<tr>
<th align="left">Predecessors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">POP_JUMP_IF_FALSE</td>
<td align="right">7,288,332</td>
<td align="right">99.5%</td>
</tr>
<tr>
<td align="left">STORE_FAST</td>
<td align="right">7,400</td>
<td align="right">0.1%</td>
</tr>
<tr>
<td align="left">RESUME_CHECK</td>
<td align="right">6,348</td>
<td align="right">0.1%</td>
</tr>
<tr>
<td align="left">RETURN_VALUE</td>
<td align="right">3,540</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">3,306</td>
<td align="right">0.0%</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Successors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">7,283,962</td>
<td align="right">99.4%</td>
</tr>
<tr>
<td align="left">LOAD_GLOBAL_MODULE</td>
<td align="right">29,532</td>
<td align="right">0.4%</td>
</tr>
<tr>
<td align="left">LOAD_GLOBAL_BUILTIN</td>
<td align="right">12,365</td>
<td align="right">0.2%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR</td>
<td align="right">1,699</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_MODULE</td>
<td align="right">300</td>
<td align="right">0.0%</td>
</tr>
</tbody>
</table>


</details>

### LOAD_SUPER_ATTR

<details>
<summary> Successors and predecessors for LOAD_SUPER_ATTR </summary>

<table>
<thead>
<tr>
<th align="left">Predecessors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">860</td>
<td align="right">100.0%</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Successors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">LOAD_SUPER_ATTR_METHOD</td>
<td align="right">840</td>
<td align="right">97.7%</td>
</tr>
<tr>
<td align="left">LOAD_SUPER_ATTR_ATTR</td>
<td align="right">20</td>
<td align="right">2.3%</td>
</tr>
</tbody>
</table>


</details>

### MAKE_CELL

<details>
<summary> Successors and predecessors for MAKE_CELL </summary>

<table>
<thead>
<tr>
<th align="left">Predecessors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">MAKE_CELL</td>
<td align="right">13,979,337</td>
<td align="right">58.1%</td>
</tr>
<tr>
<td align="left">CALL_FUNCTION_EX</td>
<td align="right">4,668,977</td>
<td align="right">19.4%</td>
</tr>
<tr>
<td align="left">CALL_PY_EXACT_ARGS</td>
<td align="right">2,444,138</td>
<td align="right">10.2%</td>
</tr>
<tr>
<td align="left">CACHE</td>
<td align="right">1,126,998</td>
<td align="right">4.7%</td>
</tr>
<tr>
<td align="left">CALL_PY_GENERAL</td>
<td align="right">956,619</td>
<td align="right">4.0%</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Successors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">MAKE_CELL</td>
<td align="right">13,979,337</td>
<td align="right">58.1%</td>
</tr>
<tr>
<td align="left">RESUME_CHECK</td>
<td align="right">9,518,179</td>
<td align="right">39.5%</td>
</tr>
<tr>
<td align="left">RETURN_GENERATOR</td>
<td align="right">578,820</td>
<td align="right">2.4%</td>
</tr>
</tbody>
</table>


</details>

### POP_JUMP_IF_FALSE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_FALSE </summary>

<table>
<thead>
<tr>
<th align="left">Predecessors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">TO_BOOL_BOOL</td>
<td align="right">2,061,270,943</td>
<td align="right">38.5%</td>
</tr>
<tr>
<td align="left">COMPARE_OP_INT</td>
<td align="right">1,118,944,465</td>
<td align="right">20.9%</td>
</tr>
<tr>
<td align="left">IS_OP</td>
<td align="right">448,130,871</td>
<td align="right">8.4%</td>
</tr>
<tr>
<td align="left">TO_BOOL_NONE</td>
<td align="right">313,878,458</td>
<td align="right">5.9%</td>
</tr>
<tr>
<td align="left">CONTAINS_OP_SET</td>
<td align="right">294,730,837</td>
<td align="right">5.5%</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Successors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">2,762,695,211</td>
<td align="right">51.6%</td>
</tr>
<tr>
<td align="left">LOAD_GLOBAL_BUILTIN</td>
<td align="right">804,789,313</td>
<td align="right">15.0%</td>
</tr>
<tr>
<td align="left">LOAD_FAST_LOAD_FAST</td>
<td align="right">366,534,168</td>
<td align="right">6.8%</td>
</tr>
<tr>
<td align="left">RETURN_CONST</td>
<td align="right">309,024,697</td>
<td align="right">5.8%</td>
</tr>
<tr>
<td align="left">LOAD_CONST</td>
<td align="right">260,563,261</td>
<td align="right">4.9%</td>
</tr>
</tbody>
</table>


</details>

### POP_JUMP_IF_NONE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_NONE </summary>

<table>
<thead>
<tr>
<th align="left">Predecessors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">152,900,647</td>
<td align="right">67.0%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_INSTANCE_VALUE</td>
<td align="right">36,791,453</td>
<td align="right">16.1%</td>
</tr>
<tr>
<td align="left">LOAD_GLOBAL_MODULE</td>
<td align="right">16,497,120</td>
<td align="right">7.2%</td>
</tr>
<tr>
<td align="left">LOAD_DEREF</td>
<td align="right">15,308,880</td>
<td align="right">6.7%</td>
</tr>
<tr>
<td align="left">BINARY_SUBSCR</td>
<td align="right">5,118,372</td>
<td align="right">2.2%</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Successors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">149,565,203</td>
<td align="right">65.5%</td>
</tr>
<tr>
<td align="left">LOAD_DEREF</td>
<td align="right">27,877,560</td>
<td align="right">12.2%</td>
</tr>
<tr>
<td align="left">JUMP_BACKWARD</td>
<td align="right">13,654,067</td>
<td align="right">6.0%</td>
</tr>
<tr>
<td align="left">LOAD_GLOBAL_BUILTIN</td>
<td align="right">12,440,517</td>
<td align="right">5.5%</td>
</tr>
<tr>
<td align="left">LOAD_FAST_LOAD_FAST</td>
<td align="right">9,771,371</td>
<td align="right">4.3%</td>
</tr>
</tbody>
</table>


</details>

### POP_JUMP_IF_NOT_NONE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_NOT_NONE </summary>

<table>
<thead>
<tr>
<th align="left">Predecessors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">296,966,028</td>
<td align="right">84.2%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_INSTANCE_VALUE</td>
<td align="right">21,548,887</td>
<td align="right">6.1%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR</td>
<td align="right">13,779,125</td>
<td align="right">3.9%</td>
</tr>
<tr>
<td align="left">STORE_FAST_LOAD_FAST</td>
<td align="right">8,870,340</td>
<td align="right">2.5%</td>
</tr>
<tr>
<td align="left">EXTENDED_ARG</td>
<td align="right">7,323,040</td>
<td align="right">2.1%</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Successors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">190,798,234</td>
<td align="right">54.1%</td>
</tr>
<tr>
<td align="left">LOAD_FAST_LOAD_FAST</td>
<td align="right">55,273,426</td>
<td align="right">15.7%</td>
</tr>
<tr>
<td align="left">LOAD_GLOBAL_MODULE</td>
<td align="right">34,513,054</td>
<td align="right">9.8%</td>
</tr>
<tr>
<td align="left">JUMP_BACKWARD</td>
<td align="right">26,910,074</td>
<td align="right">7.6%</td>
</tr>
<tr>
<td align="left">LOAD_GLOBAL_BUILTIN</td>
<td align="right">19,528,636</td>
<td align="right">5.5%</td>
</tr>
</tbody>
</table>


</details>

### POP_JUMP_IF_TRUE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_TRUE </summary>

<table>
<thead>
<tr>
<th align="left">Predecessors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">TO_BOOL_BOOL</td>
<td align="right">636,796,062</td>
<td align="right">52.6%</td>
</tr>
<tr>
<td align="left">TO_BOOL</td>
<td align="right">114,102,003</td>
<td align="right">9.4%</td>
</tr>
<tr>
<td align="left">COMPARE_OP_INT</td>
<td align="right">105,782,717</td>
<td align="right">8.7%</td>
</tr>
<tr>
<td align="left">CONTAINS_OP_DICT</td>
<td align="right">54,576,265</td>
<td align="right">4.5%</td>
</tr>
<tr>
<td align="left">COMPARE_OP</td>
<td align="right">41,467,715</td>
<td align="right">3.4%</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Successors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">454,164,709</td>
<td align="right">37.5%</td>
</tr>
<tr>
<td align="left">JUMP_BACKWARD</td>
<td align="right">436,536,876</td>
<td align="right">36.1%</td>
</tr>
<tr>
<td align="left">LOAD_GLOBAL_BUILTIN</td>
<td align="right">84,209,236</td>
<td align="right">7.0%</td>
</tr>
<tr>
<td align="left">LOAD_CONST</td>
<td align="right">67,464,122</td>
<td align="right">5.6%</td>
</tr>
<tr>
<td align="left">LOAD_FAST_LOAD_FAST</td>
<td align="right">34,593,095</td>
<td align="right">2.9%</td>
</tr>
</tbody>
</table>


</details>

### RETURN_CONST

<details>
<summary> Successors and predecessors for RETURN_CONST </summary>

<table>
<thead>
<tr>
<th align="left">Predecessors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">POP_JUMP_IF_FALSE</td>
<td align="right">309,024,697</td>
<td align="right">28.5%</td>
</tr>
<tr>
<td align="left">POP_TOP</td>
<td align="right">153,973,770</td>
<td align="right">14.2%</td>
</tr>
<tr>
<td align="left">STORE_ATTR_SLOT</td>
<td align="right">141,703,881</td>
<td align="right">13.1%</td>
</tr>
<tr>
<td align="left">STORE_ATTR_INSTANCE_VALUE</td>
<td align="right">129,475,217</td>
<td align="right">12.0%</td>
</tr>
<tr>
<td align="left">FOR_ITER_LIST</td>
<td align="right">95,687,664</td>
<td align="right">8.8%</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Successors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">POP_TOP</td>
<td align="right">471,159,197</td>
<td align="right">43.5%</td>
</tr>
<tr>
<td align="left">INTERPRETER_EXIT</td>
<td align="right">350,733,168</td>
<td align="right">32.4%</td>
</tr>
<tr>
<td align="left">EXIT_INIT_CHECK</td>
<td align="right">57,267,754</td>
<td align="right">5.3%</td>
</tr>
<tr>
<td align="left">TO_BOOL_BOOL</td>
<td align="right">53,096,375</td>
<td align="right">4.9%</td>
</tr>
<tr>
<td align="left">END_FOR</td>
<td align="right">37,964,583</td>
<td align="right">3.5%</td>
</tr>
</tbody>
</table>


</details>

### SEND

<details>
<summary> Successors and predecessors for SEND </summary>

<table>
<thead>
<tr>
<th align="left">Predecessors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">LOAD_CONST</td>
<td align="right">105,935,460</td>
<td align="right">94.9%</td>
</tr>
<tr>
<td align="left">JUMP_BACKWARD_NO_INTERRUPT</td>
<td align="right">5,638,660</td>
<td align="right">5.1%</td>
</tr>
<tr>
<td align="left">SEND</td>
<td align="right">28,280</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">SEND_GEN</td>
<td align="right">240</td>
<td align="right">0.0%</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Successors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">END_SEND</td>
<td align="right">99,932,240</td>
<td align="right">89.5%</td>
</tr>
<tr>
<td align="left">END_ASYNC_FOR</td>
<td align="right">6,000,000</td>
<td align="right">5.4%</td>
</tr>
<tr>
<td align="left">YIELD_VALUE</td>
<td align="right">5,633,980</td>
<td align="right">5.0%</td>
</tr>
<tr>
<td align="left">SEND</td>
<td align="right">28,280</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">RESUME_CHECK</td>
<td align="right">5,160</td>
<td align="right">0.0%</td>
</tr>
</tbody>
</table>


</details>

### SET_FUNCTION_ATTRIBUTE

<details>
<summary> Successors and predecessors for SET_FUNCTION_ATTRIBUTE </summary>

<table>
<thead>
<tr>
<th align="left">Predecessors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">MAKE_FUNCTION</td>
<td align="right">66,942,786</td>
<td align="right">99.9%</td>
</tr>
<tr>
<td align="left">SET_FUNCTION_ATTRIBUTE</td>
<td align="right">44,121</td>
<td align="right">0.1%</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Successors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">60,874,755</td>
<td align="right">90.9%</td>
</tr>
<tr>
<td align="left">STORE_FAST</td>
<td align="right">4,568,610</td>
<td align="right">6.8%</td>
</tr>
<tr>
<td align="left">CALL_PY_EXACT_ARGS</td>
<td align="right">714,480</td>
<td align="right">1.1%</td>
</tr>
<tr>
<td align="left">LOAD_CONST</td>
<td align="right">608,940</td>
<td align="right">0.9%</td>
</tr>
<tr>
<td align="left">STORE_DEREF</td>
<td align="right">87,684</td>
<td align="right">0.1%</td>
</tr>
</tbody>
</table>


</details>

### STORE_ATTR

<details>
<summary> Successors and predecessors for STORE_ATTR </summary>

<table>
<thead>
<tr>
<th align="left">Predecessors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">31,654,243</td>
<td align="right">64.9%</td>
</tr>
<tr>
<td align="left">LOAD_FAST_LOAD_FAST</td>
<td align="right">8,519,272</td>
<td align="right">17.5%</td>
</tr>
<tr>
<td align="left">CALL_NON_PY_GENERAL</td>
<td align="right">5,436,780</td>
<td align="right">11.1%</td>
</tr>
<tr>
<td align="left">SWAP</td>
<td align="right">1,242,894</td>
<td align="right">2.5%</td>
</tr>
<tr>
<td align="left">CALL_KW</td>
<td align="right">1,200,840</td>
<td align="right">2.5%</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Successors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">14,260,068</td>
<td align="right">29.2%</td>
</tr>
<tr>
<td align="left">LOAD_DEREF</td>
<td align="right">13,446,060</td>
<td align="right">27.6%</td>
</tr>
<tr>
<td align="left">RETURN_CONST</td>
<td align="right">9,063,228</td>
<td align="right">18.6%</td>
</tr>
<tr>
<td align="left">JUMP_BACKWARD</td>
<td align="right">6,765,600</td>
<td align="right">13.9%</td>
</tr>
<tr>
<td align="left">LOAD_CONST</td>
<td align="right">2,291,641</td>
<td align="right">4.7%</td>
</tr>
</tbody>
</table>


</details>

### STORE_DEREF

<details>
<summary> Successors and predecessors for STORE_DEREF </summary>

<table>
<thead>
<tr>
<th align="left">Predecessors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">BINARY_OP_ADD_INT</td>
<td align="right">26,873,280</td>
<td align="right">55.0%</td>
</tr>
<tr>
<td align="left">LOAD_CONST</td>
<td align="right">6,728,760</td>
<td align="right">13.8%</td>
</tr>
<tr>
<td align="left">UNPACK_SEQUENCE_TWO_TUPLE</td>
<td align="right">3,356,640</td>
<td align="right">6.9%</td>
</tr>
<tr>
<td align="left">YIELD_VALUE</td>
<td align="right">2,419,200</td>
<td align="right">4.9%</td>
</tr>
<tr>
<td align="left">BUILD_LIST</td>
<td align="right">2,254,320</td>
<td align="right">4.6%</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Successors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">LOAD_DEREF</td>
<td align="right">14,556,904</td>
<td align="right">29.8%</td>
</tr>
<tr>
<td align="left">LOAD_FAST_LOAD_FAST</td>
<td align="right">13,438,080</td>
<td align="right">27.5%</td>
</tr>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">8,718,289</td>
<td align="right">17.8%</td>
</tr>
<tr>
<td align="left">LOAD_CONST</td>
<td align="right">4,516,680</td>
<td align="right">9.2%</td>
</tr>
<tr>
<td align="left">STORE_FAST</td>
<td align="right">3,356,460</td>
<td align="right">6.9%</td>
</tr>
</tbody>
</table>


</details>

### STORE_FAST

<details>
<summary> Successors and predecessors for STORE_FAST </summary>

<table>
<thead>
<tr>
<th align="left">Predecessors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">STORE_FAST</td>
<td align="right">711,356,581</td>
<td align="right">10.3%</td>
</tr>
<tr>
<td align="left">FOR_ITER_LIST</td>
<td align="right">544,064,954</td>
<td align="right">7.8%</td>
</tr>
<tr>
<td align="left">RETURN_VALUE</td>
<td align="right">400,819,618</td>
<td align="right">5.8%</td>
</tr>
<tr>
<td align="left">LOAD_CONST</td>
<td align="right">396,107,800</td>
<td align="right">5.7%</td>
</tr>
<tr>
<td align="left">FOR_ITER_RANGE</td>
<td align="right">386,713,789</td>
<td align="right">5.6%</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Successors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">3,478,601,698</td>
<td align="right">50.2%</td>
</tr>
<tr>
<td align="left">LOAD_FAST_LOAD_FAST</td>
<td align="right">926,099,743</td>
<td align="right">13.4%</td>
</tr>
<tr>
<td align="left">STORE_FAST</td>
<td align="right">711,356,581</td>
<td align="right">10.3%</td>
</tr>
<tr>
<td align="left">LOAD_GLOBAL_BUILTIN</td>
<td align="right">472,311,722</td>
<td align="right">6.8%</td>
</tr>
<tr>
<td align="left">LOAD_DEREF</td>
<td align="right">318,968,447</td>
<td align="right">4.6%</td>
</tr>
</tbody>
</table>


</details>

### STORE_FAST_STORE_FAST

<details>
<summary> Successors and predecessors for STORE_FAST_STORE_FAST </summary>

<table>
<thead>
<tr>
<th align="left">Predecessors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">STORE_FAST_STORE_FAST</td>
<td align="right">1,603,189,202</td>
<td align="right">64.4%</td>
</tr>
<tr>
<td align="left">UNPACK_SEQUENCE_TWO_TUPLE</td>
<td align="right">329,513,940</td>
<td align="right">13.2%</td>
</tr>
<tr>
<td align="left">UNPACK_SEQUENCE_TUPLE</td>
<td align="right">255,981,902</td>
<td align="right">10.3%</td>
</tr>
<tr>
<td align="left">UNPACK_SEQUENCE_LIST</td>
<td align="right">221,203,200</td>
<td align="right">8.9%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_SLOT</td>
<td align="right">45,905,880</td>
<td align="right">1.8%</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Successors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">STORE_FAST_STORE_FAST</td>
<td align="right">1,603,189,202</td>
<td align="right">64.4%</td>
</tr>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">612,979,446</td>
<td align="right">24.6%</td>
</tr>
<tr>
<td align="left">STORE_FAST</td>
<td align="right">103,168,980</td>
<td align="right">4.1%</td>
</tr>
<tr>
<td align="left">LOAD_FAST_LOAD_FAST</td>
<td align="right">74,382,842</td>
<td align="right">3.0%</td>
</tr>
<tr>
<td align="left">LOAD_GLOBAL_MODULE</td>
<td align="right">45,965,320</td>
<td align="right">1.8%</td>
</tr>
</tbody>
</table>


</details>

### UNPACK_SEQUENCE

<details>
<summary> Successors and predecessors for UNPACK_SEQUENCE </summary>

<table>
<thead>
<tr>
<th align="left">Predecessors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">CALL_METHOD_DESCRIPTOR_NOARGS</td>
<td align="right">96,080</td>
<td align="right">83.9%</td>
</tr>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">11,097</td>
<td align="right">9.7%</td>
</tr>
<tr>
<td align="left">CALL_BUILTIN_FAST</td>
<td align="right">2,440</td>
<td align="right">2.1%</td>
</tr>
<tr>
<td align="left">RETURN_VALUE</td>
<td align="right">1,700</td>
<td align="right">1.5%</td>
</tr>
<tr>
<td align="left">FOR_ITER_LIST</td>
<td align="right">1,054</td>
<td align="right">0.9%</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Successors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">STORE_FAST_STORE_FAST</td>
<td align="right">106,260</td>
<td align="right">92.8%</td>
</tr>
<tr>
<td align="left">STORE_FAST</td>
<td align="right">4,323</td>
<td align="right">3.8%</td>
</tr>
<tr>
<td align="left">UNPACK_SEQUENCE_TWO_TUPLE</td>
<td align="right">2,400</td>
<td align="right">2.1%</td>
</tr>
<tr>
<td align="left">UNPACK_SEQUENCE_TUPLE</td>
<td align="right">600</td>
<td align="right">0.5%</td>
</tr>
<tr>
<td align="left">UNPACK_SEQUENCE</td>
<td align="right">445</td>
<td align="right">0.4%</td>
</tr>
</tbody>
</table>


</details>

### BINARY_OP_ADD_INT

<details>
<summary> Successors and predecessors for BINARY_OP_ADD_INT </summary>

<table>
<thead>
<tr>
<th align="left">Predecessors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">LOAD_CONST</td>
<td align="right">804,349,772</td>
<td align="right">63.5%</td>
</tr>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">259,034,667</td>
<td align="right">20.5%</td>
</tr>
<tr>
<td align="left">LOAD_FAST_LOAD_FAST</td>
<td align="right">94,578,726</td>
<td align="right">7.5%</td>
</tr>
<tr>
<td align="left">END_SEND</td>
<td align="right">29,134,080</td>
<td align="right">2.3%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_INSTANCE_VALUE</td>
<td align="right">24,606,160</td>
<td align="right">1.9%</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Successors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">STORE_FAST</td>
<td align="right">283,331,931</td>
<td align="right">22.4%</td>
</tr>
<tr>
<td align="left">LOAD_CONST</td>
<td align="right">151,370,452</td>
<td align="right">12.0%</td>
</tr>
<tr>
<td align="left">STORE_SLICE</td>
<td align="right">103,909,800</td>
<td align="right">8.2%</td>
</tr>
<tr>
<td align="left">BINARY_SUBSCR</td>
<td align="right">102,644,000</td>
<td align="right">8.1%</td>
</tr>
<tr>
<td align="left">BINARY_OP_MULTIPLY_INT</td>
<td align="right">95,863,620</td>
<td align="right">7.6%</td>
</tr>
</tbody>
</table>


</details>

### BINARY_OP_SUBTRACT_FLOAT

<details>
<summary> Successors and predecessors for BINARY_OP_SUBTRACT_FLOAT </summary>

<table>
<thead>
<tr>
<th align="left">Predecessors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">BINARY_OP_MULTIPLY_FLOAT</td>
<td align="right">109,285,680</td>
<td align="right">38.8%</td>
</tr>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">69,337,820</td>
<td align="right">24.6%</td>
</tr>
<tr>
<td align="left">LOAD_FAST_LOAD_FAST</td>
<td align="right">36,003,600</td>
<td align="right">12.8%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_INSTANCE_VALUE</td>
<td align="right">29,861,940</td>
<td align="right">10.6%</td>
</tr>
<tr>
<td align="left">BINARY_SUBSCR</td>
<td align="right">24,729,580</td>
<td align="right">8.8%</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Successors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">STORE_FAST</td>
<td align="right">108,319,972</td>
<td align="right">38.4%</td>
</tr>
<tr>
<td align="left">LOAD_FAST_LOAD_FAST</td>
<td align="right">73,280,400</td>
<td align="right">26.0%</td>
</tr>
<tr>
<td align="left">SWAP</td>
<td align="right">55,701,000</td>
<td align="right">19.8%</td>
</tr>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">29,548,920</td>
<td align="right">10.5%</td>
</tr>
<tr>
<td align="left">BINARY_OP_SUBTRACT_FLOAT</td>
<td align="right">10,737,420</td>
<td align="right">3.8%</td>
</tr>
</tbody>
</table>


</details>

### BINARY_SUBSCR_DICT

<details>
<summary> Successors and predecessors for BINARY_SUBSCR_DICT </summary>

<table>
<thead>
<tr>
<th align="left">Predecessors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">174,517,969</td>
<td align="right">73.4%</td>
</tr>
<tr>
<td align="left">LOAD_FAST_LOAD_FAST</td>
<td align="right">17,827,635</td>
<td align="right">7.5%</td>
</tr>
<tr>
<td align="left">LOAD_CONST</td>
<td align="right">14,009,740</td>
<td align="right">5.9%</td>
</tr>
<tr>
<td align="left">BINARY_SUBSCR</td>
<td align="right">10,061,220</td>
<td align="right">4.2%</td>
</tr>
<tr>
<td align="left">CALL_BUILTIN_O</td>
<td align="right">10,025,520</td>
<td align="right">4.2%</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Successors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">RETURN_VALUE</td>
<td align="right">140,276,589</td>
<td align="right">59.0%</td>
</tr>
<tr>
<td align="left">STORE_FAST</td>
<td align="right">36,988,122</td>
<td align="right">15.6%</td>
</tr>
<tr>
<td align="left">UNPACK_SEQUENCE_TUPLE</td>
<td align="right">14,268,900</td>
<td align="right">6.0%</td>
</tr>
<tr>
<td align="left">PUSH_NULL</td>
<td align="right">10,418,760</td>
<td align="right">4.4%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_METHOD_NO_DICT</td>
<td align="right">5,145,180</td>
<td align="right">2.2%</td>
</tr>
</tbody>
</table>


</details>

### BINARY_SUBSCR_GETITEM

<details>
<summary> Successors and predecessors for BINARY_SUBSCR_GETITEM </summary>

<table>
<thead>
<tr>
<th align="left">Predecessors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">LOAD_FAST_LOAD_FAST</td>
<td align="right">66,992,160</td>
<td align="right">61.9%</td>
</tr>
<tr>
<td align="left">BUILD_TUPLE</td>
<td align="right">28,812,000</td>
<td align="right">26.6%</td>
</tr>
<tr>
<td align="left">LOAD_CONST</td>
<td align="right">6,107,690</td>
<td align="right">5.6%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_INSTANCE_VALUE</td>
<td align="right">3,355,020</td>
<td align="right">3.1%</td>
</tr>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">2,847,420</td>
<td align="right">2.6%</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Successors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">RESUME_CHECK</td>
<td align="right">108,126,340</td>
<td align="right">100.0%</td>
</tr>
<tr>
<td align="left">MAKE_CELL</td>
<td align="right">11,030</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_METHOD_NO_DICT</td>
<td align="right">5,520</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">2,040</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">CONTAINS_OP</td>
<td align="right">1,280</td>
<td align="right">0.0%</td>
</tr>
</tbody>
</table>


</details>

### BINARY_SUBSCR_TUPLE_INT

<details>
<summary> Successors and predecessors for BINARY_SUBSCR_TUPLE_INT </summary>

<table>
<thead>
<tr>
<th align="left">Predecessors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">LOAD_CONST</td>
<td align="right">188,657,220</td>
<td align="right">82.6%</td>
</tr>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">39,862,287</td>
<td align="right">17.4%</td>
</tr>
<tr>
<td align="left">LOAD_FAST_LOAD_FAST</td>
<td align="right">420</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">BINARY_SUBSCR</td>
<td align="right">360</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">BINARY_SUBSCR_LIST_INT</td>
<td align="right">60</td>
<td align="right">0.0%</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Successors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">CALL_NON_PY_GENERAL</td>
<td align="right">72,000,000</td>
<td align="right">31.5%</td>
</tr>
<tr>
<td align="left">LOAD_GLOBAL_MODULE</td>
<td align="right">30,804,020</td>
<td align="right">13.5%</td>
</tr>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">25,831,213</td>
<td align="right">11.3%</td>
</tr>
<tr>
<td align="left">LOAD_CONST</td>
<td align="right">24,429,050</td>
<td align="right">10.7%</td>
</tr>
<tr>
<td align="left">YIELD_VALUE</td>
<td align="right">19,355,040</td>
<td align="right">8.5%</td>
</tr>
</tbody>
</table>


</details>

### CALL_BOUND_METHOD_EXACT_ARGS

<details>
<summary> Successors and predecessors for CALL_BOUND_METHOD_EXACT_ARGS </summary>

<table>
<thead>
<tr>
<th align="left">Predecessors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">29,787,669</td>
<td align="right">26.0%</td>
</tr>
<tr>
<td align="left">LOAD_CONST</td>
<td align="right">26,185,220</td>
<td align="right">22.9%</td>
</tr>
<tr>
<td align="left">BINARY_OP_MULTIPLY_INT</td>
<td align="right">22,513,860</td>
<td align="right">19.7%</td>
</tr>
<tr>
<td align="left">BINARY_OP_ADD_INT</td>
<td align="right">6,878,009</td>
<td align="right">6.0%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_INSTANCE_VALUE</td>
<td align="right">6,495,520</td>
<td align="right">5.7%</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Successors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">RESUME_CHECK</td>
<td align="right">86,342,979</td>
<td align="right">75.5%</td>
</tr>
<tr>
<td align="left">COPY_FREE_VARS</td>
<td align="right">27,104,627</td>
<td align="right">23.7%</td>
</tr>
<tr>
<td align="left">MAKE_CELL</td>
<td align="right">662,977</td>
<td align="right">0.6%</td>
</tr>
<tr>
<td align="left">CALL_PY_EXACT_ARGS</td>
<td align="right">159,412</td>
<td align="right">0.1%</td>
</tr>
<tr>
<td align="left">POP_TOP</td>
<td align="right">91,940</td>
<td align="right">0.1%</td>
</tr>
</tbody>
</table>


</details>

### CALL_BUILTIN_CLASS

<details>
<summary> Successors and predecessors for CALL_BUILTIN_CLASS </summary>

<table>
<thead>
<tr>
<th align="left">Predecessors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">38,593,195</td>
<td align="right">37.3%</td>
</tr>
<tr>
<td align="left">LOAD_CONST</td>
<td align="right">10,051,080</td>
<td align="right">9.7%</td>
</tr>
<tr>
<td align="left">CALL_METHOD_DESCRIPTOR_NOARGS</td>
<td align="right">9,883,654</td>
<td align="right">9.6%</td>
</tr>
<tr>
<td align="left">BINARY_OP_MULTIPLY_INT</td>
<td align="right">7,662,580</td>
<td align="right">7.4%</td>
</tr>
<tr>
<td align="left">BINARY_OP_ADD_INT</td>
<td align="right">6,888,220</td>
<td align="right">6.7%</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Successors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">GET_ITER</td>
<td align="right">32,469,598</td>
<td align="right">31.4%</td>
</tr>
<tr>
<td align="left">BINARY_OP_MULTIPLY_FLOAT</td>
<td align="right">24,782,880</td>
<td align="right">24.0%</td>
</tr>
<tr>
<td align="left">STORE_FAST</td>
<td align="right">18,142,430</td>
<td align="right">17.6%</td>
</tr>
<tr>
<td align="left">CALL_BUILTIN_CLASS</td>
<td align="right">5,522,590</td>
<td align="right">5.3%</td>
</tr>
<tr>
<td align="left">CALL_BUILTIN_O</td>
<td align="right">3,552,640</td>
<td align="right">3.4%</td>
</tr>
</tbody>
</table>


</details>

### CALL_BUILTIN_FAST

<details>
<summary> Successors and predecessors for CALL_BUILTIN_FAST </summary>

<table>
<thead>
<tr>
<th align="left">Predecessors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">LOAD_GLOBAL_BUILTIN</td>
<td align="right">434,497,240</td>
<td align="right">46.1%</td>
</tr>
<tr>
<td align="left">LOAD_CONST</td>
<td align="right">333,675,973</td>
<td align="right">35.4%</td>
</tr>
<tr>
<td align="left">LOAD_FAST_LOAD_FAST</td>
<td align="right">80,842,263</td>
<td align="right">8.6%</td>
</tr>
<tr>
<td align="left">CALL_BUILTIN_FAST</td>
<td align="right">37,470,460</td>
<td align="right">4.0%</td>
</tr>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">27,142,552</td>
<td align="right">2.9%</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Successors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">TO_BOOL_BOOL</td>
<td align="right">486,880,685</td>
<td align="right">51.7%</td>
</tr>
<tr>
<td align="left">STORE_FAST</td>
<td align="right">322,314,124</td>
<td align="right">34.2%</td>
</tr>
<tr>
<td align="left">POP_TOP</td>
<td align="right">44,968,953</td>
<td align="right">4.8%</td>
</tr>
<tr>
<td align="left">CALL_BUILTIN_FAST</td>
<td align="right">37,470,460</td>
<td align="right">4.0%</td>
</tr>
<tr>
<td align="left">COPY</td>
<td align="right">13,660,440</td>
<td align="right">1.4%</td>
</tr>
</tbody>
</table>


</details>

### CALL_BUILTIN_O

<details>
<summary> Successors and predecessors for CALL_BUILTIN_O </summary>

<table>
<thead>
<tr>
<th align="left">Predecessors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">575,632,517</td>
<td align="right">71.3%</td>
</tr>
<tr>
<td align="left">LOAD_CONST</td>
<td align="right">57,658,920</td>
<td align="right">7.1%</td>
</tr>
<tr>
<td align="left">RETURN_VALUE</td>
<td align="right">55,933,140</td>
<td align="right">6.9%</td>
</tr>
<tr>
<td align="left">BUILD_STRING</td>
<td align="right">37,276,800</td>
<td align="right">4.6%</td>
</tr>
<tr>
<td align="left">BINARY_OP_ADD_UNICODE</td>
<td align="right">19,572,000</td>
<td align="right">2.4%</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Successors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">POP_TOP</td>
<td align="right">355,295,220</td>
<td align="right">44.0%</td>
</tr>
<tr>
<td align="left">STORE_FAST</td>
<td align="right">176,210,618</td>
<td align="right">21.8%</td>
</tr>
<tr>
<td align="left">LOAD_CONST</td>
<td align="right">171,659,376</td>
<td align="right">21.3%</td>
</tr>
<tr>
<td align="left">RETURN_VALUE</td>
<td align="right">27,879,447</td>
<td align="right">3.5%</td>
</tr>
<tr>
<td align="left">STORE_SUBSCR_DICT</td>
<td align="right">13,999,260</td>
<td align="right">1.7%</td>
</tr>
</tbody>
</table>


</details>

### CALL_ISINSTANCE

<details>
<summary> Successors and predecessors for CALL_ISINSTANCE </summary>

<table>
<thead>
<tr>
<th align="left">Predecessors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">LOAD_GLOBAL_MODULE</td>
<td align="right">186,718,011</td>
<td align="right">41.4%</td>
</tr>
<tr>
<td align="left">LOAD_GLOBAL_BUILTIN</td>
<td align="right">155,809,690</td>
<td align="right">34.5%</td>
</tr>
<tr>
<td align="left">LOAD_FAST_LOAD_FAST</td>
<td align="right">61,137,087</td>
<td align="right">13.5%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_MODULE</td>
<td align="right">21,457,320</td>
<td align="right">4.8%</td>
</tr>
<tr>
<td align="left">BUILD_TUPLE</td>
<td align="right">9,926,463</td>
<td align="right">2.2%</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Successors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">TO_BOOL_BOOL</td>
<td align="right">440,159,402</td>
<td align="right">97.5%</td>
</tr>
<tr>
<td align="left">YIELD_VALUE</td>
<td align="right">5,172,952</td>
<td align="right">1.1%</td>
</tr>
<tr>
<td align="left">COPY</td>
<td align="right">3,120,420</td>
<td align="right">0.7%</td>
</tr>
<tr>
<td align="left">RETURN_VALUE</td>
<td align="right">1,664,652</td>
<td align="right">0.4%</td>
</tr>
<tr>
<td align="left">STORE_FAST</td>
<td align="right">1,176,337</td>
<td align="right">0.3%</td>
</tr>
</tbody>
</table>


</details>

### CALL_LEN

<details>
<summary> Successors and predecessors for CALL_LEN </summary>

<table>
<thead>
<tr>
<th align="left">Predecessors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">200,718,638</td>
<td align="right">73.2%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_INSTANCE_VALUE</td>
<td align="right">34,214,050</td>
<td align="right">12.5%</td>
</tr>
<tr>
<td align="left">BINARY_SUBSCR_LIST_INT</td>
<td align="right">29,548,500</td>
<td align="right">10.8%</td>
</tr>
<tr>
<td align="left">BINARY_OP</td>
<td align="right">3,086,160</td>
<td align="right">1.1%</td>
</tr>
<tr>
<td align="left">CALL_BUILTIN_CLASS</td>
<td align="right">2,569,980</td>
<td align="right">0.9%</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Successors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">LOAD_CONST</td>
<td align="right">113,621,944</td>
<td align="right">41.4%</td>
</tr>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">40,642,380</td>
<td align="right">14.8%</td>
</tr>
<tr>
<td align="left">COMPARE_OP_INT</td>
<td align="right">35,514,500</td>
<td align="right">13.0%</td>
</tr>
<tr>
<td align="left">STORE_FAST</td>
<td align="right">34,944,632</td>
<td align="right">12.7%</td>
</tr>
<tr>
<td align="left">LOAD_GLOBAL_BUILTIN</td>
<td align="right">9,755,110</td>
<td align="right">3.6%</td>
</tr>
</tbody>
</table>


</details>

### CALL_METHOD_DESCRIPTOR_FAST

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_FAST </summary>

<table>
<thead>
<tr>
<th align="left">Predecessors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">102,832,381</td>
<td align="right">41.5%</td>
</tr>
<tr>
<td align="left">LOAD_FAST_LOAD_FAST</td>
<td align="right">53,345,760</td>
<td align="right">21.5%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_METHOD_NO_DICT</td>
<td align="right">35,831,120</td>
<td align="right">14.5%</td>
</tr>
<tr>
<td align="left">LOAD_CONST</td>
<td align="right">26,962,350</td>
<td align="right">10.9%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_SLOT</td>
<td align="right">8,303,280</td>
<td align="right">3.4%</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Successors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">STORE_FAST</td>
<td align="right">173,836,160</td>
<td align="right">70.2%</td>
</tr>
<tr>
<td align="left">UNPACK_SEQUENCE_TUPLE</td>
<td align="right">14,633,560</td>
<td align="right">5.9%</td>
</tr>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">9,938,966</td>
<td align="right">4.0%</td>
</tr>
<tr>
<td align="left">RETURN_VALUE</td>
<td align="right">9,173,040</td>
<td align="right">3.7%</td>
</tr>
<tr>
<td align="left">TO_BOOL_BOOL</td>
<td align="right">7,396,674</td>
<td align="right">3.0%</td>
</tr>
</tbody>
</table>


</details>

### CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS </summary>

<table>
<thead>
<tr>
<th align="left">Predecessors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">LOAD_CONST</td>
<td align="right">60,548,780</td>
<td align="right">82.7%</td>
</tr>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">8,526,920</td>
<td align="right">11.6%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_METHOD_NO_DICT</td>
<td align="right">3,800,560</td>
<td align="right">5.2%</td>
</tr>
<tr>
<td align="left">LOAD_FAST_LOAD_FAST</td>
<td align="right">142,581</td>
<td align="right">0.2%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_SLOT</td>
<td align="right">78,240</td>
<td align="right">0.1%</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Successors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">STORE_FAST</td>
<td align="right">59,235,601</td>
<td align="right">80.9%</td>
</tr>
<tr>
<td align="left">CALL_METHOD_DESCRIPTOR_O</td>
<td align="right">6,935,320</td>
<td align="right">9.5%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_METHOD_NO_DICT</td>
<td align="right">2,919,060</td>
<td align="right">4.0%</td>
</tr>
<tr>
<td align="left">BINARY_OP</td>
<td align="right">2,010,960</td>
<td align="right">2.7%</td>
</tr>
<tr>
<td align="left">RETURN_VALUE</td>
<td align="right">867,780</td>
<td align="right">1.2%</td>
</tr>
</tbody>
</table>


</details>

### CALL_METHOD_DESCRIPTOR_NOARGS

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_NOARGS </summary>

<table>
<thead>
<tr>
<th align="left">Predecessors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">LOAD_ATTR_METHOD_NO_DICT</td>
<td align="right">160,132,404</td>
<td align="right">64.7%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_METHOD_LAZY_DICT</td>
<td align="right">66,378,626</td>
<td align="right">26.8%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR</td>
<td align="right">17,258,525</td>
<td align="right">7.0%</td>
</tr>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">3,129,180</td>
<td align="right">1.3%</td>
</tr>
<tr>
<td align="left">CALL_METHOD_DESCRIPTOR_NOARGS</td>
<td align="right">410,162</td>
<td align="right">0.2%</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Successors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">STORE_FAST</td>
<td align="right">78,128,143</td>
<td align="right">31.6%</td>
</tr>
<tr>
<td align="left">TO_BOOL_BOOL</td>
<td align="right">58,930,710</td>
<td align="right">23.8%</td>
</tr>
<tr>
<td align="left">GET_ITER</td>
<td align="right">43,266,601</td>
<td align="right">17.5%</td>
</tr>
<tr>
<td align="left">LOAD_GLOBAL_MODULE</td>
<td align="right">18,631,740</td>
<td align="right">7.5%</td>
</tr>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">12,104,214</td>
<td align="right">4.9%</td>
</tr>
</tbody>
</table>


</details>

### CALL_METHOD_DESCRIPTOR_O

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_O </summary>

<table>
<thead>
<tr>
<th align="left">Predecessors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">190,832,436</td>
<td align="right">81.6%</td>
</tr>
<tr>
<td align="left">CALL</td>
<td align="right">19,489,737</td>
<td align="right">8.3%</td>
</tr>
<tr>
<td align="left">CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS</td>
<td align="right">6,935,320</td>
<td align="right">3.0%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES</td>
<td align="right">3,038,640</td>
<td align="right">1.3%</td>
</tr>
<tr>
<td align="left">STORE_FAST</td>
<td align="right">2,536,080</td>
<td align="right">1.1%</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Successors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">POP_TOP</td>
<td align="right">127,882,933</td>
<td align="right">54.7%</td>
</tr>
<tr>
<td align="left">BINARY_OP</td>
<td align="right">72,001,440</td>
<td align="right">30.8%</td>
</tr>
<tr>
<td align="left">RETURN_VALUE</td>
<td align="right">17,252,520</td>
<td align="right">7.4%</td>
</tr>
<tr>
<td align="left">STORE_FAST</td>
<td align="right">7,600,920</td>
<td align="right">3.2%</td>
</tr>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">2,937,480</td>
<td align="right">1.3%</td>
</tr>
</tbody>
</table>


</details>

### CALL_NON_PY_GENERAL

<details>
<summary> Successors and predecessors for CALL_NON_PY_GENERAL </summary>

<table>
<thead>
<tr>
<th align="left">Predecessors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">100,246,575</td>
<td align="right">28.2%</td>
</tr>
<tr>
<td align="left">BINARY_SUBSCR_TUPLE_INT</td>
<td align="right">72,000,000</td>
<td align="right">20.3%</td>
</tr>
<tr>
<td align="left">PUSH_NULL</td>
<td align="right">50,695,024</td>
<td align="right">14.3%</td>
</tr>
<tr>
<td align="left">LOAD_FAST_LOAD_FAST</td>
<td align="right">41,584,420</td>
<td align="right">11.7%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_METHOD_LAZY_DICT</td>
<td align="right">27,296,234</td>
<td align="right">7.7%</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Successors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">STORE_FAST</td>
<td align="right">175,050,035</td>
<td align="right">49.3%</td>
</tr>
<tr>
<td align="left">POP_TOP</td>
<td align="right">43,680,155</td>
<td align="right">12.3%</td>
</tr>
<tr>
<td align="left">LOAD_GLOBAL_MODULE</td>
<td align="right">38,810,400</td>
<td align="right">10.9%</td>
</tr>
<tr>
<td align="left">BUILD_TUPLE</td>
<td align="right">36,531,830</td>
<td align="right">10.3%</td>
</tr>
<tr>
<td align="left">RETURN_VALUE</td>
<td align="right">17,842,528</td>
<td align="right">5.0%</td>
</tr>
</tbody>
</table>


</details>

### CALL_PY_EXACT_ARGS

<details>
<summary> Successors and predecessors for CALL_PY_EXACT_ARGS </summary>

<table>
<thead>
<tr>
<th align="left">Predecessors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">736,250,840</td>
<td align="right">33.9%</td>
</tr>
<tr>
<td align="left">LOAD_FAST_LOAD_FAST</td>
<td align="right">510,383,502</td>
<td align="right">23.5%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_METHOD_WITH_VALUES</td>
<td align="right">388,761,137</td>
<td align="right">17.9%</td>
</tr>
<tr>
<td align="left">BINARY_OP_SUBTRACT_INT</td>
<td align="right">93,675,400</td>
<td align="right">4.3%</td>
</tr>
<tr>
<td align="left">LOAD_GLOBAL_MODULE</td>
<td align="right">92,109,636</td>
<td align="right">4.2%</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Successors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">RESUME_CHECK</td>
<td align="right">1,948,094,871</td>
<td align="right">89.8%</td>
</tr>
<tr>
<td align="left">RETURN_GENERATOR</td>
<td align="right">134,486,429</td>
<td align="right">6.2%</td>
</tr>
<tr>
<td align="left">COPY_FREE_VARS</td>
<td align="right">68,970,510</td>
<td align="right">3.2%</td>
</tr>
<tr>
<td align="left">INSTRUMENTED_RESUME</td>
<td align="right">14,567,400</td>
<td align="right">0.7%</td>
</tr>
<tr>
<td align="left">MAKE_CELL</td>
<td align="right">2,444,138</td>
<td align="right">0.1%</td>
</tr>
</tbody>
</table>


</details>

### CALL_PY_GENERAL

<details>
<summary> Successors and predecessors for CALL_PY_GENERAL </summary>

<table>
<thead>
<tr>
<th align="left">Predecessors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">133,829,923</td>
<td align="right">49.5%</td>
</tr>
<tr>
<td align="left">LOAD_FAST_LOAD_FAST</td>
<td align="right">60,559,760</td>
<td align="right">22.4%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_METHOD_WITH_VALUES</td>
<td align="right">16,059,834</td>
<td align="right">5.9%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_METHOD_NO_DICT</td>
<td align="right">14,804,060</td>
<td align="right">5.5%</td>
</tr>
<tr>
<td align="left">BINARY_OP</td>
<td align="right">11,747,844</td>
<td align="right">4.3%</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Successors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">RESUME_CHECK</td>
<td align="right">257,260,491</td>
<td align="right">95.2%</td>
</tr>
<tr>
<td align="left">COPY_FREE_VARS</td>
<td align="right">8,342,424</td>
<td align="right">3.1%</td>
</tr>
<tr>
<td align="left">RETURN_GENERATOR</td>
<td align="right">3,454,200</td>
<td align="right">1.3%</td>
</tr>
<tr>
<td align="left">MAKE_CELL</td>
<td align="right">956,619</td>
<td align="right">0.4%</td>
</tr>
<tr>
<td align="left">CALL_PY_EXACT_ARGS</td>
<td align="right">81,960</td>
<td align="right">0.0%</td>
</tr>
</tbody>
</table>


</details>

### CALL_STR_1

<details>
<summary> Successors and predecessors for CALL_STR_1 </summary>

<table>
<thead>
<tr>
<th align="left">Predecessors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">40,529,537</td>
<td align="right">90.3%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_INSTANCE_VALUE</td>
<td align="right">2,457,600</td>
<td align="right">5.5%</td>
</tr>
<tr>
<td align="left">RETURN_VALUE</td>
<td align="right">1,734,820</td>
<td align="right">3.9%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_SLOT</td>
<td align="right">109,200</td>
<td align="right">0.2%</td>
</tr>
<tr>
<td align="left">CALL_NON_PY_GENERAL</td>
<td align="right">25,440</td>
<td align="right">0.1%</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Successors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">CALL_BUILTIN_O</td>
<td align="right">10,853,040</td>
<td align="right">24.2%</td>
</tr>
<tr>
<td align="left">CALL_PY_EXACT_ARGS</td>
<td align="right">10,848,480</td>
<td align="right">24.2%</td>
</tr>
<tr>
<td align="left">YIELD_VALUE</td>
<td align="right">7,683,360</td>
<td align="right">17.1%</td>
</tr>
<tr>
<td align="left">STORE_FAST</td>
<td align="right">5,480,417</td>
<td align="right">12.2%</td>
</tr>
<tr>
<td align="left">RETURN_VALUE</td>
<td align="right">3,358,320</td>
<td align="right">7.5%</td>
</tr>
</tbody>
</table>


</details>

### CALL_TYPE_1

<details>
<summary> Successors and predecessors for CALL_TYPE_1 </summary>

<table>
<thead>
<tr>
<th align="left">Predecessors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">327,580,757</td>
<td align="right">98.9%</td>
</tr>
<tr>
<td align="left">LOAD_CONST</td>
<td align="right">3,657,404</td>
<td align="right">1.1%</td>
</tr>
<tr>
<td align="left">LOAD_GLOBAL_BUILTIN</td>
<td align="right">19,240</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">CALL</td>
<td align="right">160</td>
<td align="right">0.0%</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Successors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">STORE_FAST</td>
<td align="right">284,162,256</td>
<td align="right">85.8%</td>
</tr>
<tr>
<td align="left">LOAD_GLOBAL_BUILTIN</td>
<td align="right">17,744,379</td>
<td align="right">5.4%</td>
</tr>
<tr>
<td align="left">LOAD_GLOBAL_MODULE</td>
<td align="right">13,471,500</td>
<td align="right">4.1%</td>
</tr>
<tr>
<td align="left">COMPARE_OP</td>
<td align="right">4,366,990</td>
<td align="right">1.3%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR</td>
<td align="right">3,044,452</td>
<td align="right">0.9%</td>
</tr>
</tbody>
</table>


</details>

### COMPARE_OP_INT

<details>
<summary> Successors and predecessors for COMPARE_OP_INT </summary>

<table>
<thead>
<tr>
<th align="left">Predecessors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">LOAD_CONST</td>
<td align="right">544,496,145</td>
<td align="right">41.2%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_INSTANCE_VALUE</td>
<td align="right">172,402,120</td>
<td align="right">13.0%</td>
</tr>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">121,789,448</td>
<td align="right">9.2%</td>
</tr>
<tr>
<td align="left">LOAD_FAST_LOAD_FAST</td>
<td align="right">120,847,338</td>
<td align="right">9.1%</td>
</tr>
<tr>
<td align="left">COPY</td>
<td align="right">100,083,960</td>
<td align="right">7.6%</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Successors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">POP_JUMP_IF_FALSE</td>
<td align="right">1,118,944,465</td>
<td align="right">84.7%</td>
</tr>
<tr>
<td align="left">POP_JUMP_IF_TRUE</td>
<td align="right">105,782,717</td>
<td align="right">8.0%</td>
</tr>
<tr>
<td align="left">RETURN_VALUE</td>
<td align="right">59,838,972</td>
<td align="right">4.5%</td>
</tr>
<tr>
<td align="left">STORE_FAST</td>
<td align="right">14,567,340</td>
<td align="right">1.1%</td>
</tr>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">10,481,040</td>
<td align="right">0.8%</td>
</tr>
</tbody>
</table>


</details>

### CONTAINS_OP_DICT

<details>
<summary> Successors and predecessors for CONTAINS_OP_DICT </summary>

<table>
<thead>
<tr>
<th align="left">Predecessors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">LOAD_FAST_LOAD_FAST</td>
<td align="right">126,413,612</td>
<td align="right">62.5%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_INSTANCE_VALUE</td>
<td align="right">30,993,677</td>
<td align="right">15.3%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR</td>
<td align="right">15,982,123</td>
<td align="right">7.9%</td>
</tr>
<tr>
<td align="left">LOAD_DEREF</td>
<td align="right">11,065,080</td>
<td align="right">5.5%</td>
</tr>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">5,732,180</td>
<td align="right">2.8%</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Successors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">POP_JUMP_IF_FALSE</td>
<td align="right">145,102,879</td>
<td align="right">71.8%</td>
</tr>
<tr>
<td align="left">POP_JUMP_IF_TRUE</td>
<td align="right">54,576,265</td>
<td align="right">27.0%</td>
</tr>
<tr>
<td align="left">RETURN_VALUE</td>
<td align="right">1,691,940</td>
<td align="right">0.8%</td>
</tr>
<tr>
<td align="left">STORE_FAST</td>
<td align="right">843,900</td>
<td align="right">0.4%</td>
</tr>
<tr>
<td align="left">CONTAINS_OP_SET</td>
<td align="right">11,780</td>
<td align="right">0.0%</td>
</tr>
</tbody>
</table>


</details>

### FOR_ITER_LIST

<details>
<summary> Successors and predecessors for FOR_ITER_LIST </summary>

<table>
<thead>
<tr>
<th align="left">Predecessors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">JUMP_BACKWARD</td>
<td align="right">829,644,464</td>
<td align="right">77.6%</td>
</tr>
<tr>
<td align="left">GET_ITER</td>
<td align="right">163,805,977</td>
<td align="right">15.3%</td>
</tr>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">54,352,042</td>
<td align="right">5.1%</td>
</tr>
<tr>
<td align="left">EXTENDED_ARG</td>
<td align="right">16,868,365</td>
<td align="right">1.6%</td>
</tr>
<tr>
<td align="left">SWAP</td>
<td align="right">3,438,355</td>
<td align="right">0.3%</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Successors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">STORE_FAST</td>
<td align="right">544,064,954</td>
<td align="right">50.9%</td>
</tr>
<tr>
<td align="left">UNPACK_SEQUENCE_TWO_TUPLE</td>
<td align="right">287,912,670</td>
<td align="right">26.9%</td>
</tr>
<tr>
<td align="left">RETURN_CONST</td>
<td align="right">95,687,664</td>
<td align="right">8.9%</td>
</tr>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">43,512,584</td>
<td align="right">4.1%</td>
</tr>
<tr>
<td align="left">LOAD_FAST_LOAD_FAST</td>
<td align="right">40,061,620</td>
<td align="right">3.7%</td>
</tr>
</tbody>
</table>


</details>

### FOR_ITER_RANGE

<details>
<summary> Successors and predecessors for FOR_ITER_RANGE </summary>

<table>
<thead>
<tr>
<th align="left">Predecessors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">JUMP_BACKWARD</td>
<td align="right">415,861,117</td>
<td align="right">92.4%</td>
</tr>
<tr>
<td align="left">GET_ITER</td>
<td align="right">25,554,223</td>
<td align="right">5.7%</td>
</tr>
<tr>
<td align="left">SWAP</td>
<td align="right">4,416,060</td>
<td align="right">1.0%</td>
</tr>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">2,547,420</td>
<td align="right">0.6%</td>
</tr>
<tr>
<td align="left">EXTENDED_ARG</td>
<td align="right">1,567,260</td>
<td align="right">0.3%</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Successors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">STORE_FAST</td>
<td align="right">386,713,789</td>
<td align="right">85.9%</td>
</tr>
<tr>
<td align="left">STORE_FAST_LOAD_FAST</td>
<td align="right">35,295,420</td>
<td align="right">7.8%</td>
</tr>
<tr>
<td align="left">JUMP_BACKWARD</td>
<td align="right">11,476,620</td>
<td align="right">2.6%</td>
</tr>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">4,048,764</td>
<td align="right">0.9%</td>
</tr>
<tr>
<td align="left">RETURN_CONST</td>
<td align="right">3,192,859</td>
<td align="right">0.7%</td>
</tr>
</tbody>
</table>


</details>

### LOAD_ATTR_INSTANCE_VALUE

<details>
<summary> Successors and predecessors for LOAD_ATTR_INSTANCE_VALUE </summary>

<table>
<thead>
<tr>
<th align="left">Predecessors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">3,216,101,202</td>
<td align="right">87.6%</td>
</tr>
<tr>
<td align="left">LOAD_FAST_LOAD_FAST</td>
<td align="right">296,748,789</td>
<td align="right">8.1%</td>
</tr>
<tr>
<td align="left">COPY</td>
<td align="right">64,819,575</td>
<td align="right">1.8%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_INSTANCE_VALUE</td>
<td align="right">54,048,504</td>
<td align="right">1.5%</td>
</tr>
<tr>
<td align="left">RETURN_VALUE</td>
<td align="right">23,175,280</td>
<td align="right">0.6%</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Successors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">1,052,827,067</td>
<td align="right">28.7%</td>
</tr>
<tr>
<td align="left">TO_BOOL_BOOL</td>
<td align="right">554,867,282</td>
<td align="right">15.1%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_METHOD_NO_DICT</td>
<td align="right">213,887,569</td>
<td align="right">5.8%</td>
</tr>
<tr>
<td align="left">RETURN_VALUE</td>
<td align="right">187,363,724</td>
<td align="right">5.1%</td>
</tr>
<tr>
<td align="left">COMPARE_OP_INT</td>
<td align="right">172,402,120</td>
<td align="right">4.7%</td>
</tr>
</tbody>
</table>


</details>

### LOAD_ATTR_METHOD_NO_DICT

<details>
<summary> Successors and predecessors for LOAD_ATTR_METHOD_NO_DICT </summary>

<table>
<thead>
<tr>
<th align="left">Predecessors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">522,572,937</td>
<td align="right">52.2%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_INSTANCE_VALUE</td>
<td align="right">213,887,569</td>
<td align="right">21.4%</td>
</tr>
<tr>
<td align="left">LOAD_CONST</td>
<td align="right">90,512,440</td>
<td align="right">9.0%</td>
</tr>
<tr>
<td align="left">LOAD_GLOBAL_MODULE</td>
<td align="right">48,665,157</td>
<td align="right">4.9%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_SLOT</td>
<td align="right">23,655,300</td>
<td align="right">2.4%</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Successors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">496,448,974</td>
<td align="right">49.6%</td>
</tr>
<tr>
<td align="left">CALL_METHOD_DESCRIPTOR_NOARGS</td>
<td align="right">160,132,404</td>
<td align="right">16.0%</td>
</tr>
<tr>
<td align="left">LOAD_CONST</td>
<td align="right">99,896,342</td>
<td align="right">10.0%</td>
</tr>
<tr>
<td align="left">LOAD_FAST_LOAD_FAST</td>
<td align="right">78,077,239</td>
<td align="right">7.8%</td>
</tr>
<tr>
<td align="left">CALL_PY_EXACT_ARGS</td>
<td align="right">66,811,033</td>
<td align="right">6.7%</td>
</tr>
</tbody>
</table>


</details>

### LOAD_ATTR_METHOD_WITH_VALUES

<details>
<summary> Successors and predecessors for LOAD_ATTR_METHOD_WITH_VALUES </summary>

<table>
<thead>
<tr>
<th align="left">Predecessors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">1,539,020,905</td>
<td align="right">89.8%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_INSTANCE_VALUE</td>
<td align="right">56,439,069</td>
<td align="right">3.3%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_SLOT</td>
<td align="right">44,293,981</td>
<td align="right">2.6%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_WITH_HINT</td>
<td align="right">23,298,684</td>
<td align="right">1.4%</td>
</tr>
<tr>
<td align="left">LOAD_FAST_LOAD_FAST</td>
<td align="right">15,255,277</td>
<td align="right">0.9%</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Successors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">721,114,180</td>
<td align="right">42.1%</td>
</tr>
<tr>
<td align="left">LOAD_FAST_LOAD_FAST</td>
<td align="right">446,212,081</td>
<td align="right">26.0%</td>
</tr>
<tr>
<td align="left">CALL_PY_EXACT_ARGS</td>
<td align="right">388,761,137</td>
<td align="right">22.7%</td>
</tr>
<tr>
<td align="left">LOAD_GLOBAL_MODULE</td>
<td align="right">89,991,374</td>
<td align="right">5.2%</td>
</tr>
<tr>
<td align="left">LOAD_CONST</td>
<td align="right">45,383,350</td>
<td align="right">2.6%</td>
</tr>
</tbody>
</table>


</details>

### LOAD_ATTR_MODULE

<details>
<summary> Successors and predecessors for LOAD_ATTR_MODULE </summary>

<table>
<thead>
<tr>
<th align="left">Predecessors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">LOAD_GLOBAL_MODULE</td>
<td align="right">312,298,509</td>
<td align="right">95.5%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_MODULE</td>
<td align="right">13,616,780</td>
<td align="right">4.2%</td>
</tr>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">628,360</td>
<td align="right">0.2%</td>
</tr>
<tr>
<td align="left">LOAD_DEREF</td>
<td align="right">335,160</td>
<td align="right">0.1%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_WITH_HINT</td>
<td align="right">14,460</td>
<td align="right">0.0%</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Successors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">PUSH_NULL</td>
<td align="right">261,559,477</td>
<td align="right">80.0%</td>
</tr>
<tr>
<td align="left">CALL_ISINSTANCE</td>
<td align="right">21,457,320</td>
<td align="right">6.6%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_MODULE</td>
<td align="right">13,616,780</td>
<td align="right">4.2%</td>
</tr>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">13,171,037</td>
<td align="right">4.0%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_METHOD_NO_DICT</td>
<td align="right">4,925,300</td>
<td align="right">1.5%</td>
</tr>
</tbody>
</table>


</details>

### LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES

<details>
<summary> Successors and predecessors for LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES </summary>

<table>
<thead>
<tr>
<th align="left">Predecessors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">147,755,277</td>
<td align="right">89.2%</td>
</tr>
<tr>
<td align="left">LOAD_FAST_LOAD_FAST</td>
<td align="right">16,649,608</td>
<td align="right">10.1%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES</td>
<td align="right">756,100</td>
<td align="right">0.5%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_INSTANCE_VALUE</td>
<td align="right">165,360</td>
<td align="right">0.1%</td>
</tr>
<tr>
<td align="left">STORE_FAST_LOAD_FAST</td>
<td align="right">148,360</td>
<td align="right">0.1%</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Successors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">LOAD_FAST_LOAD_FAST</td>
<td align="right">55,224,000</td>
<td align="right">33.4%</td>
</tr>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">27,479,197</td>
<td align="right">16.6%</td>
</tr>
<tr>
<td align="left">LOAD_GLOBAL_BUILTIN</td>
<td align="right">24,723,200</td>
<td align="right">14.9%</td>
</tr>
<tr>
<td align="left">BINARY_OP</td>
<td align="right">12,874,920</td>
<td align="right">7.8%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_METHOD_NO_DICT</td>
<td align="right">8,944,380</td>
<td align="right">5.4%</td>
</tr>
</tbody>
</table>


</details>

### LOAD_ATTR_WITH_HINT

<details>
<summary> Successors and predecessors for LOAD_ATTR_WITH_HINT </summary>

<table>
<thead>
<tr>
<th align="left">Predecessors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">215,079,026</td>
<td align="right">82.2%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_WITH_HINT</td>
<td align="right">17,832,540</td>
<td align="right">6.8%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_INSTANCE_VALUE</td>
<td align="right">13,668,526</td>
<td align="right">5.2%</td>
</tr>
<tr>
<td align="left">COPY</td>
<td align="right">12,969,540</td>
<td align="right">5.0%</td>
</tr>
<tr>
<td align="left">LOAD_FAST_LOAD_FAST</td>
<td align="right">1,275,600</td>
<td align="right">0.5%</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Successors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">74,164,260</td>
<td align="right">28.3%</td>
</tr>
<tr>
<td align="left">STORE_FAST</td>
<td align="right">41,838,480</td>
<td align="right">16.0%</td>
</tr>
<tr>
<td align="left">COMPARE_OP_INT</td>
<td align="right">33,678,720</td>
<td align="right">12.9%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_METHOD_WITH_VALUES</td>
<td align="right">23,298,684</td>
<td align="right">8.9%</td>
</tr>
<tr>
<td align="left">LOAD_CONST</td>
<td align="right">19,679,580</td>
<td align="right">7.5%</td>
</tr>
</tbody>
</table>


</details>

### LOAD_GLOBAL_BUILTIN

<details>
<summary> Successors and predecessors for LOAD_GLOBAL_BUILTIN </summary>

<table>
<thead>
<tr>
<th align="left">Predecessors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">891,306,946</td>
<td align="right">26.5%</td>
</tr>
<tr>
<td align="left">POP_JUMP_IF_FALSE</td>
<td align="right">804,789,313</td>
<td align="right">24.0%</td>
</tr>
<tr>
<td align="left">RESUME_CHECK</td>
<td align="right">711,437,670</td>
<td align="right">21.2%</td>
</tr>
<tr>
<td align="left">STORE_FAST</td>
<td align="right">472,311,722</td>
<td align="right">14.1%</td>
</tr>
<tr>
<td align="left">POP_JUMP_IF_TRUE</td>
<td align="right">84,209,236</td>
<td align="right">2.5%</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Successors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">2,265,411,514</td>
<td align="right">67.5%</td>
</tr>
<tr>
<td align="left">CALL_BUILTIN_FAST</td>
<td align="right">434,497,240</td>
<td align="right">12.9%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR</td>
<td align="right">220,580,892</td>
<td align="right">6.6%</td>
</tr>
<tr>
<td align="left">CALL_ISINSTANCE</td>
<td align="right">155,809,690</td>
<td align="right">4.6%</td>
</tr>
<tr>
<td align="left">LOAD_FAST_LOAD_FAST</td>
<td align="right">123,831,245</td>
<td align="right">3.7%</td>
</tr>
</tbody>
</table>


</details>

### LOAD_GLOBAL_MODULE

<details>
<summary> Successors and predecessors for LOAD_GLOBAL_MODULE </summary>

<table>
<thead>
<tr>
<th align="left">Predecessors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">696,099,725</td>
<td align="right">33.2%</td>
</tr>
<tr>
<td align="left">RESUME_CHECK</td>
<td align="right">238,269,101</td>
<td align="right">11.4%</td>
</tr>
<tr>
<td align="left">STORE_FAST</td>
<td align="right">200,926,793</td>
<td align="right">9.6%</td>
</tr>
<tr>
<td align="left">POP_JUMP_IF_FALSE</td>
<td align="right">192,419,249</td>
<td align="right">9.2%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_METHOD_WITH_VALUES</td>
<td align="right">89,991,374</td>
<td align="right">4.3%</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Successors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">419,478,423</td>
<td align="right">20.0%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_MODULE</td>
<td align="right">312,298,509</td>
<td align="right">14.9%</td>
</tr>
<tr>
<td align="left">CONTAINS_OP_SET</td>
<td align="right">257,599,440</td>
<td align="right">12.3%</td>
</tr>
<tr>
<td align="left">CALL_ISINSTANCE</td>
<td align="right">186,718,011</td>
<td align="right">8.9%</td>
</tr>
<tr>
<td align="left">LOAD_FAST_LOAD_FAST</td>
<td align="right">165,451,466</td>
<td align="right">7.9%</td>
</tr>
</tbody>
</table>


</details>

### RESUME_CHECK

<details>
<summary> Successors and predecessors for RESUME_CHECK </summary>

<table>
<thead>
<tr>
<th align="left">Predecessors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">CALL_PY_EXACT_ARGS</td>
<td align="right">1,948,094,871</td>
<td align="right">44.4%</td>
</tr>
<tr>
<td align="left">CACHE</td>
<td align="right">999,657,217</td>
<td align="right">22.8%</td>
</tr>
<tr>
<td align="left">SEND_GEN</td>
<td align="right">383,241,200</td>
<td align="right">8.7%</td>
</tr>
<tr>
<td align="left">CALL_PY_GENERAL</td>
<td align="right">257,260,491</td>
<td align="right">5.9%</td>
</tr>
<tr>
<td align="left">POP_TOP</td>
<td align="right">230,564,512</td>
<td align="right">5.3%</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Successors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">1,806,183,265</td>
<td align="right">41.1%</td>
</tr>
<tr>
<td align="left">LOAD_GLOBAL_BUILTIN</td>
<td align="right">711,437,670</td>
<td align="right">16.2%</td>
</tr>
<tr>
<td align="left">POP_TOP</td>
<td align="right">562,987,632</td>
<td align="right">12.8%</td>
</tr>
<tr>
<td align="left">JUMP_BACKWARD_NO_INTERRUPT</td>
<td align="right">388,886,240</td>
<td align="right">8.9%</td>
</tr>
<tr>
<td align="left">LOAD_GLOBAL_MODULE</td>
<td align="right">238,269,101</td>
<td align="right">5.4%</td>
</tr>
</tbody>
</table>


</details>

### STORE_ATTR_INSTANCE_VALUE

<details>
<summary> Successors and predecessors for STORE_ATTR_INSTANCE_VALUE </summary>

<table>
<thead>
<tr>
<th align="left">Predecessors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">LOAD_FAST_LOAD_FAST</td>
<td align="right">314,248,145</td>
<td align="right">45.7%</td>
</tr>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">278,768,917</td>
<td align="right">40.5%</td>
</tr>
<tr>
<td align="left">SWAP</td>
<td align="right">64,819,575</td>
<td align="right">9.4%</td>
</tr>
<tr>
<td align="left">RETURN_VALUE</td>
<td align="right">20,943,360</td>
<td align="right">3.0%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_INSTANCE_VALUE</td>
<td align="right">7,356,020</td>
<td align="right">1.1%</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Successors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">322,762,067</td>
<td align="right">46.9%</td>
</tr>
<tr>
<td align="left">RETURN_CONST</td>
<td align="right">129,475,217</td>
<td align="right">18.8%</td>
</tr>
<tr>
<td align="left">LOAD_FAST_LOAD_FAST</td>
<td align="right">125,794,211</td>
<td align="right">18.3%</td>
</tr>
<tr>
<td align="left">LOAD_CONST</td>
<td align="right">38,231,880</td>
<td align="right">5.6%</td>
</tr>
<tr>
<td align="left">NOP</td>
<td align="right">25,256,481</td>
<td align="right">3.7%</td>
</tr>
</tbody>
</table>


</details>

### STORE_SUBSCR_DICT

<details>
<summary> Successors and predecessors for STORE_SUBSCR_DICT </summary>

<table>
<thead>
<tr>
<th align="left">Predecessors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">LOAD_FAST_LOAD_FAST</td>
<td align="right">89,951,494</td>
<td align="right">51.7%</td>
</tr>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">44,909,403</td>
<td align="right">25.8%</td>
</tr>
<tr>
<td align="left">CALL_BUILTIN_O</td>
<td align="right">13,999,260</td>
<td align="right">8.0%</td>
</tr>
<tr>
<td align="left">RETURN_VALUE</td>
<td align="right">8,030,300</td>
<td align="right">4.6%</td>
</tr>
<tr>
<td align="left">BINARY_SUBSCR_TUPLE_INT</td>
<td align="right">3,815,040</td>
<td align="right">2.2%</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Successors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">LOAD_CONST</td>
<td align="right">72,921,497</td>
<td align="right">41.9%</td>
</tr>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">45,849,233</td>
<td align="right">26.3%</td>
</tr>
<tr>
<td align="left">JUMP_BACKWARD</td>
<td align="right">28,579,854</td>
<td align="right">16.4%</td>
</tr>
<tr>
<td align="left">RETURN_CONST</td>
<td align="right">15,346,817</td>
<td align="right">8.8%</td>
</tr>
<tr>
<td align="left">LOAD_GLOBAL_MODULE</td>
<td align="right">7,348,431</td>
<td align="right">4.2%</td>
</tr>
</tbody>
</table>


</details>

### TO_BOOL_BOOL

<details>
<summary> Successors and predecessors for TO_BOOL_BOOL </summary>

<table>
<thead>
<tr>
<th align="left">Predecessors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">647,340,855</td>
<td align="right">23.1%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_INSTANCE_VALUE</td>
<td align="right">554,867,282</td>
<td align="right">19.8%</td>
</tr>
<tr>
<td align="left">CALL_BUILTIN_FAST</td>
<td align="right">486,880,685</td>
<td align="right">17.4%</td>
</tr>
<tr>
<td align="left">CALL_ISINSTANCE</td>
<td align="right">440,159,402</td>
<td align="right">15.7%</td>
</tr>
<tr>
<td align="left">RETURN_VALUE</td>
<td align="right">234,731,401</td>
<td align="right">8.4%</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Successors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">POP_JUMP_IF_FALSE</td>
<td align="right">2,061,270,943</td>
<td align="right">73.7%</td>
</tr>
<tr>
<td align="left">POP_JUMP_IF_TRUE</td>
<td align="right">636,796,062</td>
<td align="right">22.8%</td>
</tr>
<tr>
<td align="left">EXTENDED_ARG</td>
<td align="right">78,443,242</td>
<td align="right">2.8%</td>
</tr>
<tr>
<td align="left">UNARY_NOT</td>
<td align="right">21,441,612</td>
<td align="right">0.8%</td>
</tr>
<tr>
<td align="left">TO_BOOL_INT</td>
<td align="right">12,960</td>
<td align="right">0.0%</td>
</tr>
</tbody>
</table>


</details>

### TO_BOOL_INT

<details>
<summary> Successors and predecessors for TO_BOOL_INT </summary>

<table>
<thead>
<tr>
<th align="left">Predecessors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">156,919,027</td>
<td align="right">76.6%</td>
</tr>
<tr>
<td align="left">CALL_BUILTIN_O</td>
<td align="right">12,835,620</td>
<td align="right">6.3%</td>
</tr>
<tr>
<td align="left">COPY</td>
<td align="right">8,915,688</td>
<td align="right">4.4%</td>
</tr>
<tr>
<td align="left">BINARY_OP</td>
<td align="right">7,147,344</td>
<td align="right">3.5%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_SLOT</td>
<td align="right">6,823,340</td>
<td align="right">3.3%</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Successors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">POP_JUMP_IF_FALSE</td>
<td align="right">171,687,933</td>
<td align="right">83.8%</td>
</tr>
<tr>
<td align="left">POP_JUMP_IF_TRUE</td>
<td align="right">32,000,391</td>
<td align="right">15.6%</td>
</tr>
<tr>
<td align="left">UNARY_NOT</td>
<td align="right">931,560</td>
<td align="right">0.5%</td>
</tr>
<tr>
<td align="left">EXTENDED_ARG</td>
<td align="right">164,040</td>
<td align="right">0.1%</td>
</tr>
<tr>
<td align="left">TO_BOOL_BOOL</td>
<td align="right">12,960</td>
<td align="right">0.0%</td>
</tr>
</tbody>
</table>


</details>

### TO_BOOL_NONE

<details>
<summary> Successors and predecessors for TO_BOOL_NONE </summary>

<table>
<thead>
<tr>
<th align="left">Predecessors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">124,797,290</td>
<td align="right">36.3%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_INSTANCE_VALUE</td>
<td align="right">87,715,980</td>
<td align="right">25.5%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_SLOT</td>
<td align="right">75,190,202</td>
<td align="right">21.9%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR</td>
<td align="right">23,653,500</td>
<td align="right">6.9%</td>
</tr>
<tr>
<td align="left">RETURN_CONST</td>
<td align="right">13,885,580</td>
<td align="right">4.0%</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Successors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">POP_JUMP_IF_FALSE</td>
<td align="right">313,878,458</td>
<td align="right">91.3%</td>
</tr>
<tr>
<td align="left">POP_JUMP_IF_TRUE</td>
<td align="right">28,887,008</td>
<td align="right">8.4%</td>
</tr>
<tr>
<td align="left">EXTENDED_ARG</td>
<td align="right">453,800</td>
<td align="right">0.1%</td>
</tr>
<tr>
<td align="left">TO_BOOL_ALWAYS_TRUE</td>
<td align="right">366,140</td>
<td align="right">0.1%</td>
</tr>
<tr>
<td align="left">TO_BOOL</td>
<td align="right">56,500</td>
<td align="right">0.0%</td>
</tr>
</tbody>
</table>


</details>

### TO_BOOL_STR

<details>
<summary> Successors and predecessors for TO_BOOL_STR </summary>

<table>
<thead>
<tr>
<th align="left">Predecessors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">40,826,797</td>
<td align="right">70.0%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_SLOT</td>
<td align="right">6,813,060</td>
<td align="right">11.7%</td>
</tr>
<tr>
<td align="left">CALL_METHOD_DESCRIPTOR_FAST</td>
<td align="right">3,814,380</td>
<td align="right">6.5%</td>
</tr>
<tr>
<td align="left">COPY</td>
<td align="right">2,856,217</td>
<td align="right">4.9%</td>
</tr>
<tr>
<td align="left">LOAD_GLOBAL_MODULE</td>
<td align="right">2,457,600</td>
<td align="right">4.2%</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Successors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">POP_JUMP_IF_TRUE</td>
<td align="right">30,034,057</td>
<td align="right">51.5%</td>
</tr>
<tr>
<td align="left">POP_JUMP_IF_FALSE</td>
<td align="right">27,921,377</td>
<td align="right">47.9%</td>
</tr>
<tr>
<td align="left">UNARY_NOT</td>
<td align="right">323,040</td>
<td align="right">0.6%</td>
</tr>
<tr>
<td align="left">TO_BOOL_NONE</td>
<td align="right">33,000</td>
<td align="right">0.1%</td>
</tr>
<tr>
<td align="left">TO_BOOL</td>
<td align="right">12,000</td>
<td align="right">0.0%</td>
</tr>
</tbody>
</table>


</details>

### UNPACK_SEQUENCE_TWO_TUPLE

<details>
<summary> Successors and predecessors for UNPACK_SEQUENCE_TWO_TUPLE </summary>

<table>
<thead>
<tr>
<th align="left">Predecessors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">FOR_ITER_LIST</td>
<td align="right">287,912,670</td>
<td align="right">51.3%</td>
</tr>
<tr>
<td align="left">FOR_ITER</td>
<td align="right">193,134,633</td>
<td align="right">34.4%</td>
</tr>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">36,675,586</td>
<td align="right">6.5%</td>
</tr>
<tr>
<td align="left">RETURN_VALUE</td>
<td align="right">31,388,633</td>
<td align="right">5.6%</td>
</tr>
<tr>
<td align="left">BINARY_SUBSCR_LIST_INT</td>
<td align="right">5,830,096</td>
<td align="right">1.0%</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Successors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">STORE_FAST_STORE_FAST</td>
<td align="right">329,513,940</td>
<td align="right">58.7%</td>
</tr>
<tr>
<td align="left">STORE_FAST</td>
<td align="right">215,348,976</td>
<td align="right">38.4%</td>
</tr>
<tr>
<td align="left">UNPACK_SEQUENCE_TUPLE</td>
<td align="right">12,001,200</td>
<td align="right">2.1%</td>
</tr>
<tr>
<td align="left">STORE_DEREF</td>
<td align="right">3,356,640</td>
<td align="right">0.6%</td>
</tr>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">720,600</td>
<td align="right">0.1%</td>
</tr>
</tbody>
</table>


</details>

### BINARY_OP_ADD_FLOAT

<details>
<summary> Successors and predecessors for BINARY_OP_ADD_FLOAT </summary>

<table>
<thead>
<tr>
<th align="left">Predecessors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">BINARY_OP_MULTIPLY_FLOAT</td>
<td align="right">301,743,300</td>
<td align="right">73.6%</td>
</tr>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">64,853,696</td>
<td align="right">15.8%</td>
</tr>
<tr>
<td align="left">RETURN_VALUE</td>
<td align="right">17,287,200</td>
<td align="right">4.2%</td>
</tr>
<tr>
<td align="left">BINARY_OP_MULTIPLY_INT</td>
<td align="right">8,437,640</td>
<td align="right">2.1%</td>
</tr>
<tr>
<td align="left">BINARY_OP</td>
<td align="right">7,899,100</td>
<td align="right">1.9%</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Successors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">SWAP</td>
<td align="right">116,640,000</td>
<td align="right">28.4%</td>
</tr>
<tr>
<td align="left">STORE_FAST</td>
<td align="right">115,354,417</td>
<td align="right">28.1%</td>
</tr>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">68,482,680</td>
<td align="right">16.7%</td>
</tr>
<tr>
<td align="left">RETURN_VALUE</td>
<td align="right">31,350,960</td>
<td align="right">7.6%</td>
</tr>
<tr>
<td align="left">LOAD_FAST_LOAD_FAST</td>
<td align="right">29,370,480</td>
<td align="right">7.2%</td>
</tr>
</tbody>
</table>


</details>

### BINARY_OP_MULTIPLY_FLOAT

<details>
<summary> Successors and predecessors for BINARY_OP_MULTIPLY_FLOAT </summary>

<table>
<thead>
<tr>
<th align="left">Predecessors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">560,637,880</td>
<td align="right">64.1%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_INSTANCE_VALUE</td>
<td align="right">119,363,280</td>
<td align="right">13.6%</td>
</tr>
<tr>
<td align="left">LOAD_FAST_LOAD_FAST</td>
<td align="right">71,527,020</td>
<td align="right">8.2%</td>
</tr>
<tr>
<td align="left">BINARY_SUBSCR</td>
<td align="right">67,701,000</td>
<td align="right">7.7%</td>
</tr>
<tr>
<td align="left">CALL_BUILTIN_CLASS</td>
<td align="right">24,782,880</td>
<td align="right">2.8%</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Successors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">BINARY_OP_ADD_FLOAT</td>
<td align="right">301,743,300</td>
<td align="right">34.5%</td>
</tr>
<tr>
<td align="left">YIELD_VALUE</td>
<td align="right">210,931,680</td>
<td align="right">24.1%</td>
</tr>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">122,666,580</td>
<td align="right">14.0%</td>
</tr>
<tr>
<td align="left">BINARY_OP_SUBTRACT_FLOAT</td>
<td align="right">109,285,680</td>
<td align="right">12.5%</td>
</tr>
<tr>
<td align="left">LOAD_FAST_LOAD_FAST</td>
<td align="right">41,721,880</td>
<td align="right">4.8%</td>
</tr>
</tbody>
</table>


</details>

### BINARY_OP_MULTIPLY_INT

<details>
<summary> Successors and predecessors for BINARY_OP_MULTIPLY_INT </summary>

<table>
<thead>
<tr>
<th align="left">Predecessors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">BINARY_OP_ADD_INT</td>
<td align="right">95,863,620</td>
<td align="right">35.8%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_INSTANCE_VALUE</td>
<td align="right">50,750,400</td>
<td align="right">19.0%</td>
</tr>
<tr>
<td align="left">LOAD_FAST_LOAD_FAST</td>
<td align="right">44,982,646</td>
<td align="right">16.8%</td>
</tr>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">40,220,980</td>
<td align="right">15.0%</td>
</tr>
<tr>
<td align="left">BINARY_OP</td>
<td align="right">27,332,760</td>
<td align="right">10.2%</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Successors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">LOAD_CONST</td>
<td align="right">62,918,880</td>
<td align="right">23.5%</td>
</tr>
<tr>
<td align="left">STORE_FAST</td>
<td align="right">62,292,746</td>
<td align="right">23.3%</td>
</tr>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">46,732,980</td>
<td align="right">17.5%</td>
</tr>
<tr>
<td align="left">LOAD_FAST_LOAD_FAST</td>
<td align="right">28,380,780</td>
<td align="right">10.6%</td>
</tr>
<tr>
<td align="left">BINARY_OP_ADD_INT</td>
<td align="right">23,324,460</td>
<td align="right">8.7%</td>
</tr>
</tbody>
</table>


</details>

### SWAP

<details>
<summary> Successors and predecessors for SWAP </summary>

<table>
<thead>
<tr>
<th align="left">Predecessors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">SWAP</td>
<td align="right">269,772,840</td>
<td align="right">31.8%</td>
</tr>
<tr>
<td align="left">BINARY_OP_ADD_FLOAT</td>
<td align="right">116,640,000</td>
<td align="right">13.7%</td>
</tr>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">85,592,535</td>
<td align="right">10.1%</td>
</tr>
<tr>
<td align="left">BINARY_OP_ADD_INT</td>
<td align="right">74,870,001</td>
<td align="right">8.8%</td>
</tr>
<tr>
<td align="left">BINARY_OP_SUBTRACT_INT</td>
<td align="right">67,799,988</td>
<td align="right">8.0%</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Successors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">SWAP</td>
<td align="right">269,772,840</td>
<td align="right">31.8%</td>
</tr>
<tr>
<td align="left">STORE_SUBSCR_LIST_INT</td>
<td align="right">159,175,780</td>
<td align="right">18.7%</td>
</tr>
<tr>
<td align="left">STORE_SUBSCR</td>
<td align="right">109,360,580</td>
<td align="right">12.9%</td>
</tr>
<tr>
<td align="left">COPY</td>
<td align="right">103,030,020</td>
<td align="right">12.1%</td>
</tr>
<tr>
<td align="left">STORE_ATTR_INSTANCE_VALUE</td>
<td align="right">64,819,575</td>
<td align="right">7.6%</td>
</tr>
</tbody>
</table>


</details>

### RESUME

<details>
<summary> Successors and predecessors for RESUME </summary>

<table>
<thead>
<tr>
<th align="left">Predecessors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">CACHE</td>
<td align="right">58,273,022</td>
<td align="right">100.0%</td>
</tr>
<tr>
<td align="left">CALL_PY_EXACT_ARGS</td>
<td align="right">2,061</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">INSTRUMENTED_RESUME</td>
<td align="right">300</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">CALL_BOUND_METHOD_EXACT_ARGS</td>
<td align="right">240</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">CALL_FUNCTION_EX</td>
<td align="right">60</td>
<td align="right">0.0%</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Successors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">LOAD_GLOBAL_MODULE</td>
<td align="right">58,269,560</td>
<td align="right">100.0%</td>
</tr>
<tr>
<td align="left">RETURN_CONST</td>
<td align="right">3,420</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">1,391</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">LOAD_CONST</td>
<td align="right">670</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">LOAD_NAME</td>
<td align="right">360</td>
<td align="right">0.0%</td>
</tr>
</tbody>
</table>


</details>

### BINARY_SUBSCR_LIST_INT

<details>
<summary> Successors and predecessors for BINARY_SUBSCR_LIST_INT </summary>

<table>
<thead>
<tr>
<th align="left">Predecessors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">206,056,961</td>
<td align="right">24.0%</td>
</tr>
<tr>
<td align="left">LOAD_CONST</td>
<td align="right">176,459,558</td>
<td align="right">20.5%</td>
</tr>
<tr>
<td align="left">LOAD_FAST_LOAD_FAST</td>
<td align="right">164,423,862</td>
<td align="right">19.1%</td>
</tr>
<tr>
<td align="left">COPY</td>
<td align="right">159,175,780</td>
<td align="right">18.5%</td>
</tr>
<tr>
<td align="left">BINARY_OP</td>
<td align="right">96,694,080</td>
<td align="right">11.2%</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Successors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">STORE_FAST</td>
<td align="right">212,252,984</td>
<td align="right">24.7%</td>
</tr>
<tr>
<td align="left">LOAD_CONST</td>
<td align="right">201,875,400</td>
<td align="right">23.5%</td>
</tr>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">155,311,860</td>
<td align="right">18.1%</td>
</tr>
<tr>
<td align="left">RETURN_VALUE</td>
<td align="right">90,768,407</td>
<td align="right">10.6%</td>
</tr>
<tr>
<td align="left">BINARY_OP</td>
<td align="right">65,379,191</td>
<td align="right">7.6%</td>
</tr>
</tbody>
</table>


</details>

### COMPARE_OP_FLOAT

<details>
<summary> Successors and predecessors for COMPARE_OP_FLOAT </summary>

<table>
<thead>
<tr>
<th align="left">Predecessors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">LOAD_ATTR_SLOT</td>
<td align="right">65,985,075</td>
<td align="right">56.3%</td>
</tr>
<tr>
<td align="left">BINARY_SUBSCR</td>
<td align="right">23,382,660</td>
<td align="right">20.0%</td>
</tr>
<tr>
<td align="left">LOAD_CONST</td>
<td align="right">12,000,000</td>
<td align="right">10.2%</td>
</tr>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">5,995,721</td>
<td align="right">5.1%</td>
</tr>
<tr>
<td align="left">LOAD_GLOBAL_MODULE</td>
<td align="right">3,632,195</td>
<td align="right">3.1%</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Successors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">RETURN_VALUE</td>
<td align="right">47,985,335</td>
<td align="right">40.9%</td>
</tr>
<tr>
<td align="left">POP_JUMP_IF_TRUE</td>
<td align="right">38,440,740</td>
<td align="right">32.8%</td>
</tr>
<tr>
<td align="left">POP_JUMP_IF_FALSE</td>
<td align="right">30,770,976</td>
<td align="right">26.3%</td>
</tr>
<tr>
<td align="left">COMPARE_OP</td>
<td align="right">380</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">EXTENDED_ARG</td>
<td align="right">60</td>
<td align="right">0.0%</td>
</tr>
</tbody>
</table>


</details>

### LOAD_ATTR_SLOT

<details>
<summary> Successors and predecessors for LOAD_ATTR_SLOT </summary>

<table>
<thead>
<tr>
<th align="left">Predecessors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">935,069,227</td>
<td align="right">86.3%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR</td>
<td align="right">80,213,757</td>
<td align="right">7.4%</td>
</tr>
<tr>
<td align="left">COPY</td>
<td align="right">40,131,480</td>
<td align="right">3.7%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_SLOT</td>
<td align="right">14,975,703</td>
<td align="right">1.4%</td>
</tr>
<tr>
<td align="left">LOAD_DEREF</td>
<td align="right">6,990,480</td>
<td align="right">0.6%</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Successors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">277,441,646</td>
<td align="right">25.6%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR</td>
<td align="right">83,426,225</td>
<td align="right">7.7%</td>
</tr>
<tr>
<td align="left">TO_BOOL_NONE</td>
<td align="right">75,190,202</td>
<td align="right">6.9%</td>
</tr>
<tr>
<td align="left">COMPARE_OP_FLOAT</td>
<td align="right">65,985,075</td>
<td align="right">6.1%</td>
</tr>
<tr>
<td align="left">CONTAINS_OP</td>
<td align="right">58,268,820</td>
<td align="right">5.4%</td>
</tr>
</tbody>
</table>


</details>

### STORE_ATTR_SLOT

<details>
<summary> Successors and predecessors for STORE_ATTR_SLOT </summary>

<table>
<thead>
<tr>
<th align="left">Predecessors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">LOAD_FAST_LOAD_FAST</td>
<td align="right">285,584,104</td>
<td align="right">52.3%</td>
</tr>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">220,355,679</td>
<td align="right">40.3%</td>
</tr>
<tr>
<td align="left">SWAP</td>
<td align="right">40,131,480</td>
<td align="right">7.3%</td>
</tr>
<tr>
<td align="left">STORE_ATTR_SLOT</td>
<td align="right">269,342</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">LOAD_DEREF</td>
<td align="right">25,140</td>
<td align="right">0.0%</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Successors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">163,818,099</td>
<td align="right">30.0%</td>
</tr>
<tr>
<td align="left">LOAD_FAST_LOAD_FAST</td>
<td align="right">142,813,689</td>
<td align="right">26.1%</td>
</tr>
<tr>
<td align="left">RETURN_CONST</td>
<td align="right">141,703,881</td>
<td align="right">25.9%</td>
</tr>
<tr>
<td align="left">LOAD_CONST</td>
<td align="right">87,692,762</td>
<td align="right">16.1%</td>
</tr>
<tr>
<td align="left">STORE_FAST</td>
<td align="right">6,000,000</td>
<td align="right">1.1%</td>
</tr>
</tbody>
</table>


</details>

### STORE_SUBSCR_LIST_INT

<details>
<summary> Successors and predecessors for STORE_SUBSCR_LIST_INT </summary>

<table>
<thead>
<tr>
<th align="left">Predecessors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">SWAP</td>
<td align="right">159,175,780</td>
<td align="right">58.9%</td>
</tr>
<tr>
<td align="left">LOAD_FAST_LOAD_FAST</td>
<td align="right">47,315,565</td>
<td align="right">17.5%</td>
</tr>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">26,430,825</td>
<td align="right">9.8%</td>
</tr>
<tr>
<td align="left">BINARY_SUBSCR_LIST_INT</td>
<td align="right">20,171,040</td>
<td align="right">7.5%</td>
</tr>
<tr>
<td align="left">BINARY_OP_SUBTRACT_INT</td>
<td align="right">16,239,000</td>
<td align="right">6.0%</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Successors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">JUMP_BACKWARD</td>
<td align="right">96,710,741</td>
<td align="right">35.8%</td>
</tr>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">89,159,180</td>
<td align="right">33.0%</td>
</tr>
<tr>
<td align="left">LOAD_FAST_LOAD_FAST</td>
<td align="right">78,883,709</td>
<td align="right">29.2%</td>
</tr>
<tr>
<td align="left">RETURN_CONST</td>
<td align="right">4,685,280</td>
<td align="right">1.7%</td>
</tr>
<tr>
<td align="left">LOAD_CONST</td>
<td align="right">590,940</td>
<td align="right">0.2%</td>
</tr>
</tbody>
</table>


</details>

### BEFORE_WITH

<details>
<summary> Successors and predecessors for BEFORE_WITH </summary>

<table>
<thead>
<tr>
<th align="left">Predecessors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">LOAD_ATTR_INSTANCE_VALUE</td>
<td align="right">6,049,077</td>
<td align="right">93.6%</td>
</tr>
<tr>
<td align="left">CALL_NON_PY_GENERAL</td>
<td align="right">244,380</td>
<td align="right">3.8%</td>
</tr>
<tr>
<td align="left">RETURN_VALUE</td>
<td align="right">86,840</td>
<td align="right">1.3%</td>
</tr>
<tr>
<td align="left">LOAD_GLOBAL_MODULE</td>
<td align="right">75,394</td>
<td align="right">1.2%</td>
</tr>
<tr>
<td align="left">CALL</td>
<td align="right">4,800</td>
<td align="right">0.1%</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Successors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">POP_TOP</td>
<td align="right">6,209,231</td>
<td align="right">96.1%</td>
</tr>
<tr>
<td align="left">STORE_FAST</td>
<td align="right">252,640</td>
<td align="right">3.9%</td>
</tr>
<tr>
<td align="left">UNPACK_SEQUENCE_TWO_TUPLE</td>
<td align="right">1,680</td>
<td align="right">0.0%</td>
</tr>
</tbody>
</table>


</details>

### CHECK_EXC_MATCH

<details>
<summary> Successors and predecessors for CHECK_EXC_MATCH </summary>

<table>
<thead>
<tr>
<th align="left">Predecessors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">LOAD_GLOBAL_BUILTIN</td>
<td align="right">10,614,623</td>
<td align="right">91.5%</td>
</tr>
<tr>
<td align="left">LOAD_GLOBAL_MODULE</td>
<td align="right">495,924</td>
<td align="right">4.3%</td>
</tr>
<tr>
<td align="left">BUILD_TUPLE</td>
<td align="right">446,988</td>
<td align="right">3.9%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_MODULE</td>
<td align="right">43,707</td>
<td align="right">0.4%</td>
</tr>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">1,200</td>
<td align="right">0.0%</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Successors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">POP_JUMP_IF_FALSE</td>
<td align="right">11,602,323</td>
<td align="right">100.0%</td>
</tr>
<tr>
<td align="left">EXTENDED_ARG</td>
<td align="right">120</td>
<td align="right">0.0%</td>
</tr>
</tbody>
</table>


</details>

### END_ASYNC_FOR

<details>
<summary> Successors and predecessors for END_ASYNC_FOR </summary>

<table>
<thead>
<tr>
<th align="left">Predecessors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">SEND</td>
<td align="right">6,000,000</td>
<td align="right">100.0%</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Successors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">JUMP_BACKWARD_NO_INTERRUPT</td>
<td align="right">3,932,100</td>
<td align="right">65.5%</td>
</tr>
<tr>
<td align="left">RETURN_CONST</td>
<td align="right">2,067,900</td>
<td align="right">34.5%</td>
</tr>
</tbody>
</table>


</details>

### END_SEND

<details>
<summary> Successors and predecessors for END_SEND </summary>

<table>
<thead>
<tr>
<th align="left">Predecessors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">SEND</td>
<td align="right">99,932,240</td>
<td align="right">48.8%</td>
</tr>
<tr>
<td align="left">RETURN_VALUE</td>
<td align="right">68,511,380</td>
<td align="right">33.5%</td>
</tr>
<tr>
<td align="left">RETURN_CONST</td>
<td align="right">36,223,980</td>
<td align="right">17.7%</td>
</tr>
<tr>
<td align="left">SEND_GEN</td>
<td align="right">6,400</td>
<td align="right">0.0%</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Successors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">STORE_FAST</td>
<td align="right">94,352,760</td>
<td align="right">46.1%</td>
</tr>
<tr>
<td align="left">POP_TOP</td>
<td align="right">47,426,580</td>
<td align="right">23.2%</td>
</tr>
<tr>
<td align="left">BINARY_OP_ADD_INT</td>
<td align="right">29,134,080</td>
<td align="right">14.2%</td>
</tr>
<tr>
<td align="left">LOAD_GLOBAL_MODULE</td>
<td align="right">29,134,080</td>
<td align="right">14.2%</td>
</tr>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">3,215,880</td>
<td align="right">1.6%</td>
</tr>
</tbody>
</table>


</details>

### EXIT_INIT_CHECK

<details>
<summary> Successors and predecessors for EXIT_INIT_CHECK </summary>

<table>
<thead>
<tr>
<th align="left">Predecessors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">RETURN_CONST</td>
<td align="right">57,267,754</td>
<td align="right">100.0%</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Successors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">RETURN_VALUE</td>
<td align="right">57,267,754</td>
<td align="right">100.0%</td>
</tr>
</tbody>
</table>


</details>

### GET_AITER

<details>
<summary> Successors and predecessors for GET_AITER </summary>

<table>
<thead>
<tr>
<th align="left">Predecessors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">LOAD_ATTR_INSTANCE_VALUE</td>
<td align="right">5,999,940</td>
<td align="right">100.0%</td>
</tr>
<tr>
<td align="left">RETURN_VALUE</td>
<td align="right">60</td>
<td align="right">0.0%</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Successors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">GET_ANEXT</td>
<td align="right">6,000,000</td>
<td align="right">100.0%</td>
</tr>
</tbody>
</table>


</details>

### GET_ANEXT

<details>
<summary> Successors and predecessors for GET_ANEXT </summary>

<table>
<thead>
<tr>
<th align="left">Predecessors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">JUMP_BACKWARD</td>
<td align="right">94,136,760</td>
<td align="right">94.0%</td>
</tr>
<tr>
<td align="left">GET_AITER</td>
<td align="right">6,000,000</td>
<td align="right">6.0%</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Successors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">LOAD_CONST</td>
<td align="right">100,136,760</td>
<td align="right">100.0%</td>
</tr>
</tbody>
</table>


</details>

### POP_EXCEPT

<details>
<summary> Successors and predecessors for POP_EXCEPT </summary>

<table>
<thead>
<tr>
<th align="left">Predecessors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">POP_TOP</td>
<td align="right">5,820,397</td>
<td align="right">48.6%</td>
</tr>
<tr>
<td align="left">STORE_SUBSCR_DICT</td>
<td align="right">3,075,240</td>
<td align="right">25.7%</td>
</tr>
<tr>
<td align="left">SWAP</td>
<td align="right">1,375,010</td>
<td align="right">11.5%</td>
</tr>
<tr>
<td align="left">COPY</td>
<td align="right">960,721</td>
<td align="right">8.0%</td>
</tr>
<tr>
<td align="left">STORE_FAST</td>
<td align="right">551,372</td>
<td align="right">4.6%</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Successors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">RETURN_CONST</td>
<td align="right">7,082,166</td>
<td align="right">59.2%</td>
</tr>
<tr>
<td align="left">JUMP_FORWARD</td>
<td align="right">1,529,940</td>
<td align="right">12.8%</td>
</tr>
<tr>
<td align="left">RETURN_VALUE</td>
<td align="right">1,317,410</td>
<td align="right">11.0%</td>
</tr>
<tr>
<td align="left">RERAISE</td>
<td align="right">960,721</td>
<td align="right">8.0%</td>
</tr>
<tr>
<td align="left">EXTENDED_ARG</td>
<td align="right">706,860</td>
<td align="right">5.9%</td>
</tr>
</tbody>
</table>


</details>

### PUSH_EXC_INFO

<details>
<summary> Successors and predecessors for PUSH_EXC_INFO </summary>

<table>
<thead>
<tr>
<th align="left">Predecessors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">BINARY_SUBSCR_DICT</td>
<td align="right">5,015,587</td>
<td align="right">41.9%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR</td>
<td align="right">3,317,860</td>
<td align="right">27.7%</td>
</tr>
<tr>
<td align="left">RERAISE</td>
<td align="right">954,720</td>
<td align="right">8.0%</td>
</tr>
<tr>
<td align="left">RAISE_VARARGS</td>
<td align="right">894,444</td>
<td align="right">7.5%</td>
</tr>
<tr>
<td align="left">BINARY_SUBSCR_LIST_INT</td>
<td align="right">842,520</td>
<td align="right">7.0%</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Successors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">LOAD_GLOBAL_BUILTIN</td>
<td align="right">10,706,405</td>
<td align="right">89.4%</td>
</tr>
<tr>
<td align="left">LOAD_GLOBAL_MODULE</td>
<td align="right">870,211</td>
<td align="right">7.3%</td>
</tr>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">388,140</td>
<td align="right">3.2%</td>
</tr>
<tr>
<td align="left">WITH_EXCEPT_START</td>
<td align="right">4,800</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">LOAD_GLOBAL</td>
<td align="right">341</td>
<td align="right">0.0%</td>
</tr>
</tbody>
</table>


</details>

### RETURN_GENERATOR

<details>
<summary> Successors and predecessors for RETURN_GENERATOR </summary>

<table>
<thead>
<tr>
<th align="left">Predecessors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">CALL_PY_EXACT_ARGS</td>
<td align="right">134,486,429</td>
<td align="right">58.3%</td>
</tr>
<tr>
<td align="left">COPY_FREE_VARS</td>
<td align="right">60,925,203</td>
<td align="right">26.4%</td>
</tr>
<tr>
<td align="left">CACHE</td>
<td align="right">30,371,700</td>
<td align="right">13.2%</td>
</tr>
<tr>
<td align="left">CALL_PY_GENERAL</td>
<td align="right">3,454,200</td>
<td align="right">1.5%</td>
</tr>
<tr>
<td align="left">CALL_KW</td>
<td align="right">737,640</td>
<td align="right">0.3%</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Successors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">GET_AWAITABLE</td>
<td align="right">77,344,520</td>
<td align="right">33.5%</td>
</tr>
<tr>
<td align="left">CALL_BUILTIN_FAST_WITH_KEYWORDS</td>
<td align="right">48,222,060</td>
<td align="right">20.9%</td>
</tr>
<tr>
<td align="left">GET_ITER</td>
<td align="right">37,574,400</td>
<td align="right">16.3%</td>
</tr>
<tr>
<td align="left">INTERPRETER_EXIT</td>
<td align="right">30,381,000</td>
<td align="right">13.2%</td>
</tr>
<tr>
<td align="left">LIST_APPEND</td>
<td align="right">13,436,640</td>
<td align="right">5.8%</td>
</tr>
</tbody>
</table>


</details>

### UNARY_INVERT

<details>
<summary> Successors and predecessors for UNARY_INVERT </summary>

<table>
<thead>
<tr>
<th align="left">Predecessors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">BINARY_OP</td>
<td align="right">9,984,677</td>
<td align="right">96.1%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES</td>
<td align="right">252,108</td>
<td align="right">2.4%</td>
</tr>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">122,100</td>
<td align="right">1.2%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_MODULE</td>
<td align="right">27,360</td>
<td align="right">0.3%</td>
</tr>
<tr>
<td align="left">LOAD_FAST_LOAD_FAST</td>
<td align="right">8,820</td>
<td align="right">0.1%</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Successors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">BINARY_OP</td>
<td align="right">10,395,065</td>
<td align="right">100.0%</td>
</tr>
</tbody>
</table>


</details>

### UNARY_NOT

<details>
<summary> Successors and predecessors for UNARY_NOT </summary>

<table>
<thead>
<tr>
<th align="left">Predecessors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">TO_BOOL_BOOL</td>
<td align="right">21,441,612</td>
<td align="right">80.8%</td>
</tr>
<tr>
<td align="left">COMPARE_OP</td>
<td align="right">2,531,411</td>
<td align="right">9.5%</td>
</tr>
<tr>
<td align="left">TO_BOOL_LIST</td>
<td align="right">1,234,740</td>
<td align="right">4.7%</td>
</tr>
<tr>
<td align="left">TO_BOOL_INT</td>
<td align="right">931,560</td>
<td align="right">3.5%</td>
</tr>
<tr>
<td align="left">TO_BOOL_STR</td>
<td align="right">323,040</td>
<td align="right">1.2%</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Successors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">COPY</td>
<td align="right">15,051,566</td>
<td align="right">56.7%</td>
</tr>
<tr>
<td align="left">RETURN_VALUE</td>
<td align="right">8,929,239</td>
<td align="right">33.6%</td>
</tr>
<tr>
<td align="left">STORE_FAST</td>
<td align="right">1,003,990</td>
<td align="right">3.8%</td>
</tr>
<tr>
<td align="left">CALL_PY_EXACT_ARGS</td>
<td align="right">747,000</td>
<td align="right">2.8%</td>
</tr>
<tr>
<td align="left">BUILD_MAP</td>
<td align="right">551,040</td>
<td align="right">2.1%</td>
</tr>
</tbody>
</table>


</details>

### BUILD_SET

<details>
<summary> Successors and predecessors for BUILD_SET </summary>

<table>
<thead>
<tr>
<th align="left">Predecessors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">60,489</td>
<td align="right">68.0%</td>
</tr>
<tr>
<td align="left">SWAP</td>
<td align="right">18,360</td>
<td align="right">20.6%</td>
</tr>
<tr>
<td align="left">LOAD_GLOBAL_MODULE</td>
<td align="right">9,960</td>
<td align="right">11.2%</td>
</tr>
<tr>
<td align="left">JUMP_FORWARD</td>
<td align="right">120</td>
<td align="right">0.1%</td>
</tr>
<tr>
<td align="left">BINARY_OP</td>
<td align="right">60</td>
<td align="right">0.1%</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Successors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">LOAD_GLOBAL_BUILTIN</td>
<td align="right">36,600</td>
<td align="right">41.1%</td>
</tr>
<tr>
<td align="left">RETURN_VALUE</td>
<td align="right">23,889</td>
<td align="right">26.8%</td>
</tr>
<tr>
<td align="left">SWAP</td>
<td align="right">18,360</td>
<td align="right">20.6%</td>
</tr>
<tr>
<td align="left">CONTAINS_OP_SET</td>
<td align="right">9,000</td>
<td align="right">10.1%</td>
</tr>
<tr>
<td align="left">CALL_METHOD_DESCRIPTOR_FAST</td>
<td align="right">960</td>
<td align="right">1.1%</td>
</tr>
</tbody>
</table>


</details>

### GET_AWAITABLE

<details>
<summary> Successors and predecessors for GET_AWAITABLE </summary>

<table>
<thead>
<tr>
<th align="left">Predecessors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">RETURN_GENERATOR</td>
<td align="right">77,344,520</td>
<td align="right">93.1%</td>
</tr>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">3,296,880</td>
<td align="right">4.0%</td>
</tr>
<tr>
<td align="left">RETURN_VALUE</td>
<td align="right">2,446,440</td>
<td align="right">2.9%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_INSTANCE_VALUE</td>
<td align="right">9,000</td>
<td align="right">0.0%</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Successors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">LOAD_CONST</td>
<td align="right">83,096,840</td>
<td align="right">100.0%</td>
</tr>
</tbody>
</table>


</details>

### IS_OP

<details>
<summary> Successors and predecessors for IS_OP </summary>

<table>
<thead>
<tr>
<th align="left">Predecessors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">LOAD_ATTR</td>
<td align="right">228,852,189</td>
<td align="right">44.4%</td>
</tr>
<tr>
<td align="left">LOAD_GLOBAL_MODULE</td>
<td align="right">136,181,339</td>
<td align="right">26.4%</td>
</tr>
<tr>
<td align="left">LOAD_FAST_LOAD_FAST</td>
<td align="right">108,111,876</td>
<td align="right">21.0%</td>
</tr>
<tr>
<td align="left">LOAD_GLOBAL_BUILTIN</td>
<td align="right">15,682,649</td>
<td align="right">3.0%</td>
</tr>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">11,180,006</td>
<td align="right">2.2%</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Successors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">POP_JUMP_IF_FALSE</td>
<td align="right">448,130,871</td>
<td align="right">86.9%</td>
</tr>
<tr>
<td align="left">POP_JUMP_IF_TRUE</td>
<td align="right">35,050,897</td>
<td align="right">6.8%</td>
</tr>
<tr>
<td align="left">EXTENDED_ARG</td>
<td align="right">18,016,440</td>
<td align="right">3.5%</td>
</tr>
<tr>
<td align="left">YIELD_VALUE</td>
<td align="right">9,441,626</td>
<td align="right">1.8%</td>
</tr>
<tr>
<td align="left">STORE_FAST</td>
<td align="right">2,456,260</td>
<td align="right">0.5%</td>
</tr>
</tbody>
</table>


</details>

### JUMP_BACKWARD_NO_INTERRUPT

<details>
<summary> Successors and predecessors for JUMP_BACKWARD_NO_INTERRUPT </summary>

<table>
<thead>
<tr>
<th align="left">Predecessors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">RESUME_CHECK</td>
<td align="right">388,886,240</td>
<td align="right">98.9%</td>
</tr>
<tr>
<td align="left">END_ASYNC_FOR</td>
<td align="right">3,932,100</td>
<td align="right">1.0%</td>
</tr>
<tr>
<td align="left">POP_EXCEPT</td>
<td align="right">207,171</td>
<td align="right">0.1%</td>
</tr>
<tr>
<td align="left">EXTENDED_ARG</td>
<td align="right">88,164</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">DELETE_FAST</td>
<td align="right">60</td>
<td align="right">0.0%</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Successors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">SEND_GEN</td>
<td align="right">383,247,580</td>
<td align="right">97.5%</td>
</tr>
<tr>
<td align="left">SEND</td>
<td align="right">5,638,660</td>
<td align="right">1.4%</td>
</tr>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">4,069,990</td>
<td align="right">1.0%</td>
</tr>
<tr>
<td align="left">LOAD_GLOBAL_BUILTIN</td>
<td align="right">81,391</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">NOP</td>
<td align="right">34,932</td>
<td align="right">0.0%</td>
</tr>
</tbody>
</table>


</details>

### LOAD_FAST_AND_CLEAR

<details>
<summary> Successors and predecessors for LOAD_FAST_AND_CLEAR </summary>

<table>
<thead>
<tr>
<th align="left">Predecessors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">GET_ITER</td>
<td align="right">19,857,469</td>
<td align="right">56.1%</td>
</tr>
<tr>
<td align="left">LOAD_FAST_AND_CLEAR</td>
<td align="right">15,530,817</td>
<td align="right">43.9%</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Successors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">SWAP</td>
<td align="right">19,857,469</td>
<td align="right">56.1%</td>
</tr>
<tr>
<td align="left">LOAD_FAST_AND_CLEAR</td>
<td align="right">15,530,817</td>
<td align="right">43.9%</td>
</tr>
</tbody>
</table>


</details>

### RAISE_VARARGS

<details>
<summary> Successors and predecessors for RAISE_VARARGS </summary>

<table>
<thead>
<tr>
<th align="left">Predecessors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">LOAD_ATTR_MODULE</td>
<td align="right">583,740</td>
<td align="right">43.8%</td>
</tr>
<tr>
<td align="left">LOAD_GLOBAL_BUILTIN</td>
<td align="right">543,240</td>
<td align="right">40.7%</td>
</tr>
<tr>
<td align="left">CALL_NON_PY_GENERAL</td>
<td align="right">134,304</td>
<td align="right">10.1%</td>
</tr>
<tr>
<td align="left">POP_JUMP_IF_FALSE</td>
<td align="right">32,160</td>
<td align="right">2.4%</td>
</tr>
<tr>
<td align="left">LOAD_CONST</td>
<td align="right">17,040</td>
<td align="right">1.3%</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Successors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">PUSH_EXC_INFO</td>
<td align="right">894,444</td>
<td align="right">67.1%</td>
</tr>
<tr>
<td align="left">COPY</td>
<td align="right">437,460</td>
<td align="right">32.8%</td>
</tr>
<tr>
<td align="left">LOAD_CONST</td>
<td align="right">180</td>
<td align="right">0.0%</td>
</tr>
</tbody>
</table>


</details>

### RERAISE

<details>
<summary> Successors and predecessors for RERAISE </summary>

<table>
<thead>
<tr>
<th align="left">Predecessors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">POP_EXCEPT</td>
<td align="right">960,721</td>
<td align="right">64.7%</td>
</tr>
<tr>
<td align="left">POP_TOP</td>
<td align="right">386,940</td>
<td align="right">26.1%</td>
</tr>
<tr>
<td align="left">POP_JUMP_IF_FALSE</td>
<td align="right">122,700</td>
<td align="right">8.3%</td>
</tr>
<tr>
<td align="left">CALL_INTRINSIC_1</td>
<td align="right">9,480</td>
<td align="right">0.6%</td>
</tr>
<tr>
<td align="left">POP_JUMP_IF_TRUE</td>
<td align="right">4,800</td>
<td align="right">0.3%</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Successors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">PUSH_EXC_INFO</td>
<td align="right">954,720</td>
<td align="right">64.6%</td>
</tr>
<tr>
<td align="left">COPY</td>
<td align="right">514,621</td>
<td align="right">34.8%</td>
</tr>
<tr>
<td align="left">CALL_INTRINSIC_1</td>
<td align="right">9,000</td>
<td align="right">0.6%</td>
</tr>
</tbody>
</table>


</details>

### YIELD_VALUE

<details>
<summary> Successors and predecessors for YIELD_VALUE </summary>

<table>
<thead>
<tr>
<th align="left">Predecessors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">YIELD_VALUE</td>
<td align="right">383,262,128</td>
<td align="right">40.0%</td>
</tr>
<tr>
<td align="left">BINARY_OP_MULTIPLY_FLOAT</td>
<td align="right">210,931,680</td>
<td align="right">22.0%</td>
</tr>
<tr>
<td align="left">CALL_INTRINSIC_1</td>
<td align="right">94,136,760</td>
<td align="right">9.8%</td>
</tr>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">69,482,780</td>
<td align="right">7.3%</td>
</tr>
<tr>
<td align="left">BUILD_TUPLE</td>
<td align="right">31,496,880</td>
<td align="right">3.3%</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Successors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">INTERPRETER_EXIT</td>
<td align="right">468,395,685</td>
<td align="right">48.9%</td>
</tr>
<tr>
<td align="left">YIELD_VALUE</td>
<td align="right">383,262,128</td>
<td align="right">40.0%</td>
</tr>
<tr>
<td align="left">STORE_FAST</td>
<td align="right">77,157,889</td>
<td align="right">8.1%</td>
</tr>
<tr>
<td align="left">UNPACK_SEQUENCE_TUPLE</td>
<td align="right">24,808,480</td>
<td align="right">2.6%</td>
</tr>
<tr>
<td align="left">STORE_DEREF</td>
<td align="right">2,419,200</td>
<td align="right">0.3%</td>
</tr>
</tbody>
</table>


</details>

### BINARY_OP_SUBTRACT_INT

<details>
<summary> Successors and predecessors for BINARY_OP_SUBTRACT_INT </summary>

<table>
<thead>
<tr>
<th align="left">Predecessors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">LOAD_CONST</td>
<td align="right">360,967,114</td>
<td align="right">72.9%</td>
</tr>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">70,260,045</td>
<td align="right">14.2%</td>
</tr>
<tr>
<td align="left">LOAD_FAST_LOAD_FAST</td>
<td align="right">41,826,012</td>
<td align="right">8.4%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_INSTANCE_VALUE</td>
<td align="right">16,326,960</td>
<td align="right">3.3%</td>
</tr>
<tr>
<td align="left">CALL_LEN</td>
<td align="right">2,653,060</td>
<td align="right">0.5%</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Successors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">STORE_FAST</td>
<td align="right">106,577,909</td>
<td align="right">21.5%</td>
</tr>
<tr>
<td align="left">CALL_PY_EXACT_ARGS</td>
<td align="right">93,675,400</td>
<td align="right">18.9%</td>
</tr>
<tr>
<td align="left">SWAP</td>
<td align="right">67,799,988</td>
<td align="right">13.7%</td>
</tr>
<tr>
<td align="left">BINARY_OP</td>
<td align="right">44,597,089</td>
<td align="right">9.0%</td>
</tr>
<tr>
<td align="left">RETURN_VALUE</td>
<td align="right">39,936,480</td>
<td align="right">8.1%</td>
</tr>
</tbody>
</table>


</details>

### CALL_ALLOC_AND_ENTER_INIT

<details>
<summary> Successors and predecessors for CALL_ALLOC_AND_ENTER_INIT </summary>

<table>
<thead>
<tr>
<th align="left">Predecessors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">BINARY_OP</td>
<td align="right">20,510,360</td>
<td align="right">34.8%</td>
</tr>
<tr>
<td align="left">BINARY_OP_ADD_FLOAT</td>
<td align="right">9,000,000</td>
<td align="right">15.3%</td>
</tr>
<tr>
<td align="left">BINARY_OP_MULTIPLY_FLOAT</td>
<td align="right">8,978,540</td>
<td align="right">15.2%</td>
</tr>
<tr>
<td align="left">RETURN_CONST</td>
<td align="right">7,864,740</td>
<td align="right">13.3%</td>
</tr>
<tr>
<td align="left">RETURN_VALUE</td>
<td align="right">4,579,560</td>
<td align="right">7.8%</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Successors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">RESUME_CHECK</td>
<td align="right">55,943,674</td>
<td align="right">94.9%</td>
</tr>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">1,661,000</td>
<td align="right">2.8%</td>
</tr>
<tr>
<td align="left">COPY_FREE_VARS</td>
<td align="right">1,324,080</td>
<td align="right">2.2%</td>
</tr>
<tr>
<td align="left">CALL_ALLOC_AND_ENTER_INIT</td>
<td align="right">32,180</td>
<td align="right">0.1%</td>
</tr>
<tr>
<td align="left">STORE_FAST</td>
<td align="right">12,520</td>
<td align="right">0.0%</td>
</tr>
</tbody>
</table>


</details>

### CALL_BOUND_METHOD_GENERAL

<details>
<summary> Successors and predecessors for CALL_BOUND_METHOD_GENERAL </summary>

<table>
<thead>
<tr>
<th align="left">Predecessors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">6,064,632</td>
<td align="right">68.5%</td>
</tr>
<tr>
<td align="left">LOAD_CONST</td>
<td align="right">1,390,197</td>
<td align="right">15.7%</td>
</tr>
<tr>
<td align="left">BINARY_OP_ADD_INT</td>
<td align="right">600,000</td>
<td align="right">6.8%</td>
</tr>
<tr>
<td align="left">BINARY_SUBSCR_LIST_INT</td>
<td align="right">588,840</td>
<td align="right">6.6%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_INSTANCE_VALUE</td>
<td align="right">125,980</td>
<td align="right">1.4%</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Successors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">RESUME_CHECK</td>
<td align="right">7,453,692</td>
<td align="right">84.2%</td>
</tr>
<tr>
<td align="left">POP_TOP</td>
<td align="right">1,361,057</td>
<td align="right">15.4%</td>
</tr>
<tr>
<td align="left">CALL_BOUND_METHOD_GENERAL</td>
<td align="right">26,196</td>
<td align="right">0.3%</td>
</tr>
<tr>
<td align="left">COPY_FREE_VARS</td>
<td align="right">13,660</td>
<td align="right">0.2%</td>
</tr>
<tr>
<td align="left">CALL_BOUND_METHOD_EXACT_ARGS</td>
<td align="right">420</td>
<td align="right">0.0%</td>
</tr>
</tbody>
</table>


</details>

### CONTAINS_OP_SET

<details>
<summary> Successors and predecessors for CONTAINS_OP_SET </summary>

<table>
<thead>
<tr>
<th align="left">Predecessors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">LOAD_GLOBAL_MODULE</td>
<td align="right">257,599,440</td>
<td align="right">85.2%</td>
</tr>
<tr>
<td align="left">LOAD_FAST_LOAD_FAST</td>
<td align="right">36,794,840</td>
<td align="right">12.2%</td>
</tr>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">4,366,697</td>
<td align="right">1.4%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_INSTANCE_VALUE</td>
<td align="right">1,960,260</td>
<td align="right">0.6%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_NONDESCRIPTOR_NO_DICT</td>
<td align="right">1,305,420</td>
<td align="right">0.4%</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Successors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">POP_JUMP_IF_FALSE</td>
<td align="right">294,730,837</td>
<td align="right">97.5%</td>
</tr>
<tr>
<td align="left">EXTENDED_ARG</td>
<td align="right">2,850,960</td>
<td align="right">0.9%</td>
</tr>
<tr>
<td align="left">RETURN_VALUE</td>
<td align="right">1,993,800</td>
<td align="right">0.7%</td>
</tr>
<tr>
<td align="left">POP_JUMP_IF_TRUE</td>
<td align="right">1,860,600</td>
<td align="right">0.6%</td>
</tr>
<tr>
<td align="left">BINARY_OP</td>
<td align="right">865,320</td>
<td align="right">0.3%</td>
</tr>
</tbody>
</table>


</details>

### LOAD_ATTR_CLASS

<details>
<summary> Successors and predecessors for LOAD_ATTR_CLASS </summary>

<table>
<thead>
<tr>
<th align="left">Predecessors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">LOAD_GLOBAL_MODULE</td>
<td align="right">90,477,370</td>
<td align="right">98.5%</td>
</tr>
<tr>
<td align="left">LOAD_FAST_LOAD_FAST</td>
<td align="right">591,660</td>
<td align="right">0.6%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_MODULE</td>
<td align="right">358,500</td>
<td align="right">0.4%</td>
</tr>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">262,220</td>
<td align="right">0.3%</td>
</tr>
<tr>
<td align="left">LOAD_GLOBAL_BUILTIN</td>
<td align="right">132,480</td>
<td align="right">0.1%</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Successors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">COMPARE_OP_INT</td>
<td align="right">57,033,600</td>
<td align="right">62.1%</td>
</tr>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">22,046,214</td>
<td align="right">24.0%</td>
</tr>
<tr>
<td align="left">PUSH_NULL</td>
<td align="right">8,285,700</td>
<td align="right">9.0%</td>
</tr>
<tr>
<td align="left">TO_BOOL_BOOL</td>
<td align="right">1,698,720</td>
<td align="right">1.8%</td>
</tr>
<tr>
<td align="left">CONTAINS_OP_DICT</td>
<td align="right">1,151,100</td>
<td align="right">1.3%</td>
</tr>
</tbody>
</table>


</details>

### LOAD_ATTR_METHOD_LAZY_DICT

<details>
<summary> Successors and predecessors for LOAD_ATTR_METHOD_LAZY_DICT </summary>

<table>
<thead>
<tr>
<th align="left">Predecessors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">138,128,698</td>
<td align="right">77.9%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_INSTANCE_VALUE</td>
<td align="right">38,037,540</td>
<td align="right">21.5%</td>
</tr>
<tr>
<td align="left">LOAD_DEREF</td>
<td align="right">845,677</td>
<td align="right">0.5%</td>
</tr>
<tr>
<td align="left">CALL_NON_PY_GENERAL</td>
<td align="right">114,240</td>
<td align="right">0.1%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_METHOD_LAZY_DICT</td>
<td align="right">71,662</td>
<td align="right">0.0%</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Successors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">CALL_METHOD_DESCRIPTOR_NOARGS</td>
<td align="right">66,378,626</td>
<td align="right">37.5%</td>
</tr>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">65,460,021</td>
<td align="right">36.9%</td>
</tr>
<tr>
<td align="left">CALL_NON_PY_GENERAL</td>
<td align="right">27,296,234</td>
<td align="right">15.4%</td>
</tr>
<tr>
<td align="left">LOAD_CONST</td>
<td align="right">8,149,958</td>
<td align="right">4.6%</td>
</tr>
<tr>
<td align="left">LOAD_FAST_LOAD_FAST</td>
<td align="right">5,603,100</td>
<td align="right">3.2%</td>
</tr>
</tbody>
</table>


</details>

### LOAD_SUPER_ATTR_METHOD

<details>
<summary> Successors and predecessors for LOAD_SUPER_ATTR_METHOD </summary>

<table>
<thead>
<tr>
<th align="left">Predecessors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">43,530,941</td>
<td align="right">100.0%</td>
</tr>
<tr>
<td align="left">LOAD_DEREF</td>
<td align="right">9,000</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">LOAD_SUPER_ATTR</td>
<td align="right">840</td>
<td align="right">0.0%</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Successors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">33,158,280</td>
<td align="right">76.2%</td>
</tr>
<tr>
<td align="left">CALL_PY_EXACT_ARGS</td>
<td align="right">4,820,260</td>
<td align="right">11.1%</td>
</tr>
<tr>
<td align="left">LOAD_FAST_LOAD_FAST</td>
<td align="right">4,253,597</td>
<td align="right">9.8%</td>
</tr>
<tr>
<td align="left">CALL_NON_PY_GENERAL</td>
<td align="right">1,194,780</td>
<td align="right">2.7%</td>
</tr>
<tr>
<td align="left">LOAD_GLOBAL_MODULE</td>
<td align="right">104,344</td>
<td align="right">0.2%</td>
</tr>
</tbody>
</table>


</details>

### SEND_GEN

<details>
<summary> Successors and predecessors for SEND_GEN </summary>

<table>
<thead>
<tr>
<th align="left">Predecessors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">JUMP_BACKWARD_NO_INTERRUPT</td>
<td align="right">383,247,580</td>
<td align="right">78.5%</td>
</tr>
<tr>
<td align="left">LOAD_CONST</td>
<td align="right">104,763,788</td>
<td align="right">21.5%</td>
</tr>
<tr>
<td align="left">SEND</td>
<td align="right">260</td>
<td align="right">0.0%</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Successors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">RESUME_CHECK</td>
<td align="right">383,241,200</td>
<td align="right">78.5%</td>
</tr>
<tr>
<td align="left">POP_TOP</td>
<td align="right">104,757,408</td>
<td align="right">21.5%</td>
</tr>
<tr>
<td align="left">END_SEND</td>
<td align="right">6,400</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">YIELD_VALUE</td>
<td align="right">6,380</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">SEND</td>
<td align="right">240</td>
<td align="right">0.0%</td>
</tr>
</tbody>
</table>


</details>

### TO_BOOL_ALWAYS_TRUE

<details>
<summary> Successors and predecessors for TO_BOOL_ALWAYS_TRUE </summary>

<table>
<thead>
<tr>
<th align="left">Predecessors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">LOAD_ATTR_INSTANCE_VALUE</td>
<td align="right">67,616,960</td>
<td align="right">59.2%</td>
</tr>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">23,807,008</td>
<td align="right">20.8%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_SLOT</td>
<td align="right">13,422,560</td>
<td align="right">11.7%</td>
</tr>
<tr>
<td align="left">COPY</td>
<td align="right">6,550,684</td>
<td align="right">5.7%</td>
</tr>
<tr>
<td align="left">BINARY_SUBSCR_DICT</td>
<td align="right">1,032,000</td>
<td align="right">0.9%</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Successors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">POP_JUMP_IF_FALSE</td>
<td align="right">86,226,897</td>
<td align="right">75.5%</td>
</tr>
<tr>
<td align="left">POP_JUMP_IF_TRUE</td>
<td align="right">27,372,840</td>
<td align="right">24.0%</td>
</tr>
<tr>
<td align="left">TO_BOOL_NONE</td>
<td align="right">366,100</td>
<td align="right">0.3%</td>
</tr>
<tr>
<td align="left">EXTENDED_ARG</td>
<td align="right">161,440</td>
<td align="right">0.1%</td>
</tr>
<tr>
<td align="left">TO_BOOL_ALWAYS_TRUE</td>
<td align="right">91,860</td>
<td align="right">0.1%</td>
</tr>
</tbody>
</table>


</details>

### TO_BOOL_LIST

<details>
<summary> Successors and predecessors for TO_BOOL_LIST </summary>

<table>
<thead>
<tr>
<th align="left">Predecessors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">53,459,291</td>
<td align="right">62.5%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_INSTANCE_VALUE</td>
<td align="right">29,414,256</td>
<td align="right">34.4%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES</td>
<td align="right">1,712,180</td>
<td align="right">2.0%</td>
</tr>
<tr>
<td align="left">BINARY_SUBSCR_DICT</td>
<td align="right">423,540</td>
<td align="right">0.5%</td>
</tr>
<tr>
<td align="left">RETURN_VALUE</td>
<td align="right">298,100</td>
<td align="right">0.3%</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Successors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">POP_JUMP_IF_FALSE</td>
<td align="right">54,524,189</td>
<td align="right">63.8%</td>
</tr>
<tr>
<td align="left">POP_JUMP_IF_TRUE</td>
<td align="right">29,426,327</td>
<td align="right">34.4%</td>
</tr>
<tr>
<td align="left">UNARY_NOT</td>
<td align="right">1,234,740</td>
<td align="right">1.4%</td>
</tr>
<tr>
<td align="left">EXTENDED_ARG</td>
<td align="right">305,940</td>
<td align="right">0.4%</td>
</tr>
<tr>
<td align="left">TO_BOOL</td>
<td align="right">19,960</td>
<td align="right">0.0%</td>
</tr>
</tbody>
</table>


</details>

### BINARY_OP_INPLACE_ADD_UNICODE

<details>
<summary> Successors and predecessors for BINARY_OP_INPLACE_ADD_UNICODE </summary>

<table>
<thead>
<tr>
<th align="left">Predecessors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">LOAD_FAST_LOAD_FAST</td>
<td align="right">1,007,880</td>
<td align="right">45.1%</td>
</tr>
<tr>
<td align="left">RETURN_VALUE</td>
<td align="right">532,380</td>
<td align="right">23.8%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_SLOT</td>
<td align="right">358,800</td>
<td align="right">16.0%</td>
</tr>
<tr>
<td align="left">BINARY_SUBSCR_STR_INT</td>
<td align="right">217,140</td>
<td align="right">9.7%</td>
</tr>
<tr>
<td align="left">CALL_FUNCTION_EX</td>
<td align="right">60,360</td>
<td align="right">2.7%</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Successors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">2,117,160</td>
<td align="right">94.7%</td>
</tr>
<tr>
<td align="left">LOAD_CONST</td>
<td align="right">60,360</td>
<td align="right">2.7%</td>
</tr>
<tr>
<td align="left">LOAD_FAST_LOAD_FAST</td>
<td align="right">25,020</td>
<td align="right">1.1%</td>
</tr>
<tr>
<td align="left">JUMP_BACKWARD</td>
<td align="right">20,860</td>
<td align="right">0.9%</td>
</tr>
<tr>
<td align="left">LOAD_GLOBAL_MODULE</td>
<td align="right">8,860</td>
<td align="right">0.4%</td>
</tr>
</tbody>
</table>


</details>

### END_FOR

<details>
<summary> Successors and predecessors for END_FOR </summary>

<table>
<thead>
<tr>
<th align="left">Predecessors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">RETURN_CONST</td>
<td align="right">37,964,583</td>
<td align="right">100.0%</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Successors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">POP_TOP</td>
<td align="right">37,964,583</td>
<td align="right">100.0%</td>
</tr>
</tbody>
</table>


</details>

### FORMAT_SIMPLE

<details>
<summary> Successors and predecessors for FORMAT_SIMPLE </summary>

<table>
<thead>
<tr>
<th align="left">Predecessors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">CONVERT_VALUE</td>
<td align="right">105,666,300</td>
<td align="right">96.3%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR</td>
<td align="right">1,423,980</td>
<td align="right">1.3%</td>
</tr>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">1,052,460</td>
<td align="right">1.0%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_SLOT</td>
<td align="right">831,600</td>
<td align="right">0.8%</td>
</tr>
<tr>
<td align="left">RETURN_VALUE</td>
<td align="right">732,120</td>
<td align="right">0.7%</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Successors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">LOAD_CONST</td>
<td align="right">57,557,400</td>
<td align="right">52.5%</td>
</tr>
<tr>
<td align="left">BUILD_STRING</td>
<td align="right">48,951,960</td>
<td align="right">44.6%</td>
</tr>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">3,196,260</td>
<td align="right">2.9%</td>
</tr>
<tr>
<td align="left">LOAD_GLOBAL_MODULE</td>
<td align="right">8,820</td>
<td align="right">0.0%</td>
</tr>
</tbody>
</table>


</details>

### GET_YIELD_FROM_ITER

<details>
<summary> Successors and predecessors for GET_YIELD_FROM_ITER </summary>

<table>
<thead>
<tr>
<th align="left">Predecessors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">LOAD_ATTR_INSTANCE_VALUE</td>
<td align="right">24,000,300</td>
<td align="right">87.4%</td>
</tr>
<tr>
<td align="left">RETURN_GENERATOR</td>
<td align="right">3,319,128</td>
<td align="right">12.1%</td>
</tr>
<tr>
<td align="left">BINARY_SUBSCR</td>
<td align="right">132,060</td>
<td align="right">0.5%</td>
</tr>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">14,160</td>
<td align="right">0.1%</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Successors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">LOAD_CONST</td>
<td align="right">27,465,648</td>
<td align="right">100.0%</td>
</tr>
</tbody>
</table>


</details>

### BUILD_CONST_KEY_MAP

<details>
<summary> Successors and predecessors for BUILD_CONST_KEY_MAP </summary>

<table>
<thead>
<tr>
<th align="left">Predecessors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">LOAD_CONST</td>
<td align="right">7,138,166</td>
<td align="right">100.0%</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Successors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">RETURN_VALUE</td>
<td align="right">3,960,720</td>
<td align="right">55.5%</td>
</tr>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">2,494,380</td>
<td align="right">34.9%</td>
</tr>
<tr>
<td align="left">CALL_METHOD_DESCRIPTOR_O</td>
<td align="right">383,280</td>
<td align="right">5.4%</td>
</tr>
<tr>
<td align="left">STORE_FAST</td>
<td align="right">244,646</td>
<td align="right">3.4%</td>
</tr>
<tr>
<td align="left">DICT_MERGE</td>
<td align="right">16,320</td>
<td align="right">0.2%</td>
</tr>
</tbody>
</table>


</details>

### BUILD_STRING

<details>
<summary> Successors and predecessors for BUILD_STRING </summary>

<table>
<thead>
<tr>
<th align="left">Predecessors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">FORMAT_SIMPLE</td>
<td align="right">48,951,960</td>
<td align="right">88.6%</td>
</tr>
<tr>
<td align="left">LOAD_CONST</td>
<td align="right">6,281,220</td>
<td align="right">11.4%</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Successors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">CALL_BUILTIN_O</td>
<td align="right">37,276,800</td>
<td align="right">67.5%</td>
</tr>
<tr>
<td align="left">CALL_PY_GENERAL</td>
<td align="right">11,581,020</td>
<td align="right">21.0%</td>
</tr>
<tr>
<td align="left">BINARY_OP_ADD_UNICODE</td>
<td align="right">2,010,960</td>
<td align="right">3.6%</td>
</tr>
<tr>
<td align="left">STORE_FAST</td>
<td align="right">1,863,540</td>
<td align="right">3.4%</td>
</tr>
<tr>
<td align="left">CALL_LIST_APPEND</td>
<td align="right">1,398,120</td>
<td align="right">2.5%</td>
</tr>
</tbody>
</table>


</details>

### DICT_UPDATE

<details>
<summary> Successors and predecessors for DICT_UPDATE </summary>

<table>
<thead>
<tr>
<th align="left">Predecessors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">13,140</td>
<td align="right">100.0%</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Successors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">DICT_MERGE</td>
<td align="right">13,140</td>
<td align="right">100.0%</td>
</tr>
</tbody>
</table>


</details>

### EXTENDED_ARG

<details>
<summary> Successors and predecessors for EXTENDED_ARG </summary>

<table>
<thead>
<tr>
<th align="left">Predecessors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">TO_BOOL_BOOL</td>
<td align="right">78,443,242</td>
<td align="right">25.6%</td>
</tr>
<tr>
<td align="left">COMPARE_OP_STR</td>
<td align="right">73,432,560</td>
<td align="right">24.0%</td>
</tr>
<tr>
<td align="left">JUMP_BACKWARD</td>
<td align="right">56,360,459</td>
<td align="right">18.4%</td>
</tr>
<tr>
<td align="left">POP_JUMP_IF_TRUE</td>
<td align="right">22,970,280</td>
<td align="right">7.5%</td>
</tr>
<tr>
<td align="left">POP_TOP</td>
<td align="right">21,125,340</td>
<td align="right">6.9%</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Successors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">POP_JUMP_IF_FALSE</td>
<td align="right">175,279,213</td>
<td align="right">57.2%</td>
</tr>
<tr>
<td align="left">JUMP_BACKWARD</td>
<td align="right">50,428,595</td>
<td align="right">16.5%</td>
</tr>
<tr>
<td align="left">FOR_ITER_GEN</td>
<td align="right">26,083,460</td>
<td align="right">8.5%</td>
</tr>
<tr>
<td align="left">FOR_ITER</td>
<td align="right">17,546,138</td>
<td align="right">5.7%</td>
</tr>
<tr>
<td align="left">FOR_ITER_LIST</td>
<td align="right">16,868,365</td>
<td align="right">5.5%</td>
</tr>
</tbody>
</table>


</details>

### LIST_APPEND

<details>
<summary> Successors and predecessors for LIST_APPEND </summary>

<table>
<thead>
<tr>
<th align="left">Predecessors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">BINARY_OP</td>
<td align="right">24,078,840</td>
<td align="right">25.5%</td>
</tr>
<tr>
<td align="left">BUILD_TUPLE</td>
<td align="right">23,077,057</td>
<td align="right">24.4%</td>
</tr>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">14,499,050</td>
<td align="right">15.4%</td>
</tr>
<tr>
<td align="left">RETURN_GENERATOR</td>
<td align="right">13,436,640</td>
<td align="right">14.2%</td>
</tr>
<tr>
<td align="left">BINARY_SUBSCR_LIST_INT</td>
<td align="right">4,800,000</td>
<td align="right">5.1%</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Successors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">JUMP_BACKWARD</td>
<td align="right">94,298,501</td>
<td align="right">99.9%</td>
</tr>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">96,000</td>
<td align="right">0.1%</td>
</tr>
<tr>
<td align="left">CALL_INTRINSIC_1</td>
<td align="right">11,520</td>
<td align="right">0.0%</td>
</tr>
</tbody>
</table>


</details>

### MAP_ADD

<details>
<summary> Successors and predecessors for MAP_ADD </summary>

<table>
<thead>
<tr>
<th align="left">Predecessors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">RETURN_VALUE</td>
<td align="right">6,195,540</td>
<td align="right">42.4%</td>
</tr>
<tr>
<td align="left">LOAD_FAST_LOAD_FAST</td>
<td align="right">5,844,686</td>
<td align="right">40.0%</td>
</tr>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">1,287,600</td>
<td align="right">8.8%</td>
</tr>
<tr>
<td align="left">CALL_BUILTIN_CLASS</td>
<td align="right">1,205,640</td>
<td align="right">8.2%</td>
</tr>
<tr>
<td align="left">JUMP_FORWARD</td>
<td align="right">76,080</td>
<td align="right">0.5%</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Successors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">JUMP_BACKWARD</td>
<td align="right">14,570,846</td>
<td align="right">99.7%</td>
</tr>
<tr>
<td align="left">LOAD_CONST</td>
<td align="right">47,940</td>
<td align="right">0.3%</td>
</tr>
<tr>
<td align="left">CALL_FUNCTION_EX</td>
<td align="right">3,000</td>
<td align="right">0.0%</td>
</tr>
</tbody>
</table>


</details>

### STORE_FAST_LOAD_FAST

<details>
<summary> Successors and predecessors for STORE_FAST_LOAD_FAST </summary>

<table>
<thead>
<tr>
<th align="left">Predecessors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">FOR_ITER_RANGE</td>
<td align="right">35,295,420</td>
<td align="right">55.6%</td>
</tr>
<tr>
<td align="left">FOR_ITER_LIST</td>
<td align="right">20,511,050</td>
<td align="right">32.3%</td>
</tr>
<tr>
<td align="left">FOR_ITER_TUPLE</td>
<td align="right">3,779,249</td>
<td align="right">6.0%</td>
</tr>
<tr>
<td align="left">FOR_ITER</td>
<td align="right">2,553,240</td>
<td align="right">4.0%</td>
</tr>
<tr>
<td align="left">CALL_LEN</td>
<td align="right">1,084,320</td>
<td align="right">1.7%</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Successors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">21,989,820</td>
<td align="right">34.7%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_METHOD_WITH_VALUES</td>
<td align="right">14,643,000</td>
<td align="right">23.1%</td>
</tr>
<tr>
<td align="left">POP_JUMP_IF_NOT_NONE</td>
<td align="right">8,870,340</td>
<td align="right">14.0%</td>
</tr>
<tr>
<td align="left">YIELD_VALUE</td>
<td align="right">4,806,720</td>
<td align="right">7.6%</td>
</tr>
<tr>
<td align="left">PUSH_NULL</td>
<td align="right">3,160,440</td>
<td align="right">5.0%</td>
</tr>
</tbody>
</table>


</details>

### BINARY_SUBSCR_STR_INT

<details>
<summary> Successors and predecessors for BINARY_SUBSCR_STR_INT </summary>

<table>
<thead>
<tr>
<th align="left">Predecessors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">BINARY_OP_SUBTRACT_INT</td>
<td align="right">10,611,960</td>
<td align="right">26.0%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_SLOT</td>
<td align="right">10,356,180</td>
<td align="right">25.4%</td>
</tr>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">10,176,060</td>
<td align="right">25.0%</td>
</tr>
<tr>
<td align="left">LOAD_CONST</td>
<td align="right">5,374,160</td>
<td align="right">13.2%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_INSTANCE_VALUE</td>
<td align="right">3,715,200</td>
<td align="right">9.1%</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Successors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">20,811,000</td>
<td align="right">51.1%</td>
</tr>
<tr>
<td align="left">STORE_FAST</td>
<td align="right">10,375,320</td>
<td align="right">25.5%</td>
</tr>
<tr>
<td align="left">LOAD_CONST</td>
<td align="right">5,147,700</td>
<td align="right">12.6%</td>
</tr>
<tr>
<td align="left">RETURN_VALUE</td>
<td align="right">3,711,600</td>
<td align="right">9.1%</td>
</tr>
<tr>
<td align="left">BINARY_OP_INPLACE_ADD_UNICODE</td>
<td align="right">217,140</td>
<td align="right">0.5%</td>
</tr>
</tbody>
</table>


</details>

### CALL_BUILTIN_FAST_WITH_KEYWORDS

<details>
<summary> Successors and predecessors for CALL_BUILTIN_FAST_WITH_KEYWORDS </summary>

<table>
<thead>
<tr>
<th align="left">Predecessors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">RETURN_GENERATOR</td>
<td align="right">48,222,060</td>
<td align="right">48.1%</td>
</tr>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">20,805,342</td>
<td align="right">20.8%</td>
</tr>
<tr>
<td align="left">LOAD_FAST_LOAD_FAST</td>
<td align="right">6,374,040</td>
<td align="right">6.4%</td>
</tr>
<tr>
<td align="left">CALL_METHOD_DESCRIPTOR_NOARGS</td>
<td align="right">5,629,706</td>
<td align="right">5.6%</td>
</tr>
<tr>
<td align="left">CALL_BUILTIN_FAST_WITH_KEYWORDS</td>
<td align="right">5,069,700</td>
<td align="right">5.1%</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Successors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">LOAD_DEREF</td>
<td align="right">46,765,320</td>
<td align="right">46.7%</td>
</tr>
<tr>
<td align="left">STORE_FAST</td>
<td align="right">18,954,722</td>
<td align="right">18.9%</td>
</tr>
<tr>
<td align="left">RETURN_VALUE</td>
<td align="right">11,728,796</td>
<td align="right">11.7%</td>
</tr>
<tr>
<td align="left">POP_TOP</td>
<td align="right">8,497,461</td>
<td align="right">8.5%</td>
</tr>
<tr>
<td align="left">CALL_BUILTIN_FAST_WITH_KEYWORDS</td>
<td align="right">5,069,700</td>
<td align="right">5.1%</td>
</tr>
</tbody>
</table>


</details>

### CALL_LIST_APPEND

<details>
<summary> Successors and predecessors for CALL_LIST_APPEND </summary>

<table>
<thead>
<tr>
<th align="left">Predecessors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">93,996,916</td>
<td align="right">53.4%</td>
</tr>
<tr>
<td align="left">BINARY_SUBSCR</td>
<td align="right">20,171,040</td>
<td align="right">11.5%</td>
</tr>
<tr>
<td align="left">BINARY_SLICE</td>
<td align="right">19,300,980</td>
<td align="right">11.0%</td>
</tr>
<tr>
<td align="left">BUILD_TUPLE</td>
<td align="right">17,938,792</td>
<td align="right">10.2%</td>
</tr>
<tr>
<td align="left">BINARY_OP</td>
<td align="right">8,543,680</td>
<td align="right">4.9%</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Successors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">JUMP_BACKWARD</td>
<td align="right">92,536,230</td>
<td align="right">52.5%</td>
</tr>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">42,588,245</td>
<td align="right">24.2%</td>
</tr>
<tr>
<td align="left">RETURN_CONST</td>
<td align="right">20,033,520</td>
<td align="right">11.4%</td>
</tr>
<tr>
<td align="left">NOP</td>
<td align="right">5,490,163</td>
<td align="right">3.1%</td>
</tr>
<tr>
<td align="left">EXTENDED_ARG</td>
<td align="right">3,497,137</td>
<td align="right">2.0%</td>
</tr>
</tbody>
</table>


</details>

### CALL_TUPLE_1

<details>
<summary> Successors and predecessors for CALL_TUPLE_1 </summary>

<table>
<thead>
<tr>
<th align="left">Predecessors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">RETURN_GENERATOR</td>
<td align="right">5,391,220</td>
<td align="right">49.8%</td>
</tr>
<tr>
<td align="left">CALL_BUILTIN_FAST_WITH_KEYWORDS</td>
<td align="right">3,487,626</td>
<td align="right">32.2%</td>
</tr>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">1,136,967</td>
<td align="right">10.5%</td>
</tr>
<tr>
<td align="left">CALL</td>
<td align="right">484,980</td>
<td align="right">4.5%</td>
</tr>
<tr>
<td align="left">RETURN_VALUE</td>
<td align="right">163,620</td>
<td align="right">1.5%</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Successors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">BINARY_OP</td>
<td align="right">3,490,646</td>
<td align="right">32.2%</td>
</tr>
<tr>
<td align="left">BUILD_TUPLE</td>
<td align="right">2,504,040</td>
<td align="right">23.1%</td>
</tr>
<tr>
<td align="left">YIELD_VALUE</td>
<td align="right">2,419,200</td>
<td align="right">22.3%</td>
</tr>
<tr>
<td align="left">STORE_FAST</td>
<td align="right">945,040</td>
<td align="right">8.7%</td>
</tr>
<tr>
<td align="left">RETURN_VALUE</td>
<td align="right">465,660</td>
<td align="right">4.3%</td>
</tr>
</tbody>
</table>


</details>

### COMPARE_OP_STR

<details>
<summary> Successors and predecessors for COMPARE_OP_STR </summary>

<table>
<thead>
<tr>
<th align="left">Predecessors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">LOAD_CONST</td>
<td align="right">149,290,084</td>
<td align="right">77.5%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_INSTANCE_VALUE</td>
<td align="right">17,050,440</td>
<td align="right">8.8%</td>
</tr>
<tr>
<td align="left">LOAD_GLOBAL_MODULE</td>
<td align="right">8,646,969</td>
<td align="right">4.5%</td>
</tr>
<tr>
<td align="left">LOAD_FAST_LOAD_FAST</td>
<td align="right">7,753,340</td>
<td align="right">4.0%</td>
</tr>
<tr>
<td align="left">RETURN_VALUE</td>
<td align="right">3,333,540</td>
<td align="right">1.7%</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Successors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">POP_JUMP_IF_FALSE</td>
<td align="right">87,350,238</td>
<td align="right">45.3%</td>
</tr>
<tr>
<td align="left">EXTENDED_ARG</td>
<td align="right">73,432,560</td>
<td align="right">38.1%</td>
</tr>
<tr>
<td align="left">POP_JUMP_IF_TRUE</td>
<td align="right">19,107,730</td>
<td align="right">9.9%</td>
</tr>
<tr>
<td align="left">COPY</td>
<td align="right">7,480,740</td>
<td align="right">3.9%</td>
</tr>
<tr>
<td align="left">RETURN_VALUE</td>
<td align="right">3,413,820</td>
<td align="right">1.8%</td>
</tr>
</tbody>
</table>


</details>

### FOR_ITER_GEN

<details>
<summary> Successors and predecessors for FOR_ITER_GEN </summary>

<table>
<thead>
<tr>
<th align="left">Predecessors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">JUMP_BACKWARD</td>
<td align="right">79,636,006</td>
<td align="right">55.5%</td>
</tr>
<tr>
<td align="left">GET_ITER</td>
<td align="right">37,634,066</td>
<td align="right">26.2%</td>
</tr>
<tr>
<td align="left">EXTENDED_ARG</td>
<td align="right">26,083,460</td>
<td align="right">18.2%</td>
</tr>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">42,240</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">SWAP</td>
<td align="right">360</td>
<td align="right">0.0%</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Successors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">RESUME_CHECK</td>
<td align="right">105,348,566</td>
<td align="right">73.5%</td>
</tr>
<tr>
<td align="left">POP_TOP</td>
<td align="right">38,045,246</td>
<td align="right">26.5%</td>
</tr>
<tr>
<td align="left">UNPACK_SEQUENCE_TUPLE</td>
<td align="right">1,260</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">STORE_FAST</td>
<td align="right">480</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">340</td>
<td align="right">0.0%</td>
</tr>
</tbody>
</table>


</details>

### FOR_ITER_TUPLE

<details>
<summary> Successors and predecessors for FOR_ITER_TUPLE </summary>

<table>
<thead>
<tr>
<th align="left">Predecessors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">JUMP_BACKWARD</td>
<td align="right">193,692,691</td>
<td align="right">72.2%</td>
</tr>
<tr>
<td align="left">GET_ITER</td>
<td align="right">69,515,694</td>
<td align="right">25.9%</td>
</tr>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">1,435,946</td>
<td align="right">0.5%</td>
</tr>
<tr>
<td align="left">EXTENDED_ARG</td>
<td align="right">1,384,380</td>
<td align="right">0.5%</td>
</tr>
<tr>
<td align="left">FOR_ITER_LIST</td>
<td align="right">1,210,857</td>
<td align="right">0.5%</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Successors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">STORE_FAST</td>
<td align="right">191,515,073</td>
<td align="right">71.4%</td>
</tr>
<tr>
<td align="left">LOAD_FAST_LOAD_FAST</td>
<td align="right">41,375,880</td>
<td align="right">15.4%</td>
</tr>
<tr>
<td align="left">RETURN_CONST</td>
<td align="right">12,450,922</td>
<td align="right">4.6%</td>
</tr>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">11,750,150</td>
<td align="right">4.4%</td>
</tr>
<tr>
<td align="left">STORE_FAST_LOAD_FAST</td>
<td align="right">3,779,249</td>
<td align="right">1.4%</td>
</tr>
</tbody>
</table>


</details>

### LOAD_ATTR_NONDESCRIPTOR_NO_DICT

<details>
<summary> Successors and predecessors for LOAD_ATTR_NONDESCRIPTOR_NO_DICT </summary>

<table>
<thead>
<tr>
<th align="left">Predecessors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">54,938,133</td>
<td align="right">85.7%</td>
</tr>
<tr>
<td align="left">LOAD_FAST_LOAD_FAST</td>
<td align="right">5,996,772</td>
<td align="right">9.4%</td>
</tr>
<tr>
<td align="left">LOAD_DEREF</td>
<td align="right">2,337,980</td>
<td align="right">3.6%</td>
</tr>
<tr>
<td align="left">BINARY_SUBSCR_LIST_INT</td>
<td align="right">253,800</td>
<td align="right">0.4%</td>
</tr>
<tr>
<td align="left">STORE_FAST_LOAD_FAST</td>
<td align="right">185,664</td>
<td align="right">0.3%</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Successors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">TO_BOOL_BOOL</td>
<td align="right">33,186,749</td>
<td align="right">51.8%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_METHOD_NO_DICT</td>
<td align="right">8,386,500</td>
<td align="right">13.1%</td>
</tr>
<tr>
<td align="left">CONTAINS_OP_DICT</td>
<td align="right">5,562,060</td>
<td align="right">8.7%</td>
</tr>
<tr>
<td align="left">CALL_BUILTIN_O</td>
<td align="right">4,071,554</td>
<td align="right">6.4%</td>
</tr>
<tr>
<td align="left">CALL_PY_EXACT_ARGS</td>
<td align="right">3,272,720</td>
<td align="right">5.1%</td>
</tr>
</tbody>
</table>


</details>

### LOAD_ATTR_PROPERTY

<details>
<summary> Successors and predecessors for LOAD_ATTR_PROPERTY </summary>

<table>
<thead>
<tr>
<th align="left">Predecessors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">39,368,467</td>
<td align="right">89.2%</td>
</tr>
<tr>
<td align="left">RETURN_VALUE</td>
<td align="right">2,952,446</td>
<td align="right">6.7%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_INSTANCE_VALUE</td>
<td align="right">743,200</td>
<td align="right">1.7%</td>
</tr>
<tr>
<td align="left">BINARY_SUBSCR</td>
<td align="right">398,520</td>
<td align="right">0.9%</td>
</tr>
<tr>
<td align="left">STORE_FAST_LOAD_FAST</td>
<td align="right">235,699</td>
<td align="right">0.5%</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Successors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">RESUME_CHECK</td>
<td align="right">33,190,171</td>
<td align="right">75.2%</td>
</tr>
<tr>
<td align="left">COPY_FREE_VARS</td>
<td align="right">3,871,095</td>
<td align="right">8.8%</td>
</tr>
<tr>
<td align="left">TO_BOOL_NONE</td>
<td align="right">3,312,849</td>
<td align="right">7.5%</td>
</tr>
<tr>
<td align="left">GET_ITER</td>
<td align="right">1,435,564</td>
<td align="right">3.3%</td>
</tr>
<tr>
<td align="left">TO_BOOL_BOOL</td>
<td align="right">533,369</td>
<td align="right">1.2%</td>
</tr>
</tbody>
</table>


</details>

### UNPACK_SEQUENCE_TUPLE

<details>
<summary> Successors and predecessors for UNPACK_SEQUENCE_TUPLE </summary>

<table>
<thead>
<tr>
<th align="left">Predecessors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">RETURN_VALUE</td>
<td align="right">240,521,160</td>
<td align="right">44.7%</td>
</tr>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">201,550,788</td>
<td align="right">37.4%</td>
</tr>
<tr>
<td align="left">YIELD_VALUE</td>
<td align="right">24,808,480</td>
<td align="right">4.6%</td>
</tr>
<tr>
<td align="left">CALL_METHOD_DESCRIPTOR_FAST</td>
<td align="right">14,633,560</td>
<td align="right">2.7%</td>
</tr>
<tr>
<td align="left">BINARY_SUBSCR_DICT</td>
<td align="right">14,268,900</td>
<td align="right">2.7%</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Successors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">STORE_FAST_STORE_FAST</td>
<td align="right">255,981,902</td>
<td align="right">47.5%</td>
</tr>
<tr>
<td align="left">STORE_FAST</td>
<td align="right">243,802,956</td>
<td align="right">45.3%</td>
</tr>
<tr>
<td align="left">UNPACK_SEQUENCE_LIST</td>
<td align="right">24,026,440</td>
<td align="right">4.5%</td>
</tr>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">14,576,820</td>
<td align="right">2.7%</td>
</tr>
<tr>
<td align="left">UNPACK_SEQUENCE_TWO_TUPLE</td>
<td align="right">29,880</td>
<td align="right">0.0%</td>
</tr>
</tbody>
</table>


</details>

### LOAD_FAST_CHECK

<details>
<summary> Successors and predecessors for LOAD_FAST_CHECK </summary>

<table>
<thead>
<tr>
<th align="left">Predecessors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">LOAD_ATTR_METHOD_NO_DICT</td>
<td align="right">1,215,840</td>
<td align="right">36.5%</td>
</tr>
<tr>
<td align="left">POP_JUMP_IF_NONE</td>
<td align="right">1,151,126</td>
<td align="right">34.6%</td>
</tr>
<tr>
<td align="left">POP_TOP</td>
<td align="right">483,840</td>
<td align="right">14.5%</td>
</tr>
<tr>
<td align="left">LOAD_GLOBAL_BUILTIN</td>
<td align="right">221,940</td>
<td align="right">6.7%</td>
</tr>
<tr>
<td align="left">STORE_FAST</td>
<td align="right">67,680</td>
<td align="right">2.0%</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Successors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">CALL_LIST_APPEND</td>
<td align="right">1,161,840</td>
<td align="right">34.9%</td>
</tr>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">1,049,100</td>
<td align="right">31.5%</td>
</tr>
<tr>
<td align="left">UNPACK_SEQUENCE_TWO_TUPLE</td>
<td align="right">480,000</td>
<td align="right">14.4%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_METHOD_NO_DICT</td>
<td align="right">219,580</td>
<td align="right">6.6%</td>
</tr>
<tr>
<td align="left">LOAD_GLOBAL_MODULE</td>
<td align="right">113,626</td>
<td align="right">3.4%</td>
</tr>
</tbody>
</table>


</details>

### LOAD_BUILD_CLASS

<details>
<summary> Successors and predecessors for LOAD_BUILD_CLASS </summary>

<table>
<thead>
<tr>
<th align="left">Predecessors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">STORE_DEREF</td>
<td align="right">1,200</td>
<td align="right">90.9%</td>
</tr>
<tr>
<td align="left">RESUME_CHECK</td>
<td align="right">120</td>
<td align="right">9.1%</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Successors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">PUSH_NULL</td>
<td align="right">1,320</td>
<td align="right">100.0%</td>
</tr>
</tbody>
</table>


</details>

### LOAD_LOCALS

<details>
<summary> Successors and predecessors for LOAD_LOCALS </summary>

<table>
<thead>
<tr>
<th align="left">Predecessors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">STORE_NAME</td>
<td align="right">1,200</td>
<td align="right">87.0%</td>
</tr>
<tr>
<td align="left">PUSH_NULL</td>
<td align="right">180</td>
<td align="right">13.0%</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Successors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">LOAD_FROM_DICT_OR_DEREF</td>
<td align="right">1,380</td>
<td align="right">100.0%</td>
</tr>
</tbody>
</table>


</details>

### CONVERT_VALUE

<details>
<summary> Successors and predecessors for CONVERT_VALUE </summary>

<table>
<thead>
<tr>
<th align="left">Predecessors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">87,664,380</td>
<td align="right">83.0%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR</td>
<td align="right">11,580,660</td>
<td align="right">11.0%</td>
</tr>
<tr>
<td align="left">CALL_METHOD_DESCRIPTOR_O</td>
<td align="right">2,010,960</td>
<td align="right">1.9%</td>
</tr>
<tr>
<td align="left">RETURN_VALUE</td>
<td align="right">1,496,100</td>
<td align="right">1.4%</td>
</tr>
<tr>
<td align="left">CALL_METHOD_DESCRIPTOR_NOARGS</td>
<td align="right">1,385,580</td>
<td align="right">1.3%</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Successors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">FORMAT_SIMPLE</td>
<td align="right">105,666,300</td>
<td align="right">100.0%</td>
</tr>
</tbody>
</table>


</details>

### DELETE_ATTR

<details>
<summary> Successors and predecessors for DELETE_ATTR </summary>

<table>
<thead>
<tr>
<th align="left">Predecessors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">83,160</td>
<td align="right">99.9%</td>
</tr>
<tr>
<td align="left">LOAD_DEREF</td>
<td align="right">60</td>
<td align="right">0.1%</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Successors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">53,200</td>
<td align="right">63.9%</td>
</tr>
<tr>
<td align="left">RETURN_CONST</td>
<td align="right">25,440</td>
<td align="right">30.6%</td>
</tr>
<tr>
<td align="left">NOP</td>
<td align="right">2,600</td>
<td align="right">3.1%</td>
</tr>
<tr>
<td align="left">LOAD_GLOBAL_MODULE</td>
<td align="right">1,920</td>
<td align="right">2.3%</td>
</tr>
<tr>
<td align="left">LOAD_CONST</td>
<td align="right">60</td>
<td align="right">0.1%</td>
</tr>
</tbody>
</table>


</details>

### LOAD_FROM_DICT_OR_DEREF

<details>
<summary> Successors and predecessors for LOAD_FROM_DICT_OR_DEREF </summary>

<table>
<thead>
<tr>
<th align="left">Predecessors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">LOAD_LOCALS</td>
<td align="right">1,380</td>
<td align="right">100.0%</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Successors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">LOAD_ATTR</td>
<td align="right">1,200</td>
<td align="right">87.0%</td>
</tr>
<tr>
<td align="left">LOAD_CONST</td>
<td align="right">180</td>
<td align="right">13.0%</td>
</tr>
</tbody>
</table>


</details>

### LOAD_NAME

<details>
<summary> Successors and predecessors for LOAD_NAME </summary>

<table>
<thead>
<tr>
<th align="left">Predecessors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">PUSH_NULL</td>
<td align="right">5,041,080</td>
<td align="right">56.0%</td>
</tr>
<tr>
<td align="left">RESUME_CHECK</td>
<td align="right">3,961,320</td>
<td align="right">44.0%</td>
</tr>
<tr>
<td align="left">RESUME</td>
<td align="right">360</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">STORE_NAME</td>
<td align="right">240</td>
<td align="right">0.0%</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Successors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">PUSH_NULL</td>
<td align="right">4,680,900</td>
<td align="right">52.0%</td>
</tr>
<tr>
<td align="left">LOAD_CONST</td>
<td align="right">4,320,720</td>
<td align="right">48.0%</td>
</tr>
<tr>
<td align="left">STORE_NAME</td>
<td align="right">1,320</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">UNPACK_SEQUENCE_TUPLE</td>
<td align="right">40</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">UNPACK_SEQUENCE</td>
<td align="right">20</td>
<td align="right">0.0%</td>
</tr>
</tbody>
</table>


</details>

### STORE_NAME

<details>
<summary> Successors and predecessors for STORE_NAME </summary>

<table>
<thead>
<tr>
<th align="left">Predecessors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">LOAD_CONST</td>
<td align="right">3,960</td>
<td align="right">40.0%</td>
</tr>
<tr>
<td align="left">SET_FUNCTION_ATTRIBUTE</td>
<td align="right">2,520</td>
<td align="right">25.5%</td>
</tr>
<tr>
<td align="left">LOAD_NAME</td>
<td align="right">1,320</td>
<td align="right">13.3%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR</td>
<td align="right">1,200</td>
<td align="right">12.1%</td>
</tr>
<tr>
<td align="left">MAKE_FUNCTION</td>
<td align="right">540</td>
<td align="right">5.5%</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Successors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">LOAD_CONST</td>
<td align="right">4,080</td>
<td align="right">41.2%</td>
</tr>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">2,520</td>
<td align="right">25.5%</td>
</tr>
<tr>
<td align="left">RETURN_CONST</td>
<td align="right">1,740</td>
<td align="right">17.6%</td>
</tr>
<tr>
<td align="left">LOAD_LOCALS</td>
<td align="right">1,200</td>
<td align="right">12.1%</td>
</tr>
<tr>
<td align="left">LOAD_NAME</td>
<td align="right">240</td>
<td align="right">2.4%</td>
</tr>
</tbody>
</table>


</details>

### BINARY_OP_ADD_UNICODE

<details>
<summary> Successors and predecessors for BINARY_OP_ADD_UNICODE </summary>

<table>
<thead>
<tr>
<th align="left">Predecessors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">35,808,920</td>
<td align="right">65.9%</td>
</tr>
<tr>
<td align="left">LOAD_CONST</td>
<td align="right">10,746,980</td>
<td align="right">19.8%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES</td>
<td align="right">2,460,900</td>
<td align="right">4.5%</td>
</tr>
<tr>
<td align="left">BUILD_STRING</td>
<td align="right">2,010,960</td>
<td align="right">3.7%</td>
</tr>
<tr>
<td align="left">RETURN_VALUE</td>
<td align="right">1,062,640</td>
<td align="right">2.0%</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Successors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">CALL_BUILTIN_O</td>
<td align="right">19,572,000</td>
<td align="right">36.0%</td>
</tr>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">14,209,320</td>
<td align="right">26.1%</td>
</tr>
<tr>
<td align="left">LOAD_CONST</td>
<td align="right">10,514,160</td>
<td align="right">19.3%</td>
</tr>
<tr>
<td align="left">SWAP</td>
<td align="right">2,963,340</td>
<td align="right">5.5%</td>
</tr>
<tr>
<td align="left">CALL_METHOD_DESCRIPTOR_O</td>
<td align="right">2,457,600</td>
<td align="right">4.5%</td>
</tr>
</tbody>
</table>


</details>

### LOAD_SUPER_ATTR_ATTR

<details>
<summary> Successors and predecessors for LOAD_SUPER_ATTR_ATTR </summary>

<table>
<thead>
<tr>
<th align="left">Predecessors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">1,035,658</td>
<td align="right">94.7%</td>
</tr>
<tr>
<td align="left">LOAD_DEREF</td>
<td align="right">58,020</td>
<td align="right">5.3%</td>
</tr>
<tr>
<td align="left">LOAD_SUPER_ATTR</td>
<td align="right">20</td>
<td align="right">0.0%</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Successors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">PUSH_NULL</td>
<td align="right">1,030,698</td>
<td align="right">94.2%</td>
</tr>
<tr>
<td align="left">LOAD_GLOBAL_MODULE</td>
<td align="right">63,000</td>
<td align="right">5.8%</td>
</tr>
</tbody>
</table>


</details>

### UNPACK_SEQUENCE_LIST

<details>
<summary> Successors and predecessors for UNPACK_SEQUENCE_LIST </summary>

<table>
<thead>
<tr>
<th align="left">Predecessors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">196,797,720</td>
<td align="right">86.6%</td>
</tr>
<tr>
<td align="left">UNPACK_SEQUENCE_TUPLE</td>
<td align="right">24,026,440</td>
<td align="right">10.6%</td>
</tr>
<tr>
<td align="left">STORE_FAST</td>
<td align="right">6,001,900</td>
<td align="right">2.6%</td>
</tr>
<tr>
<td align="left">LIST_EXTEND</td>
<td align="right">345,120</td>
<td align="right">0.2%</td>
</tr>
<tr>
<td align="left">CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS</td>
<td align="right">90,360</td>
<td align="right">0.0%</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Successors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">STORE_FAST_STORE_FAST</td>
<td align="right">221,203,200</td>
<td align="right">97.3%</td>
</tr>
<tr>
<td align="left">STORE_FAST</td>
<td align="right">6,084,480</td>
<td align="right">2.7%</td>
</tr>
<tr>
<td align="left">UNPACK_SEQUENCE_TUPLE</td>
<td align="right">24,040</td>
<td align="right">0.0%</td>
</tr>
</tbody>
</table>


</details>

### DELETE_SUBSCR

<details>
<summary> Successors and predecessors for DELETE_SUBSCR </summary>

<table>
<thead>
<tr>
<th align="left">Predecessors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">LOAD_FAST_LOAD_FAST</td>
<td align="right">72,992,880</td>
<td align="right">98.6%</td>
</tr>
<tr>
<td align="left">BUILD_SLICE</td>
<td align="right">498,660</td>
<td align="right">0.7%</td>
</tr>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">285,677</td>
<td align="right">0.4%</td>
</tr>
<tr>
<td align="left">LOAD_CONST</td>
<td align="right">235,140</td>
<td align="right">0.3%</td>
</tr>
<tr>
<td align="left">CALL_NON_PY_GENERAL</td>
<td align="right">22,080</td>
<td align="right">0.0%</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Successors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">54,397,500</td>
<td align="right">73.5%</td>
</tr>
<tr>
<td align="left">LOAD_CONST</td>
<td align="right">18,106,757</td>
<td align="right">24.5%</td>
</tr>
<tr>
<td align="left">JUMP_BACKWARD</td>
<td align="right">984,900</td>
<td align="right">1.3%</td>
</tr>
<tr>
<td align="left">RETURN_CONST</td>
<td align="right">345,600</td>
<td align="right">0.5%</td>
</tr>
<tr>
<td align="left">LOAD_FAST_LOAD_FAST</td>
<td align="right">208,140</td>
<td align="right">0.3%</td>
</tr>
</tbody>
</table>


</details>

### BUILD_SLICE

<details>
<summary> Successors and predecessors for BUILD_SLICE </summary>

<table>
<thead>
<tr>
<th align="left">Predecessors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">LOAD_CONST</td>
<td align="right">105,585,900</td>
<td align="right">99.7%</td>
</tr>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">263,400</td>
<td align="right">0.2%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_INSTANCE_VALUE</td>
<td align="right">54,000</td>
<td align="right">0.1%</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Successors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">BINARY_SUBSCR</td>
<td align="right">105,404,640</td>
<td align="right">99.5%</td>
</tr>
<tr>
<td align="left">DELETE_SUBSCR</td>
<td align="right">498,660</td>
<td align="right">0.5%</td>
</tr>
</tbody>
</table>


</details>

### UNARY_NEGATIVE

<details>
<summary> Successors and predecessors for UNARY_NEGATIVE </summary>

<table>
<thead>
<tr>
<th align="left">Predecessors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">LOAD_ATTR</td>
<td align="right">14,647,440</td>
<td align="right">49.6%</td>
</tr>
<tr>
<td align="left">LOAD_FAST_LOAD_FAST</td>
<td align="right">8,002,383</td>
<td align="right">27.1%</td>
</tr>
<tr>
<td align="left">LOAD_GLOBAL_MODULE</td>
<td align="right">3,041,387</td>
<td align="right">10.3%</td>
</tr>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">1,871,895</td>
<td align="right">6.3%</td>
</tr>
<tr>
<td align="left">BINARY_SUBSCR_TUPLE_INT</td>
<td align="right">1,205,640</td>
<td align="right">4.1%</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Successors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">16,378,320</td>
<td align="right">55.4%</td>
</tr>
<tr>
<td align="left">CALL_PY_EXACT_ARGS</td>
<td align="right">3,126,360</td>
<td align="right">10.6%</td>
</tr>
<tr>
<td align="left">BINARY_SUBSCR</td>
<td align="right">2,419,140</td>
<td align="right">8.2%</td>
</tr>
<tr>
<td align="left">STORE_SUBSCR</td>
<td align="right">2,419,140</td>
<td align="right">8.2%</td>
</tr>
<tr>
<td align="left">BUILD_TUPLE</td>
<td align="right">1,921,320</td>
<td align="right">6.5%</td>
</tr>
</tbody>
</table>


</details>

### DELETE_FAST

<details>
<summary> Successors and predecessors for DELETE_FAST </summary>

<table>
<thead>
<tr>
<th align="left">Predecessors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">FOR_ITER</td>
<td align="right">958,080</td>
<td align="right">80.4%</td>
</tr>
<tr>
<td align="left">CALL_NON_PY_GENERAL</td>
<td align="right">81,000</td>
<td align="right">6.8%</td>
</tr>
<tr>
<td align="left">STORE_FAST</td>
<td align="right">67,560</td>
<td align="right">5.7%</td>
</tr>
<tr>
<td align="left">NOP</td>
<td align="right">18,000</td>
<td align="right">1.5%</td>
</tr>
<tr>
<td align="left">STORE_ATTR_INSTANCE_VALUE</td>
<td align="right">18,000</td>
<td align="right">1.5%</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Successors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">LOAD_GLOBAL_MODULE</td>
<td align="right">479,700</td>
<td align="right">40.3%</td>
</tr>
<tr>
<td align="left">BUILD_LIST</td>
<td align="right">479,040</td>
<td align="right">40.2%</td>
</tr>
<tr>
<td align="left">RETURN_VALUE</td>
<td align="right">138,600</td>
<td align="right">11.6%</td>
</tr>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">38,607</td>
<td align="right">3.2%</td>
</tr>
<tr>
<td align="left">RETURN_CONST</td>
<td align="right">36,000</td>
<td align="right">3.0%</td>
</tr>
</tbody>
</table>


</details>

### SET_ADD

<details>
<summary> Successors and predecessors for SET_ADD </summary>

<table>
<thead>
<tr>
<th align="left">Predecessors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">18,180</td>
<td align="right">67.5%</td>
</tr>
<tr>
<td align="left">RETURN_VALUE</td>
<td align="right">5,820</td>
<td align="right">21.6%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_PROPERTY</td>
<td align="right">2,940</td>
<td align="right">10.9%</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Successors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">JUMP_BACKWARD</td>
<td align="right">26,940</td>
<td align="right">100.0%</td>
</tr>
</tbody>
</table>


</details>

### STORE_ATTR_WITH_HINT

<details>
<summary> Successors and predecessors for STORE_ATTR_WITH_HINT </summary>

<table>
<thead>
<tr>
<th align="left">Predecessors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">15,735,622</td>
<td align="right">39.2%</td>
</tr>
<tr>
<td align="left">SWAP</td>
<td align="right">12,969,540</td>
<td align="right">32.3%</td>
</tr>
<tr>
<td align="left">LOAD_FAST_LOAD_FAST</td>
<td align="right">11,405,460</td>
<td align="right">28.4%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_INSTANCE_VALUE</td>
<td align="right">4,860</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">STORE_ATTR</td>
<td align="right">440</td>
<td align="right">0.0%</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Successors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">25,047,740</td>
<td align="right">62.4%</td>
</tr>
<tr>
<td align="left">JUMP_BACKWARD</td>
<td align="right">5,307,540</td>
<td align="right">13.2%</td>
</tr>
<tr>
<td align="left">RETURN_CONST</td>
<td align="right">3,772,544</td>
<td align="right">9.4%</td>
</tr>
<tr>
<td align="left">LOAD_CONST</td>
<td align="right">3,538,680</td>
<td align="right">8.8%</td>
</tr>
<tr>
<td align="left">LOAD_FAST_LOAD_FAST</td>
<td align="right">2,307,660</td>
<td align="right">5.8%</td>
</tr>
</tbody>
</table>


</details>

### STORE_GLOBAL

<details>
<summary> Successors and predecessors for STORE_GLOBAL </summary>

<table>
<thead>
<tr>
<th align="left">Predecessors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">BINARY_OP_ADD_INT</td>
<td align="right">6,147,600</td>
<td align="right">99.9%</td>
</tr>
<tr>
<td align="left">RETURN_VALUE</td>
<td align="right">3,900</td>
<td align="right">0.1%</td>
</tr>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">120</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">BUILD_MAP</td>
<td align="right">60</td>
<td align="right">0.0%</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Successors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">4,863,540</td>
<td align="right">79.1%</td>
</tr>
<tr>
<td align="left">LOAD_GLOBAL_MODULE</td>
<td align="right">1,285,980</td>
<td align="right">20.9%</td>
</tr>
<tr>
<td align="left">LOAD_CONST</td>
<td align="right">1,920</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">RETURN_CONST</td>
<td align="right">120</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">BUILD_MAP</td>
<td align="right">60</td>
<td align="right">0.0%</td>
</tr>
</tbody>
</table>


</details>

### UNPACK_EX

<details>
<summary> Successors and predecessors for UNPACK_EX </summary>

<table>
<thead>
<tr>
<th align="left">Predecessors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">280,800</td>
<td align="right">56.1%</td>
</tr>
<tr>
<td align="left">YIELD_VALUE</td>
<td align="right">218,520</td>
<td align="right">43.7%</td>
</tr>
<tr>
<td align="left">CALL_INTRINSIC_1</td>
<td align="right">960</td>
<td align="right">0.2%</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Successors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">STORE_FAST_STORE_FAST</td>
<td align="right">500,280</td>
<td align="right">100.0%</td>
</tr>
</tbody>
</table>


</details>

### INSTRUMENTED_RESUME

<details>
<summary> Successors and predecessors for INSTRUMENTED_RESUME </summary>

<table>
<thead>
<tr>
<th align="left">Predecessors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">CALL_PY_EXACT_ARGS</td>
<td align="right">14,567,400</td>
<td align="right">100.0%</td>
</tr>
<tr>
<td align="left">RESUME</td>
<td align="right">240</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">RESUME_CHECK</td>
<td align="right">120</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">INSTRUMENTED_RESUME</td>
<td align="right">60</td>
<td align="right">0.0%</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Successors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">14,567,400</td>
<td align="right">100.0%</td>
</tr>
<tr>
<td align="left">RESUME</td>
<td align="right">300</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">LOAD_GLOBAL</td>
<td align="right">60</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">INSTRUMENTED_RESUME</td>
<td align="right">60</td>
<td align="right">0.0%</td>
</tr>
</tbody>
</table>


</details>

### INSTRUMENTED_RETURN_VALUE

<details>
<summary> Successors and predecessors for INSTRUMENTED_RETURN_VALUE </summary>

<table>
<thead>
<tr>
<th align="left">Predecessors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">7,283,640</td>
<td align="right">50.0%</td>
</tr>
<tr>
<td align="left">BINARY_OP_ADD_INT</td>
<td align="right">7,283,520</td>
<td align="right">50.0%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_INSTANCE_VALUE</td>
<td align="right">60</td>
<td align="right">0.0%</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Successors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">BINARY_OP_ADD_INT</td>
<td align="right">7,283,520</td>
<td align="right">50.0%</td>
</tr>
<tr>
<td align="left">LOAD_GLOBAL_MODULE</td>
<td align="right">7,283,520</td>
<td align="right">50.0%</td>
</tr>
<tr>
<td align="left">STORE_FAST</td>
<td align="right">120</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">POP_TOP</td>
<td align="right">60</td>
<td align="right">0.0%</td>
</tr>
</tbody>
</table>


</details>

### INSTRUMENTED_RETURN_CONST

<details>
<summary> Successors and predecessors for INSTRUMENTED_RETURN_CONST </summary>

<table>
<thead>
<tr>
<th align="left">Predecessors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">POP_TOP</td>
<td align="right">60</td>
<td align="right">33.3%</td>
</tr>
<tr>
<td align="left">CALL_LIST_APPEND</td>
<td align="right">60</td>
<td align="right">33.3%</td>
</tr>
<tr>
<td align="left">STORE_GLOBAL</td>
<td align="right">60</td>
<td align="right">33.3%</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Successors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">POP_TOP</td>
<td align="right">180</td>
<td align="right">100.0%</td>
</tr>
</tbody>
</table>


</details>

### INSTRUMENTED_JUMP_BACKWARD

<details>
<summary> Successors and predecessors for INSTRUMENTED_JUMP_BACKWARD </summary>

<table>
<thead>
<tr>
<th align="left">Predecessors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">POP_TOP</td>
<td align="right">60</td>
<td align="right">100.0%</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Successors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">FOR_ITER</td>
<td align="right">60</td>
<td align="right">100.0%</td>
</tr>
</tbody>
</table>


</details>

### WITH_EXCEPT_START

<details>
<summary> Successors and predecessors for WITH_EXCEPT_START </summary>

<table>
<thead>
<tr>
<th align="left">Predecessors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">PUSH_EXC_INFO</td>
<td align="right">4,800</td>
<td align="right">100.0%</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Successors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">TO_BOOL_NONE</td>
<td align="right">4,800</td>
<td align="right">100.0%</td>
</tr>
</tbody>
</table>


</details>

### CLEANUP_THROW

<details>
<summary> Successors and predecessors for CLEANUP_THROW </summary>

<table>
<thead>
<tr>
<th align="left">Predecessors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">CACHE</td>
<td align="right">480</td>
<td align="right">100.0%</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Successors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">CALL_INTRINSIC_1</td>
<td align="right">480</td>
<td align="right">100.0%</td>
</tr>
</tbody>
</table>


</details>

### SET_UPDATE

<details>
<summary> Successors and predecessors for SET_UPDATE </summary>

<table>
<thead>
<tr>
<th align="left">Predecessors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">LOAD_CONST</td>
<td align="right">120</td>
<td align="right">100.0%</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Successors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">LOAD_GLOBAL_BUILTIN</td>
<td align="right">120</td>
<td align="right">100.0%</td>
</tr>
</tbody>
</table>


</details>


</details>

## Specialization stats

<details>
<summary> Specialization stats by family </summary>

### BINARY_OP

<details>
<summary> specialization stats for BINARY_OP family </summary>

<table>
<thead>
<tr>
<th align="left">Kind</th>
<th align="right">Count</th>
<th align="right">Ratio</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">
deferred
<details>
<summary>ⓘ</summary>

Lists the number of "deferred" (i.e. not specialized) instructions executed.
</details>
</td>
<td align="right">999,982,037</td>
<td align="right">21.7%</td>
</tr>
<tr>
<td align="left">
hit
<details>
<summary>ⓘ</summary>

Specialized instructions that complete.
</details>
</td>
<td align="right">3,614,843,833</td>
<td align="right">78.3%</td>
</tr>
<tr>
<td align="left">
miss
<details>
<summary>ⓘ</summary>

Specialized instructions that deopt.
</details>
</td>
<td align="right">37,654,780</td>
<td align="right">0.8%</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Success</th>
<th align="right">Count</th>
<th align="right">Ratio</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">Success</td>
<td align="right">714,273</td>
<td align="right">38.5%</td>
</tr>
<tr>
<td align="left">Failure</td>
<td align="right">1,142,176</td>
<td align="right">61.5%</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Failure kind</th>
<th align="right">Count</th>
<th align="right">Ratio</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">subtract different types</td>
<td align="right">580,468</td>
<td align="right">50.8%</td>
</tr>
<tr>
<td align="left">multiply different types</td>
<td align="right">172,294</td>
<td align="right">15.1%</td>
</tr>
<tr>
<td align="left">add different types</td>
<td align="right">153,462</td>
<td align="right">13.4%</td>
</tr>
<tr>
<td align="left">remainder</td>
<td align="right">37,908</td>
<td align="right">3.3%</td>
</tr>
<tr>
<td align="left">floor divide</td>
<td align="right">33,240</td>
<td align="right">2.9%</td>
</tr>
<tr>
<td align="left">and int</td>
<td align="right">32,134</td>
<td align="right">2.8%</td>
</tr>
<tr>
<td align="left">add other</td>
<td align="right">24,101</td>
<td align="right">2.1%</td>
</tr>
<tr>
<td align="left">rshift</td>
<td align="right">23,039</td>
<td align="right">2.0%</td>
</tr>
<tr>
<td align="left">lshift</td>
<td align="right">19,140</td>
<td align="right">1.7%</td>
</tr>
<tr>
<td align="left">xor</td>
<td align="right">18,319</td>
<td align="right">1.6%</td>
</tr>
<tr>
<td align="left">true divide different types</td>
<td align="right">18,280</td>
<td align="right">1.6%</td>
</tr>
<tr>
<td align="left">subtract other</td>
<td align="right">8,040</td>
<td align="right">0.7%</td>
</tr>
<tr>
<td align="left">true divide float</td>
<td align="right">7,120</td>
<td align="right">0.6%</td>
</tr>
<tr>
<td align="left">power</td>
<td align="right">5,140</td>
<td align="right">0.5%</td>
</tr>
<tr>
<td align="left">or</td>
<td align="right">4,781</td>
<td align="right">0.4%</td>
</tr>
<tr>
<td align="left">multiply other</td>
<td align="right">2,560</td>
<td align="right">0.2%</td>
</tr>
<tr>
<td align="left">true divide other</td>
<td align="right">1,140</td>
<td align="right">0.1%</td>
</tr>
<tr>
<td align="left">and other</td>
<td align="right">970</td>
<td align="right">0.1%</td>
</tr>
<tr>
<td align="left">and different types</td>
<td align="right">40</td>
<td align="right">0.0%</td>
</tr>
</tbody>
</table>


</details>

### BINARY_SLICE

<details>
<summary> specialization stats for BINARY_SLICE family </summary>


</details>

### BINARY_SUBSCR

<details>
<summary> specialization stats for BINARY_SUBSCR family </summary>

<table>
<thead>
<tr>
<th align="left">Kind</th>
<th align="right">Count</th>
<th align="right">Ratio</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">
deferred
<details>
<summary>ⓘ</summary>

Lists the number of "deferred" (i.e. not specialized) instructions executed.
</details>
</td>
<td align="right">1,037,934,322</td>
<td align="right">41.3%</td>
</tr>
<tr>
<td align="left">
hit
<details>
<summary>ⓘ</summary>

Specialized instructions that complete.
</details>
</td>
<td align="right">1,471,958,378</td>
<td align="right">58.6%</td>
</tr>
<tr>
<td align="left">
miss
<details>
<summary>ⓘ</summary>

Specialized instructions that deopt.
</details>
</td>
<td align="right">3,378,999</td>
<td align="right">0.1%</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Success</th>
<th align="right">Count</th>
<th align="right">Ratio</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">Success</td>
<td align="right">65,437</td>
<td align="right">19.8%</td>
</tr>
<tr>
<td align="left">Failure</td>
<td align="right">265,832</td>
<td align="right">80.2%</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Failure kind</th>
<th align="right">Count</th>
<th align="right">Ratio</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">array int</td>
<td align="right">118,820</td>
<td align="right">44.7%</td>
</tr>
<tr>
<td align="left">other</td>
<td align="right">77,914</td>
<td align="right">29.3%</td>
</tr>
<tr>
<td align="left">buffer int</td>
<td align="right">27,518</td>
<td align="right">10.4%</td>
</tr>
<tr>
<td align="left">list slice</td>
<td align="right">25,580</td>
<td align="right">9.6%</td>
</tr>
<tr>
<td align="left">out of range</td>
<td align="right">12,860</td>
<td align="right">4.8%</td>
</tr>
<tr>
<td align="left">sequence int</td>
<td align="right">2,920</td>
<td align="right">1.1%</td>
</tr>
<tr>
<td align="left">buffer slice</td>
<td align="right">180</td>
<td align="right">0.1%</td>
</tr>
<tr>
<td align="left">tuple slice</td>
<td align="right">20</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">string slice</td>
<td align="right">20</td>
<td align="right">0.0%</td>
</tr>
</tbody>
</table>


</details>

### CALL

<details>
<summary> specialization stats for CALL family </summary>

<table>
<thead>
<tr>
<th align="left">Kind</th>
<th align="right">Count</th>
<th align="right">Ratio</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">
deferred
<details>
<summary>ⓘ</summary>

Lists the number of "deferred" (i.e. not specialized) instructions executed.
</details>
</td>
<td align="right">130,633,853</td>
<td align="right">2.0%</td>
</tr>
<tr>
<td align="left">
deopt
<details>
<summary>ⓘ</summary>

Specialized instructions that deopt.
</details>
</td>
<td align="right">12,000</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">
hit
<details>
<summary>ⓘ</summary>

Specialized instructions that complete.
</details>
</td>
<td align="right">6,408,925,022</td>
<td align="right">98.0%</td>
</tr>
<tr>
<td align="left">
miss
<details>
<summary>ⓘ</summary>

Specialized instructions that deopt.
</details>
</td>
<td align="right">99,079,326</td>
<td align="right">1.5%</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Success</th>
<th align="right">Count</th>
<th align="right">Ratio</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">Success</td>
<td align="right">1,919,439</td>
<td align="right">99.1%</td>
</tr>
<tr>
<td align="left">Failure</td>
<td align="right">17,220</td>
<td align="right">0.9%</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Failure kind</th>
<th align="right">Count</th>
<th align="right">Ratio</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">class no vectorcall</td>
<td align="right">15,120</td>
<td align="right">87.8%</td>
</tr>
<tr>
<td align="left">wrong number arguments</td>
<td align="right">2,060</td>
<td align="right">12.0%</td>
</tr>
<tr>
<td align="left">init not simple</td>
<td align="right">200</td>
<td align="right">1.2%</td>
</tr>
<tr>
<td align="left">init not inline values</td>
<td align="right">140</td>
<td align="right">0.8%</td>
</tr>
<tr>
<td align="left">out of versions</td>
<td align="right">40</td>
<td align="right">0.2%</td>
</tr>
<tr>
<td align="left">init not python</td>
<td align="right">40</td>
<td align="right">0.2%</td>
</tr>
</tbody>
</table>


</details>

### COMPARE_OP

<details>
<summary> specialization stats for COMPARE_OP family </summary>

<table>
<thead>
<tr>
<th align="left">Kind</th>
<th align="right">Count</th>
<th align="right">Ratio</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">
deferred
<details>
<summary>ⓘ</summary>

Lists the number of "deferred" (i.e. not specialized) instructions executed.
</details>
</td>
<td align="right">143,456,931</td>
<td align="right">8.1%</td>
</tr>
<tr>
<td align="left">
hit
<details>
<summary>ⓘ</summary>

Specialized instructions that complete.
</details>
</td>
<td align="right">1,630,497,900</td>
<td align="right">91.9%</td>
</tr>
<tr>
<td align="left">
miss
<details>
<summary>ⓘ</summary>

Specialized instructions that deopt.
</details>
</td>
<td align="right">977,354</td>
<td align="right">0.1%</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Success</th>
<th align="right">Count</th>
<th align="right">Ratio</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">Success</td>
<td align="right">22,212</td>
<td align="right">19.3%</td>
</tr>
<tr>
<td align="left">Failure</td>
<td align="right">92,738</td>
<td align="right">80.7%</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Failure kind</th>
<th align="right">Count</th>
<th align="right">Ratio</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">different types</td>
<td align="right">25,479</td>
<td align="right">27.5%</td>
</tr>
<tr>
<td align="left">big int</td>
<td align="right">22,195</td>
<td align="right">23.9%</td>
</tr>
<tr>
<td align="left">float long</td>
<td align="right">13,221</td>
<td align="right">14.3%</td>
</tr>
<tr>
<td align="left">string</td>
<td align="right">7,040</td>
<td align="right">7.6%</td>
</tr>
<tr>
<td align="left">set</td>
<td align="right">6,662</td>
<td align="right">7.2%</td>
</tr>
<tr>
<td align="left">other</td>
<td align="right">6,226</td>
<td align="right">6.7%</td>
</tr>
<tr>
<td align="left">baseobject</td>
<td align="right">6,202</td>
<td align="right">6.7%</td>
</tr>
<tr>
<td align="left">tuple</td>
<td align="right">3,296</td>
<td align="right">3.6%</td>
</tr>
<tr>
<td align="left">bool</td>
<td align="right">1,557</td>
<td align="right">1.7%</td>
</tr>
<tr>
<td align="left">list</td>
<td align="right">340</td>
<td align="right">0.4%</td>
</tr>
<tr>
<td align="left">bytes</td>
<td align="right">320</td>
<td align="right">0.3%</td>
</tr>
<tr>
<td align="left">long float</td>
<td align="right">200</td>
<td align="right">0.2%</td>
</tr>
</tbody>
</table>


</details>

### CONTAINS_OP

<details>
<summary> specialization stats for CONTAINS_OP family </summary>

<table>
<thead>
<tr>
<th align="left">Kind</th>
<th align="right">Count</th>
<th align="right">Ratio</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">
deferred
<details>
<summary>ⓘ</summary>

Lists the number of "deferred" (i.e. not specialized) instructions executed.
</details>
</td>
<td align="right">173,340,749</td>
<td align="right">25.6%</td>
</tr>
<tr>
<td align="left">
hit
<details>
<summary>ⓘ</summary>

Specialized instructions that complete.
</details>
</td>
<td align="right">503,307,821</td>
<td align="right">74.4%</td>
</tr>
<tr>
<td align="left">
miss
<details>
<summary>ⓘ</summary>

Specialized instructions that deopt.
</details>
</td>
<td align="right">1,249,640</td>
<td align="right">0.2%</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Success</th>
<th align="right">Count</th>
<th align="right">Ratio</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">Success</td>
<td align="right">24,000</td>
<td align="right">32.1%</td>
</tr>
<tr>
<td align="left">Failure</td>
<td align="right">50,693</td>
<td align="right">67.9%</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Failure kind</th>
<th align="right">Count</th>
<th align="right">Ratio</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">str</td>
<td align="right">28,220</td>
<td align="right">55.7%</td>
</tr>
<tr>
<td align="left">list</td>
<td align="right">12,040</td>
<td align="right">23.8%</td>
</tr>
<tr>
<td align="left">other</td>
<td align="right">6,098</td>
<td align="right">12.0%</td>
</tr>
<tr>
<td align="left">tuple</td>
<td align="right">4,335</td>
<td align="right">8.6%</td>
</tr>
</tbody>
</table>


</details>

### FOR_ITER

<details>
<summary> specialization stats for FOR_ITER family </summary>

<table>
<thead>
<tr>
<th align="left">Kind</th>
<th align="right">Count</th>
<th align="right">Ratio</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">
deferred
<details>
<summary>ⓘ</summary>

Lists the number of "deferred" (i.e. not specialized) instructions executed.
</details>
</td>
<td align="right">473,916,353</td>
<td align="right">20.8%</td>
</tr>
<tr>
<td align="left">
hit
<details>
<summary>ⓘ</summary>

Specialized instructions that complete.
</details>
</td>
<td align="right">1,801,363,644</td>
<td align="right">79.1%</td>
</tr>
<tr>
<td align="left">
miss
<details>
<summary>ⓘ</summary>

Specialized instructions that deopt.
</details>
</td>
<td align="right">129,656,500</td>
<td align="right">5.7%</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Success</th>
<th align="right">Count</th>
<th align="right">Ratio</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">Success</td>
<td align="right">2,446,730</td>
<td align="right">94.7%</td>
</tr>
<tr>
<td align="left">Failure</td>
<td align="right">137,392</td>
<td align="right">5.3%</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Failure kind</th>
<th align="right">Count</th>
<th align="right">Ratio</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">dict items</td>
<td align="right">56,249</td>
<td align="right">40.9%</td>
</tr>
<tr>
<td align="left">enumerate</td>
<td align="right">21,039</td>
<td align="right">15.3%</td>
</tr>
<tr>
<td align="left">seq iter</td>
<td align="right">20,300</td>
<td align="right">14.8%</td>
</tr>
<tr>
<td align="left">set</td>
<td align="right">11,624</td>
<td align="right">8.5%</td>
</tr>
<tr>
<td align="left">other</td>
<td align="right">10,080</td>
<td align="right">7.3%</td>
</tr>
<tr>
<td align="left">zip</td>
<td align="right">6,060</td>
<td align="right">4.4%</td>
</tr>
<tr>
<td align="left">dict values</td>
<td align="right">4,700</td>
<td align="right">3.4%</td>
</tr>
<tr>
<td align="left">ascii string</td>
<td align="right">2,440</td>
<td align="right">1.8%</td>
</tr>
<tr>
<td align="left">itertools</td>
<td align="right">2,240</td>
<td align="right">1.6%</td>
</tr>
<tr>
<td align="left">dict keys</td>
<td align="right">1,480</td>
<td align="right">1.1%</td>
</tr>
<tr>
<td align="left">reversed list</td>
<td align="right">660</td>
<td align="right">0.5%</td>
</tr>
<tr>
<td align="left">map</td>
<td align="right">400</td>
<td align="right">0.3%</td>
</tr>
<tr>
<td align="left">callable</td>
<td align="right">80</td>
<td align="right">0.1%</td>
</tr>
<tr>
<td align="left">bytes</td>
<td align="right">40</td>
<td align="right">0.0%</td>
</tr>
</tbody>
</table>


</details>

### LOAD_ATTR

<details>
<summary> specialization stats for LOAD_ATTR family </summary>

<table>
<thead>
<tr>
<th align="left">Kind</th>
<th align="right">Count</th>
<th align="right">Ratio</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">
deferred
<details>
<summary>ⓘ</summary>

Lists the number of "deferred" (i.e. not specialized) instructions executed.
</details>
</td>
<td align="right">1,518,860,729</td>
<td align="right">15.8%</td>
</tr>
<tr>
<td align="left">
hit
<details>
<summary>ⓘ</summary>

Specialized instructions that complete.
</details>
</td>
<td align="right">8,109,107,557</td>
<td align="right">84.1%</td>
</tr>
<tr>
<td align="left">
miss
<details>
<summary>ⓘ</summary>

Specialized instructions that deopt.
</details>
</td>
<td align="right">492,424,929</td>
<td align="right">5.1%</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Success</th>
<th align="right">Count</th>
<th align="right">Ratio</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">Success</td>
<td align="right">9,340,662</td>
<td align="right">87.1%</td>
</tr>
<tr>
<td align="left">Failure</td>
<td align="right">1,381,700</td>
<td align="right">12.9%</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Failure kind</th>
<th align="right">Count</th>
<th align="right">Ratio</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">not managed dict</td>
<td align="right">621,455</td>
<td align="right">45.0%</td>
</tr>
<tr>
<td align="left">class attr simple</td>
<td align="right">507,948</td>
<td align="right">36.8%</td>
</tr>
<tr>
<td align="left">metaclass attribute</td>
<td align="right">112,982</td>
<td align="right">8.2%</td>
</tr>
<tr>
<td align="left">method</td>
<td align="right">54,792</td>
<td align="right">4.0%</td>
</tr>
<tr>
<td align="left">shadowed</td>
<td align="right">33,489</td>
<td align="right">2.4%</td>
</tr>
<tr>
<td align="left">mutable class</td>
<td align="right">19,738</td>
<td align="right">1.4%</td>
</tr>
<tr>
<td align="left">overridden</td>
<td align="right">7,743</td>
<td align="right">0.6%</td>
</tr>
<tr>
<td align="left">class method obj</td>
<td align="right">6,781</td>
<td align="right">0.5%</td>
</tr>
<tr>
<td align="left">class attr descriptor</td>
<td align="right">6,100</td>
<td align="right">0.4%</td>
</tr>
<tr>
<td align="left">non object slot</td>
<td align="right">4,180</td>
<td align="right">0.3%</td>
</tr>
<tr>
<td align="left">non string or split</td>
<td align="right">1,780</td>
<td align="right">0.1%</td>
</tr>
<tr>
<td align="left">not in keys</td>
<td align="right">1,680</td>
<td align="right">0.1%</td>
</tr>
<tr>
<td align="left">non overriding descriptor</td>
<td align="right">1,032</td>
<td align="right">0.1%</td>
</tr>
<tr>
<td align="left">module attr not found</td>
<td align="right">940</td>
<td align="right">0.1%</td>
</tr>
<tr>
<td align="left">builtin class method</td>
<td align="right">660</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">out of versions</td>
<td align="right">400</td>
<td align="right">0.0%</td>
</tr>
</tbody>
</table>


</details>

### LOAD_GLOBAL

<details>
<summary> specialization stats for LOAD_GLOBAL family </summary>

<table>
<thead>
<tr>
<th align="left">Kind</th>
<th align="right">Count</th>
<th align="right">Ratio</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">
deferred
<details>
<summary>ⓘ</summary>

Lists the number of "deferred" (i.e. not specialized) instructions executed.
</details>
</td>
<td align="right">7,301,068</td>
<td align="right">0.1%</td>
</tr>
<tr>
<td align="left">
deopt
<details>
<summary>ⓘ</summary>

Specialized instructions that deopt.
</details>
</td>
<td align="right">600</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">
hit
<details>
<summary>ⓘ</summary>

Specialized instructions that complete.
</details>
</td>
<td align="right">5,455,021,881</td>
<td align="right">99.9%</td>
</tr>
<tr>
<td align="left">
miss
<details>
<summary>ⓘ</summary>

Specialized instructions that deopt.
</details>
</td>
<td align="right">14,780</td>
<td align="right">0.0%</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Success</th>
<th align="right">Count</th>
<th align="right">Ratio</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">Success</td>
<td align="right">42,057</td>
<td align="right">100.0%</td>
</tr>
<tr>
<td align="left">Failure</td>
<td align="right">0</td>
<td align="right">0.0%</td>
</tr>
</tbody>
</table>


</details>

### LOAD_SUPER_ATTR

<details>
<summary> specialization stats for LOAD_SUPER_ATTR family </summary>

<table>
<thead>
<tr>
<th align="left">Kind</th>
<th align="right">Count</th>
<th align="right">Ratio</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">
hit
<details>
<summary>ⓘ</summary>

Specialized instructions that complete.
</details>
</td>
<td align="right">44,634,479</td>
<td align="right">100.0%</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Success</th>
<th align="right">Count</th>
<th align="right">Ratio</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">Success</td>
<td align="right">860</td>
<td align="right">100.0%</td>
</tr>
<tr>
<td align="left">Failure</td>
<td align="right">0</td>
<td align="right">0.0%</td>
</tr>
</tbody>
</table>


</details>

### POP_JUMP_IF_FALSE

<details>
<summary> specialization stats for POP_JUMP_IF_FALSE family </summary>


</details>

### POP_JUMP_IF_NONE

<details>
<summary> specialization stats for POP_JUMP_IF_NONE family </summary>


</details>

### POP_JUMP_IF_NOT_NONE

<details>
<summary> specialization stats for POP_JUMP_IF_NOT_NONE family </summary>


</details>

### POP_JUMP_IF_TRUE

<details>
<summary> specialization stats for POP_JUMP_IF_TRUE family </summary>


</details>

### SEND

<details>
<summary> specialization stats for SEND family </summary>

<table>
<thead>
<tr>
<th align="left">Kind</th>
<th align="right">Count</th>
<th align="right">Ratio</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">
deferred
<details>
<summary>ⓘ</summary>

Lists the number of "deferred" (i.e. not specialized) instructions executed.
</details>
</td>
<td align="right">111,586,880</td>
<td align="right">18.6%</td>
</tr>
<tr>
<td align="left">
hit
<details>
<summary>ⓘ</summary>

Specialized instructions that complete.
</details>
</td>
<td align="right">487,998,608</td>
<td align="right">81.4%</td>
</tr>
<tr>
<td align="left">
miss
<details>
<summary>ⓘ</summary>

Specialized instructions that deopt.
</details>
</td>
<td align="right">13,020</td>
<td align="right">0.0%</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Success</th>
<th align="right">Count</th>
<th align="right">Ratio</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">Success</td>
<td align="right">260</td>
<td align="right">0.9%</td>
</tr>
<tr>
<td align="left">Failure</td>
<td align="right">28,520</td>
<td align="right">99.1%</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Failure kind</th>
<th align="right">Count</th>
<th align="right">Ratio</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">async generator send</td>
<td align="right">24,440</td>
<td align="right">85.7%</td>
</tr>
<tr>
<td align="left">other</td>
<td align="right">3,100</td>
<td align="right">10.9%</td>
</tr>
<tr>
<td align="left">list</td>
<td align="right">980</td>
<td align="right">3.4%</td>
</tr>
</tbody>
</table>


</details>

### STORE_ATTR

<details>
<summary> specialization stats for STORE_ATTR family </summary>

<table>
<thead>
<tr>
<th align="left">Kind</th>
<th align="right">Count</th>
<th align="right">Ratio</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">
deferred
<details>
<summary>ⓘ</summary>

Lists the number of "deferred" (i.e. not specialized) instructions executed.
</details>
</td>
<td align="right">124,067,732</td>
<td align="right">9.4%</td>
</tr>
<tr>
<td align="left">
hit
<details>
<summary>ⓘ</summary>

Specialized instructions that complete.
</details>
</td>
<td align="right">1,197,431,873</td>
<td align="right">90.5%</td>
</tr>
<tr>
<td align="left">
miss
<details>
<summary>ⓘ</summary>

Specialized instructions that deopt.
</details>
</td>
<td align="right">76,791,073</td>
<td align="right">5.8%</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Success</th>
<th align="right">Count</th>
<th align="right">Ratio</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">Success</td>
<td align="right">1,463,284</td>
<td align="right">98.2%</td>
</tr>
<tr>
<td align="left">Failure</td>
<td align="right">26,128</td>
<td align="right">1.8%</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Failure kind</th>
<th align="right">Count</th>
<th align="right">Ratio</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">class attr simple</td>
<td align="right">11,940</td>
<td align="right">45.7%</td>
</tr>
<tr>
<td align="left">overriding descriptor</td>
<td align="right">5,660</td>
<td align="right">21.7%</td>
</tr>
<tr>
<td align="left">not in dict</td>
<td align="right">3,000</td>
<td align="right">11.5%</td>
</tr>
<tr>
<td align="left">non string or split</td>
<td align="right">1,320</td>
<td align="right">5.1%</td>
</tr>
<tr>
<td align="left">no dict</td>
<td align="right">1,040</td>
<td align="right">4.0%</td>
</tr>
<tr>
<td align="left">property</td>
<td align="right">940</td>
<td align="right">3.6%</td>
</tr>
<tr>
<td align="left">not in keys</td>
<td align="right">900</td>
<td align="right">3.4%</td>
</tr>
<tr>
<td align="left">not managed dict</td>
<td align="right">582</td>
<td align="right">2.2%</td>
</tr>
<tr>
<td align="left">overridden</td>
<td align="right">446</td>
<td align="right">1.7%</td>
</tr>
<tr>
<td align="left">method</td>
<td align="right">240</td>
<td align="right">0.9%</td>
</tr>
<tr>
<td align="left">non object slot</td>
<td align="right">60</td>
<td align="right">0.2%</td>
</tr>
</tbody>
</table>


</details>

### STORE_SLICE

<details>
<summary> specialization stats for STORE_SLICE family </summary>


</details>

### STORE_SUBSCR

<details>
<summary> specialization stats for STORE_SUBSCR family </summary>

<table>
<thead>
<tr>
<th align="left">Kind</th>
<th align="right">Count</th>
<th align="right">Ratio</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">
deferred
<details>
<summary>ⓘ</summary>

Lists the number of "deferred" (i.e. not specialized) instructions executed.
</details>
</td>
<td align="right">300,534,648</td>
<td align="right">40.3%</td>
</tr>
<tr>
<td align="left">
hit
<details>
<summary>ⓘ</summary>

Specialized instructions that complete.
</details>
</td>
<td align="right">444,539,352</td>
<td align="right">59.7%</td>
</tr>
<tr>
<td align="left">
miss
<details>
<summary>ⓘ</summary>

Specialized instructions that deopt.
</details>
</td>
<td align="right">2,220</td>
<td align="right">0.0%</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Success</th>
<th align="right">Count</th>
<th align="right">Ratio</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">Success</td>
<td align="right">1,040</td>
<td align="right">1.3%</td>
</tr>
<tr>
<td align="left">Failure</td>
<td align="right">77,480</td>
<td align="right">98.7%</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Failure kind</th>
<th align="right">Count</th>
<th align="right">Ratio</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">array int</td>
<td align="right">48,560</td>
<td align="right">62.7%</td>
</tr>
<tr>
<td align="left">dict subclass no override</td>
<td align="right">18,240</td>
<td align="right">23.5%</td>
</tr>
<tr>
<td align="left">bytearray int</td>
<td align="right">5,200</td>
<td align="right">6.7%</td>
</tr>
<tr>
<td align="left">py simple</td>
<td align="right">4,420</td>
<td align="right">5.7%</td>
</tr>
<tr>
<td align="left">out of range</td>
<td align="right">940</td>
<td align="right">1.2%</td>
</tr>
<tr>
<td align="left">other</td>
<td align="right">120</td>
<td align="right">0.2%</td>
</tr>
</tbody>
</table>


</details>

### TO_BOOL

<details>
<summary> specialization stats for TO_BOOL family </summary>

<table>
<thead>
<tr>
<th align="left">Kind</th>
<th align="right">Count</th>
<th align="right">Ratio</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">
deferred
<details>
<summary>ⓘ</summary>

Lists the number of "deferred" (i.e. not specialized) instructions executed.
</details>
</td>
<td align="right">249,491,559</td>
<td align="right">6.7%</td>
</tr>
<tr>
<td align="left">
hit
<details>
<summary>ⓘ</summary>

Specialized instructions that complete.
</details>
</td>
<td align="right">3,459,683,185</td>
<td align="right">93.2%</td>
</tr>
<tr>
<td align="left">
miss
<details>
<summary>ⓘ</summary>

Specialized instructions that deopt.
</details>
</td>
<td align="right">54,900,752</td>
<td align="right">1.5%</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Success</th>
<th align="right">Count</th>
<th align="right">Ratio</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">Success</td>
<td align="right">1,048,678</td>
<td align="right">78.1%</td>
</tr>
<tr>
<td align="left">Failure</td>
<td align="right">294,549</td>
<td align="right">21.9%</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Failure kind</th>
<th align="right">Count</th>
<th align="right">Ratio</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">number</td>
<td align="right">127,317</td>
<td align="right">43.2%</td>
</tr>
<tr>
<td align="left">mapping</td>
<td align="right">64,823</td>
<td align="right">22.0%</td>
</tr>
<tr>
<td align="left">tuple</td>
<td align="right">61,646</td>
<td align="right">20.9%</td>
</tr>
<tr>
<td align="left">dict</td>
<td align="right">10,868</td>
<td align="right">3.7%</td>
</tr>
<tr>
<td align="left">set</td>
<td align="right">9,502</td>
<td align="right">3.2%</td>
</tr>
<tr>
<td align="left">bytes</td>
<td align="right">8,860</td>
<td align="right">3.0%</td>
</tr>
<tr>
<td align="left">sequence</td>
<td align="right">6,238</td>
<td align="right">2.1%</td>
</tr>
<tr>
<td align="left">other</td>
<td align="right">4,615</td>
<td align="right">1.6%</td>
</tr>
<tr>
<td align="left">float</td>
<td align="right">600</td>
<td align="right">0.2%</td>
</tr>
<tr>
<td align="left">bytearray</td>
<td align="right">80</td>
<td align="right">0.0%</td>
</tr>
</tbody>
</table>


</details>

### UNPACK_SEQUENCE

<details>
<summary> specialization stats for UNPACK_SEQUENCE family </summary>

<table>
<thead>
<tr>
<th align="left">Kind</th>
<th align="right">Count</th>
<th align="right">Ratio</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">
deferred
<details>
<summary>ⓘ</summary>

Lists the number of "deferred" (i.e. not specialized) instructions executed.
</details>
</td>
<td align="right">2,610,563</td>
<td align="right">0.2%</td>
</tr>
<tr>
<td align="left">
hit
<details>
<summary>ⓘ</summary>

Specialized instructions that complete.
</details>
</td>
<td align="right">1,324,127,034</td>
<td align="right">99.8%</td>
</tr>
<tr>
<td align="left">
miss
<details>
<summary>ⓘ</summary>

Specialized instructions that deopt.
</details>
</td>
<td align="right">2,547,700</td>
<td align="right">0.2%</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Success</th>
<th align="right">Count</th>
<th align="right">Ratio</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">Success</td>
<td align="right">51,180</td>
<td align="right">99.1%</td>
</tr>
<tr>
<td align="left">Failure</td>
<td align="right">445</td>
<td align="right">0.9%</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Failure kind</th>
<th align="right">Count</th>
<th align="right">Ratio</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">sequence</td>
<td align="right">285</td>
<td align="right">64.0%</td>
</tr>
<tr>
<td align="left">other</td>
<td align="right">80</td>
<td align="right">18.0%</td>
</tr>
<tr>
<td align="left">iterator</td>
<td align="right">80</td>
<td align="right">18.0%</td>
</tr>
</tbody>
</table>


</details>


</details>

## Specialization effectiveness

<details>
<summary> specialization effectiveness </summary>


All entries are execution counts. Should add up to the total number of
Tier 1 instructions executed.

<table>
<thead>
<tr>
<th align="left">Instructions</th>
<th align="right">Count</th>
<th align="right">Ratio</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">
Basic
<details>
<summary>ⓘ</summary>

Instructions that are not and cannot be specialized, e.g. `LOAD_FAST`.
</details>
</td>
<td align="right">62,229,394,459</td>
<td align="right">53.7%</td>
</tr>
<tr>
<td align="left">
Not specialized
<details>
<summary>ⓘ</summary>

Instructions that could be specialized but aren't, e.g. `LOAD_ATTR`, `BINARY_SLICE`.
</details>
</td>
<td align="right">11,788,140,924</td>
<td align="right">10.2%</td>
</tr>
<tr>
<td align="left">
Specialized hits
<details>
<summary>ⓘ</summary>

Specialized instructions, e.g. `LOAD_ATTR_MODULE` that complete.
</details>
</td>
<td align="right">40,948,670,461</td>
<td align="right">35.3%</td>
</tr>
<tr>
<td align="left">
Specialized misses
<details>
<summary>ⓘ</summary>

Specialized instructions, e.g. `LOAD_ATTR_MODULE` that deopt.
</details>
</td>
<td align="right">898,786,211</td>
<td align="right">0.8%</td>
</tr>
</tbody>
</table>

### Deferred by instruction

<details>
<summary> Breakdown of deferred (not specialized) instruction counts by family </summary>

<table>
<thead>
<tr>
<th align="left">Name</th>
<th align="right">Count</th>
<th align="right">Ratio</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">LOAD_ATTR</td>
<td align="right">1,518,860,729</td>
<td align="right">28.8%</td>
</tr>
<tr>
<td align="left">BINARY_SUBSCR</td>
<td align="right">1,037,934,322</td>
<td align="right">19.7%</td>
</tr>
<tr>
<td align="left">BINARY_OP</td>
<td align="right">999,982,037</td>
<td align="right">19.0%</td>
</tr>
<tr>
<td align="left">FOR_ITER</td>
<td align="right">473,916,353</td>
<td align="right">9.0%</td>
</tr>
<tr>
<td align="left">STORE_SUBSCR</td>
<td align="right">300,534,648</td>
<td align="right">5.7%</td>
</tr>
<tr>
<td align="left">TO_BOOL</td>
<td align="right">249,491,559</td>
<td align="right">4.7%</td>
</tr>
<tr>
<td align="left">CONTAINS_OP</td>
<td align="right">173,340,749</td>
<td align="right">3.3%</td>
</tr>
<tr>
<td align="left">COMPARE_OP</td>
<td align="right">143,456,931</td>
<td align="right">2.7%</td>
</tr>
<tr>
<td align="left">CALL</td>
<td align="right">130,633,853</td>
<td align="right">2.5%</td>
</tr>
<tr>
<td align="left">STORE_ATTR</td>
<td align="right">124,067,732</td>
<td align="right">2.4%</td>
</tr>
</tbody>
</table>


</details>

### Misses by instruction

<details>
<summary> Breakdown of misses (specialized deopts) instruction counts by family </summary>

<table>
<thead>
<tr>
<th align="left">Name</th>
<th align="right">Count</th>
<th align="right">Ratio</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">LOAD_ATTR_INSTANCE_VALUE</td>
<td align="right">172,465,169</td>
<td align="right">19.2%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_METHOD_WITH_VALUES</td>
<td align="right">169,556,575</td>
<td align="right">18.9%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_SLOT</td>
<td align="right">75,686,139</td>
<td align="right">8.4%</td>
</tr>
<tr>
<td align="left">FOR_ITER_LIST</td>
<td align="right">64,929,435</td>
<td align="right">7.2%</td>
</tr>
<tr>
<td align="left">FOR_ITER_TUPLE</td>
<td align="right">64,673,845</td>
<td align="right">7.2%</td>
</tr>
<tr>
<td align="left">STORE_ATTR_INSTANCE_VALUE</td>
<td align="right">62,504,078</td>
<td align="right">7.0%</td>
</tr>
<tr>
<td align="left">CALL_PY_EXACT_ARGS</td>
<td align="right">43,499,495</td>
<td align="right">4.8%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES</td>
<td align="right">40,485,320</td>
<td align="right">4.5%</td>
</tr>
<tr>
<td align="left">TO_BOOL_NONE</td>
<td align="right">24,982,356</td>
<td align="right">2.8%</td>
</tr>
<tr>
<td align="left">TO_BOOL_ALWAYS_TRUE</td>
<td align="right">24,275,138</td>
<td align="right">2.7%</td>
</tr>
</tbody>
</table>


</details>


</details>

## Call stats

<details>
<summary> Inlined calls and frame stats </summary>


This shows what fraction of calls to Python functions are inlined (i.e.
not having a call at the C level) and for those that are not, where the
call comes from.  The various categories overlap.

Also includes the count of frame objects created.

<table>
<thead>
<tr>
<th align="left"></th>
<th align="right">Count</th>
<th align="right">Ratio</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">Calls to PyEval_EvalDefault</td>
<td align="right">1,238,422,183</td>
<td align="right">26.4%</td>
</tr>
<tr>
<td align="left">Calls to Python functions inlined</td>
<td align="right">3,456,675,377</td>
<td align="right">73.6%</td>
</tr>
<tr>
<td align="left">Calls via PyEval_EvalFrame (total)</td>
<td align="right">1,238,422,183</td>
<td align="right">26.4%</td>
</tr>
<tr>
<td align="left">Calls via PyEval_EvalFrame (vector)</td>
<td align="right">687,374,619</td>
<td align="right">14.6%</td>
</tr>
<tr>
<td align="left">Calls via PyEval_EvalFrame (generator)</td>
<td align="right">551,047,564</td>
<td align="right">11.7%</td>
</tr>
<tr>
<td align="left">Calls via PyEval_EvalFrame (legacy)</td>
<td align="right">3,964,200</td>
<td align="right">0.1%</td>
</tr>
<tr>
<td align="left">Calls via PyEval_EvalFrame (function vectorcall)</td>
<td align="right">683,409,099</td>
<td align="right">14.6%</td>
</tr>
<tr>
<td align="left">Calls via PyEval_EvalFrame (build class)</td>
<td align="right">1,320</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">Calls via PyEval_EvalFrame (slot)</td>
<td align="right">160,486,898</td>
<td align="right">3.4%</td>
</tr>
<tr>
<td align="left">Calls via PyEval_EvalFrame (function ex)</td>
<td align="right">16,308,929</td>
<td align="right">0.3%</td>
</tr>
<tr>
<td align="left">Calls via PyEval_EvalFrame (api)</td>
<td align="right">145,690,450</td>
<td align="right">3.1%</td>
</tr>
<tr>
<td align="left">Calls via PyEval_EvalFrame (method)</td>
<td align="right">100,734,921</td>
<td align="right">2.1%</td>
</tr>
<tr>
<td align="left">Frame objects created</td>
<td align="right">44,024,678</td>
<td align="right">0.9%</td>
</tr>
<tr>
<td align="left">Frames pushed</td>
<td align="right">3,569,917,450</td>
<td align="right">76.0%</td>
</tr>
</tbody>
</table>


</details>

## Object stats

<details>
<summary> Allocations, frees and dict materializatons </summary>


Below, "allocations" means "allocations that are not from a freelist".
Total allocations = "Allocations from freelist" + "Allocations".

"Inline values" is the number of values arrays inlined into objects.

The cache hit/miss numbers are for the MRO cache, split into dunder and
other names.

<table>
<thead>
<tr>
<th align="left"></th>
<th align="right">Count</th>
<th align="right">Ratio</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">Allocations from freelist</td>
<td align="right">4,001,682,852</td>
<td align="right">41.0%</td>
</tr>
<tr>
<td align="left">Frees to freelist</td>
<td align="right">4,001,830,671</td>
<td align="right"></td>
</tr>
<tr>
<td align="left">Allocations</td>
<td align="right">5,766,628,663</td>
<td align="right">59.0%</td>
</tr>
<tr>
<td align="left">Allocations to 512 bytes</td>
<td align="right">5,713,058,982</td>
<td align="right">58.5%</td>
</tr>
<tr>
<td align="left">Allocations to 4 kbytes</td>
<td align="right">42,386,269</td>
<td align="right">0.4%</td>
</tr>
<tr>
<td align="left">Allocations over 4 kbytes</td>
<td align="right">11,183,412</td>
<td align="right">0.1%</td>
</tr>
<tr>
<td align="left">Frees</td>
<td align="right">5,992,560,260</td>
<td align="right"></td>
</tr>
<tr>
<td align="left">Inline values</td>
<td align="right">72,745,543</td>
<td align="right"></td>
</tr>
<tr>
<td align="left">Interpreter increfs</td>
<td align="right">43,061,720,240</td>
<td align="right">75.1%</td>
</tr>
<tr>
<td align="left">Interpreter decrefs</td>
<td align="right">50,760,101,461</td>
<td align="right">76.2%</td>
</tr>
<tr>
<td align="left">Increfs</td>
<td align="right">14,268,849,973</td>
<td align="right">24.9%</td>
</tr>
<tr>
<td align="left">Decrefs</td>
<td align="right">15,867,944,874</td>
<td align="right">23.8%</td>
</tr>
<tr>
<td align="left">Materialize dict (on request)</td>
<td align="right">4,911,240</td>
<td align="right">6.8%</td>
</tr>
<tr>
<td align="left">Materialize dict (new key)</td>
<td align="right">67,500</td>
<td align="right">0.1%</td>
</tr>
<tr>
<td align="left">Materialize dict (too big)</td>
<td align="right">0</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">Materialize dict (str subclass)</td>
<td align="right">0</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">Method cache hits</td>
<td align="right">1,705,541,333</td>
<td align="right"></td>
</tr>
<tr>
<td align="left">Method cache misses</td>
<td align="right">44,399,020</td>
<td align="right"></td>
</tr>
<tr>
<td align="left">Method cache collisions</td>
<td align="right">47,936,565</td>
<td align="right"></td>
</tr>
<tr>
<td align="left">Method cache dunder hits</td>
<td align="right">2,003,288,477</td>
<td align="right"></td>
</tr>
<tr>
<td align="left">Method cache dunder misses</td>
<td align="right">4,318,630</td>
<td align="right"></td>
</tr>
</tbody>
</table>


</details>

## GC stats

<details>
<summary> GC collections and effectiveness </summary>


Collected/visits gives some measure of efficiency.

<table>
<thead>
<tr>
<th align="right">Generation</th>
<th align="right">Collections</th>
<th align="right">Objects collected</th>
<th align="right">Object visits</th>
</tr>
</thead>
<tbody>
<tr>
<td align="right">0</td>
<td align="right">0</td>
<td align="right">0</td>
<td align="right">0</td>
</tr>
<tr>
<td align="right">1</td>
<td align="right">0</td>
<td align="right">78,194,820</td>
<td align="right">6,539,918,058</td>
</tr>
<tr>
<td align="right">2</td>
<td align="right">0</td>
<td align="right">0</td>
<td align="right">0</td>
</tr>
</tbody>
</table>


</details>

## Optimization (Tier 2) stats

<details>
<summary> statistics about the Tier 2 optimizer </summary>


</details>

## Rare events

<details>
<summary> Counts of rare/unlikely events </summary>

<table>
<thead>
<tr>
<th align="left">Event</th>
<th align="right">Count</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">
set class
<details>
<summary>ⓘ</summary>

Setting an object's class, `obj.__class__ = ...`
</details>
</td>
<td align="right">0</td>
</tr>
<tr>
<td align="left">
set bases
<details>
<summary>ⓘ</summary>

Setting the bases of a class, `cls.__bases__ = ...`
</details>
</td>
<td align="right">0</td>
</tr>
<tr>
<td align="left">
set eval frame func
<details>
<summary>ⓘ</summary>

Setting the PEP 523 frame eval function `_PyInterpreterState_SetFrameEvalFunc()`
</details>
</td>
<td align="right">0</td>
</tr>
<tr>
<td align="left">
builtin dict
<details>
<summary>ⓘ</summary>

Modifying the builtins, `__builtins__.__dict__[var] = ...`
</details>
</td>
<td align="right">0</td>
</tr>
<tr>
<td align="left">
func modification
<details>
<summary>ⓘ</summary>

Modifying a function, e.g. `func.__defaults__ = ...`, etc.
</details>
</td>
<td align="right">0</td>
</tr>
<tr>
<td align="left">
watched dict modification
<details>
<summary>ⓘ</summary>

A watched dict has been modified
</details>
</td>
<td align="right">0</td>
</tr>
<tr>
<td align="left">
watched globals modification
<details>
<summary>ⓘ</summary>

A watched `globals()` dict has been modified
</details>
</td>
<td align="right">0</td>
</tr>
</tbody>
</table>


</details>

## Meta stats

<details>
<summary> Meta statistics </summary>

<table>
<thead>
<tr>
<th align="left"></th>
<th align="right">Count</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">Number of data files</td>
<td align="right">1,520</td>
</tr>
</tbody>
</table>


</details>

---
Stats gathered on: 2024-06-02
