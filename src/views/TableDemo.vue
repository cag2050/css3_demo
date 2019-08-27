<template>
    <div class='hello'>
        <table class="table_class">
            <tr>
                <th>dddd</th>
                <th>ffff</th>
            </tr>
            <tr v-for="(item, index) in list">
                <td class="first_td">{{ item.member_id }}</td>
                <td class="second_td" v-html="item.nickname"></td>
            </tr>
        </table>
    </div>
</template>

<style scoped>
    .table_class {
        width: 100%;
        word-break: break-all;
    }
    .first_td {
        min-width: 100px;
    }
    .second_td {
        min-width: 500px;
    }
</style>

<script>
    export default {
        name: 'hello',
        data () {
            return {
                list: [
                    {
                        'id': '185873443',
                        'member_id': '801032420801032420801032420801032420801032420801032420801032420801032420801032420801032420801032420801032420801032420801032420801032420801032420801032420801032420801032420801032420801032420801032420801032420801032420801032420801032420',
                        'nickname': '甜甜圈🍩',
                        'type': '2',
                        'create_time': '2019-08-27 16:51:05',
                        'telephone': 0,
                        'sensitive_words': [
                            {
                                'word': '甜',
                                'nature': 5,
                                'classification': 1,
                                'level': 2,
                                'group_num': 5,
                                'start': 0,
                                'end': 1,
                                'org_word': '兲',
                                'subwordpos': [[0, 1]],
                                'level_name': '严重'
                            },
                            {
                                'word': '甜',
                                'nature': 5,
                                'classification': 1,
                                'level': 2,
                                'group_num': 5,
                                'start': 1,
                                'end': 2,
                                'org_word': '兲',
                                'subwordpos': [[0, 1]],
                                'level_name': '严重'
                            },
                            {
                                'word': '圈',
                                'nature': 6,
                                'classification': 1,
                                'level': 3,
                                'group_num': 6,
                                'start': 2,
                                'end': 3,
                                'org_word': '曲案',
                                'subwordpos': [[0, 1]],
                                'level_name': '嫌疑'
                            },
                            {
                                'word': '甜',
                                'nature': 5,
                                'classification': 1,
                                'level': 2,
                                'group_num': 5,
                                'start': 0,
                                'end': 1,
                                'org_word': '兲',
                                'subwordpos': [[0, 1]],
                                'level_name': '严重'
                            },
                            {
                                'word': '甜',
                                'nature': 5,
                                'classification': 1,
                                'level': 2,
                                'group_num': 5,
                                'start': 1,
                                'end': 2,
                                'org_word': '兲',
                                'subwordpos': [[0, 1]],
                                'level_name': '严重'
                            },
                            {
                                'word': '圈',
                                'nature': 6,
                                'classification': 1,
                                'level': 3,
                                'group_num': 6,
                                'start': 2,
                                'end': 3,
                                'org_word': '曲案',
                                'subwordpos': [[0, 1]],
                                'level_name': '嫌疑'
                            }]
                    },
                    {
                        'id': '185873443',
                        'member_id': '801032420',
                        'nickname': '甜甜圈🍩',
                        'type': '2',
                        'create_time': '2019-08-27 16:51:05',
                        'telephone': 0,
                        'sensitive_words': [
                            {
                                'word': '甜',
                                'nature': 5,
                                'classification': 1,
                                'level': 2,
                                'group_num': 5,
                                'start': 0,
                                'end': 1,
                                'org_word': '兲',
                                'subwordpos': [[0, 1]],
                                'level_name': '严重'
                            },
                            {
                                'word': '甜',
                                'nature': 5,
                                'classification': 1,
                                'level': 2,
                                'group_num': 5,
                                'start': 1,
                                'end': 2,
                                'org_word': '兲',
                                'subwordpos': [[0, 1]],
                                'level_name': '严重'
                            },
                            {
                                'word': '圈',
                                'nature': 6,
                                'classification': 1,
                                'level': 3,
                                'group_num': 6,
                                'start': 2,
                                'end': 3,
                                'org_word': '曲案',
                                'subwordpos': [[0, 1]],
                                'level_name': '嫌疑'
                            },
                            {
                                'word': '甜',
                                'nature': 5,
                                'classification': 1,
                                'level': 2,
                                'group_num': 5,
                                'start': 0,
                                'end': 1,
                                'org_word': '兲',
                                'subwordpos': [[0, 1]],
                                'level_name': '严重'
                            },
                            {
                                'word': '甜',
                                'nature': 5,
                                'classification': 1,
                                'level': 2,
                                'group_num': 5,
                                'start': 1,
                                'end': 2,
                                'org_word': '兲',
                                'subwordpos': [[0, 1]],
                                'level_name': '严重'
                            },
                            {
                                'word': '圈',
                                'nature': 6,
                                'classification': 1,
                                'level': 3,
                                'group_num': 6,
                                'start': 2,
                                'end': 3,
                                'org_word': '曲案',
                                'subwordpos': [[0, 1]],
                                'level_name': '嫌疑'
                            }]
                    }
                ]
            }
        },
        methods: {}
    }
</script>
