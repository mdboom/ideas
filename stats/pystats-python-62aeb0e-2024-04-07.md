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
<td align="right">22,207,958,325</td>
<td align="right">18.9%</td>
<td align="right">18.9%</td>
<td align="right"></td>
</tr>
<tr>
<td align="left">STORE_FAST</td>
<td align="right">7,157,064,243</td>
<td align="right">6.1%</td>
<td align="right">24.9%</td>
<td align="right"></td>
</tr>
<tr>
<td align="left">LOAD_CONST</td>
<td align="right">6,431,406,401</td>
<td align="right">5.5%</td>
<td align="right">30.4%</td>
<td align="right"></td>
</tr>
<tr>
<td align="left">LOAD_FAST_LOAD_FAST</td>
<td align="right">5,283,187,728</td>
<td align="right">4.5%</td>
<td align="right">34.9%</td>
<td align="right"></td>
</tr>
<tr>
<td align="left">POP_JUMP_IF_FALSE</td>
<td align="right">5,057,989,034</td>
<td align="right">4.3%</td>
<td align="right">39.2%</td>
<td align="right"></td>
</tr>
<tr>
<td align="left">RESUME_CHECK</td>
<td align="right">4,425,052,826</td>
<td align="right">3.8%</td>
<td align="right">42.9%</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_INSTANCE_VALUE</td>
<td align="right">3,672,167,050</td>
<td align="right">3.1%</td>
<td align="right">46.0%</td>
<td align="right">4.7%</td>
</tr>
<tr>
<td align="left">LOAD_GLOBAL_BUILTIN</td>
<td align="right">3,431,053,028</td>
<td align="right">2.9%</td>
<td align="right">48.9%</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">TO_BOOL_BOOL</td>
<td align="right">2,807,832,935</td>
<td align="right">2.4%</td>
<td align="right">51.3%</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">STORE_FAST_STORE_FAST</td>
<td align="right">2,488,721,355</td>
<td align="right">2.1%</td>
<td align="right">53.4%</td>
<td align="right"></td>
</tr>
<tr>
<td align="left">RETURN_VALUE</td>
<td align="right">2,434,951,026</td>
<td align="right">2.1%</td>
<td align="right">55.5%</td>
<td align="right"></td>
</tr>
<tr>
<td align="left">POP_TOP</td>
<td align="right">2,334,418,909</td>
<td align="right">2.0%</td>
<td align="right">57.5%</td>
<td align="right"></td>
</tr>
<tr>
<td align="left">JUMP_BACKWARD</td>
<td align="right">2,226,139,455</td>
<td align="right">1.9%</td>
<td align="right">59.4%</td>
<td align="right"></td>
</tr>
<tr>
<td align="left">CALL_PY_EXACT_ARGS</td>
<td align="right">2,180,546,339</td>
<td align="right">1.9%</td>
<td align="right">61.2%</td>
<td align="right">2.0%</td>
</tr>
<tr>
<td align="left">LOAD_GLOBAL_MODULE</td>
<td align="right">2,090,593,394</td>
<td align="right">1.8%</td>
<td align="right">63.0%</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_METHOD_WITH_VALUES</td>
<td align="right">1,714,248,135</td>
<td align="right">1.5%</td>
<td align="right">64.5%</td>
<td align="right">9.9%</td>
</tr>
<tr>
<td align="left">COMPARE_OP_INT</td>
<td align="right">1,326,725,824</td>
<td align="right">1.1%</td>
<td align="right">65.6%</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">BINARY_OP_ADD_INT</td>
<td align="right">1,271,990,639</td>
<td align="right">1.1%</td>
<td align="right">66.7%</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">INTERPRETER_EXIT</td>
<td align="right">1,238,247,527</td>
<td align="right">1.1%</td>
<td align="right">67.7%</td>
<td align="right"></td>
</tr>
<tr>
<td align="left">POP_JUMP_IF_TRUE</td>
<td align="right">1,200,274,534</td>
<td align="right">1.0%</td>
<td align="right">68.7%</td>
<td align="right"></td>
</tr>
<tr>
<td align="left">BINARY_SUBSCR</td>
<td align="right">1,180,839,516</td>
<td align="right">1.0%</td>
<td align="right">69.7%</td>
<td align="right"></td>
</tr>
<tr>
<td align="left">PUSH_NULL</td>
<td align="right">1,148,664,684</td>
<td align="right">1.0%</td>
<td align="right">70.7%</td>
<td align="right"></td>
</tr>
<tr>
<td align="left">LOAD_ATTR_SLOT</td>
<td align="right">1,088,383,686</td>
<td align="right">0.9%</td>
<td align="right">71.6%</td>
<td align="right">6.9%</td>
</tr>
<tr>
<td align="left">RETURN_CONST</td>
<td align="right">1,084,111,466</td>
<td align="right">0.9%</td>
<td align="right">72.6%</td>
<td align="right"></td>
</tr>
<tr>
<td align="left">FOR_ITER_LIST</td>
<td align="right">1,075,956,788</td>
<td align="right">0.9%</td>
<td align="right">73.5%</td>
<td align="right">6.0%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR</td>
<td align="right">1,036,465,959</td>
<td align="right">0.9%</td>
<td align="right">74.4%</td>
<td align="right"></td>
</tr>
<tr>
<td align="left">LOAD_ATTR_METHOD_NO_DICT</td>
<td align="right">1,002,787,397</td>
<td align="right">0.9%</td>
<td align="right">75.2%</td>
<td align="right">0.9%</td>
</tr>
<tr>
<td align="left">BINARY_OP</td>
<td align="right">967,429,281</td>
<td align="right">0.8%</td>
<td align="right">76.0%</td>
<td align="right"></td>
</tr>
<tr>
<td align="left">YIELD_VALUE</td>
<td align="right">958,144,035</td>
<td align="right">0.8%</td>
<td align="right">76.8%</td>
<td align="right"></td>
</tr>
<tr>
<td align="left">COPY</td>
<td align="right">955,704,919</td>
<td align="right">0.8%</td>
<td align="right">77.6%</td>
<td align="right"></td>
</tr>
<tr>
<td align="left">CALL_BUILTIN_FAST</td>
<td align="right">952,629,182</td>
<td align="right">0.8%</td>
<td align="right">78.5%</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">BINARY_OP_MULTIPLY_FLOAT</td>
<td align="right">922,732,239</td>
<td align="right">0.8%</td>
<td align="right">79.2%</td>
<td align="right">0.8%</td>
</tr>
<tr>
<td align="left">BINARY_SUBSCR_LIST_INT</td>
<td align="right">860,077,391</td>
<td align="right">0.7%</td>
<td align="right">80.0%</td>
<td align="right">0.4%</td>
</tr>
<tr>
<td align="left">SWAP</td>
<td align="right">848,914,115</td>
<td align="right">0.7%</td>
<td align="right">80.7%</td>
<td align="right"></td>
</tr>
<tr>
<td align="left">CALL_BUILTIN_O</td>
<td align="right">847,036,454</td>
<td align="right">0.7%</td>
<td align="right">81.4%</td>
<td align="right">0.2%</td>
</tr>
<tr>
<td align="left">STORE_ATTR_INSTANCE_VALUE</td>
<td align="right">687,625,990</td>
<td align="right">0.6%</td>
<td align="right">82.0%</td>
<td align="right">9.1%</td>
</tr>
<tr>
<td align="left">LOAD_DEREF</td>
<td align="right">679,920,982</td>
<td align="right">0.6%</td>
<td align="right">82.6%</td>
<td align="right"></td>
</tr>
<tr>
<td align="left">IS_OP</td>
<td align="right">584,327,417</td>
<td align="right">0.5%</td>
<td align="right">83.1%</td>
<td align="right"></td>
</tr>
<tr>
<td align="left">BUILD_TUPLE</td>
<td align="right">577,625,648</td>
<td align="right">0.5%</td>
<td align="right">83.6%</td>
<td align="right"></td>
</tr>
<tr>
<td align="left">UNPACK_SEQUENCE_TWO_TUPLE</td>
<td align="right">561,347,878</td>
<td align="right">0.5%</td>
<td align="right">84.0%</td>
<td align="right"></td>
</tr>
<tr>
<td align="left">CALL</td>
<td align="right">554,908,930</td>
<td align="right">0.5%</td>
<td align="right">84.5%</td>
<td align="right"></td>
</tr>
<tr>
<td align="left">STORE_ATTR_SLOT</td>
<td align="right">551,303,708</td>
<td align="right">0.5%</td>
<td align="right">85.0%</td>
<td align="right">2.6%</td>
</tr>
<tr>
<td align="left">UNPACK_SEQUENCE_TUPLE</td>
<td align="right">523,851,138</td>
<td align="right">0.4%</td>
<td align="right">85.4%</td>
<td align="right">0.2%</td>
</tr>
<tr>
<td align="left">FOR_ITER_RANGE</td>
<td align="right">499,826,921</td>
<td align="right">0.4%</td>
<td align="right">85.8%</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">BINARY_OP_SUBTRACT_INT</td>
<td align="right">497,824,874</td>
<td align="right">0.4%</td>
<td align="right">86.3%</td>
<td align="right">0.1%</td>
</tr>
<tr>
<td align="left">SEND_GEN</td>
<td align="right">488,004,416</td>
<td align="right">0.4%</td>
<td align="right">86.7%</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">BINARY_OP_ADD_FLOAT</td>
<td align="right">458,222,232</td>
<td align="right">0.4%</td>
<td align="right">87.1%</td>
<td align="right">1.4%</td>
</tr>
<tr>
<td align="left">CALL_ISINSTANCE</td>
<td align="right">451,401,644</td>
<td align="right">0.4%</td>
<td align="right">87.5%</td>
<td align="right"></td>
</tr>
<tr>
<td align="left">GET_ITER</td>
<td align="right">446,414,398</td>
<td align="right">0.4%</td>
<td align="right">87.8%</td>
<td align="right"></td>
</tr>
<tr>
<td align="left">NOP</td>
<td align="right">442,533,516</td>
<td align="right">0.4%</td>
<td align="right">88.2%</td>
<td align="right"></td>
</tr>
<tr>
<td align="left">JUMP_BACKWARD_NO_INTERRUPT</td>
<td align="right">393,113,631</td>
<td align="right">0.3%</td>
<td align="right">88.5%</td>
<td align="right"></td>
</tr>
<tr>
<td align="left">POP_JUMP_IF_NOT_NONE</td>
<td align="right">363,859,923</td>
<td align="right">0.3%</td>
<td align="right">88.8%</td>
<td align="right"></td>
</tr>
<tr>
<td align="left">INSTRUMENTED_POP_JUMP_IF_FALSE</td>
<td align="right">349,633,860</td>
<td align="right">0.3%</td>
<td align="right">89.1%</td>
<td align="right"></td>
</tr>
<tr>
<td align="left">JUMP_FORWARD</td>
<td align="right">346,992,547</td>
<td align="right">0.3%</td>
<td align="right">89.4%</td>
<td align="right"></td>
</tr>
<tr>
<td align="left">FOR_ITER</td>
<td align="right">344,528,247</td>
<td align="right">0.3%</td>
<td align="right">89.7%</td>
<td align="right"></td>
</tr>
<tr>
<td align="left">TO_BOOL_NONE</td>
<td align="right">343,600,104</td>
<td align="right">0.3%</td>
<td align="right">90.0%</td>
<td align="right">7.3%</td>
</tr>
<tr>
<td align="left">CALL_TYPE_1</td>
<td align="right">340,858,886</td>
<td align="right">0.3%</td>
<td align="right">90.3%</td>
<td align="right"></td>
</tr>
<tr>
<td align="left">LOAD_ATTR_MODULE</td>
<td align="right">327,864,508</td>
<td align="right">0.3%</td>
<td align="right">90.6%</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">STORE_SUBSCR</td>
<td align="right">312,616,161</td>
<td align="right">0.3%</td>
<td align="right">90.9%</td>
<td align="right"></td>
</tr>
<tr>
<td align="left">EXTENDED_ARG</td>
<td align="right">307,244,902</td>
<td align="right">0.3%</td>
<td align="right">91.1%</td>
<td align="right"></td>
</tr>
<tr>
<td align="left">CONTAINS_OP_SET</td>
<td align="right">302,330,119</td>
<td align="right">0.3%</td>
<td align="right">91.4%</td>
<td align="right">0.2%</td>
</tr>
<tr>
<td align="left">BINARY_OP_SUBTRACT_FLOAT</td>
<td align="right">284,469,668</td>
<td align="right">0.2%</td>
<td align="right">91.6%</td>
<td align="right">5.3%</td>
</tr>
<tr>
<td align="left">CALL_LEN</td>
<td align="right">274,587,437</td>
<td align="right">0.2%</td>
<td align="right">91.8%</td>
<td align="right"></td>
</tr>
<tr>
<td align="left">STORE_SUBSCR_LIST_INT</td>
<td align="right">270,388,241</td>
<td align="right">0.2%</td>
<td align="right">92.1%</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">FOR_ITER_TUPLE</td>
<td align="right">268,351,794</td>
<td align="right">0.2%</td>
<td align="right">92.3%</td>
<td align="right">24.1%</td>
</tr>
<tr>
<td align="left">BINARY_OP_MULTIPLY_INT</td>
<td align="right">267,678,070</td>
<td align="right">0.2%</td>
<td align="right">92.5%</td>
<td align="right">3.2%</td>
</tr>
<tr>
<td align="left">CALL_METHOD_DESCRIPTOR_FAST</td>
<td align="right">262,791,162</td>
<td align="right">0.2%</td>
<td align="right">92.8%</td>
<td align="right">10.9%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_WITH_HINT</td>
<td align="right">261,605,596</td>
<td align="right">0.2%</td>
<td align="right">93.0%</td>
<td align="right">0.4%</td>
</tr>
<tr>
<td align="left">CALL_METHOD_DESCRIPTOR_NOARGS</td>
<td align="right">247,300,151</td>
<td align="right">0.2%</td>
<td align="right">93.2%</td>
<td align="right">8.8%</td>
</tr>
<tr>
<td align="left">BINARY_SUBSCR_DICT</td>
<td align="right">237,809,717</td>
<td align="right">0.2%</td>
<td align="right">93.4%</td>
<td align="right"></td>
</tr>
<tr>
<td align="left">CALL_METHOD_DESCRIPTOR_O</td>
<td align="right">233,898,379</td>
<td align="right">0.2%</td>
<td align="right">93.6%</td>
<td align="right">0.1%</td>
</tr>
<tr>
<td align="left">BUILD_LIST</td>
<td align="right">231,133,669</td>
<td align="right">0.2%</td>
<td align="right">93.8%</td>
<td align="right"></td>
</tr>
<tr>
<td align="left">RETURN_GENERATOR</td>
<td align="right">230,563,762</td>
<td align="right">0.2%</td>
<td align="right">94.0%</td>
<td align="right"></td>
</tr>
<tr>
<td align="left">BINARY_SUBSCR_TUPLE_INT</td>
<td align="right">228,521,823</td>
<td align="right">0.2%</td>
<td align="right">94.2%</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">UNPACK_SEQUENCE_LIST</td>
<td align="right">227,311,742</td>
<td align="right">0.2%</td>
<td align="right">94.4%</td>
<td align="right">0.6%</td>
</tr>
<tr>
<td align="left">END_SEND</td>
<td align="right">204,672,560</td>
<td align="right">0.2%</td>
<td align="right">94.5%</td>
<td align="right"></td>
</tr>
<tr>
<td align="left">TO_BOOL_INT</td>
<td align="right">204,479,985</td>
<td align="right">0.2%</td>
<td align="right">94.7%</td>
<td align="right">0.4%</td>
</tr>
<tr>
<td align="left">CONTAINS_OP_DICT</td>
<td align="right">202,156,502</td>
<td align="right">0.2%</td>
<td align="right">94.9%</td>
<td align="right">0.3%</td>
</tr>
<tr>
<td align="left">POP_JUMP_IF_NONE</td>
<td align="right">197,437,603</td>
<td align="right">0.2%</td>
<td align="right">95.1%</td>
<td align="right"></td>
</tr>
<tr>
<td align="left">TO_BOOL</td>
<td align="right">197,352,043</td>
<td align="right">0.2%</td>
<td align="right">95.2%</td>
<td align="right"></td>
</tr>
<tr>
<td align="left">COMPARE_OP_STR</td>
<td align="right">192,950,958</td>
<td align="right">0.2%</td>
<td align="right">95.4%</td>
<td align="right">0.2%</td>
</tr>
<tr>
<td align="left">COPY_FREE_VARS</td>
<td align="right">185,189,591</td>
<td align="right">0.2%</td>
<td align="right">95.5%</td>
<td align="right"></td>
</tr>
<tr>
<td align="left">LOAD_ATTR_METHOD_LAZY_DICT</td>
<td align="right">177,216,290</td>
<td align="right">0.2%</td>
<td align="right">95.7%</td>
<td align="right">2.1%</td>
</tr>
<tr>
<td align="left">STORE_SUBSCR_DICT</td>
<td align="right">174,081,304</td>
<td align="right">0.1%</td>
<td align="right">95.8%</td>
<td align="right"></td>
</tr>
<tr>
<td align="left">CONTAINS_OP</td>
<td align="right">172,162,660</td>
<td align="right">0.1%</td>
<td align="right">96.0%</td>
<td align="right"></td>
</tr>
<tr>
<td align="left">LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES</td>
<td align="right">165,504,389</td>
<td align="right">0.1%</td>
<td align="right">96.1%</td>
<td align="right">24.5%</td>
</tr>
<tr>
<td align="left">CALL_LIST_APPEND</td>
<td align="right">161,554,766</td>
<td align="right">0.1%</td>
<td align="right">96.3%</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">FOR_ITER_GEN</td>
<td align="right">144,600,900</td>
<td align="right">0.1%</td>
<td align="right">96.4%</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">COMPARE_OP</td>
<td align="right">142,585,366</td>
<td align="right">0.1%</td>
<td align="right">96.5%</td>
<td align="right"></td>
</tr>
<tr>
<td align="left">CALL_INTRINSIC_1</td>
<td align="right">140,672,329</td>
<td align="right">0.1%</td>
<td align="right">96.6%</td>
<td align="right"></td>
</tr>
<tr>
<td align="left">CALL_PY_WITH_DEFAULTS</td>
<td align="right">137,197,160</td>
<td align="right">0.1%</td>
<td align="right">96.7%</td>
<td align="right">3.6%</td>
</tr>
<tr>
<td align="left">BINARY_SLICE</td>
<td align="right">133,107,761</td>
<td align="right">0.1%</td>
<td align="right">96.9%</td>
<td align="right"></td>
</tr>
<tr>
<td align="left">CALL_BOUND_METHOD_EXACT_ARGS</td>
<td align="right">129,749,232</td>
<td align="right">0.1%</td>
<td align="right">97.0%</td>
<td align="right">6.6%</td>
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
<td align="right">117,197,860</td>
<td align="right">0.1%</td>
<td align="right">97.2%</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">TO_BOOL_ALWAYS_TRUE</td>
<td align="right">114,238,894</td>
<td align="right">0.1%</td>
<td align="right">97.3%</td>
<td align="right">21.3%</td>
</tr>
<tr>
<td align="left">FORMAT_SIMPLE</td>
<td align="right">112,956,540</td>
<td align="right">0.1%</td>
<td align="right">97.4%</td>
<td align="right"></td>
</tr>
<tr>
<td align="left">SEND</td>
<td align="right">111,602,640</td>
<td align="right">0.1%</td>
<td align="right">97.5%</td>
<td align="right"></td>
</tr>
<tr>
<td align="left">BINARY_SUBSCR_GETITEM</td>
<td align="right">108,152,024</td>
<td align="right">0.1%</td>
<td align="right">97.5%</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_CLASS</td>
<td align="right">107,202,748</td>
<td align="right">0.1%</td>
<td align="right">97.6%</td>
<td align="right">0.7%</td>
</tr>
<tr>
<td align="left">CALL_BUILTIN_CLASS</td>
<td align="right">106,079,911</td>
<td align="right">0.1%</td>
<td align="right">97.7%</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">BUILD_SLICE</td>
<td align="right">105,902,760</td>
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
<td align="left">GET_ANEXT</td>
<td align="right">100,136,760</td>
<td align="right">0.1%</td>
<td align="right">98.0%</td>
<td align="right"></td>
</tr>
<tr>
<td align="left">CALL_KW</td>
<td align="right">96,344,374</td>
<td align="right">0.1%</td>
<td align="right">98.1%</td>
<td align="right"></td>
</tr>
<tr>
<td align="left">CALL_BUILTIN_FAST_WITH_KEYWORDS</td>
<td align="right">96,268,330</td>
<td align="right">0.1%</td>
<td align="right">98.2%</td>
<td align="right"></td>
</tr>
<tr>
<td align="left">LIST_APPEND</td>
<td align="right">93,283,017</td>
<td align="right">0.1%</td>
<td align="right">98.2%</td>
<td align="right"></td>
</tr>
<tr>
<td align="left">CALL_FUNCTION_EX</td>
<td align="right">88,635,735</td>
<td align="right">0.1%</td>
<td align="right">98.3%</td>
<td align="right"></td>
</tr>
<tr>
<td align="left">TO_BOOL_LIST</td>
<td align="right">86,562,823</td>
<td align="right">0.1%</td>
<td align="right">98.4%</td>
<td align="right">1.3%</td>
</tr>
<tr>
<td align="left">GET_AWAITABLE</td>
<td align="right">83,096,840</td>
<td align="right">0.1%</td>
<td align="right">98.5%</td>
<td align="right"></td>
</tr>
<tr>
<td align="left">LOAD_GLOBAL</td>
<td align="right">80,180,809</td>
<td align="right">0.1%</td>
<td align="right">98.5%</td>
<td align="right"></td>
</tr>
<tr>
<td align="left">DELETE_SUBSCR</td>
<td align="right">79,326,911</td>
<td align="right">0.1%</td>
<td align="right">98.6%</td>
<td align="right"></td>
</tr>
<tr>
<td align="left">MAKE_FUNCTION</td>
<td align="right">73,815,500</td>
<td align="right">0.1%</td>
<td align="right">98.7%</td>
<td align="right"></td>
</tr>
<tr>
<td align="left">CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS</td>
<td align="right">73,222,030</td>
<td align="right">0.1%</td>
<td align="right">98.7%</td>
<td align="right">2.4%</td>
</tr>
<tr>
<td align="left">INSTRUMENTED_RESUME</td>
<td align="right">72,843,720</td>
<td align="right">0.1%</td>
<td align="right">98.8%</td>
<td align="right"></td>
</tr>
<tr>
<td align="left">INSTRUMENTED_RETURN_VALUE</td>
<td align="right">72,840,300</td>
<td align="right">0.1%</td>
<td align="right">98.8%</td>
<td align="right"></td>
</tr>
<tr>
<td align="left">BUILD_MAP</td>
<td align="right">68,756,032</td>
<td align="right">0.1%</td>
<td align="right">98.9%</td>
<td align="right"></td>
</tr>
<tr>
<td align="left">SET_FUNCTION_ATTRIBUTE</td>
<td align="right">66,987,028</td>
<td align="right">0.1%</td>
<td align="right">99.0%</td>
<td align="right"></td>
</tr>
<tr>
<td align="left">LOAD_ATTR_NONDESCRIPTOR_NO_DICT</td>
<td align="right">65,171,795</td>
<td align="right">0.1%</td>
<td align="right">99.0%</td>
<td align="right">19.4%</td>
</tr>
<tr>
<td align="left">STORE_FAST_LOAD_FAST</td>
<td align="right">62,345,822</td>
<td align="right">0.1%</td>
<td align="right">99.1%</td>
<td align="right"></td>
</tr>
<tr>
<td align="left">BINARY_OP_ADD_UNICODE</td>
<td align="right">59,161,480</td>
<td align="right">0.1%</td>
<td align="right">99.1%</td>
<td align="right"></td>
</tr>
<tr>
<td align="left">CALL_ALLOC_AND_ENTER_INIT</td>
<td align="right">58,972,962</td>
<td align="right">0.1%</td>
<td align="right">99.2%</td>
<td align="right">2.9%</td>
</tr>
<tr>
<td align="left">TO_BOOL_STR</td>
<td align="right">58,083,062</td>
<td align="right">0.0%</td>
<td align="right">99.2%</td>
<td align="right">4.1%</td>
</tr>
<tr>
<td align="left">EXIT_INIT_CHECK</td>
<td align="right">57,264,062</td>
<td align="right">0.0%</td>
<td align="right">99.3%</td>
<td align="right"></td>
</tr>
<tr>
<td align="left">BUILD_STRING</td>
<td align="right">56,314,560</td>
<td align="right">0.0%</td>
<td align="right">99.3%</td>
<td align="right"></td>
</tr>
<tr>
<td align="left">CALL_STR_1</td>
<td align="right">55,812,051</td>
<td align="right">0.0%</td>
<td align="right">99.4%</td>
<td align="right"></td>
</tr>
<tr>
<td align="left">STORE_DEREF</td>
<td align="right">48,905,846</td>
<td align="right">0.0%</td>
<td align="right">99.4%</td>
<td align="right"></td>
</tr>
<tr>
<td align="left">STORE_ATTR</td>
<td align="right">48,744,967</td>
<td align="right">0.0%</td>
<td align="right">99.4%</td>
<td align="right"></td>
</tr>
<tr>
<td align="left">LOAD_ATTR_PROPERTY</td>
<td align="right">48,131,688</td>
<td align="right">0.0%</td>
<td align="right">99.5%</td>
<td align="right">14.9%</td>
</tr>
<tr>
<td align="left">LIST_EXTEND</td>
<td align="right">47,443,735</td>
<td align="right">0.0%</td>
<td align="right">99.5%</td>
<td align="right"></td>
</tr>
<tr>
<td align="left">INSTRUMENTED_POP_JUMP_IF_NONE</td>
<td align="right">43,702,080</td>
<td align="right">0.0%</td>
<td align="right">99.6%</td>
<td align="right"></td>
</tr>
<tr>
<td align="left">LOAD_SUPER_ATTR_METHOD</td>
<td align="right">43,438,721</td>
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
<td align="right">40,123,112</td>
<td align="right">0.0%</td>
<td align="right">99.7%</td>
<td align="right">0.1%</td>
</tr>
<tr>
<td align="left">END_FOR</td>
<td align="right">37,965,666</td>
<td align="right">0.0%</td>
<td align="right">99.7%</td>
<td align="right"></td>
</tr>
<tr>
<td align="left">LOAD_FAST_AND_CLEAR</td>
<td align="right">35,344,485</td>
<td align="right">0.0%</td>
<td align="right">99.7%</td>
<td align="right"></td>
</tr>
<tr>
<td align="left">UNARY_NEGATIVE</td>
<td align="right">29,540,798</td>
<td align="right">0.0%</td>
<td align="right">99.7%</td>
<td align="right"></td>
</tr>
<tr>
<td align="left">INSTRUMENTED_POP_JUMP_IF_TRUE</td>
<td align="right">29,143,254</td>
<td align="right">0.0%</td>
<td align="right">99.8%</td>
<td align="right"></td>
</tr>
<tr>
<td align="left">GET_YIELD_FROM_ITER</td>
<td align="right">27,464,256</td>
<td align="right">0.0%</td>
<td align="right">99.8%</td>
<td align="right"></td>
</tr>
<tr>
<td align="left">UNARY_NOT</td>
<td align="right">26,537,161</td>
<td align="right">0.0%</td>
<td align="right">99.8%</td>
<td align="right"></td>
</tr>
<tr>
<td align="left">DICT_MERGE</td>
<td align="right">25,192,568</td>
<td align="right">0.0%</td>
<td align="right">99.8%</td>
<td align="right"></td>
</tr>
<tr>
<td align="left">MAKE_CELL</td>
<td align="right">24,078,248</td>
<td align="right">0.0%</td>
<td align="right">99.9%</td>
<td align="right"></td>
</tr>
<tr>
<td align="left">UNPACK_SEQUENCE</td>
<td align="right">14,681,812</td>
<td align="right">0.0%</td>
<td align="right">99.9%</td>
<td align="right"></td>
</tr>
<tr>
<td align="left">MAP_ADD</td>
<td align="right">14,622,232</td>
<td align="right">0.0%</td>
<td align="right">99.9%</td>
<td align="right"></td>
</tr>
<tr>
<td align="left">INSTRUMENTED_JUMP_FORWARD</td>
<td align="right">14,568,360</td>
<td align="right">0.0%</td>
<td align="right">99.9%</td>
<td align="right"></td>
</tr>
<tr>
<td align="left">PUSH_EXC_INFO</td>
<td align="right">11,976,071</td>
<td align="right">0.0%</td>
<td align="right">99.9%</td>
<td align="right"></td>
</tr>
<tr>
<td align="left">POP_EXCEPT</td>
<td align="right">11,976,060</td>
<td align="right">0.0%</td>
<td align="right">99.9%</td>
<td align="right"></td>
</tr>
<tr>
<td align="left">CHECK_EXC_MATCH</td>
<td align="right">11,608,709</td>
<td align="right">0.0%</td>
<td align="right">99.9%</td>
<td align="right"></td>
</tr>
<tr>
<td align="left">CALL_TUPLE_1</td>
<td align="right">10,827,867</td>
<td align="right">0.0%</td>
<td align="right">99.9%</td>
<td align="right"></td>
</tr>
<tr>
<td align="left">UNARY_INVERT</td>
<td align="right">10,292,989</td>
<td align="right">0.0%</td>
<td align="right">99.9%</td>
<td align="right"></td>
</tr>
<tr>
<td align="left">LOAD_NAME</td>
<td align="right">9,003,000</td>
<td align="right">0.0%</td>
<td align="right">100.0%</td>
<td align="right"></td>
</tr>
<tr>
<td align="left">BUILD_CONST_KEY_MAP</td>
<td align="right">7,138,186</td>
<td align="right">0.0%</td>
<td align="right">100.0%</td>
<td align="right"></td>
</tr>
<tr>
<td align="left">BEFORE_WITH</td>
<td align="right">6,433,845</td>
<td align="right">0.0%</td>
<td align="right">100.0%</td>
<td align="right"></td>
</tr>
<tr>
<td align="left">IMPORT_FROM</td>
<td align="right">6,174,923</td>
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
<td align="right">5,694,995</td>
<td align="right">0.0%</td>
<td align="right">100.0%</td>
<td align="right"></td>
</tr>
<tr>
<td align="left">LOAD_FAST_CHECK</td>
<td align="right">3,311,819</td>
<td align="right">0.0%</td>
<td align="right">100.0%</td>
<td align="right"></td>
</tr>
<tr>
<td align="left">LOAD_SUPER_ATTR_ATTR</td>
<td align="right">2,418,971</td>
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
<td align="right">1,484,820</td>
<td align="right">0.0%</td>
<td align="right">100.0%</td>
<td align="right"></td>
</tr>
<tr>
<td align="left">RAISE_VARARGS</td>
<td align="right">1,333,314</td>
<td align="right">0.0%</td>
<td align="right">100.0%</td>
<td align="right"></td>
</tr>
<tr>
<td align="left">DELETE_FAST</td>
<td align="right">1,190,896</td>
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
<td align="left">BUILD_SET</td>
<td align="right">89,073</td>
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
<td align="right">8,580</td>
<td align="right">0.0%</td>
<td align="right">100.0%</td>
<td align="right"></td>
</tr>
<tr>
<td align="left">RESUME</td>
<td align="right">5,794</td>
<td align="right">0.0%</td>
<td align="right">100.0%</td>
<td align="right">1,589.0%</td>
</tr>
<tr>
<td align="left">WITH_EXCEPT_START</td>
<td align="right">4,800</td>
<td align="right">0.0%</td>
<td align="right">100.0%</td>
<td align="right"></td>
</tr>
<tr>
<td align="left">INSTRUMENTED_JUMP_BACKWARD</td>
<td align="right">4,254</td>
<td align="right">0.0%</td>
<td align="right">100.0%</td>
<td align="right"></td>
</tr>
<tr>
<td align="left">INSTRUMENTED_POP_JUMP_IF_NOT_NONE</td>
<td align="right">3,420</td>
<td align="right">0.0%</td>
<td align="right">100.0%</td>
<td align="right"></td>
</tr>
<tr>
<td align="left">INSTRUMENTED_FOR_ITER</td>
<td align="right">2,334</td>
<td align="right">0.0%</td>
<td align="right">100.0%</td>
<td align="right"></td>
</tr>
<tr>
<td align="left">INSTRUMENTED_RETURN_CONST</td>
<td align="right">1,680</td>
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
<td align="left">SET_UPDATE</td>
<td align="right">120</td>
<td align="right">0.0%</td>
<td align="right">100.0%</td>
<td align="right"></td>
</tr>
</tbody>
</table>


</details>

## Pair counts

<details>
<summary> Pair counts for top 100 Tier 1 instructions </summary>


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
<td align="right">3,579,086,144</td>
<td align="right">3.0%</td>
<td align="right">3.0%</td>
</tr>
<tr>
<td align="left">LOAD_FAST LOAD_ATTR_INSTANCE_VALUE</td>
<td align="right">3,215,991,965</td>
<td align="right">2.7%</td>
<td align="right">5.8%</td>
</tr>
<tr>
<td align="left">POP_JUMP_IF_FALSE LOAD_FAST</td>
<td align="right">2,481,415,959</td>
<td align="right">2.1%</td>
<td align="right">7.9%</td>
</tr>
<tr>
<td align="left">LOAD_GLOBAL_BUILTIN LOAD_FAST</td>
<td align="right">2,292,127,250</td>
<td align="right">1.9%</td>
<td align="right">9.8%</td>
</tr>
<tr>
<td align="left">LOAD_FAST LOAD_CONST</td>
<td align="right">2,257,255,878</td>
<td align="right">1.9%</td>
<td align="right">11.7%</td>
</tr>
<tr>
<td align="left">CALL_PY_EXACT_ARGS RESUME_CHECK</td>
<td align="right">1,949,579,119</td>
<td align="right">1.7%</td>
<td align="right">13.4%</td>
</tr>
<tr>
<td align="left">TO_BOOL_BOOL POP_JUMP_IF_FALSE</td>
<td align="right">1,925,527,237</td>
<td align="right">1.6%</td>
<td align="right">15.0%</td>
</tr>
<tr>
<td align="left">RESUME_CHECK LOAD_FAST</td>
<td align="right">1,817,063,591</td>
<td align="right">1.5%</td>
<td align="right">16.6%</td>
</tr>
<tr>
<td align="left">STORE_FAST_STORE_FAST STORE_FAST_STORE_FAST</td>
<td align="right">1,603,189,342</td>
<td align="right">1.4%</td>
<td align="right">17.9%</td>
</tr>
<tr>
<td align="left">LOAD_FAST LOAD_ATTR_METHOD_WITH_VALUES</td>
<td align="right">1,538,779,346</td>
<td align="right">1.3%</td>
<td align="right">19.2%</td>
</tr>
<tr>
<td align="left">COMPARE_OP_INT POP_JUMP_IF_FALSE</td>
<td align="right">1,104,268,706</td>
<td align="right">0.9%</td>
<td align="right">20.2%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_INSTANCE_VALUE LOAD_FAST</td>
<td align="right">1,054,650,054</td>
<td align="right">0.9%</td>
<td align="right">21.1%</td>
</tr>
<tr>
<td align="left">CACHE RESUME_CHECK</td>
<td align="right">1,000,326,215</td>
<td align="right">0.8%</td>
<td align="right">21.9%</td>
</tr>
<tr>
<td align="left">STORE_FAST LOAD_FAST_LOAD_FAST</td>
<td align="right">975,395,933</td>
<td align="right">0.8%</td>
<td align="right">22.7%</td>
</tr>
<tr>
<td align="left">LOAD_FAST LOAD_ATTR_SLOT</td>
<td align="right">940,860,473</td>
<td align="right">0.8%</td>
<td align="right">23.5%</td>
</tr>
<tr>
<td align="left">LOAD_FAST LOAD_GLOBAL_BUILTIN</td>
<td align="right">922,497,064</td>
<td align="right">0.8%</td>
<td align="right">24.3%</td>
</tr>
<tr>
<td align="left">POP_TOP LOAD_FAST</td>
<td align="right">853,565,469</td>
<td align="right">0.7%</td>
<td align="right">25.0%</td>
</tr>
<tr>
<td align="left">JUMP_BACKWARD FOR_ITER_LIST</td>
<td align="right">835,402,299</td>
<td align="right">0.7%</td>
<td align="right">25.8%</td>
</tr>
<tr>
<td align="left">POP_JUMP_IF_FALSE LOAD_GLOBAL_BUILTIN</td>
<td align="right">815,714,792</td>
<td align="right">0.7%</td>
<td align="right">26.5%</td>
</tr>
<tr>
<td align="left">LOAD_CONST BINARY_OP_ADD_INT</td>
<td align="right">810,110,008</td>
<td align="right">0.7%</td>
<td align="right">27.1%</td>
</tr>
<tr>
<td align="left">LOAD_CONST LOAD_FAST</td>
<td align="right">784,265,008</td>
<td align="right">0.7%</td>
<td align="right">27.8%</td>
</tr>
<tr>
<td align="left">POP_TOP JUMP_BACKWARD</td>
<td align="right">752,848,183</td>
<td align="right">0.6%</td>
<td align="right">28.4%</td>
</tr>
<tr>
<td align="left">LOAD_FAST CALL_PY_EXACT_ARGS</td>
<td align="right">737,474,861</td>
<td align="right">0.6%</td>
<td align="right">29.1%</td>
</tr>
<tr>
<td align="left">RESUME_CHECK LOAD_GLOBAL_BUILTIN</td>
<td align="right">726,877,060</td>
<td align="right">0.6%</td>
<td align="right">29.7%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_METHOD_WITH_VALUES LOAD_FAST</td>
<td align="right">721,055,155</td>
<td align="right">0.6%</td>
<td align="right">30.3%</td>
</tr>
<tr>
<td align="left">LOAD_CONST LOAD_CONST</td>
<td align="right">715,009,001</td>
<td align="right">0.6%</td>
<td align="right">30.9%</td>
</tr>
<tr>
<td align="left">LOAD_FAST LOAD_GLOBAL_MODULE</td>
<td align="right">714,002,100</td>
<td align="right">0.6%</td>
<td align="right">31.5%</td>
</tr>
<tr>
<td align="left">STORE_FAST STORE_FAST</td>
<td align="right">711,822,792</td>
<td align="right">0.6%</td>
<td align="right">32.1%</td>
</tr>
<tr>
<td align="left">LOAD_FAST PUSH_NULL</td>
<td align="right">687,445,621</td>
<td align="right">0.6%</td>
<td align="right">32.7%</td>
</tr>
<tr>
<td align="left">LOAD_FAST TO_BOOL_BOOL</td>
<td align="right">657,917,293</td>
<td align="right">0.6%</td>
<td align="right">33.3%</td>
</tr>
<tr>
<td align="left">TO_BOOL_BOOL POP_JUMP_IF_TRUE</td>
<td align="right">636,728,319</td>
<td align="right">0.5%</td>
<td align="right">33.8%</td>
</tr>
<tr>
<td align="left">STORE_FAST_STORE_FAST LOAD_FAST</td>
<td align="right">612,955,104</td>
<td align="right">0.5%</td>
<td align="right">34.3%</td>
</tr>
<tr>
<td align="left">LOAD_FAST CALL_BUILTIN_O</td>
<td align="right">580,435,736</td>
<td align="right">0.5%</td>
<td align="right">34.8%</td>
</tr>
<tr>
<td align="left">LOAD_FAST RETURN_VALUE</td>
<td align="right">571,145,819</td>
<td align="right">0.5%</td>
<td align="right">35.3%</td>
</tr>
<tr>
<td align="left">RESUME_CHECK POP_TOP</td>
<td align="right">564,052,295</td>
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
<td align="right">554,765,397</td>
<td align="right">0.5%</td>
<td align="right">36.7%</td>
</tr>
<tr>
<td align="left">FOR_ITER_LIST STORE_FAST</td>
<td align="right">550,308,059</td>
<td align="right">0.5%</td>
<td align="right">37.2%</td>
</tr>
<tr>
<td align="left">LOAD_CONST COMPARE_OP_INT</td>
<td align="right">549,709,507</td>
<td align="right">0.5%</td>
<td align="right">37.7%</td>
</tr>
<tr>
<td align="left">PUSH_NULL LOAD_FAST</td>
<td align="right">537,538,194</td>
<td align="right">0.5%</td>
<td align="right">38.1%</td>
</tr>
<tr>
<td align="left">LOAD_FAST_LOAD_FAST LOAD_FAST</td>
<td align="right">528,706,052</td>
<td align="right">0.4%</td>
<td align="right">38.6%</td>
</tr>
<tr>
<td align="left">LOAD_FAST LOAD_ATTR_METHOD_NO_DICT</td>
<td align="right">523,077,497</td>
<td align="right">0.4%</td>
<td align="right">39.0%</td>
</tr>
<tr>
<td align="left">LOAD_FAST LOAD_ATTR</td>
<td align="right">520,548,644</td>
<td align="right">0.4%</td>
<td align="right">39.4%</td>
</tr>
<tr>
<td align="left">LOAD_FAST_LOAD_FAST CALL_PY_EXACT_ARGS</td>
<td align="right">510,378,216</td>
<td align="right">0.4%</td>
<td align="right">39.9%</td>
</tr>
<tr>
<td align="left">LOAD_FAST_LOAD_FAST LOAD_FAST_LOAD_FAST</td>
<td align="right">500,581,944</td>
<td align="right">0.4%</td>
<td align="right">40.3%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_METHOD_NO_DICT LOAD_FAST</td>
<td align="right">497,912,669</td>
<td align="right">0.4%</td>
<td align="right">40.7%</td>
</tr>
<tr>
<td align="left">BINARY_SUBSCR LOAD_FAST</td>
<td align="right">492,963,134</td>
<td align="right">0.4%</td>
<td align="right">41.1%</td>
</tr>
<tr>
<td align="left">IS_OP POP_JUMP_IF_FALSE</td>
<td align="right">492,779,034</td>
<td align="right">0.4%</td>
<td align="right">41.6%</td>
</tr>
<tr>
<td align="left">CALL_BUILTIN_FAST TO_BOOL_BOOL</td>
<td align="right">486,851,848</td>
<td align="right">0.4%</td>
<td align="right">42.0%</td>
</tr>
<tr>
<td align="left">STORE_FAST LOAD_GLOBAL_BUILTIN</td>
<td align="right">474,179,763</td>
<td align="right">0.4%</td>
<td align="right">42.4%</td>
</tr>
<tr>
<td align="left">RETURN_CONST POP_TOP</td>
<td align="right">470,916,241</td>
<td align="right">0.4%</td>
<td align="right">42.8%</td>
</tr>
<tr>
<td align="left">YIELD_VALUE INTERPRETER_EXIT</td>
<td align="right">468,254,785</td>
<td align="right">0.4%</td>
<td align="right">43.2%</td>
</tr>
<tr>
<td align="left">JUMP_BACKWARD FOR_ITER_RANGE</td>
<td align="right">464,794,357</td>
<td align="right">0.4%</td>
<td align="right">43.6%</td>
</tr>
<tr>
<td align="left">POP_JUMP_IF_TRUE LOAD_FAST</td>
<td align="right">452,854,239</td>
<td align="right">0.4%</td>
<td align="right">44.0%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_METHOD_WITH_VALUES LOAD_FAST_LOAD_FAST</td>
<td align="right">446,210,924</td>
<td align="right">0.4%</td>
<td align="right">44.3%</td>
</tr>
<tr>
<td align="left">CALL_ISINSTANCE TO_BOOL_BOOL</td>
<td align="right">440,093,463</td>
<td align="right">0.4%</td>
<td align="right">44.7%</td>
</tr>
<tr>
<td align="left">POP_JUMP_IF_TRUE JUMP_BACKWARD</td>
<td align="right">437,014,708</td>
<td align="right">0.4%</td>
<td align="right">45.1%</td>
</tr>
<tr>
<td align="left">FOR_ITER_RANGE STORE_FAST</td>
<td align="right">435,647,120</td>
<td align="right">0.4%</td>
<td align="right">45.4%</td>
</tr>
<tr>
<td align="left">LOAD_GLOBAL_BUILTIN CALL_BUILTIN_FAST</td>
<td align="right">434,497,240</td>
<td align="right">0.4%</td>
<td align="right">45.8%</td>
</tr>
<tr>
<td align="left">LOAD_DEREF LOAD_FAST</td>
<td align="right">432,868,312</td>
<td align="right">0.4%</td>
<td align="right">46.2%</td>
</tr>
<tr>
<td align="left">LOAD_FAST LOAD_FAST</td>
<td align="right">431,714,494</td>
<td align="right">0.4%</td>
<td align="right">46.6%</td>
</tr>
<tr>
<td align="left">RETURN_VALUE RETURN_VALUE</td>
<td align="right">417,394,985</td>
<td align="right">0.4%</td>
<td align="right">46.9%</td>
</tr>
<tr>
<td align="left">RETURN_VALUE STORE_FAST</td>
<td align="right">416,422,854</td>
<td align="right">0.4%</td>
<td align="right">47.3%</td>
</tr>
<tr>
<td align="left">LOAD_CONST STORE_FAST</td>
<td align="right">411,919,405</td>
<td align="right">0.3%</td>
<td align="right">47.6%</td>
</tr>
<tr>
<td align="left">CALL_BUILTIN_O POP_TOP</td>
<td align="right">394,656,180</td>
<td align="right">0.3%</td>
<td align="right">47.9%</td>
</tr>
<tr>
<td align="left">RESUME_CHECK JUMP_BACKWARD_NO_INTERRUPT</td>
<td align="right">388,880,420</td>
<td align="right">0.3%</td>
<td align="right">48.3%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_METHOD_WITH_VALUES CALL_PY_EXACT_ARGS</td>
<td align="right">388,523,590</td>
<td align="right">0.3%</td>
<td align="right">48.6%</td>
</tr>
<tr>
<td align="left">LOAD_FAST_LOAD_FAST LOAD_CONST</td>
<td align="right">387,847,359</td>
<td align="right">0.3%</td>
<td align="right">48.9%</td>
</tr>
<tr>
<td align="left">YIELD_VALUE YIELD_VALUE</td>
<td align="right">383,256,356</td>
<td align="right">0.3%</td>
<td align="right">49.3%</td>
</tr>
<tr>
<td align="left">JUMP_BACKWARD_NO_INTERRUPT SEND_GEN</td>
<td align="right">383,241,760</td>
<td align="right">0.3%</td>
<td align="right">49.6%</td>
</tr>
<tr>
<td align="left">SEND_GEN RESUME_CHECK</td>
<td align="right">383,235,380</td>
<td align="right">0.3%</td>
<td align="right">49.9%</td>
</tr>
<tr>
<td align="left">POP_JUMP_IF_FALSE LOAD_FAST_LOAD_FAST</td>
<td align="right">366,432,675</td>
<td align="right">0.3%</td>
<td align="right">50.2%</td>
</tr>
<tr>
<td align="left">LOAD_CONST BINARY_OP_SUBTRACT_INT</td>
<td align="right">366,252,877</td>
<td align="right">0.3%</td>
<td align="right">50.5%</td>
</tr>
<tr>
<td align="left">LOAD_GLOBAL_MODULE LOAD_FAST</td>
<td align="right">361,580,718</td>
<td align="right">0.3%</td>
<td align="right">50.8%</td>
</tr>
<tr>
<td align="left">LOAD_FAST_LOAD_FAST BINARY_SUBSCR</td>
<td align="right">354,205,695</td>
<td align="right">0.3%</td>
<td align="right">51.1%</td>
</tr>
<tr>
<td align="left">RETURN_CONST INTERPRETER_EXIT</td>
<td align="right">352,450,953</td>
<td align="right">0.3%</td>
<td align="right">51.4%</td>
</tr>
<tr>
<td align="left">BINARY_OP_MULTIPLY_FLOAT BINARY_OP_ADD_FLOAT</td>
<td align="right">349,743,300</td>
<td align="right">0.3%</td>
<td align="right">51.7%</td>
</tr>
<tr>
<td align="left">LOAD_FAST BINARY_SUBSCR</td>
<td align="right">348,647,903</td>
<td align="right">0.3%</td>
<td align="right">52.0%</td>
</tr>
<tr>
<td align="left">LOAD_FAST CALL_TYPE_1</td>
<td align="right">337,182,052</td>
<td align="right">0.3%</td>
<td align="right">52.3%</td>
</tr>
<tr>
<td align="left">LOAD_CONST CALL_BUILTIN_FAST</td>
<td align="right">333,648,811</td>
<td align="right">0.3%</td>
<td align="right">52.6%</td>
</tr>
<tr>
<td align="left">BUILD_TUPLE RETURN_VALUE</td>
<td align="right">333,466,652</td>
<td align="right">0.3%</td>
<td align="right">52.9%</td>
</tr>
<tr>
<td align="left">NOP LOAD_FAST</td>
<td align="right">332,780,632</td>
<td align="right">0.3%</td>
<td align="right">53.2%</td>
</tr>
<tr>
<td align="left">UNPACK_SEQUENCE_TWO_TUPLE STORE_FAST_STORE_FAST</td>
<td align="right">329,435,977</td>
<td align="right">0.3%</td>
<td align="right">53.4%</td>
</tr>
<tr>
<td align="left">RETURN_VALUE INTERPRETER_EXIT</td>
<td align="right">328,892,029</td>
<td align="right">0.3%</td>
<td align="right">53.7%</td>
</tr>
<tr>
<td align="left">CALL_BUILTIN_FAST STORE_FAST</td>
<td align="right">328,062,982</td>
<td align="right">0.3%</td>
<td align="right">54.0%</td>
</tr>
<tr>
<td align="left">INSTRUMENTED_POP_JUMP_IF_FALSE LOAD_FAST</td>
<td align="right">327,768,960</td>
<td align="right">0.3%</td>
<td align="right">54.3%</td>
</tr>
<tr>
<td align="left">STORE_FAST LOAD_DEREF</td>
<td align="right">318,840,141</td>
<td align="right">0.3%</td>
<td align="right">54.6%</td>
</tr>
<tr>
<td align="left">STORE_ATTR_INSTANCE_VALUE LOAD_FAST</td>
<td align="right">317,845,858</td>
<td align="right">0.3%</td>
<td align="right">54.8%</td>
</tr>
<tr>
<td align="left">LOAD_FAST_LOAD_FAST STORE_ATTR_INSTANCE_VALUE</td>
<td align="right">316,692,490</td>
<td align="right">0.3%</td>
<td align="right">55.1%</td>
</tr>
<tr>
<td align="left">LOAD_GLOBAL_MODULE LOAD_ATTR_MODULE</td>
<td align="right">312,158,008</td>
<td align="right">0.3%</td>
<td align="right">55.4%</td>
</tr>
<tr>
<td align="left">POP_JUMP_IF_FALSE RETURN_CONST</td>
<td align="right">308,922,927</td>
<td align="right">0.3%</td>
<td align="right">55.6%</td>
</tr>
<tr>
<td align="left">LOAD_FAST POP_JUMP_IF_NOT_NONE</td>
<td align="right">306,545,138</td>
<td align="right">0.3%</td>
<td align="right">55.9%</td>
</tr>
<tr>
<td align="left">LOAD_CONST BINARY_OP</td>
<td align="right">303,031,132</td>
<td align="right">0.3%</td>
<td align="right">56.1%</td>
</tr>
<tr>
<td align="left">TO_BOOL_NONE POP_JUMP_IF_FALSE</td>
<td align="right">299,282,883</td>
<td align="right">0.3%</td>
<td align="right">56.4%</td>
</tr>
<tr>
<td align="left">LOAD_FAST_LOAD_FAST LOAD_ATTR_INSTANCE_VALUE</td>
<td align="right">298,581,909</td>
<td align="right">0.3%</td>
<td align="right">56.6%</td>
</tr>
<tr>
<td align="left">CONTAINS_OP_SET POP_JUMP_IF_FALSE</td>
<td align="right">294,730,859</td>
<td align="right">0.3%</td>
<td align="right">56.9%</td>
</tr>
<tr>
<td align="left">CALL_TYPE_1 STORE_FAST</td>
<td align="right">293,762,385</td>
<td align="right">0.2%</td>
<td align="right">57.1%</td>
</tr>
<tr>
<td align="left">BINARY_OP_ADD_INT STORE_FAST</td>
<td align="right">288,132,026</td>
<td align="right">0.2%</td>
<td align="right">57.4%</td>
</tr>
<tr>
<td align="left">FOR_ITER_LIST UNPACK_SEQUENCE_TWO_TUPLE</td>
<td align="right">287,889,323</td>
<td align="right">0.2%</td>
<td align="right">57.6%</td>
</tr>
<tr>
<td align="left">LOAD_FAST_LOAD_FAST STORE_ATTR_SLOT</td>
<td align="right">287,871,095</td>
<td align="right">0.2%</td>
<td align="right">57.9%</td>
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
<td align="right">65,990,001</td>
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
<td align="right">10,971,700</td>
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
<td align="left">LOAD_FAST_LOAD_FAST</td>
<td align="right">354,205,695</td>
<td align="right">30.0%</td>
</tr>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">348,647,903</td>
<td align="right">29.5%</td>
</tr>
<tr>
<td align="left">COPY</td>
<td align="right">109,352,700</td>
<td align="right">9.3%</td>
</tr>
<tr>
<td align="left">BUILD_SLICE</td>
<td align="right">105,404,100</td>
<td align="right">8.9%</td>
</tr>
<tr>
<td align="left">BINARY_OP_ADD_INT</td>
<td align="right">103,604,000</td>
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
<td align="left">LOAD_FAST</td>
<td align="right">492,963,134</td>
<td align="right">41.7%</td>
</tr>
<tr>
<td align="left">LOAD_FAST_LOAD_FAST</td>
<td align="right">171,084,840</td>
<td align="right">14.5%</td>
</tr>
<tr>
<td align="left">BINARY_OP_MULTIPLY_FLOAT</td>
<td align="right">115,701,000</td>
<td align="right">9.8%</td>
</tr>
<tr>
<td align="left">BINARY_SUBSCR</td>
<td align="right">96,295,743</td>
<td align="right">8.2%</td>
</tr>
<tr>
<td align="left">STORE_FAST</td>
<td align="right">88,257,320</td>
<td align="right">7.5%</td>
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
<td align="right">10,620,811</td>
<td align="right">91.5%</td>
</tr>
<tr>
<td align="left">LOAD_GLOBAL_MODULE</td>
<td align="right">495,954</td>
<td align="right">4.3%</td>
</tr>
<tr>
<td align="left">BUILD_TUPLE</td>
<td align="right">447,048</td>
<td align="right">3.9%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_MODULE</td>
<td align="right">43,696</td>
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
<td align="right">11,608,589</td>
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
<td align="right">158,717,107</td>
<td align="right">35.6%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_INSTANCE_VALUE</td>
<td align="right">68,356,740</td>
<td align="right">15.3%</td>
</tr>
<tr>
<td align="left">RETURN_VALUE</td>
<td align="right">55,159,542</td>
<td align="right">12.4%</td>
</tr>
<tr>
<td align="left">CALL_METHOD_DESCRIPTOR_NOARGS</td>
<td align="right">43,266,726</td>
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
<td align="right">164,217,770</td>
<td align="right">36.8%</td>
</tr>
<tr>
<td align="left">FOR_ITER_TUPLE</td>
<td align="right">69,523,885</td>
<td align="right">15.6%</td>
</tr>
<tr>
<td align="left">CALL_PY_EXACT_ARGS</td>
<td align="right">66,894,628</td>
<td align="right">15.0%</td>
</tr>
<tr>
<td align="left">FOR_ITER</td>
<td align="right">54,722,538</td>
<td align="right">12.3%</td>
</tr>
<tr>
<td align="left">FOR_ITER_GEN</td>
<td align="right">37,635,148</td>
<td align="right">8.4%</td>
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
<td align="right">173,435,453</td>
<td align="right">39.2%</td>
</tr>
<tr>
<td align="left">POP_JUMP_IF_FALSE</td>
<td align="right">93,182,725</td>
<td align="right">21.1%</td>
</tr>
<tr>
<td align="left">STORE_FAST</td>
<td align="right">57,539,470</td>
<td align="right">13.0%</td>
</tr>
<tr>
<td align="left">STORE_ATTR_INSTANCE_VALUE</td>
<td align="right">25,256,610</td>
<td align="right">5.7%</td>
</tr>
<tr>
<td align="left">POP_JUMP_IF_TRUE</td>
<td align="right">23,866,566</td>
<td align="right">5.4%</td>
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
<td align="right">332,780,632</td>
<td align="right">75.2%</td>
</tr>
<tr>
<td align="left">LOAD_GLOBAL_BUILTIN</td>
<td align="right">29,543,312</td>
<td align="right">6.7%</td>
</tr>
<tr>
<td align="left">LOAD_CONST</td>
<td align="right">15,615,740</td>
<td align="right">3.5%</td>
</tr>
<tr>
<td align="left">LOAD_GLOBAL_MODULE</td>
<td align="right">15,605,146</td>
<td align="right">3.5%</td>
</tr>
<tr>
<td align="left">NOP</td>
<td align="right">15,130,600</td>
<td align="right">3.4%</td>
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
<td align="right">5,820,714</td>
<td align="right">48.6%</td>
</tr>
<tr>
<td align="left">STORE_SUBSCR_DICT</td>
<td align="right">3,075,240</td>
<td align="right">25.7%</td>
</tr>
<tr>
<td align="left">SWAP</td>
<td align="right">1,375,172</td>
<td align="right">11.5%</td>
</tr>
<tr>
<td align="left">COPY</td>
<td align="right">960,720</td>
<td align="right">8.0%</td>
</tr>
<tr>
<td align="left">STORE_FAST</td>
<td align="right">557,074</td>
<td align="right">4.7%</td>
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
<td align="right">7,082,258</td>
<td align="right">59.1%</td>
</tr>
<tr>
<td align="left">JUMP_FORWARD</td>
<td align="right">1,529,940</td>
<td align="right">12.8%</td>
</tr>
<tr>
<td align="left">RETURN_VALUE</td>
<td align="right">1,317,572</td>
<td align="right">11.0%</td>
</tr>
<tr>
<td align="left">RERAISE</td>
<td align="right">960,720</td>
<td align="right">8.0%</td>
</tr>
<tr>
<td align="left">EXTENDED_ARG</td>
<td align="right">707,010</td>
<td align="right">5.9%</td>
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
<td align="right">564,052,295</td>
<td align="right">24.2%</td>
</tr>
<tr>
<td align="left">RETURN_CONST</td>
<td align="right">470,916,241</td>
<td align="right">20.2%</td>
</tr>
<tr>
<td align="left">CALL_BUILTIN_O</td>
<td align="right">394,656,180</td>
<td align="right">16.9%</td>
</tr>
<tr>
<td align="left">POP_JUMP_IF_FALSE</td>
<td align="right">132,767,692</td>
<td align="right">5.7%</td>
</tr>
<tr>
<td align="left">CALL_METHOD_DESCRIPTOR_O</td>
<td align="right">127,894,639</td>
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
<td align="right">853,565,469</td>
<td align="right">36.6%</td>
</tr>
<tr>
<td align="left">JUMP_BACKWARD</td>
<td align="right">752,848,183</td>
<td align="right">32.2%</td>
</tr>
<tr>
<td align="left">RESUME_CHECK</td>
<td align="right">230,562,442</td>
<td align="right">9.9%</td>
</tr>
<tr>
<td align="left">RETURN_CONST</td>
<td align="right">155,282,448</td>
<td align="right">6.7%</td>
</tr>
<tr>
<td align="left">LOAD_FAST_LOAD_FAST</td>
<td align="right">81,403,759</td>
<td align="right">3.5%</td>
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
<td align="right">5,015,631</td>
<td align="right">41.9%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR</td>
<td align="right">3,271,260</td>
<td align="right">27.3%</td>
</tr>
<tr>
<td align="left">RERAISE</td>
<td align="right">954,720</td>
<td align="right">8.0%</td>
</tr>
<tr>
<td align="left">RAISE_VARARGS</td>
<td align="right">894,474</td>
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
<td align="right">10,712,521</td>
<td align="right">89.4%</td>
</tr>
<tr>
<td align="left">LOAD_GLOBAL_MODULE</td>
<td align="right">870,230</td>
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
<td align="right">380</td>
<td align="right">0.0%</td>
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
<td align="right">687,445,621</td>
<td align="right">59.8%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_MODULE</td>
<td align="right">261,491,832</td>
<td align="right">22.8%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR</td>
<td align="right">66,176,709</td>
<td align="right">5.8%</td>
</tr>
<tr>
<td align="left">LOAD_DEREF</td>
<td align="right">49,698,131</td>
<td align="right">4.3%</td>
</tr>
<tr>
<td align="left">LOAD_FAST_LOAD_FAST</td>
<td align="right">46,717,864</td>
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
<td align="right">537,538,194</td>
<td align="right">46.8%</td>
</tr>
<tr>
<td align="left">LOAD_FAST_LOAD_FAST</td>
<td align="right">287,216,486</td>
<td align="right">25.0%</td>
</tr>
<tr>
<td align="left">LOAD_CONST</td>
<td align="right">197,468,913</td>
<td align="right">17.2%</td>
</tr>
<tr>
<td align="left">CALL</td>
<td align="right">51,740,701</td>
<td align="right">4.5%</td>
</tr>
<tr>
<td align="left">LOAD_GLOBAL_MODULE</td>
<td align="right">34,347,841</td>
<td align="right">3.0%</td>
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
<td align="right">571,145,819</td>
<td align="right">23.5%</td>
</tr>
<tr>
<td align="left">RETURN_VALUE</td>
<td align="right">417,394,985</td>
<td align="right">17.1%</td>
</tr>
<tr>
<td align="left">BUILD_TUPLE</td>
<td align="right">333,466,652</td>
<td align="right">13.7%</td>
</tr>
<tr>
<td align="left">BINARY_SUBSCR_DICT</td>
<td align="right">140,276,383</td>
<td align="right">5.8%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_INSTANCE_VALUE</td>
<td align="right">129,007,495</td>
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
<td align="left">RETURN_VALUE</td>
<td align="right">417,394,985</td>
<td align="right">17.1%</td>
</tr>
<tr>
<td align="left">STORE_FAST</td>
<td align="right">416,422,854</td>
<td align="right">17.1%</td>
</tr>
<tr>
<td align="left">INTERPRETER_EXIT</td>
<td align="right">328,892,029</td>
<td align="right">13.5%</td>
</tr>
<tr>
<td align="left">UNPACK_SEQUENCE_TUPLE</td>
<td align="right">240,521,742</td>
<td align="right">9.9%</td>
</tr>
<tr>
<td align="left">TO_BOOL_BOOL</td>
<td align="right">234,688,070</td>
<td align="right">9.6%</td>
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
<td align="right">35.0%</td>
</tr>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">79,801,241</td>
<td align="right">25.5%</td>
</tr>
<tr>
<td align="left">LOAD_FAST_LOAD_FAST</td>
<td align="right">54,965,660</td>
<td align="right">17.6%</td>
</tr>
<tr>
<td align="left">BINARY_OP_ADD_INT</td>
<td align="right">41,532,300</td>
<td align="right">13.3%</td>
</tr>
<tr>
<td align="left">LOAD_CONST</td>
<td align="right">11,512,500</td>
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
<td align="left">JUMP_BACKWARD</td>
<td align="right">110,771,820</td>
<td align="right">35.4%</td>
</tr>
<tr>
<td align="left">LOAD_FAST_LOAD_FAST</td>
<td align="right">104,593,740</td>
<td align="right">33.5%</td>
</tr>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">35,892,220</td>
<td align="right">11.5%</td>
</tr>
<tr>
<td align="left">LOAD_GLOBAL_BUILTIN</td>
<td align="right">27,003,100</td>
<td align="right">8.6%</td>
</tr>
<tr>
<td align="left">LOAD_DEREF</td>
<td align="right">15,741,060</td>
<td align="right">5.0%</td>
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
<td align="right">141,646,134</td>
<td align="right">71.8%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_INSTANCE_VALUE</td>
<td align="right">44,266,086</td>
<td align="right">22.4%</td>
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
<td align="right">1,132,700</td>
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
<td align="left">POP_JUMP_IF_TRUE</td>
<td align="right">99,601,492</td>
<td align="right">50.5%</td>
</tr>
<tr>
<td align="left">POP_JUMP_IF_FALSE</td>
<td align="right">82,811,840</td>
<td align="right">42.0%</td>
</tr>
<tr>
<td align="left">INSTRUMENTED_POP_JUMP_IF_TRUE</td>
<td align="right">14,567,100</td>
<td align="right">7.4%</td>
</tr>
<tr>
<td align="left">TO_BOOL</td>
<td align="right">208,160</td>
<td align="right">0.1%</td>
</tr>
<tr>
<td align="left">UNARY_NOT</td>
<td align="right">61,606</td>
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
<td align="right">303,031,132</td>
<td align="right">31.3%</td>
</tr>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">174,998,737</td>
<td align="right">18.1%</td>
</tr>
<tr>
<td align="left">CALL_METHOD_DESCRIPTOR_O</td>
<td align="right">72,001,440</td>
<td align="right">7.4%</td>
</tr>
<tr>
<td align="left">LOAD_FAST_LOAD_FAST</td>
<td align="right">66,386,022</td>
<td align="right">6.9%</td>
</tr>
<tr>
<td align="left">BINARY_SUBSCR_LIST_INT</td>
<td align="right">65,379,209</td>
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
<td align="right">173,268,799</td>
<td align="right">17.9%</td>
</tr>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">166,501,802</td>
<td align="right">17.2%</td>
</tr>
<tr>
<td align="left">LOAD_FAST_LOAD_FAST</td>
<td align="right">120,315,500</td>
<td align="right">12.4%</td>
</tr>
<tr>
<td align="left">BINARY_SUBSCR_LIST_INT</td>
<td align="right">96,694,080</td>
<td align="right">10.0%</td>
</tr>
<tr>
<td align="left">LOAD_CONST</td>
<td align="right">91,344,885</td>
<td align="right">9.4%</td>
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
<td align="right">104,033,283</td>
<td align="right">45.0%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_SLOT</td>
<td align="right">36,764,611</td>
<td align="right">15.9%</td>
</tr>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">23,421,487</td>
<td align="right">10.1%</td>
</tr>
<tr>
<td align="left">SWAP</td>
<td align="right">11,816,773</td>
<td align="right">5.1%</td>
</tr>
<tr>
<td align="left">LOAD_CONST</td>
<td align="right">11,189,640</td>
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
<td align="left">STORE_FAST</td>
<td align="right">110,367,489</td>
<td align="right">47.8%</td>
</tr>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">74,522,184</td>
<td align="right">32.2%</td>
</tr>
<tr>
<td align="left">SWAP</td>
<td align="right">11,816,833</td>
<td align="right">5.1%</td>
</tr>
<tr>
<td align="left">RETURN_VALUE</td>
<td align="right">8,195,127</td>
<td align="right">3.5%</td>
</tr>
<tr>
<td align="left">CALL_METHOD_DESCRIPTOR_FAST</td>
<td align="right">8,086,342</td>
<td align="right">3.5%</td>
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
<td align="right">177,561,317</td>
<td align="right">30.7%</td>
</tr>
<tr>
<td align="left">LOAD_CONST</td>
<td align="right">165,296,178</td>
<td align="right">28.6%</td>
</tr>
<tr>
<td align="left">LOAD_FAST_LOAD_FAST</td>
<td align="right">125,519,770</td>
<td align="right">21.7%</td>
</tr>
<tr>
<td align="left">CALL</td>
<td align="right">36,557,824</td>
<td align="right">6.3%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR</td>
<td align="right">16,453,974</td>
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
<td align="left">RETURN_VALUE</td>
<td align="right">333,466,652</td>
<td align="right">57.7%</td>
</tr>
<tr>
<td align="left">LOAD_CONST</td>
<td align="right">67,169,473</td>
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
<td align="right">23,077,079</td>
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
<td align="left">LOAD_FAST</td>
<td align="right">215,921,906</td>
<td align="right">38.9%</td>
</tr>
<tr>
<td align="left">BINARY_SUBSCR_TUPLE_INT</td>
<td align="right">72,000,020</td>
<td align="right">13.0%</td>
</tr>
<tr>
<td align="left">LOAD_FAST_LOAD_FAST</td>
<td align="right">53,606,315</td>
<td align="right">9.7%</td>
</tr>
<tr>
<td align="left">PUSH_NULL</td>
<td align="right">51,740,701</td>
<td align="right">9.3%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_INSTANCE_VALUE</td>
<td align="right">37,351,185</td>
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
<td align="left">STORE_FAST</td>
<td align="right">179,562,811</td>
<td align="right">32.4%</td>
</tr>
<tr>
<td align="left">RESUME_CHECK</td>
<td align="right">136,067,680</td>
<td align="right">24.5%</td>
</tr>
<tr>
<td align="left">POP_TOP</td>
<td align="right">59,598,625</td>
<td align="right">10.7%</td>
</tr>
<tr>
<td align="left">LOAD_GLOBAL_MODULE</td>
<td align="right">39,078,751</td>
<td align="right">7.0%</td>
</tr>
<tr>
<td align="left">BUILD_TUPLE</td>
<td align="right">36,557,824</td>
<td align="right">6.6%</td>
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
<td align="right">41,060,831</td>
<td align="right">46.3%</td>
</tr>
<tr>
<td align="left">DICT_MERGE</td>
<td align="right">25,192,568</td>
<td align="right">28.4%</td>
</tr>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">15,931,348</td>
<td align="right">18.0%</td>
</tr>
<tr>
<td align="left">BUILD_MAP</td>
<td align="right">3,904,980</td>
<td align="right">4.4%</td>
</tr>
<tr>
<td align="left">STORE_FAST</td>
<td align="right">2,309,791</td>
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
<td align="right">43,922,651</td>
<td align="right">49.6%</td>
</tr>
<tr>
<td align="left">STORE_FAST</td>
<td align="right">17,450,765</td>
<td align="right">19.7%</td>
</tr>
<tr>
<td align="left">RESUME_CHECK</td>
<td align="right">11,547,475</td>
<td align="right">13.0%</td>
</tr>
<tr>
<td align="left">LOAD_FAST_LOAD_FAST</td>
<td align="right">4,981,620</td>
<td align="right">5.6%</td>
</tr>
<tr>
<td align="left">MAKE_CELL</td>
<td align="right">4,668,999</td>
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
<td align="right">46,514,569</td>
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
<td align="right">41,060,831</td>
<td align="right">29.2%</td>
</tr>
<tr>
<td align="left">LOAD_CONST</td>
<td align="right">3,370,440</td>
<td align="right">2.4%</td>
</tr>
<tr>
<td align="left">BUILD_MAP</td>
<td align="right">2,070,158</td>
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
<td align="right">50,976,920</td>
<td align="right">35.8%</td>
</tr>
<tr>
<td align="left">LOAD_FAST_LOAD_FAST</td>
<td align="right">46,732,952</td>
<td align="right">32.8%</td>
</tr>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">16,812,297</td>
<td align="right">11.8%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR</td>
<td align="right">8,859,605</td>
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
<td align="right">88,043,449</td>
<td align="right">61.7%</td>
</tr>
<tr>
<td align="left">POP_JUMP_IF_TRUE</td>
<td align="right">41,468,488</td>
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
<td align="right">2,531,462</td>
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
<td align="right">75,215,220</td>
<td align="right">43.7%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_SLOT</td>
<td align="right">58,268,820</td>
<td align="right">33.8%</td>
</tr>
<tr>
<td align="left">LOAD_FAST_LOAD_FAST</td>
<td align="right">19,570,151</td>
<td align="right">11.4%</td>
</tr>
<tr>
<td align="left">LOAD_CONST</td>
<td align="right">7,483,471</td>
<td align="right">4.3%</td>
</tr>
<tr>
<td align="left">LOAD_GLOBAL_MODULE</td>
<td align="right">2,879,880</td>
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
<td align="right">95,723,622</td>
<td align="right">55.6%</td>
</tr>
<tr>
<td align="left">INSTRUMENTED_POP_JUMP_IF_FALSE</td>
<td align="right">58,268,820</td>
<td align="right">33.8%</td>
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
<td align="right">78,570,975</td>
<td align="right">42.4%</td>
</tr>
<tr>
<td align="left">CACHE</td>
<td align="right">62,530,718</td>
<td align="right">33.8%</td>
</tr>
<tr>
<td align="left">CALL_BOUND_METHOD_EXACT_ARGS</td>
<td align="right">27,104,114</td>
<td align="right">14.6%</td>
</tr>
<tr>
<td align="left">CALL_PY_WITH_DEFAULTS</td>
<td align="right">4,454,207</td>
<td align="right">2.4%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_PROPERTY</td>
<td align="right">3,870,862</td>
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
<td align="left">RESUME_CHECK</td>
<td align="right">124,190,868</td>
<td align="right">67.1%</td>
</tr>
<tr>
<td align="left">RETURN_GENERATOR</td>
<td align="right">60,922,163</td>
<td align="right">32.9%</td>
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
<td align="right">252,695,854</td>
<td align="right">73.3%</td>
</tr>
<tr>
<td align="left">GET_ITER</td>
<td align="right">54,722,538</td>
<td align="right">15.9%</td>
</tr>
<tr>
<td align="left">EXTENDED_ARG</td>
<td align="right">17,546,212</td>
<td align="right">5.1%</td>
</tr>
<tr>
<td align="left">SWAP</td>
<td align="right">10,908,976</td>
<td align="right">3.2%</td>
</tr>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">8,516,454</td>
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
<td align="right">193,084,702</td>
<td align="right">56.0%</td>
</tr>
<tr>
<td align="left">STORE_FAST</td>
<td align="right">84,425,070</td>
<td align="right">24.5%</td>
</tr>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">26,149,918</td>
<td align="right">7.6%</td>
</tr>
<tr>
<td align="left">RETURN_CONST</td>
<td align="right">12,952,442</td>
<td align="right">3.8%</td>
</tr>
<tr>
<td align="left">SWAP</td>
<td align="right">10,524,316</td>
<td align="right">3.1%</td>
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
<td align="right">752,848,183</td>
<td align="right">33.8%</td>
</tr>
<tr>
<td align="left">POP_JUMP_IF_TRUE</td>
<td align="right">437,014,708</td>
<td align="right">19.6%</td>
</tr>
<tr>
<td align="left">STORE_FAST</td>
<td align="right">228,823,973</td>
<td align="right">10.3%</td>
</tr>
<tr>
<td align="left">POP_JUMP_IF_FALSE</td>
<td align="right">208,796,953</td>
<td align="right">9.4%</td>
</tr>
<tr>
<td align="left">STORE_SUBSCR</td>
<td align="right">110,771,820</td>
<td align="right">5.0%</td>
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
<td align="right">835,402,299</td>
<td align="right">37.5%</td>
</tr>
<tr>
<td align="left">FOR_ITER_RANGE</td>
<td align="right">464,794,357</td>
<td align="right">20.9%</td>
</tr>
<tr>
<td align="left">FOR_ITER</td>
<td align="right">252,695,854</td>
<td align="right">11.4%</td>
</tr>
<tr>
<td align="left">FOR_ITER_TUPLE</td>
<td align="right">193,693,055</td>
<td align="right">8.7%</td>
</tr>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">128,674,623</td>
<td align="right">5.8%</td>
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
<td align="left">POP_JUMP_IF_FALSE</td>
<td align="right">119,076,725</td>
<td align="right">34.3%</td>
</tr>
<tr>
<td align="left">STORE_FAST</td>
<td align="right">108,232,512</td>
<td align="right">31.2%</td>
</tr>
<tr>
<td align="left">POP_TOP</td>
<td align="right">55,694,300</td>
<td align="right">16.1%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_SLOT</td>
<td align="right">11,995,080</td>
<td align="right">3.5%</td>
</tr>
<tr>
<td align="left">STORE_ATTR_INSTANCE_VALUE</td>
<td align="right">8,968,140</td>
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
<td align="left">LOAD_FAST</td>
<td align="right">131,780,869</td>
<td align="right">38.0%</td>
</tr>
<tr>
<td align="left">LOAD_FAST_LOAD_FAST</td>
<td align="right">78,079,400</td>
<td align="right">22.5%</td>
</tr>
<tr>
<td align="left">LOAD_CONST</td>
<td align="right">38,631,215</td>
<td align="right">11.1%</td>
</tr>
<tr>
<td align="left">LOAD_GLOBAL_BUILTIN</td>
<td align="right">27,880,482</td>
<td align="right">8.0%</td>
</tr>
<tr>
<td align="left">JUMP_BACKWARD</td>
<td align="right">24,968,520</td>
<td align="right">7.2%</td>
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
<td align="right">35,834,671</td>
<td align="right">75.5%</td>
</tr>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">10,675,191</td>
<td align="right">22.5%</td>
</tr>
<tr>
<td align="left">LOAD_CONST</td>
<td align="right">712,020</td>
<td align="right">1.5%</td>
</tr>
<tr>
<td align="left">RETURN_VALUE</td>
<td align="right">110,193</td>
<td align="right">0.2%</td>
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
<td align="right">46,514,569</td>
<td align="right">98.0%</td>
</tr>
<tr>
<td align="left">STORE_FAST</td>
<td align="right">443,253</td>
<td align="right">0.9%</td>
</tr>
<tr>
<td align="left">UNPACK_SEQUENCE_LIST</td>
<td align="right">345,120</td>
<td align="right">0.7%</td>
</tr>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">136,173</td>
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
<td align="right">520,548,644</td>
<td align="right">50.2%</td>
</tr>
<tr>
<td align="left">LOAD_GLOBAL_BUILTIN</td>
<td align="right">220,581,768</td>
<td align="right">21.3%</td>
</tr>
<tr>
<td align="left">LOAD_GLOBAL_MODULE</td>
<td align="right">101,476,855</td>
<td align="right">9.8%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_SLOT</td>
<td align="right">83,426,669</td>
<td align="right">8.0%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR</td>
<td align="right">38,676,822</td>
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
<td align="right">228,852,354</td>
<td align="right">22.1%</td>
</tr>
<tr>
<td align="left">STORE_FAST</td>
<td align="right">227,303,300</td>
<td align="right">21.9%</td>
</tr>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">101,222,191</td>
<td align="right">9.8%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_SLOT</td>
<td align="right">80,213,818</td>
<td align="right">7.7%</td>
</tr>
<tr>
<td align="left">PUSH_NULL</td>
<td align="right">66,176,709</td>
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
<td align="right">2,257,255,878</td>
<td align="right">35.1%</td>
</tr>
<tr>
<td align="left">LOAD_CONST</td>
<td align="right">715,009,001</td>
<td align="right">11.1%</td>
</tr>
<tr>
<td align="left">LOAD_FAST_LOAD_FAST</td>
<td align="right">387,847,359</td>
<td align="right">6.0%</td>
</tr>
<tr>
<td align="left">STORE_FAST</td>
<td align="right">275,684,307</td>
<td align="right">4.3%</td>
</tr>
<tr>
<td align="left">POP_JUMP_IF_FALSE</td>
<td align="right">245,985,588</td>
<td align="right">3.8%</td>
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
<td align="right">810,110,008</td>
<td align="right">12.6%</td>
</tr>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">784,265,008</td>
<td align="right">12.2%</td>
</tr>
<tr>
<td align="left">LOAD_CONST</td>
<td align="right">715,009,001</td>
<td align="right">11.1%</td>
</tr>
<tr>
<td align="left">COMPARE_OP_INT</td>
<td align="right">549,709,507</td>
<td align="right">8.5%</td>
</tr>
<tr>
<td align="left">STORE_FAST</td>
<td align="right">411,919,405</td>
<td align="right">6.4%</td>
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
<td align="right">318,840,141</td>
<td align="right">46.9%</td>
</tr>
<tr>
<td align="left">POP_JUMP_IF_FALSE</td>
<td align="right">53,361,361</td>
<td align="right">7.8%</td>
</tr>
<tr>
<td align="left">CALL_BUILTIN_FAST_WITH_KEYWORDS</td>
<td align="right">46,765,320</td>
<td align="right">6.9%</td>
</tr>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">30,055,886</td>
<td align="right">4.4%</td>
</tr>
<tr>
<td align="left">POP_JUMP_IF_NONE</td>
<td align="right">26,911,620</td>
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
<td align="left">LOAD_FAST</td>
<td align="right">432,868,312</td>
<td align="right">63.7%</td>
</tr>
<tr>
<td align="left">PUSH_NULL</td>
<td align="right">49,698,131</td>
<td align="right">7.3%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR</td>
<td align="right">35,046,357</td>
<td align="right">5.2%</td>
</tr>
<tr>
<td align="left">LOAD_CONST</td>
<td align="right">31,476,286</td>
<td align="right">4.6%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_METHOD_NO_DICT</td>
<td align="right">18,491,405</td>
<td align="right">2.7%</td>
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
<td align="right">3,579,086,144</td>
<td align="right">16.1%</td>
</tr>
<tr>
<td align="left">POP_JUMP_IF_FALSE</td>
<td align="right">2,481,415,959</td>
<td align="right">11.2%</td>
</tr>
<tr>
<td align="left">LOAD_GLOBAL_BUILTIN</td>
<td align="right">2,292,127,250</td>
<td align="right">10.3%</td>
</tr>
<tr>
<td align="left">RESUME_CHECK</td>
<td align="right">1,817,063,591</td>
<td align="right">8.2%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_INSTANCE_VALUE</td>
<td align="right">1,054,650,054</td>
<td align="right">4.7%</td>
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
<td align="right">3,215,991,965</td>
<td align="right">14.5%</td>
</tr>
<tr>
<td align="left">LOAD_CONST</td>
<td align="right">2,257,255,878</td>
<td align="right">10.2%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_METHOD_WITH_VALUES</td>
<td align="right">1,538,779,346</td>
<td align="right">6.9%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_SLOT</td>
<td align="right">940,860,473</td>
<td align="right">4.2%</td>
</tr>
<tr>
<td align="left">LOAD_GLOBAL_BUILTIN</td>
<td align="right">922,497,064</td>
<td align="right">4.2%</td>
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
<td align="right">975,395,933</td>
<td align="right">18.5%</td>
</tr>
<tr>
<td align="left">LOAD_FAST_LOAD_FAST</td>
<td align="right">500,581,944</td>
<td align="right">9.5%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_METHOD_WITH_VALUES</td>
<td align="right">446,210,924</td>
<td align="right">8.4%</td>
</tr>
<tr>
<td align="left">POP_JUMP_IF_FALSE</td>
<td align="right">366,432,675</td>
<td align="right">6.9%</td>
</tr>
<tr>
<td align="left">PUSH_NULL</td>
<td align="right">287,216,486</td>
<td align="right">5.4%</td>
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
<td align="right">528,706,052</td>
<td align="right">10.0%</td>
</tr>
<tr>
<td align="left">CALL_PY_EXACT_ARGS</td>
<td align="right">510,378,216</td>
<td align="right">9.7%</td>
</tr>
<tr>
<td align="left">LOAD_FAST_LOAD_FAST</td>
<td align="right">500,581,944</td>
<td align="right">9.5%</td>
</tr>
<tr>
<td align="left">LOAD_CONST</td>
<td align="right">387,847,359</td>
<td align="right">7.3%</td>
</tr>
<tr>
<td align="left">BINARY_SUBSCR</td>
<td align="right">354,205,695</td>
<td align="right">6.7%</td>
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
<td align="left">INSTRUMENTED_RESUME</td>
<td align="right">58,272,600</td>
<td align="right">72.7%</td>
</tr>
<tr>
<td align="left">INSTRUMENTED_POP_JUMP_IF_TRUE</td>
<td align="right">14,567,760</td>
<td align="right">18.2%</td>
</tr>
<tr>
<td align="left">INSTRUMENTED_POP_JUMP_IF_FALSE</td>
<td align="right">7,284,380</td>
<td align="right">9.1%</td>
</tr>
<tr>
<td align="left">STORE_FAST</td>
<td align="right">13,960</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">RESUME_CHECK</td>
<td align="right">6,793</td>
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
<td align="right">65,557,881</td>
<td align="right">81.8%</td>
</tr>
<tr>
<td align="left">INSTRUMENTED_POP_JUMP_IF_NONE</td>
<td align="right">14,567,340</td>
<td align="right">18.2%</td>
</tr>
<tr>
<td align="left">LOAD_GLOBAL_MODULE</td>
<td align="right">30,751</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">LOAD_GLOBAL_BUILTIN</td>
<td align="right">12,552</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_MODULE</td>
<td align="right">9,460</td>
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
<td align="right">1,925,527,237</td>
<td align="right">38.1%</td>
</tr>
<tr>
<td align="left">COMPARE_OP_INT</td>
<td align="right">1,104,268,706</td>
<td align="right">21.8%</td>
</tr>
<tr>
<td align="left">IS_OP</td>
<td align="right">492,779,034</td>
<td align="right">9.7%</td>
</tr>
<tr>
<td align="left">TO_BOOL_NONE</td>
<td align="right">299,282,883</td>
<td align="right">5.9%</td>
</tr>
<tr>
<td align="left">CONTAINS_OP_SET</td>
<td align="right">294,730,859</td>
<td align="right">5.8%</td>
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
<td align="right">2,481,415,959</td>
<td align="right">49.1%</td>
</tr>
<tr>
<td align="left">LOAD_GLOBAL_BUILTIN</td>
<td align="right">815,714,792</td>
<td align="right">16.1%</td>
</tr>
<tr>
<td align="left">LOAD_FAST_LOAD_FAST</td>
<td align="right">366,432,675</td>
<td align="right">7.2%</td>
</tr>
<tr>
<td align="left">RETURN_CONST</td>
<td align="right">308,922,927</td>
<td align="right">6.1%</td>
</tr>
<tr>
<td align="left">LOAD_CONST</td>
<td align="right">245,985,588</td>
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
<td align="right">168,707,085</td>
<td align="right">85.4%</td>
</tr>
<tr>
<td align="left">LOAD_DEREF</td>
<td align="right">14,342,962</td>
<td align="right">7.3%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_INSTANCE_VALUE</td>
<td align="right">5,736,779</td>
<td align="right">2.9%</td>
</tr>
<tr>
<td align="left">BINARY_SUBSCR</td>
<td align="right">5,114,730</td>
<td align="right">2.6%</td>
</tr>
<tr>
<td align="left">LOAD_GLOBAL_MODULE</td>
<td align="right">1,929,780</td>
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
<td align="left">LOAD_FAST</td>
<td align="right">116,430,535</td>
<td align="right">59.0%</td>
</tr>
<tr>
<td align="left">LOAD_DEREF</td>
<td align="right">26,911,620</td>
<td align="right">13.6%</td>
</tr>
<tr>
<td align="left">JUMP_BACKWARD</td>
<td align="right">13,654,093</td>
<td align="right">6.9%</td>
</tr>
<tr>
<td align="left">LOAD_GLOBAL_BUILTIN</td>
<td align="right">12,921,678</td>
<td align="right">6.5%</td>
</tr>
<tr>
<td align="left">LOAD_FAST_LOAD_FAST</td>
<td align="right">9,767,765</td>
<td align="right">4.9%</td>
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
<td align="right">306,545,138</td>
<td align="right">84.2%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_INSTANCE_VALUE</td>
<td align="right">23,410,848</td>
<td align="right">6.4%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR</td>
<td align="right">13,720,809</td>
<td align="right">3.8%</td>
</tr>
<tr>
<td align="left">STORE_FAST_LOAD_FAST</td>
<td align="right">8,870,340</td>
<td align="right">2.4%</td>
</tr>
<tr>
<td align="left">EXTENDED_ARG</td>
<td align="right">7,323,040</td>
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
<td align="left">LOAD_FAST</td>
<td align="right">190,757,525</td>
<td align="right">52.4%</td>
</tr>
<tr>
<td align="left">LOAD_FAST_LOAD_FAST</td>
<td align="right">64,874,138</td>
<td align="right">17.8%</td>
</tr>
<tr>
<td align="left">LOAD_GLOBAL_MODULE</td>
<td align="right">36,433,882</td>
<td align="right">10.0%</td>
</tr>
<tr>
<td align="left">JUMP_BACKWARD</td>
<td align="right">26,884,535</td>
<td align="right">7.4%</td>
</tr>
<tr>
<td align="left">LOAD_GLOBAL_BUILTIN</td>
<td align="right">19,528,685</td>
<td align="right">5.4%</td>
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
<td align="right">636,728,319</td>
<td align="right">53.0%</td>
</tr>
<tr>
<td align="left">COMPARE_OP_INT</td>
<td align="right">111,062,677</td>
<td align="right">9.3%</td>
</tr>
<tr>
<td align="left">TO_BOOL</td>
<td align="right">99,601,492</td>
<td align="right">8.3%</td>
</tr>
<tr>
<td align="left">CONTAINS_OP_DICT</td>
<td align="right">54,576,605</td>
<td align="right">4.5%</td>
</tr>
<tr>
<td align="left">IS_OP</td>
<td align="right">49,450,940</td>
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
<td align="right">452,854,239</td>
<td align="right">37.7%</td>
</tr>
<tr>
<td align="left">JUMP_BACKWARD</td>
<td align="right">437,014,708</td>
<td align="right">36.4%</td>
</tr>
<tr>
<td align="left">LOAD_GLOBAL_BUILTIN</td>
<td align="right">90,099,279</td>
<td align="right">7.5%</td>
</tr>
<tr>
<td align="left">LOAD_CONST</td>
<td align="right">67,464,142</td>
<td align="right">5.6%</td>
</tr>
<tr>
<td align="left">LOAD_FAST_LOAD_FAST</td>
<td align="right">34,578,260</td>
<td align="right">2.9%</td>
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
<td align="right">31,632,910</td>
<td align="right">64.9%</td>
</tr>
<tr>
<td align="left">LOAD_FAST_LOAD_FAST</td>
<td align="right">8,519,267</td>
<td align="right">17.5%</td>
</tr>
<tr>
<td align="left">CALL</td>
<td align="right">5,436,780</td>
<td align="right">11.2%</td>
</tr>
<tr>
<td align="left">SWAP</td>
<td align="right">1,242,901</td>
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
<td align="right">14,261,162</td>
<td align="right">29.3%</td>
</tr>
<tr>
<td align="left">LOAD_DEREF</td>
<td align="right">13,446,060</td>
<td align="right">27.6%</td>
</tr>
<tr>
<td align="left">RETURN_CONST</td>
<td align="right">9,063,273</td>
<td align="right">18.6%</td>
</tr>
<tr>
<td align="left">JUMP_BACKWARD</td>
<td align="right">6,765,600</td>
<td align="right">13.9%</td>
</tr>
<tr>
<td align="left">LOAD_CONST</td>
<td align="right">2,291,640</td>
<td align="right">4.7%</td>
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
<td align="right">711,822,792</td>
<td align="right">9.9%</td>
</tr>
<tr>
<td align="left">FOR_ITER_LIST</td>
<td align="right">550,308,059</td>
<td align="right">7.7%</td>
</tr>
<tr>
<td align="left">FOR_ITER_RANGE</td>
<td align="right">435,647,120</td>
<td align="right">6.1%</td>
</tr>
<tr>
<td align="left">RETURN_VALUE</td>
<td align="right">416,422,854</td>
<td align="right">5.8%</td>
</tr>
<tr>
<td align="left">LOAD_CONST</td>
<td align="right">411,919,405</td>
<td align="right">5.8%</td>
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
<td align="right">3,579,086,144</td>
<td align="right">50.0%</td>
</tr>
<tr>
<td align="left">LOAD_FAST_LOAD_FAST</td>
<td align="right">975,395,933</td>
<td align="right">13.6%</td>
</tr>
<tr>
<td align="left">STORE_FAST</td>
<td align="right">711,822,792</td>
<td align="right">9.9%</td>
</tr>
<tr>
<td align="left">LOAD_GLOBAL_BUILTIN</td>
<td align="right">474,179,763</td>
<td align="right">6.6%</td>
</tr>
<tr>
<td align="left">LOAD_DEREF</td>
<td align="right">318,840,141</td>
<td align="right">4.5%</td>
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
<td align="right">1,603,189,342</td>
<td align="right">64.4%</td>
</tr>
<tr>
<td align="left">UNPACK_SEQUENCE_TWO_TUPLE</td>
<td align="right">329,435,977</td>
<td align="right">13.2%</td>
</tr>
<tr>
<td align="left">UNPACK_SEQUENCE_TUPLE</td>
<td align="right">255,982,064</td>
<td align="right">10.3%</td>
</tr>
<tr>
<td align="left">UNPACK_SEQUENCE_LIST</td>
<td align="right">221,203,222</td>
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
<td align="right">1,603,189,342</td>
<td align="right">64.4%</td>
</tr>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">612,955,104</td>
<td align="right">24.6%</td>
</tr>
<tr>
<td align="left">STORE_FAST</td>
<td align="right">103,169,002</td>
<td align="right">4.1%</td>
</tr>
<tr>
<td align="left">LOAD_FAST_LOAD_FAST</td>
<td align="right">74,352,932</td>
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
<td align="left">CALL_METHOD_DESCRIPTOR_FAST</td>
<td align="right">14,567,240</td>
<td align="right">99.2%</td>
</tr>
<tr>
<td align="left">CALL_METHOD_DESCRIPTOR_NOARGS</td>
<td align="right">96,080</td>
<td align="right">0.7%</td>
</tr>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">11,119</td>
<td align="right">0.1%</td>
</tr>
<tr>
<td align="left">CALL_BUILTIN_FAST</td>
<td align="right">2,440</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">RETURN_VALUE</td>
<td align="right">1,740</td>
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
<td align="right">14,567,580</td>
<td align="right">99.2%</td>
</tr>
<tr>
<td align="left">STORE_FAST_STORE_FAST</td>
<td align="right">106,260</td>
<td align="right">0.7%</td>
</tr>
<tr>
<td align="left">STORE_FAST</td>
<td align="right">4,404</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">UNPACK_SEQUENCE_TWO_TUPLE</td>
<td align="right">2,400</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">UNPACK_SEQUENCE_TUPLE</td>
<td align="right">620</td>
<td align="right">0.0%</td>
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
<td align="right">38.4%</td>
</tr>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">69,337,860</td>
<td align="right">24.4%</td>
</tr>
<tr>
<td align="left">LOAD_FAST_LOAD_FAST</td>
<td align="right">36,003,600</td>
<td align="right">12.7%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_INSTANCE_VALUE</td>
<td align="right">29,861,940</td>
<td align="right">10.5%</td>
</tr>
<tr>
<td align="left">BINARY_SUBSCR</td>
<td align="right">24,729,580</td>
<td align="right">8.7%</td>
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
<td align="right">108,305,468</td>
<td align="right">38.1%</td>
</tr>
<tr>
<td align="left">LOAD_FAST_LOAD_FAST</td>
<td align="right">73,280,400</td>
<td align="right">25.8%</td>
</tr>
<tr>
<td align="left">SWAP</td>
<td align="right">55,701,000</td>
<td align="right">19.6%</td>
</tr>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">29,548,920</td>
<td align="right">10.4%</td>
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
<td align="right">174,518,207</td>
<td align="right">73.4%</td>
</tr>
<tr>
<td align="left">LOAD_FAST_LOAD_FAST</td>
<td align="right">17,827,633</td>
<td align="right">7.5%</td>
</tr>
<tr>
<td align="left">LOAD_CONST</td>
<td align="right">14,010,700</td>
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
<td align="right">140,276,383</td>
<td align="right">59.0%</td>
</tr>
<tr>
<td align="left">STORE_FAST</td>
<td align="right">36,989,144</td>
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
<td align="right">41,518,739</td>
<td align="right">39.1%</td>
</tr>
<tr>
<td align="left">CALL_METHOD_DESCRIPTOR_NOARGS</td>
<td align="right">9,883,661</td>
<td align="right">9.3%</td>
</tr>
<tr>
<td align="left">BINARY_OP_MULTIPLY_INT</td>
<td align="right">7,662,580</td>
<td align="right">7.2%</td>
</tr>
<tr>
<td align="left">BINARY_OP_ADD_INT</td>
<td align="right">6,888,220</td>
<td align="right">6.5%</td>
</tr>
<tr>
<td align="left">LOAD_CONST</td>
<td align="right">6,494,880</td>
<td align="right">6.1%</td>
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
<td align="right">33,425,978</td>
<td align="right">31.5%</td>
</tr>
<tr>
<td align="left">BINARY_OP_MULTIPLY_FLOAT</td>
<td align="right">24,782,880</td>
<td align="right">23.4%</td>
</tr>
<tr>
<td align="left">STORE_FAST</td>
<td align="right">18,097,167</td>
<td align="right">17.1%</td>
</tr>
<tr>
<td align="left">CALL_BUILTIN_CLASS</td>
<td align="right">5,508,053</td>
<td align="right">5.2%</td>
</tr>
<tr>
<td align="left">BINARY_OP</td>
<td align="right">4,804,980</td>
<td align="right">4.5%</td>
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
<td align="right">186,720,732</td>
<td align="right">41.4%</td>
</tr>
<tr>
<td align="left">LOAD_GLOBAL_BUILTIN</td>
<td align="right">155,740,789</td>
<td align="right">34.5%</td>
</tr>
<tr>
<td align="left">LOAD_FAST_LOAD_FAST</td>
<td align="right">61,137,292</td>
<td align="right">13.5%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_MODULE</td>
<td align="right">21,456,160</td>
<td align="right">4.8%</td>
</tr>
<tr>
<td align="left">BUILD_TUPLE</td>
<td align="right">9,926,516</td>
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
<td align="right">440,093,463</td>
<td align="right">97.5%</td>
</tr>
<tr>
<td align="left">YIELD_VALUE</td>
<td align="right">5,173,083</td>
<td align="right">1.1%</td>
</tr>
<tr>
<td align="left">COPY</td>
<td align="right">3,120,420</td>
<td align="right">0.7%</td>
</tr>
<tr>
<td align="left">RETURN_VALUE</td>
<td align="right">1,664,667</td>
<td align="right">0.4%</td>
</tr>
<tr>
<td align="left">STORE_FAST</td>
<td align="right">1,176,359</td>
<td align="right">0.3%</td>
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
<td align="right">102,406,570</td>
<td align="right">39.0%</td>
</tr>
<tr>
<td align="left">LOAD_FAST_LOAD_FAST</td>
<td align="right">53,345,760</td>
<td align="right">20.3%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_METHOD_NO_DICT</td>
<td align="right">35,831,120</td>
<td align="right">13.6%</td>
</tr>
<tr>
<td align="left">LOAD_CONST</td>
<td align="right">26,964,684</td>
<td align="right">10.3%</td>
</tr>
<tr>
<td align="left">LOAD_GLOBAL_MODULE</td>
<td align="right">15,395,460</td>
<td align="right">5.9%</td>
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
<td align="right">188,816,259</td>
<td align="right">71.9%</td>
</tr>
<tr>
<td align="left">UNPACK_SEQUENCE</td>
<td align="right">14,567,240</td>
<td align="right">5.5%</td>
</tr>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">9,920,243</td>
<td align="right">3.8%</td>
</tr>
<tr>
<td align="left">RETURN_VALUE</td>
<td align="right">9,172,800</td>
<td align="right">3.5%</td>
</tr>
<tr>
<td align="left">TO_BOOL_BOOL</td>
<td align="right">7,396,802</td>
<td align="right">2.8%</td>
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
<td align="right">737,474,861</td>
<td align="right">33.8%</td>
</tr>
<tr>
<td align="left">LOAD_FAST_LOAD_FAST</td>
<td align="right">510,378,216</td>
<td align="right">23.4%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_METHOD_WITH_VALUES</td>
<td align="right">388,523,590</td>
<td align="right">17.8%</td>
</tr>
<tr>
<td align="left">LOAD_GLOBAL_MODULE</td>
<td align="right">96,909,699</td>
<td align="right">4.4%</td>
</tr>
<tr>
<td align="left">BINARY_OP_SUBTRACT_INT</td>
<td align="right">93,675,400</td>
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
<td align="right">1,949,579,119</td>
<td align="right">89.4%</td>
</tr>
<tr>
<td align="left">RETURN_GENERATOR</td>
<td align="right">134,487,399</td>
<td align="right">6.2%</td>
</tr>
<tr>
<td align="left">COPY_FREE_VARS</td>
<td align="right">78,570,975</td>
<td align="right">3.6%</td>
</tr>
<tr>
<td align="left">INSTRUMENTED_RESUME</td>
<td align="right">14,572,740</td>
<td align="right">0.7%</td>
</tr>
<tr>
<td align="left">MAKE_CELL</td>
<td align="right">2,444,894</td>
<td align="right">0.1%</td>
</tr>
</tbody>
</table>


</details>

### CALL_PY_WITH_DEFAULTS

<details>
<summary> Successors and predecessors for CALL_PY_WITH_DEFAULTS </summary>

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
<td align="right">55,973,680</td>
<td align="right">40.8%</td>
</tr>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">31,714,953</td>
<td align="right">23.1%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_METHOD_WITH_VALUES</td>
<td align="right">16,029,402</td>
<td align="right">11.7%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_METHOD_NO_DICT</td>
<td align="right">13,438,715</td>
<td align="right">9.8%</td>
</tr>
<tr>
<td align="left">BINARY_OP_ADD_INT</td>
<td align="right">4,200,980</td>
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
<td align="left">RESUME_CHECK</td>
<td align="right">128,616,646</td>
<td align="right">93.7%</td>
</tr>
<tr>
<td align="left">COPY_FREE_VARS</td>
<td align="right">4,454,207</td>
<td align="right">3.2%</td>
</tr>
<tr>
<td align="left">RETURN_GENERATOR</td>
<td align="right">3,418,920</td>
<td align="right">2.5%</td>
</tr>
<tr>
<td align="left">MAKE_CELL</td>
<td align="right">607,107</td>
<td align="right">0.4%</td>
</tr>
<tr>
<td align="left">CALL_PY_EXACT_ARGS</td>
<td align="right">81,600</td>
<td align="right">0.1%</td>
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
<td align="right">337,182,052</td>
<td align="right">98.9%</td>
</tr>
<tr>
<td align="left">LOAD_CONST</td>
<td align="right">3,657,434</td>
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
<td align="right">293,762,385</td>
<td align="right">86.2%</td>
</tr>
<tr>
<td align="left">LOAD_GLOBAL_BUILTIN</td>
<td align="right">17,744,530</td>
<td align="right">5.2%</td>
</tr>
<tr>
<td align="left">LOAD_GLOBAL_MODULE</td>
<td align="right">13,471,500</td>
<td align="right">4.0%</td>
</tr>
<tr>
<td align="left">COMPARE_OP</td>
<td align="right">4,367,113</td>
<td align="right">1.3%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR</td>
<td align="right">3,044,600</td>
<td align="right">0.9%</td>
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
<td align="right">835,402,299</td>
<td align="right">77.6%</td>
</tr>
<tr>
<td align="left">GET_ITER</td>
<td align="right">164,217,770</td>
<td align="right">15.3%</td>
</tr>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">54,352,671</td>
<td align="right">5.1%</td>
</tr>
<tr>
<td align="left">EXTENDED_ARG</td>
<td align="right">17,349,490</td>
<td align="right">1.6%</td>
</tr>
<tr>
<td align="left">SWAP</td>
<td align="right">3,409,195</td>
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
<td align="right">550,308,059</td>
<td align="right">51.1%</td>
</tr>
<tr>
<td align="left">UNPACK_SEQUENCE_TWO_TUPLE</td>
<td align="right">287,889,323</td>
<td align="right">26.8%</td>
</tr>
<tr>
<td align="left">RETURN_CONST</td>
<td align="right">95,692,989</td>
<td align="right">8.9%</td>
</tr>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">43,936,058</td>
<td align="right">4.1%</td>
</tr>
<tr>
<td align="left">LOAD_FAST_LOAD_FAST</td>
<td align="right">40,061,600</td>
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
<td align="right">464,794,357</td>
<td align="right">93.0%</td>
</tr>
<tr>
<td align="left">GET_ITER</td>
<td align="right">26,500,784</td>
<td align="right">5.3%</td>
</tr>
<tr>
<td align="left">SWAP</td>
<td align="right">4,416,060</td>
<td align="right">0.9%</td>
</tr>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">2,547,420</td>
<td align="right">0.5%</td>
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
<td align="right">435,647,120</td>
<td align="right">87.2%</td>
</tr>
<tr>
<td align="left">STORE_FAST_LOAD_FAST</td>
<td align="right">35,295,420</td>
<td align="right">7.1%</td>
</tr>
<tr>
<td align="left">JUMP_BACKWARD</td>
<td align="right">11,477,580</td>
<td align="right">2.3%</td>
</tr>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">4,034,253</td>
<td align="right">0.8%</td>
</tr>
<tr>
<td align="left">RETURN_CONST</td>
<td align="right">3,192,863</td>
<td align="right">0.6%</td>
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
<td align="right">523,077,497</td>
<td align="right">52.2%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_INSTANCE_VALUE</td>
<td align="right">213,762,099</td>
<td align="right">21.3%</td>
</tr>
<tr>
<td align="left">LOAD_CONST</td>
<td align="right">90,512,440</td>
<td align="right">9.0%</td>
</tr>
<tr>
<td align="left">LOAD_GLOBAL_MODULE</td>
<td align="right">48,664,838</td>
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
<td align="right">497,912,669</td>
<td align="right">49.7%</td>
</tr>
<tr>
<td align="left">CALL_METHOD_DESCRIPTOR_NOARGS</td>
<td align="right">160,121,673</td>
<td align="right">16.0%</td>
</tr>
<tr>
<td align="left">LOAD_CONST</td>
<td align="right">99,904,059</td>
<td align="right">10.0%</td>
</tr>
<tr>
<td align="left">LOAD_FAST_LOAD_FAST</td>
<td align="right">78,063,637</td>
<td align="right">7.8%</td>
</tr>
<tr>
<td align="left">CALL_PY_EXACT_ARGS</td>
<td align="right">66,813,685</td>
<td align="right">6.7%</td>
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
<td align="right">312,158,008</td>
<td align="right">95.2%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_MODULE</td>
<td align="right">13,616,040</td>
<td align="right">4.2%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_NONDESCRIPTOR_NO_DICT</td>
<td align="right">1,081,680</td>
<td align="right">0.3%</td>
</tr>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">628,120</td>
<td align="right">0.2%</td>
</tr>
<tr>
<td align="left">LOAD_DEREF</td>
<td align="right">335,160</td>
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
<td align="left">PUSH_NULL</td>
<td align="right">261,491,832</td>
<td align="right">79.8%</td>
</tr>
<tr>
<td align="left">CALL_ISINSTANCE</td>
<td align="right">21,456,160</td>
<td align="right">6.5%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_MODULE</td>
<td align="right">13,616,040</td>
<td align="right">4.2%</td>
</tr>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">13,179,891</td>
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
<td align="right">922,497,064</td>
<td align="right">26.9%</td>
</tr>
<tr>
<td align="left">POP_JUMP_IF_FALSE</td>
<td align="right">815,714,792</td>
<td align="right">23.8%</td>
</tr>
<tr>
<td align="left">RESUME_CHECK</td>
<td align="right">726,877,060</td>
<td align="right">21.2%</td>
</tr>
<tr>
<td align="left">STORE_FAST</td>
<td align="right">474,179,763</td>
<td align="right">13.8%</td>
</tr>
<tr>
<td align="left">POP_JUMP_IF_TRUE</td>
<td align="right">90,099,279</td>
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
<td align="left">LOAD_FAST</td>
<td align="right">2,292,127,250</td>
<td align="right">66.8%</td>
</tr>
<tr>
<td align="left">CALL_BUILTIN_FAST</td>
<td align="right">434,497,240</td>
<td align="right">12.7%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR</td>
<td align="right">220,581,768</td>
<td align="right">6.4%</td>
</tr>
<tr>
<td align="left">CALL_ISINSTANCE</td>
<td align="right">155,740,789</td>
<td align="right">4.5%</td>
</tr>
<tr>
<td align="left">LOAD_FAST_LOAD_FAST</td>
<td align="right">125,271,623</td>
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
<td align="right">714,002,100</td>
<td align="right">34.2%</td>
</tr>
<tr>
<td align="left">RESUME_CHECK</td>
<td align="right">238,126,246</td>
<td align="right">11.4%</td>
</tr>
<tr>
<td align="left">STORE_FAST</td>
<td align="right">206,671,921</td>
<td align="right">9.9%</td>
</tr>
<tr>
<td align="left">POP_JUMP_IF_FALSE</td>
<td align="right">192,350,671</td>
<td align="right">9.2%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_METHOD_WITH_VALUES</td>
<td align="right">89,991,467</td>
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
<td align="right">361,580,718</td>
<td align="right">17.3%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_MODULE</td>
<td align="right">312,158,008</td>
<td align="right">14.9%</td>
</tr>
<tr>
<td align="left">CONTAINS_OP_SET</td>
<td align="right">257,599,440</td>
<td align="right">12.3%</td>
</tr>
<tr>
<td align="left">CALL_ISINSTANCE</td>
<td align="right">186,720,732</td>
<td align="right">8.9%</td>
</tr>
<tr>
<td align="left">LOAD_FAST_LOAD_FAST</td>
<td align="right">165,773,014</td>
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
<td align="right">1,949,579,119</td>
<td align="right">44.1%</td>
</tr>
<tr>
<td align="left">CACHE</td>
<td align="right">1,000,326,215</td>
<td align="right">22.6%</td>
</tr>
<tr>
<td align="left">SEND_GEN</td>
<td align="right">383,235,380</td>
<td align="right">8.7%</td>
</tr>
<tr>
<td align="left">POP_TOP</td>
<td align="right">230,562,442</td>
<td align="right">5.2%</td>
</tr>
<tr>
<td align="left">CALL</td>
<td align="right">136,067,680</td>
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
<td align="left">LOAD_FAST</td>
<td align="right">1,817,063,591</td>
<td align="right">41.1%</td>
</tr>
<tr>
<td align="left">LOAD_GLOBAL_BUILTIN</td>
<td align="right">726,877,060</td>
<td align="right">16.4%</td>
</tr>
<tr>
<td align="left">POP_TOP</td>
<td align="right">564,052,295</td>
<td align="right">12.7%</td>
</tr>
<tr>
<td align="left">JUMP_BACKWARD_NO_INTERRUPT</td>
<td align="right">388,880,420</td>
<td align="right">8.8%</td>
</tr>
<tr>
<td align="left">LOAD_GLOBAL_MODULE</td>
<td align="right">238,126,246</td>
<td align="right">5.4%</td>
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
<td align="right">657,917,293</td>
<td align="right">23.4%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_INSTANCE_VALUE</td>
<td align="right">554,765,397</td>
<td align="right">19.8%</td>
</tr>
<tr>
<td align="left">CALL_BUILTIN_FAST</td>
<td align="right">486,851,848</td>
<td align="right">17.3%</td>
</tr>
<tr>
<td align="left">CALL_ISINSTANCE</td>
<td align="right">440,093,463</td>
<td align="right">15.7%</td>
</tr>
<tr>
<td align="left">RETURN_VALUE</td>
<td align="right">234,688,070</td>
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
<td align="right">1,925,527,237</td>
<td align="right">68.6%</td>
</tr>
<tr>
<td align="left">POP_JUMP_IF_TRUE</td>
<td align="right">636,728,319</td>
<td align="right">22.7%</td>
</tr>
<tr>
<td align="left">INSTRUMENTED_POP_JUMP_IF_FALSE</td>
<td align="right">145,675,980</td>
<td align="right">5.2%</td>
</tr>
<tr>
<td align="left">EXTENDED_ARG</td>
<td align="right">78,443,354</td>
<td align="right">2.8%</td>
</tr>
<tr>
<td align="left">UNARY_NOT</td>
<td align="right">21,427,131</td>
<td align="right">0.8%</td>
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
<td align="right">156,847,091</td>
<td align="right">76.7%</td>
</tr>
<tr>
<td align="left">CALL_BUILTIN_O</td>
<td align="right">12,835,620</td>
<td align="right">6.3%</td>
</tr>
<tr>
<td align="left">COPY</td>
<td align="right">8,740,220</td>
<td align="right">4.3%</td>
</tr>
<tr>
<td align="left">BINARY_OP</td>
<td align="right">7,074,914</td>
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
<td align="right">171,367,173</td>
<td align="right">83.8%</td>
</tr>
<tr>
<td align="left">POP_JUMP_IF_TRUE</td>
<td align="right">32,000,272</td>
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
<td align="right">287,889,323</td>
<td align="right">51.3%</td>
</tr>
<tr>
<td align="left">FOR_ITER</td>
<td align="right">193,084,702</td>
<td align="right">34.4%</td>
</tr>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">36,675,606</td>
<td align="right">6.5%</td>
</tr>
<tr>
<td align="left">RETURN_VALUE</td>
<td align="right">31,388,655</td>
<td align="right">5.6%</td>
</tr>
<tr>
<td align="left">BINARY_SUBSCR_LIST_INT</td>
<td align="right">5,828,318</td>
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
<td align="right">329,435,977</td>
<td align="right">58.7%</td>
</tr>
<tr>
<td align="left">STORE_FAST</td>
<td align="right">215,829,981</td>
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
<td align="right">1,000,326,215</td>
<td align="right">80.6%</td>
</tr>
<tr>
<td align="left">POP_TOP</td>
<td align="right">87,757,378</td>
<td align="right">7.1%</td>
</tr>
<tr>
<td align="left">COPY_FREE_VARS</td>
<td align="right">62,530,718</td>
<td align="right">5.0%</td>
</tr>
<tr>
<td align="left">INSTRUMENTED_RESUME</td>
<td align="right">58,268,760</td>
<td align="right">4.7%</td>
</tr>
<tr>
<td align="left">RETURN_GENERATOR</td>
<td align="right">30,371,700</td>
<td align="right">2.4%</td>
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
<td align="right">468,254,785</td>
<td align="right">37.8%</td>
</tr>
<tr>
<td align="left">RETURN_CONST</td>
<td align="right">352,450,953</td>
<td align="right">28.5%</td>
</tr>
<tr>
<td align="left">RETURN_VALUE</td>
<td align="right">328,892,029</td>
<td align="right">26.6%</td>
</tr>
<tr>
<td align="left">INSTRUMENTED_RETURN_VALUE</td>
<td align="right">58,268,700</td>
<td align="right">4.7%</td>
</tr>
<tr>
<td align="left">RETURN_GENERATOR</td>
<td align="right">30,381,000</td>
<td align="right">2.5%</td>
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
<td align="right">105,585,360</td>
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
<td align="right">105,404,100</td>
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
<td align="right">221,511,263</td>
<td align="right">23.2%</td>
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
<td align="right">95,950,218</td>
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
<td align="right">16.7%</td>
</tr>
<tr>
<td align="left">TO_BOOL_BOOL</td>
<td align="right">146,037,221</td>
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
<td align="right">85,578,201</td>
<td align="right">10.1%</td>
</tr>
<tr>
<td align="left">BINARY_OP_ADD_INT</td>
<td align="right">74,869,997</td>
<td align="right">8.8%</td>
</tr>
<tr>
<td align="left">BINARY_OP_SUBTRACT_INT</td>
<td align="right">67,800,009</td>
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
<td align="right">18.8%</td>
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
<td align="right">64,819,585</td>
<td align="right">7.6%</td>
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
<td align="right">810,110,008</td>
<td align="right">63.7%</td>
</tr>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">259,034,656</td>
<td align="right">20.4%</td>
</tr>
<tr>
<td align="left">LOAD_FAST_LOAD_FAST</td>
<td align="right">94,578,803</td>
<td align="right">7.4%</td>
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
<td align="right">288,132,026</td>
<td align="right">22.7%</td>
</tr>
<tr>
<td align="left">LOAD_CONST</td>
<td align="right">151,370,492</td>
<td align="right">11.9%</td>
</tr>
<tr>
<td align="left">STORE_SLICE</td>
<td align="right">103,909,800</td>
<td align="right">8.2%</td>
</tr>
<tr>
<td align="left">BINARY_SUBSCR</td>
<td align="right">103,604,000</td>
<td align="right">8.1%</td>
</tr>
<tr>
<td align="left">BINARY_OP_MULTIPLY_INT</td>
<td align="right">95,863,620</td>
<td align="right">7.5%</td>
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
<td align="right">366,252,877</td>
<td align="right">73.6%</td>
</tr>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">70,260,043</td>
<td align="right">14.1%</td>
</tr>
<tr>
<td align="left">LOAD_FAST_LOAD_FAST</td>
<td align="right">41,826,102</td>
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
<td align="right">111,863,737</td>
<td align="right">22.5%</td>
</tr>
<tr>
<td align="left">CALL_PY_EXACT_ARGS</td>
<td align="right">93,675,400</td>
<td align="right">18.8%</td>
</tr>
<tr>
<td align="left">SWAP</td>
<td align="right">67,800,009</td>
<td align="right">13.6%</td>
</tr>
<tr>
<td align="left">BINARY_OP</td>
<td align="right">44,597,093</td>
<td align="right">9.0%</td>
</tr>
<tr>
<td align="left">RETURN_VALUE</td>
<td align="right">39,936,480</td>
<td align="right">8.0%</td>
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
<td align="right">206,056,953</td>
<td align="right">24.0%</td>
</tr>
<tr>
<td align="left">LOAD_CONST</td>
<td align="right">176,459,765</td>
<td align="right">20.5%</td>
</tr>
<tr>
<td align="left">LOAD_FAST_LOAD_FAST</td>
<td align="right">164,393,258</td>
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
<td align="right">212,223,893</td>
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
<td align="right">90,768,241</td>
<td align="right">10.6%</td>
</tr>
<tr>
<td align="left">BINARY_OP</td>
<td align="right">65,379,209</td>
<td align="right">7.6%</td>
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
<td align="right">45.6%</td>
</tr>
<tr>
<td align="left">LOAD_CONST</td>
<td align="right">333,648,811</td>
<td align="right">35.0%</td>
</tr>
<tr>
<td align="left">LOAD_FAST_LOAD_FAST</td>
<td align="right">81,322,514</td>
<td align="right">8.5%</td>
</tr>
<tr>
<td align="left">CALL_BUILTIN_FAST</td>
<td align="right">37,470,460</td>
<td align="right">3.9%</td>
</tr>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">27,584,972</td>
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
<td align="right">486,851,848</td>
<td align="right">51.1%</td>
</tr>
<tr>
<td align="left">STORE_FAST</td>
<td align="right">328,062,982</td>
<td align="right">34.4%</td>
</tr>
<tr>
<td align="left">POP_TOP</td>
<td align="right">44,973,657</td>
<td align="right">4.7%</td>
</tr>
<tr>
<td align="left">CALL_BUILTIN_FAST</td>
<td align="right">37,470,460</td>
<td align="right">3.9%</td>
</tr>
<tr>
<td align="left">RETURN_VALUE</td>
<td align="right">13,723,467</td>
<td align="right">1.4%</td>
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
<td align="right">549,709,507</td>
<td align="right">41.4%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_INSTANCE_VALUE</td>
<td align="right">172,379,861</td>
<td align="right">13.0%</td>
</tr>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">121,789,444</td>
<td align="right">9.2%</td>
</tr>
<tr>
<td align="left">LOAD_FAST_LOAD_FAST</td>
<td align="right">120,849,567</td>
<td align="right">9.1%</td>
</tr>
<tr>
<td align="left">COPY</td>
<td align="right">100,083,960</td>
<td align="right">7.5%</td>
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
<td align="right">1,104,268,706</td>
<td align="right">83.2%</td>
</tr>
<tr>
<td align="left">POP_JUMP_IF_TRUE</td>
<td align="right">111,062,677</td>
<td align="right">8.4%</td>
</tr>
<tr>
<td align="left">RETURN_VALUE</td>
<td align="right">59,838,963</td>
<td align="right">4.5%</td>
</tr>
<tr>
<td align="left">STORE_FAST</td>
<td align="right">14,567,340</td>
<td align="right">1.1%</td>
</tr>
<tr>
<td align="left">INSTRUMENTED_POP_JUMP_IF_FALSE</td>
<td align="right">14,567,100</td>
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
<td align="right">47,315,889</td>
<td align="right">17.5%</td>
</tr>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">26,430,832</td>
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
<td align="right">96,710,914</td>
<td align="right">35.8%</td>
</tr>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">89,159,180</td>
<td align="right">33.0%</td>
</tr>
<tr>
<td align="left">LOAD_FAST_LOAD_FAST</td>
<td align="right">78,883,867</td>
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
<td align="right">37,965,666</td>
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
<td align="right">37,965,666</td>
<td align="right">100.0%</td>
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
<td align="right">57,264,062</td>
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
<td align="right">57,264,062</td>
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
<td align="right">93.5%</td>
</tr>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">3,212,400</td>
<td align="right">2.8%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR</td>
<td align="right">1,424,700</td>
<td align="right">1.3%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_MODULE</td>
<td align="right">1,080,000</td>
<td align="right">1.0%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_SLOT</td>
<td align="right">831,600</td>
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
<td align="right">57,558,060</td>
<td align="right">51.0%</td>
</tr>
<tr>
<td align="left">BUILD_STRING</td>
<td align="right">50,033,400</td>
<td align="right">44.3%</td>
</tr>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">5,356,260</td>
<td align="right">4.7%</td>
</tr>
<tr>
<td align="left">LOAD_GLOBAL_MODULE</td>
<td align="right">8,820</td>
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
<td align="right">134,487,399</td>
<td align="right">58.3%</td>
</tr>
<tr>
<td align="left">COPY_FREE_VARS</td>
<td align="right">60,922,163</td>
<td align="right">26.4%</td>
</tr>
<tr>
<td align="left">CACHE</td>
<td align="right">30,371,700</td>
<td align="right">13.2%</td>
</tr>
<tr>
<td align="left">CALL_PY_WITH_DEFAULTS</td>
<td align="right">3,418,920</td>
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
<td align="right">7,138,186</td>
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
<td align="right">244,666</td>
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
<td align="right">17,282,186</td>
<td align="right">25.1%</td>
</tr>
<tr>
<td align="left">BUILD_TUPLE</td>
<td align="right">12,202,600</td>
<td align="right">17.7%</td>
</tr>
<tr>
<td align="left">STORE_FAST</td>
<td align="right">8,731,020</td>
<td align="right">12.7%</td>
</tr>
<tr>
<td align="left">SWAP</td>
<td align="right">7,992,976</td>
<td align="right">11.6%</td>
</tr>
<tr>
<td align="left">RESUME_CHECK</td>
<td align="right">4,990,755</td>
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
<td align="right">30,185,777</td>
<td align="right">43.9%</td>
</tr>
<tr>
<td align="left">STORE_FAST</td>
<td align="right">20,037,341</td>
<td align="right">29.1%</td>
</tr>
<tr>
<td align="left">SWAP</td>
<td align="right">7,992,976</td>
<td align="right">11.6%</td>
</tr>
<tr>
<td align="left">CALL_BUILTIN_FAST</td>
<td align="right">4,322,400</td>
<td align="right">6.3%</td>
</tr>
<tr>
<td align="left">CALL_FUNCTION_EX</td>
<td align="right">3,904,980</td>
<td align="right">5.7%</td>
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
<td align="right">50,033,400</td>
<td align="right">88.8%</td>
</tr>
<tr>
<td align="left">LOAD_CONST</td>
<td align="right">6,281,160</td>
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
<td align="left">CALL_BUILTIN_O</td>
<td align="right">37,276,800</td>
<td align="right">66.2%</td>
</tr>
<tr>
<td align="left">CALL</td>
<td align="right">11,581,080</td>
<td align="right">20.6%</td>
</tr>
<tr>
<td align="left">STORE_FAST</td>
<td align="right">2,944,260</td>
<td align="right">5.2%</td>
</tr>
<tr>
<td align="left">BINARY_OP_ADD_UNICODE</td>
<td align="right">2,010,960</td>
<td align="right">3.6%</td>
</tr>
<tr>
<td align="left">CALL_LIST_APPEND</td>
<td align="right">1,398,120</td>
<td align="right">2.5%</td>
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
<td align="right">96,344,374</td>
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
<td align="right">41,909,925</td>
<td align="right">43.5%</td>
</tr>
<tr>
<td align="left">STORE_FAST</td>
<td align="right">32,273,156</td>
<td align="right">33.5%</td>
</tr>
<tr>
<td align="left">POP_TOP</td>
<td align="right">7,931,101</td>
<td align="right">8.2%</td>
</tr>
<tr>
<td align="left">RETURN_VALUE</td>
<td align="right">6,120,481</td>
<td align="right">6.4%</td>
</tr>
<tr>
<td align="left">COPY_FREE_VARS</td>
<td align="right">3,418,380</td>
<td align="right">3.5%</td>
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
<td align="right">24,772,273</td>
<td align="right">98.3%</td>
</tr>
<tr>
<td align="left">LOAD_DEREF</td>
<td align="right">172,664</td>
<td align="right">0.7%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_INSTANCE_VALUE</td>
<td align="right">154,931</td>
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
<td align="right">25,192,568</td>
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
<td align="right">78,443,354</td>
<td align="right">25.5%</td>
</tr>
<tr>
<td align="left">COMPARE_OP_STR</td>
<td align="right">73,432,560</td>
<td align="right">23.9%</td>
</tr>
<tr>
<td align="left">JUMP_BACKWARD</td>
<td align="right">56,840,586</td>
<td align="right">18.5%</td>
</tr>
<tr>
<td align="left">POP_JUMP_IF_TRUE</td>
<td align="right">22,971,240</td>
<td align="right">7.5%</td>
</tr>
<tr>
<td align="left">POP_TOP</td>
<td align="right">21,604,380</td>
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
<td align="left">POP_JUMP_IF_FALSE</td>
<td align="right">102,440,803</td>
<td align="right">33.3%</td>
</tr>
<tr>
<td align="left">INSTRUMENTED_POP_JUMP_IF_FALSE</td>
<td align="right">72,839,040</td>
<td align="right">23.7%</td>
</tr>
<tr>
<td align="left">JUMP_BACKWARD</td>
<td align="right">50,908,902</td>
<td align="right">16.6%</td>
</tr>
<tr>
<td align="left">FOR_ITER_GEN</td>
<td align="right">26,083,460</td>
<td align="right">8.5%</td>
</tr>
<tr>
<td align="left">FOR_ITER</td>
<td align="right">17,546,212</td>
<td align="right">5.7%</td>
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
<td align="right">5,399,015</td>
<td align="right">87.4%</td>
</tr>
<tr>
<td align="left">STORE_FAST</td>
<td align="right">639,713</td>
<td align="right">10.4%</td>
</tr>
<tr>
<td align="left">STORE_DEREF</td>
<td align="right">136,195</td>
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
<td align="right">4,618,323</td>
<td align="right">74.8%</td>
</tr>
<tr>
<td align="left">STORE_DEREF</td>
<td align="right">1,556,600</td>
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
<td align="right">5,694,995</td>
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
<td align="right">5,399,015</td>
<td align="right">94.8%</td>
</tr>
<tr>
<td align="left">STORE_FAST</td>
<td align="right">295,980</td>
<td align="right">5.2%</td>
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
<td align="right">228,852,354</td>
<td align="right">39.2%</td>
</tr>
<tr>
<td align="left">LOAD_GLOBAL_MODULE</td>
<td align="right">156,828,621</td>
<td align="right">26.8%</td>
</tr>
<tr>
<td align="left">LOAD_FAST_LOAD_FAST</td>
<td align="right">117,712,005</td>
<td align="right">20.1%</td>
</tr>
<tr>
<td align="left">LOAD_GLOBAL_BUILTIN</td>
<td align="right">44,482,649</td>
<td align="right">7.6%</td>
</tr>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">15,961,283</td>
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
<td align="left">POP_JUMP_IF_FALSE</td>
<td align="right">492,779,034</td>
<td align="right">84.3%</td>
</tr>
<tr>
<td align="left">POP_JUMP_IF_TRUE</td>
<td align="right">49,450,940</td>
<td align="right">8.5%</td>
</tr>
<tr>
<td align="left">EXTENDED_ARG</td>
<td align="right">18,016,440</td>
<td align="right">3.1%</td>
</tr>
<tr>
<td align="left">STORE_FAST</td>
<td align="right">12,056,260</td>
<td align="right">2.1%</td>
</tr>
<tr>
<td align="left">YIELD_VALUE</td>
<td align="right">9,422,903</td>
<td align="right">1.6%</td>
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
<td align="right">19,828,109</td>
<td align="right">56.1%</td>
</tr>
<tr>
<td align="left">LOAD_FAST_AND_CLEAR</td>
<td align="right">15,516,376</td>
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
<td align="right">19,828,109</td>
<td align="right">56.1%</td>
</tr>
<tr>
<td align="left">LOAD_FAST_AND_CLEAR</td>
<td align="right">15,516,376</td>
<td align="right">43.9%</td>
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
<td align="right">36.7%</td>
</tr>
<tr>
<td align="left">POP_JUMP_IF_NONE</td>
<td align="right">1,136,554</td>
<td align="right">34.3%</td>
</tr>
<tr>
<td align="left">POP_TOP</td>
<td align="right">483,840</td>
<td align="right">14.6%</td>
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
<td align="right">35.1%</td>
</tr>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">1,049,100</td>
<td align="right">31.7%</td>
</tr>
<tr>
<td align="left">UNPACK_SEQUENCE_TWO_TUPLE</td>
<td align="right">480,000</td>
<td align="right">14.5%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_METHOD_NO_DICT</td>
<td align="right">219,580</td>
<td align="right">6.6%</td>
</tr>
<tr>
<td align="left">LOAD_GLOBAL_MODULE</td>
<td align="right">99,054</td>
<td align="right">3.0%</td>
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
<td align="right">5,845,132</td>
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
<td align="right">14,571,292</td>
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
<td align="right">308,922,927</td>
<td align="right">28.5%</td>
</tr>
<tr>
<td align="left">POP_TOP</td>
<td align="right">155,282,448</td>
<td align="right">14.3%</td>
</tr>
<tr>
<td align="left">STORE_ATTR_SLOT</td>
<td align="right">142,186,590</td>
<td align="right">13.1%</td>
</tr>
<tr>
<td align="left">STORE_ATTR_INSTANCE_VALUE</td>
<td align="right">129,367,320</td>
<td align="right">11.9%</td>
</tr>
<tr>
<td align="left">FOR_ITER_LIST</td>
<td align="right">95,692,989</td>
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
<td align="right">470,916,241</td>
<td align="right">43.4%</td>
</tr>
<tr>
<td align="left">INTERPRETER_EXIT</td>
<td align="right">352,450,953</td>
<td align="right">32.5%</td>
</tr>
<tr>
<td align="left">EXIT_INIT_CHECK</td>
<td align="right">57,264,062</td>
<td align="right">5.3%</td>
</tr>
<tr>
<td align="left">TO_BOOL_BOOL</td>
<td align="right">53,101,722</td>
<td align="right">4.9%</td>
</tr>
<tr>
<td align="left">END_FOR</td>
<td align="right">37,965,666</td>
<td align="right">3.5%</td>
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
<td align="right">56.6%</td>
</tr>
<tr>
<td align="left">FOR_ITER_LIST</td>
<td align="right">20,511,588</td>
<td align="right">32.9%</td>
</tr>
<tr>
<td align="left">FOR_ITER_TUPLE</td>
<td align="right">3,779,474</td>
<td align="right">6.1%</td>
</tr>
<tr>
<td align="left">FOR_ITER</td>
<td align="right">1,473,240</td>
<td align="right">2.4%</td>
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
<td align="right">21,989,864</td>
<td align="right">35.3%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_METHOD_WITH_VALUES</td>
<td align="right">14,643,000</td>
<td align="right">23.5%</td>
</tr>
<tr>
<td align="left">POP_JUMP_IF_NOT_NONE</td>
<td align="right">8,870,340</td>
<td align="right">14.2%</td>
</tr>
<tr>
<td align="left">YIELD_VALUE</td>
<td align="right">4,806,720</td>
<td align="right">7.7%</td>
</tr>
<tr>
<td align="left">PUSH_NULL</td>
<td align="right">3,160,920</td>
<td align="right">5.1%</td>
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
<td align="right">383,256,356</td>
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
<td align="right">69,240,714</td>
<td align="right">7.2%</td>
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
<td align="right">468,254,785</td>
<td align="right">48.9%</td>
</tr>
<tr>
<td align="left">YIELD_VALUE</td>
<td align="right">383,256,356</td>
<td align="right">40.0%</td>
</tr>
<tr>
<td align="left">STORE_FAST</td>
<td align="right">78,361,554</td>
<td align="right">8.2%</td>
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
<td align="right">4,265</td>
<td align="right">73.6%</td>
</tr>
<tr>
<td align="left">INSTRUMENTED_RESUME</td>
<td align="right">960</td>
<td align="right">16.6%</td>
</tr>
<tr>
<td align="left">CALL_PY_EXACT_ARGS</td>
<td align="right">380</td>
<td align="right">6.6%</td>
</tr>
<tr>
<td align="left">CALL_FUNCTION_EX</td>
<td align="right">60</td>
<td align="right">1.0%</td>
</tr>
<tr>
<td align="left">COPY_FREE_VARS</td>
<td align="right">60</td>
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
<td align="left">RETURN_CONST</td>
<td align="right">3,420</td>
<td align="right">59.0%</td>
</tr>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">671</td>
<td align="right">11.6%</td>
</tr>
<tr>
<td align="left">LOAD_CONST</td>
<td align="right">489</td>
<td align="right">8.4%</td>
</tr>
<tr>
<td align="left">LOAD_GLOBAL</td>
<td align="right">485</td>
<td align="right">8.4%</td>
</tr>
<tr>
<td align="left">LOAD_NAME</td>
<td align="right">360</td>
<td align="right">6.2%</td>
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
<td align="right">60.5%</td>
</tr>
<tr>
<td align="left">LOAD_CONST</td>
<td align="right">10,746,980</td>
<td align="right">18.2%</td>
</tr>
<tr>
<td align="left">CALL_STR_1</td>
<td align="right">4,804,960</td>
<td align="right">8.1%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES</td>
<td align="right">2,460,900</td>
<td align="right">4.2%</td>
</tr>
<tr>
<td align="left">BUILD_STRING</td>
<td align="right">2,010,960</td>
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
<td align="left">CALL_BUILTIN_O</td>
<td align="right">19,572,000</td>
<td align="right">33.1%</td>
</tr>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">14,209,320</td>
<td align="right">24.0%</td>
</tr>
<tr>
<td align="left">LOAD_CONST</td>
<td align="right">10,514,160</td>
<td align="right">17.8%</td>
</tr>
<tr>
<td align="left">STORE_FAST</td>
<td align="right">6,583,080</td>
<td align="right">11.1%</td>
</tr>
<tr>
<td align="left">SWAP</td>
<td align="right">2,963,340</td>
<td align="right">5.0%</td>
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
<td align="right">6,111,544</td>
<td align="right">5.7%</td>
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
<td align="right">108,129,820</td>
<td align="right">100.0%</td>
</tr>
<tr>
<td align="left">MAKE_CELL</td>
<td align="right">11,044</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_METHOD_NO_DICT</td>
<td align="right">6,000</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">2,040</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">CONTAINS_OP</td>
<td align="right">1,220</td>
<td align="right">0.0%</td>
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
<td align="right">188,658,663</td>
<td align="right">82.6%</td>
</tr>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">39,862,320</td>
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
<td align="left">CALL</td>
<td align="right">72,000,020</td>
<td align="right">31.5%</td>
</tr>
<tr>
<td align="left">LOAD_GLOBAL_MODULE</td>
<td align="right">30,804,020</td>
<td align="right">13.5%</td>
</tr>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">25,831,235</td>
<td align="right">11.3%</td>
</tr>
<tr>
<td align="left">LOAD_CONST</td>
<td align="right">24,429,064</td>
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
<td align="right">55,939,982</td>
<td align="right">94.9%</td>
</tr>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">1,661,020</td>
<td align="right">2.8%</td>
</tr>
<tr>
<td align="left">COPY_FREE_VARS</td>
<td align="right">1,324,080</td>
<td align="right">2.2%</td>
</tr>
<tr>
<td align="left">CALL_ALLOC_AND_ENTER_INIT</td>
<td align="right">32,240</td>
<td align="right">0.1%</td>
</tr>
<tr>
<td align="left">STORE_FAST</td>
<td align="right">15,640</td>
<td align="right">0.0%</td>
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
<td align="left">LOAD_CONST</td>
<td align="right">41,547,140</td>
<td align="right">32.0%</td>
</tr>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">29,816,041</td>
<td align="right">23.0%</td>
</tr>
<tr>
<td align="left">BINARY_OP_MULTIPLY_INT</td>
<td align="right">22,513,860</td>
<td align="right">17.4%</td>
</tr>
<tr>
<td align="left">BINARY_OP_ADD_INT</td>
<td align="right">6,878,167</td>
<td align="right">5.3%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_INSTANCE_VALUE</td>
<td align="right">6,495,520</td>
<td align="right">5.0%</td>
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
<td align="right">101,728,956</td>
<td align="right">78.4%</td>
</tr>
<tr>
<td align="left">COPY_FREE_VARS</td>
<td align="right">27,104,114</td>
<td align="right">20.9%</td>
</tr>
<tr>
<td align="left">MAKE_CELL</td>
<td align="right">662,441</td>
<td align="right">0.5%</td>
</tr>
<tr>
<td align="left">CALL_PY_EXACT_ARGS</td>
<td align="right">159,221</td>
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
<td align="right">50.1%</td>
</tr>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">20,790,532</td>
<td align="right">21.6%</td>
</tr>
<tr>
<td align="left">LOAD_FAST_LOAD_FAST</td>
<td align="right">6,374,040</td>
<td align="right">6.6%</td>
</tr>
<tr>
<td align="left">CALL_METHOD_DESCRIPTOR_NOARGS</td>
<td align="right">5,629,816</td>
<td align="right">5.8%</td>
</tr>
<tr>
<td align="left">CALL_BUILTIN_FAST_WITH_KEYWORDS</td>
<td align="right">5,069,700</td>
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
<td align="left">LOAD_DEREF</td>
<td align="right">46,765,320</td>
<td align="right">48.6%</td>
</tr>
<tr>
<td align="left">STORE_FAST</td>
<td align="right">18,942,612</td>
<td align="right">19.7%</td>
</tr>
<tr>
<td align="left">POP_TOP</td>
<td align="right">8,497,590</td>
<td align="right">8.8%</td>
</tr>
<tr>
<td align="left">RETURN_VALUE</td>
<td align="right">7,765,394</td>
<td align="right">8.1%</td>
</tr>
<tr>
<td align="left">CALL_BUILTIN_FAST_WITH_KEYWORDS</td>
<td align="right">5,069,700</td>
<td align="right">5.3%</td>
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
<td align="right">580,435,736</td>
<td align="right">68.5%</td>
</tr>
<tr>
<td align="left">LOAD_CONST</td>
<td align="right">87,419,880</td>
<td align="right">10.3%</td>
</tr>
<tr>
<td align="left">RETURN_VALUE</td>
<td align="right">55,933,140</td>
<td align="right">6.6%</td>
</tr>
<tr>
<td align="left">BUILD_STRING</td>
<td align="right">37,276,800</td>
<td align="right">4.4%</td>
</tr>
<tr>
<td align="left">BINARY_OP_ADD_UNICODE</td>
<td align="right">19,572,000</td>
<td align="right">2.3%</td>
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
<td align="right">394,656,180</td>
<td align="right">46.6%</td>
</tr>
<tr>
<td align="left">STORE_FAST</td>
<td align="right">176,212,888</td>
<td align="right">20.8%</td>
</tr>
<tr>
<td align="left">LOAD_CONST</td>
<td align="right">171,659,379</td>
<td align="right">20.3%</td>
</tr>
<tr>
<td align="left">RETURN_VALUE</td>
<td align="right">27,881,202</td>
<td align="right">3.3%</td>
</tr>
<tr>
<td align="left">STORE_SUBSCR_DICT</td>
<td align="right">13,999,260</td>
<td align="right">1.7%</td>
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
<td align="right">201,185,344</td>
<td align="right">73.3%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_INSTANCE_VALUE</td>
<td align="right">34,223,236</td>
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
<td align="right">113,622,276</td>
<td align="right">41.4%</td>
</tr>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">40,642,380</td>
<td align="right">14.8%</td>
</tr>
<tr>
<td align="left">COMPARE_OP_INT</td>
<td align="right">35,514,516</td>
<td align="right">12.9%</td>
</tr>
<tr>
<td align="left">STORE_FAST</td>
<td align="right">35,425,551</td>
<td align="right">12.9%</td>
</tr>
<tr>
<td align="left">LOAD_GLOBAL_BUILTIN</td>
<td align="right">9,755,118</td>
<td align="right">3.6%</td>
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
<td align="right">93,997,725</td>
<td align="right">58.2%</td>
</tr>
<tr>
<td align="left">BINARY_SUBSCR</td>
<td align="right">20,171,040</td>
<td align="right">12.5%</td>
</tr>
<tr>
<td align="left">BINARY_SLICE</td>
<td align="right">19,300,980</td>
<td align="right">11.9%</td>
</tr>
<tr>
<td align="left">BINARY_OP</td>
<td align="right">8,543,680</td>
<td align="right">5.3%</td>
</tr>
<tr>
<td align="left">BINARY_SUBSCR_TUPLE_INT</td>
<td align="right">5,132,580</td>
<td align="right">3.2%</td>
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
<td align="right">92,522,988</td>
<td align="right">57.3%</td>
</tr>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">28,023,292</td>
<td align="right">17.3%</td>
</tr>
<tr>
<td align="left">RETURN_CONST</td>
<td align="right">20,033,520</td>
<td align="right">12.4%</td>
</tr>
<tr>
<td align="left">NOP</td>
<td align="right">5,490,169</td>
<td align="right">3.4%</td>
</tr>
<tr>
<td align="left">EXTENDED_ARG</td>
<td align="right">3,497,159</td>
<td align="right">2.2%</td>
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
<td align="right">142,590</td>
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
<td align="right">59,235,610</td>
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
<td align="right">160,121,673</td>
<td align="right">64.7%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_METHOD_LAZY_DICT</td>
<td align="right">66,378,638</td>
<td align="right">26.8%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR</td>
<td align="right">17,258,636</td>
<td align="right">7.0%</td>
</tr>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">3,129,180</td>
<td align="right">1.3%</td>
</tr>
<tr>
<td align="left">CALL_METHOD_DESCRIPTOR_NOARGS</td>
<td align="right">410,164</td>
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
<td align="right">78,128,635</td>
<td align="right">31.6%</td>
</tr>
<tr>
<td align="left">TO_BOOL_BOOL</td>
<td align="right">58,930,758</td>
<td align="right">23.8%</td>
</tr>
<tr>
<td align="left">GET_ITER</td>
<td align="right">43,266,726</td>
<td align="right">17.5%</td>
</tr>
<tr>
<td align="left">LOAD_GLOBAL_MODULE</td>
<td align="right">18,631,740</td>
<td align="right">7.5%</td>
</tr>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">12,104,221</td>
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
<td align="right">190,844,148</td>
<td align="right">81.6%</td>
</tr>
<tr>
<td align="left">CALL</td>
<td align="right">19,489,731</td>
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
<td align="right">127,894,639</td>
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
<td align="right">3,487,736</td>
<td align="right">32.2%</td>
</tr>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">1,136,975</td>
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
<td align="right">3,490,756</td>
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
<td align="right">945,068</td>
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
<td align="right">149,531,944</td>
<td align="right">77.5%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_INSTANCE_VALUE</td>
<td align="right">17,050,440</td>
<td align="right">8.8%</td>
</tr>
<tr>
<td align="left">LOAD_GLOBAL_MODULE</td>
<td align="right">8,632,405</td>
<td align="right">4.5%</td>
</tr>
<tr>
<td align="left">LOAD_FAST_LOAD_FAST</td>
<td align="right">7,753,340</td>
<td align="right">4.0%</td>
</tr>
<tr>
<td align="left">RETURN_VALUE</td>
<td align="right">3,333,300</td>
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
<td align="left">EXTENDED_ARG</td>
<td align="right">73,432,560</td>
<td align="right">38.1%</td>
</tr>
<tr>
<td align="left">POP_JUMP_IF_FALSE</td>
<td align="right">43,867,590</td>
<td align="right">22.7%</td>
</tr>
<tr>
<td align="left">INSTRUMENTED_POP_JUMP_IF_FALSE</td>
<td align="right">43,710,360</td>
<td align="right">22.7%</td>
</tr>
<tr>
<td align="left">INSTRUMENTED_POP_JUMP_IF_TRUE</td>
<td align="right">14,567,580</td>
<td align="right">7.5%</td>
</tr>
<tr>
<td align="left">COPY</td>
<td align="right">7,480,740</td>
<td align="right">3.9%</td>
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
<td align="right">126,413,681</td>
<td align="right">62.5%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_INSTANCE_VALUE</td>
<td align="right">30,933,587</td>
<td align="right">15.3%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR</td>
<td align="right">15,982,402</td>
<td align="right">7.9%</td>
</tr>
<tr>
<td align="left">LOAD_DEREF</td>
<td align="right">11,065,080</td>
<td align="right">5.5%</td>
</tr>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">5,733,140</td>
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
<td align="right">145,031,377</td>
<td align="right">71.7%</td>
</tr>
<tr>
<td align="left">POP_JUMP_IF_TRUE</td>
<td align="right">54,576,605</td>
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
<td align="right">4,366,719</td>
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
<td align="right">294,730,859</td>
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
<td align="right">80,839,672</td>
<td align="right">55.9%</td>
</tr>
<tr>
<td align="left">GET_ITER</td>
<td align="right">37,635,148</td>
<td align="right">26.0%</td>
</tr>
<tr>
<td align="left">EXTENDED_ARG</td>
<td align="right">26,083,460</td>
<td align="right">18.0%</td>
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
<td align="right">106,552,232</td>
<td align="right">73.7%</td>
</tr>
<tr>
<td align="left">POP_TOP</td>
<td align="right">38,046,328</td>
<td align="right">26.3%</td>
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
<td align="right">193,693,055</td>
<td align="right">72.2%</td>
</tr>
<tr>
<td align="left">GET_ITER</td>
<td align="right">69,523,885</td>
<td align="right">25.9%</td>
</tr>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">1,436,203</td>
<td align="right">0.5%</td>
</tr>
<tr>
<td align="left">EXTENDED_ARG</td>
<td align="right">1,384,380</td>
<td align="right">0.5%</td>
</tr>
<tr>
<td align="left">FOR_ITER_LIST</td>
<td align="right">1,210,917</td>
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
<td align="right">191,506,833</td>
<td align="right">71.4%</td>
</tr>
<tr>
<td align="left">LOAD_FAST_LOAD_FAST</td>
<td align="right">41,376,560</td>
<td align="right">15.4%</td>
</tr>
<tr>
<td align="left">RETURN_CONST</td>
<td align="right">12,444,800</td>
<td align="right">4.6%</td>
</tr>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">11,740,615</td>
<td align="right">4.4%</td>
</tr>
<tr>
<td align="left">STORE_FAST_LOAD_FAST</td>
<td align="right">3,779,474</td>
<td align="right">1.4%</td>
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
<td align="right">90,474,428</td>
<td align="right">84.4%</td>
</tr>
<tr>
<td align="left">LOAD_GLOBAL_BUILTIN</td>
<td align="right">15,498,240</td>
<td align="right">14.5%</td>
</tr>
<tr>
<td align="left">LOAD_FAST_LOAD_FAST</td>
<td align="right">591,660</td>
<td align="right">0.6%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_MODULE</td>
<td align="right">361,960</td>
<td align="right">0.3%</td>
</tr>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">262,220</td>
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
<td align="left">COMPARE_OP_INT</td>
<td align="right">57,033,600</td>
<td align="right">53.2%</td>
</tr>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">22,046,198</td>
<td align="right">20.6%</td>
</tr>
<tr>
<td align="left">LOAD_FAST_LOAD_FAST</td>
<td align="right">15,652,200</td>
<td align="right">14.6%</td>
</tr>
<tr>
<td align="left">PUSH_NULL</td>
<td align="right">8,282,760</td>
<td align="right">7.7%</td>
</tr>
<tr>
<td align="left">TO_BOOL_BOOL</td>
<td align="right">1,698,720</td>
<td align="right">1.6%</td>
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
<td align="right">3,215,991,965</td>
<td align="right">87.6%</td>
</tr>
<tr>
<td align="left">LOAD_FAST_LOAD_FAST</td>
<td align="right">298,581,909</td>
<td align="right">8.1%</td>
</tr>
<tr>
<td align="left">COPY</td>
<td align="right">64,819,585</td>
<td align="right">1.8%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_INSTANCE_VALUE</td>
<td align="right">54,045,145</td>
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
<td align="right">1,054,650,054</td>
<td align="right">28.7%</td>
</tr>
<tr>
<td align="left">TO_BOOL_BOOL</td>
<td align="right">554,765,397</td>
<td align="right">15.1%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_METHOD_NO_DICT</td>
<td align="right">213,762,099</td>
<td align="right">5.8%</td>
</tr>
<tr>
<td align="left">COMPARE_OP_INT</td>
<td align="right">172,379,861</td>
<td align="right">4.7%</td>
</tr>
<tr>
<td align="left">RETURN_VALUE</td>
<td align="right">129,007,495</td>
<td align="right">3.5%</td>
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
<td align="right">138,128,900</td>
<td align="right">77.9%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_INSTANCE_VALUE</td>
<td align="right">38,037,540</td>
<td align="right">21.5%</td>
</tr>
<tr>
<td align="left">LOAD_DEREF</td>
<td align="right">845,805</td>
<td align="right">0.5%</td>
</tr>
<tr>
<td align="left">CALL</td>
<td align="right">114,240</td>
<td align="right">0.1%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_METHOD_LAZY_DICT</td>
<td align="right">71,669</td>
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
<td align="right">66,378,638</td>
<td align="right">37.5%</td>
</tr>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">65,460,146</td>
<td align="right">36.9%</td>
</tr>
<tr>
<td align="left">CALL</td>
<td align="right">27,296,978</td>
<td align="right">15.4%</td>
</tr>
<tr>
<td align="left">LOAD_CONST</td>
<td align="right">8,150,131</td>
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
<td align="right">1,538,779,346</td>
<td align="right">89.8%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_INSTANCE_VALUE</td>
<td align="right">56,426,811</td>
<td align="right">3.3%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_SLOT</td>
<td align="right">44,294,110</td>
<td align="right">2.6%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_WITH_HINT</td>
<td align="right">23,298,672</td>
<td align="right">1.4%</td>
</tr>
<tr>
<td align="left">LOAD_FAST_LOAD_FAST</td>
<td align="right">15,182,347</td>
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
<td align="right">721,055,155</td>
<td align="right">42.1%</td>
</tr>
<tr>
<td align="left">LOAD_FAST_LOAD_FAST</td>
<td align="right">446,210,924</td>
<td align="right">26.0%</td>
</tr>
<tr>
<td align="left">CALL_PY_EXACT_ARGS</td>
<td align="right">388,523,590</td>
<td align="right">22.7%</td>
</tr>
<tr>
<td align="left">LOAD_GLOBAL_MODULE</td>
<td align="right">89,991,467</td>
<td align="right">5.2%</td>
</tr>
<tr>
<td align="left">LOAD_CONST</td>
<td align="right">45,383,348</td>
<td align="right">2.6%</td>
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
<td align="right">147,709,707</td>
<td align="right">89.2%</td>
</tr>
<tr>
<td align="left">LOAD_FAST_LOAD_FAST</td>
<td align="right">16,620,462</td>
<td align="right">10.0%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES</td>
<td align="right">757,300</td>
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
<td align="right">27,400,907</td>
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
<td align="right">8,935,380</td>
<td align="right">5.4%</td>
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
<td align="right">43,281,964</td>
<td align="right">89.9%</td>
</tr>
<tr>
<td align="left">RETURN_VALUE</td>
<td align="right">2,952,362</td>
<td align="right">6.1%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_INSTANCE_VALUE</td>
<td align="right">743,200</td>
<td align="right">1.5%</td>
</tr>
<tr>
<td align="left">BINARY_SUBSCR</td>
<td align="right">398,520</td>
<td align="right">0.8%</td>
</tr>
<tr>
<td align="left">STORE_FAST_LOAD_FAST</td>
<td align="right">235,866</td>
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
<td align="right">37,094,336</td>
<td align="right">77.1%</td>
</tr>
<tr>
<td align="left">COPY_FREE_VARS</td>
<td align="right">3,870,862</td>
<td align="right">8.0%</td>
</tr>
<tr>
<td align="left">TO_BOOL_NONE</td>
<td align="right">3,291,522</td>
<td align="right">6.8%</td>
</tr>
<tr>
<td align="left">GET_ITER</td>
<td align="right">1,435,955</td>
<td align="right">3.0%</td>
</tr>
<tr>
<td align="left">TO_BOOL_BOOL</td>
<td align="right">533,511</td>
<td align="right">1.1%</td>
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
<td align="right">940,860,473</td>
<td align="right">86.4%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR</td>
<td align="right">80,213,818</td>
<td align="right">7.4%</td>
</tr>
<tr>
<td align="left">COPY</td>
<td align="right">40,131,480</td>
<td align="right">3.7%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_SLOT</td>
<td align="right">14,973,658</td>
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
<td align="right">277,441,954</td>
<td align="right">25.5%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR</td>
<td align="right">83,426,669</td>
<td align="right">7.7%</td>
</tr>
<tr>
<td align="left">TO_BOOL_NONE</td>
<td align="right">75,190,460</td>
<td align="right">6.9%</td>
</tr>
<tr>
<td align="left">COMPARE_OP_FLOAT</td>
<td align="right">65,985,463</td>
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
<td align="right">2,360,931</td>
<td align="right">97.6%</td>
</tr>
<tr>
<td align="left">LOAD_DEREF</td>
<td align="right">58,020</td>
<td align="right">2.4%</td>
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
<td align="right">2,355,971</td>
<td align="right">97.4%</td>
</tr>
<tr>
<td align="left">LOAD_GLOBAL_MODULE</td>
<td align="right">63,000</td>
<td align="right">2.6%</td>
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
<td align="right">43,428,881</td>
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
<td align="right">76.3%</td>
</tr>
<tr>
<td align="left">CALL_PY_EXACT_ARGS</td>
<td align="right">4,791,115</td>
<td align="right">11.0%</td>
</tr>
<tr>
<td align="left">LOAD_FAST_LOAD_FAST</td>
<td align="right">4,180,667</td>
<td align="right">9.6%</td>
</tr>
<tr>
<td align="left">CALL</td>
<td align="right">1,195,300</td>
<td align="right">2.8%</td>
</tr>
<tr>
<td align="left">LOAD_GLOBAL_MODULE</td>
<td align="right">104,359</td>
<td align="right">0.2%</td>
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
<td align="right">316,692,490</td>
<td align="right">46.1%</td>
</tr>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">276,209,755</td>
<td align="right">40.2%</td>
</tr>
<tr>
<td align="left">SWAP</td>
<td align="right">64,819,585</td>
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
<td align="right">317,845,858</td>
<td align="right">46.2%</td>
</tr>
<tr>
<td align="left">RETURN_CONST</td>
<td align="right">129,367,320</td>
<td align="right">18.8%</td>
</tr>
<tr>
<td align="left">LOAD_FAST_LOAD_FAST</td>
<td align="right">128,259,173</td>
<td align="right">18.7%</td>
</tr>
<tr>
<td align="left">LOAD_CONST</td>
<td align="right">38,231,858</td>
<td align="right">5.6%</td>
</tr>
<tr>
<td align="left">NOP</td>
<td align="right">25,256,610</td>
<td align="right">3.7%</td>
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
<td align="right">287,871,095</td>
<td align="right">52.2%</td>
</tr>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">223,006,127</td>
<td align="right">40.5%</td>
</tr>
<tr>
<td align="left">SWAP</td>
<td align="right">40,131,480</td>
<td align="right">7.3%</td>
</tr>
<tr>
<td align="left">STORE_ATTR_SLOT</td>
<td align="right">269,326</td>
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
<td align="right">166,710,969</td>
<td align="right">30.2%</td>
</tr>
<tr>
<td align="left">LOAD_FAST_LOAD_FAST</td>
<td align="right">144,375,256</td>
<td align="right">26.2%</td>
</tr>
<tr>
<td align="left">RETURN_CONST</td>
<td align="right">142,186,590</td>
<td align="right">25.8%</td>
</tr>
<tr>
<td align="left">LOAD_CONST</td>
<td align="right">87,693,193</td>
<td align="right">15.9%</td>
</tr>
<tr>
<td align="left">STORE_FAST</td>
<td align="right">6,000,000</td>
<td align="right">1.1%</td>
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
<td align="right">89,951,501</td>
<td align="right">51.7%</td>
</tr>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">44,909,013</td>
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
<td align="right">72,921,491</td>
<td align="right">41.9%</td>
</tr>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">45,776,631</td>
<td align="right">26.3%</td>
</tr>
<tr>
<td align="left">JUMP_BACKWARD</td>
<td align="right">28,579,141</td>
<td align="right">16.4%</td>
</tr>
<tr>
<td align="left">RETURN_CONST</td>
<td align="right">15,346,811</td>
<td align="right">8.8%</td>
</tr>
<tr>
<td align="left">LOAD_GLOBAL_MODULE</td>
<td align="right">7,348,072</td>
<td align="right">4.2%</td>
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
<td align="right">23,806,505</td>
<td align="right">20.8%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_SLOT</td>
<td align="right">13,422,560</td>
<td align="right">11.7%</td>
</tr>
<tr>
<td align="left">COPY</td>
<td align="right">6,550,625</td>
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
<td align="right">86,226,654</td>
<td align="right">75.5%</td>
</tr>
<tr>
<td align="left">POP_JUMP_IF_TRUE</td>
<td align="right">27,371,720</td>
<td align="right">24.0%</td>
</tr>
<tr>
<td align="left">TO_BOOL_NONE</td>
<td align="right">366,160</td>
<td align="right">0.3%</td>
</tr>
<tr>
<td align="left">EXTENDED_ARG</td>
<td align="right">161,460</td>
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
<td align="right">54,510,042</td>
<td align="right">63.0%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_INSTANCE_VALUE</td>
<td align="right">29,414,296</td>
<td align="right">34.0%</td>
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
<td align="right">298,160</td>
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
<td align="right">55,574,930</td>
<td align="right">64.2%</td>
</tr>
<tr>
<td align="left">POP_JUMP_IF_TRUE</td>
<td align="right">29,425,751</td>
<td align="right">34.0%</td>
</tr>
<tr>
<td align="left">UNARY_NOT</td>
<td align="right">1,234,762</td>
<td align="right">1.4%</td>
</tr>
<tr>
<td align="left">EXTENDED_ARG</td>
<td align="right">306,480</td>
<td align="right">0.4%</td>
</tr>
<tr>
<td align="left">TO_BOOL</td>
<td align="right">19,940</td>
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
<td align="right">124,789,481</td>
<td align="right">36.3%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_INSTANCE_VALUE</td>
<td align="right">87,706,660</td>
<td align="right">25.5%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_SLOT</td>
<td align="right">75,190,460</td>
<td align="right">21.9%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR</td>
<td align="right">23,659,200</td>
<td align="right">6.9%</td>
</tr>
<tr>
<td align="left">RETURN_CONST</td>
<td align="right">13,893,440</td>
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
<td align="right">299,282,883</td>
<td align="right">87.1%</td>
</tr>
<tr>
<td align="left">POP_JUMP_IF_TRUE</td>
<td align="right">28,818,021</td>
<td align="right">8.4%</td>
</tr>
<tr>
<td align="left">INSTRUMENTED_POP_JUMP_IF_FALSE</td>
<td align="right">14,568,120</td>
<td align="right">4.2%</td>
</tr>
<tr>
<td align="left">EXTENDED_ARG</td>
<td align="right">453,780</td>
<td align="right">0.1%</td>
</tr>
<tr>
<td align="left">TO_BOOL_ALWAYS_TRUE</td>
<td align="right">366,220</td>
<td align="right">0.1%</td>
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
<td align="right">41,906,551</td>
<td align="right">72.1%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_SLOT</td>
<td align="right">6,813,060</td>
<td align="right">11.7%</td>
</tr>
<tr>
<td align="left">CALL_METHOD_DESCRIPTOR_FAST</td>
<td align="right">3,814,380</td>
<td align="right">6.6%</td>
</tr>
<tr>
<td align="left">LOAD_GLOBAL_MODULE</td>
<td align="right">2,457,600</td>
<td align="right">4.2%</td>
</tr>
<tr>
<td align="left">COPY</td>
<td align="right">1,536,231</td>
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
<td align="left">POP_JUMP_IF_TRUE</td>
<td align="right">29,777,251</td>
<td align="right">51.3%</td>
</tr>
<tr>
<td align="left">POP_JUMP_IF_FALSE</td>
<td align="right">27,933,331</td>
<td align="right">48.1%</td>
</tr>
<tr>
<td align="left">UNARY_NOT</td>
<td align="right">323,040</td>
<td align="right">0.6%</td>
</tr>
<tr>
<td align="left">TO_BOOL_NONE</td>
<td align="right">32,940</td>
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
<td align="right">196,797,742</td>
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
<td align="right">221,203,222</td>
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
<td align="right">6,049,068</td>
<td align="right">94.0%</td>
</tr>
<tr>
<td align="left">CALL</td>
<td align="right">220,035</td>
<td align="right">3.4%</td>
</tr>
<tr>
<td align="left">RETURN_VALUE</td>
<td align="right">88,760</td>
<td align="right">1.4%</td>
</tr>
<tr>
<td align="left">LOAD_GLOBAL_MODULE</td>
<td align="right">75,382</td>
<td align="right">1.2%</td>
</tr>
<tr>
<td align="left">CALL_KW</td>
<td align="right">540</td>
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
<td align="left">POP_TOP</td>
<td align="right">6,209,210</td>
<td align="right">96.5%</td>
</tr>
<tr>
<td align="left">STORE_FAST</td>
<td align="right">222,955</td>
<td align="right">3.5%</td>
</tr>
<tr>
<td align="left">UNPACK_SEQUENCE_TWO_TUPLE</td>
<td align="right">1,680</td>
<td align="right">0.0%</td>
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
<td align="right">44,982,666</td>
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
<td align="right">62,292,766</td>
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
<td align="right">46,655,031</td>
<td align="right">83.6%</td>
</tr>
<tr>
<td align="left">RETURN_VALUE</td>
<td align="right">6,534,820</td>
<td align="right">11.7%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_INSTANCE_VALUE</td>
<td align="right">2,457,600</td>
<td align="right">4.4%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_SLOT</td>
<td align="right">109,200</td>
<td align="right">0.2%</td>
</tr>
<tr>
<td align="left">CALL</td>
<td align="right">25,580</td>
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
<td align="right">11,359,331</td>
<td align="right">20.4%</td>
</tr>
<tr>
<td align="left">CALL_BUILTIN_O</td>
<td align="right">10,853,040</td>
<td align="right">19.4%</td>
</tr>
<tr>
<td align="left">CALL_PY_EXACT_ARGS</td>
<td align="right">10,848,480</td>
<td align="right">19.4%</td>
</tr>
<tr>
<td align="left">YIELD_VALUE</td>
<td align="right">7,683,360</td>
<td align="right">13.8%</td>
</tr>
<tr>
<td align="left">BINARY_OP_ADD_UNICODE</td>
<td align="right">4,804,960</td>
<td align="right">8.6%</td>
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
<td align="right">240,521,742</td>
<td align="right">45.9%</td>
</tr>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">201,550,948</td>
<td align="right">38.5%</td>
</tr>
<tr>
<td align="left">YIELD_VALUE</td>
<td align="right">24,808,480</td>
<td align="right">4.7%</td>
</tr>
<tr>
<td align="left">BINARY_SUBSCR_DICT</td>
<td align="right">14,268,900</td>
<td align="right">2.7%</td>
</tr>
<tr>
<td align="left">STORE_FAST</td>
<td align="right">12,060,960</td>
<td align="right">2.3%</td>
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
<td align="right">255,982,064</td>
<td align="right">48.9%</td>
</tr>
<tr>
<td align="left">STORE_FAST</td>
<td align="right">243,802,974</td>
<td align="right">46.5%</td>
</tr>
<tr>
<td align="left">UNPACK_SEQUENCE_LIST</td>
<td align="right">24,026,440</td>
<td align="right">4.6%</td>
</tr>
<tr>
<td align="left">UNPACK_SEQUENCE_TWO_TUPLE</td>
<td align="right">29,880</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">9,600</td>
<td align="right">0.0%</td>
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
<td align="right">36,222,540</td>
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
<td align="right">47,425,140</td>
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
<td align="right">73,815,500</td>
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
<td align="right">66,943,378</td>
<td align="right">90.7%</td>
</tr>
<tr>
<td align="left">LOAD_GLOBAL_MODULE</td>
<td align="right">2,498,700</td>
<td align="right">3.4%</td>
</tr>
<tr>
<td align="left">LOAD_GLOBAL_BUILTIN</td>
<td align="right">1,949,608</td>
<td align="right">2.6%</td>
</tr>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">1,561,053</td>
<td align="right">2.1%</td>
</tr>
<tr>
<td align="left">STORE_FAST</td>
<td align="right">513,143</td>
<td align="right">0.7%</td>
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
<td align="right">9,911,747</td>
<td align="right">96.3%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES</td>
<td align="right">222,962</td>
<td align="right">2.2%</td>
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
<td align="right">10,292,989</td>
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
<td align="right">21,427,131</td>
<td align="right">80.7%</td>
</tr>
<tr>
<td align="left">COMPARE_OP</td>
<td align="right">2,531,462</td>
<td align="right">9.5%</td>
</tr>
<tr>
<td align="left">TO_BOOL_LIST</td>
<td align="right">1,234,762</td>
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
<td align="right">15,051,586</td>
<td align="right">56.7%</td>
</tr>
<tr>
<td align="left">RETURN_VALUE</td>
<td align="right">8,914,785</td>
<td align="right">33.6%</td>
</tr>
<tr>
<td align="left">STORE_FAST</td>
<td align="right">1,004,020</td>
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
<td align="right">60,573</td>
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
<td align="right">23,973</td>
<td align="right">26.9%</td>
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
<td align="right">388,880,420</td>
<td align="right">98.9%</td>
</tr>
<tr>
<td align="left">END_ASYNC_FOR</td>
<td align="right">3,932,100</td>
<td align="right">1.0%</td>
</tr>
<tr>
<td align="left">POP_EXCEPT</td>
<td align="right">212,857</td>
<td align="right">0.1%</td>
</tr>
<tr>
<td align="left">EXTENDED_ARG</td>
<td align="right">88,194</td>
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
<td align="right">383,241,760</td>
<td align="right">97.5%</td>
</tr>
<tr>
<td align="left">SEND</td>
<td align="right">5,638,660</td>
<td align="right">1.4%</td>
</tr>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">4,069,985</td>
<td align="right">1.0%</td>
</tr>
<tr>
<td align="left">LOAD_GLOBAL_BUILTIN</td>
<td align="right">81,390</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">NOP</td>
<td align="right">34,947</td>
<td align="right">0.0%</td>
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
<td align="right">25.8%</td>
</tr>
<tr>
<td align="left">BUILD_TUPLE</td>
<td align="right">23,077,079</td>
<td align="right">24.7%</td>
</tr>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">14,499,109</td>
<td align="right">15.5%</td>
</tr>
<tr>
<td align="left">RETURN_GENERATOR</td>
<td align="right">13,436,640</td>
<td align="right">14.4%</td>
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
<td align="right">93,175,197</td>
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
<tr>
<td align="left">INSTRUMENTED_JUMP_BACKWARD</td>
<td align="right">300</td>
<td align="right">0.0%</td>
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
<td align="right">13,979,898</td>
<td align="right">58.1%</td>
</tr>
<tr>
<td align="left">CALL_FUNCTION_EX</td>
<td align="right">4,668,999</td>
<td align="right">19.4%</td>
</tr>
<tr>
<td align="left">CALL_PY_EXACT_ARGS</td>
<td align="right">2,444,894</td>
<td align="right">10.2%</td>
</tr>
<tr>
<td align="left">CACHE</td>
<td align="right">1,127,082</td>
<td align="right">4.7%</td>
</tr>
<tr>
<td align="left">CALL_BOUND_METHOD_EXACT_ARGS</td>
<td align="right">662,441</td>
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
<td align="left">MAKE_CELL</td>
<td align="right">13,979,898</td>
<td align="right">58.1%</td>
</tr>
<tr>
<td align="left">RESUME_CHECK</td>
<td align="right">9,519,530</td>
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
<td align="left">CALL</td>
<td align="right">138,474</td>
<td align="right">10.4%</td>
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
<td align="right">894,474</td>
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
<td align="right">960,720</td>
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
<td align="right">514,620</td>
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
<td align="right">66,943,378</td>
<td align="right">99.9%</td>
</tr>
<tr>
<td align="left">SET_FUNCTION_ATTRIBUTE</td>
<td align="right">43,650</td>
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
<td align="right">60,873,107</td>
<td align="right">90.9%</td>
</tr>
<tr>
<td align="left">STORE_FAST</td>
<td align="right">4,570,115</td>
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
<td align="right">87,654</td>
<td align="right">0.1%</td>
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
<td align="right">54.9%</td>
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
<td align="right">14,556,268</td>
<td align="right">29.8%</td>
</tr>
<tr>
<td align="left">LOAD_FAST_LOAD_FAST</td>
<td align="right">13,438,080</td>
<td align="right">27.5%</td>
</tr>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">8,721,146</td>
<td align="right">17.8%</td>
</tr>
<tr>
<td align="left">LOAD_CONST</td>
<td align="right">4,516,620</td>
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
<td align="right">349,743,300</td>
<td align="right">76.3%</td>
</tr>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">64,839,122</td>
<td align="right">14.2%</td>
</tr>
<tr>
<td align="left">RETURN_VALUE</td>
<td align="right">17,287,200</td>
<td align="right">3.8%</td>
</tr>
<tr>
<td align="left">BINARY_OP_MULTIPLY_INT</td>
<td align="right">8,437,640</td>
<td align="right">1.8%</td>
</tr>
<tr>
<td align="left">BINARY_OP</td>
<td align="right">7,899,100</td>
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
<td align="left">STORE_FAST</td>
<td align="right">163,339,852</td>
<td align="right">35.6%</td>
</tr>
<tr>
<td align="left">SWAP</td>
<td align="right">116,640,000</td>
<td align="right">25.5%</td>
</tr>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">68,482,680</td>
<td align="right">14.9%</td>
</tr>
<tr>
<td align="left">RETURN_VALUE</td>
<td align="right">31,350,960</td>
<td align="right">6.8%</td>
</tr>
<tr>
<td align="left">LOAD_FAST_LOAD_FAST</td>
<td align="right">29,370,480</td>
<td align="right">6.4%</td>
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
<td align="right">65,985,463</td>
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
<td align="right">5,995,730</td>
<td align="right">5.1%</td>
</tr>
<tr>
<td align="left">LOAD_GLOBAL_MODULE</td>
<td align="right">3,632,182</td>
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
<td align="right">47,985,723</td>
<td align="right">40.9%</td>
</tr>
<tr>
<td align="left">POP_JUMP_IF_TRUE</td>
<td align="right">38,440,740</td>
<td align="right">32.8%</td>
</tr>
<tr>
<td align="left">POP_JUMP_IF_FALSE</td>
<td align="right">30,770,957</td>
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
<td align="right">383,241,760</td>
<td align="right">78.5%</td>
</tr>
<tr>
<td align="left">LOAD_CONST</td>
<td align="right">104,762,396</td>
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
<td align="right">383,235,380</td>
<td align="right">78.5%</td>
</tr>
<tr>
<td align="left">POP_TOP</td>
<td align="right">104,756,016</td>
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
<td align="right">80.5%</td>
</tr>
<tr>
<td align="left">CALL</td>
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
<td align="left">POP_EXCEPT</td>
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
<td align="right">38,596</td>
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
<td align="right">56,016,326</td>
<td align="right">86.0%</td>
</tr>
<tr>
<td align="left">LOAD_FAST_LOAD_FAST</td>
<td align="right">5,996,787</td>
<td align="right">9.2%</td>
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
<td align="right">185,788</td>
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
<td align="right">33,188,072</td>
<td align="right">50.9%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_METHOD_NO_DICT</td>
<td align="right">8,386,500</td>
<td align="right">12.9%</td>
</tr>
<tr>
<td align="left">CONTAINS_OP_DICT</td>
<td align="right">5,562,060</td>
<td align="right">8.5%</td>
</tr>
<tr>
<td align="left">CALL_BUILTIN_O</td>
<td align="right">4,068,311</td>
<td align="right">6.2%</td>
</tr>
<tr>
<td align="left">CALL_PY_EXACT_ARGS</td>
<td align="right">3,272,720</td>
<td align="right">5.0%</td>
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
<td align="right">92.0%</td>
</tr>
<tr>
<td align="left">LOAD_CONST</td>
<td align="right">5,516,100</td>
<td align="right">7.0%</td>
</tr>
<tr>
<td align="left">BUILD_SLICE</td>
<td align="right">498,660</td>
<td align="right">0.6%</td>
</tr>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">285,671</td>
<td align="right">0.4%</td>
</tr>
<tr>
<td align="left">CALL</td>
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
<td align="right">68.6%</td>
</tr>
<tr>
<td align="left">LOAD_CONST</td>
<td align="right">18,106,751</td>
<td align="right">22.8%</td>
</tr>
<tr>
<td align="left">JUMP_FORWARD</td>
<td align="right">5,280,960</td>
<td align="right">6.7%</td>
</tr>
<tr>
<td align="left">JUMP_BACKWARD</td>
<td align="right">984,900</td>
<td align="right">1.2%</td>
</tr>
<tr>
<td align="left">RETURN_CONST</td>
<td align="right">345,600</td>
<td align="right">0.4%</td>
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
<td align="right">214,970,878</td>
<td align="right">82.2%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_WITH_HINT</td>
<td align="right">17,832,560</td>
<td align="right">6.8%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_INSTANCE_VALUE</td>
<td align="right">13,667,638</td>
<td align="right">5.2%</td>
</tr>
<tr>
<td align="left">COPY</td>
<td align="right">12,969,540</td>
<td align="right">5.0%</td>
</tr>
<tr>
<td align="left">LOAD_FAST_LOAD_FAST</td>
<td align="right">1,260,540</td>
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
<td align="right">74,164,640</td>
<td align="right">28.3%</td>
</tr>
<tr>
<td align="left">STORE_FAST</td>
<td align="right">41,834,820</td>
<td align="right">16.0%</td>
</tr>
<tr>
<td align="left">COMPARE_OP_INT</td>
<td align="right">33,678,720</td>
<td align="right">12.9%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_METHOD_WITH_VALUES</td>
<td align="right">23,298,672</td>
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
<td align="right">8,002,376</td>
<td align="right">27.1%</td>
</tr>
<tr>
<td align="left">LOAD_GLOBAL_MODULE</td>
<td align="right">3,041,395</td>
<td align="right">10.3%</td>
</tr>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">1,871,932</td>
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
<td align="right">2,640</td>
<td align="right">30.8%</td>
</tr>
<tr>
<td align="left">SET_FUNCTION_ATTRIBUTE</td>
<td align="right">2,520</td>
<td align="right">29.4%</td>
</tr>
<tr>
<td align="left">LOAD_NAME</td>
<td align="right">1,320</td>
<td align="right">15.4%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR</td>
<td align="right">1,200</td>
<td align="right">14.0%</td>
</tr>
<tr>
<td align="left">MAKE_FUNCTION</td>
<td align="right">540</td>
<td align="right">6.3%</td>
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
<td align="right">2,760</td>
<td align="right">32.2%</td>
</tr>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">2,520</td>
<td align="right">29.4%</td>
</tr>
<tr>
<td align="left">RETURN_CONST</td>
<td align="right">1,740</td>
<td align="right">20.3%</td>
</tr>
<tr>
<td align="left">LOAD_LOCALS</td>
<td align="right">1,200</td>
<td align="right">14.0%</td>
</tr>
<tr>
<td align="left">LOAD_NAME</td>
<td align="right">240</td>
<td align="right">2.8%</td>
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
<td align="right">15,742,446</td>
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
<td align="right">500</td>
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
<td align="right">3,772,532</td>
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
<td align="right">60.8%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_INSTANCE_VALUE</td>
<td align="right">119,363,280</td>
<td align="right">12.9%</td>
</tr>
<tr>
<td align="left">BINARY_SUBSCR</td>
<td align="right">115,701,000</td>
<td align="right">12.5%</td>
</tr>
<tr>
<td align="left">LOAD_FAST_LOAD_FAST</td>
<td align="right">71,527,020</td>
<td align="right">7.8%</td>
</tr>
<tr>
<td align="left">CALL_BUILTIN_CLASS</td>
<td align="right">24,782,880</td>
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
<td align="left">BINARY_OP_ADD_FLOAT</td>
<td align="right">349,743,300</td>
<td align="right">37.9%</td>
</tr>
<tr>
<td align="left">YIELD_VALUE</td>
<td align="right">210,931,680</td>
<td align="right">22.9%</td>
</tr>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">122,666,580</td>
<td align="right">13.3%</td>
</tr>
<tr>
<td align="left">BINARY_OP_SUBTRACT_FLOAT</td>
<td align="right">109,285,680</td>
<td align="right">11.8%</td>
</tr>
<tr>
<td align="left">LOAD_FAST_LOAD_FAST</td>
<td align="right">41,721,880</td>
<td align="right">4.5%</td>
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
<td align="right">3,317,736</td>
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
<td align="right">27,464,256</td>
<td align="right">100.0%</td>
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
<td align="left">CACHE</td>
<td align="right">58,268,760</td>
<td align="right">80.0%</td>
</tr>
<tr>
<td align="left">CALL_PY_EXACT_ARGS</td>
<td align="right">14,572,740</td>
<td align="right">20.0%</td>
</tr>
<tr>
<td align="left">RESUME_CHECK</td>
<td align="right">780</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">INSTRUMENTED_RESUME</td>
<td align="right">660</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">RESUME</td>
<td align="right">300</td>
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
<td align="left">LOAD_GLOBAL</td>
<td align="right">58,272,600</td>
<td align="right">80.0%</td>
</tr>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">14,569,320</td>
<td align="right">20.0%</td>
</tr>
<tr>
<td align="left">RESUME</td>
<td align="right">960</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">INSTRUMENTED_RESUME</td>
<td align="right">660</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">LOAD_CONST</td>
<td align="right">180</td>
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
<td align="left">LOAD_ATTR_INSTANCE_VALUE</td>
<td align="right">58,268,760</td>
<td align="right">80.0%</td>
</tr>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">7,285,500</td>
<td align="right">10.0%</td>
</tr>
<tr>
<td align="left">BINARY_OP_ADD_INT</td>
<td align="right">7,283,520</td>
<td align="right">10.0%</td>
</tr>
<tr>
<td align="left">BINARY_SLICE</td>
<td align="right">540</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">INSTRUMENTED_RETURN_VALUE</td>
<td align="right">480</td>
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
<td align="left">INTERPRETER_EXIT</td>
<td align="right">58,268,700</td>
<td align="right">80.0%</td>
</tr>
<tr>
<td align="left">BINARY_OP_ADD_INT</td>
<td align="right">7,283,520</td>
<td align="right">10.0%</td>
</tr>
<tr>
<td align="left">LOAD_GLOBAL_MODULE</td>
<td align="right">7,283,520</td>
<td align="right">10.0%</td>
</tr>
<tr>
<td align="left">STORE_FAST</td>
<td align="right">2,580</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">CALL_PY_EXACT_ARGS</td>
<td align="right">480</td>
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
<td align="left">INSTRUMENTED_POP_JUMP_IF_FALSE</td>
<td align="right">1,020</td>
<td align="right">60.7%</td>
</tr>
<tr>
<td align="left">POP_TOP</td>
<td align="right">300</td>
<td align="right">17.9%</td>
</tr>
<tr>
<td align="left">INSTRUMENTED_FOR_ITER</td>
<td align="right">240</td>
<td align="right">14.3%</td>
</tr>
<tr>
<td align="left">CALL_LIST_APPEND</td>
<td align="right">60</td>
<td align="right">3.6%</td>
</tr>
<tr>
<td align="left">STORE_GLOBAL</td>
<td align="right">60</td>
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
<td align="left">STORE_FAST</td>
<td align="right">1,020</td>
<td align="right">60.7%</td>
</tr>
<tr>
<td align="left">TO_BOOL_BOOL</td>
<td align="right">400</td>
<td align="right">23.8%</td>
</tr>
<tr>
<td align="left">POP_TOP</td>
<td align="right">180</td>
<td align="right">10.7%</td>
</tr>
<tr>
<td align="left">INTERPRETER_EXIT</td>
<td align="right">60</td>
<td align="right">3.6%</td>
</tr>
<tr>
<td align="left">TO_BOOL</td>
<td align="right">20</td>
<td align="right">1.2%</td>
</tr>
</tbody>
</table>


</details>

### INSTRUMENTED_FOR_ITER

<details>
<summary> Successors and predecessors for INSTRUMENTED_FOR_ITER </summary>

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
<td align="left">INSTRUMENTED_JUMP_BACKWARD</td>
<td align="right">1,314</td>
<td align="right">56.3%</td>
</tr>
<tr>
<td align="left">GET_ITER</td>
<td align="right">960</td>
<td align="right">41.1%</td>
</tr>
<tr>
<td align="left">SWAP</td>
<td align="right">60</td>
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
<td align="left">STORE_FAST</td>
<td align="right">1,434</td>
<td align="right">61.4%</td>
</tr>
<tr>
<td align="left">LOAD_CONST</td>
<td align="right">240</td>
<td align="right">10.3%</td>
</tr>
<tr>
<td align="left">UNPACK_SEQUENCE_TWO_TUPLE</td>
<td align="right">240</td>
<td align="right">10.3%</td>
</tr>
<tr>
<td align="left">INSTRUMENTED_RETURN_CONST</td>
<td align="right">240</td>
<td align="right">10.3%</td>
</tr>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">120</td>
<td align="right">5.1%</td>
</tr>
</tbody>
</table>


</details>

### INSTRUMENTED_JUMP_FORWARD

<details>
<summary> Successors and predecessors for INSTRUMENTED_JUMP_FORWARD </summary>

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
<td align="right">14,567,640</td>
<td align="right">100.0%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR</td>
<td align="right">240</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">240</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">STORE_ATTR</td>
<td align="right">180</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">STORE_ATTR_INSTANCE_VALUE</td>
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
<td align="right">14,567,580</td>
<td align="right">100.0%</td>
</tr>
<tr>
<td align="left">STORE_FAST</td>
<td align="right">480</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">LOAD_GLOBAL</td>
<td align="right">300</td>
<td align="right">0.0%</td>
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
<td align="left">STORE_FAST</td>
<td align="right">2,700</td>
<td align="right">63.5%</td>
</tr>
<tr>
<td align="left">INSTRUMENTED_POP_JUMP_IF_TRUE</td>
<td align="right">894</td>
<td align="right">21.0%</td>
</tr>
<tr>
<td align="left">LIST_APPEND</td>
<td align="right">300</td>
<td align="right">7.1%</td>
</tr>
<tr>
<td align="left">INSTRUMENTED_POP_JUMP_IF_FALSE</td>
<td align="right">300</td>
<td align="right">7.1%</td>
</tr>
<tr>
<td align="left">POP_TOP</td>
<td align="right">60</td>
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
<td align="left">LOAD_FAST</td>
<td align="right">2,940</td>
<td align="right">69.1%</td>
</tr>
<tr>
<td align="left">INSTRUMENTED_FOR_ITER</td>
<td align="right">1,314</td>
<td align="right">30.9%</td>
</tr>
</tbody>
</table>


</details>

### INSTRUMENTED_POP_JUMP_IF_TRUE

<details>
<summary> Successors and predecessors for INSTRUMENTED_POP_JUMP_IF_TRUE </summary>

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
<td align="left">COMPARE_OP_STR</td>
<td align="right">14,567,580</td>
<td align="right">50.0%</td>
</tr>
<tr>
<td align="left">TO_BOOL</td>
<td align="right">14,567,100</td>
<td align="right">50.0%</td>
</tr>
<tr>
<td align="left">TO_BOOL_BOOL</td>
<td align="right">7,494</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">TO_BOOL_STR</td>
<td align="right">720</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">TO_BOOL_NONE</td>
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
<td align="left">LOAD_FAST</td>
<td align="right">14,571,000</td>
<td align="right">50.0%</td>
</tr>
<tr>
<td align="left">LOAD_GLOBAL</td>
<td align="right">14,567,760</td>
<td align="right">50.0%</td>
</tr>
<tr>
<td align="left">NOP</td>
<td align="right">2,700</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">INSTRUMENTED_JUMP_BACKWARD</td>
<td align="right">894</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">LOAD_FAST_LOAD_FAST</td>
<td align="right">420</td>
<td align="right">0.0%</td>
</tr>
</tbody>
</table>


</details>

### INSTRUMENTED_POP_JUMP_IF_FALSE

<details>
<summary> Successors and predecessors for INSTRUMENTED_POP_JUMP_IF_FALSE </summary>

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
<td align="right">145,675,980</td>
<td align="right">41.7%</td>
</tr>
<tr>
<td align="left">EXTENDED_ARG</td>
<td align="right">72,839,040</td>
<td align="right">20.8%</td>
</tr>
<tr>
<td align="left">CONTAINS_OP</td>
<td align="right">58,268,820</td>
<td align="right">16.7%</td>
</tr>
<tr>
<td align="left">COMPARE_OP_STR</td>
<td align="right">43,710,360</td>
<td align="right">12.5%</td>
</tr>
<tr>
<td align="left">TO_BOOL_NONE</td>
<td align="right">14,568,120</td>
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
<td align="left">LOAD_FAST</td>
<td align="right">327,768,960</td>
<td align="right">93.7%</td>
</tr>
<tr>
<td align="left">LOAD_CONST</td>
<td align="right">14,567,760</td>
<td align="right">4.2%</td>
</tr>
<tr>
<td align="left">LOAD_GLOBAL</td>
<td align="right">7,284,380</td>
<td align="right">2.1%</td>
</tr>
<tr>
<td align="left">LOAD_FAST_LOAD_FAST</td>
<td align="right">11,040</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">INSTRUMENTED_RETURN_CONST</td>
<td align="right">1,020</td>
<td align="right">0.0%</td>
</tr>
</tbody>
</table>


</details>

### INSTRUMENTED_POP_JUMP_IF_NONE

<details>
<summary> Successors and predecessors for INSTRUMENTED_POP_JUMP_IF_NONE </summary>

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
<td align="right">29,134,200</td>
<td align="right">66.7%</td>
</tr>
<tr>
<td align="left">LOAD_GLOBAL</td>
<td align="right">14,567,340</td>
<td align="right">33.3%</td>
</tr>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">540</td>
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
<td align="right">43,702,080</td>
<td align="right">100.0%</td>
</tr>
</tbody>
</table>


</details>

### INSTRUMENTED_POP_JUMP_IF_NOT_NONE

<details>
<summary> Successors and predecessors for INSTRUMENTED_POP_JUMP_IF_NOT_NONE </summary>

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
<td align="right">3,420</td>
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
<td align="left">LOAD_FAST</td>
<td align="right">3,420</td>
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
<td align="right">1,003,226,673</td>
<td align="right">21.2%</td>
</tr>
<tr>
<td align="left">
hit
<details>
<summary>ⓘ</summary>

Specialized instructions that complete.
</details>
</td>
<td align="right">3,726,661,022</td>
<td align="right">78.8%</td>
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
<td align="right">714,296</td>
<td align="right">38.5%</td>
</tr>
<tr>
<td align="left">Failure</td>
<td align="right">1,143,092</td>
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
<td align="right">581,070</td>
<td align="right">50.8%</td>
</tr>
<tr>
<td align="left">multiply different types</td>
<td align="right">173,488</td>
<td align="right">15.2%</td>
</tr>
<tr>
<td align="left">add different types</td>
<td align="right">153,473</td>
<td align="right">13.4%</td>
</tr>
<tr>
<td align="left">remainder</td>
<td align="right">38,490</td>
<td align="right">3.4%</td>
</tr>
<tr>
<td align="left">floor divide</td>
<td align="right">32,640</td>
<td align="right">2.9%</td>
</tr>
<tr>
<td align="left">and int</td>
<td align="right">32,128</td>
<td align="right">2.8%</td>
</tr>
<tr>
<td align="left">add other</td>
<td align="right">24,444</td>
<td align="right">2.1%</td>
</tr>
<tr>
<td align="left">rshift</td>
<td align="right">23,040</td>
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
<td align="right">17,080</td>
<td align="right">1.5%</td>
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
<td align="right">0.4%</td>
</tr>
<tr>
<td align="left">or</td>
<td align="right">4,767</td>
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
<td align="right">973</td>
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
<td align="right">1,183,852,260</td>
<td align="right">44.6%</td>
</tr>
<tr>
<td align="left">
hit
<details>
<summary>ⓘ</summary>

Specialized instructions that complete.
</details>
</td>
<td align="right">1,471,933,970</td>
<td align="right">55.4%</td>
</tr>
<tr>
<td align="left">
miss
<details>
<summary>ⓘ</summary>

Specialized instructions that deopt.
</details>
</td>
<td align="right">3,379,585</td>
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
<td align="right">65,438</td>
<td align="right">17.8%</td>
</tr>
<tr>
<td align="left">Failure</td>
<td align="right">301,403</td>
<td align="right">82.2%</td>
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
<td align="right">154,460</td>
<td align="right">51.2%</td>
</tr>
<tr>
<td align="left">other</td>
<td align="right">77,922</td>
<td align="right">25.9%</td>
</tr>
<tr>
<td align="left">buffer int</td>
<td align="right">27,521</td>
<td align="right">9.1%</td>
</tr>
<tr>
<td align="left">list slice</td>
<td align="right">25,520</td>
<td align="right">8.5%</td>
</tr>
<tr>
<td align="left">out of range</td>
<td align="right">12,840</td>
<td align="right">4.3%</td>
</tr>
<tr>
<td align="left">sequence int</td>
<td align="right">2,920</td>
<td align="right">1.0%</td>
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
<td align="right">665,742,191</td>
<td align="right">9.1%</td>
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
<td align="right">6,637,117,186</td>
<td align="right">90.9%</td>
</tr>
<tr>
<td align="left">
miss
<details>
<summary>ⓘ</summary>

Specialized instructions that deopt.
</details>
</td>
<td align="right">113,245,336</td>
<td align="right">1.6%</td>
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
<td align="right">2,175,202</td>
<td align="right">90.2%</td>
</tr>
<tr>
<td align="left">Failure</td>
<td align="right">236,873</td>
<td align="right">9.8%</td>
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
<td align="left">meth descr method fastcall keywords</td>
<td align="right">58,140</td>
<td align="right">24.5%</td>
</tr>
<tr>
<td align="left">code complex parameters</td>
<td align="right">51,032</td>
<td align="right">21.5%</td>
</tr>
<tr>
<td align="left">init not inline values</td>
<td align="right">29,260</td>
<td align="right">12.4%</td>
</tr>
<tr>
<td align="left">cfunc noargs</td>
<td align="right">18,916</td>
<td align="right">8.0%</td>
</tr>
<tr>
<td align="left">class no vectorcall</td>
<td align="right">15,200</td>
<td align="right">6.4%</td>
</tr>
<tr>
<td align="left">cfunc varargs keywords</td>
<td align="right">12,176</td>
<td align="right">5.1%</td>
</tr>
<tr>
<td align="left">metaclass</td>
<td align="right">9,937</td>
<td align="right">4.2%</td>
</tr>
<tr>
<td align="left">other</td>
<td align="right">9,254</td>
<td align="right">3.9%</td>
</tr>
<tr>
<td align="left">class mutable</td>
<td align="right">5,796</td>
<td align="right">2.4%</td>
</tr>
<tr>
<td align="left">meth descr varargs keywords</td>
<td align="right">5,264</td>
<td align="right">2.2%</td>
</tr>
<tr>
<td align="left">bound method</td>
<td align="right">3,978</td>
<td align="right">1.7%</td>
</tr>
<tr>
<td align="left">cmethod</td>
<td align="right">3,900</td>
<td align="right">1.6%</td>
</tr>
<tr>
<td align="left">cfunc varargs</td>
<td align="right">3,460</td>
<td align="right">1.5%</td>
</tr>
<tr>
<td align="left">init not simple</td>
<td align="right">3,140</td>
<td align="right">1.3%</td>
</tr>
<tr>
<td align="left">wrong number arguments</td>
<td align="right">2,060</td>
<td align="right">0.9%</td>
</tr>
<tr>
<td align="left">meth descr varargs</td>
<td align="right">1,940</td>
<td align="right">0.8%</td>
</tr>
<tr>
<td align="left">init not python</td>
<td align="right">1,220</td>
<td align="right">0.5%</td>
</tr>
<tr>
<td align="left">str</td>
<td align="right">1,040</td>
<td align="right">0.4%</td>
</tr>
<tr>
<td align="left">operator wrapper</td>
<td align="right">1,040</td>
<td align="right">0.4%</td>
</tr>
<tr>
<td align="left">method wrapper</td>
<td align="right">80</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">out of versions</td>
<td align="right">40</td>
<td align="right">0.0%</td>
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
<td align="right">143,437,334</td>
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
<td align="right">1,635,908,031</td>
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
<td align="right">966,611</td>
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
<td align="right">21,964</td>
<td align="right">19.2%</td>
</tr>
<tr>
<td align="left">Failure</td>
<td align="right">92,679</td>
<td align="right">80.8%</td>
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
<td align="right">25,301</td>
<td align="right">27.3%</td>
</tr>
<tr>
<td align="left">big int</td>
<td align="right">22,194</td>
<td align="right">23.9%</td>
</tr>
<tr>
<td align="left">float long</td>
<td align="right">13,248</td>
<td align="right">14.3%</td>
</tr>
<tr>
<td align="left">string</td>
<td align="right">7,040</td>
<td align="right">7.6%</td>
</tr>
<tr>
<td align="left">set</td>
<td align="right">6,663</td>
<td align="right">7.2%</td>
</tr>
<tr>
<td align="left">other</td>
<td align="right">6,236</td>
<td align="right">6.7%</td>
</tr>
<tr>
<td align="left">baseobject</td>
<td align="right">6,202</td>
<td align="right">6.7%</td>
</tr>
<tr>
<td align="left">tuple</td>
<td align="right">3,380</td>
<td align="right">3.6%</td>
</tr>
<tr>
<td align="left">bool</td>
<td align="right">1,555</td>
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
<td align="right">173,337,562</td>
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
<td align="right">503,236,981</td>
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
<td align="right">50,738</td>
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
<td align="right">28,280</td>
<td align="right">55.7%</td>
</tr>
<tr>
<td align="left">list</td>
<td align="right">12,040</td>
<td align="right">23.7%</td>
</tr>
<tr>
<td align="left">other</td>
<td align="right">6,087</td>
<td align="right">12.0%</td>
</tr>
<tr>
<td align="left">tuple</td>
<td align="right">4,331</td>
<td align="right">8.5%</td>
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
<td align="right">471,626,253</td>
<td align="right">20.2%</td>
</tr>
<tr>
<td align="left">
hit
<details>
<summary>ⓘ</summary>

Specialized instructions that complete.
</details>
</td>
<td align="right">1,859,052,948</td>
<td align="right">79.7%</td>
</tr>
<tr>
<td align="left">
miss
<details>
<summary>ⓘ</summary>

Specialized instructions that deopt.
</details>
</td>
<td align="right">129,683,455</td>
<td align="right">5.6%</td>
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
<td align="right">2,447,236</td>
<td align="right">94.7%</td>
</tr>
<tr>
<td align="left">Failure</td>
<td align="right">138,213</td>
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
<td align="right">57,628</td>
<td align="right">41.7%</td>
</tr>
<tr>
<td align="left">enumerate</td>
<td align="right">21,041</td>
<td align="right">15.2%</td>
</tr>
<tr>
<td align="left">seq iter</td>
<td align="right">20,300</td>
<td align="right">14.7%</td>
</tr>
<tr>
<td align="left">set</td>
<td align="right">11,604</td>
<td align="right">8.4%</td>
</tr>
<tr>
<td align="left">other</td>
<td align="right">9,820</td>
<td align="right">7.1%</td>
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
<td align="right">1,520</td>
<td align="right">1.1%</td>
</tr>
<tr>
<td align="left">reversed list</td>
<td align="right">660</td>
<td align="right">0.5%</td>
</tr>
<tr>
<td align="left">map</td>
<td align="right">80</td>
<td align="right">0.1%</td>
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
<td align="right">1,518,596,180</td>
<td align="right">15.7%</td>
</tr>
<tr>
<td align="left">
hit
<details>
<summary>ⓘ</summary>

Specialized instructions that complete.
</details>
</td>
<td align="right">8,137,414,794</td>
<td align="right">84.2%</td>
</tr>
<tr>
<td align="left">
miss
<details>
<summary>ⓘ</summary>

Specialized instructions that deopt.
</details>
</td>
<td align="right">492,868,488</td>
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
<td align="right">9,348,677</td>
<td align="right">87.1%</td>
</tr>
<tr>
<td align="left">Failure</td>
<td align="right">1,389,590</td>
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
<td align="right">623,527</td>
<td align="right">44.9%</td>
</tr>
<tr>
<td align="left">class attr simple</td>
<td align="right">510,145</td>
<td align="right">36.7%</td>
</tr>
<tr>
<td align="left">metaclass attribute</td>
<td align="right">113,021</td>
<td align="right">8.1%</td>
</tr>
<tr>
<td align="left">method</td>
<td align="right">54,909</td>
<td align="right">4.0%</td>
</tr>
<tr>
<td align="left">shadowed</td>
<td align="right">36,440</td>
<td align="right">2.6%</td>
</tr>
<tr>
<td align="left">mutable class</td>
<td align="right">19,763</td>
<td align="right">1.4%</td>
</tr>
<tr>
<td align="left">overridden</td>
<td align="right">7,749</td>
<td align="right">0.6%</td>
</tr>
<tr>
<td align="left">class method obj</td>
<td align="right">6,804</td>
<td align="right">0.5%</td>
</tr>
<tr>
<td align="left">class attr descriptor</td>
<td align="right">6,040</td>
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
<td align="left">module attr not found</td>
<td align="right">1,400</td>
<td align="right">0.1%</td>
</tr>
<tr>
<td align="left">non overriding descriptor</td>
<td align="right">1,092</td>
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
<td align="right">80,152,846</td>
<td align="right">1.4%</td>
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
<td align="right">5,521,631,322</td>
<td align="right">98.6%</td>
</tr>
<tr>
<td align="left">
miss
<details>
<summary>ⓘ</summary>

Specialized instructions that deopt.
</details>
</td>
<td align="right">15,100</td>
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
<td align="right">43,063</td>
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
<td align="right">45,857,692</td>
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
<td align="right">487,991,396</td>
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
<td align="right">124,066,393</td>
<td align="right">9.3%</td>
</tr>
<tr>
<td align="left">
hit
<details>
<summary>ⓘ</summary>

Specialized instructions that complete.
</details>
</td>
<td align="right">1,202,241,344</td>
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
<td align="right">76,811,466</td>
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
<td align="right">1,463,692</td>
<td align="right">98.2%</td>
</tr>
<tr>
<td align="left">Failure</td>
<td align="right">26,348</td>
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
<td align="right">12,180</td>
<td align="right">46.2%</td>
</tr>
<tr>
<td align="left">overriding descriptor</td>
<td align="right">5,660</td>
<td align="right">21.5%</td>
</tr>
<tr>
<td align="left">not in dict</td>
<td align="right">3,000</td>
<td align="right">11.4%</td>
</tr>
<tr>
<td align="left">non string or split</td>
<td align="right">1,320</td>
<td align="right">5.0%</td>
</tr>
<tr>
<td align="left">no dict</td>
<td align="right">1,040</td>
<td align="right">3.9%</td>
</tr>
<tr>
<td align="left">property</td>
<td align="right">940</td>
<td align="right">3.6%</td>
</tr>
<tr>
<td align="left">not in keys</td>
<td align="right">860</td>
<td align="right">3.3%</td>
</tr>
<tr>
<td align="left">not managed dict</td>
<td align="right">604</td>
<td align="right">2.3%</td>
</tr>
<tr>
<td align="left">overridden</td>
<td align="right">444</td>
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
<td align="right">312,536,861</td>
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
<td align="right">444,467,325</td>
<td align="right">58.7%</td>
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
<td align="right">80,480</td>
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
<td align="right">48,800</td>
<td align="right">60.6%</td>
</tr>
<tr>
<td align="left">dict subclass no override</td>
<td align="right">20,880</td>
<td align="right">25.9%</td>
</tr>
<tr>
<td align="left">bytearray int</td>
<td align="right">5,200</td>
<td align="right">6.5%</td>
</tr>
<tr>
<td align="left">py simple</td>
<td align="right">4,420</td>
<td align="right">5.5%</td>
</tr>
<tr>
<td align="left">out of range</td>
<td align="right">940</td>
<td align="right">1.2%</td>
</tr>
<tr>
<td align="left">other</td>
<td align="right">240</td>
<td align="right">0.3%</td>
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
<td align="right">250,882,426</td>
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
<td align="right">3,469,963,565</td>
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
<td align="right">54,874,448</td>
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
<td align="right">1,048,165</td>
<td align="right">78.0%</td>
</tr>
<tr>
<td align="left">Failure</td>
<td align="right">295,900</td>
<td align="right">22.0%</td>
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
<td align="right">128,067</td>
<td align="right">43.3%</td>
</tr>
<tr>
<td align="left">mapping</td>
<td align="right">65,055</td>
<td align="right">22.0%</td>
</tr>
<tr>
<td align="left">tuple</td>
<td align="right">61,699</td>
<td align="right">20.9%</td>
</tr>
<tr>
<td align="left">dict</td>
<td align="right">11,224</td>
<td align="right">3.8%</td>
</tr>
<tr>
<td align="left">set</td>
<td align="right">9,512</td>
<td align="right">3.2%</td>
</tr>
<tr>
<td align="left">bytes</td>
<td align="right">8,862</td>
<td align="right">3.0%</td>
</tr>
<tr>
<td align="left">sequence</td>
<td align="right">6,241</td>
<td align="right">2.1%</td>
</tr>
<tr>
<td align="left">other</td>
<td align="right">4,560</td>
<td align="right">1.5%</td>
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
<td align="right">17,177,864</td>
<td align="right">1.3%</td>
</tr>
<tr>
<td align="left">
hit
<details>
<summary>ⓘ</summary>

Specialized instructions that complete.
</details>
</td>
<td align="right">1,309,963,058</td>
<td align="right">98.7%</td>
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
<td align="right">51,200</td>
<td align="right">99.1%</td>
</tr>
<tr>
<td align="left">Failure</td>
<td align="right">448</td>
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
<td align="right">288</td>
<td align="right">64.3%</td>
</tr>
<tr>
<td align="left">other</td>
<td align="right">80</td>
<td align="right">17.9%</td>
</tr>
<tr>
<td align="left">iterator</td>
<td align="right">80</td>
<td align="right">17.9%</td>
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
<td align="right">63,825,217,452</td>
<td align="right">54.2%</td>
</tr>
<tr>
<td align="left">
Not specialized
<details>
<summary>ⓘ</summary>

Instructions that could be specialized but aren't, e.g. `LOAD_ATTR`, `BINARY_SLICE`.
</details>
</td>
<td align="right">12,234,402,786</td>
<td align="right">10.4%</td>
</tr>
<tr>
<td align="left">
Specialized hits
<details>
<summary>ⓘ</summary>

Specialized instructions, e.g. `LOAD_ATTR_MODULE` that complete.
</details>
</td>
<td align="right">40,838,732,604</td>
<td align="right">34.7%</td>
</tr>
<tr>
<td align="left">
Specialized misses
<details>
<summary>ⓘ</summary>

Specialized instructions, e.g. `LOAD_ATTR_MODULE` that deopt.
</details>
</td>
<td align="right">913,403,916</td>
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
<td align="right">1,518,596,180</td>
<td align="right">25.1%</td>
</tr>
<tr>
<td align="left">BINARY_SUBSCR</td>
<td align="right">1,183,852,260</td>
<td align="right">19.5%</td>
</tr>
<tr>
<td align="left">BINARY_OP</td>
<td align="right">1,003,226,673</td>
<td align="right">16.6%</td>
</tr>
<tr>
<td align="left">CALL</td>
<td align="right">665,742,191</td>
<td align="right">11.0%</td>
</tr>
<tr>
<td align="left">FOR_ITER</td>
<td align="right">471,626,253</td>
<td align="right">7.8%</td>
</tr>
<tr>
<td align="left">STORE_SUBSCR</td>
<td align="right">312,536,861</td>
<td align="right">5.2%</td>
</tr>
<tr>
<td align="left">TO_BOOL</td>
<td align="right">250,882,426</td>
<td align="right">4.1%</td>
</tr>
<tr>
<td align="left">CONTAINS_OP</td>
<td align="right">173,337,562</td>
<td align="right">2.9%</td>
</tr>
<tr>
<td align="left">COMPARE_OP</td>
<td align="right">143,437,334</td>
<td align="right">2.4%</td>
</tr>
<tr>
<td align="left">STORE_ATTR</td>
<td align="right">124,066,393</td>
<td align="right">2.0%</td>
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
<td align="right">172,329,875</td>
<td align="right">18.9%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_METHOD_WITH_VALUES</td>
<td align="right">170,175,957</td>
<td align="right">18.6%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_SLOT</td>
<td align="right">75,580,227</td>
<td align="right">8.3%</td>
</tr>
<tr>
<td align="left">FOR_ITER_LIST</td>
<td align="right">64,927,111</td>
<td align="right">7.1%</td>
</tr>
<tr>
<td align="left">FOR_ITER_TUPLE</td>
<td align="right">64,703,124</td>
<td align="right">7.1%</td>
</tr>
<tr>
<td align="left">STORE_ATTR_INSTANCE_VALUE</td>
<td align="right">62,518,560</td>
<td align="right">6.8%</td>
</tr>
<tr>
<td align="left">CALL_PY_EXACT_ARGS</td>
<td align="right">43,510,819</td>
<td align="right">4.8%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES</td>
<td align="right">40,582,360</td>
<td align="right">4.4%</td>
</tr>
<tr>
<td align="left">CALL_METHOD_DESCRIPTOR_FAST</td>
<td align="right">28,672,634</td>
<td align="right">3.1%</td>
</tr>
<tr>
<td align="left">TO_BOOL_NONE</td>
<td align="right">24,951,419</td>
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
<td align="right">1,240,386,598</td>
<td align="right">26.2%</td>
</tr>
<tr>
<td align="left">Calls to Python functions inlined</td>
<td align="right">3,488,070,324</td>
<td align="right">73.8%</td>
</tr>
<tr>
<td align="left">Calls via PyEval_EvalFrame (total)</td>
<td align="right">1,240,386,598</td>
<td align="right">26.2%</td>
</tr>
<tr>
<td align="left">Calls via PyEval_EvalFrame (vector)</td>
<td align="right">689,479,797</td>
<td align="right">14.6%</td>
</tr>
<tr>
<td align="left">Calls via PyEval_EvalFrame (generator)</td>
<td align="right">550,906,801</td>
<td align="right">11.7%</td>
</tr>
<tr>
<td align="left">Calls via PyEval_EvalFrame (legacy)</td>
<td align="right">3,964,200</td>
<td align="right">0.1%</td>
</tr>
<tr>
<td align="left">Calls via PyEval_EvalFrame (function vectorcall)</td>
<td align="right">685,514,277</td>
<td align="right">14.5%</td>
</tr>
<tr>
<td align="left">Calls via PyEval_EvalFrame (build class)</td>
<td align="right">1,320</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">Calls via PyEval_EvalFrame (slot)</td>
<td align="right">161,813,753</td>
<td align="right">3.4%</td>
</tr>
<tr>
<td align="left">Calls via PyEval_EvalFrame (function ex)</td>
<td align="right">16,309,174</td>
<td align="right">0.3%</td>
</tr>
<tr>
<td align="left">Calls via PyEval_EvalFrame (api)</td>
<td align="right">145,672,681</td>
<td align="right">3.1%</td>
</tr>
<tr>
<td align="left">Calls via PyEval_EvalFrame (method)</td>
<td align="right">100,735,050</td>
<td align="right">2.1%</td>
</tr>
<tr>
<td align="left">Frame objects created</td>
<td align="right">44,011,254</td>
<td align="right">0.9%</td>
</tr>
<tr>
<td align="left">Frames pushed</td>
<td align="right">2,654,113,668</td>
<td align="right">56.1%</td>
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
<td align="right">4,096,209,151</td>
<td align="right">39.6%</td>
</tr>
<tr>
<td align="left">Frees to freelist</td>
<td align="right">4,096,335,191</td>
<td align="right"></td>
</tr>
<tr>
<td align="left">Allocations</td>
<td align="right">6,253,067,702</td>
<td align="right">60.4%</td>
</tr>
<tr>
<td align="left">Allocations to 512 bytes</td>
<td align="right">6,199,501,515</td>
<td align="right">59.9%</td>
</tr>
<tr>
<td align="left">Allocations to 4 kbytes</td>
<td align="right">42,381,619</td>
<td align="right">0.4%</td>
</tr>
<tr>
<td align="left">Allocations over 4 kbytes</td>
<td align="right">11,184,568</td>
<td align="right">0.1%</td>
</tr>
<tr>
<td align="left">Frees</td>
<td align="right">6,479,160,699</td>
<td align="right"></td>
</tr>
<tr>
<td align="left">Inline values</td>
<td align="right">72,695,801</td>
<td align="right"></td>
</tr>
<tr>
<td align="left">Interpreter increfs</td>
<td align="right">44,087,614,307</td>
<td align="right">74.9%</td>
</tr>
<tr>
<td align="left">Interpreter decrefs</td>
<td align="right">52,093,241,937</td>
<td align="right">75.8%</td>
</tr>
<tr>
<td align="left">Increfs</td>
<td align="right">14,742,368,305</td>
<td align="right">25.1%</td>
</tr>
<tr>
<td align="left">Decrefs</td>
<td align="right">16,608,013,193</td>
<td align="right">24.2%</td>
</tr>
<tr>
<td align="left">Materialize dict (on request)</td>
<td align="right">4,911,240</td>
<td align="right">6.8%</td>
</tr>
<tr>
<td align="left">Materialize dict (new key)</td>
<td align="right">65,040</td>
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
<td align="right">1,704,693,869</td>
<td align="right"></td>
</tr>
<tr>
<td align="left">Method cache misses</td>
<td align="right">45,244,433</td>
<td align="right"></td>
</tr>
<tr>
<td align="left">Method cache collisions</td>
<td align="right">47,431,211</td>
<td align="right"></td>
</tr>
<tr>
<td align="left">Method cache dunder hits</td>
<td align="right">2,007,047,864</td>
<td align="right"></td>
</tr>
<tr>
<td align="left">Method cache dunder misses</td>
<td align="right">2,967,427</td>
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
<td align="right">78,314,600</td>
<td align="right">6,459,886,654</td>
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
<td align="left">
Optimization attempts
<details>
<summary>ⓘ</summary>

The number of times a potential trace is identified.  Specifically, this occurs in the JUMP BACKWARD instruction when the counter reaches a threshold.
</details>
</td>
<td align="right">0</td>
<td align="right"></td>
</tr>
<tr>
<td align="left">
Traces created
<details>
<summary>ⓘ</summary>

The number of traces that were successfully created.
</details>
</td>
<td align="right">0</td>
<td align="right"></td>
</tr>
<tr>
<td align="left">
Trace stack overflow
<details>
<summary>ⓘ</summary>

A trace is truncated because it would require more than 5 stack frames.
</details>
</td>
<td align="right">0</td>
<td align="right"></td>
</tr>
<tr>
<td align="left">
Trace stack underflow
<details>
<summary>ⓘ</summary>

A potential trace is abandoned because it pops more frames than it pushes.
</details>
</td>
<td align="right">0</td>
<td align="right"></td>
</tr>
<tr>
<td align="left">
Trace too long
<details>
<summary>ⓘ</summary>

A trace is truncated because it is longer than the instruction buffer.
</details>
</td>
<td align="right">0</td>
<td align="right"></td>
</tr>
<tr>
<td align="left">
Trace too short
<details>
<summary>ⓘ</summary>

A potential trace is abandoced because it it too short.
</details>
</td>
<td align="right">0</td>
<td align="right"></td>
</tr>
<tr>
<td align="left">
Inner loop found
<details>
<summary>ⓘ</summary>

A trace is truncated because it has an inner loop
</details>
</td>
<td align="right">0</td>
<td align="right"></td>
</tr>
<tr>
<td align="left">
Recursive call
<details>
<summary>ⓘ</summary>

A trace is truncated because it has a recursive call.
</details>
</td>
<td align="right">0</td>
<td align="right"></td>
</tr>
<tr>
<td align="left">
Low confidence
<details>
<summary>ⓘ</summary>

A trace is abandoned because the likelihood of the jump to top being taken is too low.
</details>
</td>
<td align="right">0</td>
<td align="right"></td>
</tr>
<tr>
<td align="left">
Executors invalidated
<details>
<summary>ⓘ</summary>

The number of executors that were invalidated due to watched dictionary changes.
</details>
</td>
<td align="right">0</td>
<td align="right"></td>
</tr>
<tr>
<td align="left">
Traces executed
<details>
<summary>ⓘ</summary>

The number of traces that were executed
</details>
</td>
<td align="right">0</td>
<td align="right"></td>
</tr>
<tr>
<td align="left">
Uops executed
<details>
<summary>ⓘ</summary>

The total number of uops (micro-operations) that were executed
</details>
</td>
<td align="right">0</td>
<td align="right"></td>
</tr>
</tbody>
</table>

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
<td align="left">
Optimizer attempts
<details>
<summary>ⓘ</summary>

The number of times the trace optimizer (_Py_uop_analyze_and_optimize) was run.
</details>
</td>
<td align="right">0</td>
<td align="right"></td>
</tr>
<tr>
<td align="left">
Optimizer successes
<details>
<summary>ⓘ</summary>

The number of traces that were successfully optimized.
</details>
</td>
<td align="right">0</td>
<td align="right"></td>
</tr>
<tr>
<td align="left">
Optimizer no memory
<details>
<summary>ⓘ</summary>

The number of optimizations that failed due to no memory.
</details>
</td>
<td align="right">0</td>
<td align="right"></td>
</tr>
<tr>
<td align="left">
Remove globals builtins changed
<details>
<summary>ⓘ</summary>

The builtins changed during optimization
</details>
</td>
<td align="right">0</td>
<td align="right"></td>
</tr>
<tr>
<td align="left">
Remove globals incorrect keys
<details>
<summary>ⓘ</summary>

The keys in the globals dictionary aren't what was expected
</details>
</td>
<td align="right">0</td>
<td align="right"></td>
</tr>
</tbody>
</table>

### Trace length histogram

<details>
<summary> trace length histogram </summary>

<table>
<thead>
<tr>
<th align="left">Range</th>
<th align="right">Count</th>
<th align="right">Ratio</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left"><= 1</td>
<td align="right">0</td>
<td align="right"></td>
</tr>
</tbody>
</table>


</details>

### Optimized trace length histogram

<details>
<summary> optimized trace length histogram </summary>

<table>
<thead>
<tr>
<th align="left">Range</th>
<th align="right">Count</th>
<th align="right">Ratio</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left"><= 1</td>
<td align="right">0</td>
<td align="right"></td>
</tr>
</tbody>
</table>


</details>

### Trace run length histogram

<details>
<summary> trace run length histogram </summary>

<table>
<thead>
<tr>
<th align="left">Range</th>
<th align="right">Count</th>
<th align="right">Ratio</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left"><= 1</td>
<td align="right">0</td>
<td align="right"></td>
</tr>
</tbody>
</table>


</details>

### Uop execution stats

<details>
<summary> uop execution stats </summary>


</details>

### Unsupported opcodes

<details>
<summary> unsupported opcodes </summary>


</details>

### Optimizer errored out with opcode

<details>
<summary> Optimization stopped after encountering this opcode </summary>


</details>


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
<td align="right">1,540</td>
</tr>
</tbody>
</table>


</details>

---
Stats gathered on: 2024-04-07
